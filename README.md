# Projeto: Análise de Sentimentos com Azure Language Studio

**Aluno:** Cleyton Junior Molina  
**Plataforma:** DIO  
**Tecnologias:** Microsoft Azure - Language Studio  

## Objetivo

Este projeto tem como objetivo demonstrar a criação de um ambiente no Azure para realizar **análise de sentimentos** de avaliações e comentários, utilizando o serviço Azure Language.

## Etapas do Projeto

### 1. Criação do Resource Group no Azure

Foi criado um **grupo de recursos** chamado `LAB-9000` no portal do Azure. Dentro desse grupo foram adicionados dois recursos principais:

- **PROJETODIO** (serviço de linguagem)
- **projetodio-asvv...** (serviço de pesquisa)

📷 *Print da criação do lab no Azure:*  
![Lab Azure](./a67e7cff-46fa-4b43-82fe-d92c6cb472ba.png)

---

### 2. Coleta de Dados (Comentário real do Reclame Aqui)

O texto utilizado para análise foi retirado do site Reclame Aqui, em uma reclamação real sobre o Mercado Livre:

🔗 [Reclamação original](https://www.reclameaqui.com.br/mercado-livre/produtos-de-ma-qualidade-e-reembolso-parcial_5H12Tf8zRub3gne4/)

📝 Texto usado na análise:

> "comprei dois produtos de um mesmo vendedor. Artigos de péssima qualidade, eram pra ser calças fusô plus size, eram curtas e justas nas pernas; devolvi no mesmo dia em que chegaram (3 de julho). Até agora não ocorreu o reembolso. Para piorar, hoje entrei na minha conta e vi mensagem de que iriam reembolsar o valor de apenas um dos produtos. Tentei contato com Mercado Livre, simplesmente não consegui acessar o chat. O vendedor não respondeu minha mensagem questionando. Quero todo o meu dinheiro de volta. Não bastasse a perda de tempo e a frustração por ter recebido artigos de péssima qualidade, só falta ainda ter prejuízo."

📷 *Print do texto inserido na ferramenta Language Studio:*  
![Texto Reclame Aqui](./a851204f-7dd3-4c9a-844d-e866409dac47.png)

---

### 3. Análise de Sentimento

Foi utilizada a ferramenta **Language Studio** com o recurso de **Sentiment Analysis**. O resultado obtido indicou:

- **Sentimento Geral:** Negativo  
- **Confiança:** 94% negativo, 6% neutro, 0% positivo

📷 *Print do resultado da análise:*  
![Resultado Análise Sentimento](./4b7a178d-f97d-4c45-86f2-758eb6983187.png)

---

## Aprendizados

Durante este projeto, aprendi a:

- Criar um ambiente (Lab) no Azure com recursos personalizados
- Utilizar o Language Studio para análise de sentimentos
- Realizar extração de texto real de fontes como o Reclame Aqui
- Entender como a IA da Microsoft interpreta sentimentos com base no texto

---

## Conclusão

Este projeto mostra como o Azure pode ser uma ferramenta poderosa para análise de sentimentos em avaliações reais de usuários. A capacidade de classificar emoções e interpretar intenções em larga escala pode ser aplicada em empresas, SACs e plataformas de e-commerce para melhorar o atendimento ao cliente.

