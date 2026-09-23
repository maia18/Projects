# 📊 Desafio DIO: Organizador de Declaração de Imposto de Renda com Excel

> Repositório desenvolvido para o desafio prático de criação de uma ferramenta no Microsoft Excel para organização e controle de dados para a Declaração de Imposto de Renda de Pessoa Física (IRPF), proposto pela [Digital Innovation One (DIO)](https://www.dio.me/?utm_source=gemini).

## 📌 Sobre o Projeto

O objetivo deste projeto é construir uma planilha estruturada e automatizada no Microsoft Excel para auxiliar no agrupamento, classificação e cálculo de dados financeiros necessários para o preenchimento da declaração anual do Imposto de Renda.

A solução visa reduzir erros, prevenir a malha fina e facilitar a consulta aos informes de rendimentos, despesas dedutíveis e evolução patrimonial.

## 🎯 Objetivos e Aprendizados

Durante o desenvolvimento deste desafio, foram aplicados os seguintes conceitos e recursos do Excel:

* **Organização e Estruturação de Dados:** Separação clara de rendimentos tributáveis, isentos e de tributação exclusiva.
* **Fórmulas e Funções Principais:**
  * `SOMASE` / `SOMASES` para totalizar despesas por categoria (Saúde, Educação, Dependentes).
  * `SE`, `E`, `OU` para verificação de limites de dedução e validações.
  * `PROCV` / `PROCX` para cruzamento de dados de fontes pagadoras e CNPJs.
* **Validação de Dados:** Criação de listas suspensas (drop-down) para categorização padronizada de lançamentos.
* **Formatação Condicional:** Alertas visuais para limite de deduções e pendências de comprovação.
* **Dashboard e Relatórios:** Gráficos e cards com resumo prévio do imposto a pagar ou restituição a receber.

## 📊 Funcionalidades da Planilha

* **[x] Controle de Rendimentos:** Aba dedicada para salários, pró-labore, aposentadorias e rendimentos de investimentos (IRRF).
* **[x] Lançamento de Despesas Dedutíveis:** Registro organizado de gastos com saúde, educação, pensão alimentícia e dependentes.
* **[x] Acompanhamento de Bens e Direitos:** Histórico e comparação de saldos de imóveis, veículos, contas bancárias e aplicações (Ano Anterior vs. Ano Atual).
* **[x] Renda Variável e Investimentos:** Apuração de lucros/prejuízos e retenções na fonte.
* **[x] Resumo IRPF (Dashboard):** Visão executiva consolidada para rápido preenchimento no programa oficial da Receita Federal.

## 📁 Estrutura do Repositório

```text
.
├── docs/                   # Documentação complementar ou capturas de tela
├── src/                    # Arquivo principal da planilha (.xlsx)
│   └── Organizador_IRPF.xlsx
├── README.md               # Descrição e guia do projeto
└── LICENSE                 # Licença do repositório
```

## 🚀 Como Utilizar

1. **Faça o Download ou Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/Desafio-DIO-Excel---Organizador-Imposto-de-Renda.git
   ```

2. **Abra o arquivo:**
   * Navegue até a pasta `src/` e abra o arquivo `Organizador_IRPF.xlsx` no Microsoft Excel.

3. **Preencha os dados:**
   * Insira seus dados de rendimentos, despesas e bens nas respetivas abas conforme seus Informes de Rendimentos e recibos.

4. **Consulte o Resumo:**
   * Utilize a aba **Resumo / Dashboard** para visualizar a prévia dos totais acumulados e facilitar a digitação no programa gerador da Receita Federal.

## 🛠️ Tecnologias e Ferramentas

* **Microsoft Excel / Office 365**
* **Git & GitHub**

## 🤝 Contribuições

Sinta-se à vontade para abrir *issues* ou enviar *pull requests* com sugestões de melhoria!

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
