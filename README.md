# woof-page

Landing page da Woof Pet Marketing. HTML e CSS puros, sem build: `index.html` + `assets/`.

## Ver localmente

```bash
python3 -m http.server 8080   # abre em http://localhost:8080
```

## Publicar

`Dockerfile` serve o site com nginx na porta 80 — no Coolify, crie um recurso a partir deste repositório com build pack **Dockerfile**.

## O que manter em dia

- **Planos** (`#planos` no `index.html`): os valores repetem os de `app.woof.ia.br/planos`, que são dados da Casa e ainda provisórios. Quando a Casa mudar um plano, mude aqui também.
- **Links do app**: os botões levam para `https://app.woof.ia.br/cadastro` (com `?plano=loja` ou `?plano=agencia`) e `/login`.
- **Logo** (`assets/marca/`): o PNG é usado como máscara CSS — a cor vem de `color`. Não edite o arquivo para mudar a cor. Quando houver o SVG do designer, troque os PNGs.
- O design de origem está no canvas de design da Woof (Claude).
