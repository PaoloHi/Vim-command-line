# Vim-command-line

# Comandos Básicos de Vim

## Modos de Vim

- **Normal Mode**: Modo de navegación y ejecución de comandos.
- **Insert Mode**: Modo de edición de texto.
- **Visual Mode**: Modo de selección de texto.

## Navegación

- `h`, `j`, `k`, `l`: Moverse hacia la izquierda, abajo, arriba y derecha, respectivamente.
- `w`: Moverse a la siguiente palabra.
- `b`: Retroceder a la palabra anterior.
- `0`: Moverse al inicio de la línea.
- `$`: Moverse al final de la línea.
- `gg`: Ir al inicio del archivo.
- `G`: Ir al final del archivo.
- `:n`: Ir a la línea n (reemplazar "n" por el número de línea).
- `/{texto}`: Buscar "texto" hacia adelante.
- `?{texto}`: Buscar "texto" hacia atrás.
- `n`: Ir a la siguiente coincidencia de búsqueda.
- `N`: Ir a la coincidencia anterior de búsqueda.

## Edición

- `i`: Entrar en el modo Insert antes del cursor.
- `I`: Entrar en el modo Insert al inicio de la línea.
- `a`: Entrar en el modo Insert después del cursor.
- `A`: Entrar en el modo Insert al final de la línea.
- `o`: Agregar una nueva línea debajo.
- `O`: Agregar una nueva línea encima.
- `x`: Eliminar el carácter bajo el cursor.
- `dd`: Eliminar la línea actual.
- `yy`: Copiar la línea actual.
- `p`: Pegar el contenido copiado o cortado.

## Comandos Generales

- `:w`: Guardar el archivo.
- `:q`: Salir de Vim.
- `:q!`: Salir de Vim sin guardar cambios.
- `:wq` o `:x`: Guardar y salir.
- `:e {nombre_archivo}`: Abrir un archivo.
- `:set nu`: Mostrar números de línea.
- `:set nonu`: Ocultar números de línea.

## Manipulación de Ventanas

- `:split`: Dividir la ventana horizontalmente.
- `:vsplit`: Dividir la ventana verticalmente.
- `Ctrl-w Ctrl-w`: Cambiar entre ventanas.
- `Ctrl-w +/-`: Cambiar el tamaño de la ventana.
- `Ctrl-w =`: Igualar el tamaño de las ventanas.

## Otros Comandos Útiles

- `:help {comando}`: Obtener ayuda sobre un comando.
- `:set {opción}`: Configurar opciones de Vim.
- `:sh`: Ejecutar una shell desde Vim.
- `u`: Deshacer la última acción.
- `Ctrl-r`: Rehacer la última acción.

## Comandos de Búsqueda y Reemplazo

- `:%s/{buscar}/{reemplazar}/g`: Reemplazar todas las coincidencias en el archivo.
- `:s/{buscar}/{reemplazar}/g`: Reemplazar en la línea actual.
- `:noh`: Desactivar resaltado de búsqueda.

Recuerda que Vim tiene una amplia gama de comandos y atajos de teclado. Estos son solo algunos de los comandos básicos para comenzar a usar Vim de manera efectiva.
