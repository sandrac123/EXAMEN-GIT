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
