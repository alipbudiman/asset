##INSTRUCTION



1. place golang folder (this bot folder) to your server path (recommended using ubuntu 18 - 24) as root user.

2. place this folder on root folder

3. run script starter.sh using command `bash starter.sh`

4. type `export GOROOT=/usr/local/go` and enter

5. type `export GOPATH=$HOME` and enter

6. type `export PATH=$GOPATH/bin:$GOROOT/bin:$PATH` and enter

7. type `nano .profile` and add GOROOT=/usr/local/go, export GOPATH=$HOME, export PATH=$GOPATH/bin:$GOROOT/bin:$PATH

example:

![Screenshot 2022-09-01 092200](https://user-images.githubusercontent.com/82330418/187818726-85d7a8f7-4b5e-486f-b7f7-40c6faac6525.png)

8. after that, press `CTRL + x` `y` `enter`

9. check you go version, type `go version`

10. if result in console is

```SHELL
go version go1.15.2 linux/amd64
```

   its means oke

11. you can edit in main.go or you can compail and run your bot using `go build main.go`

12. run app using `./main your name file`

13. you can update default database in alipdatabasego.go and upload to your drobox

14. you can update new app for command update version in bot golang via uploading new app into drobox

note: folder in drobox > golang



##REGISTER IP ADRESS

1. open folder registip

2. run script `python3 registip.py`
