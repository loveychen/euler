Simplifying Graph Convolutional Networks(SGCN)
============

Paper link: [Simplifying Graph Convolutional Networks](https://arxiv.org/pdf/1902.07153.pdf)

Run
-------
```python
python run_sgcn.py [--optional_params=params]
```

Params:

| Parameter Name | Default | Note |
| ----------------- | -------------- | ------------------------------- |
| dataset           | cora           | cora/pubmed/citeseer/ppi/reddit |
| hidden_dim        | 32             | hidden dimension                |
| layers            | 2              | GCN layer number                |
| batch_size        | 32             | running batch size              |
| num_epochs        | 10             | epochs to run                   |
| log_steps         | 20             | log per steps                   |
| model_dir         | ckpt           | checkpoint dir                  |
| learning_rate     | 0.01           | run learning rate               |
| optimizer         | adam           | run optimizer algorithm         |
| run_mode          | train          | train/evaluate                  |

Result
------
| Dataset | F1 |
| ---------- | ------------------ |
| cora       | 0.825              |
| pubmed     | 0.866              |
| citeseer   | 0.716              |

