# Mi proyecto
# 1. Inicializa un nuevo repositorio Git en un directorio llamado "mi_proyecto"
mkdir mi_proyecto
cd mi_proyecto
git init

# 2. Crea un archivo llamado "README.md" y añade algún contenido
echo "# Mi Proyecto" > README.md

# 3. Comprueba el estado de tu repositorio
git status

# 4. Añade el archivo README.md al área de preparación (staged area)
git add README.md

# 5. Realiza un commit con los cambios y un mensaje descriptivo
git commit -m "Inicialización del proyecto con README"

# 6. Visualiza el historial de commits
git log