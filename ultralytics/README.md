## 环境安装
```
git clone https://github.com/ultralytics/ultralytics
cd ultralytics
conda activate yolo
pip install -r requirements.txt -i https://pypi.douban.com/simple/
```
## 运行
cd ultralytics/yolo/v8可以看到有三个任务classify detect segment，将下载好的权重分别放到三个文件夹内
- classify
```
python predict.py
```
- detect
```
python predict.py
```
- segment
```
python predict.py
```
结果保存在runs文件夹中可以查看

