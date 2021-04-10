# Drum Kit

## *function removeStyle() Lesson*
- ### **event.propertyName**
  - 当发生transitionend事件时，propertyName属性返回与转换关联的CSS属性的名称。此属性是只读的。
- ### **event.target**
  - event.target 属性返回哪个 DOM 元素触发了事件。
  - 这对比较 event.target 和 this 是非常有用的，以便判断事件是否因事件冒泡被处理。
- ### **div.classList.remove()** and **classList.add()**
  - **classList**属性返回元素的类名
  - **add()**: 向元素添加一个或多个类名。如果指定的类已存在，则不会添加该类。
  - **contains()**: 返回一个布尔值，指示元素是否具有指定的类名。
  - **item()**: 返回具有元素中指定索引号的类名。 索引从0开始。如果索引超出范围，则返回null。
  - **toggle()**: [reference](https://www.jc2182.com/javascript/javascript-element-classlist-attr.html)
  - **remove()**: 从元素中删除一个或多个类名。注意：删除不存在的类不会引发错误。
  

## *function playSound() Lesson*

- ### **\`${}`** 模板字面量
  - <kbd>`</kbd> , 不是 <kbd>'</kbd>
  - \`字符串 ${ 变量、属性名 } `
  -  ``` var a = 1;
      var b = 2;
      //不用模板的写法
      console.log("三是" + (a + b) + "不是" + (2 * a + b)); //"三是3不是4"
      //使用模板字符串的写法
      console.log(`三是${a + b}不是${2 * a + b}`); //"三是3不是4"```

## *Other Lesson*
- ### **document.querySelectorAll('.dot')**
  - CSS类名选择器,class包含dot，符合条件元素名组成数组
- ### **document.querySelector()**
  - 即便多个符合，只返回第一个元素名
- ### **data-\* 全局属性** 
  - data-* 属性用于存储页面或应用程序专用的自定义数据。
  - data-* 属性使我们能够在所有HTML元素上嵌入自定义数据属性。
  - 可以在页面的JavaScript中使用存储的（自定义）数据（无需任何Ajax调用或服务器端数据库查询）。
  - data-*属性由两部分组成：
    - 属性名称不应包含任何大写字母，并且在前缀“data-”之后必须至少有一个字符。
    - 属性值可以是任何字符串
- ### **transitionend**
  - 在 CSS transition 结束后会被触发。