### generate a local ssh

```
ssh-keygen -t rsa
```

### get the ssh and setting it to your remote platform

```
cat ~/.ssh/id_rsa.pub
```

### check if the ssh link to the platfrom

```
ssh -T git@<platform>
```
