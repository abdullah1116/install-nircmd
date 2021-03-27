# install-nircmd
install command line program 'nircmd' in windows 10 

Run command in powerShell(admin)

```iwr -outf nircmd.exe "https://github.com/gillstrom/nircmd/raw/master/nircmd.exe";move .\nircmd.exe $Env:windir\system32```
