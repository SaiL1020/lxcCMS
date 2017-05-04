# Content Management System by Xiaocong Li

## Intro
+ This is a Java Web project forked from Xiaocong Li (@lixiaocong)
+ I am working on providing a **REST service** relating to Shadowsocks
+ 中文请查看[README.zh](https://github.com/SaiL1020/lxcCMS/blob/dev/README.zh.md)

## Blog
+ Sign up / Log in by users
+ Features on articles: write, remove, modify, look-up

## Management
+ Transmission activities: add, remove, download

## Wechat Official Account
+ Ability to set the token & pull up the latest articles

## Techniques in use
+ Business Logic Layer : **spring**
+ Data Access Layer : **hibernate** + **jpa** + **mysql**
+ User Interface : **jsp** + **angular**

## Requirement on the server-side (Docker recommended)
+ mysql5.7 : need create the blog table
+ transmission-daemon : need id/pwd setting
+ aria2c : need token setting

## Future work
+ (upgrading to angular2 & websocket)
+ (option to have google ui)
+ (email supporting)
