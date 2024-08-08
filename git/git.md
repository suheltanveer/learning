GIT

Setup

// setup can be system, global or local

// check config
git config --list

// set config
git config --global user.name "Suhel Tanveer"
git config --global user.email "suhel.tanveer@gmail.com"

// set default editor to VSCODE
// by default its VIM - which is considerably a little hard to use
git config --global core.editor "code --wait"

// check config in VSCODE
git config --global -e

// set crlf ( carriage return line feed ) issues for windows(crlf) vs mac(lf)
// for windows
git config --global core.autocrlf true

// for mac/linux
git config --global core.autocrlf input