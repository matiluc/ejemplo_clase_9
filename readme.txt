INICIALIZAR CREAR Y Subir

1. Inicializá Git (si no lo está):
git init

2. Agregá el archivo remoto (solo si no está):
git remote add origin https://github.com/tu-usuario/tu-repo.git

3. Agregá los archivos:
git add .

4. Commit con mensaje:
git commit -m "mensaje del commit"

5. Subí al repo (rama main):
git push -u origin main


RAMAS:

1. Ver ramas disponibles:
git branch

2. Crear nueva rama:
git checkout -b nombre-de-la-rama

3. Cambiar a una rama existente:
git checkout nombre-de-la-rama

3. Volver a la rama principal (por ejemplo main):
git checkout main

4. Subir una rama nueva a GitHub:
git push -u origin nombre-de-la-rama

5.Mergear una rama en main (estando parado en main):
git merge nombre-de-la-rama

6. (Opcional) Eliminar rama local después de mergear:
git branch -d nombre-de-la-rama

7. (Opcional) Eliminar rama en remoto:
git push origin --delete nombre-de-la-rama


CLONAR

git clone https://github.com/usuario/repositorio.git

Entrá a la carpeta clonada:
cd repositorio

Abrila en VSCode si querés:
code .