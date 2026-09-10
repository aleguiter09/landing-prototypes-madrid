# Landing Prototypes Madrid

**PROTOTIPO / DEMO**: Spanish mobile-first landing page prototype for Fisioterapia Estrella, a Madrid clinic prospect. This is a demonstration site, not the official client website.

---

## 🏥 Fisioterapia Estrella

Refreshed mobile-first landing for [Fisioterapia Estrella](https://fisioterapiaestrella.com/)

**Type:** Redesign (broken template → modern clean site)  
**Location:** Calle Antonio Casero, 12, Madrid (Retiro/Pacífico)  
**Contact:** Tel 915 733 915 · fisioterapiaestrella@gmail.com  
**Path:** `sites/fisioterapia-estrella/index.html`

### Content Structure (preserved from real site)

**Hero / Bienvenida:**
- Centro en el barrio, totalmente reformado y equipado
- Tratamiento personalizado
- Amplia experiencia con personal altamente cualificado

**Terapias / Servicios:**
- Rehabilitación
- Terapia manual
- Reeducación postural global (RPG)
- Fisioterapia deportiva
- Fisioterapia respiratoria
- Neurorehabilitación

**Tarifas** (fixed from broken pricing UI on live site):
- Primera sesión: 60 min — 40 €
- Sesión individual: 45 min — 35 €
- Bono 10 sesiones: 45 min — 315 € (válido por un año)

**Contacto:**
- Teléfono: 915 733 915
- Email: fisioterapiaestrella@gmail.com
- CTAs: Llamar / WhatsApp / Email

**Encuéntranos:**
- Dirección: Calle Antonio Casero, 12, Madrid
- Horario: Lunes a Viernes 9:30–13:30 y 15:00–20:00

### Design Features

- **Modern mobile-first responsive design** with calm sage/teal palette
- **Inter font** from Google Fonts for clean readability
- **Fixed pricing presentation** — card-based layout (not broken table)
- **Sticky mobile CTA bar** (Tel + WhatsApp) for easy booking
- **All real content preserved** from fisioterapiaestrella.com
- **Prominent PROTOTIPO disclaimer badge**
- **AA contrast compliance**

---

## 🚀 How to Preview Locally

### Option 1: Direct file open
Open `index.html` in your browser, then click through to the Fisioterapia Estrella prototype.

### Option 2: Simple HTTP server (recommended)

**Node.js:**
```bash
npx serve .
# Opens at http://localhost:3000
```

**Python 3:**
```bash
python -m http.server 8000
# Opens at http://localhost:8000
```

**Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

Then navigate to `/sites/fisioterapia-estrella/index.html`

---

## 📂 Repository Structure

```
/
├── index.html                              # Hub page
├── shared/
│   └── styles.css                          # Shared CSS design system
├── sites/
│   └── fisioterapia-estrella/
│       └── index.html                      # Fisioterapia Estrella prototype
└── README.md                               # This file
```

---

## ⚠️ Important Notice

**PROTOTIPO / DEMO**: This repository contains a demonstration prototype only. This is not the official website for Fisioterapia Estrella. The prototype is clearly marked with disclaimer badges.

---

## 🇪🇸 Español

# Prototipo Landing Page Madrid

**PROTOTIPO / DEMO**: Prototipo de página de aterrizaje móvil-primero en español para Fisioterapia Estrella. Este es un sitio de demostración, no el sitio web oficial.

## Contenido

**Fisioterapia Estrella**: Rediseño moderno del sitio existente. Corrige la presentación rota de precios del sitio actual, mantiene toda la funcionalidad y contenido real (servicios, tarifas, contacto, horarios), con diseño responsive móvil-primero y CTAs claros.

## Cómo Previsualizar

Abre `index.html` directamente en tu navegador, o usa un servidor HTTP local:

```bash
npx serve .
# o
python -m http.server 8000
```

Luego navega a `/sites/fisioterapia-estrella/index.html`

---

**Contact:** For questions about this prototype, contact Alejandro.
