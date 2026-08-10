# 🚗 Dekassegui Auto

## Projeto

Dekassegui Auto

**Proprietário:** Dekassegui Digital

Site:
https://autofacil.sitemodelo.store/

---

# Tipo de projeto

Projeto interno / demonstrativo da Dekassegui Digital.

O Dekassegui Auto é um ambiente próprio utilizado para validar uma experiência digital baseada em catálogo automotivo e conteúdo estruturado.

O domínio atual é infraestrutura do projeto, não a identidade permanente do ativo.

---

# Objetivo

Documentar um projeto interno em que registros de veículos são tratados como conteúdo estruturado, permitindo apresentação consistente e reutilizável em listagens e páginas individuais.

O objetivo deste estudo de caso é registrar a arquitetura realmente comprovada sem transformar o projeto em marketplace, CRM, SaaS, sistema completo de estoque ou plataforma automotiva avançada.

---

# Estado atual

O site público apresenta a identidade Dekassegui Auto e comunica uma experiência voltada à listagem de carros, páginas individuais de veículos, contato e financiamento.

Foram identificadas páginas públicas como:

- Home
- Carros
- Sobre Nós
- Contato
- Financiamento

A listagem pública apresenta múltiplos veículos com imagem, título, detalhes automotivos visíveis e link para páginas individuais em `/carro/...`.

---

# Tecnologias confirmadas

Com base em evidências públicas e contexto administrativo validado pelo responsável, foram identificadas as seguintes tecnologias:

- WordPress
- Elementor
- Elementor Pro
- LiteSpeed Cache
- GTranslate
- Click to Chat / WhatsApp
- Advanced Custom Fields (ACF)

O ACF é registrado aqui como tecnologia confirmada com base em evidência administrativa fornecida pelo responsável do projeto.

---

# Conteúdo estruturado

A REST pública do WordPress confirma a existência do post type público `carro`:

- Post type: `carro`
- Nome: Carros
- REST base: `carro`
- Endpoint: `/wp-json/wp/v2/carro`
- Registros individuais: `/carro/...`

Foram identificados múltiplos registros públicos de veículos no endpoint `carro`, incluindo páginas individuais para itens do catálogo.

Também foram confirmadas taxonomias associadas ao post type `carro`:

- `ano`
- `cor`
- `marca`
- `modelo`

Este estudo de caso registra a existência dessas taxonomias sem inferir relações específicas entre termos quando essa associação não estiver inequivocamente comprovada.

---

# Arquitetura confirmada

Há evidência pública de apresentação reutilizável baseada em conteúdo estruturado.

A relação observada é:

registros `carro`
→ apresentados em múltiplos itens
→ dentro de estrutura Elementor Loop
→ com links individuais `/carro/...`

Foram identificados no HTML público elementos e widgets compatíveis com Loop do Elementor, incluindo:

- `elementor-widget-loop-grid`
- `elementor-loop-container`
- `data-elementor-type="loop-item"`
- `e-loop-item`
- `widget-theme-post-title`
- `widget-theme-post-featured-image`

Também foi observado uso consistente de título e imagem destacada nos itens do catálogo.

Essa evidência sustenta a descrição do projeto como apresentação reutilizável baseada em conteúdo estruturado.

---

# ACF e limitações da evidência pública

Foi observado no ambiente administrativo um grupo ACF denominado "Detalhes do carro", associado a Carros, contendo 23 campos.

Essa evidência administrativa confirma a existência do grupo e sua associação ao contexto de Carros.

A REST pública possui a propriedade `acf`, porém retorna:

```json
"acf":[]
```

Portanto, não é possível confirmar publicamente os nomes ou valores dos 23 campos ACF.

Este estudo de caso não afirma que todos os 23 campos estão ativos, que todos são utilizados, que todos alimentam o frontend ou que os campos visíveis publicamente correspondem diretamente aos campos ACF.

---

# Escopo documentado

- Projeto interno / demonstrativo
- Site público da Dekassegui Auto
- Catálogo/listagem de veículos
- Páginas individuais em `/carro/...`
- Post type público `carro`
- Endpoint REST `/wp-json/wp/v2/carro`
- Taxonomias `ano`, `cor`, `marca` e `modelo`
- Campos automotivos visíveis no frontend, como Shaken, imposto, ano, transmissão e valor
- Apresentação reutilizável com Elementor Loop
- ACF confirmado por evidência administrativa

---

# Visão de evolução

O projeto funciona como laboratório interno para compreender soluções mais escaláveis em projetos com múltiplos registros semelhantes.

A principal visão de evolução é amadurecer o uso de conteúdo estruturado, campos personalizados e templates reutilizáveis para reduzir retrabalho e manter apresentações consistentes.

Essa visão não deve ser tratada como produto comercial, white label, marketplace, CRM ou plataforma automotiva pronta.

---

# Limites documentados

Este estudo de caso não afirma que o Dekassegui Auto possui:

- marketplace automotivo;
- CRM;
- SaaS;
- sistema completo de estoque;
- white label pronto;
- arquitetura headless;
- integração automotiva externa;
- gestão avançada de concessionária;
- pagamentos;
- financiamento real integrado;
- código PHP próprio confirmado;
- plugin próprio confirmado;
- REST API customizada confirmada.

Também não afirma que todos os dados visíveis no frontend vêm do ACF.

Não foi possível confirmar publicamente o nome de templates internos do Elementor, configuração do Theme Builder, Single Template específico, Archive Template específico ou estrutura administrativa da Elementor Library.

---

# Desafios

O principal desafio é documentar a competência arquitetural real do projeto sem exagerar sua maturidade.

O projeto mostra um caminho importante: conteúdo repetitivo pode ser tratado como dado estruturado e apresentado de forma consistente, mas a documentação precisa separar o que é público, o que foi confirmado administrativamente e o que ainda não foi comprovado.

---

# Resultado

O projeto passa a ser registrado como ambiente interno / demonstrativo da Dekassegui Digital com foco em catálogo automotivo estruturado.

O diferencial documentado é a combinação de post type específico, taxonomias, campos personalizados confirmados administrativamente e apresentação reutilizável via Elementor Loop.

---

# Aprendizados

Este projeto reforça princípios importantes da Dekassegui Digital:

- Domínio é infraestrutura, não identidade do projeto.
- Conteúdo repetitivo pode se beneficiar de estrutura própria.
- Post types, taxonomias e campos personalizados ajudam a reduzir retrabalho.
- Templates reutilizáveis tornam a apresentação mais consistente.
- Evidência administrativa e evidência pública devem ser diferenciadas.
- Arquitetura real deve ser documentada sem inflar maturidade.

---

## Status

🟡 Projeto interno / demonstrativo em evolução

Última atualização:
Agosto de 2026
