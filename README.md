Sign iOS apps from the link

  Important modifications:
  The first file to modify the paths of the PedroVille and folder paths `` sgin.sh ''
  ``

  # iPhone Distribution: abdaslam abdallah (xxxxxxx) Developer certificate name Example
  Certificate_Name = "iPhone Distribution: xxxxxxx xxxxxx (xxxxxxx)"

  # Profile path
  Profile_Path = "/ Users / xxxx / xxxxxx / xxxx / xxx / embedded.mobileprovision"
  # Path of application files
  IPAS_FOLDER = "/ Users / xxxxxxx / xxxxx / xxxxxx / rsn / files"

  # Do not change Shi // the number of repetitions desired
  DUPLICATS_NUMBER = "0"

  # Extract path files after signing
  OUTPUT_DIR = "/ xxxxx / xxxxxx / xxxxxx / re-sign-IPA-file-auto"

  ``

  Modify the command line in the index.php file to match the path of your folders
  `` php
  $ output = shell_exec ('chmod + x /Users/abdulsalmabdullh/Documents/test/rsn/sgin.sh'); // this
  $ output = shell_exec ('/ Users / abdulsalmabdullh / Documents / test / rsn / sgin.sh'); // This
  ``
  Please be careful to put the tracks in their correct place to run the signature without problems

  # Installation on the server

  You must reserve a domain and a security certificate from the site

  https://www.name.com/

  Of course you need to take a security certificate to accept the subdomain if you have many groups

  But you buy and book the domain

  Changed the IP domains to the IP server from the program mamp pro

  And download the security certificate files crt & key
  And put them in the mamp program
  Go through the ssl checkbox
  Then learn on ssl
  Under this option you will get a path to degrade the security certificate files
  

970 cfpropertylist / CFBinaryPropertyList.php


 Load diff
 Large diffs are not rendered by default.
   586 cfpropertylist / CFPropertyList.php


 Load diff
 Large diffs are not rendered by default.
   742 cfpropertylist / CFType.php
