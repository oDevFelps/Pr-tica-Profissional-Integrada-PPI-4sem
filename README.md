# Pr-tica-Profissional-Integrada-PPI-4sem# Build Log Automotivo (TCC) 🚗💨

![Status do Projeto: Em Desenvolvimento](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

Projeto de TCC (Trabalho de Conclusão de Curso) em Sistemas para Internet.

O **Build Log Automotivo** é uma plataforma web desenhada para entusiastas de carros que modificam seus veículos. O objetivo é resolver a dor comum de perder o controle sobre o histórico de modificações, manutenções e, principalmente, os custos envolvidos em um "carro projeto".

A plataforma permite que o usuário crie um diário de bordo detalhado para cada veículo, transformando um amontoado de notas fiscais e memórias em um histórico organizado e financeiramente rastreável.

## 🎯 Status Atual: MVP (Produto Mínimo Viável)

O foco inicial é construir o núcleo funcional do sistema, que inclui:

* [ ] Autenticação de Usuários (Cadastro e Login).
* [ ] Módulo "Garagem" (Cadastro de um ou mais veículos/projetos).
* [ ] Módulo "Diário" (Adicionar lançamentos de modificação ou manutenção).
* [ ] Dashboard Simples (Visualizar o histórico e o custo total investido por projeto).

## 🚀 Roadmap (Funcionalidades Futuras)

Após a entrega do MVP, o projeto poderá evoluir para incluir:

* [ ] Upload de fotos e notas fiscais por lançamento.
* [ ] Gráficos de custos por categoria (Estética, Performance, Manutenção).
* [ ] Exportação do histórico completo em PDF (útil para revenda).
* [ ] Módulo avançado: Assistente de compatibilidade de Som Automotivo (baseado na Ideia 5).

## 🛠️ Tecnologias Utilizadas (Stack)

* **Back-end:** PHP
* **Front-end:** HTML, CSS, JavaScript
* **Banco de Dados:** MySQL

## 🏁 Como Rodar o Projeto Localmente

Este projeto utiliza um stack LAMP/XAMPP/WAMP.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/](https://github.com/)[SEU-USUARIO]/[NOME-DO-REPOSITORIO].git
    ```

2.  **Mova para seu servidor local:**
    * Mova a pasta do projeto para o diretório `htdocs` (XAMPP) ou `www` (WAMP).

3.  **Crie o Banco de Dados:**
    * Acesse seu `phpMyAdmin` (ou cliente MySQL de preferência).
    * Crie um novo banco de dados (ex: `build_log_db`).
    * Importe o arquivo `database.sql` (que estará na raiz do projeto) para criar as tabelas.

4.  **Configure a Conexão:**
    * Encontre o arquivo de configuração de conexão (ex: `config.php` ou `db.php`).
    * Altere as variáveis de `HOST`, `DB_NAME`, `USER` e `PASSWORD` para que correspondam às suas credenciais do MySQL.

5.  **Acesse:**
    * Abra seu navegador e acesse: `http://localhost/[NOME-DA-PASTA-DO-PROJETO]`

## 👨‍💻 Autor

* **[Felipe de Arruda]** - [lipeaq05@gmail.com]

---
