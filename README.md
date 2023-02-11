# Instagram_Search_Engine

Aşağıdaki işlemleri yapabilmeniz için Instagram ve facebook hesabiniz business olmali

https://developers.facebook.com/

Facebook hesabinizla login ol

Sag ust menudeki My Apps kismina tikla

Sol tarafta apps filtresinden All Apps'i sec.

Sag taraftaki Cretap App kismina tikla

Select an app type icin isletme/business secenegini secin

Add an app name: uygulamaniza isim verin

app contact email: kontakt emailinizi yazin

Devam tusuna basin

Yeni sayfaya yonlendirileceksiniz.

- Access_token: https://developers.facebook.com/docs/facebook-login/guides/access-tokens

- Client_id: Ayarlar'dan App ID: Settings/Basic/App ID   

- Client_secret: Ayarlar'dan App Secret: Settings/Basic/App Secret  

- Page_id: Business Facebook hesabınızın ana sayfasında About sekmesine tıklayarak: Facebook Page ID

- Instagram_account_id: Instagram API tokenı sekmesinden

Bu tokenları yaratırken hesabınızda vermeniz gereken izinler:

pages_show_list
instagram_basic
instagram_content_publish
pages_read_engagement
public_profile

Uretilen tokenlarin bazilarinin suresi vardir. O yuzden kodun icinde api tokenlarin aktif 
olup olamadigini kontrol kontrol ediyoruz once. Lutfen adimlari tek tek uygulayin.