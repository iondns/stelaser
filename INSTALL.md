See [doc/build-\*.md](/doc)

wget https://stelaser.com/wp-content/uploads/CMC.zip

find . -type f -print0 | xargs -0 sed -i 's/cpuminerscoin/stelasercoin/g'
find . -type f -print0 | xargs -0 sed -i 's/Cpuminerscoin/stelasercoin/g'
find . -type f -print0 | xargs -0 sed -i 's/CpuminersCoin/stelasercoin/g'
find . -type f -print0 | xargs -0 sed -i 's/CPUminerscoin/stelasercoin/g'
find . -type f -print0 | xargs -0 sed -i 's/CPUMINERSCOIN/stelasercoin/g'
find . -type f -print0 | xargs -0 sed -i 's/CMC/STELASER/g'

find . -type f -print0 | xargs -0 sed -i 's/cpuchain/stelaser/g'
find . -type f -print0 | xargs -0 sed -i 's/Cpuchain/stelaser/g'
find . -type f -print0 | xargs -0 sed -i 's/CPUchain/stelaser/g'
find . -type f -print0 | xargs -0 sed -i 's/CPUChain/stelaser/g'
find . -type f -print0 | xargs -0 sed -i 's/CPUCHAIN/stelaser/g'
find . -type f -print0 | xargs -0 sed -i 's/CPU/STELASER/g'


find . -type f -print0 | xargs -0 sed -i 's/15993/16967/g'
find . -type f -print0 | xargs -0 sed -i 's/15994/16966/g'
find . -type f -print0 | xargs -0 sed -i 's/15995/16968/g'
find . -type f -print0 | xargs -0 sed -i 's/15996/16969/g'
find . -type f -print0 | xargs -0 sed -i 's/15997/16970/g'
find . -type f -print0 | xargs -0 sed -i 's/15998/16971/g'

= 15993 15994

(FIND TEXT IN DOCUMENTS) grep -r "1234" .
FIXME: This hack should be removed a few years after


simply run at the path where the share/genbuild.sh file is
chmod +x genbuild.sh

sudo apt update 
sudo apt install gcc-8 g++-8




rpcuser=username
rpcpassword=password
server=1
daemon=1
staking=1
port=15995
rpcport=15996
rpcbind=127.0.0.1
maxconnections=48
rpcallowip=127.0.0.1
banscore=10000
_________________________________________
16.4 18.4

sudo add-apt-repository universe
sudo apt-get update
sudo apt-get install git
sudo apt-get install build-essential
sudo apt-get install libtool autotools-dev autoconf
sudo apt-get install libssl-dev
sudo apt-get install libboost-all-dev
sudo apt-get install pkg-config
sudo apt-get install libevent-dev
sudo apt-get install libzmq3-dev
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev
sudo apt-get install libdb4.8++-dev

git clone https://github.com/stelaser/stelaser.git
cd stelaser
./autogen.sh
./configure --enable-upnp-default --without-gui
make -j 4
------------------------------------------------------------

for port in \
  "19707 12707" "19708 12708" \
  "29707 22707" "29708 22708" \
  "39707 32707" "39708 32708" \
  "49707 42707" "49708 42708"
do
  from=$(echo $port | cut -d' ' -f1)
  to=$(echo $port | cut -d' ' -f2)
  echo "Replacing $from ➜ $to ..."
  find . -type f \( -name "*.cpp" -o -name "*.h" -o -name "*.conf" -o -name "*.in" \) -print0 | xargs -0 sed -i "s/$from/$to/g"
done


