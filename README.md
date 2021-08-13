
return the version when you ask for wich ___

alias wich='f(){   "$@" --version;  unset -f f; }; f'
