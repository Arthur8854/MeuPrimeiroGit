# Meu primeiro git
# Arthur Stradioto da Silva

Projeto utilizado para aprender git
## Estrutura do projeto

O projeto possui documentação na pasta `docs`
e páginas HTML e arquivos CSS na pasta `src`.

## Desenvolvimento

Até o momento foram desenvolvidas:
git
- Estrutura inicial do projeto;
- Documentação dos produtos;
- Página de produtos;
- Estilização inicial;
- Página de pedidos;
- Documentação dos pedidos.

## Questionário

### 1. Qual é a diferença entre Working Directory, Staging Area e Repository?

O Working Directory é a pasta onde estão os arquivos que estamos
alterando durante o desenvolvimento.

A Staging Area é a área onde colocamos os arquivos que serão
incluídos no próximo commit através do comando `git add`.

O Repository é onde ficam armazenados os commits e o histórico
das versões do projeto.

### 2. Qual é a diferença entre git commit e git push?

O `git commit` salva as alterações no repositório local,
criando um ponto no histórico do projeto.

O `git push` envia os commits que estão no repositório local
para o repositório remoto, como o GitHub.

### 3. É possível realizar vários commits antes de executar um git push? Explique.

Sim. É possível realizar vários commits localmente antes de
executar o `git push`.

Quando o push for executado, os commits que ainda não foram
enviados serão enviados para o repositório remoto.

### 4. Por que é interessante realizar commits pequenos e descritivos?

Porque commits pequenos facilitam a compreensão do histórico
do projeto. Mensagens descritivas também ajudam a identificar
facilmente qual alteração foi realizada em cada versão.

### 5. O que acontece com os commits locais quando ainda não executamos o git push?

Os commits continuam armazenados no repositório local. Eles não
são perdidos apenas porque ainda não foram enviados para o GitHub.

Eles serão enviados posteriormente quando executarmos o comando
`git push`.

### 6. Como verificar, pelo GitHub, se os commits foram enviados corretamente?

Podemos acessar o repositório no GitHub e verificar o histórico
de commits. Também podemos conferir se os arquivos e alterações
realizadas estão disponíveis no repositório remoto.