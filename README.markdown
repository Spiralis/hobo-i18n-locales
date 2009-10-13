# Welcome to the Hobo-i18n-translations project
This is a complementary site for maintaining different hobo-i18n locale translations. 

## hobo-i18n and locale files
hobo-i18n does not say any thing about how many and which files you add your i18n-keys and translations to. Neither does RoR-i18n, as a matter of fact. Instead the simple convention used in this repository is to collect all hobo-specific-defaults in a single file named hobo.&lt;locale&gt;.yml. 

## Application specific hobo-translations
Additional keys that is a part of your application can be put in any number of files. It is all really up to you. I personally use one single file named app.&lt;locale&gt;.yml to hold application-specific keys.

## RoR-i18n locales
The hobo-i18n project is based on the techniques found in RoR-i18n. So, following traditional RoR conventions, download the applicable locales from http://github.com/svenfuchs/rails-i18n/tree/master/rails/locale/ and put them also in your locales folder.
