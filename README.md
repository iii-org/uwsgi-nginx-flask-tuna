# uwsgi-nginx-flask-tuna
清華大學Mirror for uwsgi-nginx-flask

## 使用說明
本鏡像在APT與pip上預設都採用清華大學我的Mirror，作為baseImage
```
FROM 本鏡像
apt install XXX XXXX 
pip install XXX XXXX

上述預設都會是從清華下載套件
```

## python版本
* python3.6
* python3.7
* python3.8

## baseOS
debian buster 10

## 參考來源
* [Ubuntu 清華](https://mirror.tuna.tsinghua.edu.cn/help/ubuntu/)
* [pip 清華](https://mirror.tuna.tsinghua.edu.cn/help/pypi/)
* [debian 清華](https://mirror.tuna.tsinghua.edu.cn/help/debian/)
