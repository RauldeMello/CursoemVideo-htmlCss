# Modelo de caixas

* height (altura)
* width (largura)
* border (borda)
* padding (preenchimento)
    - pode ser padding em todos os lados ou padding específico
* margin (margem, preenchimento externo, padding externo)
    - margin pode ter outline, uma borda fora do elemento

## Tipos de caixas

* Box-level
    - Sempre se inicia em uma nova linha
    - Sempre ocupa a largura total da tela (100% do viewport)
    - Exemplo: <div>, <h1>-<h6>, <p>, <main>, <header>, <nav>, <article>, etc...

* Inline-level
    - Sempre se inicia na mesma linha, sem quebrar
    - Não ocupa 100% do viewport, ocupa o necessário para o conteúdo ser mostrado
    - Exemplo <span>, <a>, <button>, <input>, <strong>, etc...