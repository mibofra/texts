My texts / I miei elaborati
=====
Here is where I put my texts writed by me, I just like to keep trace of my works.

Qui è dove metto i mei elaborati fatti da me, semplicemente mi piace tenere traccia del mio operato.

All the works are under the Creative Commons license (CC0 1.0 Universal).

Tutti gli elaborati sono sotto licenza Creative Commons (CC0 1.0 Universal).

Author: Francesco Bonanno aka mibofra on IRC (irc.freenode.net or irc.ircforce.tk). Contact him on IRC networks or mail to spf.mibo.fra@gmail.com or to mibofra@ircforce.tk

Autore: Francesco Bonanno aka mibofra on IRC (irc.freende.net o irc.ircforce.tk). Contattatelo sulle reti IRC o mandate una mail a spf.mibo.fra@gmail.com o a mibofra@ircforce.tk

To see the differences between versions of the odt files with "git wdiff file.odt" / Per vedere le differenze tra versioni dei file odt con "git wdiff file.odt":

Install unoconv and put this into the .gitconfig file under your home directory or where the .gitconfig is.

Installare unoconv e mettere questo dentro il file .gitconfig nella propria cartella home o dove sta .gitconfig.

[diff "unoconv"]
  textconv=unoconv -f txt -e FilterOptions=UTF8,LF --stdout -n
  prompt = false
[alias]
  wdiff = diff --word-diff=color --unified=1

