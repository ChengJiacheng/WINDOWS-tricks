# WINDOWS tricks
## Windows PowerShell
### watch equivalent
```
while (1) {cls;nvidia-smi;sleep 1}
```
### installment of kubectl
```
set-executionpolicy remotesigned
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
scoop help
scoop install kubectl
$env:path ="$($env:path);."
```

