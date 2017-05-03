# 3. Püf Noktalar

## Alias Tanımlama
`nano ~/.bash_profile` komutunu kullanarak `.bash_profile` dosyasını açın
> alias dockerlogin='ssh www-data@adnan.local -p2222'  # Aliasınızı .bash_profile e ekleyin

## Özel bir dizine çabuk gidebilmek için
nano ~/.bashrc
> export hotellogs="/workspace/hotel-api/storage/logs"

```bash
source ~/.bashrc
cd $hotellogs
```

