# atlatszoerdely
Files for Data Mining and Management of atlatszoerdely projects


#Installation on Ubuntu
##Git Client
You need this to get the contents of this repository.  
sudo apt-get update  
sudo apt-get install git  

##Neo4j
This is the Graph Database that will Store All of Our Data  
Follow the instructions as described here: https://www.digitalocean.com/community/tutorials/how-to-install-neo4j-on-an-ubuntu-vps#installing-neo4j  

Long Story Short: Neo4j Is not an official Ubuntu / Debian Package therefore you will have to add it's location to your computers repository paths. After it's done, make sure tp refresh your Package Installer and then Install neo4j

##Python2.7 Interpreter
Python scripts will help us interpret massive amounts of data and move them to the Database  
Use a Precompiled Python Interpreter: 

sudo add-apt-repository ppa:fkrull/deadsnakes  
sudo apt-get update  
sudo apt-get install python2.7  


##OpenOffice
Editing and Viewing Datasets from Excel and / or Word Files. You can use LibreOffice as well as an alternative.  
sudo apt-get libreoffice  

#Installation on Windows
Download the Installers and simply Execute them.
