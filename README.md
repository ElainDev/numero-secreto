<h1 align="center">Dominando Git e GitHub</h1>

<p align="center">
Este projeto é focado no aprendizado de controle de versão. Aqui aplico os conceitos do curso <b>Git e GitHub: compartilhando e colaborando em projetos</b> da Alura, documentando o fluxo de trabalho profissional com repositórios. 
</p>

<div align="center"> <img src="assets/Em construção.png" width="100px" alt="Status" style="vertical-align: middle;"> <strong style="font-size: 18px;">Status: Praticando Comandos 🛠️</strong> </div>


## 📝 Sobre o Projeto
O objetivo deste repositório é servir como um guia prático de comandos Git. O foco saiu da lógica de código puro e entrou na gestão de como esse código é armazenado, versionado e compartilhado com outros desenvolvedores.

## 🛠️ O que estou praticando:
Fluxo Local: Inicialização de repositórios e controle de estados dos arquivos.

Histórico de Versões: Criação de pontos de restauração (commits) com mensagens claras.

Trabalho Remoto: Conexão do computador local com servidores na nuvem (GitHub).

Sincronização: Envio e recebimento de atualizações de código.

## 🧠 Conhecimentos Adquiridos (Fluxo Git)

| Ação| Comandos | Descrição |
| :--- | :--- | :---  
| **Iniciar** | `git init` | Cria um novo repositório Git local na pasta atual.
| **Monitorar** | `git add`| Adiciona arquivos à "Staging Area" (prepara para o commit).
| **Gravar** | `git commit`| Salva permanentemente as alterações no histórico com uma mensagem.
| **Conectar** | `git remote` | Estabelece o vínculo entre o seu PC e o repositório no GitHub.
| **Enviar** | `git push` | Sobe as suas alterações locais para o servidor remoto.
| **Atualizar** | `git pull` | Traz as alterações do GitHub para o seu computador.


## Anotação 📝
| Sintaxe | Função |
| :--- | :--- |
| git init | Inicializa o rastreamento do Git na pasta. |
| git add . |  Adiciona todos os arquivos modificados para a próxima gravação. |
| git commit -m "msg" | Grava as alterações com uma mensagem descritiva. |
| git -M main | Renomeia a ramificação principal para "main" (padrão atual). |
| git remote add [id] [url] | Vincula um nome (ex: origin) a um link de repositório remoto. |
| git push -u origin main | Envia os arquivos e configura o destino padrão para os próximos pushes. |
| git remote -v | Lista os repositórios remotos conectados e suas URLs. |
| git remote remove [id]| Corta o vínculo com um repositório remoto específico. |
| git remote set-url [id] [URL] | Atualiza o endereço (URL) de um repositório remoto já existente. |
| git status | Mostra quais arquivos foram modificados e o que está pronto para o commit. |
| git log | Exibe o histórico de todos os commits realizados no projeto. |
| git remote | Visualizar os repositórios remotos linkados com o repositório local |
| git push origin main | Envia os seus commits do repositório local (seu computador) para o repositório remoto (GitHub) na ramificação principal (main). |
| git pull origin main | Busca as alterações que estão no repositório remoto e as mescla automaticamente no seu repositório local. É o comando usado para manter seu código atualizado com o que está no GitHub. |
| git clone | Baixar uma cópia de um repositório hospedado no GitHub para o seu computador |

### 🔄 Sincronização com GitHub
* `git push origin main`: Sobe meu trabalho para o servidor.
* `git pull origin main`: Traz as novidades do servidor para minha máquina.


## 🛠️ Como rodar o projeto
Ainda não é necessário instalar nada! Para ver o que já foi feito:

Faça o download ou clone este repositório.

Abra o arquivo index.html em qualquer navegador (Chrome, Edge, Firefox).

<h2 align="center">🤝 Contribuição</h2>
<p align="center">Este é um projeto de estudos. Sinta-se à vontade para dar sugestões ou feedbacks!</p>