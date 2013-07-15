# Mac OS X 个版本清空 DNS 缓存命令 #

### Mac OS X 10.4.x 及早期版本 ###
 
> sudo lookupd -flushcache
 
### Mac OS X 10.5.x - 10.6.x 及早期版本 ###
 
> sudo dscacheutil -flushcache
 
### Mac OS X 10.7.x - 10.8.x 及早期版本 ###
 
> sudo killall -HUP mDNSResponder
