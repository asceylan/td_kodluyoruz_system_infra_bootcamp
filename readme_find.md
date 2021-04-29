find . -mtime -1

find . -type f -newermt "yesterday"

son 1 saat

 find /home/daygeek/ -type d -mmin -60

find /home/daygeek -newermt "-1 hours" -ls

1gb olanları bul ve sil(düzenlendi)

find . -type f -size 1G -exec rm -rf {} ;

yada

find . -type f -size 1G -delete

yeni versiyonda bu

10gbdab yüksek olanlar

find . -size +10G

10 la 5 gb arası için

find . -size +5G -size -10G
