# PanKey

**PanKey** is a modern and secure Password Manager designed with simplicity and safety in mind. Unlike cloud-based solutions, PanKey manages and encrypts all your data locally on your device, giving you complete control over your sensitive information.

---

## Features

### 🛡️ **Maximum Security**

- **Local Data Storage:** All passwords are stored and encrypted directly on your device, eliminating reliance on the cloud.
- **Encryption:** Utilizes AES-256 encryption to protect your data from unauthorized access.
- **Biometric Authentication:** Supports fingerprint and facial recognition for quick and secure access.

### 🔑 **Smart Password Management**

- **Password Generator:** Create strong, customizable passwords with ease.
- **Security Insights:** Identify weak and duplicate passwords.
- **Offline Mode:** Works without an internet connection to ensure your data stays local.

### ⚡ **User-Friendly Design**

- Clean, intuitive interface for quick navigation.
- Tagging and categorization to organize your credentials.
- Dark mode for a comfortable experience in low-light environments.

---

## Installation

### Clone the Repository

```bash
https://github.com/davide-peterlini/PanKey.git
```

### Run the Application

#### For Mobile (Ionic Framework):

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the app:
   ```bash
   npm run ionic:build && npx cap copy android && npx cap run android --target={DEVICE_NAME} --no-build
   ```
3. Follow platform-specific instructions for iOS or Android emulators.

#### For Web (Ionic Framework):

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the web app:
   ```bash
   npm run ionic:serve
   ```

---

## Technologies Used

- **Frontend:** Ionic Framework with Vue3
- **Backend:** JS
- **Database:** Local SQLite (for local password storage)
- **Encryption:** AES-256

---

## Screenshots

### Dashboard

...

### Add New Password

...

---

## Roadmap

### Upcoming Features:

- **Export & Import:** Securely transfer passwords between devices.
- **Customizable Alerts:** Receive notifications for password updates.
- **Multi-language Support:** Expanding accessibility.

---

## Contributing

We welcome contributions! Follow these steps to get started:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request on GitHub.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or feedback, open an issue on GitHub.

---

Thank you for using **PanKey**! Secure your world, one password at a time.

