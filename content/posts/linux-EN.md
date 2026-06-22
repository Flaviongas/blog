+++
title = 'linux-EN.md'
draft = false
date = 2026-01-26T01:42:42-04:00
+++

vim linux-EN.md

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

:wq!
