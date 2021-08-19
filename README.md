# OverTheWire_Bandit
Notes on Over The Wire, Bandit

~ =  |
| Level | Key | Command | Description |  
|-------|-----|---------|-------------|
Level0|boJ9jbbUNNfktd78OOpsqOltutMc3MY1|ssh bandit0@bandit.labs.overthewire.org -p 2220|ssh User@domain, -p is port
level1|CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9|cat ./-
level2|UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK|cat ./spaces\ in\ this\ filename
level3|pIwrPrtPN36QITSp3EQaw936yaFoFgAB|cd inhere/ - cat .hidden
level4|koReBOKuIDDepwhWk7jZC0RTdopnAYKh|file ./* - cat ./-file07
level5|DXjZPULLxYr17uwoI01bNLQbtFemEgo7|find ./ -size 1033c
level6|HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs|find ./ -user bandit7 -group bandit6 -size 33c
level7|cvX2JJa4CFALtqS87jk27qwqGhBM9plV|cat data.txt ~ grep millionth
level8|UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR|cat data.txt ~ sort ~ uniq -c
level9|truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk|strings data.txt ~ grep "======="
level10|IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR|base64 -d data.txt
level11|5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu|ROT13
level12|8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL|tar -xf - gunzip - bunzip2 xxd -r
level13|4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e|ssh -i RSA-file User@localhost -p 2220
level14|BfMYroe26WYalil77FoDi9qh59eK5xNr|nc localhost 30000|Connects you to target, TCP 
level15|
level16|
