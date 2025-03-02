# Notes

- Aus <http://www.scribus-user.de/forum/viewtopic.php?f=5&t=219>
 - Utnik sagt: ich würde ein buch nie in scribus schreiben. dafür ist ein textverarbeitungsprogramm wie z.b. libreOffice sicher vorzuziehen.  
   für das layout ist scribus je nach art des buches (siehe fragen von arran) eine sinnvolle option. aus libreOffice lässt sich der text auch mit absatzstilen importieren, falls dies gewünscht wird.
- die lehrerin sagt: Die größten Probleme/Irrwege ergeben sich, wenn man versucht, Scribus wie ein Schreibprogramm zu benutzen. Es ist wichtig für deinen Bekannten, es grundsätzlich als Satzprogramm zu verwenden! 
- Utnik sagt: wenn das buch aus kapiteln oder sonstigen abschnitten besteht, würde ich diese sicher einzeln einfügen und nach jedem abschnitt die rahmenverkettung unterbrechen. bei mehreren huntert seiten in verknüpften textrahmen wird sonst jede änderung auf einer der ersten seiten zu einer kaffeepause…
- die Lehrerin sagt: Keinesfalls würde ich von einem Rohtext in einem Office-Programm ausgehen. Die Korrektur der Übertragungsfehler dauert nach meiner Erfahrung länger als das Setzen aus einer *.TXT-Datei, wenn man die entsprechenden Stile sauber definiert hat und die Textrahmen immer nur kapitelweise verknüpft.
- Creating a running header with the chapter title
  - Sadly, Scribus does not have variable that can be defined with a matching paragraph style.
  - Here is a workaround using Symbols:
    - Create text frame with the correct size and type the current chapter title in there
    - Add the frame to the patterns ("Item > Send to > Patterns"; patterns being a sort of "linked" scrapbook elements)
    - Delete the original text frame with the heading
    - Insert the heading frame from "Window > Symbols" and place it at the correct position
    - Select the text frame and "Item > Duplicate/Transform > Multiple Duplicate > By pages" and let Scribus put the frame on all pages where it is needed.
    - For the next chapter create a new frame that you will add to the "Patterns"
    - By double clicking on the pattern item, you can edit and change the chapter title.
