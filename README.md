<h1 align="center">  Implementação de Técnicas de Remoção de Ruído para
Reconstrução de Dados de Pticografia
  
## Índice 

* [📝 Detalhes do Projeto](#detalhes-do-projeto)
* [📁 Acesso ao projeto](#acesso-ao-projeto)
* [👩‍💻 Desenvolvedores do Projeto](#desenvolvedores-do-projeto)
* [📚 Referências](#referências)

## 📝Detalhes do Projeto

A pticografia é uma técnica de imageamento por difração que possibilita a reconstrução da fase da
imagem a partir de padrões de difração obtidos através da varredura de regiões de uma amostra. Nessa
técnica, ocorre a interação entre a onda incidente (probe), e o objeto, gerando uma onda de saída em que
a fase é perdida durante a detecção. O PIE (do inglês, Ptychographical Iterative Engine) e suas variações,
o ePIE (extended PIE) e o rPIE (regularized PIE), são algoritmos que possibilitam a recuperação da fase
em diferentes condições experimentais. No entanto, os padrões de difração medidos são contaminados
por diferentes fontes de ruído, impactando na qualidade da reconstrução da imagem. Neste trabalho,
foram considerados os ruídos de Poisson e Gaussiano, os quais representam, respectivamente, ruídos
relacionados à contagem de fótons e ruídos da medida do detector. Assim, para reduzir os efeitos desses
ruídos e preservar as estruturas das imagens reconstruídas, foi utilizado o filtro guiado (guided filter).
Essa técnica realiza a suavização dos ruídos preservando as bordas. Os resultados obtidos mostraram que
o algoritmo rPIE apresentou um desempenho melhor na reconstrução da fase quando comparado ao PIE
e ao ePIE. Além disso, o filtro guiado foi aplicado de duas maneiras distintas, sendo elas (I) diretamente
às imagens afetadas pelos ruídos, com o objetivo de avaliar a capacidade de redução de ruído e (II)
implementado junto ao rPIE. Os resultados indicam que a implementação do filtro guiado pode auxiliar
na reconstrução de dados ruidosos, mas sua eficiência depende dos parâmetros utilizados.

## 📁Acesso ao projeto

Para ver o projeto você pode acessar os arquivos abaixo:
- [Código PIE](https://github.com/Eloisa-Souza/Tecnicas-de-remocao-de-ruido-para-pticografia/blob/main/IP_IV_PIE_ePIE_rPIE.ipynb)
- [Código filtro]()

## 👩‍💻Desenvolvedores do Projeto

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/172425341?s=400&u=27f1f6f0257dfea068b3b763758914d077f15952&v=4" width=115><br><sub>Eloisa Maria Amador Souza</sub>](https://github.com/settings/profile) |  

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/65614037?v=4" width=115><br><sub>Emanuel Piveta Pozzobon</sub>](https://github.com/empipo) |  


## 📚Referências

[1] JACOBSEN, Chris. X-ray microscopy. Cambridge: Cambridge University Press, 2020. \textbf{(Advances in Microscopy and Microanalysis)}. DOI: https://doi.org/10.1017/9781139924542

[2] KONIJNENBERG, S. An introduction to the theory of ptychographic phase retrieval methods. \textbf{Advanced Optical Technologies}, v. 6, n. 6, p. 423–438, 2017. DOI: https://doi.org/10.1515/aot-2017-0049

[3] DIEROLF, Martin. Ptychographic X-ray computed tomography at the nanoscale. \textbf{Nature}, v. 467, p. 436-439, 2010. DOI:  https://doi.org/10.1038/nature09419

[4] VAN DER WALT, S. et al. scikit-image: image processing in Python.\textbf{PeerJ}, v. 2, e453, 2014. DOI: https://doi.org/10.7717/peerj.453

[5] HE, Kaiming; SUN, Jian; TANG, Xiaoou. Guided image filtering. IEEE Transactions on Pattern Analysis and Machine Intelligence, v. 35, n. 6, p. 1397–1409, jun. 2013. DOI: 10.1109/TPAMI.2012.213

[6] QIAO, Ziling; WEN, Xiu; ZHOU, Xuyang; QIN, Feng; LIU, Shutian; GAO, Bin; LIU, Wei; CHI, Dazhao; LIU, Zhengjun. Adaptive iterative guided filtering for suppressing background noise in ptychographical imaging. Optics and Lasers in Engineering, v. 160, art. 107233, jan. 2023. DOI: 10.1016/j.optlaseng.2022.107233.

[7] HUANG, Mingsheng; ZHU, Yanghang; DUAN, Qingwu; ZHU, Yaohua; JIANG, Jingyu; ZHANG, Yong. Adaptive Guided Filtering and Spectral-Entropy-Based Non-Uniformity Correction for High-Resolution Infrared Line-Scan Images. Sensors, v. 25, n. 14, art. 4287, 2025. DOI: 10.3390/s25144287.

[8] RODENBURG, John; MAIDEN, Andrew. Ptychography. In: HAWKES, Peter W.; SPENCE, John C. H. (ed.). Springer Handbook of Microscopy. Cham: Springer, 2019. p. 819–904. DOI: {10.1007/978-3-030-00069-1\_17}

[9] ABE, Masaki; TAKAZAWA, Shuntaro; UEMATSU, Hideshi; SASAKI, Yuhei; OKAWA, Naru; ISHIGURO, Nozomu; TAKAHASHI, Yukio. Guided-image-filtering-assisted phase retrieval for amplitude reconstruction in single-frame coherent diffraction imaging. Optica, v. 11, n. 12, p. 1832–1840, dez. 2024. DOI: 10.1364/OPTICA.537748.

[10] MAIDEN, Andrew; JOHNSON, Daniel; LI, Peng. Further improvements to the ptychographical iterative engine. Optica, v. 4, n. 7, p. 736–745, jul. 2017. DOI: 10.1364/OPTICA.4.000736
