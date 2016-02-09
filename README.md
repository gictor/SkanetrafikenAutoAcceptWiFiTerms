# SkanetrafikenAutoAcceptWiFiTerms
A small tool/guide for Ubuntu (but can probably be applied to most *nix flavours) to automatically accept terms of agreement when connected to Skånetrafiken WiFi and thereby automattically gain access to the onboard internet.

## How to get started

### Step 1
Figure out the name of your WiFi interface, easily done by the command `ifconfig`. Replace your interface name with the one in the example called `wlp3s0`

### Step 2
Place your modified script in `/etc/network/if-up.d/skanetrafiken` and give it execution permissions by running `sudo chmod +x /etc/network/if-up.d/skanetrafiken` 

### Step 3
Not really a step in particular, but next time you connect to Skånetrafikens WiFi you will automatically gain access
