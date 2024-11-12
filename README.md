# alquran-json

alquran-json adalah pustaka data Al-Qur'an dalam format JSON yang menyediakan teks Arab, terjemahan bahasa Indonesia, dan tafsir. Dengan struktur JSON yang rapi, pustaka ini memudahkan pengembang untuk mengintegrasikan data Al-Qur'an ke dalam berbagai aplikasi, seperti aplikasi edukasi, tadarus, dan tafsir digital.

## Fitur

- **Teks Arab**: Memuat teks Al-Qur'an dalam bahasa Arab.
- **Terjemahan Bahasa Indonesia**: Menyediakan terjemahan Al-Qur'an dalam bahasa Indonesia.
- **Tafsir**: Memuat tafsir untuk memahami konteks ayat.

## Struktur Data

Pustaka JSON ini mengorganisir data Al-Qur'an berdasarkan:
- **Surah**: Setiap surah memiliki nomor dan nama.
- **Ayat**: Setiap ayat berisi teks Arab, terjemahan, dan tafsir.

Contoh struktur JSON:
```json
{
  "surah": {
    "1": {
      "name": "Al-Fatihah",
      "ayahs": {
        "1": {
          "arab": "بِسْمِ ٱللَّهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ",
          "indonesia": "Dengan nama Allah Yang Maha Pengasih, Maha Penyayang.",
          "tafsir": "Ayat ini memulai setiap tindakan dengan menyebut nama Allah."
        }
      }
    }
  }
}
