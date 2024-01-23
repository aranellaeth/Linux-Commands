# Linux-Commands
Some useful commands for linux terminal

Windows makinadan VPS'e bağlanmak için powershell'e bağlanmak için aşağıdaki komutu gir:

ssh root@207.180.221.246 = Sunucuya ait IP'yi yazacaksın. root yerine farklı kullanıcı ismi verdiysen eğer onu yazmalısın

rm -r klasör ve içindekileri uçurur

ls -la yüklü uygulamaları görebilirsin

kill komutu yanına top komutunu girdiğinde gözüken PID'yi girerek uygulamayı durdurursun

/ - root işareti

~ - home işareti

Apropos <komut> - komuta ait optinoları sıralı listeliyor açıklamalarıyla. (man komutunu kullanmak zor geliyorsa). Örneğin apropos passwd komutunu yazdın. çıkan sonuçlarda parantez içindeki rakamı "passwd (1)" başına yazarak ilgili man'e ulaşırsın. "man 1 passwd"

pwd - printing working directory (tell me where I am)

ls - yüklü klasörleri gösterir. ls -laht komutu ile (long listing,hidden files, human readable, total usages)

cd - change directory demek. istediğin klasörün içine gidiyorsun. geri gitmek istiyorsan eğer cd .. komutuyla bir üstüne çıkarsın. kullanıcına dönmek istiyorsan cd ~ komutunu kullanırsın.

cd /root ile başlarsan, nerede olursan ol istediğin directorye gidersin

touch <filename> klasör oluşturmanı sağlıyor. tocuc kalsor1 klasor2 .... diye oluşturabilirsin. 

touch ../<filename> bir üst klasöre oluşturursun. kendi ana root altına oluşturmak için touch ~/<filename> yazarsın. (Not: aslında asıl amacı zaman etiketi vurması. ama istediğin isimdeki dosyaları hemen ve hızlıca oluşturabiliyorsun.
