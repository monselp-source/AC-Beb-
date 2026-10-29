# PRD — App de Seguimiento de Alimentación Complementaria

## 1. Objetivo

Aplicación móvil web que permite a una madre registrar qué alimentos ha probado su bebé durante la etapa de alimentación complementaria, a partir de una lista predefinida organizada por categoría. 

**Usuario:** Madre de un bebé de 7 meses iniciando alimentación complementaria.  
**Plataforma:** Navegador móvil (diseño adaptado a pantalla de celular).

---

## 2. Funcionalidades principales

### 2.1 Lista de alimentos predefinida
- La app incluye una lista de alimentos recomendados para alimentación complementaria, organizados en categorías:
  - Frutas
  - Verduras
  - Cereales y tubérculos
  - Proteínas (carnes, legumbres, huevo)
  - Grasas
- Cada alimento tiene dos estados: **Pendiente** o **Probado**.

### 2.2 Marcar un alimento como probado
- La usuaria puede tocar un alimento para marcarlo como "Probado".
- El alimento cambia visualmente de estado (por ejemplo, color o tachado).
- Se puede desmarcar si se marcó por error.

### 2.3 Vista de progreso
- En la pantalla principal se muestra cuántos alimentos se han probado del total.
  - Ejemplo: "12 de 40 alimentos probados"
- El progreso se puede ver también por categoría.

### 2.4 Filtros rápidos
- La usuaria puede filtrar la lista para ver:
  - Todos los alimentos
  - Solo los pendientes
  - Solo los ya probados

---

## 3. Pantallas

| Pantalla | Descripción |
|---|---|
| **Inicio / Lista** | Lista de alimentos agrupados por categoría con estado visual. Barra de progreso total. Filtros en la parte superior. |
| **Detalle de alimento** | Al tocar un alimento se confirma el cambio de estado (probado / pendiente). |

---

## 4. Fuera de alcance (v1)

Las siguientes funcionalidades **no** forman parte de esta versión:

- Registro de fecha en que se probó el alimento
- Registro de reacciones o notas
- Múltiples perfiles de bebé
- Agregar alimentos personalizados a la lista
- Notificaciones o recordatorios
- Sincronización en la nube o entre dispositivos
- Autenticación / login

---

## 5. Datos guardados

Los datos se guardan localmente en el navegador del celular (localStorage).  
No se requiere conexión a internet una vez cargada la app.

---

## 6. Criterios de éxito

- La usuaria puede ver todos los alimentos organizados por categoría.
- Puede marcar y desmarcar alimentos fácilmente con un toque.
- Puede ver su progreso general y por categoría.
- La app funciona bien en pantalla de celular.
