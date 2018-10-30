GambleDice is an open source GambleCoin Dice game, GambleDice is free to use and distribute.<br>
<br>
== Pre-Requisites ==<br>
Linux<br>
Apache2<br>
PHP<br>
MySQL<br>
gamblecoind<br>
<br>
== Installation ==<br>
<br>
gamblecoind<br>
<br>
1) Install gamblecoind<br>
2) Edit your gamblecoin.conf in ~/.gamblecoin/gamblecoin.conf (you may need to create this) to look like the following, You will need to change the username and pass.<br>
<br>
server=1<br>
rpcuser=Your Username<br>
rpcpassword=Your Password<br>
rpcport=12010<br>
<br>
3) run gamblecoind -daemon<br>
4) let it fully sync to the network before moving on to the next part (or the script will not work)<br>
<br>
GamblecoinDice<br>
<br>
1) Put in a directory of your choice<br>
2) Change to the inc/ directory and change the permissions to 777 (chmod 777 *)<br>
3) Run the script from your prefered web browser and follow the installation instructions on screen<br>
4) Once completed remove the install directory for security reasons<br>
5) You now have access to http://your-server/dice/admin (or wherever you put the dice script)<br>
6) Finally, Deposit your funds using the address on the wallet tab in the admin menu (Depositing your funds to another address will not work and will not show as available casino funds)<br>
<br>
If you have any problems you can create an issue<br>
<br>
Good Luck and have fun running your own casino!<br>
