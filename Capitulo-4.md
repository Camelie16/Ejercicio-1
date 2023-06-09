#Repositorios remotos
*Se usan en sistemas de control de versiones descentralizado o distribuido.
*En los repositorios remotos se evita tocar el repositorio directamente, y cada desarrollador realiza repositorios locales y cada desarrollador va tener una copia local de ese repositorio.
\*Los repositorios remotos son comunmente usados en GitHub, GitLab.

Para agregar un repositorio remoto nuevo, use el comando git remote add en el terminal, dentro del directorio donde está almacenado su repositorio.

El comando git remote add toma dos argumentos:

Un nombre remoto, por ejemplo, origin
Una dirección URL remota, por ejemplo, https://github.com/OWNER/REPOSITORY.git
Por ejemplo:

$ git remote add origin https://github.com/OWNER/REPOSITORY.git

# Set a new remote

$ git remote -v

# Verify new remote

> origin https://github.com/OWNER/REPOSITORY.git (fetch)
> origin https://github.com/OWNER/REPOSITORY.git (push)
