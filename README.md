# pyinstaller-first

## 如何开始

``` bash
pip install pyinstaller

pyinstaller -D main.py

# 修改main.spec, 将需要的数据文件包含进去,比如: 
datas=[('okjx.json','.'),('relax/ua_fake.json','relax')],

pyinstaller -F main.spec

```