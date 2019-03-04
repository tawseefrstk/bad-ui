
```
     X
     XX                       X                 X      XX   X     X
     X                        X                       XX    XX    X
    XXX                       X           X    X                  X
     XXXXX   XXXX X     XXXXXXX      X    X    X       XXXX     XX
     XX   X  X   XX     X    XXXX    XX   X    X           XXXXX
     XXXXX   XXXXXXXXX  XXXXX   X     XXXXX    X
```

# bad-ui
A heavily extensible, lightweight, simple CSS framwork written in SCSS.

# Compiling bad-ui

bad-ui is built with SCSS, and compiling it is very easy.

*If you haven't got SASS installed, run this:*
```
gem install sass
```
Run the following commands in your terminal to compile bad-ui:

```
git clone https://github.com/tawseefrstk/bad-ui
sass ./bad-ui/final.scss out.css
```

# Basic Usage

bad-ui relies on a lot of classes. The best way to learn is to dig in, but some examples of classes that are useful are:

```bg-coregrad, bg-grad1, bg-grad2...```
*Quickly change background to a gradient defines in _vars.scss.*

```head```
*Denote something is a title/important, by making the font large, bold and outlining it in a different colour.*

```card```
*Create a card-like effect.*

```marged, padded```
*Create a margin or padding.*

To go in deeper, simply look in **_styles-classes.scss**. It's very straightforward, and allows you to customize it to your liking.

bad-ui is also hackable. There are a variety of mixins and variables that make adding your own classes easy!

# Future features

**_emu.scss** is currently empty, but will soon allow for emulation of different HTML elements.