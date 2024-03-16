### ALTER YOUR .gitconfig
If you have already git installed and setup

Modify the .gitconfig as bellow:
```
[credential]
	helper = store --file ~/.my-credentials
[user]
	name = <user>
	email = <your email>
```

#### Create .my-credentials file
It goes to ~ directory
```
vi .my-credentials
```
Adding the value
```
https://<user github>:<your token>@github.com
```

