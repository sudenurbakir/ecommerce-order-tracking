# Root Cause Analysis

## Vaka: Geciken Sipariş

**Sipariş No:** CC-1001

### 1. Problem

Sipariş iki gündür hazırlanıyor ancak kargoya verilemiyor.

### 2. Tespit Edilen Durum

Sistem stokta ürün olduğunu gösterirken depoda ürün bulunamıyor.

### 3. Olası Kök Neden

Sistem stok kayıtları ile depodaki gerçek stok miktarı arasında tutarsızlık bulunması.

Bu neden, stok kayıtları kontrol edilerek doğrulanmalıdır.

### 4. İlk Aksiyonlar

- Depodaki gerçek stok miktarını kontrol etmek.
- Sistem stok kaydını incelemek.
- Tutarsızlığın nedenini ilgili ekiple araştırmak.
- Siparişin tamamlanması için uygulanabilir çözümü belirlemek.
- Müşteriyi siparişin durumu hakkında bilgilendirmek.

### 5. Önleyici Aksiyon

Sistem stoklarıyla depo stoklarının düzenli karşılaştırılması ve tespit edilen farklılıkların incelenmesi.

### 6. Başarı Ölçütü

- Stok uyuşmazlığı nedeniyle geciken sipariş sayısının azalması.
- Sipariş sorunlarının çözülme süresinin kısalması.

### Not

Bu çalışma, kurgusal bir e-ticaret operasyonu simülasyonudur.
