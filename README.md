# THESE SCRIPTS ARE ONLY FOR UEFI-SYSTEM 

after connecting to net

run the following commands

# for ARTIX-runit
    su
    bash <(curl -s https://raw.githubusercontent.com/XA-DE/scripts/main/artix/runitbase)

then for network

    ln -s /etc/runit/sv/NetworkManager /run/runit/service/NetworkManager

# for ARCH 
    bash <(curl -s https://raw.githubusercontent.com/XA-DE/scripts/main/arch/base)
