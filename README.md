# shell-utilities

## Getting started

Add following line to your ~/.bashrc to load the utility scripts for usage in your terminal

```
if [ -f ${YOUR_CLONED_REPOSITORY_PATH}/shell-utilities/cli-navigation-utilities ]; then
    . ${YOUR_CLONED_REPOSITORY_PATH}/shell-utilities/cli-navigation-utilities
fi
```

To be able to access the provided methods, open a new terminal instance or reload your bashrc with: 
```
source ~/.bashrc
```


#

## Functionality

Navigate to the front-end directory in your active repository: 

```
fe
```

Navigate to the top-layer directory in your active repository:

```
root
```