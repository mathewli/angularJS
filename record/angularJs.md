**AngularJS** 扩展了HTML   
  1. ng-app：定义了一个AngularJS应用程序
  2. ng-model：将元素的值（比如输入域的值）绑定到应用程序
  3. ng-bind:把应用程序变量name绑定到某个段路的innerHTML   
     (<h1 ng-bind="name"></h1>和<h1>Hello {{name}}</h1>一样)   
  4. 表达式，写在双大括号中{{}}，与javascript一样   
  5. AngularJS 模块（Module）定义了 AngularJS 应用   
     AngularJS 控制器（Controller） 用于控制 AngularJS 应用。
     ng-app指令定义了应用, ng-controller 定义了控制器
  6. 对象 ng-init="person={firstName:'mathew', lastName:'li'}"
     调用绑定 ng-bind="person.firstName" 显示用
     ng-model="person.firstName" input值的输入
     
  7. 数组 ng-init="age=[1,2,3]"
     调用绑定 ng-bind="age[0]";
          ng-model="age[0]"同上