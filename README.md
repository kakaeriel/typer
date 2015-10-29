### Typer (Answer)

##### Sebutkan library apa saja yang dipakai, website library itu dimana, dan dokumentasi library itu ada dimana ?
* jQuery 
  - Web : <http://jquery.com/> 
  - Docs : <http://api.jquery.com/> 
* Backbone
  - Web : <http://backbonejs.org/> 
  - Docs : <http://backbonejs.org/> 
* UnderscoreJS
  - Web : <http://underscorejs.org/> 
  - Docs : <http://underscorejs.org/> 
* Bootstrap
  - Web : <http://getbootstrap.com/> 
  - Docs : <http://getbootstrap.com/getting-started/>
* jQuery UI (unused)
  - Web : <http://jqueryui.com/> 
  - Docs : <http://api.jqueryui.com/>

##### Aplikasi itu 'laggy'. Kenapa? Bagaimana cara membuat animasi lebih 'smooth'?
* Untuk membuat animasi menjadi smooth, gunakan CSS Transition
  ```sh 
  $(this.el).css({position: 'absolute', 'transition': 'all 1s ease-out'});
  ```
* Untuk meningkatkan performance : 
  -  Compress library JS dan CSS yang di gunakan.
(http://plugins.netbeans.org/plugin/49666/js-css-minify-compress)
  -  Hapus library yang tidak digunakan, check dengan menggunakan Google Chrome audits. (bootstrap-theme.css, jquery-ui-1.10.4.css, jquery-ui-1.10.4.min.js)
  -  Hapus CSS rules yang tidak di gunakan, check menggunakan Google Chrome Audits dan hapus menggunakan Grunt-Uncss. (https://github.com/addyosmani/grunt-uncss)

##### Aplikasi itu tidak akan jalan di salah satu 3 browser populer (Chrome, Firefox, Internet Explorer)? Kenapa? Solusinya hanya menghapus satu character di code, character yang mana?

Saya mencoba menjalankan aplikasi di 3 browser tersebut, dan semua berjalan dengan lancar.
* Google Chrome	46.0.2490.80	Running
* Mozilla Firefox	41.0.2	Running
* IE	11	Running
* IE	10 (Developer Mode)	Running
* IE	9 (Developer Mode)	Running
* IE	8 (Developer Mode)	Running
* IE	7 (Developer Mode)	Running

