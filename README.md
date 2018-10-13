# Babylon

apt-get list
    nfs-common
    xdotool
    libdev-ssl
    ftp
    tlp tlp-rdw acpi-call-dkms tp-smapi-dkms acpi-call-dkms ⇐ battery

Command List
    update-rc.d postgresql enable && service postgresql start
    inside MSF ⇒ 
        msfdb init
            CLOSE AND RESTAT msfconsole
        db_rebuild_cache
    curl -sL https://deb.nodesource.com/setup_8.x | apt-get install -y nodejs
    npm install gitbook-cli -g
    wget http://old-releases.ubuntu.com/ubuntu/pool/universe/x/xwatchwin/xwatchwin_1.1.1-2_amd64.deb && sudo dpkg -i xwatchwin_1.1.1-2_amd64.deb && sudo apt-get install -f


    

git clone list
    https://github.com/magnumripper/JohnTheRipper.git #JumboJohn
    https://github.com/rougeth/knocker.git #PortKnocker
    https://github.com/hausec/ADAPE-Script.git # AD & PrivEsc
    https://github.com/theevilbit/ciscot7.git #ciscoPWDecrypt
    https://github.com/EmpireProject/Empire.git #empire # cd Empire && setup/install.sh
    https://github.com/brokensound77/identipy.git #ident-113/tcp 
    https://github.com/pentestmonkey/ident-user-enum.git #ident-113/tcp Priv of service
    https://github.com/SecureAuthCorp/impacket #impacketEnufSaid
    https://github.com/rebootuser/LinEnum # Linux LPE Suggester
    https://github.com/jondonas/linux-exploit-suggester-2 #another LPE Sugester *nix
    https://github.com/lucyoa/kernel-exploits #LinuexExploitList
    https://github.com/SecWiki/linux-kernel-exploits #secwiki CH LPE list
    https://github.com/FuzzySecurity/PowerShell-Suite #PowershellSuite 
    https://github.com/byt3bl33d3r/pth-toolkit #PTH tools (wmi, ps blahblah)    
    https://github.com/danielmiessler/SecLists #wordlists
    https://github.com/SecWiki/windows-kernel-exploits # windows exploits
    https://github.com/brav0hax/smbexec-2 #smbexec tools
    https://github.com/portcullislabs/udp-proto-scanner #udp-proto-scanner
    https://github.com/sensepost/xrdp #XRDP - dependencies xwininfo xwatchwin, xdotool
    
    
    
    for i in $(curl https://github.com/pentestmonkey?tab=repositories | grep codeRepository | cut -d"\"" -f2); do git clone https://github.com$i; done; #cloneptmonkey's entire Repos
