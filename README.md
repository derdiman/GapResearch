# GapResearch

**Sürüm: 1.1.0**

**Türkçe:** GapResearch, akademik literatürü analiz etmek, çalışmalar arasındaki ortak temaları ve farklılıkları belirlemek, kanıta dayalı olası araştırma boşluklarını ortaya çıkarmak ve özgün araştırma soruları geliştirmek için tasarlanmış bir yapay zekâ becerisidir. Lisans, yüksek lisans ve doktora öğrencileri ile akademisyen ve araştırmacılara yöneliktir. Kaynak doğruluğunu, kanıtların izlenebilirliğini, araştırmacının akademik sorumluluğunu, şeffaflığı ve akademik etik ilkelerini gözetir. Yapay zekâ çıktılarının insan tarafından doğrulanmasını ve nihai akademik değerlendirmenin araştırmacı tarafından yapılmasını esas alır.

**English:** GapResearch is an AI skill designed to analyze academic literature, identify common themes and differences across studies, surface evidence-based potential research gaps, and develop original research questions. It is intended for undergraduate, master's, and doctoral students, as well as academics and researchers. It emphasizes source verification, evidence traceability, researcher accountability, transparency, and academic integrity. It requires human verification of AI-generated outputs and keeps final scholarly judgment with the researcher.

## 1.1.0 ile gelenler

PDF veya önceden seçilmiş konu gerekmeden başlanabilir. Skill önce çalışma türünü öğrenir: lisans bitirme projesi, yüksek lisans tezi, doktora tezi, bilimsel makale veya TÜBİTAK projesi. PDF yükleyenler için de bu hedef belirlenir.

Alan, süre, ilgi ve kaynaklara göre farklı konu ailelerinden geniş bir öneri havuzu sunulur; yöntem, öğrenme/katkı, araç-veri ihtiyacı ve uygulanabilirlik üzerinden kısa listeye geçilir. Bitirme projesinde mesleki beceri, makalede uluslararası literatür, tezlerde YÖK Tez ve yabancı tez arşivleri, TÜBİTAK'ta güncel resmi program koşulları dikkate alınır. Tarama ile doğrulanmamış fikirler açıkça belirtilir. Mevcut PDF inceleme ve kanıt izlenebilirliği akışı korunur.

Başlangıç örneği: “Bitirme projem için konum ve PDF'im yok. Alanımı ve olanaklarımı öğrenerek konu seçmeme yardım et.”

English: Version 1.1.0 adds guided topic discovery without uploaded PDFs. Suggestions are tailored to undergraduate projects, master's/doctoral theses, articles, and TÜBİTAK projects while preserving the evidence-based literature analysis workflow.

## Dil seçenekleri

- Türkçe sürüm: kök dizindeki `SKILL.md`, `references/` ve `templates/`.

## Kullanım

`GapResearch` klasörünü desteklenen aracın beceri/skill dizinine yerleştirin veya özel becerileri destekleyen ortama yükleyin.

Türkçe örnek komut: “GapResearch becerisini kullanarak yüklediğim makaleleri incele, literatürü sentezle ve kanıta dayalı araştırma boşluklarını belirle.”

English example: “Use the GapResearch skill to analyze these papers, synthesize the literature, and identify defensible research gaps.”

## Klasörler

- `SKILL.md`: Türkçe iş akışı ve kalite gereklilikleri
- `references/`: Konu keşfi yönergeleri, çalışma çıkarım, boşluk kaydı ve rapor şablonları
- `templates/`: Türkçe CSV kayıt tabloları

## Sınırlılıklar

Bu beceri Scopus, Web of Science, yayıncı abonelikleri veya herhangi bir modele kendiliğinden erişim sağlamaz. Tarama kapsamı, bağlı araçlara ve kullanıcının erişim haklarına bağlıdır. Yapılandırılmış bir boşluk taraması otomatik olarak PRISMA uyumlu sistematik derleme sayılmaz.

## Lisans

Bu depoya bir açık kaynak lisansı eklenmeden önce lisans tercihi belirlenmelidir.
