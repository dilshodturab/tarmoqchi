# Tarmoqchi - The Lightweight Tunneling Tool 🚀

A powerful, secure and efficient solution for HTTP tunneling. Create secure tunnels to expose your local services to the internet with ease.

![Tarmoqchi Logo](https://pub-efb2bbde7206420692920475ba73046f.r2.dev/logo.png)

## 🔥 Features

- **🔗 Secure Tunneling** – Connect your local services to the internet with ease
- **⚡ Blazing Fast** – Experience high-speed, low-latency connections
- **🔐 Authentication** – Secure your tunnel with token-based authentication

## 🚀 Installation

### Quick Install on MacOS/Linux

```bash
curl -fsSL https://github.com/jamshid-elmurodov/tarmoqchi/releases/download/Tarmoqchi-1.0.0/install.sh | sudo bash
```

### Manual Installation on Windows

1. Download the latest release from the [releases page](https://github.com/jamshid-elmurodov/tarmoqchi/releases/tag/Tarmoqchi-1.0.0)
2. Use it

## 🔧 Usage

### Authentication

Before using Tarmoqchi, you need to authenticate using your auth token:

```bash
tarmoqchi --auth YOUR_AUTH_TOKEN
```

You can get your auth token by visiting [Tarmoqchi.uz](https://tarmoqchi.uz/auth/token).

### Creating a Tunnel

To create a tunnel to your local service:

```bash
tarmoqchi --port YOUR_PORT
```

Replace `YOUR_PORT` with the local port number your service is running on (e.g., 8080, 3000, etc.).

### Command Options

```bash
# Show version information
tarmoqchi --version

# Display help information
tarmoqchi --help
```

## ⚙️ Configuration

Tarmoqchi stores configuration files in the following locations:

- Linux/macOS: `~/.config/tarmoqchi/`
- Windows: `%APPDATA%\tarmoqchi\`

## 📝 Examples

### Exposing a Web Server

```bash
# Start a local web server
python -m http.server 8000

# In a new terminal, create a tunnel to expose it
tarmoqchi port 8000
```

### Exposing Multiple Services

You can run multiple instances of Tarmoqchi to expose different services:

```bash
tarmoqchi port 3000 # For a React app
tarmoqchi port 8080 # For a backend API
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

Please read our [Contributing Guidelines](https://github.com/jamshid-elmurodov/tarmoqchi/blob/main/CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/jamshid-elmurodov/tarmoqchi/blob/main/LICENSE) file for details.

## 🔗 Links

- [Website](https://tarmoqchi.uz)
- [GitHub Repository](https://github.com/jamshid-elmurodov/tarmoqchi)
- [Issue Tracker](https://github.com/jamshid-elmurodov/tarmoqchi/issues)

---

© 2025 Tarmoqchi. All rights reserved.
