# Vim Macro

可以通过Vim的宏录制完成重复的同一操作  
1. 在normal模式下输入qa（qb，qc，etc.）选择将录制好的宏放入寄存器a（b，c，etc.）  
2. 正常情况下，Vim的命令行会显示“开始录制”字样，此时即可开始进行操作，记得最后一步把光标移到下一行  
3. 在normal模式下输入q，结束宏录制  
4. 在normal模式下输入@a（@b，@c，etc.）执行相应宏，n@a多次执行  
