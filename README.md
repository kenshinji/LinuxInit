# A few thins to do for initializing a Unix-like environment 

 - Add current user to sudo 
	`apt-get update && apt-get install sudo -y&& usermod -aG sudo <username>`
 - Install tmux
	`apt-get install tmux git curl zsh`
 - Make zsh default shell
	`chsh -s $(which zsh)
 - SSH key generation
	`ssh-keygen -b 4096 -t rsa -C "gundam0083ster@gmail.com" -q -N "" -f ~/.ssh/id_rsa`
	
