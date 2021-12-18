# FinalExam_WEBRO_C

Members name :
- Fitrah Mutiara (0511194000126)
- Aprilia Annisa Suryo (05111940000199)
- Nadia Tiara Febriana (05111940000217)

## Cara Menjalankan Web

- Step 1 : Install Eclipse, Tomcat, MySQL Community dan MySQL connector, dan Java JDK
- Step 2 : Set up Tomcat di Eclipse
- Step 3 : Open project di Eclipse dengan cara klik File -> Open Project From File System -> pilih foldernya
- Step 4 : Atur database
- Step 5 : Run projectnya

---------------------------------------------------------------------------------------------------------------------------------------

### Step 2 : Set up tomcat di Eclipse JEE
Referensi: [Apache Tomcat on Eclipse](https://crunchify.com/step-by-step-guide-to-setup-and-install-apache-tomcat-server-in-eclipse-development-environment-ide/)

-------------------------------------------------------------------------------------------------------------------------------------------

### Step 3 : open project di eclipse
klik File -> Open Project From File System -> pilih foldernya

-------------------------------------------------------------------------------------------------------------------------------------------

### Step 4 : atur database
1. Pada bagian tab, klik Windows -> Perspective -> Open Perspective -> Other -> Database Development
2. Di Database Explorer -> klik kanan Database Connections -> klik New -> pilih MySQL -> ganti Namenya(optional) -> Next -> Di drivers klik simbol sebelah segitiga(New Drivers Definition) -> pilih MySQL JDBC Driver versi terbaru -> lanjut klik Tab "Jar List"
3. Pada tab Jar List -> klik Add Jar -> cari direktori folder di mana mysql connector berada -> tekan OK
4. Di General -> isi username dgn "root" dan password -> klik Test Connection -> kalo ping success klik OK -> klik Finish

-------------------------------------------------------------------------------------------------------------------------------------------

### Step 5 : Run project
Klik projectnya -> klik tombol run-> pilih run on servers -> maka otomatis terbuka di internet browser yang kita gunakan

--------------------------------------------------------------------------------------------------------------------------------------------

### Kendala dalam pengerjaan
- Masih mendapatkan error message sehingga website tidak bisa dijalankan
- Kesulitan menemukan web hosting yang gratis yang dapat mensupport MySQL untuk databasenya
