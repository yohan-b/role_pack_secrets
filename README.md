Usage
=====

SECRETS_ARCHIVE_PASSPHRASE=XXXXXXX ansible-playbook -e "user=$USER" -e "WORKDIR=$HOME/secrets" -e "CLOUD_SERVER=cloud.scimetis.net" pack_secrets.yml

