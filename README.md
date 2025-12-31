# farmaceutica-ancoraggi-menu

Repository di lavoro per il tema Shopify:

- **Store**: `farmaceutica-internazionale-italiana.myshopify.com`
- **Tema (bozza)**: **Workflow [ANCHOR]**
- **Theme ID**: `188952641919`

## Regola fondamentale

Lavoriamo e testiamo **solo** su **Workflow [ANCHOR]** (unpublished). **Non** pubblicare/sovrascrivere mai il tema live.

## Sviluppo locale (preview sicuro)

Da questa cartella:

```bash
shopify theme dev --store farmaceutica-internazionale-italiana.myshopify.com --theme 188952641919
```

Per risincronizzare i file dal tema bozza:

```bash
shopify theme pull --store farmaceutica-internazionale-italiana.myshopify.com --theme 188952641919 --path .
```