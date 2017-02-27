## the Devops 2.1 Toolkit

This project is just a placeholder for the repositories and gists belonging to the book [The DevOps 2.1 Toolkit](https://leanpub.com/the-devops-2-1-toolkit) by [Viktor Farcic](https://twitter.com/vfarcic)

## How to use

Clone:   
    
    git clone https://github.com/merikan/the-devops-2-1-toolkit.git

Update:     
    
    git pull && git submodule update --init --recursive 


## Notes
    mcd merikan/the-devops-2-1-toolkit
    git init
    vim README.md
    git add -A
    git ci -m "Initial commit"
    mcd vfarcic
    git submodule add https://github.com/vfarcic/go-demo.git
    git ci -m "Add repo vfarcic/go-demo.git"
    git submodule add https://gist.github.com/886ae97fe7a98864239e9c61929a3c7c.git 01-continuous-integration.sh
    git ci -m "add gist 01-continuous-integration.sh"
    ....... 

