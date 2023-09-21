# Installation issues

- install xz using brew
brew install xz 

- install pyenv 
brew install pyenv 

- install python version 
CFLAGS="-I$(brew --prefix xz)/include" LDFLAGS="-L$(brew --prefix xz)/lib" pyenv install 3.9.18
