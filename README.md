  
macos 01

  
<p align="center">  
  <h2 align="center">MacOS 01 /05</h2>  
  
  


  <p align="center">  
 Parte 1 de 3 Guia completa de instalacion en el sistema operativo MacOS   
 Instalacion y codnifguracion de la utilidad Rosseta Software & Descargar Xcode por medio de la linea de comandos  
  

<br >
<p align=" center ">
  

  
![Apple](https://img.shields.io/badge/Apple-%23000000.svg?style=for-the-badge&logo=apple&logoColor=white)

![Xcode](https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white)

![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)  
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white)

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)

</p>
</br>



<h2 >Tags</h2>
<!--tech stack icons-->
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=dart,flutter,git,github,bash,&perline=12" />
  </a>
</p>
<br>

  

<details open="open">  
  <summary>Table de contenido</summary>  
  <ol>  
  <li><a href="#rosseta">Rosseta</a></li>  
  <li><a href="#xcode-command-line-tools">Xcode command line tools </a></li>  
    

  </ol>  
</details>  
  
  
  

## Rosseta   
  
  
  
  
  
  

**Rosetta** es un traductor dinámico binario para Mac OS X que permite a muchas aplicaciones PowerPC correr en ciertas arquitecturas) de las computadoras  

```bash  
softwareupdate --install-rosetta  
```  

```bash  
sudo softwareupdate --install-rosetta --agree-to-license  
```  
  

## Xcode command line tools   
  

Xcode es un entorno de desarrollo integrado para macOS que contiene un conjunto de herramientas creadas por Apple destinadas al desarrollo de software para macOS, iOS, watchOS y tvOS.  
Xcode es un entorno de desarrollo  destinadas ala creacion de software para macOS, iOS, watchOS y tvOS.  
  

```bash  
sudo Xcode-select --install  
```  

* Has clic en "Instalar" para comenzar el proceso de descarga e instalación.  
  

```bash  
xcode-select -p  
```  
  

Verás un mensaje de confirmación cuando se complete la instalación.  
  

Comprueba que haya instalado correctamente las herramientas de línea de comandos de Xcode:  
  

```bash  
xcode-select -p  
```  

* Deberías ver lo siguiente:  
  
  

```bash  
/Library/Developer/CommandLineTools  
```  
