Beleza! Vou atualizar o README incluindo essa info sobre a API JSON e o link atualizado do projeto.

---

# Dashboard de Vendas com Streamlit

## 📌 Sobre o Projeto

Este projeto é um dashboard interativo de vendas desenvolvido com [Streamlit](https://docs.streamlit.io/). Ele consome dados em formato JSON via API pública, manipula com `pandas` e exibe gráficos interativos com `plotly`.

**Fonte dos dados:** [API JSON - Produtos](https://labdados.com/produtos)

👉 [Demo Online Atualizado](https://maykend-dash.streamlit.app/)
👉 [Repositório GitHub](https://github.com/maykends/dashboard_vendas)

---

## 📚 Bibliotecas Utilizadas

* [Streamlit](https://docs.streamlit.io/) — framework para criação de apps web interativos em Python
* [Requests](https://requests.readthedocs.io/en/latest/) — para fazer requisições HTTP e consumir a API JSON
* [Pandas](https://pandas.pydata.org/docs/) — manipulação e análise de dados
* [Plotly](https://plotly.com/python/) — criação de gráficos interativos

---

## 🚀 Como rodar o projeto localmente

### 1. Requisitos

* Python instalado (recomendado Python 3.8 ou superior) — [https://www.python.org/downloads/](https://www.python.org/downloads/)
* Editor de código (ex: [Visual Studio Code](https://code.visualstudio.com/))

### 2. Clonar o repositório

```bash
git clone https://github.com/maykends/dashboard_vendas.git
cd dashboard_vendas
```

### 3. Criar e ativar ambiente virtual (venv)

Windows PowerShell:

```powershell
python -m venv venv
.\venv\Scripts\activate
```

Você verá `(venv)` no prompt indicando que o ambiente está ativo.

### 4. Instalar dependências

```bash
pip install -r requirements.txt
```

Se não tiver o arquivo `requirements.txt`, instale manualmente:

```bash
pip install streamlit requests pandas plotly
```

### 5. Executar a aplicação

```bash
streamlit run Dashboard.py
```

---

## 📦 Requisitos do projeto

Para garantir que o ambiente esteja configurado corretamente, confira as versões das bibliotecas:

```bash
pip freeze
```

Exemplo esperado:

```
pandas==2.3.1
plotly==6.2.0
requests==2.32.4
streamlit==x.x.x
```

---

## ☁️ Deploy da aplicação

* A aplicação está hospedada no Streamlit Cloud, acesse em:
  [https://maykend-dash.streamlit.app/](https://maykend-dash.streamlit.app/)

* Para fazer o deploy:

  1. Suba seu código para um repositório GitHub público ou privado
  2. Crie uma conta no [Streamlit Cloud](https://streamlit.io/cloud) e conecte seu repositório
  3. Configure as dependências em `requirements.txt`
  4. Faça o deploy e obtenha a URL pública do app

---

## 🎯 Funcionalidades aprendidas neste projeto

* Consumir dados JSON de uma API pública usando `requests`
* Manipular dados obtidos via API com `pandas`
* Criar visualizações interativas com `plotly`
* Identificar as bibliotecas instaladas no ambiente virtual e suas versões
* Criar arquivo de requisitos (`requirements.txt`) para projetos Python
* Realizar upload do projeto no GitHub
* Fazer deploy de aplicativo web pelo Streamlit Cloud
* Configurar URL personalizada para apps Streamlit

---

## 📄 Links úteis

* Python Downloads: [https://www.python.org/downloads/](https://www.python.org/downloads/)
* Visual Studio Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
* Documentação Streamlit: [https://docs.streamlit.io/](https://docs.streamlit.io/)
* Requests: [https://requests.readthedocs.io/en/latest/](https://requests.readthedocs.io/en/latest/)
* Pandas: [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)
* Plotly: [https://plotly.com/python/](https://plotly.com/python/)

---

Se quiser, posso gerar o arquivo `requirements.txt` para você também! Quer?
