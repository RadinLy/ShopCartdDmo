# ShopCartdDmo
购物车demo，解决checkbox选中复用和更改商品数量复用


如何避免这两种控件的复用，1，把Checkbox加入到Map集合中，通过Map集合对控件进行操作，2，把每个条目布局中的商品数量加入到Bean类中。

checkbox加入到map中有何好处，首先，你购物车不可能是只是在adapter中记录选中消息，你activity中可能会存在全选操作，那么，你在Activity中如何快速修改全部的选中状态，那么就直接循环一下map集合，并刷新adapter,就可以完成。

条目布局中的数量加入到Bean类，传递到下一个订单支付界面，可以直接通过Bean类传递一个序列化类，就不会做太多的循环查询数据操作了。



#简书连接跳转
#http://www.jianshu.com/p/91d0f271c6c0
