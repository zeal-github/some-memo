# Notes about tensorflow

## 1. with g.as_default():

1. 一旦开始任务，就会有一个默认的的图被创建，可以通过 `tf.get_default_graph()` 访问
2. g = tf.graph 可以创建一个新图
3. 要增加内容到创建的新图需要用`with g.as_default():`语句，并且所有操作放在`with`模块下，否则是对默认图进行添加操作