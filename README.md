# Brief de Proyecto — Grúas y Asistencia Vial

## 1. Resumen del proyecto

- **Tipo de proyecto:** Landing page.
- El desarrollador trabajará sobre una **plantilla base de HTML ya existente**. La estructura de secciones de la página **ya está definida por la plantilla** y no debe modificarse ni reinterpretarse a partir de este documento.
- Ya se entregó por separado un **prompt inicial** para adaptar dicha plantilla al negocio. Este README es el brief complementario con la información del negocio, el branding y los requisitos visuales.

---

## 2. Información del negocio

Esta es toda la información disponible del cliente. **No agregar datos que no estén aquí** (dirección, redes sociales, horarios detallados, correo, etc. no fueron proporcionados y deben omitirse del sitio):

| Dato | Valor |
|---|---|
| Nombre del negocio | Grúas y Asistencia Vial |
| Servicio | Servicio de grúas / transporte de vehículos |
| Teléfono | 55 1365 9946 |
| Disponibilidad | Servicio las 24 horas (dato extraído del logo) |

---

## 3. Branding (extraído del logo)

### Paleta de colores

| Uso sugerido | Color | HEX |
|---|---|---|
| Color primario / acento de marca | Naranja | `#F5821F` |
| Color secundario / fondo oscuro | Negro | `#111111` |
| Color base / contraste claro | Blanco | `#FFFFFF` |
| Detalle metálico (efecto cromado del texto del logo) | Gris plata | `#C7CBD1` |
| Fondo secundario / superficies oscuras | Gris asfalto | `#1E1E1E` |

> Estos HEX son una aproximación visual extraída del logo. Se recomienda calibrarlos con un cuentagotas sobre el archivo original antes de fijarlos como variables definitivas de diseño.

### Tipografía sugerida

- **Títulos:** una tipografía sans-serif de peso alto (Bold/ExtraBold), tipo **Montserrat** o **Poppins**, que refleje la fuerza y solidez del logo.
- **Cuerpo de texto:** una sans-serif limpia y legible, tipo **Inter** o **Roboto**, para mantener el contraste "premium" frente a los títulos.

### Identidad visual

- Estética robusta, industrial y confiable, coherente con el rubro de grúas y asistencia vial.
- El naranja debe usarse como color de acento (CTAs, íconos, detalles), no como color dominante de fondo, para mantener un acabado corporativo.
- El negro y el blanco deben ser la base principal de la interfaz, aportando contraste y seriedad.

---

## 4. Estilo visual obligatorio

El sitio debe transmitir una imagen **premium, enterprise y corporativa de marca**, con un acabado de **nivel big tech**: elegante y a la vez minimalista. Evitar recargar la interfaz; priorizar espacio en blanco, jerarquía visual clara y acabados prolijos por sobre la cantidad de elementos.

---

## 5. Efectos y animaciones requeridos

- Efectos visuales y **animaciones activadas por scroll** a lo largo de la página.
- **Pantalla de carga (preloader)** con spinner + logo del negocio, mostrada antes de renderizar el contenido principal.
- Animación en el **título del hero**, con alguno de los siguientes efectos (o una combinación): efecto máquina de escribir, cambio de color en las letras, u otros efectos tipográficos dinámicos.

---

## 6. Instrucciones sobre assets

- **Logo (`imagenes/logo.jpeg`):** viene con fondo. Antes de usarlo en el sitio, se debe **remover el fondo** para dejarlo con fondo transparente (PNG o SVG), tanto para el preloader como para cualquier otro uso en la interfaz.
- **Foto de la grúa (`imagenes/WhatsApp Image...jpeg`):** es una foto real de una de las grúas del negocio y puede usarse como imagen del hero o de fondo. La foto incluye un logotipo "ike" visible en la puerta del vehículo, correspondiente a una marca de un tercero: se recomienda recortar, encuadrar o difuminar esa zona antes de publicarla. Además, optimizar/comprimir la imagen para uso web antes de integrarla.

---

## 7. Nota para el desarrollador

Este brief y el prompt inicial son el punto de partida, no el resultado final. El desarrollador puede **iterar sobre el proyecto usando Claude, dándole instrucciones las veces que sea necesario**, hasta lograr el resultado deseado.

---

## 8. Checklist para el desarrollador

- [ ] Remover el fondo del logo (`imagenes/logo.jpeg`) y exportarlo en formato con transparencia.
- [ ] Recortar o difuminar el logotipo "ike" visible en la foto de la grúa antes de usarla.
- [ ] Optimizar/comprimir las imágenes finales para web.
- [ ] Aplicar la paleta de colores (naranja, negro, blanco, plata) como variables de diseño.
- [ ] Aplicar la tipografía sugerida (títulos en Montserrat/Poppins, cuerpo en Inter/Roboto).
- [ ] Cargar el teléfono `55 1365 9946` en los puntos de contacto/CTA de la plantilla.
- [ ] Implementar el preloader con spinner + logo del negocio.
- [ ] Implementar animaciones/efectos activados por scroll.
- [ ] Implementar la animación del título del hero (máquina de escribir, cambio de color u otro efecto tipográfico).
- [ ] Revisar que el resultado final transmita un estilo premium, enterprise y minimalista de nivel big tech.
- [ ] Iterar con Claude sobre el resultado hasta lograr el acabado deseado.
