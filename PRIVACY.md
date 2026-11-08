# Widget Notch Gizlilik Politikası

Widget Notch hesap oluşturmanı istemez ve uygulama bir analiz veya telemetri hizmeti kullanmaz.

| Özellik | Veri ve alıcı |
| --- | --- |
| Canlı şarkı sözleri | Açıkken şarkı adı ve sanatçı, eşleşme için [LRCLIB](https://lrclib.net/docs) ile paylaşılır. |
| Hava durumu | Aradığın şehir veya ilçe adı Open-Meteo konum servisine, seçtiğin konumun koordinatları [Open-Meteo](https://open-meteo.com/en/docs) tahmin servisine gönderilir. GPS konumu istenmez. |
| Güncellemeler | Sürüm bilgisi ve paket [GitHub Releases](https://docs.github.com/en/rest/releases/releases) üzerinden alınır. Güncelleme kontrolü uygulama sürümünü içeren bir istemci tanıtıcısı gönderir. Paket onayından sonra indirilir. |
| Pano geçmişi | İsteğe bağlıdır. Metinler, bağlantılar ve resimler Windows hesabına bağlı şifrelemeyle cihazda tutulur. Kayıtlar dışarı gönderilmez. Ayarlardan geçmişi temizleyebilir veya kaydı kapatabilirsin. Geçmişi temizlemek için sabitlenen kayıtların önce sabitlemesini kaldır. |
| Windows bildirimleri | İzin verilirse bildirim merkezindeki uygulama adı, zaman ve bildirim metni yalnızca açık widget içinde cihazda gösterilir. İçerik kaydedilmez veya gönderilmez. Windows gizlilik ayarlarından erişimi kapatabilirsin. |
| Tarayıcı uzantısı | İsteğe bağlı Chrome/Edge uzantısı aktif indirmelerin dosya adını ve varsa ilerleme bilgisini yerel bağlantıyla uygulamaya iletir. İndirme adresleri iletilmez. |

Ayarlar ve yerel kayıtlar `%LOCALAPPDATA%\DynamicNotch` klasöründedir. Windows medya, ses ve ekran bilgisi uygulama tarafından cihazda işlenir. Ağ isteklerinde ilgili hizmet IP adresi gibi standart bağlantı bilgilerini görebilir.

Sorular ve geri bildirim için [GitHub Issues](https://github.com/tprkidea/widget-notch/issues) kullanılabilir. Özel pano içeriğini veya kişisel verilerini herkese açık bir bildirime ekleme.
