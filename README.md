# Diccionarios de Broots

Los diccionarios sin internet de [Broots](https://github.com/IVANICUSXXIII/broots), un gestor de e-books compatible con Calibre. Broots baja de acá el del idioma que hace falta, la primera vez que se pide, y verifica su huella. Para usarlos no hay que hacer nada a mano.

Están en [las versiones](https://github.com/IVANICUSXXIII/broots-diccionarios/releases) de este repositorio: una base SQLite por idioma (español, inglés y portugués), comprimida con Brotli.

Son una versión **resumida** de [Wiktionary](https://www.wiktionary.org/), obra de sus colaboradores, con los datos que [kaikki.org](https://kaikki.org/) extrae con [wiktextract](https://github.com/tatuylonen/wiktextract). Qué se cambió y a quién se le da el crédito está en [CREDITOS.txt](CREDITOS.txt).

**Licencia:** [CC BY-SA 4.0](LICENSE), la misma de Wiktionary. Broots tiene su propia licencia (GPL-3.0); estos datos son archivos aparte. El programa que los arma es `app/scripts/armar-diccionarios.mjs`, en el repositorio de Broots.

---

The offline dictionaries of [Broots](https://github.com/IVANICUSXXIII/broots), a Calibre-compatible e-book manager. Broots downloads the one it needs from here the first time it's requested and verifies its checksum.

They are an **abridged** version of [Wiktionary](https://www.wiktionary.org/), by its contributors, using data extracted by [kaikki.org](https://kaikki.org/) with [wiktextract](https://github.com/tatuylonen/wiktextract). See [CREDITOS.txt](CREDITOS.txt) for changes and credits.

**License:** [CC BY-SA 4.0](LICENSE), same as Wiktionary. Broots has its own license (GPL-3.0); this data ships as separate files.
