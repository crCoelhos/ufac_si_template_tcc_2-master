# abntex2-UFAC

Este projeto consiste em uma personalização da classe abnTeX2 para atender aos requisitos dos Trabalhos de Conclusão de Curso (TCC) do curso de Sistemas de Informação da Universidade Federal do Acre (UFAC).

O pacote abntex2-UFAC fornece o arquivo abntex2-UFAC.sty, projetado para ser integrado com o pacote abnTex2, amplamente utilizada no LaTeX, junto com o arquivo abntex2-alf.bst, com alterações da biblioteca abnTex2 para atender requisitos da ABNT modificados em 2023.


## Compatível com as normas ABNT vigentes:

O modelo é parcialmente compatível com as seguintes normas vigentes:

- **ABNT NBR 10520:2023**: Informação e documentação - Citações de organizações e gerais, citações diretas e utilização de termos estrangeiros de origem latina.

O modelo é compatível com as seguintes normas vigentes:

- **ABNT NBR 6022:2018**: Informação e documentação - Artigo em publicação periódica científica - Apresentação
- **ABNT NBR 6023:2002**:  Informação e documentação -  Referência - Elaboração`**`
- **ABNT NBR 6024:2012**: Informação e documentação - Numeração  progressiva das seções de um documento - Apresentação
- **ABNT NBR 6027:2012**: Informação e documentação - Sumário - Apresentação
- **ABNT NBR 6028:2003**: Informação e documentação - Resumo - Apresentação
- **ABNT NBR 6029:2006**: Informação e documentação - Livros e folhetos - Apresentação
- **ABNT NBR 6034:2004**: Informação e documentação - Índice - Apresentação
- **ABNT NBR 10520:2002**: Informação e documentação - Citações
- **ABNT NBR 10719:2015**: Informação e documentação - Relatório técnico e/ou científico - Apresentação
- **ABNT NBR 14724:2011**: Informação e documentação - Trabalhos acadêmicos - Apresentação
- **ABNT NBR 15287:2011**: Informação e documentação - Projeto de pesquisa - Apresentação


## Como utilizar:

O arquivo UFAC-Modelo-TCC.tex contém o código com exemplos e a estrutura necessária para a elaboração de um TCC conforme o modelo do curso de Sistemas de Informação da UFAC, sendo apenas necessário alterar o conteúdo dos arquivos para adequar ao seu trabalho.

Para obter detalhes mais abrangentes sobre a classe abntex2, acesse https://www.abntex.net.br/.

### Dependências do modelo:

A compilação correta do arquivo UFAC-modelo-TCC.tex depende: do arquivo de modificação de dados de estilo abntex2-alf.bst, de um arquivo de configuração de estilo (abntex2-UFAC.sty) e de um arquivo de banco de dados de referências (referencias.bib) e o compilador pdfLaTeX.


## Colaboradores do projeto:
Criador e mantenedor deste trabalho:
[Manoel Limeira](https://github.com/mlimeira).
Contribuidores da versão 1.1 deste trabalho:
[Christopher Saar](https://github.com/crCoelhos), [Victor Alexandre](https://github.com/vyctor922), [Clécio Elias](https://github.com/Cleps).


## Como contribuir com código:

Para contribuir com código-fonte do modelo:

1. Instale a ferramenta de controle de versões [Git](http://git-scm.com/);
1. Faça um ** git clone** do [código-fonte](https://github.com/mlimeira/ufac_si_template_tcc.git) no Github;
1. Mantenha seu repositório local atualizado com o comando **git pull**;
1. Estude o código e faça sua contribuição;
1. Anote no arquivo [README](https://github.com/mlimeira/ufac_si_template_tcc/blob/master/README) as alterações realizadas por você;
* Comente tambem as alterações no próprio código. Veja exemplos nos próprios arquivos. Não é necessário anotar as alterações no cabeçalho dos modelos de documentos. Nesse caso, apenas o faça no arquivo `README`;
1. Envie a sua contribuição ao repositório com **git commit** e **git push**.


## Customizações do abnTeX2 além da nossa:

- [Custumização usando BibLaTeX e abnTeX2](https://github.com/eekBR/ufpr-abntex2): Customização com adaptações consistentes quanto a norma NBR 10520:2023
- [Customizações conhecidas](https://github.com/abntex/abntex2/wiki/Customiza%C3%A7%C3%B5es-Conhecidas): Customizações conhecidas e recomendadas pela equipe do abnTeX2.


<br><br><br>


## Histórico de Modificações:
#### YYYY/MM/DD - v1.9.8**
- Exemplo de correção a ser citada no histórico de modificações.

#### 2024/01/30 - v1.1.0

- Ajuste nas citações para refletir as mudanças introduzidas pela norma NBR 10520:2023 por meio do documento abntex2-alf.bst.
- Ajustes de espaçamentos, comentários, formatação do código e exemplos no texto.
