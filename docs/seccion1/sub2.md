# Enlaces, imágenes y listas en HTML

## Enlaces

```html
<a href="https://www.google.com">Ir a Google</a>
```

```html
<a href="https://github.com" target="_blank">GitHub</a>
```

## Imágenes

```html
<img src="https://www.example.com/logo.png" alt="Logo de ejemplo" width="200">
```

!!! tip "Consejo"
    Usa siempre el atributo `alt` para mejorar la accesibilidad.

## Listas

### No ordenada

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

### Ordenada

```html
<ol>
  <li>Primero</li>
  <li>Segundo</li>
  <li>Tercero</li>
</ol>
```

!!! warning "¡Ojo!"
    No pongas listas dentro de `<p>`. No son compatibles.