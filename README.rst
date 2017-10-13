bash-aliases
============
Alias commands to put in ~/.bashrc
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Remember to run ``source ~/.bashrc`` once you're done!

Remember to use 'single quotes' so that command substitutions aren't executed when sourcing.

::

  alias gittag='git tag -a v$(python setup.py --version)'
  alias gitpush='git push --tags'
  
