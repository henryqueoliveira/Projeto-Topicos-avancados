# Processo DevOps

## Branches

- `main`: produção/versão estável.
- `develop`: integração.
- `feature/*`: novas funcionalidades.
- `fix/*`: correções.

## Commits

- `feat:` nova funcionalidade
- `fix:` correção
- `docs:` documentação
- `test:` testes
- `refactor:` reorganização interna
- `style:` alterações visuais

## Desenvolvimento

Backlog → branch de trabalho → desenvolvimento → commit/push → develop → revisão/testes → main.

## Testes

Verificar:
- funcionamento da funcionalidade;
- navegação;
- validação de formulários;
- fluxo de inscrição;
- responsividade;
- erros;
- requisitos básicos de segurança;
- critérios de aceite.

## Entrega

`feature/* → develop → testes/revisão → main → deploy`

A publicação poderá ser automatizada com GitHub + Vercel quando houver uma versão implementada do site.

## Monitoramento

Após o deploy:
- disponibilidade;
- erros;
- falhas de deploy;
- funcionamento das páginas;
- desempenho básico;
- logs/registros da hospedagem.

Correções: `fix/* → develop → testes → main → novo deploy`.
