Sekarang kita akan mencoba mempraketekan html tulis / copy kode dibawah ini lalu letakan pada file index.html :  

```html title="index.html"
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pertama</title>
</head>
<body>
    <h1>Website Buatan Saya</h1>
    <p>Ini hasil pertama saya belajar html</p>
</body>
</html>
```  
  
Hasil dari kode tersebut adalah seperti ini:  
![Alt text](https://i.ibb.co/jRC1DwW/6.png)  
  
!!!Penjelasan  
    - HTML Terkenal dengan kurung nya jadi kita bisa perhatikan di semua barisnya awalnya di mulai dengan < dan diakhiri dengan >  
    - Didalam kurung tersebut diberikan istilah elemen / tag contoh `<html>` disebut tag html  
    - Bisa kita lihat bahwasannya html menggunakan bahasa inggris tapi hanya dasar saja seperti head (kepala), body (badan), dllnya.  
    - Ada 2 jenis penulisan elemen/tag :  
      
        1. Penulisan yang ada penutupnya seperti `<title>Website Pertama</title>` kita lihat diawal dan diakhir diawali dengan tag yang sama namun untuk penutupnya ada simbol `/` , lalu pada jenis ini tag kita dapat diisi dengan kata / dengan tag elemen yang lainnya  
      
        2. Penulisan yang tanpa ada penutupnya seperti `<img src="gambar.jpg">` jenis penulisan seperti ini tidak perlu kita tutup karena tidak memerlukan isi namun untuk memberikan isinya dapat diberikan dari `src="gambar.jpg"` yang biasa disebut dengan attribut  
  
    - Terdapat 2 bagian pada kode HTML yaitu head dan body
        
        - Head: bagian informasi / pengaturan dari website
        - Body: bagian isi / konten dari website  
    - `<title>Website Pertama</title>` : digunakan untuk memberikan informasi website
    - `<h1>Website Buatan Saya</h1>` : digunakan untuk membuat tampilan judul. **h** adalah header / judul sedangan **1** sebagai ukuran huruf (selain h1 ada juga h2,h3,h4,h5,h6)  
    - `<p>Ini hasil pertama saya belajar html</p>` : digunakan untuk membuat tampilan paragraf