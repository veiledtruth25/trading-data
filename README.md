# Trading Data Repository

Repository ini berisi data akun trading yang di-update otomatis oleh EA (Expert Advisor) dari MetaTrader 5.

## Struktur

```
trading-data/
└── accounts/
    └── account.json    # Data akun terbaru
```

## Format Data

```json
{
  "last_updated": "2025-01-02T12:00:00Z",
  "account": {
    "login": 12345678,
    "server": "MetaQuotes-Demo",
    "currency": "USD",
    "balance": 10000.00,
    "equity": 10250.50,
    "margin": 500.00,
    "free_margin": 9750.50,
    "margin_level": 2050.10,
    "profit": 250.50
  }
}
```

## Raw URL

Untuk mengakses data dari web:
```
https://raw.githubusercontent.com/veiledtruth25/trading-data/main/accounts/combined.json
```
