# Patika.Dev Veri Yapıları ve Algoritmalar Eğitimi
## Insertion Sort Projesi

**[22,27,16,2,18,6]**  -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

---
Birinci Aşama:
[22,27,16,2,18,6]

İkinci Aşama:
[16,22,27,2,18,6]

Üçüncü Aşama:
[2,16,22,27,18,6]

Dördüncü Aşama:
[2,16,18,22,27,6]

Beşinci Aşama:
[2,6,16,18,22,27]

Insertion Sort algoritması worst case ve average case'de (en kötü ve ortalama durum) O(n²), best case'de (en iyi durum) O(n) zaman karmaşıklığına sahiptir.

---
**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

---
Birinci Aşama:
Tüm dizi gezilir, en küçük sayının 2 olduğu anlaşılır, bu eleman dizinin ilk elemanıyla yer değiştirir.
[2,3,5,8,7,9,4,15,6]

İkinci Aşama:
İlk eleman hariç tüm dizi gezilir, en küçük sayının 3 olduğu anlaşılır, bu eleman dizinin ikinci elemanıyla yer değiştirir (zaten ikinci eleman olduğu için yer değiştirme olmaz)
[2,3,5,8,7,9,4,15,6]

Üçüncü Aşama:
İlk iki eleman hariç tüm dizi gezilir, en küçük sayının 4 olduğu anlaşılır, bu eleman dizinin üçüncü elemanıyla yer değiştirir:
[2,3,4,8,7,9,5,15,6]

Dördüncü Aşama:
İlk üç eleman hariç tüm dizi gezilir, en küçük sayının 5 olduğu anlaşılır, bu eleman dizinin dördüncü elemanıyla yer değiştirir:
[2,3,4,5,7,9,8,15,6]

....