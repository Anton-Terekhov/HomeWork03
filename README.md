# HomeWork03
Работа с LVM на имеющемся образе /dev/mapper/VolGroup00-LogVol00 38G 738M 37G 2% /
Уменьшить том под / до 8G
Выделить том под /home
Выделить том под /var
/var - сделать в mirror
/home - сделать том для снэпшотов
Прописать монтирование в fstab
Попробовать с разными опциями и разными файловыми системами ( на выбор)
- сгенерить файлы в /home/
- снять снэпшот
- удалить часть файлов
- восстановится со снэпшота
- залоггировать работу можно с помощью утилиты script

* на нашей куче дисков попробовать поставить btrfs/zfs - с кешем, снэпшотами - разметить здесь каталог /op
