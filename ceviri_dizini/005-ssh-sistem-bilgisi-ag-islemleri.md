## 1.4. SSH, System Info & Network Operations

<table>
   <tr>
      <td><a href="#a-bg">bg</a></td>
      <td><a href="#b-cal">cal</a></td>
      <td><a href="#c-date">date</a></td>
      <td><a href="#d-df">df</a></td>
      <td><a href="#e-dig">dig</a></td>
      <td><a href="#f-du">du</a></td>
      <td><a href="#g-fg">fg</a></td>
      <td><a href="#h-finger">finger</a></td>
      <td><a href="#i-kill">kill</a></td>
      <td><a href="#j-killall">killall</a></td>
   </tr>
   <tr>
      <td><a href="#k-last">last</a></td>
      <td><a href="#l-man">man</a></td>
      <td><a href="#m-passwd">passwd</a></td>
      <td><a href="#n-ping">ping</a></td>
      <td><a href="#o-ps">ps</a></td>
      <td><a href="#p-quota">quota</a></td>
      <td><a href="#q-scp">scp</a></td>
      <td><a href="#r-ssh">ssh</a></td>
      <td><a href="#s-top">top</a></td>
      <td><a href="#t-uname">uname</a></td>
   </tr>
   <tr>
      <td><a href="#u-uptime">uptime</a></td>
      <td><a href="#v-w">w</a></td>
      <td><a href="#w-wget">wget</a></td>
      <td><a href="#x-whoami">whoami</a></td>
      <td><a href="#y-whois">whois</a></td>
   </tr>
</table>

### a. `bg`
Durdurulan yada arkaplandaki işleri listeler.

### b. `cal`
Aylık takvimi gösterir

### c. `date`
Şuanki zaman ve saati gösterir

### d. `df`
Disk kullanımını gösterir.

### e. `dig`
Alanadının DNS bilgilerini çeker.
```bash
dig domain
```

### f. `du`
Dosya yada dizinlerin disk kullanımlarını gösterir. Bu komut hakkında daha fazla bilgi için [tıklayın](http://www.linfo.org/du.html)
```bash
du [option] [filename|directory]
```
Opsiyonlar:
- `-h` (insan okumasına elverişli) Çıktıyı kilobyte (K), megabyte (M) ve gigabyte (G) biçiminde gösterir.
- `-s` (toplam) Bir dizinin toplam disk kullanımını gösterir. 

Örnek:
```bash
du -sh pictures
1.4M pictures
```

### g. `fg`
Ön plandaki son işlem bilgisini gösterir.

### h. `finger`
Kullanıcı hakkında bilgiler gösterir.  
```bash
finger username
```

### i. `kill`
Verilen ID li işlemi sonlandırır.  
```bash
kill PID
```

### j. `killall`
Verilen isme sahip tüm işlemleri sonlandırır.  
```bash
killall processname
```

### k. `last`
Belirtilen kullanıcının son oturum açma tarihlerini listeler.  
```bash
last yourUsername
```

### l. `man`
Belirtilen komut için kullanım klavuzunu gösterir.  
```bash
man command
```

### m. `passwd`
Kullanıcı parolasını değiştirmeyi sağlar.

### n. `ping`
Sunucuya ping gönderir ve sonuçlarını yazar.  
```bash
ping host
```

### o. `ps`
İşlemlerinizi gösterir.  
```bash
ps -u yourusername
```

### p. `quota`
Disk kotanızı gösterir.  
```bash
quota -v
```

### q. `scp`
Yerelden uzağa, uzaktan yerele yada uzaktan uzağa sunucular arası dosya aktarımını sağlar.

*yerel sunucudan uzağa kopyala*
```bash
scp source_file user@host:directory/target_file
```
*uzak sunucudan yerele kopyala*
```bash
scp user@host:directory/source_file target_file
scp -r user@host:directory/source_folder farget_folder
```
Bu kouta `-P` parametresiyle özel port belirtebilirsiniz.  
```bash
scp -P port user@host:directory/source_file target_file
```

### r. `ssh`
ssh (SSH istemcisi) uzak bir makineyi yönetmenizi sağlar.  
```bash
ssh user@host
```
Bu kouta `-P` parametresiyle özel port belirtebilirsiniz.  
```bash
ssh -p port user@host
```

### s. `top`
Aktif işlemleri listeler.

### t. `uname`
Kernel bilgisini gösterir.  
```bash
uname -a
```

### u. `uptime`
Uptime bilgisini (çalışma zamanını) gösterir.

### v. `w`
Kimlerin online olduğunu gösterir.

### w. `wget`
Dosya indirir.  
```bash
wget file
```

### x. `whoami`
Giriş yapılan kullanıcı adını döndürür.

### y. `whois`
Alanadı için whois bilgisini çeker.  
```bash
whois domain
```

