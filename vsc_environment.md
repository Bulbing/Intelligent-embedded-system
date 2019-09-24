#vsc中python的环境：   
1.win10下修改系统变量的路径：[链接](https://www.pconline.com.cn/win10/1100/11001561.html)   
2.lauch.json中的设置：  
<p>   
  {  
  "version": "0.2.0",   
  "configurations": [   
    {   
      "name": "Python: Current File",   
      "type": "python",   
      "request": "launch",   
      "program": "${file}",   
      "console": "integratedTerminal"   
    }   
  ]    
}    
</p>  
