# Entrega creando Cuenta Github

## Cuenta de Github con Gitbash:

### Comandos usados para generar  nueva llave ssh: 


$ ssh-keygen -t ed25519 -C "tu_email@ejemplo.com" --> Comando genera una llave ssh.

eval "$(ssh-agent -s)" --> inicializando agente ssh.

$ ssh-add ~/.ssh/id_ed25519 --> Agregando llave privada SSh al ssh-agent. de esta manera cada vez que se realize  una solicitud a Github verificara la clave privada con la clave publica.



#### Comandos usados de git:

git init --> Permite Inicializar un repositorio local.
git add . --> Agregamos los cambios al stage área.
git commit -m "mensaje" confirmamos los cambios para versionarlos.
git push origin main/master --> Subimos los cambios la repositorio remoto (github).





