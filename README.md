İki metin arasındaki en uzun ortak alt dizileri (karakter sıralaması korunarak) bulur ve bunları ekrana bastırır.
Metin karşılaştırmaları, DNA dizilimi, sürüm kontrol sistemleri gibi alanlarda benzerlik ölçümü için LCS hesaplamak gerekir. Bu program da bu amaçla en uzun ortak alt diziyi tespit eder.
Boşlukları siler (removeSpaces)
Dinamik programlama matrisleri (L, B) oluşturulur:
L[i][j]: İlk i karakter ve ilk j karakterin LCS uzunluğunu tutar.
B[i][j]: Geriye doğru izleme yaparken hangi yönden geldiğimizi tutar.
findLCS fonksiyonu ile matrisi kullanarak tüm LCS yolları geri izlenir ve yazdırılır.
Matrisler ve sonuçlar ekrana bastırılır, bellek temizlenir.
