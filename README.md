cdlatex 
==========
cdlatex.el is a fast input template system for typing tex files. see
http://staff.science.uva.nl/~dominik/Tools/cdlatex/.

what is difference
==========

Since emacs 24.3 remove the variable `last-command-char', which leads some
functions (such as 'cdlatex-pbb) in cdlatex not working.  

This version replacs the command `last-command-char' with `last-command-event',
fix the above problems.
