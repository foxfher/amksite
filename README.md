<head>
    <!-- CSS Files -->
     <link href="custom.css" rel="stylesheet" />
</head>

# amksite
![title](config-amksite/title.svg)

![alt](https://img.shields.io/apm/l/vim-mode?label=license&logo=dark-green) ![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-success) ![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github) [![GitHub contributors](https://img.shields.io/github/contributors/foxfher/github-readme-quotes.svg)](https://github.com/foxfher/github-readme-quotes/graphs/contributors) ![Pull Request Counts](https://img.shields.io/bitbucket/pr/foxfher/github-readme-quotes) ![last commit](https://img.shields.io/github/last-commit/foxfher/github-readme-quotes) ![deployment-status](https://img.shields.io/website?url=https%3A%2F%2Fgithub-readme-quotes.herokuapp.com%2Fquote) [![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/foxfher/github-readme-quotes/)
 
A program to enable and disable virtual host configurations in Apache Server for debian or Arch linux.

### ![install](config-amksite/install.svg) &nbsp; Installation

Installs helpers for Apache which let you easily enable and disable sites and apps. Similar to a2ensite and a2dissite from Apache2.

To install, run this command in your terminal:
```console
$ curl https://raw.githubusercontent.com/foxfher/amksite/master/install | sh
```

### ![usage](config-amksite/usage.png)  &nbsp; Usage

```console
$ amksite
usage: amksite (-h | -l | -e | -d) [host-name]

example: amksite -e default.conf
         amksite -d default.conf
         amksite -l 

Arguments:
-h Show this help message
-l List of enabled and disabled settings.
-e Enable a configuration.
-d Disable a configuration.
host-name The hostname to operate with.
```

### Limitations

The following folders must exist:

    [✔]::[Succes]: User root.
    [✔]::[Succes]: sites-available.
    [✔]::[Succes]: sites-enabled.


###  &copy;Credits

     FILE:        amksite
     DESCRIPTION: Apache enable/disable/List site, originally written by Fernando Bello M.
     LICENSE:     Licensed under Apache License 2.0 run debian or arch Linux
     OPTIONS:     amksite (-h | -l | -e | -d) [host-name]
     AUTHOR:      Fernando Bello Mota <fbello04@hotmail.com>
     VERSION:     1.0

#### ![license](config-amksite/license.png) Licencia
![alt](https://img.shields.io/apm/l/vim-mode?label=license&logo=dark-blue&style=for-the-badge) 
```
Licencia MIT
Copyright (c) 2019 Fernando Bello Mota <fbello04@hotmail.com>
Se concede permiso por la presente, libre de cargos, a cualquier persona que obtenga una copia de este software y de los
archivos de documentación asociados (el "Software"), a utilizar el Software sin restricción, incluyendo sin limitación los
derechos a usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar, y/o vender copias del Software, y a 
permitir a las personas a las que se les proporcione el Software a hacer lo mismo, sujeto a las siguientes condiciones:
El aviso de copyright anterior y este aviso de permiso se incluirán en todas las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "COMO ESTÁ", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A
GARANTÍAS DE COMERCIALIZACIÓN, IDONEIDAD PARA UN PROPÓSITO PARTICULAR E INCUMPLIMIENTO. EN NINGÚN CASO LOS AUTORES O 
PROPIETARIOS DE LOS DERECHOS DE AUTOR SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN, DAÑOS U OTRAS RESPONSABILIDADES, YA SEA 
EN UNA ACCIÓN DE CONTRATO, AGRAVIO O CUALQUIER OTRO MOTIVO, DERIVADAS DE, FUERA DE O EN CONEXIÓN CON EL SOFTWARE O SU USO 
U OTRO TIPO DE ACCIONES EN EL SOFTWARE.
```
