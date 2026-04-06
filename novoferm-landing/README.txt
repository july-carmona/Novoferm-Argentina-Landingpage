NOVOFERM ARGENTINA - Archivos para deploy en Vercel
====================================================

ESTRUCTURA:
novoferm-deploy/
├── index.html                          ← Página principal (links a PDFs ya configurados)
├── img/
│   ├── hero-banner.jpg                 ← Foto hero (puerta + nave industrial)
│   ├── novoferm-argentina-logo.svg     ← Logo SVG oficial
│   ├── puerta-cortafuego.png           ← Card producto: puerta
│   ├── porton-novoslide.png            ← Card producto: portón
│   ├── persiana-enrollable.jpeg        ← Card producto: persiana
│   ├── muelle-de-carga.jpg             ← Card producto: muelle
│   ├── cert-inti.png                   ← Logo INTI
│   ├── cert-iram.png                   ← Logo IRAM
│   ├── cert-iso.png                    ← Logo ISO
│   ├── cert-iqnet.png                  ← Logo IQNet
│   ├── landing-puertas-doble.png       ← Para landing puertas (futuro)
│   ├── landing-persianas-doble.png     ← Para landing persianas (futuro)
│   ├── landing-portones-doble.png      ← PENDIENTE - Para landing portones (futuro)
│   └── landing-muelles-doble.jpg       ← PENDIENTE - Para landing muelles (futuro)
│
├── catalogos/                          ← SUBIR ACÁ LOS PDFs con estos nombres:
│   ├── puertas-cortafuego.pdf
│   ├── portones-novoslide.pdf
│   ├── persianas-enrollables.pdf
│   └── muelles-de-carga.pdf
│
└── README.txt


CATÁLOGOS (PDFs):
Los links en index.html ya apuntan a estos archivos.
Solo hay que meter los PDFs en /catalogos/ con los nombres indicados arriba.


IMÁGENES DOBLE PARA LANDINGS (futuras subpáginas de cada producto):
- landing-puertas-doble.png       ✅ INCLUIDA (detalle barra antipánico + puerta completa)
- landing-persianas-doble.png     ✅ INCLUIDA (persiana abierta + cerrada con operario)
- landing-portones-doble.png      ❌ PENDIENTE (no se subió aún a Claude)
- landing-muelles-doble.jpg       ❌ PENDIENTE (no se subió aún a Claude)

Cuando tengas las imágenes doble de portones y muelles,
renombralas así y agregalas a /img/.


PARA SUBIR A VERCEL:
1. Metí los 4 PDFs en /catalogos/
2. Subí toda la carpeta a un repo de GitHub
   o arrastrala directo a vercel.com/new
3. El dominio novoferm.com.ar se configura en Vercel > Settings > Domains
