# FlujoGIT

Documentación de flujo de trabajo remoto con Git

## Organización
Se recomienda crear una organización que sea la propietaria del repositorio principal. A partir de dicho repositorio los miembros o colaboradores podran hacer un fork hacia sus cuentas personales.

### pasos para crear una organización

1. Click foto perfil
2. Click en settings
3. click en organizations
4. Click en new Orgatization
5. Elegir plan y llenar datos

## Creación de fork
para crear un fork debes inciar sesión en GitHub y luego ingresar a la landing page del proyecto del que quieras sacar tu fork.

## Administración de remotos

Listar remotos 
git remote -v

Agregar remotos
git remote add FlujoGIT_Origin git@github.com:Cartoimagen/FlujoGIT.git

Eliminar remotos
git remote remove FlujoGIT_Origin

## Creando etiquetas

Es necesario entender que las etiquetas o releses solo deben ser creadas en la rama master del proyecto raiz.

para entender como llamar o categorizar a tus versiones te recomendamos un articulo en nuestro blog:
https://ed.team/blog/como-se-deciden-las-versiones-del-software