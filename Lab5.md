# Create Local YUM repository on CentOS 7 / RHEL 7 using DVD #
    

----------


## Mount the CD/DVD ROM on the any directory of your wish, for testing mount it on /cdrom. ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xta1/v/t1.0-9/11796229_10204551504976878_2454069909584135081_n.jpg?oh=78e64e4dafbbe74528928fcf40af4f60&oe=563AA259)

## Create the new repo file ##

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfa1/v/t1.0-9/11796393_10204551504936877_7052873772964534452_n.jpg?oh=2eb24cc8610031725bdc6948d1f55ebb&oe=567268D1)
## Before installing clear the repository cache ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11828839_10204551505016879_9040746349119202794_n.jpg?oh=056809880de18532de17d077a9ee0033&oe=5683FB48)

## Install the package using the yum command ##

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfp1/v/t1.0-9/11816967_10204551505416889_6210264612475589937_n.jpg?oh=d39eafff806f9bc6fb81a5d0d9ad3256&oe=566D5B57)
## Out put will be like below ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xta1/v/t1.0-9/11239609_10204551505456890_6731595684734070749_n.jpg?oh=c6e49b450767b5f0ea6107fd1f759886&oe=563591A8)

## Install PHP, Apache web server and MySQL server on CentOS 7 ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11825060_10204551505576893_8673669872958204300_n.jpg?oh=ae1702e0226509c51ac3ad3af6d01535&oe=566C1590)

## Set SELinux to allow OwnCloud to write the data ##

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11825610_10204551505936902_8953087191221619672_n.jpg?oh=580efe788769892b34b3b6319aa1b18e&oe=5665ECA5)

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfa1/v/t1.0-9/11828613_10204551505976903_7819481667864094082_n.jpg?oh=e0d872d729d074fc80febe91f6489eb9&oe=5668D9C3)
## Allow apache in firewall ##

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtf1/v/t1.0-9/11825762_10204551506416914_3181624140776194623_n.jpg?oh=9e071300793a659e1f7c22cfaf9a2970&oe=56840D65)
## Start Apache and MariaDB ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtp1/v/t1.0-9/11707844_10204551506536917_2205792802339666035_n.jpg?oh=fa355ec0bf95da3c0ee3822b3c81f1e8&oe=56382055)

## Auto start the service at system start-up ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xaf1/v/t1.0-9/11828696_10204551506656920_90017236210315090_n.jpg?oh=8525685296d4429b934a70cdd667cf3f&oe=567F9FD4)

## Download ownCloud ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11145085_10204551507016929_4474526580339252970_n.jpg?oh=6164fb2cd8f1180afa3066d549d76898&oe=566F4FE7)

## Extract the archive ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xaf1/v/t1.0-9/11825686_10204551507096931_609389422660602074_n.jpg?oh=739400a92168a8092cde171f6fa79166&oe=566F41C1)

## Allow the web server to read and write the files on cloud directory ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfa1/v/t1.0-9/11822376_10204551507136932_4012181220666647693_n.jpg?oh=59c1bd871e7ac7694f3bcf81b79d28f8&oe=567D6120)

## Create Database ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtp1/v/t1.0-9/11836828_10204551507456940_7456233515074639971_n.jpg?oh=0feee510fd023e6aaf7602aad8e549e8&oe=566CBAD4)

## Create database called “clouddb” ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/11060085_10204551507656945_5098378332039546891_n.jpg?oh=c99f72ffdf16bd8a5ddb5e858a6d5351&oe=56744410)

## Allow “clouddbuser” to access the “clouddb” database on localhost with predefined password ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtf1/v/t1.0-9/11063784_10204551507696946_8454922376034033222_n.jpg?oh=af504b19be58ab7dcc6fae852dd9949a&oe=56820131)

## Configure Apache server ##

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11220843_10204551507816949_7955970975240464632_n.jpg?oh=14dd2785339451f48687a19f5da3181f&oe=5677BFAC)
## Remember to restart all services related to Apache server ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11220843_10204551507816949_7955970975240464632_n.jpg?oh=14dd2785339451f48687a19f5da3181f&oe=5677BFAC)

## Configure ownCloud ##
![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11825087_10204551508176958_3896481539171668477_n.jpg?oh=601a22ec881a55e926103b93d4cc1041&oe=5673F944)

![](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xft1/v/t1.0-9/11836918_10204551508376963_255890298159945946_n.jpg?oh=b1a23054cbf42d0f2ed579193183a1ef&oe=5666F999)


