Düzeltmeler:

- addRow(): bozuk DOM erişimleri düzeltildi, her eklenen item için benzersiz id atandı, silme sonrası toplam yeniden hesaplanıyor.
- renderDbList(): rehber listesi doğru şekilde map ve join ile render ediliyor.
- renderArchive(): arşiv renderında item id kullanımı ve arama koruması eklendi.
- calcSum(): parseFloat güvenli hale getirildi ve toplam hesaplaması iyileştirildi.

Detaylar için index.html dosyasına bakınız.
