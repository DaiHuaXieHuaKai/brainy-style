### brainy-style
brainy-style是一个基础的布局样式类，包含了flex、spacing、align、ellipsis等的相关布局。

#### 用法

1.水平居中
```
    <div class="flex flex-justify-content-center">
        我水平居中了
    </div>
    <div class="text-center">
        我水平居中了
    </div>
```
2.垂直居中
```
    <div class="flex flex-align-items-center" style="height:100px;">
        我垂直居中了(先设置高度)
    </div>
```
3.水平垂直居中
```
    <div class="flex flex-align-items-center flex-justify-content-center" style="height:100px;">
        我水平垂直居中了(先设置高度)
    </div>
```
4.水平排列并两端对齐
```
    <div class="flex flex-justify-content-between">
        <div>我是最左边的</div>
        <div>我是最右边的</div>
    </div>
```