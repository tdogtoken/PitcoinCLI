# Pitcoin Network updated as on 12/15/2022, please re-download PitcoinCLI and PitcoinWallet. And re-mine your new Pitcoin. 
# PitcoinCLI(command line interface) Updated : miner, pitcoind(node), simplewallet
# We are going to store and use Pitcoin inside computer of computer (sounds more secure, haha). To get start, please follow below procedure:
1. Download and Install Oracle VM VirtualBOX: https://www.virtualbox.org/wiki/Downloads
2. Download Linux ISO Ubuntu20.04.5 LTS:  https://releases.ubuntu.com/20.04.5/?_ga=2.256257410.804221981.1664673186-251296044.1663774267
3. Install Unbuntu inside Oracle VM VirtualBOX.
4. After Install Ubuntu, open Terminal Command  type or copy and install dependencies(install one by one): 
 
   sudo apt-get install git
 
   sudo apt-get install make 
 
   sudo apt-get install cmake
 
   sudo apt-get install libboost-all-dev 
 
5. After install all dependencies, git clone PitcoinCLI by type or copy on Terminal Command (run one by one):
   
   git clone https://github.com/tdogtoken/PitcoinCLI.git
   
   ls 
   
   cd PitcoinCLI
   
   chmod +x pitcoind
   
   chmod +x simplewallet
   
   chmod +x miner
   
6. Open more than three Terminal Command, you can go to PicoinCLI folder and right click choose open Terminal.

7. After that, to connect Pitcoin node by type or copy below command run on one of the Terminal:
   
   ./pitcoind
   
8. After you connect to Pitcoin node and create your wallet by type or copy below command run on second Terminal and follow instruction shows on command:
  
   ./simplewallet
  
9. After you connect to Pitcoin node and create your wallet, run on third Terminal type or copy flollowing command to mine:
   
   ./miner --address YourWalletAddressYouCreate
   
   
Store Mine and Transfer Pitcoin Part1:   https://youtu.be/6rdx2x83eF4

Store Mine and Transfer Pitcoin Part2:   https://youtu.be/ZBwNcbYxfBc

Store Mine and Transfer Pitcoin Part3:   https://youtu.be/vlY-swnMwCI

Store Mine and Transfer Pitcoin Part4:   https://youtu.be/tgZbx-UvhZU

Store Mine and Transfer Pitcoin Part5:   https://youtu.be/6g8c247Use8   
