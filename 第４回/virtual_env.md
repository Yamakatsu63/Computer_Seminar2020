# Jupyterlabでの仮想環境構築方法

1. condaで新しい環境を作成する

    ```conda create -n 環境名 python=バージョン パッケージ名```

1. (初回のみ)condaを初期化する

    ```conda init bash```
1. 環境をアクティブにする

    ``` conda activate 環境名```

1. (必要な場合のみ)環境にパッケージをインストールする

    ```conda install パッケージ名```

    ```pip install パッケージ名```

1. 環境を利用するカーネルを作成する

    ```ipython kernel install --user --name カーネル名```

1. launcherから作成したカーネルを選択する

## 使用例(scikit-learn)

```
conda create -n sklearn python=3.6 jupyter numpy scipy matplotlib pandas
conda activate sklearn
pip install scikit-learn
ipython kernel install --user --name sklearnkernel
```