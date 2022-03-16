在user上freeze住MLP训练model，并把所有样本的损失上传给server进行GMM  
在server上train MLP：直接采样GMM作为meta set的损失进行更新ML  
  
fed_avg :0.6592
moon:0.66
ourmodel:0.681400
