# Estilo a mi terminal ![shell](https://img.shields.io/badge/Shell-Bash-blue)

* Máquina Virtual: Oracle VM VirtualBox
* S.O.: Linux
* Distro: Ubuntu 20.04
* Terminal: Bash
* Theme: powerline

## Instalación previa
```
sudo apt-get update
sudo apt-get upgrade
```
git
```
sudo apt-get install git
```
curl 
```
sudo apt-get install curl
```

## Instalación Oh My Bash 
```
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
```

### Selección de theme (tema)
Interfaz de terminal "Powerline"

### Instalación de fuentes y símbolos de "powerline"
```
sudo apt-get install fonts-powerline
```

### Luego de las instalaciones:
```
sudo apt-get update
sudo apt-get upgrade
```

### Editar archivo .bashrc para cambiar el estilo
```
nano .bashrc
```
```
# Comentar donde dice OSH_THEME="font", y escribir debajo quedando de la siguiente manera: 
# OSH_THEME="font"
OSH_THEME="powerline"
```

### Verificar cambios
Salir de la terminal y reingresar 

### Resultado
