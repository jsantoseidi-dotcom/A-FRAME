# Componentes

O inventário histórico está em [../registry-inventory.md](../registry-inventory.md).

Cada pacote terá uma pasta própria, com uma demonstração isolada:

```text
components/
└── nome-do-pacote/
    ├── index.html
    ├── README.md
    └── assets/
```

## Critérios de validação

- Identificar o pacote, versão exata, origem e licença.
- Confirmar a API e as dependências na documentação do projeto original.
- Não carregar versões históricas sem verificar a compatibilidade com A-Frame 1.8.0.
- Demonstrar a funcionalidade real do componente, não apenas uma primitiva nativa com o mesmo nome.
- Testar carregamento, consola do browser e comportamento da cena.
- Documentar propriedades, eventos, limitações e resultado do teste.
- Marcar como **Validado** apenas depois de executar o exemplo num browser.

## Estados

- **Por analisar** — sem exemplo ou teste.
- **Em implementação** — demonstração em construção.
- **Validado** — testado com versões explicitamente indicadas.
- **Incompatível / indisponível** — dependência ou API não funciona na configuração documentada.
- **Substituído por funcionalidade nativa** — alternativa moderna identificada, sem alegar que o pacote antigo foi validado.

O Registry original está descontinuado. A compatibilidade histórica indicada no inventário não deve ser interpretada como compatibilidade atual.
