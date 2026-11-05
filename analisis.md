1. **Diferencia entre window y objetos nativos como Math o JSON, y por qué no hace falta escribir window.MathDiferencia de categoría y ámbito:**

**Objeto window (BOM)**: Es el objeto padre en el entorno del cliente que representa la ventana del navegador y actúa como el ámbito global de toda la ejecución de JavaScript en el navegador. Pertenece al entorno del navegador (BOM).   

**Objetos Nativos (Math, JSON, etc.):** Pertenecen al núcleo del lenguaje JavaScript (Core) y forman parte de sus objetos predefinidos fundamentales para realizar operaciones como cálculos matemáticos avanzados.   

**¿Por qué no hace falta escribir window.Math?**
Porque window es el objeto global y padre de todos los demás objetos en el navegador. Cualquier elemento, objeto o variable declarada o disponible en el ámbito global es automáticamente una propiedad o método de window. Por ello, es lo mismo escribir window.Math que math.

**window.open():** Objeto del Navegador (BOM).   
**parseFloat():** Objeto Nativo de JS.   
**Math.floor():** Objeto Nativo de JS.
**navigator.userAgent:** Objeto del Navegador (BOM).