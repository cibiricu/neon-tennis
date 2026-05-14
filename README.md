# Neon Tennis Rush

Archivos listos para subir a GitHub Pages y después crear el paquete Android con PWABuilder.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub.
2. Sube todos estos archivos a la raíz del repositorio, no dentro de una carpeta.
3. Entra en **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y carpeta `/root`.
6. Guarda y espera a que GitHub te dé la URL pública.

## Después

Cuando la web funcione, pega esa URL en PWABuilder para generar el `.aab` de Google Play.

Package ID recomendado para Google Play:

```text
com.cibiricu.neontennisrush
```

Para subir una actualización a Google Play, usa el mismo Package ID y sube el Version Code.
