# DIO | Resumos Git e GitHub

Repositorios para aramazenar resumos sobre Git e GitHub sobre o curso de versionamento de codigoo com Git e GitHUB da [Digital innovation One](https://www.dio.me/)

## 📚 Documentação
- [Documentação GIT](https://git-scm.com/docs)
- [Documentaçao GitHub](https://docs.github.com/pt)

## Resumo Git : 
É um sistema de versao distruibuido gratuito e openSource , um exemplo mais cotidiano é como se fosse um album de fotos.
salva o historico do codigo no PC.

## Working area
 Working Area (Working Directory / Diretório de Trabalho)
É a pasta do seu projeto no sistema de arquivos do computador, onde você visualiza e edita os arquivos diretamente no seu editor de código (como VS Code ou IntelliJ).

- O que acontece aqui: Quando você cria, modifica ou deleta um arquivo, essas alterações acontecem no Working Area.
- Estado das alterações: O Git detecta que os arquivos foram alterados, mas eles ainda não estão sendo rastreados formalmente para uma versão.
- Comando para ver o status: git status (mostra os arquivos modificados em vermelho).

## Staging Area(Ou Index)
É uma zona intermediária ou "área de preparação". Ela funciona como um ambiente onde você seleciona e organiza exatamente quais alterações quer incluir no seu próximo salvamento (commit).

- O que acontece aqui: Você escolhe arquivos específicos do Working Area e os envia para a Staging Area. Isso permite agrupar apenas as mudanças relevantes antes de confirmar a versão
- Por que existe: Permite criar commits limpos e organizados. Por exemplo, se você alterou 5 arquivos, mas apenas 2 fazem parte de uma correção de bug, você envia apenas esses 2 para a Staging Area.
- Comando para enviar arquivos: git add nome_do_arquivo ou git add . (mostra os arquivos em verde no git status).

## Repository
É o banco de dados do Git (armazenado no diretório oculto .git). Nele ficam gravados permanentemente todos os snapshots (snapshots de commits), históricos de alterações, mensagens de commit e branches do projeto.

- O que acontece aqui: Quando você faz um commit, o Git pega tudo o que estava preparado na Staging Area e salva como um novo ponto na história do código.
- Estado das alterações: As alterações agora estão salvas de forma segura e possuem um identificador único (hash SHA-1).
- Comando para salvar: git commit -m "Mensagem descrevendo a alteração".
```
Observação Branch:No Git, uma branch (ou "ramificação") é uma linha paralela de desenvolvimento dentro do mesmo repositório.

Ela permite que você se separe da linha principal de código para desenvolver novas funcionalidades, corrigir bugs ou fazer experimentos sem afetar o código principal que já está funcionando.
```

## Observações
```
Commit:serve para registrar e salvar permanentemente um conjunto de alteraçõesde um projeto.
Branch:Uma branch é uma linha independente de desenvolvimento em um projeto é como criar umacopia paralela do codigo.

```

## 👨‍💻Resumo de alguns comandos Git 

| Comandos  | Resumos | 
|-------|---------|
| mkdir | comando de terminal para criar pasta|
|git clone|clona um repositorio Git existente|
|git init|cria um novo repositório do Git em um diretório vazio ou converte um projeto existente em um projeto rastreado pelo controle de versão|
|git commit|grava alterações no repositoiro|
|git log|exibe os registros log do commit|
|git pull| baixa as alterações mais recentes de um repositório remoto (como o GitHub) e as mescla imediatamente com o seu repositório local no seu computador|
| cd    |comando para navegar entre as pastas do computador|
| ls    | usado para listar arquivos e diretorios da pasta atual|
| cat   | usado para exiber o conteudo ,o tipo ou o tamanho do objeto interno do repositoiro|
|git remote add| usado para conectar o seu repositorio local a um repositorio remoto(ex:GitHub)|
|git remote set-url origin|https do repositoiro|
|git status|mostra o estado atual do seu repositorio Git da sua arvore de trabalho|
|ssh-keygen|responsavel por gerar as chaves,caso for usar token|
|cd ~/.ssh|comando para ver as chaves|
|git restore| descarta todas as alterações feitas localmente|
|git commit --amend -m""| alterar a mensagem do commit|
|git reset --soft| desfaz o último commit (ou um commit anterior), mas mantém todas as suas alterações salvas na área de preparação (staging area) e preserva intactos os arquivos no seu computador|
|git reset --mixed|desfaz o último commit (ou um anterior) e tira todos os arquivos da staging area (área de preparação), mas ainda mantém todas as suas alterações salvas na sua pasta de trabalho (working directory).|
|git reset --hard|Ele desfaz o commit, limpa a área de staging e deleta permanentemente todas as alterações dos arquivos na sua pasta de trabalho (working directory)|
|git push -u origin main| é o comando para mandar as coisas do repositorio local para o repositorio remoto|





 
