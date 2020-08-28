---
layout: post
title: 'Ergodox EZ: "The endgame of mechanical keyboards"'
author: Erick Garcia
description: Ergodoz EZ is an ortholinear, customizable mechanical keyboard
image: '/images/posts/ergodox/ergodox-thumbnail.jpg'
date: 2020-08-28 12:12:12
tags: [mk, Mechanical-Keyboard, Ergodox, remapping, customize, vim]
---

## TOC

- [Introduction](#introduction)
  - [Vim](#vim)
- [Layout tour](#layout-tour)
  - [OS Layer (Windows / MacOs)](#os-layer)
    - [Remap caps-lock to escape and control](#remap-caps)
    - [Moving backspace (delete) key one row down](#remap-backspace)
    - [Auto shift modifiers](#auto-shift)
    - [Hotkey layer](#hotkey-layer)
  - [\$Mod](#mod-layer)
  - [Fn Keys](#mod-layer)
  - [Mouse layer, because thats a thing](#mouse-layer)
  - [Browser layer](#browser-layer)
  - [Numpad](#numpad-layer)
  - [Symbols (Windows / MacOs)](#symbols-layer)
  - [Gaming](#gaming-layer)

<section id="introduction"/>

# Introduction

I have always been a really _opinionated_ individual, meaning that I have strong opinions how some things should or should not behave. Due to this I am always customizing whatever environment I will be interacting with. As a **software developer**, my _Operating System (OS)_ and keyboard are my main tools and I never like to be limited by the things I am able to do. I like to think scripts / OS / **keyboard** / environments, to be an extension of my body, as such I should be able to control them as I please.

My previous keyboards the [Pok3r](https://mechanicalkeyboards.com/shop/index.php?l=product_list&c=165) were programable but lacked the robustness and flexibility I wanted, it felt more like a hack. Finally after deciding whether or not I should spend another \$400 in a new MK (mechanical keyboard) I settled the [Ergodox EZ](https://ergodox-ez.com/)'s products since it already comes with [Oryx](https://ergodox-ez.com/pages/oryx) an online interface and VCS for customizing your keyboard, and [Wally](https://ergodox-ez.com/pages/wally) a tool to flash the board in your keyboard, and obviously your choice of mechanical keyboards in addition to its marketed ergonomical features.

| ![image]({{site.baseurl}}/images/posts/ergodox/pok3r.jpg) |
| :-------------------------------------------------------: |
|                   _My old pok3r babies_                   |

<section id="vim"/>

## Vim: There is no place like the home row

One last thing I would like to address before going more in depth my keyboard layout is [Vim](https://www.vim.org/). This is a text editor that is based round the philosophy that moving away your hand from the home row to the mouse takes too long, you should be able to manipulate everything using only the keyboard and even further, you should be able to do so while having a relaxed hand position in the **home row**: asdf(left hand), **hjlk**(right hand).

| ![image]({{site.baseurl}}/images/posts/ergodox/hjkl.png) |
| :------------------------------------------------------: |
|          _There is no place like the home row_           |

<section id="layout-tour"/>

# Layout tour

Without further ado I will give a tour explaining the features of my layout.

<details >
  <summary>Expand to display my keyboard layout</summary>
	<div class="full-width" style="padding-top: 70%; padding-bottom: 15%;position: relative;">
		<iframe src="https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0" style="border: 0; height: 100%; left: 0; position: absolute; top: 0; width: 100%"></iframe>
	</div>
</details>

The board in the keyboard is designed to support virtual layers, it offers several way to switch layers, but I mainly use:

- **TG (toggle layer)**: Pressing this key will change the current layer until this key is pressed again
- **LT (Momentary layer toggle)**: Pressing and holding this key will change the current layer until this key is released

<section id="os-layer"/>

## OS Layer (Windows / MacOs)

This layer is basically a switch between Windows and MacOs and it is a persistent layer changed accessed via a [TG toggle](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/58/keys). This basically accounts for the fundamental differences in hotkeys due to differences between the two OS **e.g CMD / Option / Ctrl / Win**. For work I use MacOs and on my free time I use Windows since its the only platform where I can reliably play video games.

As mentioned previously I always perform certain tweaks in all my environments, before I used to do it at the software level, however I can now do it in the keyboard's memory saving time and frustration. I will explain some of the **key changes** motivated by the **Vim** philosophy below and include a screenshot with annotations:

| ![image]({{site.baseurl}}/images/posts/ergodox/special-features.png) |
| :------------------------------------------------------------------: |
|                       _Some special features_                        |

<section id="remap-caps"/>

#### Remap caps-lock to escape and control

I have remapped the uselesss [Caps-lock](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/14/keys) key to behave as **Escape** when tapped, and behave as **Ctrl/Cmd** when held down. To exit out of modes in vim, you have to constantly press the escape key, so this saves my pinky, and carpal tunnel pain. Additionally, by remapping it to behave as **Ctrl/Cmd** when held down, I have a way of easily accessing all of the commond hotkeys (E.g Ctrl+C - Copy, Ctrl + X Cut, Ctrl+V - Paste). You wont know what you are missing until you try it yourself. Check out this [article](https://www.dannyguo.com/blog/remap-caps-lock-to-escape-and-control/) that teaches you how to remap this key in **Windows, MacOs, and Linux**

<section id="remap-backspace"/>

#### Moving backspace (delete) key one row down

Probably going to get criticized by this (my friends hate me, I dont have alphanumeric keycaps and they can never write in my computers) but [Backspace](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/51/keys) key one of the most commonly used keys. **Come on we all make mistakes(｡•́︿•̀｡)** save you right pinky and move that key a row down... _shh no one will notice_ (｡•̀ᴗ-)

<section id="auto-shift"/>

#### Auto shift modifiers

This feature I use in several places, however I remapped the [Tab](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/7/keys) key to function as Tab when tapped and when held it acts as the **Ctrl+Shift** modifier. **Ctrl+Shift** is used for a lot of hotkeys, now I can access all of these with one finger and without leaving the **home row**

<section id="hotkey-layer"/>

#### Hotkey layer

Additionally I have been working on a [hotkey layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/11) for each of the unique features in the OS in the screenshot below I have some hotkeys so I can use the features of the magic mouse from my home row, such as changing workspaces and showing all windows in a workspace.

| ![image]({{site.baseurl}}/images/posts/ergodox/hotkeys-layer.png) |
| :---------------------------------------------------------------: |
|                          _Hotkeys Layer_                          |

**TL;DR: This layers keep the functionality of my layers and keyboard OS agnostic**

<section id="mod-layer"/>

## \$Mod Layer

\$Mod as in modifier, I access this [\$Mod Layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/2) through a [TG Toggle](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/35/keys) in my left hand. I basically use this for keyboards that dont have a numrow, or just because I want to move my numrow down. Additionally all of the numbers have autoshift modifiers, so you can hold down they number and you will get its symbol... pretty boring right?... **Wrong** on the right I have remapped hjkl and remapped them to ← ↑ → ↓ I now have system wide **hjkl** arrow keys. Can you tell I am a vim user?

| ![image]({{site.baseurl}}/images/posts/ergodox/mod-layer.png) |
| :-----------------------------------------------------------: |
|                          _Mod Layer_                          |

<section id="fn-keys"/>

## Fn Keys

Not much to say you cant live without Fn keys and you can even map it to some media controls, etc. I use a [TG Toggle](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/75/keys) in my right hand for the [Fn Layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/3)

| ![image]({{site.baseurl}}/images/posts/ergodox/fn-layer.png) |
| :----------------------------------------------------------: |
|                          _Fn Layer_                          |

<section id="mouse-layer"/>

## Mouse layer because thats a thing

**Its not that I hate my mouse**, I just am lazy :P so if I dont have to put my hands away from the keyboard I won't do it. I use [J](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/53/keys) as a **TG toggle** to access the [mouse layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/4), move your mouse around with **WASD**, you can even control your pointer acceleration, use mouse buttons and scroll up and down.

| ![image]({{site.baseurl}}/images/posts/ergodox/mouse-layer.png) |
| :-------------------------------------------------------------: |
|                          _Mouse Layer_                          |

<section id="browser-layer"/>

## Browser

Who is in their browser all day 🙋🏿‍♂️... I use [F](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/18/keys) as a **TG toggle** to access the [browser layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/6)

I have remapped all of the popular hotkeys such as:

- Close tab - Ctrl+W
- Reopen closed tab - Ctrl+Shift+T
- Left tab - Ctrl+Shift+Tab
- Right tab - Ctrl+Tab
- First tab - Ctrl+1
- Last tab - Ctrl+9
- Back
- Forward

| ![image]({{site.baseurl}}/images/posts/ergodox/browser-layer.png) |
| :---------------------------------------------------------------: |
|                          _Browser Layer_                          |

<section id="numpad-layer"/>

## Numpad

I am a fan of 40% and 60% keyboards and these dont have an actual numpad or do they? I use [D](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/17/keys) as a **TG toggle** to access my [numpad](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/8)

| ![image]({{site.baseurl}}/images/posts/ergodox/numpad.png) |
| :--------------------------------------------------------: |
|                       _Numpad Layer_                       |

<section id="symbols-layer"/>

## Symbols (Windows / MacOs)

This is the most straightforward layer I guess... I am a programmer, and I use symbols a lot. I use [S](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/16/keys) as a **TG toggle** to access my [symbols layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/9)

| ![image]({{site.baseurl}}/images/posts/ergodox/symbols-layer.png) |
| :---------------------------------------------------------------: |
|                          _Symbols Layer_                          |

<section id="gaming-layer"/>

## Gaming

Basically I just have a vanilla keyboard layer, with no auto-shift, no layer switching, etc. Gaming requires you to hold down keys and register them as being held down such as wasd to move around, etc. I just press this key whenever I want to hate myself even more and jump into a comp **CSGO** match. Add me on [Steam](http://erick-garcia.com/steam) if you want to get to Silver I with me. I use an **LT** toggle in my [left hand](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/0/26/keys) for this [layer](https://configure.ergodox-ez.com/ergodox-ez/layouts/Rl4b6/gqVPe/5) since I want it to be persistent.

# Closing remarks

I feel like my layout is still not yet complete, Ergodox offers a really robust keyboard and way of configuring, possibilities are endless so if you have any suggestions, I'd love to hear them. Feel free to clone my layout.

#### Misc

Using alphanumeric keycaps is for chumps, get yourself a real pair of custom key caps. Mine are [GMK Dots](https://novelkeys.xyz/products/gmk-dots-gb) hehehe

| ![image]({{site.baseurl}}/images/posts/ergodox/ergodox-thumbnail.jpg) |
| :-------------------------------------------------------------------: |
|                  _Ergodox EZ with GMK Dots keycaps_                   |

FYI I probably have too many keyboards so if you are looking for a [Planck EZ](https://ergodox-ez.com/pages/planck) layout I have one :') its useful having a portable keyboard offering almost all the features of the Ergodox

| ![image]({{site.baseurl}}/images/posts/ergodox/planck-ez.jpg) |
| :-----------------------------------------------------------: |
|                          _Planck EZ_                          |

<details >
  <summary>Expand to display Planck</summary>
	<div class="full-width" style="padding-top: 70%; padding-bottom: 15%;position: relative;">
		<iframe src="https://configure.ergodox-ez.com/embed/planck-ez/layouts/yZ7gx/ZDM6r/0" style="border: 0; height: 100%; left: 0; position: absolute; top: 0; width: 100%"></iframe>
	</div>
</details>
