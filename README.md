# PTT 圖片爬蟲

## 下載相依套件
```bash
pip install -r requirement.txt
```

## 如何使用
```
python main.py -h

usage: main.py [-h] [--label LABEL] [--pages PAGES]

optional arguments:
  -h, --help            show this help message and exit
  --label LABEL, -l LABEL   選擇 PTT 看板 e.g. Food
  --pages PAGES, -p PAGES   設定頁數上限，預設為全部
```

爬取 PTT 美食版所有圖片
```
python main.py --label Food
```
