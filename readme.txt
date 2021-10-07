- open powershell as admin
- text: 	set-executionpolicy RemoteSigned
- to accept script
- activate env python
- run this script

pyinstaller --noconfirm --onedir --windowed --icon "E:/Tools/manga_tool/logo.ico" --add-data "E:/Tools/manga_tool/comicDays.py;." --add-data "E:/Tools/manga_tool/pocket.py;." --add-data "E:/Tools/manga_tool/viewerHeros.py;." --add-data "E:/Tools/manga_tool/cookie.txt;."  "E:/Tools/manga_tool/app.py"