<!DOCTYPE html>
<html>
<head>
    <title>Document</title>
</head>
<style>
    body{
        background-color: aquamarine;
    }
</style>
<body>
    <p align="center">praktek DPK</p>
    <marquee>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</marquee>
    <pre>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis<br> nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><hr>
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt<br> in culpa qui officia deserunt mollit anim id est laborum.
    </pre>
    <table border="1">
        <caption>Monthly savings</caption>
        <tr>
          <th>tag</th>
          <th>keterangan</th>
        </tr>
        <tr>
          <td>&lt;tabel&gt;</td>
          <td>tag yang digunakan untuk mendefinisikan sebuah tabel</td>
        </tr>
        <tr>
            <td>&lt;thead&gt;</td>
            <td>tag yang menunjukan bigian dari kepala tabel(header)</td>
        </tr>
        <tr>
            <td>&lt;tbody&gt;</td>
            <td>tag yang digunakan untuk mendefinisikan bigian isi dari suatu tabel(body&gt;</td>
        </tr>
        <tr>
            <td>&lt;tfoot&gt;</td>
            <td>tag ini mendefinisikan bagian penutup dari tabel(footer)</td>
        </tr>
        <tr>
            <td>&lt;tr&gt;</td>
            <td>tag utama yang digunakan untuk membuat baris pada tabel(elemen baris)</td>
        </tr>
        <tr>
            <td>&lt;td&gt;</td>
            <td>tag utama yang digunakan untuk membuat kolom tabel</td>
        </tr>
        <tr>
            <td>&lt;th&gt;</td>
            <td>fungsinya hampir sama dengan tag &lt;td&gt; pada tag &lt;th&gt; konten/teks akan tercetak tebal dan rata tengan(center)</td>
        </tr>
      </table><br />
      <form action="/action_page.php">
        <label for="fname">First name:</label><br />
        <input id="fname" name="fname" type="text" value="name" /><br />
        <label for="lname">Last name:</label><br />
        <input id="lname" name="lname" type="text" value="Name" /><br /><br />
        <input type="submit" value="kirim" />
      </form> 
    <p><a href="https://www.w3schools.com/">Visit W3Schools.com!</a></p>
	</iframe>
      <img height="25%" src="https://pelayananpublik.id/wp-content/uploads/2020/03/Screenshot_20200303-174621_1.jpg" width="25%" />
      <p><cite>Lorem ipsum</cite>consectetur adipiscing elit.</p>
    <p>Lorem ipsum dolor sit amet, <b>consectetur adipiscing elit, sed do eiusmod tempor incididunt</b> ut labore et dolore magna aliqua. <em>Ut enim ad minim veniam, quis nostrud exercitation</em> ullamco laboris nisi ut aliquip ex ea commodo consequat. <i>Duis aute irure dolor in reprehenderit in voluptate velit esse</i> cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, <mark>sunt in culpa qui officia deserunt mollit anim id est laborum</mark>.</p>
    <label class="container">One
        <input type="checkbox" checked="checked">
        <span class="checkmark"></span>
      </label>
      
      <label class="container">Two
        <input type="checkbox">
        <span class="checkmark"></span>
      </label>
      
      <label class="container">Three
        <input type="checkbox">
        <span class="checkmark"></span>
      </label>
      
      <label class="container">Four
        <input type="checkbox">
        <span class="checkmark"></span>
      </label>
      <h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
<ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
  </ul>
  <p>The<abbr title="World Health Organization">Lorem ipsum</abbr>  dolor sit amet, consectetur adipiscing elit.</p>
  Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br> 
  <table>
    <colgroup>
      <col span="2" style="background-color:red">
      <col style="background-color:yellow">
    </colgroup>
    <tr>
      <th>ISBN</th>
      <th>Title</th>
      <th>Price</th>
    </tr>
    <tr>
      <td>3476896</td>
      <td>My first HTML</td>
      <td>$53</td>
    </tr>
    <tr>
      <td>5869207</td>
      <td>My first CSS</td>
      <td>$49</td>
    </tr>
  </table>
  <dl>
    <dt>Coffee</dt>
    <dd>Black hot drink</dd>
    <dt>Milk</dt>
    <dd>White cold drink</dd>
  </dl>
  <p>My favorite color is <del>blue</del> <ins>red</ins>!</p>
  <form action="/action_page.php">
    <fieldset>
     <legend>Personalia:</legend>
     <label for="fname">First name:</label>
     <input type="text" id="fname" name="fname"><br><br>
     <label for="lname">Last name:</label>
     <input type="text" id="lname" name="lname"><br><br>
     <label for="email">Email:</label>
     <input type="email" id="email" name="email"><br><br>
     <label for="birthday">Birthday:</label>
     <input type="date" id="birthday" name="birthday"><br><br>
     <input type="submit" value="Submit">
    </fieldset>
   </form>
   <form action="/action_page.php">
    <label for="cars">Choose a car:</label>
    <select name="cars" id="cars">
      <optgroup label="Swedish Cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
      </optgroup>
      <optgroup label="German Cars">
        <option value="mercedes">Mercedes</option>
        <option value="audi">Audi</option>
      </optgroup>
    </select>
    <br><br>
    <input type="submit" value="Submit">
  </form>
  <p>WWF's goal is to: 
    <q>Build a future where people live in harmony with nature.</q>
    We hope they succeed.</p>
    <select id="cars">
        <option value="volvo">Volvo</option>
        <option value="saab">Saab</option>
        <option value="opel">Opel</option>
        <option value="audi">Audi</option>
      </select>
      <script href="scrpit.js"></script>
      <p><big>Lorem ipsum dolor sit amet, consectetur adipiscing elit</big>, <u>ed do eiusmod tempor incididunt ut labore et dolore magna aliqua</u>.<b> Ut enim ad minim veniam, quis</b> <i>nostrud exercitation ullamco,</i><small> nisi ut aliquip ex ea commodo consequat. Duis aute irure</small> <sup>dolor in reprehenderit in voluptate velit</sup> esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      <font size="1">ukuran satu</font><br>
      <font size="2">ukuran satu</font><br>
      <font size="3">ukuran satu</font><br>
      <font size="4">ukuran satu</font><br>
      <font size="5">ukuran satu</font><br>
      <font size="6">ukuran satu</font><br>
      <font size="7">ukuran satu</font><br>
      <font color="blue">warna biru</font><br>
      <font color="red>">warna merah</font><br>
      <font color="Black">warna hitam</font><br>
      <font color="yellow">warna kuning</font><br>
      <font color="green">warna hijau</font><br>
      <font color="pink">warna pink</font><br>
      <font color="white">warna putih</font><br>
      <font face="arial">jenis arial</font><br>
      <font face="tahoma">jenis tahoma</font><br>
      <font face="couriel new">jenis couriel new</font><br>
      <font face="calibri">jenis calibri</font><br>
      <font face="algariant">jenis algariant</font><br>
      <font face="times new roman">jenis times new roman</font><br>
      <font face="comic sans ms">jenis comic sans ms</font><br>
      <form>
        <p><label>Review of W3Schools:</label></p>
        <textarea >At w3schools.com you will learn how to make a website. They offer free tutorials in all web development technologies.</textarea>
        <br>
        <input type="submit" value="Submit">
      </form>
      <p>My mother has <span style="color:blue">blue</span> eyes.</p>
    </body>
</html>
