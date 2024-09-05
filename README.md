SOC-FE/
│
├── .next/                    # Direktori build dari Next.js (dihasilkan secara otomatis)
│
├── BUILD_ID                  # Identifikasi unik build untuk versi saat ini
│
├── config/                   # Konfigurasi aplikasi
│   └── api.js                # Konfigurasi untuk API yang digunakan dalam aplikasi
│
├── constants/                # Konstanta yang digunakan dalam aplikasi
│   └── constants.js          # File untuk menyimpan nilai konstanta global
│
├── context/                  # Context digunakan untuk mengelola state global yang dapat diakses oleh berbagai komponen dalam aplikasi tanpa harus mengoper state tersebut secara manual melalui props.
│   └── AppContext.js         
│
├── next-backup/              # Folder untuk menyimpan cadangan dari direktori .next atau build lainnya
│   ├── cache/                # Cache yang disimpan dalam backup
│   ├── server/               # File server yang disimpan dalam backup
│   └── static/               # File statis yang disimpan dalam backup
│
├── public/                   # Direktori untuk file-file statis yang dapat diakses secara publik
│   ├── asset/                # Aset tambahan yang mungkin digunakan dalam aplikasi
│   ├── favicon.ico           # Ikon kecil yang tampil di tab browser
│   ├── next.svg              # Logo Next.js
│   └── vercel.svg            # Logo Vercel yang digunakan jika di-hosting di Vercel
│
├── reducer/                  # Folder untuk file reducer, digunakan untuk state management 
│   └── AppReducer.js         # Reducer utama untuk mengelola state global aplikasi
│
├── REQ000006137853/          # Kemungkinan folder untuk menyimpan file permintaan atau spesifikasi tertentu
│
├── src/                      # Kode sumber utama aplikasi
│   ├── components/           
│   ├── pages/                
│   └── styles/               
│
├── utils/                    # Folder untuk fungsi utilitas
│   └── Utils.js              
│
├── backup.sh                 # Skrip shell untuk melakukan pencadangan file atau direktori
├── jsconfig.json             # Konfigurasi untuk JavaScript dalam proyek, memudahkan resolusi path
├── next.config.js            # Konfigurasi untuk Next.js, memungkinkan pengaturan perilaku khusus
├── package.json              # Berisi dependensi dan skrip-skrip yang digunakan dalam proyek
├── package-lock.json         # File yang memastikan konsistensi versi dependensi yang diinstal
├── pm2.json                  # Konfigurasi untuk PM2, sebuah proses manager untuk Node.js
└── README.md                 # Dokumentasi proyek
