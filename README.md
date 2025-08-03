# OmegaPrimeWarpForce
OmegaPrimeWarpForce/
├── backend/
│   ├── app.py                  # Główny backend Flask
│   ├── auth.py                 # Autoryzacja JWT
│   ├── tasks.py                # Kolejkowanie i zarządzanie zadaniami
│   ├── notifications.py        # Powiadomienia (Pushbullet, Telegram, e-mail)
│   ├── monitoring.py           # Watchdog i monitorowanie zasobów
│   ├── ai_module.py            # Moduł AI (analiza i optymalizacja)
│   ├── config.py               # Konfiguracja systemu
│   ├── requirements.txt        # Lista zależności Python
│   └── utils.py                # Funkcje pomocnicze
├── frontend/
│   ├── public/
│   │   └── index.html          # Główny szablon HTML
│   ├── src/
│   │   ├── components/         # Komponenty React
│   │   ├── services/           # Warstwa komunikacji z API
│   │   ├── App.js              # Główny komponent React
│   │   ├── index.js            # Start aplikacji
│   │   └── styles.css          # Style CSS
│   ├── package.json            # Zależności frontendu
│   └── README.md               # Instrukcje frontendu
├── docs/
│   ├── architecture.md         # Opis architektury systemu
│   ├── setup.md                # Instrukcja instalacji i konfiguracji
│   ├── usage.md                # Przewodnik użytkownika
│   └── api_reference.md        # Dokumentacja API
├── .gitignore
├── README.md
└── LICENSE
