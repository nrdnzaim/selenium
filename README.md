# Selenium IDE Chrome Uzantısı Olarak Ekleme
[Buraya](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd) tıklayarak Chrome'a uzantı olarak ekleyin.
## Testleri çalıştırmak için aşağıdaki adımları izleyin.
- Uzantılardan Selenium IDE ikonuna tıklayın.
  * Selenium IDE ekranından "Open an existing project" seçeneğine tıklayın.
  * İlk olarak daha önce indirmiş olduğunuz "deepin.dev.side" projesini seçip açın.
    - Açılan projede sırasıyla; anasayfa, contact_us, profil testlerini çalıştırın. "anasayfa" testinde 2. adımda bulunan "set window size" adımında hata alırsanız kendi tarayıcınızın boyutlarına göre düzenlemeniz gerekmektedir.
  * Daha sonra Selenium IDE ekranında sağ üstte yer alan "Open project" butonuna tıklayarak "test_project.side" projesini seçip açın.
    - Açılan projede sırasıyla; home_page, explore_product, product_detail ve provider testlerini çalıştırın.
    - Tüm testlerde 2. adımda yer alan "set window size" komutunu kendi tarayıcınızın boyutlarına göre ayarlayın.
    - Tüm testlerde kullanıcı girişi yapılan adımlarda yer alan (css=.JDAKTe:nth-child(x) .w1I7fb) hedefinin x değişkeninde düzenleme yapılmalıdır. (Giriş yapmak istediğiniz hesabın kaçıncı sırada olduğu bilgisi.)
    - Kullanıcı girişi tarayıcınızda tek bir adres üzerinden yani hesap seçimi yapılmadan gerçekleşiyorsa tüm testlerde komutlar arasından (css=.JDAKTe:nth-child(1) .w1I7fb) adımı yorum satırı haline getirilmelidir. (komutun içerisinde yer alan "//" simgesine tıklayarak yorum satırı haline getirebilirsiniz.)
    - "provider" testinde 16. adımda, 97. adımda ve 160. adımda çalışma durur ve bilgisayardan gerekli dosyalar seçilip yüklenir. Sonrasında bu adımlardan sonraki adımlarda sağ tık yapılarak "Play from here" seçeneğine tıklanır.
    - Son olarak "provider" testinde 176. adımda test durur ve provider verify edildikten sonra yine bu adımda sağ tık yapılarak "Play from here" seçeneğine tıklanır.
