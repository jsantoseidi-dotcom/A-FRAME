# ocean

Demonstração isolada do componente e primitivo `ocean` / `<a-ocean>` incluído em A-Frame Extras.

- Projeto: [c-frame/aframe-extras](https://github.com/c-frame/aframe-extras)
- Pacote npm: `aframe-extras`
- Versão fixada: `7.7.0`
- Licença declarada no `package.json`: MIT
- A-Frame usado nesta página: `1.7.1`
- Exemplo: [index.html](./index.html)

## Origem e compatibilidade

O inventário histórico regista `aframe-extras.ocean` como origem do identificador `ocean`. O projeto atual mantém o primitivo em `src/primitives/a-ocean.js`, incluído no grupo `primitives`.

Há uma diferença entre as referências de compatibilidade que deve ficar explícita:

- O README do A-Frame Extras 7.7.0 declara a série **A-Frame 1.7.x** compatível com a série **Extras 7.x.x**.
- O Component Directory comunitário lista `ocean` como mantido e confirmado com A-Frame **1.8.0**.

Para esta demonstração, a dependência base foi fixada em **A-Frame 1.7.1**, dentro da compatibilidade declarada pelo README do pacote. A indicação 1.8.0 do diretório comunitário fica registada como confirmação adicional, mas não substitui a tabela de compatibilidade publicada pelo projeto.

## API usada

O código-fonte regista:

- o componente `ocean`, com os campos `width`, `depth`, `density`, `amplitude`, `amplitudeVariance`, `speed`, `speedVariance`, `color` e `opacity`;
- o primitivo `a-ocean`, com mapeamentos para as propriedades do componente.

A página usa apenas os atributos também ilustrados no README de primitivas: `width`, `depth`, `density`, `speed` e `color`. Os valores predefinidos do esquema no código-fonte são: largura 10, profundidade 10, densidade 10, amplitude 0.1, variação de amplitude 0.3, velocidade 1, variação de velocidade 2, cor `#7AD2F7` e opacidade 0.8.

## Execução

Abra a página através do GitHub Pages ou sirva a raiz do repositório com um servidor HTTP local. Não é necessário compilar o projeto: a página carrega as distribuições fixadas por CDN.

Scripts utilizados:

```html
<script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/c-frame/aframe-extras@7.7.0/dist/aframe-extras.min.js"></script>
```

A ordem é intencional: A-Frame é carregado antes do bundle Extras, que usa a instância global `THREE` fornecida pelo A-Frame.

## Estado de validação

**Implementado; validação manual pendente.** Foram inspecionados o README, `package.json`, `src/primitives/a-ocean.js`, `src/primitives/index.js` e `webpack.config.js` na origem do projeto. A configuração de build confirma a geração do bundle `aframe-extras.min.js`. Não foi executado um browser nesta revisão; ainda falta confirmar o carregamento efetivo dos CDNs, a criação do mar e a animação das ondas.

## Fontes primárias

- [A-Frame Extras — README](https://github.com/c-frame/aframe-extras/blob/676f3628bb477d646293f9743eda31aca556114a/README.md)
- [Código-fonte do primitivo e componente ocean](https://github.com/c-frame/aframe-extras/blob/676f3628bb477d646293f9743eda31aca556114a/src/primitives/a-ocean.js)
- [README dos primitivos](https://github.com/c-frame/aframe-extras/blob/676f3628bb477d646293f9743eda31aca556114a/src/primitives/README.md)
- [package.json — versão e licença](https://github.com/c-frame/aframe-extras/blob/676f3628bb477d646293f9743eda31aca556114a/package.json)
- [Component Directory comunitário — entrada ocean](https://github.com/c-frame/aframewiki/blob/gh-pages/en/pages/component-directory.md)
- [npm — aframe-extras](https://www.npmjs.com/package/aframe-extras)
