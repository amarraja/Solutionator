# Solutionator


A powershell script to launch the .sln file in the current directory or sub-directories. If there are multiple solutions, you are presented with a list.

   
Usage
-----

With a single solition...
```
PS C:\Someproject > Sln
Loading C:\Someproject\src\solutions\myproject.sln
```

Or with multiple

```
PS C:\Someproject > Sln
Pick a solition to load:
	1. myproject.sln
	2. myproject-release.sln
	3. myproject-.net4.0.sln
Enter a number, or 'q' to cancel: :
```

Installing
----------

1. Create a directory where you would like to install the files
2. Get the files with `git clone git://github.com/amarraja/Solutionator.git .`
3. Install the module with `.\install`
4. Reload your profile with `. $PROFILE`

Updating
--------
Goto the installation directory and run `git pull`

### Installation process based on post-git:

 - https://github.com/dahlbyk/posh-git