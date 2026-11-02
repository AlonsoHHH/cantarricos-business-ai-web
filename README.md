# Cantarricos Business AI — sitio informativo OAuth

Sitio estático público e independiente del chatbot y del repositorio de producción.

## Publicación en GitHub Pages
1. Crear un repositorio **público** nuevo, por ejemplo `cantarricos-business-ai-web`.
2. Subir `index.html` y `privacidad.html` a la raíz de la rama principal.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Comprobar que abren las páginas y que el enlace de privacidad funciona.

## Importante sobre Google OAuth
Google exige verificar la propiedad del dominio utilizado por el sitio para determinadas verificaciones OAuth. Una URL `github.io` **no garantiza** que cumpla este requisito. Si Google no permite verificarla como propia, habrá que conectar un dominio personalizado y verificar su propiedad en Search Console.

Este sitio no recoge datos, no contiene analítica, no expone tokens y no realiza OAuth; solo informa de la finalidad y privacidad de la aplicación.
Revisar las afirmaciones sobre almacenamiento y seguridad contra la implementación final antes de publicar la app OAuth en producción.
