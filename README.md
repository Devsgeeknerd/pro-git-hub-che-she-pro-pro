<!-- Título -->
# Git & GitHub

**O que é Git?**

Git é um sistema de controle de versão distribuído, desenvolvido por Linus Torvalds em 2005.

Ele permite que múltiplos desenvolvedores trabalhem simultaneamente em um projeto, minimizando conflitos.

O Git rastreia alterações no código-fonte ao longo do tempo, possibilitando reverter para versões anteriores, comparar modificações e colaborar de forma eficiente.

**Principais Caraterísticas do Git:**

* **Distribuído:** Cada desenvolvedor possui uma cópia completa do repositório, incluindo seu histórico, permitindo trabalho offline.

* **Rastreamento de Alterações:** Registra cada modificação no código, mostrando quem fez a alteração e quando.

* **Branches (Ramificações):** Permite a criação de ramificações para desenvolver novas funcionalidades ou correções sem impactar a versão principal do código.

* **Mesclagem (Merge):** Facilita a combinação de alterações de diferentes ramificações, resolvendo conflitos quando necessários.

**O que é GitHub?**

GitHub é uma plataforma de hospedagem de código-fonte que utiliza o Git como sistema de controle de versão.

Lançado em 2008, o GitHub permite que desenvolvedores colaborem em projetos, compartilhem código e gerenciem repositórios de forma eficiente, oferecendo uma interface web intuitiva.

**Principais Caraterísticas do GitHub:

* **Repositórios:** Criação de repositórios públicos ou privados para armazenar projetos.

* **Colaboração:** Facilita a colaboração através de pull requests, onde alterações propostas podem ser revisadas antes de serem integradas ao projeto principal.

* **Issues:** Sistema de rastreamento de problemas para relatar bugs, solicitar funcionalidades e discutir melhorias.

* **GitHub Actions:** Automação de fluxos de trabalho, como integração continua e entrega contínua (CI/CD).

**Boas Práticas no uso de Git e GitHub:**

* **Commits Frequentes e Significativos:** Realize commits pequenos e frequentes com mensagens claras que expliquem as alterações.

* **Uso de Branches:** Crie branches para novas funcionalidades ou correções, mantendo o branch principal (main ou master) limpo e estável.

* **Pull Requests:** Utilize pull requests para revisar e discutir alterações antes de mesclá-las ao branch principal.

* **Mensagens de Commit Claras:** Escreva mensagens que expliquem o "o que" e "por que" das alterações.

* **Documentação:** Mantenha uma documentação clara e atualizada, incluindo um arquivo README que explique como configurar e usar o projeto.

* **Gerenciamento de Issues:** Utilize o sistema de issues do GitHub para rastrear bugs e solicitações de funcionalidades, organizando o trabalho e priorizando tarefas.

* **Revisão de Código:** Incentive a revisão de código entre os membros da equipe para melhorar a qualidade do código e promover aprendizado.

* **Sincronização Regular:** Mantenha seu repositório local sincronizado com o remoto, usando `git pull` regularmente.

* **Tags e Releases:** Use tags para marcar versões específicas do projeto, facilitando o gerenciamento de versões e a comunicação sobre novas funcionalidades ou correções.

* **Segurança:** Evite armazenar informações sensíveis no repositório, utilizando arquivos de configuração que não sejam versionados (como `.env`).

| COMANDOS | DESCRIÇÃO |
| :------- | :-------- |
| `git init` | Inicializa um novo repositório Git em um diretório. |
| `git clone <url>` | Cria uma cópia local de um repositório remoto. O <url> pode ser um link para um repositório no GitHub, GitLab, etc. |
| `git status` | Mostra o estado atual do repositório, incluindo arquivos modificados, não rastreados e prontos para commit. |
| `git add <arquivo>` | Adiciona um ou mais arquivos ao índice (staging area) para serem incluídos no próximo commit. |
| `git add .` | Adicionar todos os arquivos modificados. |
| `git commit -m "mensagem"` | Cria um novo commit com as alterações adicionadas ao índice, usando a mensagem fornecida para descrever o commit. |
| `git log` | Exibe o histórico de commits do repositório, mostrando informações como o hash do commit, autor, data e mensagem. |
| `git diff` | Mostra as diferenças entre as alterações não comitadas e a última versão do commit. |
| `git diff <arquivo>` | Mostra as diferenças entre as alterações não comitadas e a última versão do commit em um arquivo específico. |
| `git branch` | Lista todas as branches no repositório. |
| `git branch <nome-da-branch>` | Cria uma nova branch. |
| `git checkout <nome-da-branch>` | Muda para a branch específica. |
| `git checkout -b <nome-da-branch>` | Cria e muda para a nova branch criada. |
| `git merge <nome-da-branch>` | Mescla as alterações da branch especificada na branch atual. |
| `git pull` | Atualiza a branch local com as alterações do repositório remoto. É uma combinação de `git fetch` e `git merge`. |
| `git push` | Envia os commits da branch local para o repositório remoto. |
| `git remote -v` | Lista os repositórios remotos associados ao repositório local, mostrando suas URLs. |
| `` |  |

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fpro-git-hub-che-she-pro-pro&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/pro-git-hub-che-she-pro-pro?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/pro-git-hub-che-she-pro-pro?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/pro-git-hub-che-she-pro-pro?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/pro-git-hub-che-she-pro-pro?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/pro-git-hub-che-she-pro-pro?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
