# Jenkins con Vagrant

Este proyecto permite levantar un entorno de integración continua utilizando **Jenkins** sobre una máquina virtual automatizada con **Vagrant** y **VirtualBox**.

## 📦 Tecnologías utilizadas

- [Vagrant](https://www.vagrantup.com/) - Automatización de entornos de desarrollo
- [VirtualBox](https://www.virtualbox.org/) - Virtualización
- [Jenkins](https://www.jenkins.io/) - Servidor de integración continua
- [Shell Script](https://www.gnu.org/software/bash/) - Automatización de instalación y configuración

## 🚀 Objetivo

Facilitar la configuración de un entorno Jenkins local, reproducible y aislado, ideal para pruebas, desarrollo y aprendizaje de pipelines CI/CD.

## 🛠️ Requisitos

- [Git](https://git-scm.com/)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads)

## 📥 Instalación

1. Clona este repositorio:

   ```
   git clone https://github.com/SebastianVeloza/Vagrant_Jenkins.git
   cd Vagrant_Jenkins
   ```
Inicia la máquina virtual con Vagrant:

```
vagrant up --provision
```
Esto descargará la imagen base (si es necesario), creará la VM, y ejecutará el provision.sh para instalar y configurar Jenkins automáticamente.

Accede a Jenkins desde tu navegador:

```
http://localhost:8089
```
Para obtener la contraseña inicial de Jenkins: 

la puedes ver en el ultimo log al ejecutar el vagrant up

## 🧰 Comandos útiles
| Comando                 | Descripción                                      |
|-------------------------|--------------------------------------------------|
| `vagrant up`           | Inicia la VM y ejecuta el provisionamiento       |
| `vagrant halt`         | Apaga la VM                                      |
| `vagrant destroy`      | Elimina la VM completamente                      |
| `vagrant ssh`         | Accede por SSH a la VM                           |
| `vagrant reload --provision` | Reinicia y reprovisiona la VM             |


## 🧪 Probado en
SO Host: Ubuntu 22.04 / Windows 11

Vagrant 2.4+

VirtualBox 7+

👨‍💻 Autor
Sebastian Veloza - GitHub
