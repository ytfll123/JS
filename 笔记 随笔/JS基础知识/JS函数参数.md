#JS 传参#

JS函数中有一个重要的概念叫做**参数**，参数分为两种，

1. 形参
2. 实参

在我们在定义函数时的参数被称之为形参；

在函数调用的时候的参数称之为实参；


##1 形参##

形参全程为形式参数，类似于在函数内部定义了一个局部变量，但不相同，目的是为了使我们传递参数时能够找到正确的位置，

##2 实参##

实参为实际的参数，也可以认为是数据或者值，在函数调用时，将值或者数据传递到形式参数所在的位置，使函数操作更为灵活。

##重点##

参数的数量并不是一一对应的，实参和形参的数量是可以不相同的，原因在于我们传递参数的时候，实际上传递的是一个数组，而不是传递的一个一个的参数，所以有以下两种情况

当形参小于实参的时候，多余的形参会被默认为undefined

当实参小于形参的时候，多余的实参将不会被传递给形参，若想要调用多余的实参  需要使用argument操作命令；

##return##

函数中有个特殊的指令为return，每个函数执行完毕后都会有一个return返回值，若不写，则默认为undefined，当函数读到return时则会自动终止，类似于for循环的break跳出； 但是函数可以定义返回一个值而且我们可以打印出这个return值；
