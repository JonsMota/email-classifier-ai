# Email Classifier AI

## Descrição

Esta aplicação web utiliza inteligência artificial para classificar emails em categorias predefinidas (Produtivo e Improdutivo) e sugerir respostas automáticas baseadas na classificação realizada. O objetivo é automatizar a leitura e classificação de emails, liberando tempo da equipe para outras tarefas.

## Estrutura do Projeto

AUTOU-DESAFIO/
├── static/
│   └── style.css
├── backend/
│   └── classifier.py
│   └── app.py
├── frontend/
│   └── index.html
│   └── result.html
├── requirements.txt
├── README.md


## Pré-requisitos

- Python 3.7 ou superior
- Conta no OpenAI com chave de API
- Conta no GitHub
- Conta na Vercel (opcional, para hospedagem)

## Configuração do Ambiente

1.Clone o Repositório:

   ```sh
   git clone https://github.com/JonsMota/email-classifier-ai
   cd email-classifier-ai

2.Crie um Ambiente Virtual:

python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`

3.Instale as Dependências:

pip install -r requirements.txt

4. Configure a Chave da API do OpenAI:
Acesse OpenAI e crie uma conta.
Após criar a conta, vá para a seção de API Keys e gere uma nova chave de API.
> Crie um arquivo .env na raiz do projeto e adicione sua chave de API do OpenAI: 
`env API_KEY=your_openai_api_key


5. **Baixe os Recursos do NLTK:**

No terminal Python, execute:

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')

Executando a Aplicação Localmente
Inicie o Servidor Flask:

Acesse a Aplicação:

Abra o navegador e vá para http://127.0.0.1:5000.

Hospedagem na Vercel
Crie um Repositório no GitHub:

Acesse github.com e crie um novo repositório.
Clone o repositório e copie os arquivos do projeto para o diretório clonado.
Adicione, faça commit e envie os arquivos para o GitHub.
Hospede na Vercel:

Acesse vercel.com e faça login.
Clique em "New Project" e selecione "Import Git Repository".
Conecte sua conta do GitHub e selecione o repositório email-classifier-ai.
Clique em "Import" e siga as instruções para configurar o projeto.
Adicione a variável de ambiente API_KEY com a chave da API do OpenAI no painel de configurações do projeto na Vercel.
Clique em "Deploy".

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Desenvolvido por Jonas com 💻 e ☕.


### Conclusão

O arquivo `README.md` deve ser colocado na pasta raiz do seu projeto (`AUTOU-DESAFIO/`). Ele fornece instruções claras sobre como configurar e executar a aplicação localmente, além de informações sobre a estrutura do projeto, pré-requisitos, e como hospedar a aplicação na Vercel.
### Conclusão

O arquivo `README.md` deve ser colocado na pasta raiz do seu projeto (`AUTOU-DESAFIO/`). Ele fornece instruções claras sobre como configurar e executar a aplicação localmente, além de informações sobre a estrutura do projeto, pré-requisitos, e como hospedar a aplicação na Vercel.