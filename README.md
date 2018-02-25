# DLDN-tv-script-generation
Minha solução para o 3 projeto do Curso Deep Learning Nanodegree do Udacity

Neste projeto será utilizado RNN (Rede Neural Recorrente) para gerar um script de um dos episódios de Os Simpsons. A rede utilizará como treinamento partes de alguns episodios das 27 temporadas da série, e como saída a ML retornará um script de um novo episódio. Não estou utlizando GPU, o treinamento será feito em meu próprio notebook. Por isso estou não utilizei muitas EPOCH e utilizei poucos dados para treinamento. 

Para uma melhor acurácia utilize GPU, reduza a quantidade de palavras utilizadas em cada sentença, e utilize mais dados de treinamento

Para realizar este projeto será utilizado:

 - RNN (Rede Neural Recorrente)
 - Tensorflow (versão 1.0 ou acima)
 - Word2Vec
 - Word Embeddings
