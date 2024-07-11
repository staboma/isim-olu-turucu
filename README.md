# Rastgele İsim Üretici

Bu Python scripti, önceden tanımlanmış listelerden rastgele seçilen ilk ve son isimleri birleştirerek rastgele isimler üretir. Bu script, `random` modülünü kullanarak bir listeden rastgele eleman seçimini ve Python'da temel string biçimlendirmesini gösterir.

## Kurulum

Bu scripti çalıştırmak için makinenizde Python yüklü olmalıdır. Python'u resmi web sitesinden indirebilir ve kurabilirsiniz: [python.org](https://www.python.org/).

## Kullanım

1. Depoyu klonlayın veya script dosyasını yerel makinenize indirin.
2. Scriptin bulunduğu dizine gidin.
3. Scripti Python kullanarak çalıştırın:

    ```bash
    python random_name_generator.py
    ```

Script, her biri rastgele seçilmiş bir ilk ve son isimden oluşan beş rastgele isim üretecektir.

## Kod Açıklaması

Script aşağıdaki bileşenlerden oluşur:

1. **random modülünün ithal edilmesi**: Bu modül, rastgele sayı üretme ve bir listeden rastgele eleman seçme işlevleri sağlar.


2. **generate_name fonksiyonunun tanımlanması**: Bu fonksiyon, verilen ilk ve son isim listelerinden rastgele birer isim seçerek birleştirir ve geri döner.


3. **İsim listelerinin tanımlanması**: Kullanılacak olan ilk ve son isimlerin listeleri tanımlanır.


4. **İsimlerin üretilmesi ve yazdırılması**: generate_name fonksiyonu beş kez çağrılarak rastgele isimler üretilir ve yazdırılır.


## Özelleştirme

İsim listelerini ihtiyaçlarınıza göre özelleştirebilirsiniz. `first_names` ve `last_names` listelerine istediğiniz isimleri ekleyerek veya çıkararak scripti özelleştirebilirsiniz.
