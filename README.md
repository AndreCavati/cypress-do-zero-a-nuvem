# 🌲 Cypress, do Zero a Nuvem ☁️

Projeto Simples, desenvolvido para o Curso da Escola TAT(Talking About Testing)


## Pré-Requisitos

Necessário ter Git, Node.js e npm instalado para clonar e executar o projeto

> Utilizei as seguintes versões **22.17.0**, **10.9.2** e **2.50.0**, de Node.js, npm e git, respectivamente. Recomendo usar as mesmas versões ou versões mais recentes de suporte de longo prazo (LTS) dos sistemas listados.

## Instalação

* [Node.js](https://nodejs.org/en/download) (22.17.0 no momento da redação deste artigo)
* npm (10.9.2 no momento da redação deste artigo)
* [git](https://git-scm.com/) (2.50.0 no momento da redação deste artigo)
> **Obs. :** Ao instalar o Node.js, o npm é instalado junto.
> **Obs. 2:** Para verificar as versões do Node.js, npm e git instaladas em seu computador, execute o comando node `--version && npm --version && git --version` em seu terminal de linha de comando.


## Testes

Neste projeto, você pode executar os testes no modo desktop ou mobile


### Desktop

Execute `npm test` (ou `npm t` para a versão curta) para executar o teste no modo headless em uma viewport de desktop.

Ou execute `npm run cy:open` para abrir a Cypress App em uma janela de exibição de desktop.


### Mobile

Execute `npm run test:mobile` para executar o teste no modo headless em uma viewport mobile.

Ou execute `npm run cy:open:mobile` para abrir a Cypress App em uma janela de visualização mobile.

---

Projeto feito com ♥ por [André Cavati](https://github.com/AndreCavati), com instrução do professor [Walmir Filho](https://github.com/wlsf82)