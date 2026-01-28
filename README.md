# 📄 CFE AdminDocs System — Gestión Administrativa

Sistema web desarrollado en Laravel para la creación, control y seguimiento de actas administrativas y cartas de llamada de atención dentro de la Comisión Federal de Electricidad (CFE), integrando flujos de autorización y notificaciones automatizadas.

## 📌 Objetivo del Proyecto

Digitalizar y optimizar los procesos administrativos internos relacionados con incidencias laborales, garantizando trazabilidad, control documental y cumplimiento institucional.

## ✨ Características

- Registro de empleados
- Generación de actas administrativas
- Emisión de cartas de atención
- Flujo de validación por niveles
- Envío automático de correos
- Historial de procesos
- Control de versiones
- Panel administrativo
- Gestión por roles

## 🛠️ Tecnologías Utilizadas

- Laravel
- PHP 8+
- MySQL / MariaDB
- Blade / Livewire
- JavaScript
- SMTP / Mail Services
- Tailwind CSS

## ⚙️ Instalación

```bash
git clone https://github.com/usuario/cfe-admindocs-system.git
cd cfe-admindocs-system
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install
npm run build
php artisan serve
