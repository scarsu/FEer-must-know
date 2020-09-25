# Step-By-Step

## 如何判断this指向

### 默认绑定

严格模式，指向undefined

非严格模式，浏览器环境，指向window/globalThis

非严格模式，node环境，指向global

### 隐式绑定

通过对象方法调用的函数内，this指向该对象

### 显示绑定

通过call，apply，bind方法调用的函数，指向绑定的对象

### new绑定

通过new调用的构造函数内，this指向新创建的对象

### 箭头函数

箭头函数this指向，取决于定义箭头函数的上下文中this指向

