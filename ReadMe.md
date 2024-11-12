## Başlangıç

git init

<!-- Bu komut, projeye git'i dahil ediyor. Bu komut yazılmadan projede git config dosyaları oluşmaz. -->

## Konfigürasyonlar

git config --global --list

<!-- Bu komut, e-mail ve username bilgilerimizin kayıtlı olup olmadığını gösteriyor. -->

git config --global user.email user@email.com

<!-- E-posta eklemek için -->

git config --global user.name username

<!-- Kullanıcı adı eklemek için -->

git add .

<!-- Dosyaları gönderme kanalına alır. -->

git commit -m "mesaj alanı"

<!-- Dosyaların gönderilmesiyle ilgili mesajı belirler. -->

git remote add origin repo_url

<!-- Bu konut, repo oluşturulduktan sonra çalıştırılır. repo-url, github'da oluşturulan projeden alınmalıdır. -->

git push -u origin

<!-- Commit ile gönderilen kodlar artık repoya gönderilir. -->
