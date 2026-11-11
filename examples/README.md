# A-Frame Examples

Área de demonstrações práticas dos componentes do [A-Frame Registry](https://aframe.io/aframe-registry/).

## Objetivos

- Catalogar os componentes do Registry.
- Disponibilizar exemplos executáveis no browser.
- Documentar instalação, propriedades, eventos e compatibilidade.
- Distinguir componentes mantidos, experimentais e descontinuados.

## Estrutura

Cada componente terá uma pasta própria com:
- `index.html`: demonstração principal.
- `README.md`: descrição, dependências e instruções.
- exemplos adicionais quando fizer sentido.

## Executar localmente

Como os exemplos usam módulos e recursos web, serve esta pasta através de um servidor HTTP. Por exemplo:

```bash
python -m http.server 8000
```

Depois abre `http://localhost:8000/examples/` a partir da raiz do repositório.

## Estado do catálogo

O catálogo inicial é um ponto de partida. Cada integração será validada individualmente; a presença de um componente no Registry não garante compatibilidade com A-Frame 1.8.0.
