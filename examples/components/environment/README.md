# environment

Componente comunitário que gera um ambiente procedural completo para uma cena A-Frame.

- Pacote: `aframe-environment-component`
- Versão fixada: `1.5.0`
- Licença: MIT
- A-Frame usado no exemplo: `1.8.0`
- Demonstração: [abrir index.html](./index.html)

## API usada

A demonstração usa propriedades documentadas pelo projeto:

- `preset: forest` — seleciona o preset de floresta.
- `dressing: trees` e `dressingAmount: 35` — adiciona árvores decorativas.
- `ground: hills` e `groundColor` — define terreno e cor.
- `skyType: atmosphere` e `fog` — configura céu atmosférico e nevoeiro.

O projeto lista os presets e os parâmetros suportados no README de origem.

## Dependências

```html
<script src="https://aframe.io/releases/1.8.0/aframe.min.js"></script>
<script src="https://unpkg.com/aframe-environment-component@1.5.0/dist/aframe-environment-component.min.js"></script>
```

A versão 1.5.0 está publicada no npm sob licença MIT. O README do projeto indica A-Frame 1.7.0 ou posterior, pelo que 1.8.0 está dentro da compatibilidade declarada.

## Estado de validação

**Implementado; validação manual pendente.** A API e a compatibilidade declarada foram verificadas nas fontes do projeto e na documentação A-Frame 1.8.0. Ainda é necessário abrir a página num browser, confirmar o carregamento do script e verificar a geração do ambiente e o desempenho.

## Referências primárias

- [Repositório e README do projeto](https://github.com/supermedium/aframe-environment-component)
- [Pacote npm — versão 1.5.0](https://www.npmjs.com/package/aframe-environment-component)
- [A-Frame 1.8.0 — Adding an Environment](https://aframe.io/docs/1.8.0/guides/building-a-basic-scene.html)
