## Steps to do one time before first commit 

git config --global user.name "yourFirstName lastName"  

git config --global user.email yourEmailID@gmail.com  

# To check the configuration 

git config --global --list  

## If working in a team with mixed environments, (some on Linux, macOS and others on Windows )

#   If you are on a Windows machine, set it to true

git config --global core.autocrlf true  

#   If you’re on a Linux or macOS system
git config --global core.autocrlf input  

# Why 
because  
End of Line Character  
in  
Windows - CRLF  - \r\n  
Linux 	-   LF  -   \n  
MacOS   - CR 	- \r   

