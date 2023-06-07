# 《HelloAIGC》——20230526

## 内容
> **以下为本期内容**｜每日更新

1、[DeOldify](https://github.com/jantic/DeOldify)：一款可以给老旧照片上色的项目。该项目基于深度学习实现了对黑白图像和视频进行着色的功能。

<p align="center"><img src='https://foruda.gitee.com/images/1685069469680386262/cbc9e395_6522093.jpeg' style="max-width:80%; max-height=80%;"></img></p>

2、[wandb](https://github.com/wandb/wandb)：一款轻量级的机器学习可视化工具。该项目是用于可视化和跟踪机器学习实验的工具，通过几行代码就可以实现跟踪、比较和可视化机器学习实验。

```python
import wandb

# 1. Start a W&B run
wandb.init(project="gpt3")

# 2. Save model inputs and hyperparameters
config = wandb.config
config.learning_rate = 0.01

# Model training code here ...

# 3. Log metrics over time to visualize performance
for i in range(10):
    wandb.log({"loss": loss})
```
3、[Chatbot_CN](https://github.com/charlesXu86/Chatbot_CN)：基于金融-司法领域(兼有闲聊性质)的聊天机器人，其中的主要模块有信息抽取、NLU、NLG、知识图谱等，并且利用Django整合了前端展示,目前已经封装了nlp和kg的restful接口

4、[PaddleHub](https://github.com/PaddlePaddle/PaddleHub)：Awesome pre-trained models toolkit based on PaddlePaddle. (400+ models including Image, Text, Audio, Video and Cross-Modal with Easy Inference & Serving)

5、[medaCy](https://github.com/NLPatVCU/medaCy):MedaCy is a text processing and learning framework built over spaCy to support the lightning fast prototyping, training, and application of highly predictive medical NLP models. It is designed to streamline researcher workflow by providing utilities for model training, prediction and organization while insuring the replicability of systems.

---



