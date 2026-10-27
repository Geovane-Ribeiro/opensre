# Acompanhamento da localização PT-BR

Este documento acompanha a tradução comunitária do fork [Geovane-Ribeiro/opensre](https://github.com/Geovane-Ribeiro/opensre). O projeto original e sua autoria pertencem a [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre).

## Implementado nesta branch

- `README.pt-BR.md`: guia introdutório, **não** tradução integral do README original.
- `docs/README.pt-BR.md`: orientações iniciais da documentação.
- `README.md`: link para a versão em português.
- `docs/pt-br/index.mdx`: página de entrada localizada.
- `docs/pt-br/quickstart.mdx`: início rápido traduzido.
- `docs/pt-br/features.mdx`: recursos traduzidos.
- `docs/pt-br/faq.mdx`: perguntas frequentes traduzidas.
- `docs/pt-br/install.mdx`: instalação traduzida.
- `docs/pt-br/install-local.mdx`: instalação local traduzida.
- `docs/pt-br/install.mdx`: guia de instalação traduzido.
- `docs/pt-br/install-local.mdx`: guia de instalação local traduzido.
- `docs/pt-br/integrations.mdx`: visão geral de integrações em português, com catálogo resumido.
- `docs/pt-br/shell-commands.mdx`: referência resumida de comandos do terminal em português.
- `docs/pt-br/api-http.mdx`: API HTTP traduzida.
- `docs/pt-br/masking.mdx`: explicação de mascaramento traduzida.
- `docs/docs.json`: seção de navegação PT-BR adicionada.

Os textos ingleses originais continuam disponíveis. Os guias traduzidos preservam comandos executáveis, nomes de variáveis, integrações, links técnicos e os créditos de origem.

## Ainda não implementado

- Tradução integral do README original e de todas as páginas MDX.
- Internacionalização efetiva do terminal interativo, CLI, aplicativo web e mensagens de erro.
- Internacionalização de respostas, instruções e prompts internos dos agentes.
- Alternância de idioma configurável e armazenamento de preferência de idioma.
- Testes de interface, build, lint, CLI, links e regressão.
- Revisão terminológica e técnica completa com a versão atualizada do upstream.

## Regras para as próximas alterações

1. Manter traduções em arquivos próprios sempre que possível e evitar alterações extensas no código de produção sem testes.
2. Preservar rotas, identificadores de API, chaves de configuração, variáveis de ambiente e comandos de terminal.
3. Centralizar textos da interface em catálogos de mensagens; prever idioma padrão em inglês e fallback para chaves ausentes.
4. Em fluxos com LLM, distinguir mensagens mostradas à pessoa de instruções internas de sistema. Traduções de prompts exigem testes de comportamento.
5. Validar a documentação com a ferramenta de prévia do Mintlify; validar a CLI e aplicação por testes antes de integrar ao branch principal.
6. Não atribuir a tradução comunitária à equipe oficial.

## Estado de validação

**Alterações confirmadas via API do GitHub.** Não foram executados build, testes automatizados ou prévia gráfica neste ambiente. Portanto, os arquivos traduzidos ainda precisam de validação funcional antes de um merge.

## Observação da execução mais recente

Foi tentado obter o repositório completo por Git, mas a rede do ambiente de execução não conseguiu resolver o domínio do GitHub. As mudanças foram feitas por API do GitHub e conferidas por leitura dos arquivos. **Não é possível declarar a tradução total concluída**: páginas não traduzidas, interface e prompts internos continuam pendentes. As páginas adicionadas nesta etapa são traduções resumidas com vínculos à documentação original, e não traduções integrais de todos os guias.

## Novas páginas desta etapa

- `docs/pt-br/headless-cli.mdx`: guia resumido da CLI sem interação, entrada de arquivos, permissões e JSON.
- `docs/pt-br/python-api.mdx`: guia introdutório de uso da API Python, sessões e triagem de alertas.

O projeto continua **parcialmente traduzido**. A documentação original mais extensa não foi traduzida integralmente, e as interfaces executáveis e prompts dos agentes não foram localizados e testados. Não foram executados testes automatizados de regressão ou renderização do Mintlify nesta etapa.
