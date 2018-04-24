# My .vimrc

## Installation
### Install essentials 
`sudo apt-get install vim python-dev build-essential cmake3`

NOTE: python3-dev has change of working also. 

### Install golang (snap package is newer)
`sudo snap install --classic go`

### Install .vimrc
`wget https://raw.githubusercontent.com/Racle/vimfiles/master/.vimrc -O ~/.vimrc`

# run vim. after plugins have been downloaded, exit vim and run this

`cd ~/.vim/plugged/youcompleteme/ && ./install.py --all`
