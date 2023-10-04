https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EYjkgVZuUv5HsVgJUEPv1_oB_QWs8MFBY_PBQ2UAtLqucg?e=262HGK

https://github.com/elidianaandrade/dio-curso-git-github

O que é Versionamento de Código?

Sistemas de Controle de Versão
**Controlam as versões de um arquivo ao longo do tempo.**

- Regista o histórico de atualizações de um aquivo;
- Gerencia quais foram as alterações, a data, autor, etc.;
- Organização, controle e segurança.

Tipos de Sistemas de Controle de Versão
Dentre os Sistemas de Controle de Versão (VCS), temos:
- VCS Centralizado (CVCS)
	Ex.: CVS, Subversion.
- VCS Distribuído (DVCS)
	Ex.: Git, Mercurial.


## VCS Distribuído (DVCS)

Clona o repositório completo, o que inclui o histórico de versões.

- Cada clone é como um backup;
- Possibilita um fluxo de trabalho flexível;
- Possibilidade de trabalhar sem conexão à rede.


O que é o [Git](https://git-scm.com/)?

Sistema de Controle de Versão Distribuído.

- Gratuito e Open Source (Código Aberto);
- Ramificações (branching) e fusões (merging) eficientes;
- Leve e rápido.

Breve Histórico do Git

2002 -> O projeto do núcleo (kernel) do Linux, que é open source, começa a utilizar o BitKeeper, um DVCS proprietário;

2005 -> Após conflitos com a comunidade, o BitKeeper rescinde a licença gratuita. O que leva Linus Torvalds, o criador do Linux, e sua equipe desenvolverem sua própria ferramenta, o Git.

O que é GitHub?

Plataforma de hospedagem e código para controle de versão com Git, e colaboração.

- Comunidade ativa;
- Utilizado mundialmente;
- Mascote "Octocat".

Breve Histórico do GitHub

2008 -> Desenvolvido por Chris Wanstrath, J. Hyett, Tom Preston-Werner e Scott Chacon.

2018 -> Vítima de um dos maiores ataques de DDoS (ataque distribuído de negação de serviço);
Comprado pela Microsoft Corporation por US $ 7,5 bilhões.

Git atua diretamente no banco de versões
GitHub hospeda código

Criando e Clonando Repositórios

Existem duas formas de obter um repositório Git na sua máquina:
1. Transformando um diretório local que não está sob controle de versão, num repositório Git;
2. Clonando um repositório Git existente.

para remover o versionamento de uma pasta basta remover a pasta .git, ex `rm -rf .git`

[Configure git to use 'main' as the primary branch](https://help.dreamhost.com/hc/en-us/articles/4466702078740-Configure-git-to-use-main-as-the-primary-branch)


Trabalhando com Branches

De maneira simplista, uma Branch (em tradução, "Ramo"), é uma ramificação do seu projeto.

- É um ponteiro móvel para um commit no histórico do repositório;
- Quando você cria uma nova Branch a partir de outra existente, a nova se inicia apontando para o mesmo commit da Branch que estava quando foi criada.
