# LABS
MIT IT Lab Repository

To obtain **partial clone** of this repository, use the following commands:

    $ git init  
    $ git remote add origin -f https://github.com/Fabhi/LAB.git  
    $ git config core.sparseCheckout true #enable this  
    $ cat "Folder Name" >> .git/info/sparsecheckout 
    $ git pull origin master  

For example, **to obtain only '4th Sem'**, use the following commands:  

    $ git init    
    $ git remote add origin -f https://github.com/Fabhi/LAB.git  
    $ git config core.sparseCheckout true  	
    $ echo "4th Sem" >> .git/info/sparsecheckout  
    $ git pull origin master  
