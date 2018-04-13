## 初始购物清单
```
输入：
  buy_barcodes:[String]
  allItems:[{
        barcode: string,
        name: string,
        unit: string,
        price: string
  }]loadAllItems();
输出：
  buy_lists:[{
      barcode:string,      
      name:string,
      amount:string,
      price:string,
      unit:string,
      subtotal:string
  }];
  total_prices:string
```
## 优惠查询
```
输入：
  all_promotions:[{
      type:string,
      barcodes:[string]
  }]loadAllPromotions();
  buy_lists:[{
      barcode:string,
      name:[string],
      amount:[string],
      price:[string],
      unit:[string],
      subtotal:[string]
  }];
输出：
  promotion_goods:[{
      type:string,
      name:string,
      amount:string,
      unit:string
  }];
  promotion_prices:string;
  buy_lists:[{
      barcode:string,     
      name:[string],
      amount:[string],
      price:[string],
      unit:[string],
      subtotal:[string]
  }]  
```
## 打印购物单
```
输入：
  buy_lists:[{
      barcode:string, 
      name:[string],
      amount:[string],
      price:[string],
      unit:[string],
      subtotal:[string]
  }];
  promotion_goods:[{
      type:string,
      name:string,
      amount:string,
  }];
  total_prices:string    
  promotion_prices:string
输出：
  inventory:string
```