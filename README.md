# 📚 Milo Docs

Bem-vindo ao repositório oficial da documentação da plataforma **Milo Invest**.

## 🎯 Sobre Este Repositório

Este repositório contém todos os arquivos fonte utilizados para gerar o nosso site. A documentação é construída utilizando [MkDocs](https://www.mkdocs.org/) com o tema [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), o que nos permite escrever em Markdown simples e gerar um site estático moderno e responsivo.

## 🚀 Rodando o Projeto Localmente

Para visualizar o site de documentação em sua máquina local, fazer alterações ou testar contribuições, siga os passos abaixo.

### Pré-requisitos

* **Python 3.x** instalado.
* **Pip** (gerenciador de pacotes do Python).

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/MiloInvest/milo-docs.git
    cd milo-docs
    ```

2.  **Instale as dependências:**
    Recomendamos o uso de um ambiente virtual (`venv`) para isolar as dependências do projeto.

    ```bash
    # Crie um ambiente virtual (opcional, mas recomendado)
    python -m venv venv

    # Ative o ambiente virtual
    # No Windows:
    .\venv\Scripts\activate
    # No macOS/Linux:
    source venv/bin/activate

    # Instale as dependências do MkDocs e do tema
    pip install -r requirements.txt
    ```
    *(Nota: Se o arquivo `requirements.txt` não existir, você pode instalar manualmente com `pip install mkdocs mkdocs-material`)*

### Executando o Servidor de Desenvolvimento

Com as dependências instaladas, inicie o servidor local do MkDocs:

```bash
mkdocs serve
```

Isso iniciará um servidor de desenvolvimento com live-reloading. Você poderá acessar o site de documentação no seu navegador através do endereço:

```bash
http://127.0.0.1:8000
```

Qualquer alteração que você salvar nos arquivos .md será refletida automaticamente no site.
