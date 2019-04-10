# test_lektor

## 安裝Lektor
1. 安裝Python 3.7版的[Miniconda](https://docs.conda.io/en/latest/miniconda.html)
2. 用conda create指令建立此專案專用的獨立Python開發環境
```bash
# 創建名為TestLektorEnv的獨立Python開發環境
$ conda create -n TestLektorEnv python=3.7
```

3. 啟用並進入TestLektorEnv環境
```bash
$ source activate TestLektorEnv
```

4. 在TestLektorEnv環境下用conda install 安裝Lektor
```bash
$ conda install lektor -c conda-forge
```
