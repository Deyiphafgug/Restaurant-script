python /manage.py migrate
python /manage.py runserver 
komutlarını sırasıyla çalıştırıyoruz. Ardından bize gelen linke gidiyoruz çok yüksek ihtimalle boş sayfa gelecektir bunu engellemek adına aşağıdaki adımları takip etmelisiniz.
1) "python /manage.py createsuperuser" komutunu çalıştırdıktan sonra yetkili üye bilgilerini oluşturuyoruz.
2) Ardından djangonun bize vermiş olduğu linkin sonunda /admin koyuyoruz ve az önceoluşturduğumuz kimliğin bilgileriyle giriş yapıyoruz.
3) Karşımıza çıkan modellerdeki verileri dolduruyoruz.
4) siteye tekrar gittiğimizde websiteniz kullanıma hazır olacaktır.
