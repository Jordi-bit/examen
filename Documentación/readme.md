# 🚀 Examen, debugging y documentacion 🚀

Detectar fallos en codigo, analizar una tabla en excel, crear un grafico, documentarlo todo en un Readme y publicarlos en github

---

## 📋 Tabla de Contenidos

- [🚀 Examen, debugging y documentacion 🚀](#-examen-debugging-y-documentacion-)
  - [📋 Tabla de Contenidos](#-tabla-de-contenidos)
  - [📦 Debug](#-debug)
    - [Descargar ficheros](#descargar-ficheros)
    - [Pasos](#pasos)
  - [▶️ Uso](#️-uso)
    - [Funcionalidades principales:](#funcionalidades-principales)
  - [🧰 Tecnologías](#-tecnologías)
  - [📁 Estructura del Proyecto](#-estructura-del-proyecto)
  - [🤝 Contribución](#-contribución)
  - [🪪 Licencia](#-licencia)
  - [👤 Autor](#-autor)
  - [🗕 Estado del Proyecto](#-estado-del-proyecto)
## 📦 Debug

### Descargar ficheros

- Index.html
- styles.css
- main.js

### Pasos

Mirar los codigos y corregir errores como en el de muestra.

```js
 for (let i = 0; i > 1000; i++) { 
      
      const fecha = generarFechaAleatoria();
      const cantidad = Math.floor(Math.random() * 10) + 1;
      const producto = productos[Math.floor(Math.random() * productos.length)];
      const precioUnitario = (Math.random() * 90 + 10).toFixed(2); // entre 10.00 y 100.00
      const importe = (cantidad * precioUnitario).toFixed(2);

      const fila = [fecha, cantidad, `"${producto}"`, importe].join(",");
      filas.push(fila);
    }
```

---

## ▶️ Uso

Abre tu navegador y accede a:

```
https://github.com/Jordi-bit/examen.git
```

### Funcionalidades principales:

- Podras acceder a los archivos
- Acceso a Documentación
- Uso del html para la descarga de un fichero

---

## 🧰 Tecnologías


- **Frontend:** HTML, CSS, Javascript

- **Procesadores de texto y calculo:** Hoja de calculo, Docs 

---

## 📁 Estructura del Proyecto

```
proyecto/
├── programa/
│   ├── index.html
│   ├── styles.css
│   ├── main.js
│ 
├── Hoja de calculo
├── Docs
├── MarkDown

```

---

## 🤝 Contribución

¡Las contribuciones son bienvenidas!

1. Haz un fork
2. Crea una nueva rama: `git checkout -b feature/mi-feature`
3. Haz commit de tus cambios: `git commit -m 'Agrega nueva funcionalidad'`
4. Sube tu rama: `git push origin feature/mi-feature`
5. Abre un Pull Request

---

## 🪪 Licencia

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---

## 👤 Autor

**Jordi-bit**  
GitHub: [@jordi-bit](https://github.com/jordi-bit)

---

## 🗕 Estado del Proyecto

📈 En desarrollo

