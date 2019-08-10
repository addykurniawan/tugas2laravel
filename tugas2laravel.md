**``Die Dump dd()``**
=======

Die Dump ``dd()`` adalah salah satu method yang ada pada laravel, fungsi ``dd()`` mulai digunakan pada laravel 5.5 untuk memudahkan debug program.

Fungsi ``dd()`` hanya dapat melihat isi dari satu variabel saja. Karena fungsi ``dd()`` akan berhenti tepat setelah fungsi ``dd()`` digunakan dan tidak akan menjalankan program dibawahnya, seperti ``exit()`` pada PHP.

Contoh :
============
```
public function test(){
$numbers = array('one','two','three');

dd($numbers);

echo = 'Hello';



}

```
Kode ``echo = 'Hello';`` tidak akan dieksekusi karena ada kode ``add()`` dan akan berhenti pada saat kode ``add($numbers)`` dieksekusi. 

Sumber :
=====
<a href ="https://www.profio.co.id/debugging-pada-php/">Profio.co.id</a><br>
<a href ="https://laravel-news.com/laravel-5">Laravel-News.com</a><br>
<a href ="https://amahrizal.wordpress.com/2016/04/21/mendapatkan-log-query-pada-laravel/">amahrizal.wordpress.com</a><br>
<a href ="https://symfony.com/doc/current/components/var_dumper">Symfony.com</a>