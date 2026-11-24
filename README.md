# Ejercicios de Bootstrap

Colección de prácticas front-end desarrolladas para aprender y experimentar con **Bootstrap 3.3.7**. Los ejercicios muestran componentes, clases utilitarias y técnicas responsivas mediante páginas HTML independientes, acompañadas de estilos locales y recursos distribuidos dentro de cada carpeta.

Este repositorio fue creado con fines educativos y no utiliza frameworks, gestores de paquetes ni procesos de compilación.

## Tecnologías

- **HTML5**: estructura semántica de las páginas.
- **CSS3**: personalización visual de cada ejercicio.
- **Bootstrap 3.3.7**: sistema de rejillas, componentes y utilidades.
- **jQuery 3.1.1**: dependencia JavaScript utilizada por Bootstrap.
- **Glyphicons**: fuente de iconos incluida con Bootstrap.
- **Normalize.css**: normalización de estilos CSS distribuida junto con Bootstrap.

## Prácticas incluidas

| Carpeta | Contenido trabajado |
| --- | --- |
| [`Enlazando Bootstrap`](./Enlazando%20Bootstrap/) | Integración inicial de Bootstrap 3 mediante hojas de estilos y scripts locales. |
| [`PLANTILLA`](./PLANTILLA/) | Plantilla base con la estructura HTML y los recursos necesarios para comenzar una nueva práctica. |
| [`Grid - Sistema de rejillas`](./Grid%20-%20Sistema%20de%20rejillas/) | Contenedores, filas y columnas responsivas con breakpoints `xs`, `sm`, `md` y `lg`; también incluye encabezado, contenido, barra lateral y pie de página. |
| [`Tipografía y textos`](./Tipograf%C3%ADa%20y%20textos/) | Encabezados, textos secundarios, alineaciones, transformación de mayúsculas/minúsculas, colores, fondos, énfasis y bloques de cita. |
| [`Tablas`](./Tablas/) | Tablas adaptables, bordes, filas alternadas, estados visuales y comportamiento responsivo con `.table-responsive`. |
| [`Botones`](./Botones/) | Variantes de botones, tamaños, estados activo y deshabilitado, botones enlazados, alineación y botones de ancho completo. |
| [`Imágenes`](./Im%C3%A1genes/) | Imágenes responsivas y formas con las clases `.img-responsive`, `.img-rounded`, `.img-circle` e `.img-thumbnail`. |
| [`Helper classes`](./Helper%20classes/) | Clases auxiliares para colores, fondos, alineación, visibilidad, flotado, centrado y limpieza de flotantes. |
| [`Formularios`](./Formularios/) | Diferentes patrones de formularios: controles básicos, selección y carga de archivos, formulario inline, grupos horizontales y estados de validación. |

## Funcionalidades y conceptos practicados

- Diseño responsivo basado en el sistema de rejillas de 12 columnas.
- Uso de contenedores fijos y fluidos.
- Componentes visuales de Bootstrap y estados contextuales.
- Adaptación a distintos tamaños de pantalla.
- Diseño de encabezados, contenido principal, barras laterales y pies de página.
- Formularios, campos, controles, checkbox, radio buttons, archivos y validaciones visuales.
- Tipografía, tablas, botones e imágenes.
- Reutilización de una plantilla común y recursos locales.
- Organización de ejercicios como ejemplos aislados y fáciles de comparar.

## Vista rápida del proyecto

```text
bootstrap-ejercicios/
├── Enlazando Bootstrap/
├── PLANTILLA/
├── Grid - Sistema de rejillas/
├── Tipografía y textos/
├── Tablas/
├── Botones/
├── Imágenes/
├── Helper classes/
└── Formularios/
```

Cada carpeta contiene su propia copia de Bootstrap, jQuery y CSS personalizable. Esto permite abrir las prácticas de forma independiente y facilita el estudio de los recursos usados en cada ejemplo.

## Cómo ejecutarlo

Al ser un sitio totalmente estático, no necesita instalación de dependencias ni compilación.

### Abrir directamente

1. Clona el repositorio:

   ```bash
   git clone https://github.com/FabianNorbertoEscobar/bootstrap-ejercicios.git
   cd bootstrap-ejercicios
   ```

2. Abre el archivo `index.html` de la práctica que quieras visualizar con el navegador.

### Ejecutar con un servidor local

Desde la raíz del repositorio:

```bash
python3 -m http.server 8000
```

Después visita `http://localhost:8000/` y navega hasta la carpeta deseada. Por ejemplo:

- `http://localhost:8000/Botones/`
- `http://localhost:8000/Grid%20-%20Sistema%20de%20rejillas/`
- `http://localhost:8000/Formularios/`

## Organización de las páginas

Las prácticas siguen esta estructura habitual:

```text
Practica/
├── index.html
├── css/
│   ├── bootstrap.min.css
│   ├── bootstrap-theme.min.css
│   └── estilos.css
├── js/
│   ├── jquery-3.1.1.min.js
│   ├── bootstrap.min.js
│   └── npm.js
└── fonts/
```

El archivo `css/estilos.css` contiene los ajustes propios de cada ejercicio. Los archivos `bootstrap.css`, `bootstrap.min.css` y `bootstrap-theme.css` pertenecen a la distribución de Bootstrap utilizada en el proyecto.

## Recomendación de aprendizaje

Se recomienda recorrer las carpetas en este orden:

1. **Enlazando Bootstrap**: comprender la integración.
2. **PLANTILLA**: conocer la estructura base.
3. **Tipografía y textos** y **Botones**: practicar clases visuales.
4. **Grid - Sistema de rejillas**: aprender el diseño responsivo.
5. **Tablas** e **Imágenes**: incorporar componentes y recursos.
6. **Helper classes**: dominar las utilidades de Bootstrap.
7. **Formularios**: consolidar controles, estados y layouts.

## Notas

- La práctica de imágenes utiliza URLs externas de `lorempixel.com`; es posible que dejen de mostrar imágenes si el servicio ya no está disponible.
- Los ejercicios conservan el estilo y las convenciones de Bootstrap 3, una versión anterior a Bootstrap 4 y 5.
- No hay autenticación, persistencia de datos ni backend: los formularios son ejemplos visuales y educativos.

## Autor

Fabián Norberto Escobar
