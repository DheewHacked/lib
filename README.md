#!/data/data/com.termux/files/usr/bin/bash
# FB React Tools
# by まやちゃん

black='\033[1;30m'
red='\033[1;31m'
green='\033[1;32m'
yellow='\033[1;33m'
blue='\033[1;34m'
purple='\033[1;35m'
cyan='\033[1;36m'
white='\033[1;37m'


echo -e $blue"   _______    ___               __  ";
echo -e $blue"  / __/ _ )  / _ \___ ___ _____/ /_ ";
echo -e $blue" / _// _ |  / , _/ -_) _  / __/ __/ ";
echo -e $blue"/_/ /____/ /_/|_|\__/\_,_/\__/\__/ ";
echo -e $red"              Modified by まやちゃん ";
echo -e $green" Thanks to: ";
echo -e $green" https://github.com/tomiashari/fb-autoreaction";
echo -e $green" https://github.com/dfmcvn/getFBtoken ";
echo -e $green" https://github.com/tro1d/bot-reaction-gettoken";
echo -e $white"\n";
sleep 1
echo "1 ) Input nomer atu jika kamu belum install php";
echo "2 ) Input nomer dua jika kamu sudah install php";
echo "99) Input nomor ini untuk keluar";
read -p "[まやちゃん] >"  act;

if [ $act = 1 ] || [ $act = 1 ]
then
apt update -y && apt upgrade -y
pkg install -y php
clear
sleep 1
php 1.php
clear
php 2.php
sleep 2
clear
php 3.php
fi

if [ $act = 2 ] || [ $act = 2 ]
then
apt update -y && apt upgrade -y
clear
php 1.php
clear
php 2.php
sleep 2
clear
php 3.php
fi

if [ $act = 99 ] || [ $act = 99 ]
then
echo -e $red'untuk kamu para pemula'
sleep 1
echo -e $red'jangan berhenti mencari ilmu'
sleep 2
echo -e $red'karna mencari topik lebih susah'
sleep 1
echo -e $red'(╥_╥)'
sleep 1
echo -e $red'sekian dari saya'
echo -e $cyan'まやちゃん '
echo -e $cyan'www.facebook.com/pudtraa7x'
sleep 2
exit
fi
