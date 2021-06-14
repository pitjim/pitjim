### Hi there 👋

<!--
**pitjim/pitjim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
## Configurar entorno desde cmd con git config
```
git config –-global user.name "nombre"

git config –-global user.email "tu@correo.es"
```

## ver la configuración de tu entorno cmd de git
git config --list

# Inicializar carpeta local para subir a github.
## ir a la carpeta para hacer el init de su contenido
git init
## una vez inicializada puedes añadir todo su contenido al stage
git add .
##  o archivos concretos
git add nombre_archivo
## hacer un commit inicial para confirmar los archivos añadidos con git add 
git commit -m "Inicial commit"
## para subir los archivos añadidor al stage y confirmados con el commit y antes de hacer push, hay que indicar un repositorio remoto que debe existir ya en github
git remote https://github.com/mi_nombre_usuario/mi_nombre_de_repositorio.git
## comprobar repositorio remoto con git remote
git remote -v
## cambiar el nombre de la  principal de master a main, practica buenista para eliminar terminos como master, slave, blacklist, etc...
git branch -M main
## subir el commit al con el nombre principal main desde el origen que es nuestra carpeta local 
git push -u origin main
## pedirá las credenciales para acceder al repositorio si es necesario
## comprobar el push en github.com

