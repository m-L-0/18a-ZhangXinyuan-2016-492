图的边与结点作业：
有一4阶张量img其shape=([10,28,28,3]),代表10张28*28像素的3通道RGB图像，问：
1. 如何利用索引取出第2张图片？（注意：索引均从0开始，第二张则索引为1，下同）
2. 如何利用切片取出第2张图片？
3. 使用切片与使用索引取出的一张图片有何不同？
4. 如何取出其中的第1、3、5、7张图片？
5. 如何取出第6-8张（包括6不包括8）图片中中心区域（14*14）的部分？
6. 如何将图片根据通道拆分成三份单通道图片？
7. 写出tf.shape(img)返回的张量的阶数以及shape属性的值。 

取出图片的时候注意下标，都是从0开始的；取出第奇数个或者第偶数个等有规律的图片时学会运用步长属性；多种获取shape属性的方法，会获得不同类型的属性
