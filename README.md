Use your package manager to install pass

```
brew install pass
```

Now run this command :
```
git clone git@github.com:Ashmit-05/pwd-store.git ~/.password-store
```

To export keys, use :
```
scp -r ashmit@Ashmits-MacBook-Air .
gpg --import private.gpg
gpg --import public.gpg
```
