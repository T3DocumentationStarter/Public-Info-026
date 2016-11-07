
.. Tip - just do it:
      don't use TABs (= \t, tabulators)
      replace each TAB by *three blanks* (enable RegExp for Search and Replace in your IDE)
      set TAB width and indentation to THREE in your IDE
      set 'Use blanks instead of TABs' in your IDE


.. With the following include we import some definition. We do this in each and every file.
   so we can change the definition at a single place. Use the relative path to the Includes.txt file,
   which may look as well like ../../../Includes.txt for a deeply nested source file.

.. include:: Includes.txt


.. Usually we define 'php' as default highlight language in Includes.txt.
   With the following 'highlight' directive we switch to reStructuredText as default highlight language.

.. highlight:: rst


.. The following, first section (= headline) is the 'Document Title'.


======================
My Public Info Project
======================


.. The following is 'field list' which is rendered as a horizontal table.
   Think of it as key-value pairs.


:Writing here:    `Gernot Ploiner <gp@webprofil.at>`__
:Rendered:        |today|
:Buildinfo:       `buildinfo <_buildinfo>`_
:Others:          `overview <..>`__


.. _Martin: martin.bless@mbless.de

Hallo,

Martin_ hier. Worum geht's?

#. Dies ist dein persönliches TYPO3-Documentation-Starter-Project.
   Mach damit was du willst. Schreib eine Notiz, lösch die Unterordner,
   leg andere Unterordner an, mach alles kaputt: Das ist in Ordnung.

#. Nur Du und ich haben Schreibzugriff.

#. Niemals zuvor war es einfacher, in diesem Format etwas zu schreiben:

   - Du gehst auf die `Website <https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/>`__
     und dort zu DEINEM Projekt.
     
   - Geh z. B. auf die "Hello world!" Seite.
   
   - Drücke "Edit me on Github". Auf Github muss du angemeldet sein und darauf achten, dass du die
     Einladung zur Mitarbeit an diesem Repository auch angenommen hast.
     
   - Dann kommst du sofort zum Editierformular. Schreibe ein Wort und drücke "Save". Dadurch `wird
     gleichzeitig der Docs-Server informiert.`__
     
   - Warte ein, zwei oder drei Minuten. Der Cronjob interessiert sich jede Minute dafür, ob er etwas
     für dich tun kann. Dann mach einen Reload im Browser.
     
     .. note::
     
        Kein Fork, kein Pull Request, keine Commit-Message, keinerlei Installation
        erforderlich! Sehen, ändern, speichern. Und warten - das ist bestimmt das Schwerste.
        Aber nur ganz kurze Zeit.
        
   - Ja, das reST-Format (reStructuredText__) ist 
     schon ganz schön pingelig. Dafür arbeitet es aber auch sematisch, gestaltet den
     Quelltext optimal lesbar und kann Dinge, von denen man sonst nur träumen kann.
     
   - Wenn etwas nicht so funktioniert wie erwartet:
     
     .. tip:: Schau ins Protokoll!

        Jedes Doku-Projekt, dass mit der neuen TYPO3-Documentation_Toolchain gerendert wird,
        erhält auch einen `/_buildinfo` Ordner, den man hier im Web aufrufen kann. Darin ist
        ganz besonders die Datei :file:`warnings.txt` von Interesse, denn sie enthält die
        Sphinx_ Warnungen und Fehlermeldungen.
        
     Hänge also in der Adresszeile des Browsers an die Start-URL deines Projektes ein
     `/_buildinfo/`. Oder füge direkt in deine Doku, zumindest für die Entwicklungszeit,
     einen Link ein: ```buildinfo <_buildinfo>`__`` Der sollte dann so funktionieren: 
     `buildinfo <_buildinfo>`__
     
   - Die Kapitel (=Unterordner) :doc:`Hyperlinks </Hyperlinks/Index>` und
     :doc:`reStructuredText </reStructuredText/Index>` sollen Hilfestellung beim Einstieg
     sein. Sie können natürlich bedenkenlos gelöscht werden.
     
Wenn mir mehr einfällt oder Fragen auftauchen schreibe ich mehr in der
`Mastervorlage des Starter-Projektes`__. Dort kann man also bei Bedarf
reinschauen.

Viel Spaß, viel Erfolg, und bitte: Weitersagen! Wir benötigen möglichst viele Mitstreiter
in der Community, die sich trauen, "Edit me on Github" zu drücken, wenn sie in der Doku
einen Fehler entdecken.

TYPO3 - Inspire people to share!

Martin_

        
        

.. _Sphinx: http://www.sphinx-doc.org/

.. Dies sind anonyme Hyperlinks. Jeder Link im Text, der durch ZWEI anhängende Unterstriche
   gebildet wird, verbraucht den nächsten aus dieser Liste.

__ https://docs.typo3.org/typo3cms/RenderTYPO3DocumentationGuide/ProjectsOnGithub/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/reStructuredText/Index.html
__ https://docs.typo3.org/typo3cms/drafts/github/T3DocumentationStarter/Public-Info-000/


.. toctree::
   :hidden:

   HelloWorld/Index
   Hyperlinks/Index
   reStructuredText/Index

