---
title: 第一篇文章
date: 
updated: 
tags: 文章？？
---
简介要写差不多50个字才行啊。简介要写差不多50个字才行啊。哈哈哈哈哈简介要写差不多50个字才行啊。



```typescript
(function(){
  // 禁止一个类被用来创建对象 抽象类是用来继承的
  //抽象类中可以添加抽象方法
 abstract class Animal{
    name:string;
    constructor(name:string){
      this.name=name;
    }
    //抽象方法 子类必须重写抽象方法
   abstract sayHello():void;
  }
  class Dog extends Animal{
    sayHello(){
      console.log('汪汪');
      
    }
  }
  const dog=new Dog('旺财');
  dog.sayHello();
})();

```


# 主标题

## 文章标题

- Hello world