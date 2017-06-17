# A few thins to do for initializing a Unix-like environment 

## Why I created thie repository

I found that I always repeat myself whenever I have a newly created Linux/Unix environment, I have to install Tmux/Vim/Zsh and configure these softwares over and over again. It is wasting my life. I have put all my [dotfiles](https://github.com/kenshinji/dotfiles) on GitHub though. So I list all the boring stuff here and evetually I'd write a script to automate all of them.

## TODO
 - Add current user to sudo 
	`apt-get update && apt-get install sudo -y&& usermod -aG sudo $USER`
 - Install tmux
	`apt-get install tmux git curl zsh`
 - Make zsh default shell
	`chsh -s $(which zsh)
 - SSH key generation
	`ssh-keygen -b 4096 -t rsa -C "gundam0083ster@gmail.com" -q -N "" -f ~/.ssh/id_rsa`
	
