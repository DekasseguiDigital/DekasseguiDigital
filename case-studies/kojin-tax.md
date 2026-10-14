# 🇯🇵 Kojin Tax — plataforma SaaS para brasileiros no Japão

## Projeto

**Kojin Tax**  
https://kojin-tax.dekasseguidigital.com/

## Objetivo

Oferecer uma plataforma digital para auxiliar brasileiros que trabalham por conta própria no Japão a organizar receitas, despesas, comprovantes e relatórios relacionados ao **Kakutei Shinkoku** (declaração de imposto).

## Solução

Uma aplicação web com acesso por conta, plano gratuito e planos pagos, reunindo:

- Organização de receitas e despesas;
- Simulador e checklist para a declaração;
- Relatórios e exportação para apoio ao Kakutei Shinkoku;
- Organização e leitura de recibos, incluindo OCR com IA conforme o plano;
- Acesso a arquivos e comprovantes.

## Modernização da plataforma — outubro de 2026

A Dekassegui Digital realizou uma migração tecnológica, saindo da infraestrutura anterior da Manus para hospedagem da aplicação na **Hostinger**.

O trabalho incluiu:

- Migração controlada da aplicação e persistência de dados;
- Preservação e verificação dos documentos existentes;
- Integração de autenticação e continuidade de acesso para usuários anteriores;
- Atualização dos fluxos de cadastro, login e logout;
- Verificação funcional de planos, comprovantes e relatórios em PDF;
- Versionamento e validação automatizada de alterações.

## Tecnologias

- **Node.js / Express** e **React**;
- **MySQL**;
- **Auth0** para autenticação;
- **Cloudflare R2** para armazenamento de documentos;
- **Stripe** para pagamentos;
- **Hostinger** para hospedagem;
- **GitHub** para colaboração, revisões e testes.

## Resultados verificados

- Aplicação acessível pelo domínio oficial;
- Fluxos de autenticação de usuário existente e novo cadastro testados;
- Interface de planos e geração/abertura de relatórios PDF testadas;
- Acesso a comprovantes históricos mantido nos testes realizados.

**Nota:** testes funcionais não equivalem a uma auditoria completa de todos os fluxos ou de toda a base de usuários.

## Evolução contínua

O roadmap contempla melhorias de experiência e comunicação com usuários dos planos gratuitos, respeitando privacidade, consentimento e uso não intrusivo. Recursos em desenvolvimento não são apresentados aqui como já lançados.

## Aprendizados para a Dekassegui Digital

Este projeto demonstrou a importância de:

- planejar migrações com inventário, backups e validação de integridade;
- preservar a identidade e os dados históricos durante trocas de autenticação;
- testar fluxos de usuários antigos **e** novos;
- realizar mudanças pequenas, revisáveis e com testes;
- proteger informações pessoais em toda comunicação com clientes.

> **Document. Automate. Evolve.**  
> Cada entrega amplia a base de conhecimento operacional da Dekassegui Digital.

---

**Conheça:** https://dekasseguidigital.com/kojin-kakutei-shinkoku/  
**Acesse:** https://kojin-tax.dekasseguidigital.com/
