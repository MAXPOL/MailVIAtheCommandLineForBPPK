# Mail VIA the Command Line For BPPK

cd /home/user

apt install fetchmail procmail uudeview

mkdir schedule && mkdir schedule/backup

fetchmail

cd /home/user/schedule/backup

uudeview +e * -i newsfile
