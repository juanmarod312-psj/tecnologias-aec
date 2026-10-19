# Panel Didáctico: Tecnologías Emergentes en AEC (Modelado Hidrológico en México)

Aplicación web interactiva de un solo archivo (`index.html`), construida a partir de la investigación auditada en `investigacion.md` para apoyar la toma de decisiones en una consultoría hidrológica en México enfocada en reducir retrabajos de gabinete.

## 1. Cómo abrir y utilizar el panel
1. Descarga o guarda el archivo `index.html` en cualquier carpeta de tu computadora o dispositivo móvil.
2. Haz **doble clic** sobre `index.html`. Se abrirá directamente en tu navegador predeterminado (Chrome, Edge, Firefox, Safari).
3. **No requiere internet, servidores locales, Node.js, ni claves de API.**

## 2. Funciones disponibles
* **Separación Epistemológica (Sección 1):** Distingue visualmente entre *Hechos Comprobables*, *Inferencias Técnicas*, *Propuestas Operativas* y *Lagunas de Evidencia (`Requiere validación`)*.
* **Explorador y Filtros Combinados (Sección 2):**
  * Buscador en tiempo real por palabras clave (ej. `Manning`, `HEC-RAS`, `dron`, `Tabasco`, `CONAGUA`).
  * Filtros acumulativos por **Tecnología**, **Etapa del Proyecto** (Fases 1, 2 y 3) y **Nivel de Adopción en México**.
  * Botones para **Expandir** o **Contraer** simultáneamente los detalles técnicos de las fichas visibles.
* **Comparador Lado a Lado (Sección 3):** Selecciona hasta **3 tecnologías** mediante la casilla `Comparar` en cada ficha. Si intentas seleccionar una cuarta, el sistema bloqueará la casilla y mostrará un aviso.
* **Pilotos Propuestos (Sección 4):** Presenta los 3 pilotos estructurados con responsable, insumos, pasos numerados, métrica de éxito sujeta a validación y límite de seguridad.
* **Glosario para Principiantes y Fuentes (Sección 5):** Buscador rápido de términos básicos y listado íntegro de URLs verificadas.

## 3. Cómo editar o actualizar los datos sin saber programar
Toda la información del panel está separada del diseño visual. Para actualizar un texto, agregar una referencia o modificar un piloto:
1. Abre `index.html` en cualquier editor de texto (Bloc de notas, VS Code, Notepad++).
2. Busca la línea que dice:
   ```javascript
   const APP_DATA = {