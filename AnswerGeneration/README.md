# 需要注意的事:
## albert/albert_tiny/config.json 中 type_vocab_size 改為 3:
	type_vocab_size 為 token_type_ids的词典大小,也是在任務里的Segment 的 type數,此任務有三個
	
![image](https://github.com/harry83528/taskQALineBot/blob/master/messageImage_1578628507824.jpg)
    
## type_vocab_size 改為 3 後 註解掉 albert/albert_zh/modeling_utils.py 錯誤程式碼

![image](https://github.com/harry83528/taskQALineBot/blob/master/messageImage_1578628507824.jpg)