# githubb
git config : e-posta gibi kullanıcıya özgü yapılandırma değerlerini ayarlamak için kullanılır.
git config –global user.name “[isim]”  
git config –global user.email “[e-posta adresi]”
git init : Bu komut yeni bir GIT dizini oluşturmak için kullanılır.
git init [repository adı]
git add :
Git add komutu, dizine dosyalar eklemek için kullanılabilir.
git add [dosya-adi]  örnek: git add temp.txt
git clone :
Bu komut, mevcut bir URL’den bir havuz elde etmek için kullanılır.
git clone [url]
Dizin uzaktaki bir sunucuda bulunuyorsa, şunu kullanın:
git clone alex@93.188.160.58:/path/to/repository
git commit :
Bu komut, dosyayı sürüm geçmişinde kalıcı olarak kaydeder veya anlık görüntüler.
git commit -m “[Commit mesajınız]”
git status : Dosyaları listeler.
git status
git push :
Yapılan değişiklikleri çalışma diziniyle ilişkili uzak dizinin ana dalına gönderir.
git push [variable name] master
git diff :
Henüz aşamalı olmayan dosya komutlarını gösterir.
git diff
git reset :
Dosyanın aşamasını kaldırır ancak içeriğini korur.
git reset [dosya-adi]
git rm :
Dosyayı çalışma dizininizden siler.
git rm [dosya-adi]
git log :
geçerli dalın sürüm geçmişini listelemek için kullanılır.
git log
git show :
Bu komut, belirtilen taahhüdün meta verilerini ve içerik değişikliklerini gösterir.
git show
git tag :
Belirtilen işlemi etiketlemek için kullanılır.
git tag [commitID]
git branch :
geçerli depodaki tüm yerel dalları listeler.
git branch
Yeni bir dal oluşturur : 
git branch [branch name]
git checkout :
bir daldan diğerine geçmek için kullanılır.
git checkout [branch name]
git merge :
belirtilen dalın geçmişini geçerli dalla birleştirir.
git merge [branch name]
git remote :
Yerel depoyu uzak sunucuya bağlar.
git remote add [variable name] [Uzak Sunucu Linki]
git push :
ana dalın taahhüt edilen değişikliklerini uzak havuzunuza gönderir.
git push [variable name] master
git pull :
uzak sunucudaki değişiklikleri çalışma dizininize getirir ve birleştirir.
git pull [Repository Link]
git stash :
değiştirilen tüm izlenen dosyaları geçici olarak saklar.
git stash save
