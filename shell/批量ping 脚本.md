批量ping 脚本
============
```
#!/bin/bash
A=`cat ip`
for B in $A
do
{
ping  -i 1 -c 172800   $B >> $B.txt

}&
done
```
