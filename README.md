# LATIHAN5DPBO2023

## Janji
Dicki Fathurohman_2103842_Ilmu Komputer LATIHAN5DPBO2023
Saya Dicki Fathurohman [2103842] mengerjakan LATIHAN 5 dalam mata kuliah DPBO, untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikan. Aamiin.

## Desain
`Class Mahasiswa`
Atribut :
- **NIM** (string)
- **Nama** (string)
- **Nilai** (string)
- **Fakultas** (string)
Method :
- **setter** untuk tiap atribut
- **getter** untuk tiap atribut

`Class Menu`
Atribut/Properties :
- **dtm** (DefaultTableModel)
- **isUpdate** (Boolean)
- **selectedID** (integer)
- **listMhs** (ArrayList<Mahasiswa>)
Method :
- **setTable** : Untuk menampilkan tabel beserta data isinya yang diambil dari listMhs
- **insertData** : Untuk menambahkan data kedalam listMhs
- **updateData** : Untuk mengupdate data yang dipilih pada tabel (diupdate dari listMhs)
- **deleteData** : Untuk menghapus data yang dipilih pada tabel (dihapus dari listMhs)
- **resetForm** : Untuk menghapus data yang diisikan pada form / mereset kembali form menjadi kosong

## Design GUI
![image](https://user-images.githubusercontent.com/100754802/226502062-82c00044-622d-4dc0-8e1f-e702ddc72bf1.png)

Pada Design GUI ini terdapat Text field untuk mengisi data NIM, Nama, dan Nilai Mahasiswa. Kemudian ada ComboBox atau Dropdown untuk memilih Fakultas.

Terdapat beberapa button yaitu :
- **Add** : Button ini untuk menambahkan data yang telah diisikan pada form
- **Cancel** : Button ini untuk menghapus data yang telah diisikan pada form / reset form
- **Update** : Button ini untuk mengupdate data pada kolom tabel yang dipilih, button ini muncul jika user memilih/mengklik kolom.
- **Delete** : Button ini untuk menghapus data pada kolom tabel yang dipilih, button ini muncul jika user memilih/mengklik kolom.

## Penjelasan Alur
Jika ingin menambahkan data, user harus mengisi textfield pada form dan memilih fakultas pada ComboBox/Dropdown yang telah disediakan. Kemudian jika user mengklik `add` maka data yang diisikan pada from akan ditambahkan dan ditampilkan pada tabel. Jika user mengklik 'cancel' maka data yang telah diisikan pada form akan direset.

Jika user mengklik salah satu kolom pada tabel, maka data pada kolom tabel tersebut akan mengisi textfield dan dropdown akan otomatis terganti. Jika user ingin merubah data, maka user harus merubah data pada textfield atau dropdown kemudian klik `update` agar data pada tabel terganti.

Jika user ingin menghapus data yang dipilih tersebut, maka user harus mengklik 'delete' kemudian melakukan konfirmasi apakah yakin ingin menghapus atau tidak, jika user klik yes maka data akan terhapus dan hilang dari tabel.

## Dokumentasi
![image](https://user-images.githubusercontent.com/100754802/226504066-1260303d-fe35-4bf1-9179-b1090e7cc364.png)

**Add Data**
![image](https://user-images.githubusercontent.com/100754802/226504385-de16aa00-612d-41e9-bb15-127b3b711110.png)

**Update Data**
![image](https://user-images.githubusercontent.com/100754802/226504484-ac82c9fc-1028-4103-ab52-1d3c6dd00f37.png)

**Delete Data**
![image](https://user-images.githubusercontent.com/100754802/226506898-aaa723d4-ea59-4a0c-bf58-ba07970d8d72.png)

![image](https://user-images.githubusercontent.com/100754802/226506929-b94d59d5-ff4f-4796-a8c3-7df951a2d704.png)


