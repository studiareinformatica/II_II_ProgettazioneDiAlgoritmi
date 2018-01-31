# Progettazione di Algoritmi
#### *2015/2016 · II Anno · II Semestre*

----
## Linee Guida
#### Repository
Il titolo della repository è da mantenere nel formato `NumeroAnno_NumeroSemestre_NomeCorso`. La sua struttura è simile alla seguente:

```bash
I_I_MetodologieDiProgrammazione/
	.git/ # cartella repository git
	.gitignore # file comune a tutte le repo
	LaTeX/
	LICENSE # GNU GPL
	README.md

	./LaTeX:
		.
		..
		chapter01.tex
		chapter02.tex
		chapter03.tex
		#...
		common.tex # file comune a tutte le repo
		main.tex # 'scheletro' del documento
		res/ # immagini, allegati, etc.
```

#### Commit
Per favorire la comprensione di ogni commit da parte di tutti, si consiglia il formato seguente per i *commit messages*:

`nome branch: categoria update: breve descrizione`.

Il nome branch è necessario solo se non si lavora sul `master`.

Esempi:

`lezione: update yyyy-mm-dd`

`mod: aggiornato .gitignore`

`misc: aggiunte foto appunti yyyy-mm-dd`
