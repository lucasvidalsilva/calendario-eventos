# Calendário de Eventos

Página web estática para apresentar eventos da IEADPIB em visualização mensal ou em lista, com detalhes em modal.

**Estado:** protótipo de arquivo único. A interface e os eventos ficam em `index.html`; não há backend, painel de edição, persistência, testes ou processo de build.

## Executar

Abra `index.html` no navegador ou sirva a pasta localmente:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Implementado

- navegação mensal;
- marcação de dias com eventos;
- lista completa;
- modal de detalhes;
- layout responsivo com dependências carregadas por CDN.

## Limitações

- conteúdo é editado diretamente no JavaScript do HTML;
- não há calendário externo, banco ou API;
- disponibilidade depende dos CDNs usados;
- não há acessibilidade, links ou datas validados automaticamente;
- o projeto não se relaciona diretamente ao foco principal de Engenharia de Dados do portfólio.

Recomendação de portfólio: manter como projeto periférico e não destacar até existir uma necessidade de produto e um fluxo de manutenção do conteúdo.
