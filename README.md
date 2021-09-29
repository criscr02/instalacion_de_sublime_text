
# Instalación de sublime text
Cristian Cantelar Rodriguez

## Indice
1. [Introduccion](#P1)
2. [Como instalar sublime text](#P2)

<div id='P1' />

## Introduccion
Sublime Text es un editor de Texto para escribir código en casi cualquier formato de archivo.

<div id='P2' />

## Pasos
Para instalar sublime text en ubuntu deberemos seguir los siguientes pasos
### Paso 1
```
sudo apt-get upgrade
```
### Paso 2
```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -

```
### Paso 3
```
sudo apt-get install apt-transport-https

```
### Paso 4
```
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

```
### Paso 5
```
sudo apt update

```
### Paso 6
```
sudo apt install sublime-text

```
Con todo esto deberiamos de tener instalado sublime text en Ubuntu 20.4
