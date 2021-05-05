# Ensemble_Matting

文档说明如下：
（1）./data/：该目录存放数据，构造数据集的时候需要三部分数据：1）前景照片，需要放到"./data/Distinc_fg/"目录中；2）背景照片：需要放到"./data/bk/"目录中，目前背景照片只有200张；3）matte照片，需要放到"./data/Distinc_alpha/"目录中
（2）运行“image_composite_multi.py”可以以多线程并行的方式合成数据集，合成的照片放到"./data/Distinc_composite/"目录中；
（3）运行“train_script_official_v2.py”可训练模型。
