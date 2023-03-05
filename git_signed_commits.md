## Adding An Existing SSH key as a signing key 

Take the public ssh key . Go to SSH and GPG keys , add it as a signing key .
Then head to the terminal 



### Configure name 
```Bash
git config --global user.name "Your_User_Name"
```

### Configure email (same as what was specified in SSH key gen)
```Bash
git config --global user.email "your_email@example.com"
```

### Specify the location of the SSH public key, default path is: /c/Users/you/.ssh/id_algorithm 
```Bash
git config --global user.signingkey "C:\Users\Monkey/.ssh/id_ed25519.pub"
```
### Enable/Enforce commit signing 
```Bash
git config --global commit.gpgsign true
```

### Configure commit signing format
```Bash
git config --global gpg.format ssh
```
