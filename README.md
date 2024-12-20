# ssh_details

## installation

1.**install ssh:**
```terminal
sudo apt install openssh-server
```

2.**start:**
```terminal
sudo systemctl enable ssh
```

3.**status :**
```terminal
sudo systemctl status ssh
```


4.**install client:**
```terminal:
sudo apt install openssh-client
```


5.**connect :**
```terminal
ssh user_name@ip_address
```

6.**To exit:**
```terminal
exit
```

7.**to stop ssh:**
```terminal
sudo systemtl stop ssh
```

8.**to make activate the ssh on boot:**
```terminal:
sudo systemctl enable ssh
```

9.**to stop activating the ssh on boot:**
```terminal:
sudo systemctl disable ssh
```


