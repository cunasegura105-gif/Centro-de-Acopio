# StockRed

Plataforma web diseñada para la coordinación en tiempo real de centros de acopio. Permite llevar la trazabilidad de inventarios por campaña, gestionar donaciones, registrar operaciones mediante lectura de códigos de barras y visualizar el estado operativo de los centros.

Sitio publicado: [stockred-105.netlify.app](https://stockred-105.netlify.app)

## Características principales

* **Mapa de centros activos:** Visualización interactiva con mapas y estado operativo de cada punto de acopio.
* **Módulo de operaciones y escaneo:** Registro rápido de movimientos de inventario optimizado para lectura de códigos de barras.
* **Panel de indicadores (KPIs):** Conteo automático de donaciones totales, entregas realizadas, centros activos y campañas vigentes.
* **Modelo de base de datos:** Propuesta y diseño del esquema relacional (`stockred_db.sql`) para futura integración backend.

## Tecnologías utilizadas

* **Frontend:** HTML5, JavaScript (ES6+), Tailwind CSS
* **Mapas interactivos:** Leaflet.js
* **Base de Datos (Esquema):** SQL
* **Hosting / Despliegue:** Netlify
* **Control de versiones:** Git & GitHub

## Estructura del repositorio

```text
StockRed/
├── html/
│   └── index.html               # Interfaz principal de la aplicación web
├── DOCUMENTACIÓN STOCKRED...     # Documentación técnica del proyecto
└── stockred_db.sql              # Script con el esquema de base de datos propuesto
```

## Metas a futuro
**Pronóstico del tiempo**  
  Alertas meteorológicas en tiempo real para la prevención y preparación de centros de acopio y comunidades vulnerables.

**Integración con redes sociales**  
  Difusión de campañas activas directamente desde la plataforma para lograr mayor visibilidad y maximizar la recaudación.

**Integración backend avanzada**  
  Conexión y expansión completa del esquema SQL propuesto para la persistencia total de datos en la nube.

## Ejecución local
Para revisar el código fuente o ejecutar la aplicación localmente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/cunasegura105-gif/Centro-de-Acopio.git
   ```

2. Entra al directorio del proyecto y ejecuta el archivo StockRed/html/index.html en tu navegador web.

**Equipo de desarrollo**
  Roel Armando Martinez Rico
  Jorge Arturo Guzman Ponce
  Ericka Denisse Najera Herrera
