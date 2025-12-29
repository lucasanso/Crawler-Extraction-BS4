# Crawler do portal de notícias Estadão
O projeto acima compreende as etapas de ETL

---
### Tecnologias Principais
BeautifulSoup: Obter HTML de cada uma das páginas para realizar o tratamento das informações
Regular Expressions: Para pecorrer o corpo-texto e preencher campos de cada notícia
Pandas: Para tratar os dados e fazer a leitura de arquivos .csv

---
### Artigos secundários
Unidecode: Para padronizar os caracteres e facilitar a identificação de padrões com RE
Pprint: Exibir cada notícia em formato similar ao JSON para facilitar visualização do conteúdo extraído
Requests: Fazer requisições
Os: Verificar existência dos arquivos de salvamento

---
### Como utilizar
Inicialmente, será necessário instalar os requisitos (requirements.txt)
```bash pip install -r requirements.txt```

Após isso, bastará executar o seguinte comando no terminal
```bash python app.py```

