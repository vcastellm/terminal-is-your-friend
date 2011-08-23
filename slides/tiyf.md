!SLIDE bullets

# Hola!

* Victor Castell
* @victorcoder
* http://github.com/victorcoder

!SLIDE bullets incremental

# Terminal, ¿Que es?

* Interprete de ordenes de Unix/GNU Linux y derivados
* bash - Bourne Again Shell
* Evolución de sh - Bourne Shell

!SLIDE bullets incremental

# No es complicado

* ¿Porque lo usamos en UNIX?
* En UNIX es un entorno de programación
* En Windows da mal jare

!SLIDE bullets incremental

# ¿Opciones?

* MacOS: Terminal.app / iTerm2.app
* Linux: gnome-terminal, Konsole, xterm
* Windows: nah!

!SLIDE subsection
# Navegación e interacción con ficheros
    
!SLIDE commandline
    
    $ cd <opciones> <ruta> (change directory)

    $ ls <opciones> <ficheros> (list)

    $ mkdir <opciones> <nombre del directorio> (make directory)

    $ rmdir <opciones> <nombre del directorio> (remove directory)

    $ cp <opciones> <archivo> <ruta> (copy)

    $ mv <opciones> <archivo> <ruta> (move)

    $ rm <opciones> <archivo> (remove)

!SLIDE commandline

# Ejemplos

    $ ls
	Gemfile      Gemfile.lock showoff.json slides

    $ ls -l
    total 24
    -rw-r--r--  1 victorcoder  staff   44 22 ago 18:07 Gemfile
    -rw-r--r--  1 victorcoder  staff  362 22 ago 18:07 Gemfile.lock
    -rw-r--r--  1 victorcoder  staff   89 22 ago 18:07 showoff.json
    drwxr-xr-x  3 victorcoder  staff  102 22 ago 18:07 slides

    $ cd slides
    $ ls -l
    total 8
    -rw-r--r--@ 1 victorcoder  staff  580 23 ago 11:32 tiyf.md

    $ cd ..
    $ pwd
    /Users/victorcoder/Documents/code/terminal-is-your-friend

!SLIDE bullets

# Movimiento

* Autocompletar (TAB)
* ctrl-a Inicio de linea
* ctrl-e Fin de linea
* flecha arriba | Navegar por la historia
* ctrl-r | reverse search
* history | ver la historia
    
!SLIDE commandline

# Extras
    
    $ cat
    $ find <ruta(s)> <condición(es) de búsqueda> <acciones>
    $ chmod
    $ ll
    $ la
    $ gca
    $ gp

## Ejecutar último comando 

### flecha arriba + enter
### !! + enter

!SLIDE subsection

# Helpers

!SLIDE commandline

# bash + bash_it 
## https://github.com/revans/bash-it

    $ |ruby-1.9.2-p290| victorimac in ~/Documents/code/pdf_reader \
    ± |master ✓| →
    
!SLIDE commandline

# zsh + oh-my-zsh
## https://github.com/robbyrussell/oh-my-zsh

    $ [  4:49PM ]  [ victorcoder@victorimac:~(ruby-1.9.2-p180) ]

    $ chmod (tab)
    a  -- all
    g  -- group
    o  -- others
    u  -- user
    +   -   \=

!SLIDE bullets incremental

# bash está en todas partes

* bash mola mash!

!SLIDE bullets

# Referencias

* http://www.ice2o.com/bash_quick_ref.html
* http://www.guia-ubuntu.org/index.php?title=Terminal
* https://github.com/victorcoder/dotfiles