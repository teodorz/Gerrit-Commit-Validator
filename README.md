# Gerrit-Commit-Validator
To start using this commit validator hook, add this file in your $site_path/hooks location of your Gerrit instance.

NOTE: Once you have the file added to your Gerrit instance, any change you make to it is going to be instantly applied at a global level.

# Dependencies:
If your Gerrit version is older than 2.13 then you have to add this plugin into your Gerrit instance: https://gerrit-review.googlesource.com/admin/repos/plugins%2Fhooks

If your Gerrit version is 2.13 or newer than use the following command to install the hooks plugin -> java -jar gerrit.war init -d <site_path> --install-plugin=hooks
