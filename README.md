#  Metro Kart Sistemi (və ya Mini Market Sistemi)

Bu layihə Python proqramlaşdırma dilində, fayl əsaslı (Database-siz) məlumat saxlama məntiqi ilə hazırlanmışdır[span_1](start_span)[span_1](end_span). Sistem istifadəçilərin giriş-çıxışını, balans idarəetməsini və əməliyyat tarixçəsini təmin edir.

# Xüsusiyyətlər
*   *İstifadəçi Hesabı:* Username və şifrə ilə giriş[span_2](start_span)[span_2](end_span).
*   *Təhlükəsizlik:* 3 dəfə yanlış şifrə daxil edildikdə 10 saniyəlik bloklanma (cooldown)[span_3](start_span)[span_3](end_span).
*   *Fayl Əsaslı Saxlama:* Bütün məlumatlar .json və .log fayllarında saxlanılır (Verilənlər bazası istifadə olunmur)[span_4](start_span)[span_4](end_span).
*   *Balans İdarəsi:* Alış-veriş və ya keçid zamanı balansın yoxlanılması və avtomatik çıxılması[span_5](start_span)[span_5](end_span).
*   *Tarixçə (Logging):* Hər bir uğurlu/uğursuz əməliyyatın zaman möhürü ilə qeyd edilməsi[span_6](start_span)[span_6](end_span).

# Fayl Strukturu
Şəkildəki görüntüyə uyğun olaraq faylların təyinatı[span_7](start_span)[span_7](end_span):
*   MiniMarketSystem.py (və ya MetroKartSystem.py) - Əsas proqram kodu.
*   users.json - İstifadəçi məlumatları və balans[span_8](start_span)[span_8](end_span).
*   products.json - Mövcud məhsullar və ya stansiya məlumatları[span_9](start_span)[span_9](end_span).
*   basket_enver.json - Gözləyən əməliyyatlar[span_10](start_span)[span_10](end_span).
*   history_enver.log - Sistem hadisələrinin qeydiyyatı[span_11](start_span)[span_11](end_span).

# Necə İşə Salmalı?
1. Python-un quraşdırıldığından əmin olun.
2. Terminalı açın və faylların olduğu qovluğa keçin.
3. Aşağıdakı komandanı işə salın:
   ```bash
   python MiniMarketSystem.py
