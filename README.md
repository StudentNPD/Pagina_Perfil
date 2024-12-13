# Página de Perfil

## Descripción

Este proyecto es una recreación de una página de perfil de usuario utilizando HTML y CSS. La página incluye elementos comunes de redes sociales profesionales como información personal, conexiones, solicitudes pendientes y detalles educativos.

## Características

- Navbar responsivo con menú de navegación
- Tarjeta de perfil de usuario con foto y descripción
- Sección de solicitudes de conexión con botones de acción
- Lista de conexiones actuales
- Sección de educación y logros
- Diseño moderno con sombras y bordes redondeados
- Esquema de colores profesional

## Estructura del Proyecto

```
proyecto/
│
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── foto_perfil.png
│       └── uifaces-popular-image(1-6).jpg
```

## Tecnologías Utilizadas

- HTML5
- CSS3
- Normalize.css (CDN)

## Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/StudentNPD/Pagina_Perfil.git
   ```
2. Abre el archivo `index.html` en tu navegador web preferido
3. Para modificar estilos, edita el archivo `style.css` en la carpeta `assets/css`

## Estructura de Componentes

- **Navbar**: Barra de navegación superior con logo y menú
- **Card Usuario**: Tarjeta principal con información del perfil
- **Card Solicitudes**: Sección de solicitudes de conexión pendientes
- **Card Conexiones**: Lista de conexiones actuales
- **Card Education**: Información educativa y logros

## Personalización

Para personalizar el diseño, puedes modificar las siguientes variables CSS:

```css
:root {
  --color-card: white;
}
```

## Contribución

1. Haz un Fork del proyecto
2. Crea una nueva rama (`git checkout -b feature/AmazingFeature`)
3. Realiza tus cambios
4. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
5. Push a la rama (`git push origin feature/AmazingFeature`)
6. Abre un Pull Request

## Tiempo Estimado de Desarrollo

- Configuración inicial: 30 minutos
- Estructura HTML: 1 hora
- Estilos CSS: 2-3 horas
- Ajustes y refinamiento: 1 hora
- Total estimado: ~4-5 horas

## Consejos de Desarrollo

- Comienza trabajando de arriba hacia abajo y de afuera hacia adentro
- Utiliza las herramientas de desarrollo del navegador para depurar estilos
- Mantén la consistencia en el espaciado y los colores
- Prueba en diferentes tamaños de pantalla para asegurar responsividad
