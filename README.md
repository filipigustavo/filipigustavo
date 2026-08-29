# Filipi Gustavo

Site portfolio profissional em estilo jornal — Technical Product Manager.

**Site publicado:** [https://filipigustavo.github.io/](https://filipigustavo.github.io/)

## Sobre

Página única (`index.html`) com design inspirado em jornal vintage halftone, apresentando trajetória profissional, competências e formação acadêmica.

## Publicação

O site é publicado automaticamente no **GitHub Pages** via GitHub Actions sempre que há push na branch `main`.

### Pré-requisito (configuração única)

1. Acesse **Settings → Pages** no repositório
2. Em **Source**, selecione **GitHub Actions**

Após isso, cada merge na `main` dispara o workflow [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml) e publica o site.

## Desenvolvimento local

```bash
# Servir localmente (Python)
python3 -m http.server 8080

# Abrir http://localhost:8080
```

## Estrutura

```
/
├── index.html              # Página principal (HTML + CSS + JS)
├── assets/
│   └── hero-halftone.jpg   # Imagem de fundo do hero
└── .github/workflows/
    └── deploy-pages.yml    # Deploy automático
```

## Contato

- **LinkedIn:** [linkedin.com/in/filipigustavo](https://linkedin.com/in/filipigustavo)
- **E-mail:** email@filipigustavo.com.br
