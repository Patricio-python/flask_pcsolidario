# 💻 Flask PC Solidário

Projeto desenvolvido como estudo de **Web Design** e desenvolvimento web com **Python**, aplicando conceitos básicos do microframework **Flask** e reaproveitando a estrutura de front-end (arquivos HTML e CSS) do projeto **PC Solidário**.

---

## 🎯 Objetivo do Projeto

* Praticar a criação de rotas e renderização de templates com **Flask**.
* Estruturar uma aplicação web separando lógica de negócio (`views.py`), configuração (`app.py`), templates HTML (`templates/`) e arquivos estáticos (`static/`).
* Adaptar um layout pré-existente (HTML/CSS) para funcionar dinamicamente no ecossistema Python.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Flask**
* **HTML5**
* **CSS3**

---

## 📂 Estrutura de Pastas

```text
flask_pcsolidario/
├── static/          # Arquivos estáticos (CSS, imagens, fontes, etc.)
├── templates/       # Páginas HTML renderizadas pelo Flask (Jinja2)
├── app.py           # Arquivo principal de inicialização da aplicação
├── views.py         # Definição das rotas e lógica das páginas
└── requirements.txt # Dependências do projeto
```

---

## 🚀 Como Executar o Projeto Localmente

Siga os passos abaixo para rodar a aplicação na sua máquina:

### 1. Clone o repositório
```bash
git clone https://github.com
cd flask_pcsolidario
```

### 2. Crie e ative um ambiente virtual (opcional, mas recomendado)
* **Windows:**
  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```
* **Linux / macOS:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Execute a aplicação
```bash
python app.py
```

### 5. Acesse no navegador
Abra o seu navegador e acesse:
```text
http://127.0.0.1:5000
```
