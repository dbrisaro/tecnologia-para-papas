# Curso de Tecnología para papás

Curso simple de tecnología en 5 clases de una hora: WhatsApp, Google Meet, Google Calendar, Google Docs/Sheets e Inteligencia Artificial.

🌐 **Sitio online:** https://dbrisaro.github.io/tecnologia-para-papas
📄 **PDF:** [curso-tecnologia.pdf](curso-tecnologia.pdf)

## Construir localmente

```bash
# HTML
jupyter-book build .

# PDF
jupyter-book build . --builder pdfhtml
```

## Publicar cambios

```bash
jupyter-book build .
ghp-import -n -p -f _build/html
```
