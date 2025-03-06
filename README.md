# Pelatihan Sistem Operasi 

1. Mengunduh program wget unzip xxd
```
sudo apt install wget unzip xxd
```
2. Membuat folder artists
```
mkdir artists_who_can_sing
```
3. Masuk ke folder artists
```
cd artists_who_can_sing
```
3. mendownload file zip (-O = menyimpan hasil unduhan dengan nama file tertentu )
```
wget "https://drive.usercontent.google.com/u/1/uc?id=1lV1HVmPTY_BOAK6ToXymRu7V5eVfR0ut&export=download" -O MAMAMIA.zip
```
4.melakukan unzip ke dalam folder baru (-d masukin mamamia.zip ke singing )
```
unzip MAMAMIA.zip -d singing_tutorials
```
5. masuk ke dalam folder singing
```
cd singing_tutorials
```
tambahan menampilkan list file
```
ls
```
6. Menampilkan list atribut dan file tersembunyi 
```
ls -la
```
7. Cari file NBAYoungboy
```
find .*opera*NBAYoungboy*
```
8. Menampilkan password / isi file  yg ada opera dan nbay nya
```
strings .*opera*NBAY* 
```
10. filter 1 link yg benar 
```
strings .*opera*NBAY* |grep FLAG{ 
```
11. letakkan link tersebut di flag.txt
```
strings .*opera*NBAY* |grep FLAG{ > ../ flag.txt
```
12. mundur satu folder
```
cd ..
```
13. download sebuah file baru dengan ketentuan nama “plsrunmeiamnotmalwarefr”
```
wget https://files.catbox.moe/9l4qu8 -O plsrunmeiamnotmalwarefr
```
14. dapat izin untuk execute
```
sudo chmod +x plsrunmeiamnotmalwarefr
```
15. menjalankan program tersebut
```
./ plsrunmeiamnotmalwaref
```
