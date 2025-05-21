# Probas do formulario

Neste cartafol inclúense scripts para probar e verificar o funcionamento do formulario principal.

## Scripts de proba

- **test-valid-form.html**  
  Proba o formulario con datos válidos pre-rellenos. Ao enviar, debería aparecer unha mensaxe de éxito indicando que o formulario é correcto.

- **test-invalid-form.html**  
  Proba o formulario cos campos baleiros. Ao intentar enviar, deberían aparecer mensaxes de erro e unha alerta indicando que hai campos incorrectos ou baleiros.

## Como verificar as probas manualmente

1. Abre cada ficheiro `.html` deste cartafol nun navegador web.
2. No ficheiro **test-valid-form.html**, preme o botón de envío e comproba que aparece unha mensaxe verde de éxito.
3. No ficheiro **test-invalid-form.html**, preme o botón de envío baleiro e comproba que aparecen mensaxes de erro nos campos obrigatorios e unha alerta vermella.

## Ferramenta empregada nas probas automáticas

[Playwright](https://playwright.dev/)

## Como instalar as dependencias e executar as probas automáticas

1. Instala [Node.js](https://nodejs.org/) se non o tes instalado.
2. Abre unha terminal na raíz do proxecto e executa:

   ```bash
   npm install -D playwright
   ```

3. Para executar as probas automáticas (se tes scripts Playwright configurados):

   ```bash
   npx playwright test
   ```

npx playwriht test

## Estrutura do repositorio

```
bootstrap-html-form/
├── index.php
└── procesar.php
├── tests/
│   ├── formulario.spec.js (ou .test.js para Selenium)
├── .gitignore
├── package.json
├── README.md
```

- **src/**: Código fonte do formulario e estilos.
- **tests/**: Scripts de proba e documentación das probas.
- **.gitignore**: Ficheiro para excluír arquivos e carpetas do control de versións.
- **package.json**: Dependencias e scripts do proxecto (se usas Playwright ou outras ferramentas).
- **README.md**: Documentación principal do proxecto.
