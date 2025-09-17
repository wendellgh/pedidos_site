Site de teste com tabelas HTML paginadas (estático).
Estrutura:
  /pedidos/
    index.html
    /1/index.html
    /2/index.html
    /3/index.html
    /4/index.html
    /5/index.html

Como usar:
- Baixe o zip e extraia.
- No terminal, dentro da pasta extraída, rode:
    python -m http.server 8000
  Acesse no navegador:
    http://localhost:8000/pedidos/1/
    http://localhost:8000/pedidos/2/
  No Power Query, use a Fonte -> Web e aponte para as URLs acima.

Você também pode subir direto no GitHub Pages (colocar a pasta no repositório).
