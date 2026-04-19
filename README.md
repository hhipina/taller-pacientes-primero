# Taller de Costos y Precios Hospitalarios
## PACIENTES Primero Consulting Group — Landing Page

### Cómo publicar en 3 pasos

---

**Paso 1 — Sube a GitHub**

```bash
git init
git add index.html README.md
git commit -m "Landing taller mayo 2026"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/taller-pacientes-primero.git
git push -u origin main
```

---

**Paso 2 — Despliega en Vercel**

1. Entra a https://vercel.com
2. Clic en "Add New Project"
3. Importa el repo `taller-pacientes-primero`
4. Deja todo por defecto y clic en "Deploy"
5. En ~30 segundos queda publicado en una URL de Vercel

---

**Paso 3 — Conecta tu dominio**

En **Vercel** (Settings → Domains):
- Agrega: `taller.pacientesprimero.mx`

En **Hostinger** (DNS Zone):
- Tipo: `CNAME`
- Nombre: `taller`
- Valor: `cname.vercel-dns.com`
- TTL: 3600

En ~10 minutos el DNS propaga y queda activo en:
👉 `https://taller.pacientesprimero.mx`

---

### Para actualizar la landing

Edita `index.html`, luego:

```bash
git add index.html
git commit -m "Actualización: descripción del cambio"
git push
```

Vercel actualiza automáticamente en ~20 segundos.

---

### Contacto
hipina@pacientesprimero.mx | +52 811 277 2004
