# Coli Brownies · Gestão

App web (arquivo único `index.html`, JS puro) para gestão da Coli Brownies:

- **Produção:** fornadas viram lotes, com baixa de ingredientes pela ficha técnica (formas 35x35 / 40x30)
- **Estoque de brownies:** controle de validade por lote, saída FEFO (vence primeiro, sai primeiro); locais: casa, casa congelado (validade pausada) e lojas
- **Ingredientes e embalagens:** estoque mínimo, compras com custo médio e lista de compras
- **Lojas (consignado):** envio e acerto (vendido = enviado − sobra − recolhido)
- **Financeiro:** lançamentos, contas a receber e a pagar, fluxo de caixa e DRE por competência

## Armazenamento

Por enquanto os dados ficam no `localStorage` do navegador (chave `coli_mvp_v1`): cada aparelho tem a própria base, e limpar o cache apaga tudo.
Faça backup com **Cadastros → Config → Exportar JSON**.
