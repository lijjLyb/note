### littleEndian and bigEndian

* 内存地址是按由低到高顺序排列的

大端格式

  将2进制值按从左到右的顺序写在内存上,这样低位实际存放的是高位的值
  
  即低位放高位的值

小端格式 

  将值拆解为byte,低位放低位的,高位放高位的

  低位放低位的值,高位放高位的值

* x86cpu 一般使用 小端格式

* js中 `DataView` 提供设置大端还是小端,默认为大端