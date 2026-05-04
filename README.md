# Happy Birthday Yeva! 🎂🦖

Un clon del juego del dinosaurio de Chrome hecho con Pygame, con una sorpresa de cumpleaños especial al llegar a 200 puntos.

## Despliegue en GitHub Pages

Este proyecto está configurado para desplegar automáticamente en GitHub Pages usando Pygbag (WebAssembly).

### Pasos para activar:

1. **Ve a la configuración de tu repositorio** en GitHub
2. **Navega a "Pages"** en el menú lateral izquierdo
3. **En "Build and deployment":**
   - Source: Selecciona **"GitHub Actions"**
4. **Haz push de estos cambios** al repositorio
5. **Ve a la pestaña "Actions"** de tu repositorio para ver el progreso del deploy
6. **Una vez completado**, tu juego estará disponible en:
   ```
   https://<tu-usuario>.github.io/Yeva-birthday/
   ```

## Características

- Juego del dinosaurio clásico con controles de salto (⬆️) y agacharse (⬇️)
- **Sorpresa de cumpleaños** al llegar a 200 puntos:
  - Pantalla negra con arte ASCII de un Spinosaurus con gorrito de fiesta 🎉
  - Mensaje "З днем народження, Yeva!" en ucraniano
  - Sonido tipo "beep-beep... beep-beep" estilo Jurassic Park 🎵

## Estructura del proyecto

```
Yeva-birthday/
├── .github/workflows/deploy.yml  # Workflow de GitHub Actions
├── Assets/                       # Imágenes del juego
│   ├── Dino/
│   ├── Cactus/
│   ├── Bird/
│   └── Other/
├── main.py                       # Código principal (adaptado para web)
├── index.html                    # Página web
├── requirements.txt              # Dependencias
└── README.md                     # Este archivo
```

## Desarrollo local

Para probar el juego localmente:

```bash
# Instalar dependencias
pip install pygame pygbag

# Ejecutar localmente
python main.py

# O compilar para web localmente
pygbag --build main.py
```

¡Feliz cumpleaños Yeva! 🎈
