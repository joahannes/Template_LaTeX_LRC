# Template_LaTeX_LRC
Modelo de apresentação LaTeX Beamer do Laboratório de Redes de Computadores (LRC) da UNICAMP.

**Contribuidores**:

> [Helder Oliveira](http://www.lrc.ic.unicamp.br/~helder "Helder's Homepage")

> [Joahannes Costa](http://www.lrc.ic.unicamp.br/~joahannes "Joahannes' Homepage")

### Imagens do modelo: ###

<p align="center">
	<img src="https://github.com/joahannes/Template_LaTeX_LRC/blob/master/images/template1.png" border="5" width="600"/>
</p>

<p align="center">
	<img src="https://github.com/joahannes/Template_LaTeX_LRC/blob/master/images/template2.png" border="5" width="600"/>
</p>

### Habilitar exibição de notas: ###

1. Descomentar trecho no arquivo .tex

	```tex
	% \usepackage{pgfpages}
	% \setbeameroption{show notes on second screen}
	```
2. Recompilar o arquivo .tex

3. Instalar o software [dspdfviewer](https://dspdfviewer.danny-edel.de/).

	$ sudo apt-get install dspdfviewer

4. Após instalado, abrir apresentação com o dspdfviewer via terminal

	$ dspdfviewer nome_arquivo.pdf
