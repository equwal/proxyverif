# proxyverif
Check socks proxies whether they are alive or non-responsive (ping through them).

# Install

``` shell
git clone git@github.com:equwal/proxyverif.git
cd proxyverif
chmod 755 checker
cat example.txt | checker -v
```
For a more friendly but harder to monitor output:

``` shell
cat example.txt | checker | tee success.txt
```
