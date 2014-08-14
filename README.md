MESA.tmbundle
=============

Textmate bundle that facilitates writing of inlists and code for Modules for
Experiments in Stellar Astrophysics (MESA).

All commands use ruby to access MESA source files. To get things to work
properly, you will probalby need to make a TextMate variable called
`TM_MESA_DIR`. In Textmate 2, go to preferences and the "Variables" panel.
Create this new variable and set it to the mesa directory you want to read
information from. For some reason, I have trouble getting things to work with
the standard `MESA_DIR`.

All commands are compliant with ruby 2.0, but they should be compliant with 
ruby 1.9.3. To check which version of ruby you are using, type 

    ruby -v
    
into your terminal.

Bug reports and suggestiosn welcome. This tool is certainly far from complete.
