# Object-Detection
利用tensorflow以及keras框架实现YOLO算法，对图像进行目标检测

yolo_filter_boxes：对YOLO boxes进行过滤
iou：计算交并比
yolo_non_max_suppression：对boxes进行非最大抑制（NMS）
yolo_eval:对yolo的编码进行处理转换（包括对boxes的过滤、非最大抑制等），返回scores,boxes,classes
predict:对自己的图片进行检测
# yolo_utils
read_classes:读取对象变量（coco_classes.txt），返回包含识别对象字符串的列表
read_anchors:读取anchors（yolo_anchors.txt），返回anchors（n x 2）
# yolo.h5
为节省训练时间，下载已经训练好的模型yolu.h5
具体方法：https://blog.csdn.net/weixin_41043240/article/details/79745614?utm_source=blogxgwz8
或者下载我做好的yolu.h5:链接: 链接: https://pan.baidu.com/s/1czsFrhSAlK0cF7qvykZj9Q 提取码: ygfs 
# keras_yolo.py
yolo_head：将模型输出转换为需要的格式

