# Translations for K-Manager and K-Klock


# Contribute

* Fork or download this repo
* Find the localisation code for the language you want to translate. 
  * [See here.](https://stackoverflow.com/a/12735102) 
  * Only the part before the underscore is needed in most cases. For example, French would be fr.
  * To specify a region use the form xx-rXX. For example, French, Canada (fr_CA) would be fr-rCA.
* Make a new folder called values-<localisation>. For example, values-fr
* Copy all the files from the values folder into your values-<localistion> folder.
* Open the files and translate everything inside <xyz></xyz> tags.
  * %s is a placeholder for a word. 
  * Don't change the order of tags.
  
# Keep Up-to-Date

You can subscribe to this repo to get notified if I add new strings.
I will add them to every folder with a TODO comment before them to make them easy to find.
For example:
```
<!-- TODO -->
<string name="foo">Lorem ipsum dolor sit amet</string>
```
