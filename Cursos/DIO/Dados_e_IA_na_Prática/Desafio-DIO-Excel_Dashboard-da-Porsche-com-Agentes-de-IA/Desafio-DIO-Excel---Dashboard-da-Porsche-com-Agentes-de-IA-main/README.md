# 🏎️ Desafio DIO: Dashboard Interativa de Vendas da Porsche com IA

> **Projeto:** Criando uma Dashboard da Porsche com Agentes de IA
>
> **Acesso à Dashboard:** [🔗 Clique aqui para ver a Dashboard em funcionamento](https://chatgpt.com/share/6ab3de75-26d0-83e9-8a7f-84d72ba6d683)

## 📌 Sobre o Projeto

Este projeto é a resolução do desafio prático da plataforma **DIO (Digital Innovation One)**, onde o objetivo foi transformar uma planilha com dados de vendas da Porsche em uma **Dashboard Interativa Web (HTML/CSS/JS em arquivo único)**, utilizando Inteligência Artificial (ChatGPT Canvas / Agentes de IA) para gerar o código.

O resultado final é um painel dinâmico, publicado via GitHub Pages, que responde a perguntas reais de negócio através de gráficos e filtros interativos, sem depender das limitações do Excel.

## 📸 Demonstração do Projeto

![Print da Dashboard](imgs/Captura%20de%20tela%202026-09-23%20111536.png)

## 📊 Perguntas de Negócio Escolhidas

Para que a dashboard fosse útil e não apenas um "amontoado de gráficos", defini as seguintes perguntas de negócio para guiar a visualização:

1. **Qual é o modelo de veículo que gera a maior receita total?**

   * **Por quê:** Entender qual produto traz o maior impacto financeiro é fundamental para direcionar esforços de marketing e estoque. O gráfico escolhido para responder a isso foi um \[ex: Gráfico de Barras\].

2. **Qual é a distribuição das vendas por método de pagamento?**

   * **Por quê:** Ajuda a equipe financeira a entender a liquidez e a preferência dos clientes de alto padrão (ex: Financiamento vs. PIX/À vista). Respondido com um \[ex: Gráfico de Rosca/Pizza\].

3. **Qual região (Estado/Cidade) concentra o maior volume de vendas?**

   * **Por quê:** Permite mapear oportunidades de expansão de concessionárias ou eventos regionais da marca. Respondido com um \[ex: Gráfico de Colunas\].

## 🧹 Tratamento da Base de Dados

Antes de enviar os dados para a IA, a planilha original (sanitizada no curso de Tratamento de Dados) passou pelos seguintes preparos no Excel:

* **Remoção de Colunas Desnecessárias:** As colunas com dados "crus" (originais com erro) foram excluídas, mantendo apenas as colunas sanitizadas.

* **Conversão de Tipos:** A coluna de "Preço" e "Ano" foram convertidas de texto para formato numérico.

* **Colar como Valores:** Todos os dados gerados por fórmulas na sanitização foram copiados e colados apenas como **valores** para evitar que a IA recebesse fórmulas quebradas (#REF!).

* **Exportação:** Os dados foram convertidos para formato estruturado (JSON/CSV) ou incorporados diretamente no prompt.

## 🤖 Uso da Inteligência Artificial (Processo e Prompts)

**Ferramenta Utilizada:** \[Escolha: ChatGPT com Canvas / Agente Customizado (GPTs)\]

### O Prompt Inicial

O primeiro comando enviado para a IA para gerar a estrutura base foi:

> *"Atue como um Desenvolvedor Front-end Especialista em Análise de Dados. Tenho uma base de dados com 100 vendas da Porsche contendo: modelo, cidade, estado, ano, preço e método de pagamento (os dados estão no final do prompt).
> Crie um arquivo HTML único contendo uma Dashboard interativa usando a biblioteca Chart.js.
> A dashboard deve ter um visual premium, usando as cores da Porsche (preto, vermelho, branco e cinza chumbo).
> Quero indicadores de topo (Receita Total e Total de Veículos Vendidos).
> Quero 3 gráficos para responder às seguintes perguntas: \[insira as perguntas aqui\].
> Inclua filtros interativos no topo (por Modelo e Estado) que atualizem os gráficos automaticamente."*

### Refinamento e Correções

Durante a geração, foram necessárias algumas iterações (ajuste conforme sua experiência):

* *Exemplo: A IA inicialmente colocou o filtro de cidades, mas alterei para estados para o gráfico não ficar poluído.*

* *Exemplo: Tive que pedir para a IA ajustar o layout dos gráficos usando CSS Grid para que ficassem alinhados lado a lado no Desktop.*

## 🛠️ Como Executar Este Projeto Localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. Abra o arquivo `index.html` em qualquer navegador web moderno.

3. Não é necessário instalar dependências, pois o arquivo utiliza bibliotecas via CDN (ex: Chart.js, TailwindCSS).

## ✒️ Autor

* **\[Nelson Kauê.\]** - *Aluno DIO*

* LinkedIn: [Seu LinkedIn](https://www.linkedin.com/in/nelson-kauê-b59290263)

* GitHub: [@seu-usuario](https://github.com/maia18)
