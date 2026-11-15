### `unblocker=True`

Anti-bot korumalarını aşmaya yardımcı olan sistemi etkinleştirir.

Cloudflare ve benzeri bot korumalarına sahip web sitelerinden veri toplama başarısını artırmak için tercih edilir.

Ek maliyet oluşturabilir ve bütün bot korumalarını aşmayı garanti etmez.

------------------------------------------------------------------------

### `render_js=True`

Web sayfasının JavaScript kodları çalıştırılarak tarayıcı ortamında işlenmesini sağlar.

React, Vue ve Angular gibi teknolojilerle oluşturulan dinamik içerikleri elde edebilmek için tercih edilir.

İşlem süresini ve kaynak tüketimini artırabilir.

------------------------------------------------------------------------

### `proxy_pool="public_residential_pool"`

Residential proxy havuzunun kullanılmasını sağlar.

Gerçek kullanıcı internet bağlantılarına ait IP adreslerinden yararlanarak IP tabanlı engellemelere karşı daha esnek erişim sağlamak için tercih edilir.

Maliyeti artırabilir ve proxy kullanımı engellenmeyi tamamen önlemez.

------------------------------------------------------------------------

### `country="tr"`

Proxy bağlantısının kullanılacağı ülkeyi belirler.

Türkiye'deki kullanıcılara sunulan coğrafi içerikleri elde etmek için tercih edilir.

Proxy seçeneklerini sınırlandırabilir ve diğer ülkelerde sunulan içeriklerin alınmasını engelleyebilir.

------------------------------------------------------------------------

### `auto_scroll=True`

Sayfada otomatik kaydırma işlemini etkinleştirir.

Aşağı kaydırıldığında yüklenen içerikleri (infinite scroll gibi) elde etmek için tercih edilir.

Gereksiz kaydırmalar işlem süresini artırabilir; her dinamik içeriğin yüklenmesini garanti etmez.

------------------------------------------------------------------------

### `format_options`

#### `only_content`

Web sayfasındaki ana içerik bölümünün alınmasını sağlayarak gezinme menüleri ve sayfa dışı bazı öğelerin sonuçtan çıkarılmasına yardımcı olur. 

RAG uygulamalarında gereksiz metinleri azaltıp belge içeriğine odaklanmak amacıyla tercih edilir. 

Ancak yorumlar, reklamlar veya ilgili içerik alanları gibi ana içerik dışındaki bazı bölümler tamamen temizlenmeyebilir.

#### `no_links`

Web sayfasındaki bağlantıların sonuç içeriğine eklenmesini engeller. 

Bağlantı metinlerinin RAG belgelerinde gereksiz kalabalık oluşturmasını önlemek ve daha sade bir metin elde etmek amacıyla tercih edilir. 

Ancak bağlantıların yönlendirdiği kaynaklara veya ilgili sayfalara ihtiyaç duyulan senaryolarda faydalı bilgilerin kaybolmasına neden olabilir.

#### `no_images`

Web sayfasındaki görsellerin sonuç içeriğine eklenmesini engeller. 

Yalnızca metin tabanlı RAG uygulamalarında görsel öğelere ihtiyaç duyulmadığından gereksiz içerik ve işleme yükünü azaltmak amacıyla tercih edilir. 

Ancak görsellerin açıklamaları, alternatif metinleri veya görsel referansları uygulama açısından önemliyse bu bilgilerin kaybolmasına neden olabilir.




