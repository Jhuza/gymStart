# Sistema de Diseño: GymStart

## Personalidad Visual
Limpio, moderno y motivador. Minimalismo que transmite energía sin saturar.
Inspirado en apps como Nike Training Club y Notion.

## Paleta de Colores

| Nombre | Hex | Uso |
|---|---|---|
| Primario (Acción) | #2563EB | Botones principales y elementos activos |
| Secundario (Éxito) | #10B981 | Metas cumplidas y confirmaciones |
| Fondo General | #F9FAFB | Fondo de la app, evita fatiga visual |
| Fondo Tarjetas | #FFFFFF | Contraste sobre el fondo general |
| Texto Principal | #111827 | Títulos y cuerpo de texto |
| Texto Secundario | #6B7280 | Subtítulos y etiquetas |
| Acento Error | #EF4444 | Alertas y validaciones |
| Acento Agua | #38BDF8 | Exclusivo módulo de hidratación |
| Acento Comida | #F59E0B | Exclusivo módulo de alimentación |

## Tipografía
- **Fuente Principal:** 'Inter' (Google Fonts)
- **H1:** 28px, Bold, #111827
- **H2:** 22px, SemiBold, #111827
- **H3:** 18px, Medium, #111827
- **Cuerpo:** 16px, Regular, #111827
- **Etiquetas/Captions:** 13px, Regular, #6B7280

## Componentes UI

### Botones
```css
button {
    border-radius: 10px;
    padding: 12px 24px;
    transition: all 0.2s ease;
}
button:hover {
    box-shadow: 0 4px 12px rgba(37, 99, 235, 0.2);
}
```

### Tarjetas (Cards)
```css
.card {
    background: #FFFFFF;
    border-radius: 16px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
    padding: 24px;
}
```

### Inputs
```css
input {
    border: 1px solid #E5E7EB;
    border-radius: 8px;
    padding: 10px 14px;
}
input:focus {
    border-color: #2563EB;
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}
```

## Espaciado
Sistema de grilla de 8px — usar siempre múltiplos de 8:
- **XS:** 8px
- **SM:** 16px
- **MD:** 24px
- **LG:** 32px
- **XL:** 48px

## Iconografía
- Librería: **Lucide Icons**
- Estilo: línea fina, coherente con la estética minimalista
- Tamaño estándar: 20px
- Color: heredar del texto contenedor