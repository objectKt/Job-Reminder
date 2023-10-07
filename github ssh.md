```
Administrator@PC-20190831OQEE MINGW64 ~/Desktop
$ cd ~/.ssh

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$ ls
id_rsa  id_rsa.pub  known_hosts  known_hosts.old

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$ ssh-keygen -t rsa -C "xxxx@qq.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Administrator/.ssh/id_rsa):
/c/Users/Administrator/.ssh/id_rsa already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Administrator/.ssh/id_rsa
Your public key has been saved in /c/Users/Administrator/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:gdQsja9TgeZGWpujABjyMMaGNd5qkcKZVsghK0vV/Zs xxxx@qq.com
The key's randomart image is:
+---[RSA 3072]----+
|@==o. o*         |
|O@=+ oBo=        |
|=B= .*.=o.       |
|+o.o. * oo       |
|. o. o +S o      |
| .  . o  E       |
|       .         |
|                 |
|                 |
+----[SHA256]-----+

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$ ls
id_rsa  id_rsa.pub  known_hosts  known_hosts.old

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$ cat id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQC+......

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$ ssh -T git@github.com
Hi objectKt! You've successfully authenticated, but GitHub does not provide shell access.

Administrator@PC-20190831OQEE MINGW64 ~/.ssh
$

```
