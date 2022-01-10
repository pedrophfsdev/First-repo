# GIT

[Link de download Git](https://git-scm.com/download/win)

## Git e a sua importância

- Git ajuda a criar e monitorar diferentes versões do nosso código, dentro de nossa máquina;

- Git Bash é um terminal estendido para otimizar o uso do Git.

- Benefícios: Controle de versão, Armazenamento em nuvem, Trabalho em equipe; Melhorar seu código; Reconhecimento.

  

## Navegação via command line interface
### Comandos básicos para um bom desempenho no terminal


- branch -M - renomear branch principal
- dir - lista todas as pastas
- cd - navegar entre as pastas (se digitar "cd /" a barra direciona para um caminho específico no diretório C)
- cd .. - retroceder um nível
- cls - limpar a tela
- TAB - completar textos
- mkdir + nome da pasta - criar pasta
- echo - criar arquivo
- ">" - redireciona arquivo
- del + nome da pasta = deletar arquivo
- rmdir = deleta no sistema



## Objetos internos do Git

- Blobs - contém metadados do objeto como tamanho da sting, tipo do objeto, entre outros;
- Tree - armazenam blobs e também contem metadados. A tree monta toda estrutura de localização do arquivo e pode apontar para blobs e para tree;
- Commits - são únicos para cada autor. Aponta para tree e um parente (commit).



# GITHUB



## Criar repositório público:
Acessa o GitHub -> Cria um novo -> adiciona nome -> marca a opção public -> adiciona descrição -> marca a opção Add README

## Clonar do repositório para Desktop:
Clica no Repositório -> Code -> Copia o link -> abre o GitHub na pasta que deseja baixar -> digita 'git clone + link'

## Adicionar para o controle de versão local:
Abre a pasta local no Git -> git status -> git add .

## Empurrar arquivo atualizado para repositório:
git commit -m "incluir descrição da alteração" -> git status -> git push origin main -> git status

## Resolvendo conflitos
Quando o arquivo do repositório for diferente do arquivo local, aparecerá mensagem de erro ao tentar empurra o arquivo da máquina para o reposiitório. Dessa forma é preciso integrar o arquivo local, antes de empurrar para o repositório.
Como integrar:
git pull origin main ->  git status ->
git add * -> git commit -m "texto sobre conflito" -> git push origin master

