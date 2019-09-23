# autoYamlTranslate
## goal  
to allow for easy automatic translation of yaml file used for eu4 modding.

## setup  
rename `service-account-file-example.json` into `service-account-file.json`, and put into it
the content of the file genrated by https://cloud.google.com/translate/docs/quickstart-client-libraries on the
 *configure a project* button.

## example usage
if you run `python translater.py originalYmlExample.yml translatedYmlExample.yml en fr 500`, you'll translate the
originalYmlExample.yml into a translatedYmlExample.yml, but only for the first 500 characters, and from english to french.
 