# 📚 Sistema Inteligente de Gerenciamento de Biblioteca Escolar — *Projeto Athena*
![Logo do Projeto Athena](<img width="630" height="630" alt="image" src="https://github.com/user-attachments/assets/6b7d0978-d19f-44c6-8d9b-b34fb8999752" />)

Bem-vindo(a) ao **Projeto Athena**, um sistema criado para revolucionar a forma como escolas organizam, emprestam e acompanham seus acervos literários.  
Este sistema combina tecnologia, praticidade e um toque de inteligência artificial para transformar o ato de emprestar livros em uma experiência moderna e eficiente.  

> “Um bom sistema de biblioteca é aquele que guarda histórias, mas também cria novas.”  

---

## 🗂️ Índice
- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Usar](#como-usar)
- [Exemplo de Uso](#exemplo-de-uso)
- [Próximas Atualizações](#próximas-atualizações)
- [Contribuidores](#contribuidores)
- [Contato](#contato)

---

## 🧠 Visão Geral

O **Athena** foi projetado para atender escolas de pequeno e médio porte que desejam digitalizar sua biblioteca sem depender de softwares pagos ou complexos.  
Ele oferece:
- Controle total sobre empréstimos e devoluções 📘  
- Cadastro automático de obras via leitura de código de barras 📷  
- Sugestões de leitura baseadas nos livros mais retirados 🔍  
- Estatísticas mensais de movimentação e interesse dos alunos 📊  

### Objetivos Específicos
#### Nível 1 — Modernização
Implementar uma interface acessível e intuitiva para alunos e funcionários.  
#### Nível 2 — Sustentabilidade
Reduzir o uso de papel através da digitalização dos registros.  
#### Nível 3 — Engajamento
Incentivar o hábito da leitura com recomendações e gamificação.  
#### Nível 4 — Expansão
Permitir integração com plataformas externas e bibliotecas comunitárias.  

---

## ⚙️ Funcionalidades

- Cadastro de **livros**, **usuários** e **funcionários**
- Sistema de **empréstimo** e **devolução automática**
- Geração de **relatórios inteligentes**
- **Busca avançada** por título, autor, gênero ou data
- Controle de **multa por atraso**
- Sistema de **notificações por e-mail**
- Painel administrativo com **autenticação segura**
- Ranking dos livros mais lidos da escola ⭐
- Integração com Google Books API para sinopse e capa dos livros

---

## 💻 Tecnologias Utilizadas

| Categoria | Tecnologia |
|------------|-------------|
| **Linguagem de Programação** | Python |
| **Banco de Dados** | PostgreSQL |
| **Framework** | Django REST + React |
| **Sistema Operacional** | Windows / Linux / macOS |
| **API de Integração** | Google Books API |

---

## 🚀 Como Usar

1. **Clone o repositório** em sua máquina:  
   ```bash
   git clone https://github.com/exemplo/athena-biblioteca.git
Acesse o diretório do projeto:

1. bash

2. Copiar código

3. cd athena-biblioteca

Instale as dependências:

1. bash

2. Copiar código

3. pip install -r requirements.txt

4. Configure o banco de dados no arquivo .env.

Execute o servidor local:

1. bash

2. Copiar código

3. python manage.py runserver

Acesse o sistema no navegador:
👉 http://localhost:8000

🖼️ Exemplo de Uso:

python

Copiar código
# Exemplo simples de registro de livro
from athena import Biblioteca

biblioteca = Biblioteca()
biblioteca.cadastrar_livro(
    titulo="O Pequeno Príncipe",
    autor="Antoine de Saint-Exupéry",
    genero="Ficção filosófica"
)
biblioteca.listar_livros()
"O objetivo do Athena é unir tecnologia e literatura, tornando o conhecimento mais acessível e sustentável para todos."

Nota: Algumas funções ainda estão em versão beta, e poderão ser instáveis em determinados sistemas operacionais.

✅ Próximas Atualizações

-  Implementar autenticação por token

- Adicionar sistema de recomendações

-  Criar aplicativo mobile 📱

-  Suporte multilíngue 🌍

-  Integração com sistemas de bibliotecas públicas

-  Estatísticas com gráficos dinâmicos 📊

🔗 Repositórios Relacionados
- Athena API
- Athena Frontend
- Athena Docs

👥 Contribuidores
- Agradecimento especial aos colaboradores deste projeto:

🧑‍💻 @usuario1 — Desenvolvimento Backend
👩‍🎨 @usuario2 — Design de Interface
🧠 @layzacunha — Documentação e Coordenação Geral

📞 Contato:

Quer contribuir ou tirar dúvidas?

Entre em contato com a equipe de desenvolvimento do Projeto Athena:

📧 E-mail: contato.athena@senai.com.br

💬 Discord: Athena Community Server

🌐 Site: athena-biblioteca.dev

📱 Instagram: @athenaprojeto

# Documento criado por *Layza Cunha* para a atividade prática de Markdown — Sistema de Gerenciamento de Biblioteca Escolar.
