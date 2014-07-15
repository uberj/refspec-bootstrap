Notes
-----
puppet apply --debug --hiera_config /etc/puppet/hiera.yaml --verbose --modulepath modules/ -e "include mozpuppet::mozprofile::app_a_database"
