# FrOSCon-2017-LaTeX

Materials for my LaTeX course at FrOSCon 2017 

* Some older slides: [http://uweziegenhagen.de/wp-content/uploads/2014/08/Froscon-2014-Folien.pdf](http://uweziegenhagen.de/wp-content/uploads/2014/08/Froscon-2014-Folien.pdf)

## Step 1: What is it all about?
* What is TeX, LaTeX, where does it come from?
* How can I install TeX?
* Which editor should/can I use?
 * Not MS Word!
 * Desired functionality:
	  * UTF-8
	  * Syntax highlighting
	  * Controlling the LaTeX run
  * I like TeXworks, Emacs with AucTeX, Kile, etc.

## Step 2: My first \LaTeX-Document

    \documentclass{article}

    \begin{document}
    
    Hello FrOSCon!
    
    \end{document}


The German expanded version

    \documentclass[12pt,ngerman]{scrartcl}
    
    \usepackage[utf8]{inputenc}
    \usepackage[T1]{fontenc}
    \usepackage{booktabs}
    \usepackage{babel}
    
    \begin{document}
    
    Hallo FrOSCon!
    
    \end{document}

## Step 3: Expanding the document structure (for a thesis)

* Some blindtext from [http://www.blindtextgenerator.de/](blindtextgenerator.de)

Auch gibt es niemanden, der den Schmerz an sich liebt, sucht oder wünscht, nur, weil er Schmerz ist, es sei denn, es kommt zu zufälligen Umständen, in denen Mühen und Schmerz ihm große Freude bereiten können. Um ein triviales Beispiel zu nehmen, wer von uns unterzieht sich je anstrengender körperlicher Betätigung, außer um Vorteile daraus zu ziehen?

Aber wer hat irgend ein Recht, einen Menschen zu tadeln, der die Entscheidung trifft, eine Freude zu genießen, die keine unangenehmen Folgen hat, oder einen, der Schmerz vermeidet, welcher keine daraus resultierende Freude nach sich zieht? Auch gibt es niemanden, der den Schmerz an sich liebt, sucht oder wünscht, nur, weil er Schmerz ist, es sei denn, es kommt zu zufälligen Umständen, in denen Mühen und Schmerz ihm große Freude bereiten können.

Um ein triviales Beispiel zu nehmen, wer von uns unterzieht sich je anstrengender körperlicher Betätigung, außer um Vorteile daraus zu ziehen? Aber wer hat irgend ein Recht, einen Menschen zu tadeln, der die Entscheidung trifft, eine Freude zu genießen, die keine unangenehmen Folgen hat, oder einen, der Schmerz vermeidet, welcher keine daraus resultierende Freude nach sich zieht? Auch gibt es niemanden, der den Schmerz an sich liebt, sucht oder wünscht, nur, weil er Schmerz ist, es sei denn, es kommt zu zufälligen Umständen, in denen Mühen und Schmerz ihm große Freude bereiten können. Um ein triviales Beispiel zu nehmen, wer von uns unterzieht sich je anstrengender körperlicher Betätigung, außer um Vorteile daraus zu ziehen?


* Choosing the right document class
* all the *sections
* Table of contents
* Images and Tables
* Bibliography

## Step 4: Math

* Basic math
* more math

## Presentations with Beamer

* basic presentations
* presentation styles ([http://deic.uab.es/~iblanes/beamer_gallery/](http://deic.uab.es/~iblanes/beamer_gallery/))



## More TeX-topics

* Integration and Interaction
* Code-Inclusion