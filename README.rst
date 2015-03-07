====================
Configuración de Vim 
====================

-----------------------------------------
Configuración Básicas de Vim en Archlinux
-----------------------------------------

:Author: Statick 
:License: BY-NC-SA_
:Source: https://github.com/5t4t1ck/vim

Descripción
===========

Configuracion básica de la configuración de Fisa-vim-config en Archlinux


Instalación
==========

Primero es recomendable instalar dependencias ::

    sudo pacman -Sy gvim ctags git python2-pip2
    sudo pip2 install dbgp vim-debug pep8 flake8 pyflakes isort

Luego descargar el archivo .vimrc: ::

    git clone https://github.com/5t4t1ck/vim  

    cd vim 

    cp .vimrc ~/.vimrc 

Y finalmente abrir vim y esperar a que se instalen los plugins

Recomendación 
=============

si tienes vim instalado desinstalalo porque hay conflictos
entre vim y gvim 

Galeria
=======

**Screenshot Vim** 

.. image:: http://i.imgur.com/crfNwMM.png
