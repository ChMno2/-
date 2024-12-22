# Linux命令的基礎應用
 Ls 查看當前文件夾的內容
Pwd 查看當前所在文件夾
Cd [目錄] 切換文件夾
touch[文件名] 如果文件不存在，新建文件
mkdir[目錄] 創建目錄
Rm[文件] 刪除指定的文件名
Clear 清除屏幕

# 終端命令格式
[]代表可選
Command [-options] [paratemter]
 
# 查詢命令幫助信息

—help
Command —help

Man
man command
Ex:man mkdir
(manual)手冊

Tap	可以自動補全信息
上/下 曾經使用過的命令
不想選擇 crtl+c

# Linux下文件和目錄的特點
以.開頭的文件為隱藏文件 需要用-a參數才能顯示
-a代表所有目錄
.代表當前目錄
..代表上一級目錄

# Ls常用選項
-a 顯示指定目錄下所有子目錄，包括隱藏文件
-l  以列表方式顯示文件的詳細信息
-h 配合-l以人性化方式顯示文件大小

EX:ls -l -h
