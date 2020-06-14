# 需要注意的事:
## 下載Albert後,將albert/albert_tiny/config.json 中 type_vocab_size 改為 3:
	type_vocab_size 為 token_type_ids的詞典大小,也是在任務里的Segment 的 type數,此任務有三個
	
![image](https://github.com/harry83528/NLP-BERT-Experience/blob/master/AnswerGeneration/img/type_vocab_size.jpg)
    
## type_vocab_size 改為 3 後 註解掉 albert/albert_zh/modeling_utils.py 錯誤程式碼

![image](https://github.com/harry83528/NLP-BERT-Experience/blob/master/AnswerGeneration/img/error.jpg)

