##### ÖDEV 2 : ADAM ASMACA

Adam Asmaca Oyunu
1. Belirlediğin kelimelerden rasgele bir kelime seç
2. Kullanıcıya kelimeyi alt tireli şeklinde uzunluğu göster.
3. Örneğin python için _ _ _ _ _ _ yazdır kullanıcı kaç harf olduğunu anlasın
4. Kullanıcıya harf tahminini sor 
5. Eğer doğru harf tahmin ederse bulduğu harfi ve daha önce bulduklarını kullanıcıya göster
	örn : p _ t _ _ n
6. Her harf tahmininden sonra kelimenin tamamını tahmin etmek ister misiniz sorunu yönelt
7. Y dediğinde kullanıcıdan tüm kelime tahmini al ve kontrol et, doğru değilse yeni harf tahmini yapmasını iste
8. N dediğinde 4. adıma dön
9. Kullanıcı kelimeyi doğru tahmin edince doğru bildiğini belirten mesaj ekrana yazdır
10. Yeni oyun için Y çıkmak için N girmesini iste
11. Y girer ise 1. adıma dön
12. N girer ise oyundan çık


Not : Kullanıcının 6 tahmin hakkı var.  6. hakkını kullandığında oyunu kaybeder. 
6. hakkına kadar her kullandığı hakta aşağıdaki adam asma şekilleri sırasıyla gösterilir.

```python
resim = ["""
   +---+
   |   |
       |
       |
       |
       |
--------""","""
   +---+
   |   |
   O   |
       |
       |
       |
--------""","""
   +---+
   |   |
   O   |
   |   |
       |
       |
--------""","""
   +---+
   |   |
   O   |
  /|   |
       |
       |
--------""","""
   +---+
   |   |
   O   |
  /|  |
       |
       |
--------""","""
   +---+
   |   |
   O   |
  /|  |
  /    |
       |
--------""","""
   +---+
   |   |
   O   |
  /|  |
  /   |
       |
--------"""]
```
