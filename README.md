# proxyverif
Check socks proxies whether they are alive or non-responsive (ping through them).

# Install (any operating system)
Need to have git installed. Command line:
``` shell
git clone git@github.com:equwal/proxyverif.git
cd proxyverif
```
Now the necessary package must be installed from cpan

``` shell
cpan -i LWP::UserAgent
cpan -i LWP::Protocol::socks
```

# Install (Linux)

``` shell
chmod 755 checker
cat example.txt | checker -v
```
For a more friendly but harder to monitor output:
``` shell
cat example.txt | checker | tee success.txt
```
# Install (Windows)
Install strawberry perl
http://strawberryperl.com/
Run the checker
``` shell
type example.txt | checker >success.txt
```
or watch the verbose version
``` shell
type example.txt | checker -v
```
