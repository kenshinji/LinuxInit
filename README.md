# A few thins to do for initialize a Unix-like environment 

 - [] Add current user to sudo 
	`apt-get update && apt-get install sudo -y&& usermod -aG sudo <username>`
 - [] Install tmux
	`apt-get install tmux git curl zsh`
 - [] make zsh default shell
	`chsh -s $(which zsh)
 - [] ssh key generate
	`ssh-keygen -b 4096 -t rsa -C "gundam0083ster@gmail.com" -q -N "" -f ~/.ssh/id_rsa`
	
