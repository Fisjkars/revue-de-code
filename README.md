# revue-de-code

https://fisjkars.github.io/revue-de-code/

I. Introduction de la revue de code. 
	- Rappel sur les bonnes pratiques de codage : Versionning, Coding style, CI/CD, etc…
	- Correction de bug fonctionnel/technique/performance.
	- Compréhension d’un code existant.
	- Audit de sécurité.

II. Les outils d’analyse de code.
	- Automatique                            : Sonarqube, Semgrep, Checkstyle, Junit, Cobertura…
	- Manuel                                     : Note, PoiEx, Github copilot.
	- Debugger & Instrumentation : Comment debugger des applications. (Java, .Net, C/C++)
	- Decompilation                         : (Java, .Net, C/C++)

III. Audit de code dans un contexte de sécurité.
	- Analyse en profondeur.
		- Recherche de points d’entrées sur les langages/frameworks courants web (Java, Python, PHP)
		- Recherche de points d’entrée sur des clients lourds windows/linux (optionnel)
	- Analyse par classe de vulnérabilités.
		- Vulnérabilités techniques : OS Command Injection, XXS, XXE, Deserialization, Crypto.
		- Vulnérabilités logiques     : Broken Access Control, Soft failure etc…


TP.1 (Adaptation aux capacités des filières) : 
Création d’un jeu tests unitaires avec validation de couverture de tests, corrections de checkstyle, proposition de fixs  sur Github.
Analyse de performance, detection de bottleneck => Corrections
  
TP.2 :
Analyse d’un JAR « cadenassé » :
- Decompilation Java & C (JNI).
- Debug.
- Analyse comportementale.
- Description du fonctionnement de l’application.

TP.3,4,5 : CTF 
Capture The Flag : Plusieurs challenges sécurité type whitebox/reverse
