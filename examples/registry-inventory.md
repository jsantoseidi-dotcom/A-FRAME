# Inventário do A-Frame Registry (arquivo histórico)

> **Estado da fonte:** o projeto `aframevr/aframe-registry` está assinalado como descontinuado. Este inventário regista os identificadores publicados no seu `registry.yml`; não é uma recomendação de instalação nem uma garantia de compatibilidade com A-Frame 1.8.0.

Fonte: [aframevr/aframe-registry — registry.yml](https://github.com/aframevr/aframe-registry/blob/master/registry.yml). O Registry organiza entradas por pacote npm e versões-alvo do A-Frame. Os nomes abaixo são os identificadores usados nos atributos HTML.

## Componentes

| Pacote npm / entrada | Identificadores registados | Versões A-Frame indicadas no Registry |
|---|---|---|
| `aframe-alongpath-component` | `alongpath` | 0.3, 0.5 |
| `aframe-animation-component` | `animation` | 0.3, 0.5 |
| `aframe-audioanalyser-component` | `audio-analyser` | 0.4, 0.5 |
| `aframe-auto-detect-controllers-component` | `auto-detect-controllers` | 0.4 |
| `aframe-crawling-cursor` | `crawling-cursor` | 0.3, 0.4 |
| `aframe-controller-cursor-component` | `controller-cursor` | 0.5 |
| `aframe-extras.animation-mixer` | `animation-mixer` | 0.4, 0.5 |
| `aframe-extras.grid` | `grid` | 0.5 |
| `aframe-extras.json-model` | `json-model` | 0.4, 0.5 |
| `aframe-extras.object-model` | `object-model` | 0.4, 0.5 |
| `aframe-extras.ocean` | `ocean` | 0.5 |
| `aframe-extras.tube` | `tube` | 0.5 |
| `aframe-event-set-component` | `event-set` | 0.3, 0.4, 0.5 |
| `aframe-environment-component` | `environment` | 0.6 |
| `aframe-forcegraph-component` | `forcegraph` | 0.5 |
| `aframe-gaze-control-component` | `gaze-control` | 0.6 |
| `aframe-gearvr-controls-component` | `gearvr-controls` | 0.4 |
| `aframe-gui` | `aframe-gui` | 0.7 |
| `aframe-leap-hands` | `leap-hand` | 0.5 |
| `aframe-lerp-component` | `lerp` | 0.4 |
| `aframe-line-component` | `line` | 0.5 |
| `aframe-log-component` | `log` | 0.5 |
| `aframe-metronome-component` | `metronome` | 0.6 |
| `aframe-mountain-component` | `mountain` | 0.3 |
| `aframe-motion-capture-components` | `avatar-recorder`, `avatar-replayer` | 0.5 |
| `aframe-outline` | `outline` | 0.4 |
| `aframe-particle-system-component` | `particle-system` | 0.3, 0.5 |
| `aframe-physics-system` | `dynamic-body`, `static-body`, `constraint` | 0.3, 0.4, 0.5 |
| `aframe-rain` | `rain` | 0.4 |
| `aframe-shake2show-component` | `aframe-shake2show-component` | 0.3 |
| `aframe-slice9-component` | `slice9` | 0.5 |
| `@ekolabs/aframe-spritesheet-component` | `sprite-sheet` | 0.5 |
| `aframe-point-component` | `point` | 0.4, 0.5 |
| `aframe-raytrace-component` | `raytrace` | 0.4 |
| `aframe-room-component` | `room`, `wall`, `doorhole`, `doorlink`, `floor`, `ceiling`, `sides` | 0.6 |
| `aframe-stats-in-vr-component` | `stats-in-vr` | 0.4 |
| `aframe-stereo-component` | `stereo` | 0.2, 0.5 |
| `aframe-teleport-controls` | `teleport-controls` | 0.4, 0.5 |
| `aframe-text-geometry-component` | `text-geometry` | 0.4, 0.5 |
| `aframe-ui-widgets` | `ui-button`, `ui-rotary`, `ui-toggle`, `ui-slider` | 0.4, 0.5 |
| `aframe-speech-command-component` | `speech-command` | 0.3, 0.4 |
| `super-hands` | `clickable`, `drag-droppable`, `grabbable`, `hoverable`, `progressive-controls`, `stretchable`, `super-hands` | 0.4, 0.5, 0.6 |

## Shaders

| Pacote / entrada | Identificador | Versões A-Frame indicadas |
|---|---|---|
| `aframe-sun-sky` | `sunSky` | 0.2, 0.3 |

## Estados de implementação neste repositório

| Estado | Significado |
|---|---|
| Por analisar | Ainda não foi estudada a origem, licença, versão e API. |
| Em implementação | Existe uma demonstração em construção; ainda não validada. |
| Validado | Exemplo executado num browser com a versão A-Frame e dependências indicadas. |
| Incompatível / indisponível | Não foi possível executar com a configuração documentada ou a dependência deixou de estar disponível. |
| Substituído por funcionalidade nativa | A-Frame atual já oferece a funcionalidade ou existe uma alternativa mantida; não equivale a validar o pacote histórico. |

## Componentes com documentação neste repositório

| Componente | Exemplo | Estado |
|---|---|---|
| `event-set` | [Demonstração](./components/event-set/) | Implementado; validação manual pendente |
| `particle-system` | [Demonstração](./components/particle-system/) | Implementado; validação manual pendente |
| `environment` | [Demonstração](./components/environment/) | Implementado; validação manual pendente |
| `ocean` | [Demonstração](./components/ocean/) | Implementado; validação manual pendente |\n| `physics-system` | [Demonstração](./components/physics-system/) | Implementado; validação manual pendente |

### Nota de compatibilidade — `ocean`

O Component Directory comunitário lista `ocean` como mantido e confirmado com A-Frame 1.8.0. O README do pacote `aframe-extras` 7.7.0, por sua vez, declara a compatibilidade da série 7.x com A-Frame 1.7.x. A demonstração local fixa A-Frame 1.7.1 para seguir a declaração explícita do README do pacote; a indicação 1.8.0 do diretório é preservada como referência comunitária, não como substituição da declaração do projeto. Consulte [a documentação do exemplo ocean](./components/ocean/README.md).

## Entradas históricas com substituição ou indisponibilidade identificada

A análise do [Component Directory comunitário](https://github.com/c-frame/aframewiki/blob/gh-pages/en/pages/component-directory.md) identifica os casos abaixo. Não são criadas páginas de instalação para os pacotes antigos quando a fonte recomenda uma API nativa ou declara a entrada indisponível.

| Entrada / pacote histórico | Situação indicada pelo diretório | Alternativa / tratamento no A-Frame 1.8.0 |
|---|---|---|
| `aframe-animation-component` / `animation` | Excluído por estar substituído pela animação nativa | Usar o componente [animation](https://aframe.io/docs/1.8.0/components/animation.html); a cena principal já o demonstra. |
| `aframe-auto-detect-controllers-component` | Excluído por estar substituído por `tracked-controls` | Usar os componentes nativos de controladores; [documentação Interactions & Controllers](https://aframe.io/docs/1.8.0/introduction/interactions-and-controllers.html). |
| `aframe-controller-cursor-component` / `controller-cursor` | Excluído por estar substituído por `cursor` | Usar o componente e primitivo [cursor](https://aframe.io/docs/1.8.0/introduction/interactions-and-controllers.html). |
| `aframe-extras.cube-env-map` | Excluído por suporte nativo a cubemaps | Usar o primitivo [a-cubemap](https://aframe.io/docs/1.8.0/primitives/a-cubemap.html). |
| `aframe-lerp-component` / `lerp` | Excluído por estar substituído pela animação nativa | Usar [animation](https://aframe.io/docs/1.8.0/components/animation.html), escolhendo a interpolação declarativa adequada. |
| `aframe-rain` / `rain` | O diretório indica que está sem manutenção e aponta a redundância face a particle-system | Preferir o componente comunitário mantido [particle-system](./components/particle-system/); a demonstração deste repositório continua com validação manual pendente. |
| `aframe-line-component` / `line` | O diretório indica que o repositório do pacote já não existe | Não reinstalar nem inventar uma API de substituição para o pacote. O A-Frame 1.8.0 também documenta um componente nativo [line](https://aframe.io/docs/1.8.0/components/line.html), mas não se assume compatibilidade com a API do pacote histórico. |

Estas decisões descrevem a orientação do diretório comunitário e a documentação atual do A-Frame; não constituem testes de browser aos pacotes antigos.

### Nota de análise — `physics-system`\n\nO pacote histórico `aframe-physics-system` tem um fork comunitário mantido: `@c-frame/aframe-physics-system` 4.2.4, licença MIT. O `package.json` declara `peerDependencies.aframe >=0.5.0`, mas o ambiente de desenvolvimento do pacote usa `~1.1.0`; o diretório comunitário indica compatibilidade com 1.8.0. A demonstração local fixa A-Frame 1.8.0 e o build Cannon 4.2.4, sem considerar essa combinação validada até execução num browser. A API Cannon e Ammo não é intercambiável; o exemplo documenta exclusivamente Cannon. Ver [README do exemplo](./components/physics-system/README.md).\n\n## Próximos passos

1. Verificar a página npm/GitHub de cada pacote e a sua licença.
2. Fixar uma versão explícita da dependência, sem usar `latest` em exemplos reproduzíveis.
3. Criar uma pasta por pacote e, quando necessário, uma demonstração por identificador.
4. Testar no A-Frame 1.8.0 e registar browser, dependências e resultado.
5. Atualizar o estado apenas depois do teste real.

A lista é um inventário fiel da fonte histórica consultada. Não inclui automaticamente todos os componentes publicados posteriormente no npm ou noutros repositórios da comunidade.


## Diretório comunitário atualizado

Para além deste arquivo histórico, existe um [Component Directory mantido pela comunidade](https://github.com/c-frame/aframewiki/blob/gh-pages/en/pages/component-directory.md), que se apresenta como alternativa moderna ao Registry desatualizado. Deve ser consultado numa segunda fase para identificar forks mantidos, substituições e componentes mais recentes. O objetivo deste repositório continua a ser documentar também os identificadores históricos pedidos, assinalando claramente os que foram substituídos ou deixaram de funcionar.
