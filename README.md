**Nama:** Pradytha Galuh Putranti  
**NIM:** 2304220013  
**Program Studi:** Statistika dan Sains Data  

# Tugas 1 PRAKTISI PMML
# Books to Scrape - Web Scraper & Data Analysis
Scraping program untuk website "https://books.toscrape.com/"

# Features
Web Scraping

Multi-page scraping - Automatically scrapes all available pages

Detailed data extraction including:

* Book title, category, and unique code
* Cover image URL
* Star ratings (1-5 stars)
* Prices (with and without tax)
* Stock status and availability
* Full book descriptions
* Number of reviews

## Dataset Hasil Scraping

Berikut adalah contoh tampilan **10 data pertama** dari hasil scraping website [Books to Scrape](https://books.toscrape.com/).

| No | Category           | Code                                               | Title                                           | Rating | Price (Incl Tax) | Stock | Reviews |
|----|--------------------|----------------------------------------------------|-------------------------------------------------|:------:|:----------------:|:------:|:--------:|
| 1  | Poetry             | a-light-in-the-attic_1000                          | A Light in the Attic                            | ⭐⭐⭐   | £51.77 | In stock | 0 |
| 2  | Historical Fiction | tipping-the-velvet_999                             | Tipping the Velvet                              | ⭐     | £53.74 | In stock | 0 |
| 3  | Fiction            | soumission_998                                     | Soumission                                      | ⭐     | £50.10 | In stock | 0 |
| 4  | Mystery            | sharp-objects_997                                  | Sharp Objects                                   | ⭐⭐⭐⭐ | £47.82 | In stock | 0 |
| 5  | History            | sapiens-a-brief-history-of-humankind_996           | Sapiens: A Brief History of Humankind           | ⭐⭐⭐⭐⭐ | £54.23 | In stock | 0 |
| 6  | Young Adult        | the-requiem-red_995                                | The Requiem Red                                 | ⭐     | £22.65 | In stock | 0 |
| 7  | Business           | the-dirty-little-secrets-of-getting-your-dream...  | The Dirty Little Secrets of Getting Your Dream  | ⭐⭐⭐⭐ | £33.34 | In stock | 0 |
| 8  | Default            | the-coming-woman-a-novel-based-on-the-life-of-...  | The Coming Woman: A Novel Based on the Life...  | ⭐⭐⭐   | £17.93 | In stock | 0 |
| 9  | Default            | the-boys-in-the-boat-nine-americans-and-their-...  | The Boys in the Boat: Nine Americans and...     | ⭐⭐⭐⭐ | £22.60 | In stock | 0 |
| 10 | Poetry             | the-black-maria_991                                | The Black Maria                                 | ⭐     | £52.15 | In stock | 0 |

**Total Buku:** 1000  

Setiap entri buku mencakup informasi lengkap seperti:

- **Kategori & Judul Buku**  
- **Kode unik (URL slug)**  
- **URL Gambar Sampul**  
- **Rating (1–5 bintang)**  
- **Harga (dengan & tanpa pajak)**  
- **Ketersediaan Stok & Jumlah Barang**  
- **Deskripsi Buku Lengkap**  
- **Jumlah Ulasan (Reviews)**  

- **Total Buku Terdata:** 1000  
- **Buku Termurah:** £10.00  
- **Buku Termahal:** £59.99
  
## Top 10 Buku dengan Rating Tertinggi

| No | Judul Buku                                                                 | Rating | Harga (£) |
|----|-----------------------------------------------------------------------------|:-------:|:----------:|
| 1  | Sapiens: A Brief History of Humankind                                       | ⭐⭐⭐⭐⭐ | 54.23 |
| 2  | Set Me Free                                                                 | ⭐⭐⭐⭐⭐ | 17.46 |
| 3  | Scott Pilgrim's Precious Little Life (Scott Pilgrim #1)                     | ⭐⭐⭐⭐⭐ | 52.29 |
| 4  | Rip it Up and Start Again                                                   | ⭐⭐⭐⭐⭐ | 35.02 |
| 5  | Chase Me (Paris Nights #2)                                                  | ⭐⭐⭐⭐⭐ | 25.27 |
| 6  | Black Dust                                                                  | ⭐⭐⭐⭐⭐ | 34.53 |
| 7  | Worlds Elsewhere: Journeys Around Shakespeare’s Globe                       | ⭐⭐⭐⭐⭐ | 40.30 |
| 8  | The Four Agreements: A Practical Guide to Personal Freedom                  | ⭐⭐⭐⭐⭐ | 17.66 |
| 9  | The Elephant Tree                                                           | ⭐⭐⭐⭐⭐ | 23.82 |
| 10 | Sophie's World                                                              | ⭐⭐⭐⭐⭐ | 15.94 |


## Jumlah Buku per Kategori

| Kategori              | Jumlah Buku |
|------------------------|:------------:|
| Default               | 152 |
| Nonfiction            | 110 |
| Sequential Art        | 75 |
| Add a comment         | 67 |
| Fiction               | 65 |
| Young Adult           | 54 |
| Fantasy               | 48 |
| Romance               | 35 |
| Mystery               | 32 |
| Food and Drink        | 30 |
| Childrens             | 29 |
| Historical Fiction    | 26 |
| Poetry                | 19 |
| Classics              | 19 |
| History               | 18 |
| Horror                | 17 |
| Womens Fiction        | 17 |
| Science Fiction       | 16 |
| Science               | 14 |
| Music                 | 13 |
| Business              | 12 |
| Travel                | 11 |
| Philosophy            | 11 |
| Thriller              | 11 |
| Humor                 | 10 |
| Autobiography         | 9  |
| Art                   | 8  |
| Psychology            | 7  |
| Religion              | 7  |
| Spirituality          | 6  |
| Christian Fiction     | 6  |
| New Adult             | 6  |
| Sports and Games      | 5  |
| Self Help             | 5  |
| Biography             | 5  |
| Health                | 4  |
| Politics              | 3  |
| Contemporary          | 3  |
| Christian             | 3  |
| Historical            | 2  |
| Crime                 | 1  |
| Erotica               | 1  |
| Novels                | 1  |
| Cultural              | 1  |
| Suspense              | 1  |
| Short Stories         | 1  |
| Academic              | 1  |
| Adult Fiction         | 1  |
| Parenting             | 1  |
| Paranormal            | 1  |

---


