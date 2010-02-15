# Welcome to the Hobo-i18n-locales repository
This is the official i18n-locale repository for [Hobo](http://github.com/tablatom/hobo). It focuses on maintaining different i18n-locale translations for use in Hobo. 

This used to be the repository for the hobo-i18n project, but since hobo-i18n was merged into Hobo itself this repository became the official Hobo i18n-locale source.

## Hobo default translations
Hobo does not say any thing about how many and which files you add your i18n-keys and translations to. As a matter of fact - neither does RoR-i18n. The simple convention used in this repository is to collect all hobo-specific-defaults in a single file named hobo.&lt;locale&gt;.yml. 

## Application specific translations
Additional keys that is a part of your application can be put in any number of files. It is all really up to you. I personally use one single file named app.&lt;locale&gt;.yml to hold application-specific keys.

## RoR-i18n locales
The i18n solution for Hobo is based on the techniques found in RoR-i18n. So, following traditional RoR conventions, download the applicable locales from [Sven Fuchs](http://github.com/svenfuchs/rails-i18n/tree/master/rails/locale/) and put them also in your locales folder.
