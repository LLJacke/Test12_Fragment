# Test12_Fragment
##对Fragment的理解
>Fragment,即碎片，我大概理解就是分模块、分模式编辑，同时可复用，这一节实现的是简单的左右分栏。

##实现左右分栏遇到的问题
>基本是按照教材步骤操作的，涉及的方法和类很多，并不能全部完全理解。有遇到一个不算技术上的问题，但是得记录一下。
>DetailFragment所用到的Fragment类，在自动导入时导入的是android.support.v4.app.Fragment，然而在MainActivity中引用replace方法的时候，会报错，原因是replace方法的第二个参数所用的是android.app.Fragment包，不清楚这是不是用的API更新后做的更改。
