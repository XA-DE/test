# THESE SCRIPTS ARE ONLY FOR UEFI-SYSTEM 

after connecting to net

run the following commands

# for ARTIX

    bash <(curl -s https://raw.githubusercontent.com/XA-DE/scripts/main/artixbase)
   then for network

    ln -s /etc/runit/sv/NetworkManager /run/runit/service/NetworkManager

# for ARCH 
    bash <(curl -s https://raw.githubusercontent.com/XA-DE/scripts/main/archbase)
