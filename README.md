# UniInbox

    [![CI](https://github.com/GuilhermeCostaProenca/uniinbox/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GuilhermeCostaProenca/uniinbox/actions/workflows/ci.yml)

    Projeto de produto digital para resolver dor real de mercado com execu??o em padr?o profissional de portf?lio.

    ## Proposta
    **Central ?nica de comunica??o e foco** para Profissionais com alta sobrecarga de canais digitais.

    ## Problema
    Perda de foco por excesso de notifica??es e m?ltiplos canais desconectados.

    ## P?blico-alvo
    Profissionais com alta sobrecarga de canais digitais

    ## Stack sugerida
    Frontend Next.js, backend event-driven, PostgreSQL, Redis, conectores de canais

    ## MVP inicial
    - Inbox unificada de e-mail, chat e mensagens
    - Regras de prioridade por contato e contexto
    - Modo foco com resumo inteligente ao final do bloco
    - Dashboard de carga de notifica??es por dia

    ## Estrutura base
    - `README.md`: vis?o do produto e execu??o.
    - `PRD.md`: escopo funcional e regras de produto.
    - `ARCHITECTURE.md`: desenho t?cnico inicial.
    - `BACKLOG.md`: backlog priorizado por valor.
    - `PLAN.md`: plano de execu??o em fases.
    - `.github/workflows/ci.yml`: pipeline de valida??o.

    ## Como come?ar
    1. Refinar PRD com recorte de usu?rio e problema.
    2. Definir arquitetura de refer?ncia e stack final.
    3. Implementar fluxo principal ponta a ponta.
    4. Subir CI, testes essenciais e documenta??o de uso.

    ## Riscos principais
    Limites de APIs de mensageria e UX de prioriza??o

    ## Contexto da ideia
    UniInbox –  central  única  de  comunicação  e  foco:  Hoje  um  profissional  típico  lida  com  uma
cacofonia de apps de comunicação: emails, WhatsApp, Slack/Teams, SMS, notificações disso e
daquilo.  A  consequência?  Sobrecarga  de  notificações,  perda  de  mensagens  importantes  e
dificuldade de focar no trabalho sem interrupções a cada 2 minutos. Estudos mostram que
quase metade dos trabalhadores hoje busca tempo “protegido” sem notificações para conseguir
se concentrar, e ~40% dizem que as notificações constantes atrapalham diretamente sua
capacidade de foco. Ou seja, é uma dor generalizada no mundo do trabalho digital. Por que
ainda não resolveram? Cada app quer sua atenção em tempo real e, embora existam modos
Não Perturbe e aplicativos que juntam chats, falta uma solução unificadora e inteligente: que
centralize mensagens de vários canais e permita ao usuário controlar quando e como ver cada
coisa. Imagine um painel único onde entram seus emails, mensagens instantâneas e alertas
diversos, aplicando filtros de importância e até pausando tudo para você trabalhar em paz – isso
hoje não existe de forma integrada e fácil.  Quem ganharia com isso: profissionais de  alta
conectividade – gente de vendas que fala com clientes no WhatsApp e e-mail, desenvolvedores
lidando com Slack e tickets, gestores recebendo mil notificações – todos estão querendo respirar .
Projeto hipotético:UniInbox, que junta todos os recados numa caixa de entrada universal e
inteligente. Ele poderia ter um “modo foco” (silencia notificações por um período, depois te
mostra um resumo) e um sistema de prioridade (por exemplo, alerta imediato só se for seu
chefe ou algo crítico; o resto fica pra depois). Seria uma forma de reduzir o estresse digital e
aumentar a produtividade sem perder nada importante.
