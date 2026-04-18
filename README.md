# Novoferm Argentina — Sitio Web
**novoferm.com.ar** | Distribuidor oficial: Mesquita Hnos.

---

## Estructura del proyecto

```
/
├── index.html                          → Homepage
├── productos/
│   ├── puertas-cortafuego/
│   │   └── index.html
│   ├── portones-novoslide/
│   │   └── index.html
│   ├── puertas-rapidas/
│   │   └── index.html
│   ├── muelles-novodock/
│   │   └── index.html
│   └── puerta-super/
│       └── index.html
├── catalogos/
│   ├── Puertas Súper - Multiusos - Novoferm.pdf
│   ├── Puertas - seccionales - Novoferm.pdf
│   ├── Cortinas - cortafuego - Novoferm.pdf
│   ├── Portones - NovoSlide - Novoferm.pdf
│   └── Doking (Muelles de Carga) - Novoferm.pdf
└── img/
    ├── novoferm-argentina-logo.svg
    ├── hero-banner.jpg
    ├── puerta-cortafuego.png
    ├── porton-novoslide.png
    ├── puerta-rapida.jpg
    ├── muelle-de-carga.jpg
    ├── puerta-super.jpg
    ├── landing-puertas-doble.png
    ├── landing-portones-doble.png
    ├── landing-persianas-doble.png
    ├── landing-muelles-doble.jpg
    ├── landing-puerta-super-doble.png
    ├── cert-inti.png
    ├── cert-iram.png
    ├── cert-iso.png
    └── cert-iqnet.png
```

---

## Deploy en Vercel

**Importante:** subir el contenido de la carpeta, no la carpeta en sí.

1. Descomprimí el zip
2. Abrí la carpeta `novoferm/`
3. Agregá las carpetas `img/` y `catalogos/` adentro
4. Seleccioná todo el contenido (index.html + productos/ + img/ + catalogos/)
5. Arrastrá la selección al panel de Vercel

**URL actual:** novoferm-argentina-landingpage.vercel.app  
**Dominio objetivo:** novoferm.com.ar

### DNS (NIC.ar → Vercel)
En el panel de NIC.ar, sección Delegaciones:
- Tipo **A** → `@` → `216.198.79.1`
- Tipo **CNAME** → `www` → `5fd4f8d620d2cf5c.vercel-dns-017.com`

---

## Stack técnico

- HTML / CSS / JavaScript vanilla
- Fuentes: Bebas Neue + DM Sans (Google Fonts)
- Animaciones: IntersectionObserver (scroll-triggered)
- Formulario: abre WhatsApp con mensaje pre-llenado
- GTM: GTM-5ZQ5BH78 (instalado en index.html)

**Hosting:** Vercel  
**Sin frameworks, sin dependencias, sin build step.**

---

## Páginas y productos

| Página | Producto | INTI/IRAM | Catálogos |
|--------|----------|-----------|-----------|
| puertas-cortafuego | Puertas cortafuego RF-30/60/90/120 | ✅ | 1 PDF |
| portones-novoslide | Portones NovoSlide + Cortinas cortafuego | ✅ | 2 PDFs |
| puertas-rapidas | Puertas rápidas enrollables | ❌ | 1 PDF |
| muelles-novodock | Rampas + Seccionales Thermo 40 + Abrigos | ❌ | 2 PDFs |
| puerta-super | Puerta Súper Multiusos (no contraincendios) | ❌ | 1 PDF |

---

## Pendientes

- [ ] Imágenes: `puerta-rapida.jpg` y `landing-persianas-doble.png`
- [ ] GTM en páginas de producto (solo está en index.html)
- [ ] Landing de performance (Yago)
- [ ] Galería de proyectos / obras (Fase 2)
- [ ] Blog de contenido técnico (Fase 2)

---

## Contacto comercial
**Ezequiel Mesquita** — Mesquita Hnos.  
WhatsApp: +54 9 11 6191-5191  
Email: info@novoferm.com.ar
