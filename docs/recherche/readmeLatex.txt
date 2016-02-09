# Find the pratrice guide on latex edited by Katuitshi-Ntumba 
#

package to install:
	distribution of latex (textlive):
		sudo apt-get install texlive-full
	
	A text editor (texmaker):
		sudo apt-get install texmaker


Prise en mains :
	
	* fichier contenant les erreurs de compilation, fichier ".log"

les instructions Latex:

-Ils commencent  par \{arguments obligatoires}ou[arguments optionnelles]
- les commandes sont sensibles à la casse

Debut du document :

\documentclass[Options: a4paper,11pt]{Classe du document = letter| article|report|book|slides}

\usepackage[latin1]{inputenc}
\usepackage[T1]{fontenc}	#encodage des caractères
\usepackage[francais]{babel}

Corps du document:

commence par :
\begin{document}

se termine par 
\end{document}

A l'interieur de ces commandes on a :


\indent texte
	# indenter un paragraphe

\noindent texte
		# paragraphe sans indentation

\\ texte
	#	nouvelle ligne



###Pour avoir plus de commandes prière de consulter le document pdf >>>> 



