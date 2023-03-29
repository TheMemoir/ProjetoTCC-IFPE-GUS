# ProjetoTCC-IFPE-GUS
Modelo de Projeto de TCC para cursos de graduação - IFPE Garanhuns

## Descrição 
O modelo foi elaborado utilizando a classe `Memoir` e organizado para ser executado no [Overleaf](https://pt.overleaf.com/) ou em alguma distribuição Latex (MikTex, TexLive, MacTex) que tenha os principais pacotes do modelo instalados (em particular, o [abntex](https://www.abntex.net.br/)).

**OBS.:** Particularmente uso o [TexLive](https://www.tug.org/texlive/) completo (texlive-scheme-full, no OpenSuse); não sei como fazer no Ruindows e um Mac é muito caro para comprar e testar a instalação :yum: .

## Estrutura
O projeto contém:
1. uma pasta para imagens `img`: você deve salvar todas as imagens (caso as use) do projeto nesta pasta e apontar o caminho da seguinte forma: `{img/imagem.png}`;
2. o arquivo `definitions.tex` onde estão todos os pacotes e os comandos e ambientes para o modelo. Não estão incluídos nesse arquivo os elementos pré-textuais que devem ser preenchidos (autor, orientador, etc). Esses estão no arquivo `pretxt.tex` (ver a seguir)
3. o arquivo `pretext.tex` onde estão os comandos que devem ser preenchidos pelo autor do trabalho. Apenas os comandos `\author, \title, \date` (linhas de 1 até 6) e `\orientador` (linha 51) devem ser preenchidos. No comando `\date`, mudar somente o mês.
   * Caso esse modelo seja usado também pelo curso de Engenharia Elétrica do Campus, alterar o comando `\curso`(linha 12). Se for utilizado apenas para o curso de ADS, não mudar nada exceto indicado acima.
4. o arquivo `main.tex` que é o arquivo onde se deverá digitar o trabalho, logo abaixo da linha comentada `%Início do texto`. Compile esse modelo primeiro para gerar o pdf para que sirva de referência. Em seguida, apague seu conteúdo.
5. o arquivo `postext.tex` onde se deve incluir anexos e apêndices (dois itens pós-textuais incluídos). Caso não utilize nem anexo nem apêndice, comentar (colocar um sinal de porcentagem (`%`) na linha 429 (`\input{postext.tex}`).
6. o arquivo `references.bib` onde todas as referências do projeto devem ser incluídas. Notar que nesse arquivo estão modelos dos principais tipos de referências, bastando somente copiar e colar o tipo de entrada para preenchimento com as referências utilizadas no trabalho.

## Documentação dos pacotes que deve ser consultada em caso de dúvida:

* `abntex2cite` disponível [aqui](https://linorg.usp.br/CTAN/macros/latex/contrib/abntex2/doc/abntex2cite-alf.pdf), [aqui](https://linorg.usp.br/CTAN/macros/latex/contrib/abntex2/doc/abntex2cite.pdf) e [aqui](https://www.ctan.org/pkg/abntex2).
* `memoir` (classe no qual o modelo foi elaborado) disponível [aqui](https://www.ctan.org/pkg/memoir)

## Uso do projeto no [Overleaf](https://pt.overleaf.com/)
Após fazer _download_ do arquivo .zip do projeto, siga as etapas abaixo:

1. Crie uma conta no Overleaf;
2. Faça o login;
3. Após aberta a página inicial, clique no botão verde **Novo projeto**;
4. Selecione a opção **Carregar projeto** (não selecione **Importar do GitHub** porque é um recurso _premium_, ou seja, paga-se por isso...);
5. Faça o _upload_ do arquivo .zip e o projeto já estará carregado e pronto para ser usado.
