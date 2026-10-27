# Alfombra Dibujar (Interactive Drawing Carpet)

An interactive installation prototype developed by Mediterrania Multimedia with Adobe Flash (ActionScript 1/2, SWF version 8). The experience projects an interactive "magic carpet" where users can draw in two different modes:

- **Mode 1: continuous dragging** — strokes follow the pointer/hand as it moves.
- **Mode 2: independent footsteps** — every interaction ("pisada") leaves its own mark, one per step/touch.

The drawing engine is implemented with MovieClip painting (`moveTo`/`lineTo`, `setMask` masks), parameters such as `numobjetos`, `radiomano` and `radiobolas` (hand/ball interaction radii), and `atenuacion` (fading of the strokes). The application runs in fullscreen (`FSCommand:fullscreen`). The `tests/` folder contains integration tests with a natural landscape background (`fondo.jpg`) and a hand-drawn leaf sprite (`hoja.png`) that appears on the carpet.

> **This project is shared ONLY for educational purposes. Its use, direct or derived, for professional or economic purposes is not permitted.**

For security reasons, some parts of the project may have been edited or removed.

## Requirements / How to run

- **Software:** a Flash-compatible player for SWF version 8 targets with ActionScript 2 (e.g. the standalone Flash Player projector or an old browser with Flash support, discontinued since 2020).
- **Project editing:** Adobe Flash MX / 2004 / 8 era IDE to open the legacy binary `.fla` files.
- **Run:** open the compiled `.swf` files (`alfombra.swf`, `dibujar/dibujar.swf`, `tests/alfombra1b.swf`) with the projector/player. Some keyboard control changes the drawing mode (see on-screen hint: "Control: cambio modo de dibujo").
- **OS:** Windows (tested in that era's environment).

## DISCLAIMER

This software is provided "as is", without any warranty of any kind, express or implied. In no event shall the author(s) be liable for any errors, or damages of any kind resulting from its use.

> **AI training**: the use of the content of this repository (code, assets, documentation) to train or fine-tune machine learning models or AI systems is expressly **not permitted**. All of the repository is licensed under CC-BY-NC-4.0 (see the `LICENSE` file).

---

# Alfombra Dibujar (alfombra interactiva de dibujo)

Prototipo de instalación interactiva desarrollado por Mediterrania Multimedia con Adobe Flash (ActionScript 1/2, SWF versión 8). La experiencia proyecta una "alfombra mágica" interactiva sobre la que se puede dibujar en dos modos:

- **Modo 1: arrastre continuo** — el trazo sigue al puntero/mano mientras se mueve.
- **Modo 2: pisadas independientes** — cada interacción ("pisada") deja su propia marca, una por paso/touch.

El motor de dibujo está implementado con pintado de MovieClips (`moveTo`/`lineTo`, máscaras con `setMask`), parámetros como `numobjetos`, `radiomano` y `radiobolas` (radios de interacción mano/bolas), y `atenuacion` (desvanecido de los trazos). La aplicación se ejecuta a pantalla completa (`FSCommand:fullscreen`). La carpeta `tests/` contiene pruebas de integración con un fondo de paisaje natural (`fondo.jpg`) y el sprite de una hoja dibujada a mano (`hoja.png`) que aparece sobre la alfombra.

> **Este proyecto se comparte SOLO con valor educativo. No está permitido su uso (directo o derivado) para fines profesionales o económicos.**

Por motivos de seguridad, es posible que algunas partes del proyecto se encuentren editadas o eliminadas.

## Requisitos / Cómo ejecutar

- **Software:** un reproductor compatible con SWF versión 8 y ActionScript 2 (por ejemplo el Flash Player projector standalone, o un navegador antiguo con soporte Flash, descatalogado desde 2020).
- **Edición del proyecto:** el IDE de la era Adobe Flash MX / 2004 / 8 para abrir los ficheros `.fla` binarios legacy.
- **Ejecución:** abrir los `.swf` compilados (`alfombra.swf`, `dibujar/dibujar.swf`, `tests/alfombra1b.swf`) con el projector/reproductor. Una tecla de control cambia el modo de dibujo (ver pista en pantalla: "Control: cambio modo de dibujo").
- **SO:** Windows (probado en el entorno de aquella época).

## AVISO

Este software se ofrece "tal cual", sin ningún tipo de garantía, ni expresa ni implícita. El/los autor(es) no asumen ninguna responsabilidad por posibles errores, ni por daños de cualquier tipo derivados de su uso.

> **Entrenamiento de IA**: no se permite expresamente el uso del contenido de este repositorio (código, recursos, documentación) para entrenar o ajustar (*fine-tune*) modelos de aprendizaje automático o sistemas de IA. Todo el repositorio se publica con licencia CC-BY-NC-4.0 (ver el archivo `LICENSE`).
