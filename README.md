$ ssh-keygen -o
Generating public/private ed25519 key pair.
Enter file in which to save the key (/c/Users/DELL/.ssh/id_ed25519):
Created directory '/c/Users/DELL/.ssh'.
Enter passphrase for "/c/Users/DELL/.ssh/id_ed25519" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/DELL/.ssh/id_ed25519
Your public key has been saved in /c/Users/DELL/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:ImM5tWaH6/zUh8QUQbnq6baEQnymiUvKNM9l6YL5Su8 My Dark World@DESKTOP-1LKHTA2
The key's randomart image is:
+--[ED25519 256]--+
|         .+o     |
|          ..     |
|      .   ..     |
|   . o o o.      |
|    O O S.o      |
|   + @.=.o .     |
| += ++o.o.o .    |
|+==o++ o+  .     |
|.o=E..o++.       |
+----[SHA256]-----+

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~
$ cd .ssh

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~/.ssh
$ ls -a
./  ../  id_ed25519  id_ed25519.pub

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~/.ssh
$ cat id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINgHfCgYMn1Rpi7ufdPFtpSHrPTtPSkcZWJTMa85L4YB My Dark World@DESKTOP-1LKHTA2

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~/.ssh
$ cat id_ed25519.pub^C

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~/.ssh
$ ^C

My Dark World@DESKTOP-1LKHTA2 MINGW64 ~/.ssh
$
