## settings

```
$ sudo yum install zsh

$ sudo yum install httpd24 php54 php54-mysql php54-pecl-memcached
$ sudo ln -s /home/isucon/etc/supervisord.conf /etc/supervisord.conf
$ sudo vi etc/supervisord.conf

perl to false

$ sudo service httpd restart
```

## やったこと
・環境構築（Git、ln、PHPに切り替え）
・select文を見てIndexを貼った：1434
・my.confでbuffer_poolなどをいじった：1768
・カーネルいじった(以降workload=4)：2271
・SQLの無駄なselect *をカラム指定：変化なし
・Nginxを導入しリバプロした：2514
・Apacheのリバプロを削除した：2592
・HTMLの改行を削除した：2618
・無駄なCount文を削除した：2848
・foreach内でいちいちしていたselect文を削除した：3047
