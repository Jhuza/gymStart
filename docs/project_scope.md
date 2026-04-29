# Alcance del Proyecto: GymStart

## Descripción General
GymStart es una aplicación web diseñada para jóvenes que están comenzando su camino
en el fitness. Permite llevar un registro diario de ejercicios, hidratación y alimentación
en un solo lugar, con una interfaz limpia que no abruma al usuario principiante.

## Usuario Objetivo
Jóvenes entre 16 y 28 años que están empezando en el gym y necesitan una herramienta
simple, visual y motivadora que los ayude a construir hábitos saludables sin complejidad.

## Funcionalidades Principales (Core Features)

### 1. Registro de Ejercicios
- El usuario puede agregar una actividad (ej: "Sentadillas", "Cardio")
- Duración en minutos
- Calorías aproximadas quemadas

### 2. Control de Hidratación
- Contador de vasos de agua consumidos durante el día
- Meta diaria recomendada de 8 vasos
- Indicador visual de progreso

### 3. Registro de Alimentación
- El usuario anota lo que comió
- Calorías aproximadas consumidas
- Categoría de alimento (desayuno, almuerzo, cena, snack)

### 4. Dashboard Principal
- Total de calorías quemadas vs. consumidas
- Progreso de hidratación en tiempo real
- Lista de actividades del día
- Resumen visual motivador

### 5. Historial (Fase futura)
- Ver registros de días anteriores en un calendario
- Gráficas de progreso semanal

### 6. Metas Personales (Fase futura)
- Definir objetivo de calorías y agua por día
- Notificaciones de progreso

## Reglas de Negocio
- No se requiere registro de usuario en la primera versión (datos en LocalStorage)
- La interfaz debe ser Mobile First (pensada para celular)
- El lenguaje debe ser amigable, motivador y sin tecnicismos
- Los datos del día se reinician automáticamente a medianoche
- Las calorías quemadas y consumidas se calculan en tiempo real

## Flujo Principal del Usuario
1. Usuario abre la app → ve el Dashboard con resumen del día
2. Registra un ejercicio → las calorías quemadas se actualizan
3. Registra agua → el contador de vasos sube
4. Registra comida → las calorías consumidas se actualizan
5. Al final del día → ve su resumen completo