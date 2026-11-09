
# Projenin Adı: Kod-Asistan v0.1
## Projenin Amacı: Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı
olacak bir dijital asistan tasarlamak
## Projenin Hedefleri: Bu asistanın ilerleyen zamanlarda hangi özellikleri kazanacağını
(örneğin v1.0 Akıllı Menü, v2.0 Veri Saklama) maddeler hâlinde yazınız.
## Sözde Kod (Pseudocode) Adımları:
1. BAŞLA
2. saat = 1 değerini ata
3. DÖNGÜ BAŞLAT (Sonsuz veya veri akışı bitene kadar)
    a. Sensörden o anki su seviyesini oku (su_seviyesi)
    b. EĞER su_seviyesi > 50 İSE:
         - Ekrana yazdır: "Kritik Eşik Aşıldı!"
         - Ekrana yazdır: "Tahliye Saati:", saat
         - Ekrana yazdır: "Kritik Su Seviyesi:", su_seviyesi, "metre"
         - DÖNGÜYÜ KIR (Bitir)
       DEĞİLSE:
         - Ekrana yazdır: saat, ". saat: Kapaklar kapalı, su seviyesi normal (", su_seviyesi, "m)"
         - saat = saat + 1 (Saati bir sonraki saate ilerlet)
    c. DÖNGÜ SONU
4. BİTİR
## Kaynakça
Meb Programlama Temelleri Ders Modülü
