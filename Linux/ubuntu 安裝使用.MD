#Ubuntu 安裝使用

#下載vmware boardcom
linux修改語言
新增鏡像服務器->軟件和更新->選擇最佳服務器->重新載入


#Apt terminal工具
安裝包管理工具

1.安裝
$sudo apt install 軟體

2.刪除
$sudo apt remove 軟體

3.刷新可用軟體列表
$sudo apt update

4.更新已完成的安裝包
$sudo apt update

＃常用開發工具

Python:
Sudo apt install python
Sudo apt install python3
Sudo apt install python-pip

C++:
sudo apt install cmake
sudo apt install qtcreator

刪除不必要的軟體
sudo apt remove libreoffice-office
Sudo apt remove unity-web apps-common


#deb安裝格式

安裝google瀏覽器
先下載google.deb
Https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

cd Desktop/
Ls -l
Sudo apt install libappindicator1 libindicator7
Sudo dpkg -I google-chrome-stable_current_amd64.deb
Sudo apt -f install

#安裝sogo輸入法
先在鍵盤輸入法系統中改為fcitix

接著

Sudo dpkg -I sogoupinyin_2.1.0086_amd64.deb

修復關係
Sudo apt -f install




























