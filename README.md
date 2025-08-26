# Desafio-7-dias-de-codigo-alura
7 days of Python code with Alura

![GitHub repo size](https://img.shields.io/github/repo-size/iuricode/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

Google Colab of this project : https://colab.research.google.com/drive/1XFi3LRofZfBaavlG3U9W3X4R3xDtMdWK#scrollTo=10y5RhmilE3X

### Day 1: import data

```
Join differents datasets

emprestimos_biblioteca = pd.concat([dados_2010_1,dados_2010_2,dados_2011_1,dados_2011_2,dados_2012_1,dados_2012_2,dados_2013_1,dados_2013_2,dados_2014_1,
                                    dados_2014_2,dados_2015_1,dados_2015_2,dados_2016_1,dados_2016_2,dados_2017_1,dados_2017_2,dados_2018_1,dados_2018_2,
                                    dados_2019_1,dados_2019_2,dados_2020_1],ignore_index=True)
emprestimos_biblioteca
   
```

```
Drop duplicates
emprestimos_biblioteca.value_counts()
```

```
Join one more data frame

dados_exemplares = pd.read_parquet('https://github.com/FranciscoFoz/7_Days_of_Code_Alura-Python-Pandas/raw/main/Dia_1-Importando_dados/Datasets/dados_exemplares.parquet')
dados_exemplares

emprestimos_completo = emprestimos_biblioteca.merge(dados_exemplares)
emprestimos_completo
```




### Adjustments and improvements.

The project is still under development, and the upcoming updates will focus on the following tasks:

- [x] Advanced courses about Phyton

The following tools were used in the construction of the project:

- [Python](<https://www.python.org/doc//>)
- [Google colab](<https://colab.google/>)



## 🤝 Creator

<table>
  <tr>
    <td align="center">
      <a href="#" title="Thales Farias">
        <img src="grecia.jpg" width="100" alt="Foto do Thales Farias no GitHub"/><br>
        <sub>
          <b><a href="https://www.linkedin.com/in/thalesfreirefarias/" target="_blank">Thales Farias</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
