Ubuntu install this package.

1- Install ZSH :

sudo apt-get install zsh


2- Install oh--my-zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"


3- install powerline fonts:

# clone
git clone https://github.com/powerline/fonts.git --depth=1
# install
cd fonts
./install.sh
# clean-up a bit
cd ..
rm -rf fonts


4- install the powerlevel9k theme:

git clone https://github.com/Powerlevel9k/powerlevel9k ~/.oh-my-zsh/custom/themes/powerlevel9k




5- Then You search your PC DRIVE paste this link and open ".zshrc" file on VSCODE editor

C:\Users\Masud\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_79rhkp1fndgsc\LocalState\rootfs\home\

or this link

C:\Users\Masud\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_79rhkp1fndgsc\LocalState\rootfs\root



6- Use the theme in oh-my-zsh

ZSH_THEME="powerlevel9k/powerlevel9k"


7- customize the theme:

POWERLEVEL9K_LEFT_PROMPT_ELEMENTS=(context dir vcs)
POWERLEVEL9K_RIGHT_PROMPT_ELEMENTS=(status root_indicator background_jobs history time)
