mpesa-crypto-wallet/
│
├── app/
│   │
│   ├── Models/
│   │   ├── User.php
│   │   ├── Wallet.php
│   │   ├── Transaction.php
│   │   ├── CryptoWallet.php
│   │
│   ├── Services/
│   │   ├── WalletService.php
│   │   ├── TransactionService.php
│   │   ├── CryptoService.php
│   │   ├── FeeService.php
│   │
│   ├── Controllers/
│   │   ├── AuthController.php
│   │   ├── WalletController.php
│   │   ├── TransactionController.php
│   │
│   ├── Repositories/
│   │   ├── UserRepository.php
│   │   ├── WalletRepository.php
│   │   ├── TransactionRepository.php
│   │
│   ├── Interfaces/
│   │   ├── TransferInterface.php
│   │
│   ├── DSA/
│   │   ├── Queue.php
│   │   ├── Stack.php
│   │   ├── HashMap.php
│   │
│   ├── Utils/
│   │   ├── Validator.php
│   │   ├── Logger.php
│   │
│   └── Events/
│       ├── TransactionEvent.php
│       ├── NotificationEvent.php
│
├── public/
│   ├── index.php
│   ├── .htaccess
│
├── database/
│   ├── schema.sql
│   ├── migrations/
│
├── realtime/
│   ├── websocket-server.php
│
├── tests/
│   ├── WalletTest.php
│   ├── TransactionTest.php
│
├── docs/
│   ├── uml/
│   │   ├── class-diagram.md
│   │   ├── sequence-diagram.md
│   │
│   ├── dfd/
│   │   ├── level0.png
│   │   ├── level1.png
│
├── config/
│   ├── database.php
│   ├── app.php
│
├── README.md
├── .gitignore
└── composer.json
