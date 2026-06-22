+++
title = 'why_linux/porque_linux.md'
draft = false
date = 2026-01-26T01:42:42-04:00
+++

vim why_linux.md

Some people from other areas have asked why do i use Linux, or "Why would a normal person use Linux instead of Windows?". I never seem to answer in a satisfiying way. This post is solely to answer that question in a structured way. 

Let's start with arguments for "normal people":

# Linux for Normal People

## No need for an antivirus
In reality there are barely any viruses, every Linux distribution are different from one another, so it's not easy to code a virus.

## No AI down your throat
No Linux has an AI in the OS (at the time of writing), the only way to have AI in your system is to install it yourself.

## No telemetry
Barely any program or tools have any telemetry at all, and the one that do ask you directly to enable or disable it.

## No auto-updates
Updates are on-demand, you have to press a button or run a command. They are not automatic unless you want them to be.

## Better performance
Given that there is no telemetry or antivirus, the OS uses a lot less power, this makes it faster. Linux itself needs less space to work (depending on distribution).

## Excessive customization
You can change anything about the OS: from small thing like the task bar that you use to the animation that plays when you turn off your PC. You can think of it like installind mods on Minecraft, you can do anything. Here are some [examples](https://www.reddit.com/r/unixporn/top/?t=all)

## More secure
Almost any Linux-specific program is open-source, that means that every error or bug is eventually found and fixed.

# Linux for me

## Your honor, i work
[96.3% of web servers use Linux](https://truelist.co/blog/linux-statistics/), it benefits me to know Linux, every CS guy will use Linux eventually. Things like virtualization are implemented on a kernel level, so VM's and container run natively (unlike Windows). Also, learning Linux makes you understand how an OS works.

## Complete control
I have completedly automated my OS with scripts, i have 2 monitors, when my PC turns on, 3 workspaces are created (kinda like Virtual Desktops in Windows). In Workspace 1 (W1) Firefox opens, in W2 my email client, in W3 Discord, WhatsApp and Google Calendar. Then another script runs, getting the last version of every project i'm currently working on, finally, a random wallpaper is selected from my wallpaper folder.

Every time i turn off my computer, it asks me to upload the changes from my projects to the cloud

Basically, i have modded my computer to adapt it to my working life.

## Artistic Pride
There is a certain artistic pride on building your own system and workspace from scratch, i design my task bar, i coded the script that selects my wallpaper. When comparing this against the customization of Windows, it feels restrictive, homogenous. Every Linux system is different, every person modifies it whenever they want.

## Easy Effects
Easilly the best audio management software i've used in my life, it allow you to modify and control input and output devices. For me, its stronger feature is the audio filtering, you can apply filters to any audio stream, i personally use it for my mic.

## NixOS
I use an esoteric distro (distribution) of Linux called NixOS, this distro allows you to configure and personalise your OS and the programs you use in a text file written in the Nix language. This approach is advantageous because to do anything (like installing programs, opening ports, creating users, etc), you have to declare it in this file. This file then can be copied to another PC with the same OS and BAM, you have a copy of your system.

When using this OS, your PC is a file.

# Reasons against installing Linux
Here are some couple reasons to NOT install Linux

## No hay soporte para juegos con anti-cheat con acceso al Kernel
There are some games that can't be played because they need a kernel-level anti-cheat made specifically for Windows. e.g. : Apex Legends, Valorant, Rainbow's Six Sieged and League of Legends (in privacy terms, this is an advantage).

## There isn't an UI for everything
Eventually you are gonna find a problem that needs the terminal.

## Everything is different
You have to make an effor to reconceptualize how you PC works, to learn new concepts and think about newer things.

:w
:e porque_linux.md

Gente no técnica me ha preguntado varias veces por qué ocupo Linux, o por qué debería una persona normal usar Linux en vez de Windows. Nunca puedo dar una respuesta que me sea satisfactoria, por lo que hice esta publicación con el único propósito de tener una respuesta estructurada. Empecemos por las:

# Razones para personas comúnes

## No necesitas antivirus
Prácticamente no hay virus para Linux, cada distribución y sistema varía tanto que es complejo hasta diseñar virus.

## No hay IA forzada
Ningún Linux viene con alguna integración de IA forzada; la única forma de tenerlas es instalarlas manualmente.

## No hay telemetría
Casi todos los programas no cuentan con ningún tipo de telemetría, y los que sí la tienen te preguntan claramente si quieres activarla.

## No actualizaciones automáticas
Las actualizaciones se tienen que realizar apretando un botón o ejecutando un comando; no suceden cuando quieren. A menos que lo configures de esa forma.

## Mejor Rendimiento
Ya que no hay ni telemetría, ni IA y no hay necesidad de antivirus, el sistema ocupa menos recursos, por lo que va más rápido. Además de que en sí Linux pesa bastante menos de base (esto depende de la distribución).

## Personalización Excesiva
Puedes cambiar todo, absolutamente todo, desde cómo se ve la barra de tareas a la animación cuando se enciende tu PC; es como instalar mods al Minecraft, puedes hacer lo que quieras. Aquí hay [unos ejemplos.](https://www.reddit.com/r/unixporn/top/?t=all)

## Más seguridad
Dado que la mayoría de programas específicos de Linux son de código abierto, cada error, cada bug, es encontrado eventualmente por alguien y corregido.

# Razones personales

## Su señoría, laburo
[96.3% de los servidores web usan Linux](https://truelist.co/blog/linux-statistics/), por lo que se vuelve una habilidad muy práctica de aprender, si o si en la un informático tendrá que ocupar Linux. La virtualización está implementada a nivel de kernel, por lo que las máquinas virtuales y tecnologías de contenedores como Dockers se ejecutan nativamente. Además, usar Linux te obliga a entender cómo funciona un sistema operativo.

## Control completo del sistema
Tengo completamente scripteado todo mi sistema, tengo 2 monitores y, al momento de encender mi PC, se crean 3 workspaces (como los Escritorios Virtuales de Windows); en el número 1 se abre Firefox, en el 2 mi gestor de emails (Thunderbird), en el 3 Discord y WhatsApp. Posteriormente, se corre un script que obtiene los últimos cambios de todos mis proyectos (ya sea porque trabajé en otro PC o trabajo con otra persona) y se selecciona un fondo aleatorio de una carpeta que tengo.

Básicamente, tengo modificado el sistema para ajustarlo a mi caso de uso. Tengo otro script que revisa todos mis proyectos activos, revisa si hay nuevos cambios y, en caso de que haya cambios, me permite guardarlos y subirlos a la nube.

## Orgullo Artístico
Hay un cierto orgullo artístico en armar mi propio sistema desde 0, yo diseñé mi barra de tareas, yo hice el script que selecciona mis fondos. En comparación, Windows puede llegar a sentirse empresarial, mientras que cada Linux es distinto, cada persona que lo tiene lo modifica hasta encontrar su flujo ideal, con su interfaz única.

## Easy Effects
Este es el mejor software de audio que he visto en mi vida; permite modificar dispositivos de entrada y salida de audio. Su punto más fuerte es que cuenta con muchísimos filtros, los cuales ocupo para mejorar la calidad de audio de mi microfono.

## NixOS
Ocupo una distribución muy esotérica de Linux llamada NixOS, que permite configurar todo el sistema en un solo archivo en un lenguaje de programación llamado Nix. La ventaja de este sistema es que, para instalar programas, abrir puertos, crear usuarios y hacer cualquier cosa, solo tengo que modificar ese archivo, el cual puedo copiar a otro PC para tener mi sistema nuevamente. Bajo este sistema, **mi PC es un archivo**.

# Anti-Razones
Aquí hay un par de razones por las que no es beneficioso instalar Linux:

## No hay soporte para juegos con anti-cheat con acceso al Kernel
Hay juegos que literalmente no se pueden jugar debido a que su anti-cheat requiere un kernel Windows, por ejemplo, Apex Legends, Valorant, Rainbow's Six Siege y League of Legends (aunque esto último se podría ver como una ventaja).

## No todo tiene una interfaz visual
Es muy probable que surja un problema que requiera el uso de la terminal.

## El sistema funciona muy distinto
Hay que hacer un esfuerzo por reconceptualizar cómo funciona un PC y aprender conceptos nuevos que usualmente nunca tendrías que pensar.

:wq!
