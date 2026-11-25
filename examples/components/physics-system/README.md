# physics-system — Cannon driver

Demonstração do fork comunitário mantido pelo C-Frame para física em A-Frame, usando o driver Cannon.

- Pacote: `@c-frame/aframe-physics-system`
- Versão fixada: `4.2.4`
- Licença: MIT (confirmada no `package.json` e em `LICENSE` do repositório)
- A-Frame da demonstração: `1.8.0`
- Exemplo: [index.html](./index.html)

## API demonstrada

A página usa apenas a configuração básica documentada para o Cannon driver:

- `physics="driver: cannon; debug: true"` na cena.
- `static-body` numa plataforma imóvel.
- `dynamic-body` em primitivas com malha (caixa, esfera e cilindro).

A documentação do driver descreve estes componentes como os corpos estáticos e dinâmicos da simulação. O modo `debug` desenha os volumes de colisão.

## Dependências e execução

As dependências são carregadas diretamente por URLs com versões fixas:

```html
<script src="https://aframe.io/releases/1.8.0/aframe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/c-frame/aframe-physics-system@v4.2.4/dist/aframe-physics-system.min.js"></script>
```

Abre a página através do GitHub Pages ou serve a pasta do repositório por HTTP. Não é necessário compilar o projeto para esta demonstração baseada no build distribuído.

## Compatibilidade e limitações

O `package.json` da versão 4.2.4 declara o peer dependency `aframe >=0.5.0`, mas o ambiente de desenvolvimento do próprio pacote fixa A-Frame `~1.1.0`. O Component Directory comunitário indica o physics-system como mantido e compatível com A-Frame 1.8.0. Por transparência, esta página usa 1.8.0 de acordo com o diretório; o intervalo amplo do peer dependency, por si só, não prova compatibilidade funcional.

O projeto suporta drivers Cannon e Ammo, com esquemas e APIs diferentes. Este exemplo escolhe Cannon. A documentação alerta que Cannon não oferece CCD para corpos rápidos e tem limitações no filtragem de colisões. Não se deve trocar para Ammo sem rever a configuração e as propriedades específicas do driver.

## Estado de validação

**Implementado; validação manual pendente.** Foram inspecionados o README, `CannonDriver.md`, `package.json` e `LICENSE` da tag publicada. Não foi executado num browser nesta revisão. Confirmar carregamento do CDN, ausência de erros na consola, queda dos corpos e colisões com a plataforma antes de classificar como validado.

## Fontes primárias

- [Repositório C-Frame](https://github.com/c-frame/aframe-physics-system)
- [Cannon Driver — instalação e API](https://github.com/c-frame/aframe-physics-system/blob/master/CannonDriver.md)
- [npm — @c-frame/aframe-physics-system 4.2.4](https://www.npmjs.com/package/@c-frame/aframe-physics-system)
- [LICENSE](https://github.com/c-frame/aframe-physics-system/blob/master/LICENSE)
- [Component Directory comunitário](https://github.com/c-frame/aframewiki/blob/gh-pages/en/pages/component-directory.md)
