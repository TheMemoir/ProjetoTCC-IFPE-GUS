# ProjetoTCC-IFPE-GUS
Modelo de Projeto de TCC para cursos de graduação - IFPE Garanhuns

## Descrição 
O modelo foi elaborado utilizando a classe `Memoir` e organizado para ser executado no [Overleaf](https://pt.overleaf.com/) ou em alguma distribuição Latex (MikTex, TexLive, MacTex) que tenham os principais pacotes do modelo instalados (em particular, o [abntex](https://www.abntex.net.br/).

## Estrutura
O projeto contém:
- uma pasta para imagens `img`: você deve salvar todas as imagens (caso as use) do projeto nesta pasta e apontar o caminho da seguinte forma: `{img/imagem.png}`;
- o arquivo `definitions.tex` onde estão todos os pacotes e os comandos e ambientes para o modelo. Não estão incluídos nesse arquivo os elementos pré-textuais que devem ser preenchidos (autor, orientador, etc). Esse estão no arquivo `pretxt.tex` (ver a seguir)
- o arquivo `pretext.tex` onde estão os comandos que devem ser preenchidos pelo autor do trabalho. Apenas os comandos `\author, \title, \date` (linhas de 1 até 6) e `\orientador` (linha 51) devem ser preenchidas. No comando `\date`, mudar somente o mês.
..* Caso esse modelo seja usado também pelo curso de Engenharia Elétrica do Campus, alterar o comando `\curso`(linha 12). Se for apenas para o curso de ADS, não mudar nada exceto indicado acima.
-
