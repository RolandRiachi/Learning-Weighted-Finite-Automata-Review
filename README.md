Picture an owner of a shipping company trying to study the logistics of their business; profit gener-ated by a shipment would depend largely on the kind of good being transported, its origin, and itsdestination.  With potentially infinite choices of delivery routes, the owner would likely be interestedin a finite, ideally minimal, description of possible profits.

This desire to model quantitative systems is what motivates the study of learning weighted finiteautomata (WFA). In fact, algorithms to design WFAs mimicking such systems boast applications inmany fields; for example, image processing [25, 30], speech recognition [29, 31, 35], speech synthesis[1,  38],  phonological  and  morphological  rule  compilation  [26,  27,  33],  parsing  [32],  bioinformatics[2, 20], sequence modeling and prediction [19], formal verification [3], optical character recognition[16], and more.

In this paper we report some techniques for learning WFAs reviewed by Balle and Mohri [7].The  goal  is  to  illustrate  some  relatively  new  approaches  to  the  problem  (namely,  learning  WFAsfrom queries [13, 14], learning stochastic WFAs from i.i.d.  samples [6, 24], and a learning WFAs -not necessarily probabilistic - from finite string-value pair samples [10]), to clarify some proofs andto provide hopefully insightful intuition into the motivations and definition behind each technique.

References:
[1]  Allauzen, C., Mohri, M., Riley, M.:  Statistical modeling for unit selection in speech synthesis.In:  Proceedings of ACL (2004)

[2]  Allauzn,  C.,  Mohri,  M. Talwalkar,  A.:  Sequence kernels for predicting protein essentiality. In:Proceedings of ICML (2008)

[3]  Aminof, B., Kupferman, O., Lampert, R.:  Formal analysis of online algorithms. In:  Proceedingsof AVA (2011)

[4]  Angluin, D.:  Learning regular sets from queries and counterexamples. Information and compu-tation 75(2) (1987)

[5]  Bailly, R.:  Méthodes spectrales pour l’inférence grammaticale probabiliste de langages stochas-tiques rationnels. Ph.D. thesis, Aix-Marseille Université (2011)

[6]  Bailly,  R.,  Denis,  F.,  Ralaivola,  L.:  Grammatical inference as a principal component analysisproblem. In:  Proceedings of ICML (2009)

[7]  Balle, B., Mohri, M.:  Learning Weighted Automata. Springer (2015)

[8]  Balle, B. Mohri, M.:  On the Rademacher complexity of weighted automata. In:  Proceedings ofALT (2015)

[9]  Balle,  B.:  Learning Finite-State Machines:  Statistical and Algorithmic Aspects. Ph.D. thesis,Universitat Politecnica de Catalunya (2013)

[10]  Balle, B., Mohri, M.:  Spectral learning of general weighted automata via constrained matrixcompletion. In:  Proceedings of NIPS (2012)

[11]  Beimel, A., Bergadano, F., Bshoutty, N.H., Kushilevitz, E., Varricchio, S.:  On the applicationsof multiplicity automata in learning. In:  Proceeding FOCS (1996)

[12]  Beimel, A., Bergadano, F., Bshoutty, N.H., Kushilevitz, E., Varricchio, S.:  Learning functionsrepresented as multiplicity automata. Journal of the ACM 47(3) (2000)

[13]  Bergadano, F., Varricchio, S.: Learning behaviors of automata from multiplicity and equivalencequeries. In:  Proceedings of CIAC, vol. 778. Springer (1994)

[14]  Bergadano, F., Varricchio, S.: Learning behaviors of automata from multiplicity and equivalencequeries. SIAM Journal on Computing 25(6) (1996)

[15]  Bisht,  L.,  Bshouty,  N.H.,  Mazzawi,  H.:  On  optimal  learning  algorithms  for  multiplicity  au-tomata. In:  Proceedings of COLT (2006)

[16]  Breuel, T.M.:  The OCRopus open source OCR system. In:  Proceedings of IS&T/SPIE (2008)

[17]  Cardon, A., Crochemore, M.:  Détermination de la représentation standard d’une série recon-naissable. ITA 14(4), 371-379 (1980)

[18]  Carlyle, J.W., Paz, A.,:  Realizations by stochastic finite automata. J. Comput. Syst. Sci. 5(1)(1971)

[19]  Cortes, C., Haffner, P., Mohri, M.: Rational kernels: Theory and algorithms. Journal of MachineLearning Research 5 (2004)

[20]  Durbin, R., Eddy, S.R., Krogh, A., Mitchison, G.J.: Biological Sequence Analysis: ProbabilisticModels of Proteins and Nucleic Acids. Cambridge University Press (1974)

[21]  Fazel,  M.:   Matrix  rank  minimization  with  applications.  Ph.D.  thesis,  Standford  University(2002)

[22]  Fliess, M.:  Matrices de Hankel. Journal de Mathématiques Pyres et Appliquées 53 (1974)

[23]  Golub, G., Loan, C.V.:  Matrix Computations. John Hopkins University Press (1983)

[24]  Hsu, D., Kakade, S.M., Zhang, T.:  A spectral algorithm for learning hidden markov models.In:  Proceedings of COLT (2009)

[25]  II, K.C., Kari, J.:  Image compression using weighted finite automata. Computers & Graphics17(3) (1993)

[26]  Kaplan, R.M., Kay, M.:  Regular models of phonological rule systems. Computational Linguis-tics 20(3) (1994)

[27]  Karttunen, L.:  The replace operator. In:  Proceedings of ACL (1995)

[28]  Kiefer, S., Marusic, I. Worrell, J.:  Minimisation of multiplicity tree automata.:  In:  Proceedingsof FOSSACS (2015)

[29]  Mohri, M.: Finite-state transducers in language and speech processing. Computational Linguis-tics 23(2) (1997)

[30]  Mohri,  M.:  Weighted  automata  algorithms.  In:  Handbook  of  Weighted  Automata.  Springer(2009)

[31]  Mohri, M., Pereira, F., Riley, M.:  Speech recognition with weighted finite-state transducers. In:Handbook on Speech Processing and Speech Comm. Springer (2008)

[32]  Mohri, M., Pereira, F.C.N.:  Dynamic compilation of weighted context0free grammars. In:  Pro-ceedings of COLING-ACL (1998)

[33]  Mohri, M., Sproat, R.:  An efficient compiler for weighted rewrite rules. In:  Proceedings of ACL(1996)

[34]  Mornhinweg, D., Shapiro, D.B., Valente, K.:  The principal axis theorem over arbitrary fields.American Mathematical Monthly (1993)

[35]  Pereira,  F.,  Riley,  M.:   Speech  recognition  by  composition  of  weighted  finite  automata.  In:Finite-State Language Processing. MIT Press (1997)

[36]  Schützenberger,  M.P.:   On  a  special  class  of  recurrent  events.  The  Annals  of  MathematicalStatistics 32(4) (1961)

[37]  Schützenberger, M.P.:  On the definition of a family of automata. Information and Control 4(1961)

[38]  Sproat, R.:  A finite-state architecture for tokenization and grapheme-to-phoneme conversion inmultilingual text analysis. In:  Proceedings of the ACL SIGDAT Workshop. ACL (1995)
