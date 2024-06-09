Latihan selanjutnya kita akan membuat 2 halaman html yakni home dan juga blog dimana nantinya kedua halaman tersebut akan saling terhubung 1 dengan yang lainnya. Bentuk tampilannya adalah seperti ini :  
  
![Alt text](https://i.ibb.co/ZH3BKST/pkr11.png)  
  
Untuk membuat tampilan seperti ini buat file baru dengan nama `home.html` lalu tuliskan kodenya seperti ini:  
  
```html title="home.html"
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML</title>
</head>

<body>
    <center>
        <img src="https://miro.medium.com/v2/resize:fit:792/1*lJ32Bl-lHWmNMUSiSq17gQ.png" height="150">
        <h1>Belajar HTML & CSS</h1>
        <p>Website pertama saya</p>
        <hr>
        <a href="home.html">Home</a>
        <a href="blog.html">Blog</a>
        <hr>
        <table border="1">
            <tr bgcolor="#ffcc33">
                <th>No</th>
                <th>Materi</th>
                <th>Gambar</th>
                <th>Ket</th>
            </tr>
            <tr>
                <td>1</td>
                <td>HTML</td>
                <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png"
                        height="100"></td>
                <td>belajar html</td>
            </tr>
            <tr>
                <td>2</td>
                <td>CSS</td>
                <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/180px-CSS3_logo_and_wordmark.svg.png"
                        height="100"></td>
                <td>belajar css</td>
            </tr>
        </table>
    </center>
</body>

</html>
```  
  
!!!Penjelasan
    - `<center>` : digunakan untuk membuat objek menjadi ke tengah  
    - `<img src="https://miro.medium.com/v2/resize:fit:792/1*lJ32Bl-lHWmNMUSiSq17gQ.png" height="150">` : tag **img** digunakan untuk menampilkan gambar, atribut **src** digunakan untuk memilih file gambar yang akan ditampilkan (url online) *alamat urlnya harus berupa gambar / bertipe gambar seperti jpg,png,gif,dll* , **height** adalah atribut untuk mengatur tinggi gambar  
    - `<hr>` : digunakan untuk membuat garis secara horizontal  
    - `<a href="index.html">Home</a>` : digunakan untuk hyperlink / membuat suatu objek dapat di klik, **href** berisikan sebuah url dimana ketika objek di klik akan menuju ke url tersebut  
    - `<table border="1">` : digunakan untuk membuat tabel, **border** adalah garis di sekeliling tabel (angka 1 nya adalah ketebalan garis tersebut jika diisi lebih besar maka garis akan menjadi lebih besar)  
    - `<tr bgcolor="#ffcc33">` : **Table Row** digunakan untuk membuat baris di tabel, atribut **bgcolor** untuk memberikan warna background pada baris tsb  
    - `<th>` : digunakan untuk membuat judul pada tabel  
    - `<td>` : digunakan untuk mengisi data pada tabel  
      
Selanjutnya kita akan membuat tampilan blog nya yang bentuk tampilannya seperti ini:  
  
![Alt text](https://i.ibb.co/SfHDyQg/pkr12.png)  
  
Untuk membuat tampilan seperti ini buat file baru dengan nama `blog.html` lalu tuliskan kodenya seperti ini:  

```html title="blog.html"
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML</title>
</head>

<body>
    <center>
        <img src="https://miro.medium.com/v2/resize:fit:792/1*lJ32Bl-lHWmNMUSiSq17gQ.png" height="150">
        <h1>Belajar HTML & CSS</h1>
        <p>Website pertama saya</p>
        <hr>
        <a href="home.html">Home</a>
        <a href="blog.html">Blog</a>
        <hr>
    </center>
    <h2>Blog</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png"
        height="50" hspace="10" align="left">
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus sed iusto rerum ipsa ducimus tempore saepe
        aspernatur, reiciendis quisquam iure nemo nesciunt, animi recusandae aperiam suscipit excepturi labore nobis ad?
        Vero, at adipisci facere dolor reprehenderit libero non corporis aspernatur labore. Inventore quos suscipit
        harum fuga, sint eveniet sapiente placeat, eaque nihil dolor, eius quae exercitationem alias laudantium unde
        doloremque. Ullam, quaerat qui necessitatibus at enim vero eaque exercitationem dolor eligendi debitis nemo a,
        esse quia voluptas iure fugit itaque voluptatem? Earum commodi rem ullam ipsum dignissimos sit tenetur eos.
        Quasi numquam tempora mollitia dicta ut, voluptate iure voluptatibus esse aut necessitatibus nisi illo id fugiat
        exercitationem praesentium quibusdam ab eos vero? Iusto eum sed aperiam, velit distinctio veniam dolores!
        Veritatis quaerat quibusdam, numquam voluptatibus aut voluptate esse dolore, omnis, praesentium nobis possimus
        debitis delectus. Veniam ab fuga accusantium. Voluptas dignissimos maiores est dolore voluptatem quos blanditiis
        nemo et voluptatibus!</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum esse aliquid aut vel obcaecati sit itaque id
        minima sint? Impedit exercitationem nostrum minima velit consectetur culpa beatae. Quas, minima culpa.
        Culpa veniam molestiae nulla ab quae sit esse quasi sapiente eum a praesentium officiis fugit voluptas deserunt,
        nam provident et mollitia animi! Illum ab libero assumenda eligendi aut ad temporibus.
        Nobis facere tenetur eius beatae quidem optio molestias qui. Tenetur placeat culpa odio molestias, recusandae
        praesentium tempora possimus, exercitationem aliquam quas cum dolorem, qui quasi minima ut voluptate nesciunt
        temporibus.
        Tempora minus eaque et ad, beatae quae cum fugit iusto sit illum at saepe repellat alias quidem labore ea
        corrupti vitae odit in quis pariatur veniam molestiae dicta adipisci. Sapiente!
        Maxime eligendi autem accusamus dicta, necessitatibus similique. Numquam beatae dolore eius rerum mollitia
        molestiae at delectus veniam. Debitis blanditiis facilis eos, atque quo vel dignissimos qui consectetur ex
        repellendus facere?</p>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/180px-CSS3_logo_and_wordmark.svg.png"
        height="50" hspace="10" align="right">
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores, itaque quod. Unde id, dignissimos
        repudiandae voluptatem totam voluptate corporis distinctio, vel provident in excepturi sunt quam vitae eum qui
        inventore?
        Quasi iure velit possimus, quibusdam modi excepturi? Magni reiciendis, amet consequatur odit error commodi velit
        voluptatum expedita laudantium veniam nobis esse ad sunt eos recusandae ratione aspernatur tenetur sequi
        explicabo.
        Quidem deleniti a dignissimos debitis ad, dolor est, voluptatem voluptates tempore similique doloribus quo ex.
        Labore pariatur id corrupti neque adipisci et quam alias porro praesentium harum, ratione dolor magni.
        Animi facilis sunt dicta, odio nulla suscipit voluptatem perspiciatis asperiores ducimus necessitatibus!
        Mollitia velit quod ipsam minima sit iste laboriosam voluptatibus magnam fugit facere quasi pariatur, quaerat,
        eos est inventore.
        Facere debitis, alias qui maiores harum in explicabo, veniam eos tempore, eum dolore ipsum voluptates nostrum
        unde ut architecto officiis blanditiis a assumenda perferendis incidunt. Aliquid mollitia beatae incidunt illum?
    </p>

</body>

</html>
```  
  
!!!Penjelasan
    - pada halaman blog ini kita akan menampilkan 3 buah paragraf dimana paragraf ke 1 & ke 3 mempunyai gambar sedangkan yang ke 2 tidak  
    - perhatikan pada paragraf ke 1 & ke 3, gambar dengan tulisan bisa sejajar dikarenakan pada tag `<img>` terdapat sebuah atribut `align` baik itu left (posisi dikiri) / right (posisi dikanan)
    - `hspace` adalah sebuah jarak horizontal (kiri dan kanan) yang ada pada atribut img 