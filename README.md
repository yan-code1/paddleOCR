# paddleOCR
# 相关库引自https://github.com/PaddlePaddle，本内容仅作学习和记录使用
### 平台为win10,python3.7
	1. 依赖安装, 复制以下依赖到requirements.txt ，然后 pip install -r requirement.txt
		shapely
		scikit-image==0.17.2
		imgaug==0.4.0
		pyclipper
		lmdb
		tqdm
		numpy
		visualdl
		python-Levenshtein
		opencv-contrib-python==4.2.0.32
		lxml
		premailer
		openpyxl
	2. 下面安装主要的包
		a. 安装paddleocr和paddlepaddle
		pip install -i https://pypi.tuna.tsinghua.edu.cn/simple paddleocr
		pip install -i https://pypi.tuna.tsinghua.edu.cn/simple paddlepaddle
注：安装第二个包的时候可能报缺少VC++1.4的错，下个安装下就可以了，在另一篇文章里面。
