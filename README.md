# qualissearch
Um script simples para consulta do Qualis em linha de comando

### Uso:

```
$ python3 qualissearch.py -p "Information Security"    # especifica uma string para busca
ISSN		Qualis	Journal name
1615-5262	B1	INTERNATIONAL JOURNAL OF INFORMATION SECURITY (PRINT) (CIÊNCIA DA COMPUTAÇĂO)
1687-417X	B2	EURASIP JOURNAL ON INFORMATION SECURITY (CIÊNCIA DA COMPUTAÇĂO)
1687-4161	B2	EURASIP JOURNAL ON MULTIMEDIA AND INFORMATION SECURITY (PRINT) (CIÊNCIA DA COMPUTAÇĂO)
2076-0930	B2	INTERNATIONAL JOURNAL OF COMMUNICATION NETWORKS AND INFORMATION SECURITY (PRINT) (CIÊNCIA DA COMPUTAÇĂO)
2076-0930	B2	INTERNATIONAL JOURNAL OF COMMUNICATION NETWORKS AND INFORMATION SECURITY (PRINT) (ENGENHARIAS IV)
1615-5262	B2	INTERNATIONAL JOURNAL OF INFORMATION SECURITY (PRINT) (ENGENHARIAS IV)
1687-417X	B2	EURASIP JOURNAL ON INFORMATION SECURITY (INTERDISCIPLINAR)
1615-5262	B2	INTERNATIONAL JOURNAL OF INFORMATION SECURITY (PRINT) (MATEMÁTICA / PROBABILIDADE E ESTATÍSTICA)
2147-0030	B5	INTERNATIONAL JOURNAL OF INFORMATION SECURITY SCIENCE (CIÊNCIA DA COMPUTAÇĂO)
1947-5500	B5	INTERNATIONAL JOURNAL OF COMPUTER SCIENCE AND INFORMATION SECURITY (ENSINO)
1947-5500	C 	INTERNATIONAL JOURNAL OF COMPUTER SCIENCE AND INFORMATION SECURITY (CIÊNCIA DA COMPUTAÇĂO)
1947-5500	C 	INTERNATIONAL JOURNAL OF COMPUTER SCIENCE AND INFORMATION SECURITY (ENGENHARIAS IV)
1947-5500	C 	INTERNATIONAL JOURNAL OF COMPUTER SCIENCE AND INFORMATION SECURITY (IJCSIS) (ENGENHARIAS IV)

```

```
$ python3 qualissearch.py -i 1942-4787    # especifica o ISSN do periódico
ISSN		Qualis	Journal name
1942-4787	A2	WILEY INTERDISCIPLINARY REVIEWS: DATA MINING AND KNOWLEDGE DISCOVERY (CIÊNCIA DA COMPUTAÇĂO)
```

### Criando um alias

Adicione a seguinte instrução em seu arquivo ```.bashrc```:

``` alias qsearch="python3 caminho_para_o_script/qualissearch.py" ```
