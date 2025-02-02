### 深度学习项目结构模板

dp_template/
├── configs/
│   ├── train_config.yaml
│   └── model_config.yaml
├── data/
│   ├── raw/
│   ├── processed/
│   └── datasets.py
├── models/
│   ├── model.py
│   ├── pretrained/ <!--预训练模型>
│   └── layers/   <!--自定义层或模块>
├── experiments/  
│   ├── runs/ <!--训练日志>
│   └── notebooks/ <!--实验结果分析>
├── utils/
│   ├── logger.py   <!--日志记录（如TensorBoard、WandB集成）>
│   ├── metrics.py  <!--自定义评估指标>
│   └── visualization.py  <!--结果可视化>
├── train.py
├── eval.py
├── requirements.txt
└── README.md