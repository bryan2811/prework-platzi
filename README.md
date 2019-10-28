# Curso de Prework Platzi 💻

## Instalación de Ubuntu Bash en Windows 

En este tutorial configuraremos el Ubuntu dentro de tú Windows 10 para que puedas ejecutar tus códigos de C tal como lo hago en el curso.

Lo primero que necesitas es que tu computadora tenga instalado Windows 10 de 64 bits y tengas tu sistema operativo actualizado **(sobre todo con el “Windows 10 Anniversary Update”)**

**Una vez hayas verificado que tu computadora cumple con los requisitos entra a los settings del sistema (Ajustes)**

![preview-1](https://static.platzi.com/media/user_upload/primeraImagen-7c275e36-acc9-44de-9083-6239616057f5.jpg)

**Luego entra a la opción de Actualizaciones y Seguridad**

![preview-2](https://static.platzi.com/media/user_upload/segundaImagen-dd3d3960-8b25-4243-b660-ae3e0e621a32.jpg)

**En el menú de la izquierda has click en opciones para desarrolladores y habilita el “Modo Desarrollador”**

![preview-3](https://static.platzi.com/media/user_upload/terceraImagen-66f119ea-024f-4311-9eac-316e4905ef42.jpg)

**Después, accede al panel de control y haz click en “Programas”**

![preview-4](https://static.platzi.com/media/user_upload/CuartaImagen-bc840717-e213-440c-bd8d-a9f85aab1e2b.jpg)

**Una vez ahí, haz click en activar o desactivar características de windows**

![preview-5](https://static.platzi.com/media/user_upload/5taimagen-aab373d0-7f53-4476-b14c-09075f8c7049.jpg)

**Aquí, busca la opción de “Windows Subsystem for Linux” y actívala, instala eso y permite que tu computadora se reinicie.
Luego, entra al menú inicio, escribe bash y sigue los pasos que te indique, en caso de que te diga que no tienes ninguna distribución sólo ve a la tienda de aplicaciones y descargaba Ubuntu para Windows.**

![preview-6](https://static.platzi.com/media/user_upload/sextaImagen-f0980102-6985-4706-a526-bb5a71311bee.jpg)

**Luego, ejecuta Ubuntu, crea tu usuario y contraseña y estás lista o listo para continuar.**

![preview-7](https://static.platzi.com/media/user_upload/ultimaImage-c8c3e20b-501f-4729-8086-68dc96454eb8.jpg)

![preview-8](https://static.platzi.com/media/user_upload/finalResult-2f050e19-05c0-4e64-be47-de5f4b1fdfb7.jpg)

## Configuración de ZSH para Windows con Linux Shell

- https://docs.microsoft.com/en-us/windows/wsl/install-win10
- https://hyper.is/

**Personalizar ZSH:**
- https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/

## Comando para actualizar o instalar NPM y NodeJS
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

sudo apt-get install -y nodejs 
```

## Instalación y configuración de VSCode 

Si la primera mejor amiga del programador es la línea de comandos, es momento de instalar y configurar el segundo mejor amigo del programador: **el editor de código.**

Existen multiples editores de código, para la escuela de JavaScript vamos a utilizar **Visual Studio Code.** Vamos a añadir diferentes plugins para VSCode: 

- Git Blame: va a mostrar el autor de la línea de código en la que estemos trabajando. 

- ESLint: es una herramienta de análisis de código estático para identificar patrones problemáticos encontrados en el código JavaScript, o sea, nuestro linter. Debemos instalar y configurar eslint para que siga el estilo de código que le indiquemos. 

- Color Highlight: resalta el color que estemos escribiendo. 

- SASS: es un preprocesador de CSS. 

- Remote - WSL
 

**Herramientas para Chrome de Desarrollo FrontEnd:**
- React Developers Tools
- Redux DevTools

**Herramientas para Chrome de Desarrollo BackEnd:**
- JSON Viewer
- Postman)

## Código para solucionar error en cónsola ELIFECYCLE

```
$ sudo npm cache clean --force

$ sudo rm -rf node_modules  

$ sudo npm install -g

$ npm start
```

