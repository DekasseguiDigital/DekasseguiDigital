# 🔌 WordPress Plugin Structure

Este exemplo representa a estrutura padrão utilizada pela Dekassegui Digital para o desenvolvimento de plugins WordPress.

## Estrutura

```text
plugin-name/
│
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
│
├── includes/
│   ├── admin/
│   ├── frontend/
│   ├── api/
│   └── helpers/
│
├── languages/
│
├── templates/
│
├── uninstall.php
├── plugin-name.php
├── readme.txt
└── LICENSE
```

---

## Boas práticas

- Separar Admin e Frontend.
- Evitar funções globais.
- Utilizar namespaces quando possível.
- Internacionalizar todas as strings.
- Sanitizar toda entrada de dados.
- Escapar toda saída.
- Seguir os Coding Standards do WordPress.

---

## Utilizado em

- DD Smart WhatsApp
- Dekassegui LMS
- Projetos internos da Dekassegui Digital

---

> Este é um exemplo utilizado como referência para novos projetos.
