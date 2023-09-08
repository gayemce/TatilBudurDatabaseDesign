# TatilBudur Database Design

Tatil Budur Veri Tabanı, tatil sitelerinden örnek alınarak otel, oda ve rezervasyon işlemleri için kullanılan bir veritabanıdır. Bu veritabanı, tatil planlaması ve rezervasyon yönetimi gibi işlemleri desteklemek amacıyla tasarlanmıştır. Aşağıda, veritabanının yapısı ve içeriği hakkında kısa açıklamalar bulunmaktadır.

## Tablolar

TatilBudurDb veritabanı, aşağıdaki 15 tabloyu içerir:

1. **Addresses**: Otellere ait adres bilgilerini tutar. Şehir, ilçe, cadde, içerik gibi bilgileri içerir.
2. **Categories**: Otel kategorilerini temsil eder. Kategori adı ve etkinlik durumu gibi bilgileri içerir.
3. **HotelCategories**: Otellerin kategori ilişkilerini yönetir.
4. **HotelImages**: Otellerin görsel içeriklerini tutar.
5. **Hotels**: Otelleri temsil eder. Otel adı, derecelendirme gibi bilgileri içerir.
6. **HotelSpecifications**: Otellere ait özellikleri ve açıklamalarını tutar.
7. **HotelTags**: Otellerin etiketlerini yönetir.
8. **HotelVideos**: Otellerin video içeriklerini tutar.
9. **Reservations**: Oda rezervasyonlarını temsil eder.
10. **RoomImages**: Odaların görsel içeriklerini tutar.
11. **Rooms**: Otellere ait odaları temsil eder.
12. **RoomTags**: Odaların etiketlerini yönetir.
13. **RoomVideos**: Odaların video içeriklerini tutar.
14. **Specifications**: Otellerin ve odaların sahip olduğu özellikleri temsil eder.
15. **Tags**: Etiketleri temsil eder.

## Veritabanının Amaçları

TatilBudurDb veritabanı, aşağıdaki amaçları desteklemek üzere tasarlanmıştır:

- Otellerin temel bilgilerini depolamak ve yönetmek.
- Otel kategorilerini oluşturmak, yönetmek ve ilişkilendirmek.
- Otellerin ve odaların özelliklerini ve açıklamalarını kaydetmek.
- Etiketleri oluşturmak ve otellerle, odalarla ilişkilendirmek.
- Odaların görsel ve video içeriklerini yönetmek.
- Oda rezervasyonlarını takip etmek ve yönetmek.
