# 1. Basic Operations

### a. `export`
Tüm ortam değişkenlerini gösterir. Bir değişkenle ilgili detayları almak istiyorsanız: echo $DEGISKEN_ADI
```bash
export
```
Örnek:
```bash
$ export
AWS_HOME=/Users/adnanadnan/.aws
LANG=en_US.UTF-8
LC_CTYPE=en_US.UTF-8
LESS=-R

$ echo $AWS_HOME
/Users/adnanadnan/.aws
```

### b. `whereis`
whereis komutu sistem tarafından otomatik olarak oluşturulan bir veritabanında çalıştırılabilir dosyalar, kaynak dosyalar ve manuel sayfalarını arar.
```bash
whereis name
```
Örnek:
```bash
$ whereis php
/usr/bin/php
```

### c. `which`
which komutu $PATH ortam değişkenindeki çalıştırılabilir dosyaları arar. Bu komut çalıştırılabilir dosyanın tam adresini (full path) yazdırır.
```bash
which program_name 
```
Örnek:
```bash
$ which php
/c/xampp/php/php
```

### d. clear
Ekrandaki içerikleri temizler.

