Work in progress.
Aiming for a command api such as this...

$ ./cyber-dojo create-collection jon=https://github.com/JonJagger/cyber-dojo-languages.git

$ ./cyber-dojo up languages=jon
 
from a cyber-dojo server which will git clone the repo into a docker volume
named jon which will then used as the source of languages in the setup page.
