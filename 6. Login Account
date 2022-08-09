#!/bin/sh
echo enter username
read uname
#if who | grep "^$uname "
#if who | grep "$uname "
if who | grep -w "$uname"
then
        echo exists
else
        echo not
fi
