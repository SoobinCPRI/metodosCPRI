# Métodos de pesquisa e mercado de trabalho
Repositório referente à entrega final da disciplina Métodos de pesquisa e mercado de trabalho, ministrada pelo professor Dalson Figueiredo. O produto consiste em um script de normalização da base de dados criada pelos estudantes da disciplina em Python, além de um relatório com múltiplas visualizações gráficas interativas feito em Power BI.

## Introdução: criação da base
A base de dados foi criada a partir dos dados disponíveis no site da <a href="https://www.camara.leg.br/deputados/quem-sao">Câmara dos Deputados</a>, onde foram recolhidas informações de todos os deputados federais da 56ª legislatura (2019-2022) que possuíam o status de "Em exercício" no momento da construção. No total, foram contabilizados 514 candidatos, cada qual com 4 linhas para separar seus dados por ano. As informações foram coletadas pelos estudantes membros da disciplina: José Egidio, Julia Amâncio, Samuel Melo, Thais Pinheiros e Vinícius Lopes. Os dados foram armazenados em uma planilha do Google Spreadsheets em diferentes páginas por Estado, o arquivo encontra-se disponível neste repositório. <a href="https://github.com/SoobinCPRI/metodosCPRI/blob/main/base_inicial.xlsx">Clique aqui para acessá-lo!</a>

## Normalização da base de dados
Para o produto final da disciplina, nós, José Egidio e Julia Amancio, decidimos aproveitar essa construção e construir um projeto visual em cima dela. Devido à criação da base ter sido feita por muitos autores manualmente, foram encontradas inconsistências que atrapalhariam na manipulação dos dados para a criação de recursos visuais. Para adequá-la aos padrões necessários utilizados o ambiente de desenvolvimento Google Colab para normalizar a base, além de auferir algumas estatísticas gerais que poderiam nos dar insights na construção de filtros visuais. Foi feito o upload de uma segunda versão da base inicial, onde todas as páginas de Excel foram unidas em um arquivo único csv, <a href="https://github.com/SoobinCPRI/metodosCPRI/blob/main/base_unida.csv">clique aqui para ver esse documento</a>. Com esse arquivo em mãos, basta seguir em sequência nosso script no Google Colab em Python <a href="https://github.com/SoobinCPRI/metodosCPRI/blob/main/Produto_Jose_Julia.ipynb">disponível aqui</a> para terminar com a <a href="https://github.com/SoobinCPRI/metodosCPRI/blob/main/base_formatada.csv">base formatada</a>.

## Produto visual
Devido à quantidade de informações, foi criado um relatório com a intenção de sumarizar os dados de forma visual e apontar direcionamentos, como os deputados e partidos que mais proporam, os que mais se ausentaram etc., além disso foram criadas algumas associações de correlação para saber se determinados dados estão relacionados, como partidos que mais discursam são os que mais propõem? Tudo foi construído através do aplicativo Power BI, onde possui layout responsívo e filtros interativos por ano, partido e estado. O relatório se encontra <a href="https://app.powerbi.com/view?r=eyJrIjoiM2Y1NWJjNTQtYThiYS00NWM0LTllMjEtOWMyYzI5YTQ5NDdhIiwidCI6ImUyZjc3ZDAwLTAxNjMtNGNmNi05MmIwLTQ4NGJhZmY5ZGY3ZCJ9&pageName=ReportSection296fc11b9424c389cd59">aqui</a> e ele é atualizado conforme edições no arquivo original.

## Ferramentas utilizadas:
<div style="display: inline_block"><br>
  <img align="center" alt="Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  <img align="center" alt="PowerBI" height="30" width="40" src="https://github.com/microsoft/PowerBI-Icons/blob/main/SVG/Power-BI.svg">
  <img align="center" alt="Excel" height="30" width="40" src="https://github.com/sempostma/office365-icons/blob/master/svg/excel.svg">
</div>

## Glossário para a base de dados
Glossário:
id: chave identificadora de cada observação, tornando-a única.
nome: nome do deputado em exercício.
uf: estado em que o candidato foi eleito.
pla: propostas legislativas de sua autoria.
par: propostas legislativas relatadas.
vnp: votações nominais em plenário.
dp: discursos em plenário.
pp: presenças em plenário.
aup: ausências justificadas em plenário.
aNj: ausências não justificadas em plenário
pcom: presenças em comissões.
ajcom: ausências justificadas em comissões
aNjcom: ausências não justificadas em comissões.
## Integrantes: 

> <table>
  <tbody>
<tr>
    <td><p align="left-center"><b>José Egidio</b></p></td>
    <td><a href="https://github.com/SoobinCPRI" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank" align="center"></a><a href="https://www.linkedin.com/in/josé-egidio-39ab99224" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" align="center"></a></td>
  </tr>
 
<tr>
    <td><p align="left-center"><b>Júlia Amancio</b></p></td>
    <td><a href="" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank" align="center"></a><a href="https://www.linkedin.com/in/julia-amancio" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" align="center"></a></td>
  </tr>


  </tbody>
 </table>
