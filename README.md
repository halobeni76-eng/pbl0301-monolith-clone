# PBL0301 — Monolith Clone

Proyek ini adalah hasil *clone* dari `c003-monolith` untuk mendemonstrasikan arsitektur Monolithic dasar.

## Informasi Proyek
- **Framework:** **Python[1]** (Flask)
- **Library Tambahan:** Peewee (ORM)

## Cara Menjalankan

```bash
cd pbl0301-monolith
python -m venv venv
source venv/Scripts/activate
pip install -r requirements.txt
python cars.py
```
*(Aplikasi akan berjalan di port 5010)*

## Fitur dan Endpoint
- `GET /readcar` - Menampilkan seluruh data mobil
- `GET /createcar` & `POST /createcar` - Form tambah mobil
- `GET /updatecar/<id>` & `POST /updatecar` - Form edit mobil
- `GET /deletecar/<id>` - Hapus mobil
- `GET /searchcar?q=<keyword>` - Mencari data mobil