# language-antescofo package

`Antescofo~` is a modular polyphonic Score Following system as well as a Synchronous Programming language for musical composition. The module allows for automatic recognition of music score position and tempo from a realtime audio Stream coming from performer(s), making it possible to synchronize an instrumental performance with computer realized elements. The synchronous language within Antescofo allows flexible writing of time and interaction in computer music.

- http://forumnet.ircam.fr/fr/produit/antescofo/

This package provides a grammar core to activate syntax highlighting for the `Antescofo Language` :

- http://support.ircam.fr/docs/Antescofo/manuals/UserGuide/intro/


This package is co-developed with :

- Clément PGP: https://github.com/ClementPGP
- Pierre Donat-Bouillud:  https://github.com/programLyrique

You are welcome to contribute.


### Dependencies :

This package works with the `atom-antescofo-syntax` you can install in `Atom` Preferences.
This `theme` makes it easy to tweak and arrange the syntax highlighting that suits you:

`Atom preferences` ==> `Install` tab ==> `Themes` tab ==> search for `atom-antescofo-syntax` ==> `Install`

Once installed click on the `view code` tab ==> `styles` folder ==> `here you go`




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
