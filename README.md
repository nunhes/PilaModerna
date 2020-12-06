# PilaModerna
 Pila moderna de desenvolvemento frontend

## Pila esencial de ferramentas para proxectos front-end.

Outra opción é ir ó fundamental e construír a nosa solución a partires de aí. 🚀

No cartafol do noso proxecto ```pilafrontend``` crearemos os arquivos ```index.html``` e ```index.js```

En ```index.html``` inserimos un pequeno esqueleto html5:

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Pila frontend elemental</title>

    <link src="css/app.css">
</head>
<body>
    <script src="js/app.js"></script>
</body>
</html>
```

No arquivo ```index.js``` engadimos algún método para confirmar a conexión entre ámbolos arquivos: un ```cosole.log``` ou un ```document.write``` coa data actual poderían servir para encetar. Coma:

```js
document.write(new Date())
```

Si todo vai ben xa poderás ver o teu ```index.html``` no teu navegador amosando a data de hoxe.