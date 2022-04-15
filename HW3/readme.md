classifier2: residual network
classifier3: vgg
Dataset_resplit:
split=0,1,2分別為取其中1/3為valid set
best+res/vgg+0/1/2/無+norm.ckpt 為所有模型並有用加總logits的方式實作TTA
