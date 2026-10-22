# Ponto do Café

Site institucional e loja virtual da cafeteria **Ponto do Café**, localizada em Toledo, Paraná.

## Sobre a cafeteria

O Ponto do Café oferece cafés especiais preparados com grãos selecionados, bebidas especiais, doces artesanais, salgados, lanches e combos. A proposta é criar um ambiente acolhedor para pausas rápidas, encontros, estudos, trabalho e momentos de descontração.

## Site

- Página inicial: http://localhost:8080
- Painel administrativo: http://localhost:8080/wp-admin

## Executar localmente

Requisitos: Docker e Docker Compose.

```bash
cp .env.example .env
# Edite .env e defina senhas fortes
docker compose up -d
```

Depois, acesse `http://localhost:8080`.

Para parar os serviços:

```bash
docker compose down
```

Os dados do WordPress e do MariaDB ficam em volumes Docker locais e não são versionados neste repositório.

## Serviços

- WordPress
- MariaDB
- WooCommerce
- Elementor
- WPForms

## Informações da cafeteria

- Cidade: Toledo, PR
- Produtos: cafés, doces, sobremesas, salgados, lanches e combos
- Atendimento: consulte os canais oficiais da cafeteria para horários, localização e contato

