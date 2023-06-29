# CSS 基础知识

## 选择器

1. 类选择器

   ```css
   .class {
     color: red;
   }
   ```
2. 标签选择器
    
   ```css
   div {
     color: red;
   }
   ```
3. id选择器

    ```css
    #id {
      color: red;
    }
    ```

## 伪类和伪元素

1. 伪类

    ```css
    a:hover {
      color: red;
    }
    ```

2. 伪元素

    ```css
    p::first-line {
      color: red;
    }
    ```

## 关系选择器

1. 后代选择器

    ```css
    div p {
      color: red;
    }
    ```
2. 子选择器

    ```css
    div > p {
      color: red;
    }
    ```
3. 相邻选择器

    ```css
    div + p {
      color: red;
    }
    ```
4. 兄弟选择器

    ```css
    div ~ p {
      color: red;
    }
    ```

## 选择器优先级

1. 选择器优先级

    ```css
    #id {
      color: red;
    }
    ```
    ```css
    div {
      color: red;
    }
    ```
    ```css
    .class {
      color: red;
    }
    ```
    ```css
    * {
      color: red;
    }
    ```
    ```css
    div p {
      color: red;
    }
    ```
    ```css
    div > p {
      color: red;
    }
    ```
    ```css
    div + p {
      color: red;
    }
    ```
    ```css
    div ~ p {
      color: red;
    }
    ```
    ```css
    div::first-line {
      color: red;
    }
    ```
    ```css
    div::first-letter {
      color: red;
    }
    ```
    ```css
    div::before {
      color: red;
    }
    ```
    ```css
    div::after {
      color: red;
    }
    ```
    ```css
    div:hover {
      color: red;
    }
    ```
    ```css
    div:active {
      color: red;
    }
    ```
    ```css
    div:focus {
      color: red;
    }
    ```
    ```css
## 盒模型

1. 盒模型

    ```css
    div {
      width: 100px;
      height: 100px;
      padding: 10px;
      border: 10px solid red;
      margin: 10px;
    }
    ```

## 浮动

1. 浮动

    ```css
    div {
      float: left;
    }
    ```
2. 清除浮动

    ```css
    div::after {
      content: '';
      display: block;
      clear: both;
    }
    ```
3. BFC

    ```css
    div {
      overflow: hidden;
    }
    ```