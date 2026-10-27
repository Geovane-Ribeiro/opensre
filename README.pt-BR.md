<div align="center">

<img src="docs/logo/opensre-logo-white.svg" alt="OpenSRE" width="360" />

# OpenSRE v0.1 — Crie seus próprios agentes de IA para SRE

**Documentação em português do Brasil (PT-BR)**

O OpenSRE é um framework de código aberto para agentes de inteligência artificial aplicados à engenharia de confiabilidade de sites (SRE). Ele também oferece recursos para treinamento e avaliação desses agentes. Conecte suas ferramentas de operação, defina fluxos de trabalho e investigue questões de produção em sua própria infraestrutura.

**Idiomas:** [Português (Brasil)](README.pt-BR.md) · [English](README.md) · [简体中文](README.zh-CN.md)

[Guia de início rápido (oficial)](https://www.opensre.com/docs/getting-started/quickstart) · [Documentação oficial](https://www.opensre.com/docs) · [Perguntas frequentes](https://opensre.com/docs/guides/faq)

</div>

> **Aviso:** o OpenSRE está em versão alfa pública. Alguns fluxos centrais já podem ser experimentados, mas as APIs, integrações e funcionalidades ainda podem mudar. Esta tradução não é uma publicação oficial da equipe original.

## Antes de começar

Tenha disponível:

- Um terminal aberto em um projeto de código.
- Um repositório Git (recomendado para acompanhar o fluxo completo de demonstração).
- As permissões e credenciais exigidas pelas integrações que você decidir configurar.

## Instalação e primeiros passos

No macOS ou Linux, o README oficial apresenta este comando:

```bash
curl -fsSL https://install.opensre.com | bash -s -- -gh
```

**Atenção:** esse comando executa um script remoto. Antes de usá-lo, avalie a origem e o conteúdo do instalador. Acesse o [README original](README.md) para conferir as instruções atualizadas, as opções do instalador e o restante do procedimento. A tradução não altera comandos nem parâmetros de execução.

## O que você pode fazer com o OpenSRE?

- **Investigação de incidentes:** organizar evidências e explorar possíveis causas de problemas em produção.
- **Integrações:** conectar ferramentas de observabilidade e operações suportadas pelo projeto.
- **Fluxos de trabalho personalizados:** definir etapas de investigação e ações de agentes.
- **Treinamento e avaliação:** experimentar como agentes de IA respondem às tarefas.
- **Implantação própria:** executar componentes em infraestrutura sob seu controle, conforme os requisitos técnicos do projeto.

Os resultados e as integrações disponíveis dependem da versão instalada, da configuração e das credenciais concedidas.

## Recomendações de segurança

1. Comece em um ambiente de laboratório, sem acesso de escrita a sistemas de produção.
2. Use credenciais de menor privilégio e proteja segredos e dados sensíveis.
3. Revise qualquer ação de remediação antes de permitir execução automática.
4. Verifique a documentação oficial para requisitos, limites e atualizações.

## Onde encontrar as instruções completas

O [README em inglês](README.md) permanece como referência completa e atualizada para instalação, implantação, arquitetura, integrações, segurança, telemetria, licença e citações.

A documentação oficial está disponível em [opensre.com/docs](https://www.opensre.com/docs). A tradução progressiva dos demais materiais deve manter intactos exemplos executáveis, identificadores de API, variáveis de ambiente, rotas e nomes de arquivos.

## Sobre esta tradução

Esta versão brasileira é mantida no fork [Geovane-Ribeiro/opensre](https://github.com/Geovane-Ribeiro/opensre) e preserva a autoria e os créditos do projeto original [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre).

**Licença:** consulte [LICENSE](LICENSE) e os avisos legais do projeto original. Traduções e adaptações não alteram a licença existente.
