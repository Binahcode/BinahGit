# BinahGit

Documentacion de flujo de trabajo con GIT

## Organizacion

Se recomienda crear una organizacion que se la propietaria del repositorio principal.
A partir de dicho repositorio los miembros o colaboradores podran hacer un fork hacia sus cuencas
personales.

### Pasos para crear una organizacion

1. Click en tu foto de perfil (Esquina superior derecha)
2. Click en Settings
3. Click en Organizaciones(Menu izquierdo).
4. Click en Nueva Organizacion
5. Elegir plan y llenar datos.

### Creacion de Fork

Para crear un fork debes iniciar sesion en GitHub y luego ingresar a la landing page del proyecto del que quieras obtener tu Fork.

### Como trabajar con 2 o mas remotos

Listar remoros
`git remote -v`

Agregar remotos
`git remote add BinahGit git@github.com:Binahcode/BinahGit.git`

Eliminar remotos
`git remote remove BinahGit`

### Creando etiquetas

Es necesario entender que las etiquetas (o releases) solo deben ser creadas a partir de la rama master como buena practica.
Para entender como llamar o categorizar a tus versiones te recomendamos un articulo en nuestro blog: https://app.ed.team/blog/como-se-deciden-las-versiones-del-software