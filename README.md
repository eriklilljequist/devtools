# Provisioning of my macbook

## Install system dependencies
Install developer tools such as Git and Homebrew along with transient dependencies
Execute `. .install_system_dependencies` 

## Install 3rd party applications
Edit ansible/play-general.yml and ansible/play-roels.yml to fit your needs.
Execute `. .run_ansible`

## Work behind NTLM proxy
Set varibles:
- DOMAIN in .start_proxy
- PROXY_URL in .start_proxy

Execute `. .start_proxy`
