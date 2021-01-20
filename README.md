# clock
(下面使用的是自己编译的nginx，并不是apt安装的nginx)<br>
nginx设置
````
/usr/local/nginx/sbin/nginx -c /usr/local/nginx/conf/nginx.conf
/usr/local/nginx/sbin/nginx -s reload
````

部署
````
nohup python clock.py &
disown -h %1
````
然后就可以关掉远程终端了

[效果展示](www.academics.work/clock)
