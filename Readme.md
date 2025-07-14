📌 Recomendaciones al nombrar variables de colores:
Nombre de variable	Uso sugerido
--color-primary	Color principal (marca o énfasis)
--color-secondary	Color secundario (fondo alternativo)
--color-background	Fondo general de la app
--color-surface	Fondo de tarjetas o secciones
--color-text	Texto principal
--color-muted	Texto atenuado o secundario
--color-border	Bordes y líneas suaves
--color-success	Indicadores positivos
--color-error	Indicadores de error
--color-warning	Advertencias
--color-info	Mensajes informativos

🎨 Base del sistema (diseño atómico mínimo)
Elemento	¿Está incluido?	Descripción breve
Variables SASS	✅	Paleta de colores, fuentes, tipografía
Reset/Base	✅	Reset CSS + estilos base para body, html, etc.
Layout	✅	Header, Sidebar, Footer, Main layout
Utilidades	✅	Mixins, funciones, helpers
Dark mode	✅	Tema oscuro modificando las variables

🧩 Componentes esenciales de UI
Componente	¿Está incluido?	Finalidad principal
Button	✅	Acciones principales/secundarias
Card	✅	Contenedor de bloques de información
Form	✅	Campos de entrada reutilizables
Table	✅	Visualización de datos estructurados
Alert	✅	Mostrar mensajes importantes de estado
Modal	✅	Diálogos emergentes (confirmaciones)
Tag/Badge	✅	Estados, etiquetas, pequeños indicadores

💡 ¿Qué más podrías agregar después?
Esto ya es suficiente para lanzar un SaaS MVP o Admin Panel funcional.
Pero a medida que escales, podrías añadir:

Componente / Funcionalidad	Justificación
Navbar con dropdown	Navegación compleja
Tabs	Navegación por secciones
Breadcrumb	Mejora la jerarquía visual
Sidebar con collapses	Mejor UX si hay muchos módulos
Toasts / Notifications	Feedback no bloqueante
Skeleton loaders	Mejora UX durante cargas
Avatar / UserMenu	Perfil y sesión
Theme switcher	Light/Dark Mode en toggle
Pagination	Navegar tablas grandes
Chart básico (opcional)	Visualizar métricas

