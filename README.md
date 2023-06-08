# test-sekawan

- User dan Password
- ADMIN = - username : admin
          - password : admin
 - Yang Menyetujui = - username : gudang
                     - password : gudang
                     - atau bisa di cek di table sql user untuk role selain admin, untuk passwordnya sama dengan username nya
  
 - Database Version
 Mysql versi 15.1
 
 - PHP Version
 PHP versi 8.2.6
 
 - Framework 
 Codeigniter 3 
 
 - Panduan set up aplikasi

1) edit file /Application/config/config.php, sesuaikan utk base_url nya
2) edit file /Application/config/database.php, sesuaikan setiingan databasenya
3) setelah set up, lanjut import file db_sekawan.sql ke dalam databse management nya seperti PhpMyAdmin
4) jika menggunakan xampp taruh aplikasi di dalam htdoc directory

di root folder aplikasi terdatapat file sql, database modelling nya dan contoh laporan excel hasil print
