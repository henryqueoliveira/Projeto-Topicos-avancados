# Site de Gerenciamento de Eventos Universitários

Projeto Integrador — Tópicos Avançados em Sistemas de Informação II

## Atividade 04 — Introdução ao DevOps

### 1. Objetivo

Nosso projeto tem como objetivo desenvolver um **site responsivo para gerenciamento de eventos universitários**. A proposta é centralizar em um único ambiente a divulgação e consulta de eventos, autenticação dos usuários, inscrições, acompanhamento da participação e, futuramente, controle de presença e emissão de certificados.

Para transformar a ideia em um produto digital entregue continuamente, a equipe utilizará práticas de DevOps, integrando versionamento, desenvolvimento incremental, testes, entrega e monitoramento.

### 2. Repositório Git

O código-fonte e a documentação serão versionados com Git e armazenados no GitHub. O repositório permitirá colaboração entre os integrantes, histórico das alterações e controle das versões.

Estrutura inicial:

```text
site-eventos-universitarios/
├── README.md
├── .gitignore
├── docs/
│   ├── requisitos.md
│   ├── backlog.md
│   ├── processo-devops.md
│   └── equipe.md
├── src/
├── public/
└── tests/
```

### 3. Organização das branches

```text
main
└── develop
    ├── feature/home
    ├── feature/login
    ├── feature/eventos
    ├── feature/inscricao
    └── fix/nome-da-correcao
```

- `main`: versão estável e pronta para entrega.
- `develop`: integração das funcionalidades em desenvolvimento.
- `feature/*`: desenvolvimento de uma funcionalidade específica.
- `fix/*`: correções de erros.

Fluxo: **feature/* → develop → testes/revisão → main → deploy**

### 4. Estratégia de commits

Usaremos mensagens curtas e padronizadas:

```text
feat: adiciona listagem de eventos
fix: corrige validacao do login
docs: atualiza documentacao do projeto
test: adiciona teste do fluxo de inscricao
refactor: reorganiza estrutura dos componentes
style: ajusta responsividade da pagina inicial
```

### 5. Backlog inicial

O backlog completo está em `docs/backlog.md`. A prioridade inicial é o fluxo:

**Tela Inicial → Login → Eventos → Detalhes do Evento → Inscrição → Confirmação**

### 6. Processo de desenvolvimento

1. Seleção de uma tarefa do backlog.
2. Criação da branch `feature/*`.
3. Desenvolvimento.
4. Commit e push.
5. Integração na `develop`.
6. Revisão e testes.
7. Integração na `main`.
8. Deploy.

### 7. Processo de testes

Antes de uma funcionalidade chegar à `main`, serão verificados funcionamento, navegação, formulários, fluxo de inscrição, responsividade, erros, requisitos básicos de segurança e critérios de aceite.

### 8. Processo de entrega

**Código desenvolvido → develop → testes/revisão → main → deploy → site disponível**

Quando o site estiver implementado, a publicação poderá ser automatizada pela integração do repositório com a Vercel.

### 9. Processo de monitoramento

Após a publicação, a equipe acompanhará disponibilidade do site, erros de execução, falhas de deploy, funcionamento das páginas, desempenho básico e registros da hospedagem. Correções seguirão o fluxo `fix/* → develop → testes → main → deploy`.

### 10. Ciclo DevOps

**Planejar → Desenvolver → Versionar → Testar → Entregar → Monitorar → Melhorar ↺**

### 11. Equipe

- Pedro Almeida Bonilha — Product Owner
- Henryque Marques de Oliveira — Scrum Master
- Leonardo Marques Silva — Arquiteto de Software
- Samir Santos de Melo — Dev/DevOps
- Vinícius Borges — Security Officer
- Davi Oliveira — Analista de Qualidade e Sustentabilidade
- Cristiano — Analista de Negócios

## Entrega

Após subir estes arquivos no GitHub, compartilhar o repositório com a professora conforme solicitado no enunciado da atividade e entregar o link do repositório.
