# 🎄 Calendario de adviento

Una página web con 24 casillas, una por cada día del 1 al 24 de diciembre. Cada casilla solo se puede abrir a partir de su día (hora de España) y guarda en el navegador cuáles se han abierto ya.

## Personalizar

Todo se cambia en el bloque `CONFIG` al principio del `<script>` de `index.html`:

- `nombre`: su nombre (sale en el subtítulo)
- `firma`: cómo firmas al final
- `dias`: los 24 mensajes. Cada uno tiene `emoji`, `titulo`, `texto` y un `regalo` opcional (un plan, una pista, un vale…). Si dejas `regalo: ""` no aparece la cajita.

## Probarlo antes de diciembre

- `index.html?prueba` → todas las casillas se pueden abrir
- `index.html?dia=10` → simula que es 10 de diciembre

## Publicarlo con GitHub Pages

1. En el repo: **Settings → Pages**
2. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
3. En un par de minutos estará en `https://<tu-usuario>.github.io/<nombre-del-repo>/`
