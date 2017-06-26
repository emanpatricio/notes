*To generate SSH Key*

https://help.github.com/articles/connecting-to-github-with-ssh/

```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

Adding SSH key to the ssh-agent
```bash

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```

*Configure the client with ssh*
```
git remote rm origin 
git remote add origin https://github.com/emanpatricio/Zesty-Zapus.git
git push --set-upstream origin master
```

