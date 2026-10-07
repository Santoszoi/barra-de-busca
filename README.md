# Search UI

Componente de busca criado para praticar UX/UI em uma interação pequena, com atenção a estados, feedback e teclado.

## Experiência

- foco visual claro;
- atalho `/` para abrir a busca;
- `Esc` para limpar e sair;
- resultados filtrados enquanto o usuário digita;
- estado vazio;
- botão de limpeza contextual;
- layout responsivo.

## Tecnologias

HTML5, CSS3 e JavaScript.

## Rodando localmente

```bash
git clone https://github.com/Santoszoi/barra-de-busca.git
cd barra-de-busca
python -m http.server 8000
```

Abra `http://localhost:8000`.

## Decisões de UX/UI

A interface mantém uma única ação principal e mostra controles secundários apenas quando são úteis. Os estados de foco, resultado e ausência de resultados dão retorno imediato sem interromper a digitação.

Este é um exercício de interface. Para aplicações completas, consulte os projetos destacados no meu perfil.
