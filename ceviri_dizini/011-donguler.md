## 2.5. Loops

bash de 3 tip döngü vardır. `for`, `while` ve `until`.

`for` Sözdizimleri:
```bash
for x := 1 to 10 do
begin
  komutlar
end

for name [in list]
do
  $name bilgisini kullanabilen komutlar
done

for (( başlangıç ; bitiş_şartı ; her_döngüde_yapılacak_güncelleme ))
do
  komutlar...
done
```

`while` Sözdizimi:
```bash
while koşul; do
  komutlar
done
```

`until` Sözdizimi:
```bash
until koşul; do
  komutlar
done
```

