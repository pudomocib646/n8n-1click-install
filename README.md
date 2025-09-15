# 🚀 n8n One-Click Installer

Этот скрипт автоматически устанавливает [n8n](https://n8n.io/) на сервер под управлением Ubuntu (20.04, 22.04, 24.04 LTS) с использованием Docker Compose.

## 📺 Наши каналы

- [Blockchain Odyssey](https://t.me/cryptomaniainvest)
- [Neural Expedition](https://t.me/NeuralExpedition)

## ✅ Возможности

- Автоматическая установка Docker и Docker Compose
- Настройка домена и SSL-сертификата через Traefik и Let's Encrypt
- Поддержка SQLite и PostgreSQL
- Автозапуск сервисов при перезагрузке системы
- Команды для обновления, остановки и перезапуска

## 🧰 Требования

- Сервер под управлением Ubuntu 20.04, 22.04 или 24.04 LTS
- Доменное имя, указывающее на IP-адрес сервера
- Доступ к серверу по SSH с правами `root`

## 🚀 Использование

1. Скачайте скрипт:
   ```bash
   wget https://raw.githubusercontent.com/pudomocib646/n8n-1click-install/main/install-n8n.sh
