<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia de Graylog" width="160" height="160">
  </a>
  <h1 align="center">Guia de Graylog</h1>
</p>

## :dart: O guia para alavancar a sua carreira

> Graylog é uma plataforma open source de gerenciamento centralizado de logs: ela recebe mensagens de servidores, aplicações, containers e dispositivos de rede em formatos como GELF e Syslog, indexa tudo em um back-end de busca (Elasticsearch/OpenSearch) e deixa você investigar, correlacionar e alertar sobre esses dados em um único lugar. Nascida na Alemanha em 2010, hoje a empresa se reposiciona como uma plataforma de SIEM com IA embutida para times enxutos de segurança, mas o núcleo continua sendo o mesmo: centralizar log, permitir busca rápida com PromQL-like query language própria e automatizar a resposta a incidentes. Este guia reúne a documentação oficial, tutoriais em português e inglês, ferramentas do ecossistema (GELF, Sidecar, Data Node, plugins) e um capítulo dedicado a usar IA na prática com o Graylog — incluindo o servidor MCP que a própria Graylog passou a embutir no produto — tudo verificado e organizado para quem quer sair do zero e chegar à primeira busca e ao primeiro alerta em produção.

<sub> <strong>Siga nas redes sociais para acompanhar mais conteúdos: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/manotoquinho)
[![Discord Badge](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/NbMQUPjHz7)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmXzz_VR0Li8-YOvWN_t3g)
</sub>

## ⚠️ Aviso importante

> Antes de tudo você pode me ajudar e colaborar, deu bastante trabalho fazer esse repositório e organizar para fazer seu estudo ou trabalho melhor, portanto você pode me ajudar das seguintes maneiras:

- Me siga no [Github](https://github.com/arthurspk)
- Acesse as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil)
- Mande feedbacks no [LinkedIn](https://www.linkedin.com/in/arthurspk/)

## 💡 Nossa proposta

> A proposta deste guia é dar uma ideia sobre o atual panorama e guiá-lo se você estiver confuso sobre qual será o seu próximo aprendizado, sem influenciar você a seguir os 'hypes' e 'trends' do momento. Acreditamos que com um maior conhecimento das diferentes estruturas e soluções disponíveis poderá escolher a ferramenta que melhor se aplica às suas demandas. E lembre-se, 'hypes' e 'trends' nem sempre são as melhores opções.

## :beginner: Para quem está começando agora

> Não se assuste com a quantidade de conteúdo apresentado neste guia. Acredito que quem está começando pode usá-lo não como um objetivo, mas como um apoio para os estudos. <b>Neste momento, dê enfoque no que te dá produtividade e o restante marque como <i>Ver depois</i></b>. Ao passo que seu conhecimento se torna mais amplo, a tendência é este guia fazer mais sentido e ficar fácil de ser assimilado. Bons estudos e entre em contato sempre que quiser! :punch:

## 🚨 Colabore

- Abra Pull Requests com atualizações
- Discuta ideias em Issues
- Compartilhe o repositório com a sua comunidade

## 🌍 Tradução

> Se você deseja acompanhar esse repositório em outro idioma que não seja o Português Brasileiro, você pode optar pelas escolhas de idiomas abaixo, você também pode colaborar com a tradução para outros idiomas e a correções de possíveis erros ortográficos, a comunidade agradece.

<img src = "https://i.imgur.com/lpP9V2p.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>English — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/GprSvJe.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Spanish — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/4DX1q8l.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Chinese — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/6MnAOMg.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Hindi — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/8t4zBFd.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Arabic — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/iOdzTmD.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>French — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/PILSgAO.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Italian — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/0lZOSiy.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Korean — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/3S5pFlQ.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Russian — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/i6DQjZa.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>German — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>
<img src = "https://i.imgur.com/wWRZMNK.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Japanese — </b> [Click Here](https://github.com/arthurspk/guiadegraylog)<br>

## 📚 ÍNDICE

[🗺️ Roadmap](#️-roadmap) <br>
[🚀 Por onde começar](#-por-onde-começar) <br>
[📖 Documentação oficial](#-documentação-oficial) <br>
[🔤 Sites e cursos para aprender Graylog](#-sites-e-cursos-para-aprender-graylog) <br>
[📚 Livros](#-livros) <br>
[🎥 Canais no Youtube](#-canais-no-youtube) <br>
[📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters) <br>
[🛠️ Ferramentas](#️-ferramentas) <br>
[🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios) <br>
[🤖 IA na prática](#-ia-na-prática) <br>
[💼 Carreira e vagas](#-carreira-e-vagas) <br>
[👥 Comunidades](#-comunidades) <br>

## 🗺️ Roadmap

- [O que é o Graylog](https://go2docs.graylog.org/current/what_is_graylog/what_is_graylog.htm) — Visão geral oficial da plataforma e das variantes Graylog Open, Enterprise, Security e Illuminate.
- [Novidades do Graylog 7.1](https://go2docs.graylog.org/current/what_is_graylog/what_s_new_in_graylog_7.1.htm) — Página oficial com o que mudou na versão mais recente da plataforma.
- [Matriz de compatibilidade](https://go2docs.graylog.org/current/downloading_and_installing_graylog/compatibility_matrix.htm) — Referência oficial de versões de SO, JVM e navegadores suportadas em cada release.
- [Release notes](https://go2docs.graylog.org/current/upgrading_graylog/release_notes.htm) — Notas de cada versão lançada, direto da documentação oficial.
- [Graylog2/graylog2-server — Releases](https://github.com/Graylog2/graylog2-server/releases) — Histórico completo de releases no GitHub, com changelog técnico de cada versão.

## 🚀 Por onde começar

1. Leia ["O que é o Graylog"](https://go2docs.graylog.org/current/what_is_graylog/what_is_graylog.htm) para entender a arquitetura: Graylog Server, Data Node (busca) e MongoDB (metadados).
2. Suba um ambiente local seguindo a [instalação oficial via Docker](https://go2docs.graylog.org/current/downloading_and_installing_graylog/docker_installation.htm).
3. Configure seu primeiro [Input](https://go2docs.graylog.org/current/getting_in_log_data/getting_in_log_data.html) em formato [GELF](https://go2docs.graylog.org/current/getting_in_log_data/gelf.html) para começar a receber logs de uma aplicação.
4. Aprenda a [sintaxe de busca](https://go2docs.graylog.org/current/making_sense_of_your_log_data/search_syntax_reference.htm) para filtrar e investigar mensagens.
5. Organize o fluxo com [Streams](https://go2docs.graylog.org/current/making_sense_of_your_log_data/streams.html) e enriqueça os dados com [Pipelines](https://go2docs.graylog.org/current/making_sense_of_your_log_data/pipelines.html).
6. Configure seu primeiro [Alert](https://go2docs.graylog.org/current/interacting_with_your_log_data/alerts.html) a partir de uma busca salva.
7. Veja tudo isso na prática no vídeo [Implementação do Graylog e NXLog no Ubuntu Server 22.04](https://www.youtube.com/watch?v=_Hp8fuKdfCo), do canal Bora para Prática.

## 📖 Documentação oficial

- [Instalação via Docker](https://go2docs.graylog.org/current/downloading_and_installing_graylog/docker_installation.htm) — Guia oficial para subir um Graylog completo com Docker.
- [Downloads oficiais](https://graylog.org/downloads/) — Pacotes, imagens e links de instalação direto do site do Graylog.
- [Instalando o Data Node](https://go2docs.graylog.org/current/downloading_and_installing_graylog/install_graylog_data_node.htm) — Como instalar o Data Node, o componente que hoje concentra a busca e o armazenamento (baseado em OpenSearch).
- [Getting in log data — visão geral](https://go2docs.graylog.org/current/getting_in_log_data/getting_in_log_data.html) — Panorama oficial de todas as formas de trazer logs para o Graylog (Inputs, Sidecar, Forwarder).
- [GELF](https://go2docs.graylog.org/current/getting_in_log_data/gelf.html) — Documentação do Graylog Extended Log Format, o formato de log nativo e recomendado da plataforma.
- [Especificação do formato GELF](https://go2docs.graylog.org/current/getting_in_log_data/gelf_format.html) — Referência técnica completa dos campos e do payload do GELF.
- [Graylog Sidecar](https://go2docs.graylog.org/current/getting_in_log_data/graylog_sidecar.html) — Documentação do agente oficial que gerencia coletores de log (Filebeat, Winlogbeat etc.) remotamente.
- [Input de Beats](https://go2docs.graylog.org/current/getting_in_log_data/beats_input.html) — Como configurar um Input para receber logs enviados por Filebeat/Winlogbeat.
- [Pipelines](https://go2docs.graylog.org/current/making_sense_of_your_log_data/pipelines.html) — Documentação do processador de pipelines, usado para rotear, transformar e enriquecer mensagens.
- [Casos de uso de Pipelines](https://go2docs.graylog.org/current/making_sense_of_your_log_data/pipeline_usage.html) — Exemplos oficiais de regras de pipeline para mascarar dados, mudar timezone e mais.
- [Streams](https://go2docs.graylog.org/current/making_sense_of_your_log_data/streams.html) — Como rotear mensagens em tempo real para diferentes destinos com base em regras.
- [Extractors](https://go2docs.graylog.org/current/making_sense_of_your_log_data/extractors.htm) — Extração de campos de mensagens não estruturadas sem precisar escrever uma pipeline.
- [Referência de sintaxe de busca](https://go2docs.graylog.org/current/making_sense_of_your_log_data/search_syntax_reference.htm) — Referência oficial e completa da linguagem de busca do Graylog.
- [Como buscar seus dados de log](https://go2docs.graylog.org/current/making_sense_of_your_log_data/how_to_search_your_log_data.htm) — Tutorial oficial de busca, do básico ao avançado.
- [Alerts](https://go2docs.graylog.org/current/interacting_with_your_log_data/alerts.html) — Documentação do sistema de alertas do Graylog.
- [Tipos de alerta](https://go2docs.graylog.org/current/interacting_with_your_log_data/alert_types.htm) — Referência oficial dos tipos de condição disponíveis para disparar um alerta.
- [Dashboards](https://go2docs.graylog.org/current/interacting_with_your_log_data/dashboards.html) — Como montar dashboards e widgets a partir de buscas salvas.
- [Event Definitions](https://go2docs.graylog.org/current/interacting_with_your_log_data/event_definitions.html) — Documentação de como definir e correlacionar eventos a partir de dados de log.
- [Correlation engine](https://go2docs.graylog.org/current/interacting_with_your_log_data/correlation_engine.html) — Como o motor de correlação de eventos do Graylog funciona por trás dos Event Definitions.
- [REST API](https://go2docs.graylog.org/current/setting_up_graylog/rest_api.html) — Referência oficial da API HTTP usada por integrações, scripts e pela própria interface web do Graylog.
- [Casos de uso da REST API](https://go2docs.graylog.org/current/setting_up_graylog/rest_api_use_cases.htm) — Exemplos práticos de chamadas à API para tarefas comuns de administração.
- [Content Packs](https://go2docs.graylog.org/current/what_more_can_graylog_do_for_me/content_packs.html) — Como empacotar e importar Inputs, Streams e Dashboards prontos.
- [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) — Código-fonte oficial do Graylog no GitHub: issues, discussões técnicas e o histórico completo do projeto.
- [Graylog Marketplace](https://marketplace.graylog.org/) — Catálogo oficial de plugins, integrations e Content Packs para estender o Graylog.

## 🔤 Sites e cursos para aprender Graylog

> Cursos para aprender Graylog em Português

- [Implementação do Graylog e NXLog no Ubuntu Server 22.04](https://www.youtube.com/watch?v=_Hp8fuKdfCo) — Robson Vaamonde (canal Bora para Prática) mostra a instalação completa do Graylog com OpenSearch e NXLog, do zero.
- [LIVE Descomplicando o Graylog](https://www.youtube.com/watch?v=aSdsk73_tHE) — Live técnica do canal LINUXtips, com Jeferson (badtuxx) e Maiki, sobre gerenciamento de logs com Graylog.
- [Guia de como criar um cluster com o centralizador de logs Graylog 3.3](https://dev.to/sysadminas/guia-de-como-criar-um-cluster-com-o-centralizador-de-logs-graylog-3-3-16d8) — Tutorial em português passo a passo para montar um cluster Graylog.
- [Centralização de logs do Kubernetes com Graylog + Fluentd](https://dev.to/aloisiobilck/centralizacao-de-logs-do-kubernetes-com-graylog-fluentd-22l8) — Artigo mostrando como enviar logs de um cluster Kubernetes para o Graylog usando Fluentd.
- [vaamonde/ubuntu-2204 — implementação do Graylog](https://github.com/vaamonde/ubuntu-2204/blob/main/04-news/05-graylog.md) — Roteiro guiado em 24 passos (texto + vídeo) para instalar OpenSearch, Graylog e NXLog em um Ubuntu Server, mantido e atualizado em 2026.

> Cursos para aprender Graylog em Inglês

- [An Introduction to Graylog](https://dev.to/klauenboesch/an-introduction-to-graylog-79o) — Artigo introdutório sobre os conceitos centrais do Graylog: Inputs, Streams e Extractors.
- [Setup Graylog on Synology DSM 7.x with Docker for UniFi logs](https://dev.to/bitoiu/setup-graylog-on-synology-dsm-7x-with-docker-for-unifi-logs-35h6) — Tutorial prático de como subir um Graylog com Docker Compose para centralizar logs de dispositivos UniFi.
- [How To Configure Graylog to Centralize Logs](https://www.digitalocean.com/community/tutorials/how-to-configure-graylog-to-centralize-logs-on-ubuntu-16-04) — Tutorial oficial da DigitalOcean sobre instalação e configuração inicial do Graylog.
- [How To Collect Nginx and PHP-FPM Logs With Graylog](https://www.digitalocean.com/community/tutorials/how-to-collect-nginx-and-php-fpm-logs-with-graylog-on-ubuntu-16-04) — Tutorial da DigitalOcean mostrando como enviar logs de Nginx e PHP-FPM para o Graylog.
- [Graylog and CoPilot Integration](https://www.youtube.com/watch?v=MyvPmQ4Cfb0) — Taylor Walton (SOCFortress) mostra como integrar o Graylog à plataforma open source de SOC CoPilot.
- [Wazuh Content Pack For Graylog](https://www.youtube.com/watch?v=euFrHP0VkD8) — Taylor Walton mostra como configurar o Content Pack do Wazuh dentro do Graylog para montar um stack de SIEM.

## 📚 Livros

- [The Art of Monitoring (James Turnbull)](https://www.artofmonitoring.com/) — Livro pago sobre arquitetura de monitoramento e logging centralizado, com conceitos aplicáveis diretamente a um pipeline como o do Graylog.
- [Apostila de DevOps (Caelum)](https://github.com/caelum/apostila-devops) — Apostila gratuita e de código aberto em português cobrindo o panorama de ferramentas de monitoramento contínuo, incluindo o Graylog.
- [Site Reliability Engineering — Monitoring Distributed Systems (Google, gratuito)](https://sre.google/sre-book/monitoring-distributed-systems/) — Capítulo gratuito do livro de SRE do Google sobre o que (e o que não) monitorar e alertar, referência para quem opera um Graylog em produção.

## 🎥 Canais no Youtube

> Em português

- [Bora para Prática](https://www.youtube.com/@boraparapratica) — Canal de Robson Vaamonde com implementações práticas de infraestrutura, incluindo o Graylog do zero no Ubuntu Server.
- [LINUXtips](https://www.youtube.com/@LinuxTips) — Maior canal de DevOps do Brasil, com lives técnicas que incluem gerenciamento de logs com Graylog.
- [Iago Ferreira TI](https://www.youtube.com/@IagoFerreiraTI) — Conteúdo de carreira em Cloud, DevOps e SRE, incluindo o mercado de observabilidade onde o Graylog aparece como ferramenta.

> Em inglês

- [Taylor Walton (SOCFortress)](https://www.youtube.com/@taylorwalton_socfortress) — Tutoriais de como integrar o Graylog ao Wazuh e à plataforma SOCFortress para montar um SOC open source completo.

## 📰 Sites, blogs e newsletters

- [Graylog — blog oficial](https://graylog.org/blog/) — Anúncios de release, novidades de produto e artigos técnicos publicados pelo próprio time do Graylog.
- [250 GB/day of logs with Graylog: The good, the bad and the ugly](https://thehftguy.wordpress.com/2016/09/12/250-gbday-of-logs-with-graylog-the-good-the-bad-and-the-ugly/) — Relato real de engenharia sobre operar Graylog em alta escala, com armadilhas e lições aprendidas.

## 🛠️ Ferramentas

- [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server) — O servidor Graylog em si: repositório oficial do projeto open source.
- [Graylog Docker (oficial)](https://github.com/Graylog2/graylog-docker) — Imagem Docker oficial do Graylog.
- [Graylog2/docker-compose](https://github.com/Graylog2/docker-compose) — Conjunto oficial de arquivos Docker Compose para subir um Graylog completo para testes ou demonstração.
- [OpenSearch](https://opensearch.org/) — Motor de busca e armazenamento usado pelo Graylog (via Data Node) para indexar e consultar os logs.
- [MongoDB](https://www.mongodb.com/) — Banco de dados usado pelo Graylog para armazenar metadados de configuração (streams, usuários, dashboards).
- [Graylog Sidecar (collector-sidecar)](https://github.com/Graylog2/collector-sidecar) — Repositório oficial do agente que gerencia coletores de log remotamente a partir do Graylog.
- [Graylog Ansible Role (oficial)](https://github.com/Graylog2/graylog-ansible-role) — Role Ansible oficial para instalar e configurar o Graylog.
- [Graylog Plugin — Threat Intel](https://github.com/Graylog2/graylog-plugin-threatintel) — Plugin oficial que enriquece mensagens de log com dados de inteligência de ameaças (IoCs).
- [Graylog Plugin — Slack](https://github.com/graylog-labs/graylog-plugin-slack) — Plugin oficial para enviar alertas do Graylog diretamente para o Slack.
- [Graylog Plugin — AWS](https://github.com/Graylog2/graylog-plugin-aws) — Conjunto oficial de plugins para integrar o Graylog a serviços da AWS, como CloudTrail e Flow Logs.
- [Telegram Alert (plugin)](https://github.com/irgendwr/TelegramAlert) — Plugin da comunidade para enviar notificações de alerta do Graylog para o Telegram.
- [graypy](https://github.com/severb/graypy) — Handler de logging em Python que envia mensagens no formato GELF para o Graylog.
- [pygelf](https://github.com/keeprocking/pygelf) — Biblioteca Python alternativa de handlers de logging com suporte a GELF.
- [logback-gelf](https://github.com/osiegmar/logback-gelf) — Appender do Logback (Java) para enviar mensagens GELF sem dependências extras.
- [logstash-gelf](https://github.com/mp911de/logstash-gelf) — Implementação de GELF em Java para os principais frameworks de log (log4j, log4j2, logback e mais).
- [gelf-php](https://github.com/bzikarsky/gelf-php) — Implementação em PHP para enviar logs a um backend compatível com GELF, como o Graylog.
- [laravel-gelf-logger](https://github.com/hedii/laravel-gelf-logger) — Pacote para enviar logs do Laravel diretamente para o Graylog via GELF.
- [Serilog.Sinks.Graylog](https://github.com/serilog-contrib/serilog-sinks-graylog) — Sink do Serilog (.NET) para enviar logs estruturados ao Graylog.
- [gelf-extensions-logging](https://github.com/mattwcole/gelf-extensions-logging) — Provider GELF para o Microsoft.Extensions.Logging (.NET).
- [graylog-golang](https://github.com/robertkowalski/graylog-golang) — Implementação completa em Go para enviar mensagens em GELF ao Graylog.
- [node-gelf-pro](https://github.com/kkamkou/node-gelf-pro) — Cliente Node.js para enviar logs ao Graylog no formato GELF.
- [gelf-rb](https://github.com/graylog-labs/gelf-rb) — Biblioteca Ruby oficial da comunidade Graylog para o formato GELF.
- [Graylog CLI Dashboard](https://github.com/graylog-labs/cli-dashboard) — Dashboard de stream do Graylog que roda direto no terminal.

## 🧪 Projetos práticos e desafios

- [vaamonde/ubuntu-2204 — implementação do Graylog](https://github.com/vaamonde/ubuntu-2204/blob/main/04-news/05-graylog.md) — Projeto guiado com 24 etapas para colocar OpenSearch, Graylog e NXLog no ar em um Ubuntu Server do zero.
- [lawrencesystems/graylog](https://github.com/lawrencesystems/graylog) — Projeto com Docker Compose e configuração de NXLog para Windows, pronto para enviar logs GELF a um Graylog local.
- [SOCFortress CoPilot](https://github.com/socfortress/CoPilot) — Plataforma open source de SOC que integra Graylog e Wazuh; um desafio completo para quem quer montar um mini-SOC do zero.

## 🤖 IA na prática

Graylog é uma das poucas ferramentas deste guia que passou a embutir um servidor MCP (Model Context Protocol) diretamente no produto: a partir das versões mais recentes, dá para conectar um assistente de IA como Claude à sua própria instância do Graylog e pedir para ele investigar logs, montar buscas ou explicar um alerta usando linguagem natural. Além do recurso oficial, a comunidade também mantém vários servidores MCP alternativos e mais enxutos para o mesmo fim.

**Para aprender**
- Peça para um assistente de IA **explicar uma query de busca do Graylog** que você não escreveu, campo por campo, incluindo o que cada operador (`AND`, `OR`, faixas de tempo, wildcards) está filtrando.
- Peça para **gerar uma regra de Pipeline** (por exemplo, mascarar um CPF ou normalizar um campo de IP) a partir de uma descrição em português do que você precisa, e depois valide o resultado manualmente.
- Cole a saída de log de uma aplicação nova e peça sugestões de **como estruturar essa mensagem em GELF**, com quais campos adicionais fariam sentido antes de instrumentar o código.

**Para trabalhar**
- O [Model Context Protocol (MCP) do Graylog](https://go2docs.graylog.org/current/setting_up_graylog/graylog_mcp.htm) é o servidor MCP **oficial**, embutido no próprio produto — a [documentação de configuração](https://go2docs.graylog.org/current/setting_up_graylog/configure_mcp.htm) e a [referência de ferramentas MCP](https://go2docs.graylog.org/current/setting_up_graylog/model_context_protocol__mcp__tools.htm) explicam como habilitá-lo e quais ações ele expõe.
- Servidores MCP da comunidade como o [mcp-graylog](https://github.com/mothlike/mcp-graylog), o [graylog-mcp](https://github.com/lcaliani/graylog-mcp) e o [mcp-server-graylog](https://github.com/Pranavj17/mcp-server-graylog) conectam assistentes como Claude e Cursor a uma instância do Graylog para buscar e agregar logs via linguagem natural.
- O [Graylog MCP Wizard Skill](https://github.com/glog-tools/graylog-mcp-wizard-skill) é uma Claude Skill pronta que guia a conexão do Claude Code/Claude Desktop ao servidor MCP do Graylog passo a passo.
- Use IA para gerar **Extractors ou regras regex** a partir de uma amostra de log não estruturado — uma das tarefas mais repetitivas de quem administra Inputs no Graylog.
- Depois de qualquer busca, pipeline ou alerta gerado por IA, **valide manualmente na aba de busca do próprio Graylog** antes de salvar em produção — um filtro de tempo errado ou um `AND`/`OR` trocado muda completamente o resultado.

**Limites e boas práticas**
- Um servidor MCP conectado ao Graylog dá acesso de leitura (e, dependendo da configuração, de escrita) a dados de log que podem conter informação sensível — nunca conecte um assistente de IA a uma instância de produção sem revisar as permissões do token de API usado.
- IA erra a sintaxe de busca do Graylog com frequência, principalmente em intervalos de tempo relativos e em campos com nomes customizados — sempre rode a busca manualmente antes de confiar no resultado.
- Cuidado com Pipelines geradas por IA que descartam mensagens silenciosamente (`drop_message()`) — um teste malfeito pode fazer você perder logs importantes sem perceber.
- Entenda a regra antes de ativá-la: um alerta ou uma pipeline gerada por IA que dispara errado (ou não dispara) em produção é problema seu, não da IA.

- [Model Context Protocol — documentação oficial](https://modelcontextprotocol.io/) — Especificação aberta do protocolo MCP, usado pelo Graylog e pelos servidores da comunidade para conversar com assistentes de IA.
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete e chat com IA no editor; útil para escrever pipelines, extractors e chamadas à REST API do Graylog.
- [Cursor](https://cursor.com/) — Editor baseado em IA que se conecta bem a servidores MCP para automatizar tarefas de administração do Graylog.
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de código no terminal que, via MCP, consegue consultar o Graylog e ajudar a investigar incidentes direto do terminal.

## 💼 Carreira e vagas

Graylog aparece com frequência em vagas de DevOps, SRE e, cada vez mais, de Analista de SOC/SIEM no Brasil — muitas vezes ao lado de ferramentas como Wazuh, Elastic e Grafana em pilhas de observabilidade e segurança.

- [DevOps-Brasil/Vagas](https://github.com/DevOps-Brasil/Vagas) — Repositório brasileiro com vagas de DevOps, SRE e observabilidade publicadas como issues no GitHub.
- [Analisando vagas de Cloud, DevOps e SRE](https://www.youtube.com/watch?v=fADlNgre4BY) — Iago Ferreira analisa vagas reais de Cloud/DevOps/SRE no Brasil e o que elas pedem, incluindo ferramentas de observabilidade e logging.

## 👥 Comunidades

- [Graylog Community](https://community.graylog.org/) — Fórum oficial da comunidade Graylog, com dúvidas técnicas, anúncios e discussões sobre a plataforma.
- [r/graylog](https://www.reddit.com/r/graylog/) — Subreddit dedicado à comunidade do Graylog.
- [SOCFortress — Discord](https://discord.gg/UN3pNBzaEQ) — Comunidade em torno do SOCFortress CoPilot, com bastante troca sobre integração entre Graylog e Wazuh.
- [LINUXtips — Discord](https://discord.gg/linuxtips) — Uma das maiores comunidades de DevOps do Brasil, onde ferramentas como o Graylog aparecem com frequência nas discussões.
