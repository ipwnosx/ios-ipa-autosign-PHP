Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@ipwnosx 
1
0 0 ipwnosx/ios-ipa-autosign-B2
 Code  Issues 0  Pull requests 0  Actions  Projects 0  Wiki  Security  Insights  Settings
No description, website, or topics provided.
 2 commits
 1 branch
 0 releases
 1 contributor
 MIT
@ipwnosx
ipwnosx Add files via upload
Latest commit
4b34666
now
Type	Name	Latest commit message	Commit time
cfpropertylist	Add files via upload	now
css	Add files via upload	now
img	Add files via upload	now
rsn	Add files via upload	now
LICENSE	Initial commit	7 minutes ago
README.md	Add files via upload	now
index.php	Add files via upload	now
ipaDistrubution.php	Add files via upload	now
 README.md
re-sign-IPA-file-auto
re-sgin ipa file auto from url's :) beta2

Important modifications: The first file to modify the paths Pedrovail paths and folders sgin.sh


#  iPhone Distribution: Taylor Mitchell (xxxxxxx) 
Certificate_Name="iPhone Distribution: xxxxxxx xxxxxx (xxxxxxx)"

# Profile path
Profile_Path="/Users/xxxx/xxxxxx/xxxx/xxx/embedded.mobileprovision"
# Path of application files
IPAS_FOLDER="/Users/xxxxxxx/xxxxx/xxxxxx/rsn/files"

#   Do not change Shit // the number of repetitions desired
DUPLICATS_NUMBER="0"

# Extract path files after signing
OUTPUT_DIR="/xxxxx/xxxxxx/xxxxxx/re-sign-IPA-file-auto"

Modify the command line in the index.php file to match the path of your folders

$ output  =  shell_exec ( ' chmod + x /Users/taylormitchell/Documents/test/rsn/sgin.sh ' ); // this 
$ output  =  shell_exec ( ' /Users/taylormitchell/Documents/test/rsn/sgin.sh ' ); // And this
Please be careful to put the tracks in their correct place to run the signature without problems

Installation on the server
You must reserve a domain and a security certificate from the site

https://www.name.com/

Of course you need to take a security certificate to accept the subdomain if you have many groups

But you buy and book the domain

Changed the IP domains to the IP server from the program mamp pro

And download the security certificate files crt & key and put them in the program mamp by going Pearl ssl box and then learn on the ssl and under this option you will get a path to degrade security certificate files

Note
The tool is still experimental but is working efficiently currently without problems
