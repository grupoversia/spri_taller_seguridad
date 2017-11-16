# Repositorio

Laboratorio Seguridad SPRI Enpresa Digitala - Grupo Versia

## Getting Started

Este repositorio contiene todos los playbooks para poder desplegar las herramientas vistas en el taller impartido por SPRI-Enpresa Digitala y el Basque CyberSecurity Center.
Las IPs son del rango 192.168.1.X, habría repasar los ficheros para adaptar loas IPs a otro rango.

## Prerequisitos

Es necesario tener un servidor con Ansible instalado y los servidores base instalados:

- ELK, SEC y ElastAlert está en Ubuntu.
- Doorman está en Ubuntu.
- Cerebro esta en Ubuntu.
- El AD es un Windows 2012 Server.
- También son necesarios 2 Windows 10 como clientes del AD.
- En el laboratorio también se usó un KALI para las pruebas.

Además al desplegar en sistemas Windows hay que habilitar WinRM en estos sistemas. Se puede seguir la siguiente documentación de Ansible:
http://docs.ansible.com/ansible/latest/intro_windows.html#windows-system-prep

Y además instalar el paquete de python en la máquina de Ansible:

```
pip install ansible pywinrm
```

Tras estos prerequisitos, se podrán desplegar los playbooks para configurar todos los sistemas.

## Despliegue

TODO

## Autores y contacto

* **Rubén Rodríguez - Grupo Versia** - Creación de los playbooks

