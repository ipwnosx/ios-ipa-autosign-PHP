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
The first Arabic tool to and sign iOS applications from the link

Important modifications: The first file to modify the paths Pedrovail paths and folders sgin.sh


#  iPhone Distribution: abdaslam abdallah (xxxxxxx) اسم شهادة المطورين مثال
Certificate_Name="iPhone Distribution: xxxxxxx xxxxxx (xxxxxxx)"

# مسار بروفايل
Profile_Path="/Users/xxxx/xxxxxx/xxxx/xxx/embedded.mobileprovision"
#مسار ملفات التطبيقات
IPAS_FOLDER="/Users/xxxxxxx/xxxxx/xxxxxx/rsn/files"

#   لا تغير شي// عدد التكرارات المرادة
DUPLICATS_NUMBER="0"

# مسار استخراج الملفات بعد التوقيع
OUTPUT_DIR="/xxxxx/xxxxxx/xxxxxx/re-sign-IPA-file-auto"

Modify the command line in the index.php file to match the path of your folders

$ output  =  shell_exec ( ' chmod + x /Users/abdulsalmabdullh/Documents/test/rsn/sgin.sh ' ); // this 
$ output  =  shell_exec ( ' /Users/abdulsalmabdullh/Documents/test/rsn/sgin.sh ' ); // And this
Please be careful to put the tracks in their correct place to run the signature without problems

Installation on the server
You must reserve a domain and a security certificate from the site

https://www.name.com/

Of course you need to take a security certificate to accept the subdomain if you have many groups

But you buy and book the domain

Changed the IP domains to the IP server from the program mamp pro

And download the security certificate files crt & key and put them in the program mamp by going Pearl ssl box and then learn on the ssl and under this option you will get a path to degrade security certificate files

Note
The tool is still experimental but is working efficiently currently without problems and any problem you face continue to me in Twitter
