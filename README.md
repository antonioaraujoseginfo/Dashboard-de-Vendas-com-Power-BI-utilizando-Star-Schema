## Dashboard de Vendas com Power BI utilizando Star Schema

Este projeto é um dashboard interativo de vendas desenvolvido com Power BI, utilizando um esquema em estrela (Star Schema) para modelagem dos dados. O objetivo é fornecer insights detalhados sobre o desempenho de vendas, permitindo a análise de métricas chave como faturamento, quantidade vendida, e desempenho por produto, região e período.

## Tabela de Conteúdos

1. [Introdução](#introdução)
2. [Objetivos do Projeto](#objetivos-do-projeto)
3. [Arquitetura de Dados](#arquitetura-de-dados)
4. [Instalação](#instalação)
5. [Como Usar](#como-usar)
6. [Contribuição](#contribuição)
7. [Licença](#licença)
8. [Contato](#contato)

## Introdução

Este projeto foi desenvolvido para demonstrar a aplicação do Star Schema na construção de um dashboard de vendas com Power BI. O Star Schema foi escolhido por sua simplicidade e eficiência na modelagem de dados para relatórios e análises.

## Objetivos do Projeto

- Desenvolver um dashboard de vendas completo utilizando Power BI.
- Aplicar o Star Schema para modelagem de dados.
- Fornecer insights claros e detalhados sobre as métricas de vendas.
- Permitir a visualização de dados por diferentes dimensões, como tempo, produto e região.

## Arquitetura de Dados

O esquema em estrela utilizado neste projeto é composto por uma tabela fato central (Vendas) e várias tabelas de dimensão (Tempo, Produto, Cliente, Região). Esta arquitetura permite consultas rápidas e eficientes, facilitando a análise de grandes volumes de dados.

- **Tabela Fato (Vendas):** Contém as métricas principais como quantidade vendida, receita e custo.
- **Tabelas Dimensão:**
  - **Tempo:** Data, mês, ano, trimestre.
  - **Produto:** Nome, categoria, subcategoria.
  - **Cliente:** Nome, região, segmento.
  - **Região:** País, estado, cidade.

## Instalação

1. Clone este repositório para sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/Dashboard_Vendas_Power_Bi_utilizando_Star_Schema.git
    ```

2. Abra o arquivo `.pbix` no Power BI Desktop.

3. Conecte o Power BI aos seus dados de vendas. Verifique se as conexões de dados estão configuradas corretamente.

4. Atualize os dados e explore o dashboard.

## Como Usar

1. **Filtros:** Use os filtros disponíveis para segmentar os dados por diferentes períodos, produtos, regiões e outras dimensões.
2. **Visualizações:** Explore gráficos interativos de barras, linhas e mapas que mostram tendências e padrões de vendas.
3. **Exportação:** Exporte relatórios e gráficos para PDF ou outros formatos para compartilhamento.

## Contribuição

Contribuições são bem-vindas! Se você deseja colaborar:

1. Faça um fork do repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça suas alterações e comite-as (`git commit -m 'Descrição das alterações'`).
4. Envie suas mudanças (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

- **Nome:** Antonio Araújo
- **Email:** antonioaraujolb@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/antonio-araujo-seginfo/

---
