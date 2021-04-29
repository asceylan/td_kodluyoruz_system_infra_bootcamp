find . -mtime -1
[00:48]
find . -type f -newermt "yesterday"
[00:48]
--son 1 saat
[00:49]
# find /home/daygeek/ -type d -mmin -60
[00:49]
find /home/daygeek -newermt "-1 hours" -ls
[00:52]
-----1gb olanları bul ve sil(düzenlendi)
[00:54]
find . -type f -size 1G -exec rm -rf {} ;
[00:54]
yada
[00:56]
find . -type f -size 1G -delete
[00:56]
yeni versiyonda bu
[00:57]
----10gbdab yüksek olanlar
[00:57]
find . -size +10G
[00:57]
10 la 5 gb arası için
[00:58]
find . -size +5G -size -10G
