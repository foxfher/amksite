# amksite
 
A program to enable and disable virtual host configurations in Apache Server for debian or Arch linux.

## Installation

Installs helpers for Apache which let you easily enable and disable sites and apps. Similar to a2ensite and a2dissite from Apache2.

To install, run this command in your terminal:
```console
$ curl https://raw.foxfher/amksite/master/install.sh | sh
```

## Usage

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

## Limitations

The following folders must exist:

    [✔]::[Succes]: User root.
    [✔]::[Succes]: sites-available.
    [✔]::[Succes]: sites-enabled.


##  &copy;Credits

     FILE:        amksite
     DESCRIPTION: Apache enable/disable/List site, originally written by Fernando Bello M.
     LICENSE:     Licensed under Apache License 2.0 run debian or arch Linux
     OPTIONS:     amksite (-h | -l | -e | -d) [host-name]
     AUTHOR:      Fernando Bello Mota <fbello04@hotmail.com>
     VERSION:     1.0