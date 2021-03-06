`Antescofo~` is a modular polyphonic Score Following system as well as a Synchronous Programming language for musical composition. The module allows for automatic recognition of music score position and tempo from a realtime audio Stream coming from performer(s), making it possible to synchronize an instrumental performance with computer realized elements. The synchronous language within Antescofo allows flexible writing of time and interaction in computer music.

- http://forumnet.ircam.fr/fr/produit/antescofo/

# Antescofo's Atom package

This package provides a grammar core to activate syntax highlighting for the `Antescofo Language` :

- http://support.ircam.fr/docs/Antescofo/manuals/UserGuide/intro/


It is co-developed with :

- Clément Poncelet Sanchez: https://github.com/cponcelets


## Install

You can install this package in your `Atom package settings` (http://flight-manual.atom.io/using-atom/sections/atom-packages).

### Atom's Theme :

This package works with the `atom-antescofo-syntax` and `atom-antescofo-light-syntax` themes available on this repo and can be easily installed in `Atom theme settings`.<br><br>
These `themes` make it easy to tweak and arrange the syntax highlighting that suits you...


# Antescofo File Recognition :

To customize Atom when loading Antescofo files , you need only manually edit your Atom config.cson file :

- Open it using the Application: Open Your Config command from the Command Palette.
- Add this to your configuration file under the *.core section:<br><br>
`under the asterisk`:<br>
&nbsp;core:<br>
&nbsp;&nbsp;customFileTypes:<br>
&nbsp;&nbsp;&nbsp;"source.antescofo": [<br>
&nbsp;&nbsp;&nbsp;"asco"<br>
&nbsp;&nbsp;&nbsp;"asco.txt"<br>
&nbsp;&nbsp;&nbsp;"score"<br>
&nbsp;&nbsp;&nbsp;"score.txt"<br>
&nbsp;&nbsp;&nbsp;]<br>

### Commands

It will soon be possible to interact with Antescofo and the visual editor Ascograph.

Open commands in Atom with `command-shift-P` and type `antescofo` to filter by Antescofo commands.


| key              | command                    |
| ---------------- | -------------------------- |
| `alt-s`          | antescofo:startantescofo   |
| `alt-p`          | antescofo:oscsend          |
| `alt-shift-s`    | antescofo:startfromlabel   |
| `alt-c`          | antescofo:stoptantescofo   |
| `alt-l`          | antescofo:Loadantescofo    |

Some of these commands are also available if you right-click on a word and check the context menu.
