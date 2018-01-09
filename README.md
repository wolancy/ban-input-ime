# ban-input-ime   
chrome在30.1.n.n.n版本之后就不支持css里面ime-mode了在网上查了很多关于chrome禁用输入法的解决办法，试过之后都不行  
最最让人头疼的是输入法输入之后按下enter键，不管你怎么做，输入的内容都会显示，此时的enter是在输入法里面起作用，你的代码对它无用，相当于复制粘贴。
在这里js部分给input绑定onkeyup事件和onblur事件      
输入法最让人头疼的是，keyup事件能解决大多时候的情况。    
blur事件可以有效解决这个让人头疼的问题，但不是最好的解决方法，当input失去焦点的时候我们将里面的内容做一次处理。    
本内容解决的是只能输入数字。    
[index]( https://wolancy.github.io/ban-input-ime/index.html)    
