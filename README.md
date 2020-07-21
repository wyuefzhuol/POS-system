# 完成任务如下：
### POS system tasking:
1. 生成唯一型商品条形码数组uniqueBarcodes
    - 输入：barcodes:[string]
    - 输出：uniqueBarcodes:[string]
2. 计算唯一商品条形码对应的数量itemQuantity
    - 输入：uniqueBarcodes:[string]
    - 输出：itemQuantity:{barcodes:string,quantity:int}
3. 获取每一个商品的名称 . 单价信息
    - 输入：uniqueBarcodes:[string]
    - 输出：barcodesWithQuantity:{barcoude:string,name:string,quantity:int,unit price:int}
4. 计算每一个商品的总价
    - 输入：barcodesWithQuantity:{barcoude:string,name:string,quantity:int,unit price:int}
    - 输出：barcodesWithQuantity:{barcoude:string,name:string,quantity:int,unit price:int,subtotal:int}
5. 合计商品价格进行总价Total的计算
    - 输入：barcodesWithQuantity:{barcoude:string,name:string,quantity:int,unit price:int,subtotal:int}
    - 输出：total:int
6. 格式化商品信息与总价生成receipt
    - 输入：barcodesWithQuantity:{barcoude:string,name:string,quantity:int,unit price:int,subtotal:int}、total:int
    - 输出：receipt:string
### 上下文图如下:
![加载失败](https://github.com/wyuefzhuol/POS-system/raw/master/POSsystem.png)
### PDCA分析如下:
| 