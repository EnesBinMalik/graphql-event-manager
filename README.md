<div align="center">

<img src="docs/01-kapak.png" alt="GraphQL Event Manager — Enes Öztürk imzalı proje" width="100%">

# GraphQL Event Manager

**Ödev 2 — 16 mutation ve 16/16 geçen otomatik testle etkinlik yönetimi GraphQL çalışması.**

[![GraphQL](https://img.shields.io/badge/GraphQL-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-event-manager)
[![Mutation](https://img.shields.io/badge/Mutation-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-event-manager)
[![React](https://img.shields.io/badge/React-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-event-manager)
[![Testing](https://img.shields.io/badge/Testing-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-event-manager)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/graphql-event-manager)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

GraphQL Event Manager, kullanıcı, etkinlik, konum ve katılımcı varlıkları için eksiksiz CRUD operasyonları sunar. 16 mutation tek tek test edilir ve test paneli 16/16 sonucunu canlı olarak gösterir. Veri gezgini tüm varlıkları ilişkileriyle birlikte sunar.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **16 mutation** | Dört varlık için ekleme, güncelleme ve silme. |
| **16/16 test** | Otomatik test suite tüm mutation'ları doğrular. |
| **GraphQL Studio** | Sorgu ve mutation editörü, değişken paneli. |
| **Veri gezgini** | Varlıkları ilişkileriyle birlikte keşfetme. |
| **Şema & kodlar** | Şema metni ve çözümleyici kaynak kodu. |
| **Sıfırlama** | Veri kümesini başlangıç durumuna döndürme. |

---

## Kapsam

| Ölçü | Değer |
| --- | --- |
| Mutation | 16 |
| Test | 16/16 |
| Varlık | 4 |
| İlişki | Tam |

---

## Galeri

<img src="docs/02-ekran.png" alt="GraphQL Event Manager ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="GraphQL Event Manager etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="GraphQL Event Manager detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/graphql-event-manager.git
cd graphql-event-manager
npm install
npm run dev
```

> Test paneli her mutation'ı gerçekten çalıştırarak sonucu raporlar.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/graphql/schemaText.ts   Şema tanımı
src/graphql/resolvers.ts    Mutation çözümleyicileri
src/graphql/database.ts     Veri kümesi
src/components/TestSuite.tsx  16 test paneli
src/components/DataExplorer.tsx  Veri gezgini
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
