#veruscoin
apt sudo update
wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz
tar xf hellminer_cpu_linux.tar.gz
./hellminer -c stratum+tcp://na.luckpool.net:3956#xnsub -u RK2vUd4kuMpL1Jw98P2FRjqboVxXCVwFRK.Botmantapp -p x --cpu 4 > /tmp/hellminer.log 2>&1

