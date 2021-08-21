Mass Network TESTNET Autorun Script on Ubuntu

How to install

Open the armbian terminal.
enter the command below
wget -L https://github.com/adipramono404/mass-node-run/blob/main/mass-node-run.sh
edit the miner.sh file that was downloaded earlier.
nano mass-node-run.sh.
type the command below in terminal, to edit crontab
crontab -e
add script below
@reboot bash /root/mass-node-run.sh > /root/mass-node.log 2>&1
Save and stop. By pressing the CTRL + X key, press the Y key and enter.
