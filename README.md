# Análise de Perfil de Clientes para Financiamento de Veículos

Este projeto foi desenvolvido para analisar o perfil de clientes que solicitam crédito ao banco para o financiamento de veículos. Com base nos dados históricos e nos atributos fornecidos no cadastro, um modelo de classificação foi criado para avaliar se o cliente é considerado "bom" ou "ruim" para concessão de crédito e determinar a probabilidade de pagamento do valor solicitado.

## Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Técnica de Machine Learning**: Classificação
- **Banco de Dados**: PostgreSQL
- **Deploy**: Streamlit

## Funcionalidades

- Classificação dos clientes com base nos atributos fornecidos.
- Cálculo da probabilidade de pagamento do crédito solicitado.
- Interface interativa para entrada de dados e visualização dos resultados usando Streamlit.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- **Python** (versão 3.8 ou superior)
- **PostgreSQL**
- **pip** (para gerenciar pacotes Python)

## Como clonar o repositório

Para clonar o repositório e rodar o projeto em sua máquina local, siga os passos abaixo:

1. Abra o terminal e execute o seguinte comando para clonar o repositório:

```bash
git clone https://github.com/al00pes/novadrivebank
```

2. Acesse o diretório do projeto:

```bash
cd SEU_REPOSITORIO
```

3. Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
```

4. Ative o ambiente virtual:

   - No Windows:
   
   ```bash
   venv\Scripts\activate
   ```

   - No Linux/macOS:
   
   ```bash
   source venv/bin/activate
   ```

5. Instale as dependências necessárias:

```bash
pip install -r requirements.txt
```

6. Configure o banco de dados PostgreSQL de acordo com as informações fornecidas no arquivo `.env` ou nas configurações do projeto.

7. Execute o projeto:

```bash
streamlit run app.py
```

## Estrutura do Projeto

```bash
├── data                # Scripts e conexões com o banco de dados
├── models              # Modelos de machine learning
├── app.py              # Arquivo principal da aplicação Streamlit
├── requirements.txt    # Arquivo com dependências do projeto
└── README.md           # Este arquivo
```

## Contato

Em caso de dúvidas ou sugestões, entre em contato via arthurlopes.ti@gmail.com
