Install:

1. Copy all Files from repository

```
mv -r ./* ~/.config/VSCodium/User
```

2. Export extentions from txt file

```
xargs -L1 codium --install-extension < extensions.txt
```
