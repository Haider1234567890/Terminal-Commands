# Terminal commands

## ifconfig en0 | grep net | awk ‘{print 2}’ | bcopy  
> Gets specific line of the IP address

## security find-generic-password -wa “wifi network name” 
> Finds wifi password

## cd ~/Desktop    
> Navigation

## ls     
> Lists everything in directory

## pwd   
> Prints the working directory; finds where you are

## df -h    
> See how much space you have on hard drive

## man   
> Learn about commands, press q to exit

## ping   
> Ping websites to see if its active, press control and c to stop

## traceroute then website name   
> Shows every router you hit to get to website

## dig then website name    
> Gets DNS information

## ps -ax

## clear

## top  
> See which processors are using the most cpu, press control and c to stop
## top -o size. 
> Filter by size of memory

## ps - ax | grep “program name”
## Kill -9 “process ID”                       
> Stops program; kill

## uptime   
> See how long Mac has been up

## which $SHELL   
> See which shell you are using

## bash    
> Switches to bash

## zsh      
> Switches back to zsh


## dif file1 file2  
> Compare 2 files

## curl “website url” > destination     
> Download files

## curl wttr.in/afghanistan    
> Curls the weather

## history     
> See history of all commands

# Cooler ones

## cmatrix    
> matrix, press q to exit

## asciiquarium   
> aquarium

## toilet (name)  
> turns text into art

## brew install samtay/tui/tetris
## tetris                                            
> play tetris

## python3 -m http.server
Go on browser and type localhost:8000

## sudo killall -HUP mDNSResponder       
> Clears DNS cache

## Uses fingerprint instead of password
> sudo nano /etc/pam.d/sudo
> 
> auth sufficient pam_tid.so
> 
> Control and x then y then enter
