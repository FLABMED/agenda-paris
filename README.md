# Agenda pública · Misión Empresarial a París 2026 · Fundación LAB

Agenda de la Misión Empresarial de Fundación LAB a París (2, 3 y 4 de noviembre de 2026), publicada con GitHub Pages.

- Página completa: `https://flabmed.github.io/agenda-paris/`
- Versión para incrustar (sin banner, altura automática): `https://flabmed.github.io/agenda-paris/?embed=1`

## Código para incrustar en otra web

```html
<iframe id="agenda-flab-paris"
  src="https://flabmed.github.io/agenda-paris/?embed=1"
  title="Agenda de la Misión Empresarial a París 2026"
  style="width:100%;border:0;min-height:900px" loading="lazy"></iframe>
<script>
  window.addEventListener("message", function (e) {
    if (e.origin !== "https://flabmed.github.io") return;
    if (e.data && e.data.type === "flab-agenda-height") {
      document.getElementById("agenda-flab-paris").style.height = e.data.height + "px";
    }
  });
</script>
```

Si el gestor de la web no permite `<script>`, basta con el `<iframe>` y una altura fija (por ejemplo `height="1600"`).

## Archivos

- `index.html`: la agenda (datos, diseño y lógica, con imágenes incrustadas). Fuente: programa de la misión del 26/10/2026.
