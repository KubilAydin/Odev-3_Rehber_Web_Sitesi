# Rehber Web Sitesi Oluşturma

## Rehber Web Sitesinde Yapılanlar.
* Her container için özel classlar veya idler oluşturuldu. 
* Linkler flex ile oluşturuldu yatay olarak sıralandı. 
* Özel cardlar oluşturuldu. (Responsive değil.)
* Footer Oluşturuldu.
* Responsive form oluşturuldu.
 
  

## Github page ile yayınlandı.
### [Bu link ile ulaşabilirsiniz](https://kubilaydin.github.io/Odev-3_Rehber_Web_Sitesi/)
 
## Özel Yapılan İçerikler Şunlardır..
* Navbar oluşturuldu.
```
        <div class="title">
            <h2>Kubilay Aydın</h2>
        </div>
            <div class="links">
                <a href="index.html">Anasayfa</a>
                <a href="iletisim.html" target="_blank">İletişim</a>
                <a href="servisler.html" target="_blank">Servisler</a>
                <a href="hakkinda.html" target="_blank">Hakkında</a> 
            </div>
```
* Linklere özel ayrı bir still oluşturuldu.
* Cards yapısı oluşturuldu.
```
    <article class="main">
        <div class="card">
            <div class="imgposition">
                <img src="img/CSSDesign.png" alt="html">
            </div>      
            <div class="cardbody">
                <h4 class="cardtitle">Style'lendirme</h4>
                <p class="cardtext">Web sitesi güzel bir görünüş</p>
            </div>
        </div>
        <div class="card">
            <div class="imgposition">
                <img src="img/JSDesign.jpg" alt="html" class="img-fluid">
            </div> 
            <div class="cardbody">
                <h4 class="cardtitle">Kullanıcıyla Etkileşim</h4>
                <p class="cardtext">Kullanıcının deneyimini artıralım.</p>
            </div>
        </div>
        <div class="card">
            <div class="imgposition">
                <img src="img/ReactDesign.jpg" alt="js" class="img-fluid">
            </div>                  
            <div class="cardbody">
                <h4 class="cardtitle">Daha hızlı çözümler için Kütüphame</h4>
                <p class="cardtext">Geniş bir kütüphane <br> <q>Açıl susam açıl</q></p>
            </div>
        </div>
    </article>
```

* Responsive Form oluşturuldu.
```
    <article class="coms">
        <div class="lists">
            <h2 class="list-title">İletişim Bilgilerim</h2>
            <ul>
                <li style="width: 33%;">Mimar Sinan Mah. Şair Ruhi Sokak Aydın Ap. 30/4</li>
                <li> Telefon: +90 531 253 4552</li>
                <li style="width: 33%;"> Mail: kubilay.aydin.aydin@gmail.com</li>
            </ul>
            <div class="description">
                <p>Aşağıdakı formu doldurarak sizinle iletişime geçelim.</p>
            </div>
            <div class="communication">
                <form action="submit.html">
                    <div class="row">
                        <div class="col-25">
                            <label for="fname">Adınız:</label>
                        </div>
                        <div class="col-75">
                            <input type="text" id="fname" placeholder="Adınız:">
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-25">
                            <label for="lname">Soyadınız:</label>
                        </div>
                        <div class="col-75">
                            <input type="text" id="lname" placeholder="Soyadınız:">
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-25">
                            <label for="mail">Mailiniz:</label>
                        </div>
                        <div class="col-75">
                            <input type="email" id="mail" placeholder="Mailiniz:">
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-25">
                            <label for="message">Mesaj:</label>
                        </div>
                        <div class="col-75">
                            <textarea name="message" id="message" placeholder="Mesajı buraya giriniz."></textarea>
                        </div>
                    </div>
                    <div class="row">
                        <input type="submit" value="Gönder">
                    </div>
                </form>
            </div>
        </div>
    </article>
```
* Style Kısmı aşağıdaki gibidir.
```
    .row {
        height: 60px;
    }
    input[type=text], input[type=email], select, textarea {
    width: 95%;
    padding: 12px;
    border-radius: 4px;
    resize: vertical;
    }
    input[type=submit] {
        float: center;
        width: 33%;
        padding: 12px 50px 12px 50px;
        margin-top: 12px;
        font-size: 16px;
    }
    label {
        padding: 12px 0 12px 0;
        display: inline-block;
    }
    .col-25 {
        float: left;
        color: #ffff;
        width: 25%;
    }
    .col-75 {
        margin-top: 6px;
        float: left;
        color: #FFFF;
        width: 75%;
    }
```
* Footer oluşturuldu.
```
    <footer class="footer">
        Designed by Kubilay Aydın
    </footer>
```
