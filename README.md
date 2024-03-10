# test-aja

curl -sqL "https://steamcdn-a.akamaihd.net/client/installer/steamcmd_linux.tar.gz" | tar zxvf -
./steamcmd.sh

force_install_dir ./PZ/

login anonymous

app_update 380870 validate
