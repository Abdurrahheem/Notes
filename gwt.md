Update GAP SDK

1. git checkout master
2. git pull
3. git submodule update --init --recursive
4. comment line 32-34 in CMakeLists.txt
5. make all -j