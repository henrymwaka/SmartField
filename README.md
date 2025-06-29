# SmartField: Intelligent Field Phenotyping App

SmartField is an ODK-X-based mobile application that digitizes phenotypic data collection in breeding trials. It improves upon the Field Book app with features like:

- Intelligent reminders for missing data
- GPS, photo, and audio capture
- Rust rating scales
- Plot-level history and summary views
- Future-ready dashboard for supervisors

## 📦 Features
- Barcode-enabled plot navigation
- Task tracking with visual alerts
- Trait visibility toggles
- Offline-first; sync-ready via ODK-X Sync Endpoint

## 🚀 Installation
1. Clone this repo or download a release ZIP
2. Copy the contents of `config/full_config.zip` to:
   ```
   /sdcard/opendatakit/default/config/
   ```
3. Install [ODK-X Services](https://docs.odk-x.org/services-intro/), Survey, and Tables
4. Launch **SmartField Maize Trial** in Survey

## 📄 Documentation
See the `/docs` folder for:
- Field user guide
- Admin/deployment guide
- Dashboard wireframe

## 🛠 Technologies
- ODK-X Survey, Tables, Services
- JavaScript-based form logic
- Optional server backend: Node.js/Django + PostgreSQL

## 🤝 Contributing
See [`CONTRIBUTING.md`](CONTRIBUTING.md)

## 📜 License
MIT License
