# llvm-sh
For convenience there is an automatic installation script available that installs LLVM for you.
To install the latest stable version:
bash -c "$(wget -O - https://raw.githubusercontent.com/Anonym3310/llvm-sh/master/llvm.sh)"

To install a specific version of LLVM:
git clone https://github.com/Anonym3310/llvm-sh
cd llvm-sh
chmod +x llvm.sh
sudo ./llvm.sh <version number>
