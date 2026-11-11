# event-set

Componente comunitário que permite associar eventos a alterações de propriedades de entidades A-Frame.

- Pacote: `aframe-event-set-component`
- Versão fixada: `5.1.0`
- Licença indicada no npm: MIT
- A-Frame usado no exemplo: `1.8.0`
- Demonstração: [abrir index.html](./index.html)

## Interação

- Ao passar o cursor sobre o cubo, muda a cor.
- Ao retirar o cursor, repõe a cor.
- Ao clicar, altera escala e cor.

O exemplo usa `event-set__<instância>` com a propriedade `_event` para indicar o evento observado.

## Dependências

O HTML carrega as versões fixas por CDN:

```html
<script src="https://aframe.io/releases/1.8.0/aframe.min.js"></script>
<script src="https://unpkg.com/aframe-event-set-component@5.1.0/dist/aframe-event-set-component.min.js"></script>
```

## Estado de validação

**Implementado; validação manual pendente.** A documentação oficial de A-Frame 1.8.0 inclui um exemplo de integração com event-set. Antes de marcar como validado, confirmar no browser que o CDN carrega e que os eventos de cursor e clique atualizam a entidade.

## Referências

- [Documentação A-Frame 1.8.0 — Interactions & Controllers](https://aframe.io/docs/1.8.0/introduction/interactions-and-controllers.html)
- [npm — aframe-event-set-component](https://www.npmjs.com/package/aframe-event-set-component)
