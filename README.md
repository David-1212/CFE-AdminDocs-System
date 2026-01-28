# ⚡ CFE SmartAdmin System  
Sistema Inteligente de Gestión Administrativa

Plataforma web desarrollada en Laravel para la automatización y control de actas administrativas y cartas de llamada de atención dentro de la Comisión Federal de Electricidad (CFE), integrando flujos institucionales, generación de documentos, notificaciones y asistencia con inteligencia artificial.

---

## 📌 Descripción

CFE SmartAdmin System es una solución digital diseñada para optimizar los procesos administrativos internos relacionados con incidencias laborales, permitiendo el seguimiento estructurado de cada caso, la generación automática de documentos oficiales y la comunicación eficiente mediante correos electrónicos y asistentes virtuales.

---

## 🎯 Objetivo del Proyecto

Modernizar los procesos administrativos de CFE mediante una plataforma centralizada que garantice:

- Trazabilidad documental  
- Control jerárquico de validaciones  
- Automatización de comunicaciones  
- Reducción de tiempos operativos  
- Seguridad en la información  

---

## ✨ Funcionalidades Principales

- Registro y gestión de empleados
- Creación de actas administrativas
- Emisión de cartas de llamada de atención
- Flujo de validación multinivel
- Generación automática de documentos PDF
- Envío de notificaciones por correo
- Chatbot institucional
- Asistente con inteligencia artificial
- Control de roles y permisos
- Historial y auditoría de procesos
- Alertas visuales

---

## 🛠️ Tecnologías Utilizadas

- Laravel 10
- PHP 8.1+
- Livewire 3
- BotMan (Chatbot)
- OpenAI API
- DomPDF
- MySQL / MariaDB
- SweetAlert
- Spatie Permissions
- Laravel Sanctum
- Intervention Image

---

## ⚙️ Requisitos del Sistema

- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL / MariaDB
- Servidor SMTP

---

## 🚀 Instalación

```bash
git clone https://github.com/usuario/cfe-smartadmin-system.git
cd cfe-smartadmin-system
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
npm install
npm run build
php artisan serve
