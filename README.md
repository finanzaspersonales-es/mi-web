# 🏠 Calculadora de Hipoteca España - GitHub Pages

## 🚀 Guía de Deployment (5 minutos)

### **Paso 1: Crear repositorio en GitHub**

1. Ve a [github.com](https://github.com) e inicia sesión (o crea cuenta gratis)
2. Click en el botón **"New"** (verde, arriba a la derecha)
3. Nombre del repositorio: `calculadora-hipoteca` (o el que quieras)
4. Marca como **"Public"**
5. ✅ Marca **"Add a README file"**
6. Click en **"Create repository"**

---

### **Paso 2: Subir el archivo HTML**

**Opción A - Desde la interfaz web (más fácil):**

1. En tu repositorio, click en **"Add file"** → **"Upload files"**
2. Arrastra el archivo `index.html` que descargaste
3. En el mensaje de commit escribe: `Initial commit - Calculadora hipoteca`
4. Click en **"Commit changes"**

**Opción B - Usando Git (si ya lo tienes instalado):**

```bash
git clone https://github.com/TU_USUARIO/calculadora-hipoteca.git
cd calculadora-hipoteca
# Copia aquí el index.html
git add index.html
git commit -m "Initial commit - Calculadora hipoteca"
git push origin main
```

---

### **Paso 3: Activar GitHub Pages**

1. En tu repositorio, ve a **Settings** (arriba a la derecha)
2. En el menú izquierdo, busca **"Pages"** (sección "Code and automation")
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona:
   - Branch: `main` 
   - Folder: `/ (root)`
5. Click en **"Save"**

⏱️ **Espera 2-3 minutos** mientras se despliega...

---

### **Paso 4: ¡Tu web está ONLINE! 🎉**

Tu calculadora estará disponible en:

```
https://TU_USUARIO.github.io/calculadora-hipoteca/
```

**Ejemplo:** Si tu usuario es `danielamartinez`, sería:
```
https://danielamartinez.github.io/calculadora-hipoteca/
```

---

## 📊 Optimización para AdSense

### **Espacios publicitarios incluidos:**

El HTML ya tiene 2 placeholders para AdSense:

1. **Leaderboard (728x90)** - Después de la calculadora
2. **Medium Rectangle (300x250)** - Antes del footer

### **Pasos para activar AdSense:**

1. **Solicitar cuenta AdSense:**
   - Ve a [google.com/adsense](https://www.google.com/adsense)
   - Necesitarás dominio propio (ver siguiente sección) o esperar aprobación con `.github.io`

2. **Reemplazar placeholders:**
   
   Busca en el HTML:
   ```html
   <div class="ad-placeholder">
   ```
   
   Y reemplaza cada bloque con el código de anuncio de AdSense:
   ```html
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXX"
        crossorigin="anonymous"></script>
   <ins class="adsbygoogle"
        style="display:block"
        data-ad-client="ca-pub-XXXXXXXXXX"
        data-ad-slot="YYYYYYYYYY"
        data-ad-format="auto"></ins>
   <script>
        (adsbygoogle = window.adsbygoogle || []).push({});
   </script>
   ```

---

## 🌐 Mejora: Dominio propio (opcional pero recomendado)

### **Por qué usar dominio propio:**
- ✅ Mejor tasa de aprobación en AdSense
- ✅ Más profesional → mayor confianza → mayor CTR
- ✅ Mejor SEO
- 💰 Solo €8-12/año

### **Dominios recomendados:**

- `calculadorahipoteca.es` 
- `mihipoteca.es`
- `simuladorhipoteca.es`
- `hipotecaonline.es`

**Dónde comprar:**
- [Namecheap](https://www.namecheap.com) - €8-10/año
- [Hostinger](https://www.hostinger.es) - €9-12/año
- [Google Domains](https://domains.google) - €12/año

### **Conectar dominio propio a GitHub Pages:**

1. Compra el dominio
2. En tu repositorio: **Settings** → **Pages** → **Custom domain**
3. Escribe tu dominio: `calculadorahipoteca.es`
4. En tu proveedor de dominio, configura estos DNS:

   **Tipo A records:**
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

   **CNAME record:**
   ```
   www → TU_USUARIO.github.io
   ```

5. Espera 24-48h para propagación DNS

---

## 🤖 Automatización con Claude

### **Claude Code (tu PC local):**

```bash
# Publicar contenido nuevo automáticamente
claude code "Crea un artículo SEO sobre tipos de hipotecas en España 2026"

# Actualizar datos
claude code "Actualiza las tasas de interés promedio en el artículo principal"
```

### **Claude for Chrome (automatización web):**

1. Instala la extensión desde Chrome Web Store
2. Navega a tu panel de GitHub
3. Dale instrucciones a Claude:
   - "Sube el nuevo artículo que creamos"
   - "Actualiza la sección de noticias"
   - "Modera los comentarios del blog"

---

## 📈 Próximos pasos para maximizar RPM

### **Fase 1 - Contenido (semanas 1-4):**
- [ ] Crea 10-15 artículos SEO sobre hipotecas
- [ ] Añade calculadora de gastos notariales
- [ ] Añade comparador de bancos (tabla)

### **Fase 2 - Tráfico (mes 2-3):**
- [ ] Optimiza para palabras clave de alto CPC
- [ ] Crea contenido para "calculadora hipoteca [ciudad]"
- [ ] Guest posts en blogs financieros

### **Fase 3 - Monetización (mes 3+):**
- [ ] Solicita AdSense (necesitas ~50 visitas/día)
- [ ] Añade programa de afiliados de bancos
- [ ] Considera vender leads (€5-15 por lead)

---

## 🛠️ Estructura de archivos sugerida

```
calculadora-hipoteca/
├── index.html              (Calculadora principal - YA TIENES)
├── articulos/
│   ├── tipos-hipotecas.html
│   ├── mejores-bancos-2026.html
│   └── gastos-comprar-casa.html
├── calculadoras/
│   ├── gastos-notariales.html
│   └── capacidad-endeudamiento.html
└── assets/
    ├── css/
    └── js/
```

---

## 📊 Métricas objetivo

| Métrica | Mes 1 | Mes 3 | Mes 6 |
|---------|-------|-------|-------|
| Visitas/día | 20-50 | 100-200 | 500+ |
| RPM | - | $25-35 | $35-45 |
| Ingresos/mes | - | $75-200 | $500+ |

---

## ⚡ Comandos útiles

**Actualizar la web:**
```bash
# Edita index.html localmente
git add index.html
git commit -m "Actualización: [describe cambio]"
git push origin main
# En 1-2 minutos se actualiza automáticamente
```

**Ver analytics:**
- Añade Google Analytics en el `<head>`:
  ```html
  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'G-XXXXXXXXXX');
  </script>
  ```

---

## 🆘 Problemas comunes

**La página no carga:**
- Espera 3-5 minutos después de activar Pages
- Verifica que el archivo se llame exactamente `index.html`
- Revisa Settings → Pages que esté en verde

**AdSense rechazado:**
- Necesitas contenido original (mínimo 10-15 páginas)
- Tráfico regular (50+ visitas/día)
- Dominio propio ayuda mucho
- Evita contenido duplicado

**Bajo CTR/RPM:**
- Coloca anuncios cerca de la calculadora
- Usa formato responsive
- Prueba diferentes posiciones (A/B testing)

---

## 💬 Contacto

¿Dudas? Pregúntame lo que necesites. Estoy aquí para ayudarte a que esto funcione 🚀

---

**¡Ahora sí, a por ese AdSense! 💰**
