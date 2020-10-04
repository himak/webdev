# webdev
Ako sa naučiť programovať v PHP za víkend

### Syntax PHP

- PHP

  https://www.tutorialspoint.com/php/php_syntax_overview.htm
  
- na začiatok si pozrite tieto témy:

  Ako písať PHP kód, komentáre
  
  https://www.tutorialspoint.com/php/php_syntax_overview.htm
 
  Premenné
  
  https://www.tutorialspoint.com/php/php_variable_types.htm
  
  Operátory
  
  https://www.tutorialspoint.com/php/php_operator_types.htm
  
  Podmienky
  
  https://www.tutorialspoint.com/php/php_decision_making.htm
  
  Cykly
  
  https://www.tutorialspoint.com/php/php_loop_types.htm
  
  Polia
  
  https://www.tutorialspoint.com/php/php_arrays.htm
  
  Práca s textami (napr. spájanie)
  
  https://www.tutorialspoint.com/php/php_strings.htm
  
  Funkcie
  
  https://www.tutorialspoint.com/php/php_functions.htm


### Nevyhnutné programy pre webdevelopment

- inštalácia lokálneho servera pomocou bezplatnej aplikácie MAMP (nainštaluje server Apache, jazyk PHP a databázový server MySQL)

  Windows
  
  https://www.mamp.info/en/windows/

  masOS
  
  https://www.mamp.info/en/mac/
  
- Editor zdrojového kódu (IDE) **Visual Studio Code**

  https://code.visualstudio.com

### Doplňujúce pogramy

- príkazový riadok (terminál)

  Windows / macOS
  
  https://hyper.is/#installation
  
- **Git** repozitár

  Windows / macOS
  
  https://git-scm.com/downloads

- inštalátor ostatných knižníc **Node.js a NPM**

  Windows / macOS
  
  https://nodejs.org/en/download/
  
- inštalátor PHP knižníc **Composer**
  
  Windows
  
  https://getcomposer.org/doc/00-intro.md#installation-windows
  
  Mac
  
  https://getcomposer.org/doc/00-intro.md#installation-linux-unix-macos
  
  
# Prvá webová stránka

Po nainštalovaní lokálneho servera MAMP, si vytvorte nový projekt (zložku s názvom **mojweb**) v zložke:

    C:/MAMP/htdocs
    C:/MAMP/htdocs/mojweb

Zložku si otvorte v programe Visual Studio Code a vytvorte si nový súbor **index.php**. Do tohto súboru si môžete písať PHP kód, napr.

    <?php

          echo 'Moja web stranka';

    ?>
  
Ulože obsah súboru index.php s PHP kódom a otvorte si v prehlidači URL adresu:

    http://localhost/mojweb
  
  Zobrazí sa stránka s textom **Moja web stranka**
