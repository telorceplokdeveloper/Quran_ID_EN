# Quran JSON API INDONESIA - ENGLISH | بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم

Simplified Perfect Complete Quran JSON (Indonesian Translation, Tafsir, and Audio) Along with the REST API. Please use it as best you can and have a blessing.

## Quran JSON Directory Structure

```sh
.
├── README.md
├── quran-complete.json         // AL-Quran JSON Complete
├── quran.json                  // AL-Quran JSON
├── road_to_jannah.json         // API QuranJSON
└── surah                       // Complete Surah JSON Directory
    └── <number_of:1-114>.json
```

## Real app that uses QuranJSON

- [Pemuda Hijrah Apps Android](https://play.google.com/store/apps/details?id=id.my.tsigroup.pemudahijrah)

Add your application to this list with a pull request

## Use Of API / Service

### Run your own service

```sh
npm install
npm start
```

#### Access the Simple Quran API

```sh
GET - BASE_URL/
```

#### Access the Complete Surah Al Fatihah API

```sh
GET - BASE_URL/surah/1
```

### Using the QuranJSON Github JSON Service

Can be directly accessed through the directory.

Quran:

```sh
https://raw.githubusercontent.com/telorceplokdeveloper/QuranJSON/master/quran.json
```

Surah:

```sh
https://raw.githubusercontent.com/telorceplokdeveloper/QuranJSON/master/surah/1.json
```
