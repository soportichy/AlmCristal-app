# 📦 StockPro - Gestión de Inventario

Aplicación web moderna para gestión de inventario de pequeños negocios.

## 🌐 Versiones Disponibles

### 📱 Versión Local (`/local`)
- **URL**: [stockpro-local.vercel.app](https://stockpro-local.vercel.app)
- **Tecnología**: HTML + CSS + JS vanilla + localStorage
- **Características**:
  - ✅ Funciona 100% offline
  - ✅ Sin configuración ni cuentas
  - ✅ Ideal para demos rápidas y pruebas
  - ❌ Datos solo en el navegador actual
  - ❌ No sincroniza entre dispositivos

### ☁️ Versión Cloud (`/cloud`)
- **URL**: [stockpro-cloud.vercel.app](https://stockpro-cloud.vercel.app)
- **Tecnología**: HTML + CSS + JS + Supabase (PostgreSQL + Auth)
- **Características**:
  - ✅ Sincronización en tiempo real entre dispositivos
  - ✅ Autenticación segura con email/contraseña
  - ✅ Datos persistentes en la nube
  - ✅ Escalable gratis hasta 500MB de base de datos
  - ❌ Requiere conexión a internet
  - ❌ Necesita crear cuenta gratuita en Supabase

## 🚀 Despliegue en Vercel

Ambas versiones están configuradas para desplegarse automáticamente desde GitHub:

1. Cada `git push` actualiza ambas URLs en Vercel
2. La versión Local usa el directorio `/local` como raíz
3. La versión Cloud usa el directorio `/cloud` como raíz

## 🛠️ Desarrollo Local

```bash
# Clonar repo
git clone https://github.com/tu-usuario/stockpro-app.git
cd stockpro-app

# Abrir en VS Code
code .

# Instalar extensión "Live Server" y abrir index.html de la versión deseada