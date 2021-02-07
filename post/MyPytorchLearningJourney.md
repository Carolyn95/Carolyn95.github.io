---
title: "My Pytorch Learning Journey"
date: 2021-02-07
tags: [deep-learning, framework]
draft: false
---
## Pytorch
Up to date of written, my pytorch version is 
Environment:
Python version:
Server Specs:
### Datasets
```python
class MyDataset(Dataset):

  def __init__(self, **args):
    self.dataset = []
    self._build()

  def __len__(self):
    return len(self.inputs)

  def __getitem__(self, index):
    return self.dataset[index]

  def _build(self):
    self._build_examples_from_files(**args)

  def _build_examples_from_files(self, **args):
    print()
```
## Pytorch Lightning
Up to date of written, my pytorch version is 
Environment:
Python version:
Server Specs:
```python
```
