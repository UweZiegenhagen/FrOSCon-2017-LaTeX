# FrOSCon-2017-LaTeX

Materials for my LaTeX course at FrOSCon 2017 

* Some older slides: [http://uweziegenhagen.de/wp-content/uploads/2014/08/Froscon-2014-Folien.pdf](http://uweziegenhagen.de/wp-content/uploads/2014/08/Froscon-2014-Folien.pdf)

## Step 1: What is it all about?
* What is TeX, LaTeX, where does it come from?
* LaTeX and HTML
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

Hyperref stuff for copy & paste
    
    \usepackage{hyperref}
    \hypersetup{
     bookmarks=true, % show bookmarks bar
     unicode=false,  % non - Latin characters in Acrobat’s bookmarks
     pdftoolbar=true,% show Acrobat’s toolbar
     pdfmenubar=true,% show Acrobat’s menu
     pdffitwindow=false, % window fit to page when opened
     pdfstartview={FitH},% fits the width of the page to the window
     pdftitle={My title},% title
     pdfauthor={Author}, % author
     pdfsubject={Subject},   % subject of the document
     pdfcreator={Creator},   % creator of the document
     pdfproducer={Producer}, % producer of the document
     pdfkeywords={keyword1} {key2} {key3},   % list of keywords
     pdfnewwindow=true,  % links in new window
     colorlinks=true,% false: boxed links; true: colored links
     linkcolor=red,  % color of internal links
     filecolor=cyan, % color of file links
     citecolor=green, % color of file links
     urlcolor=magenta% color of external links
    }




## Step 4: Math

* Basic math
* more math

## Presentations with Beamer

* basic presentations
* presentation styles ([http://deic.uab.es/~iblanes/beamer_gallery/](http://deic.uab.es/~iblanes/beamer_gallery/))



## More TeX-topics

* Integration and Interaction
* Writing letters with scrlttr2
* Code-Inclusion