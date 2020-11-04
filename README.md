Introdução a Recuperação de Informação Musical
==============

Slides e códigos de exemplo.

Instalação
-----
* eu tô usando Python3.8, mas acho que dá pra rodar usando 3.7 sem problemas
* a `librosa` depende do `ffmpeg`, que é uma dependência do sistema operacional.
então, `sudo apt-get install ffmpeg` pra quem for de ubuntu e `pacman -S ffmpeg`
pra quem for de arch linux.

* no mais:

```console
$ virtualenv venv 			# cria ambiente virtual
$ source venv/bin/activate 		# ativa o ambiente
$ pip install -r requirements.txt	# instala dependências
$ jupyter notebook 			# roda os notebooks
$ deactivate				# quando você quiser parar seu ambiente
```

Diretório
-----
- `audios`: diretório com os áudios. por uma questão de direitos autorais,
tá vazio, mas eu casualmente vou deixar os links dos áudios que baixei aqui
nas referências pra você conseguir baixar também
- `slides`: autoexplicativo
- `autotaggers.ipynb`: alguns exemplos de aplicação do [musicnn](https://github.com/jordipons/musicnn/tree/master/musicnn)
- `sinais_e_representações`: notebook explicativo sobre representações no tempo
e frequência

Referências
-----
músicas usadas nessa palestra (ordem alfabética):
* [Calcinha Preta - Cobertor](https://www.youtube.com/watch?v=U7gvTUe7m-E)
* [Chico Science e Nação Zumbi - A Praieira](https://www.youtube.com/watch?v=jE6p22nz7CU)
* [Escape The Fate - Ungrateful](https://www.youtube.com/watch?v=6kDUZs5tiYM)
* [Gloria Groove - Coisa Boa](https://www.youtube.com/watch?v=2T9b47ZtwQU)
* [MC Rebecca - Ao Som do 150](https://www.youtube.com/watch?v=R11tF-QgY0c)
* [Tom Jobim - Garota de Ipanema](https://www.youtube.com/watch?v=WuenyQ4NCQE)
