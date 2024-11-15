# point1_experiment-record
实验环境：   
<img src="https://github.com/user-attachments/assets/250aa7ac-43d4-4d68-b921-e60b45a5c223" alt="description" style="width: 50%; height: auto;">  
实验参数：  
  *num_classes=2*  
  *model_name=bert*  
  *train_batch_size=16*  
  *val_batch_size=16*  
  *test_batch_size=16*  
  *num_epoch=20*  
  *lr=0.01*  
  *weight_decay=0.01*  
  *device=cuda*  
  *backend=store_true*  
  *workers=12*  
 
## 实验： roBert-BILSTM(IMDB)
参数：hidden_size=320 num_layers=1,
| Accuracy | precision |  recall | specificity |  f1_score | loss
| --- | --- | --- | --- | --- | --- | 
| 0.94 | 0.9309 |  0.9483 | 0.9300 | 0.9395 | 0.3730 |

<img src="https://github.com/user-attachments/assets/c6f5cf9a-949b-40e6-bf6d-469a9f6bad08" alt="description" style="width: 50%; height: auto;">

## 实验： roBert-bilstm_textcnn_modiAttention(IMDB)
参数：hidden_size=512 num_layers=1  
<img src="https://github.com/user-attachments/assets/46b71378-9742-4a1f-928a-f8c9e140f9ed" alt="description" style="width: 50%; height: auto;">  
| Accuracy | precision |  recall | specificity |  f1_score | loss
| --- | --- | --- | --- | --- | --- | 
| 0.94 | 0.9330 | 0.9501 | 0.9322 | 0.9415 | 0.3705 | 0.3696

<img src="https://github.com/user-attachments/assets/c6f5cf9a-949b-40e6-bf6d-469a9f6bad08" alt="description" style="width: 50%; height: auto;">
