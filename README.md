# Challenge Alura Store Brasil

Este projeto apresenta uma análise de dados detalhada sobre o desempenho de quatro unidades da **Alura Store BR**. O objetivo central foi identificar, através de indicadores de performance (KPIs), a unidade com menor eficiência para subsidiar uma decisão estratégica de desinvestimento (venda), permitindo que o Senhor João inicie um novo empreendimento com capital otimizado.

---

## 🛠️ Tecnologias e Práticas Aplicadas

* **Python & Pandas**: Utilizados para o carregamento de arquivos CSV, tratamento de dados e extração de métricas essenciais como faturamento total e ticket médio.
* **Matplotlib**: Empregada para a criação de visualizações gráficas (barras, categorias e satisfação), facilitando a interpretação dos resultados para o público leigo.
* **Análise de Dados**: Comparação multidimensional de desempenho entre diferentes unidades, cruzando volume de vendas com categorias de produtos e satisfação.

---

## 📊 Visualizações e KPIs

Neste projeto, foram geradas visualizações para responder aos seguintes requisitos:
1. **Faturamento por Loja**: Identificação da saúde financeira bruta.
2. **Mix de Produtos**: Análise de quais categorias trazem mais retorno.
3. **Avaliação de Satisfação**: Medição da experiência do cliente.


---

## Análise e Recomendação Final


A análise inicial revela que, embora todas as lojas operem com um volume de vendas quase idêntico (aproximadamente 2.359 itens por unidade), existe uma disparidade clara no faturamento bruto. A Loja 4 apresenta o menor faturamento da rede (R$ 1,38M), enquanto a Loja 1 lidera o grupo.

<img width="691" height="496" alt="Gráfico de Faturamento por Loja" src="https://github.com/user-attachments/assets/8721063b-ab3e-4b08-b06f-c5a18979782f" />

A Loja 4 concentra suas vendas em categorias de baixo valor agregado, resultando no menor ticket médio do grupo. Como observado no gráfico abaixo, possui um número de vendas significativamente menor em categorias premium como Eletrônicos e Eletrodomésticos em comparação às demais.

<img width="1387" height="790" alt="Gráfico de Valor Total por Categoria" src="https://github.com/user-attachments/assets/cfb42e3c-f6fd-46ce-b147-bab28051534a" />

O esforço logístico para movimentar milhares de itens é praticamente o mesmo para todas as lojas, conforme demonstrado pela distribuição equilibrada das quantidades vendidas:

<img width="1490" height="790" alt="Gráfico de Quantidade Total por Categoria" src="https://github.com/user-attachments/assets/04a2d760-d1d9-4446-b770-27329df92272" />

Diferente da Loja 1, que apesar de enfrentar desafios operacionais como custos de frete elevados e a menor nota de satisfação (3.98), ainda se mantém como o maior ativo financeiro (R$ 1,53M), a Loja 4 não oferece uma vantagem competitiva que justifique sua manutenção em detrimento de uma unidade mais rentável.

<img width="536" height="573" alt="Gráfico de Avaliação de Satisfação" src="https://github.com/user-attachments/assets/f7fbab1d-94c4-4a01-8423-dd4099e26abe" />

---

## Conclusão

Com base nos dados processados, o diagnóstico indica que a Loja 4 é a unidade recomendada para venda.

A análise revelou que, embora todas as lojas vendam um volume de itens quase idêntico (aprox. 2.359), a Loja 4 possui o menor faturamento da rede (R$ 1,38M). Isso ocorre porque ela concentra suas vendas em categorias de baixo valor, resultando no menor ticket médio do grupo. Diferente da Loja 1, que apesar de ter custos de frete altos e baixa satisfação, é o maior ativo financeiro (R$ 1,53M), a Loja 4 exige o mesmo esforço operacional para entregar o menor retorno financeiro, tornando-a a escolha mais lógica para venda.

