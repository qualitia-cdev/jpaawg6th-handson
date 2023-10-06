# JPAAWG 6th General Meeting ゼロから始めるAIハンズオン -「スパムフィルタ」と「メールの件名自動生成」

## 事前準備

本トレーニングセッションでは参加者に皆さんのパソコンからクラウドに接続して、実際に「スパムフィルタ」と「メールの件名自動生成」を作成します。
Google Colabの環境を使用しますので、事前に接続の確認を行っておいてください。

5～10分程度で確認可能です。

## Google Colabの準備

1. 次のURLにアクセスします。
https://colab.research.google.com/
2. ポップアップが表示された場合は閉じてください。
3. 「File」 -> 「New notebook」の順にクリックしてください。

入力欄にコードを入力し、再生ボタンのような三角のボタンをクリックするとコードが実行されます。

次のコードをコピペして実行し「Hello! JPAAWG」と表示されることを確認してください。

```python
print("Hello!", "JPAAWG")
```

新しくコードを入力する場合は、「+ Code」をクリックします。

**これで準備は完了です。**

当日のトレーニングセッションをお楽しみください。


もっと深い興味があり、Google Colabを使わずにローカルのパソコンで実行したい場合は下記の英語のドキュメントの2章をご覧ください。

---

# Preparing Dev Environment for AI session

## 1. Google Colab (Mandatory) (Recommended)

### 1.1 Introduction

I'm going to use Google Colab for this session. Google Colab, or Colaboratory, is a free Jupyter notebook environment that runs in the cloud. It allows you to write and execute code, run live code cells, and share your work with others. Colab is a popular tool for machine learning, data analysis, and education.

Here are some of the benefits of using Google Colab:

- It is free to use.
- It runs in the cloud, so you don't need to install any software on your computer.
- It can access powerful hardware, such as GPUs and TPUs.
- It is easy to share your work with others.
- It is a great way to learn about machine learning and data science.

### 1.2 Getting Started

**Prerequisites:**

- **You need a Google account to use Google Colab. So please create a one if you don't have one.**
- **Sign in to your Google account.**

1. Please visit:
https://colab.research.google.com/

2. Click, File -> New notebook
3. By clicking + Code, you can add a new code cell
4. To execute a code cell, click the play button on the left of the cell
   - Try to execute following code cell.
   - You can copy and paste the following code to the cell.

```python
print("Hello JPAAWG")
```

Please check following video for more details:
https://www.youtube.com/watch?v=RLYoEyIHL6A


***Google colab is mandatory for the Subject generation session. You cannot use your local environment for the subject generation session due to various reason.***



## 2. Local Development Environment (Optional Method) [Not Recommended]

### Disclaimer and Warning

**We not responsible for any issues caused by installing software on your computer. Installing libraries may cause issues with your existing libraries and broken your existing environment. Please use your own judgement.**

In any case, for example if you want to use your dev environment for the session, you can use your local development environment. In this case, you need to install following software.

- Python 3.10
- Jupyter Notebook

### 2.1 Anaconda

Easiest way to use Anaconda. Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing, that aims to simplify package management and deployment. Package versions are managed by the package management system conda.

#### 2.1.1 Windows

1) Go to [Download Anaconda](https://www.anaconda.com/download#downloads) and download the installer for windows.
2) Follow the instructions to install Anaconda [Installation guide windows](https://docs.anaconda.com/free/anaconda/install/windows/)
3) After installation, The app should start. If it doesn't search for it from your Start Menu to launch.
4) Ignore the prompt to log in.
5) Choose Jupyter Notebook from the list and press Launch. This will open a new tab in your default browser.

#### 2.1.2 Mac

1) Go to [Download Anaconda](https://www.anaconda.com/download#downloads) and download the installer for Mac.
2) Follow the instructions to install Anaconda [Installation guide mac](https://docs.anaconda.com/free/anaconda/install/mac-os/)
3) After installation, The app should start. If it doesn't search for it from your Start Menu to launch.
4) Ignore the prompt to log in.
5) Choose Jupyter Notebook from the list and press Launch. This will open a new tab in your default browser.

![Anaconda Navigator](images/anaconda-navi.png)

Please refer following video for more details:
https://www.youtube.com/watch?v=WUeBzT43JyY

### 2.2 VS Code

If you are using VS Code, you can install Python extension and Jupyter extension. Then you can open a notebook file (.ipynb) and start using it.

Please refer following video for more details:
https://www.youtube.com/watch?v=jNk-ZmeIz6c

### Libraries
Install following libraries using pip in the notebook cell. "!" is used to run shell commands in the notebook cell.

```bash
!pip install pandas scikit-learn numpy matplotlib seaborn nltk wordcloud xgboost lightgbm
```

There are many ways to install Python and Jupyter Notebook. You can use Anaconda, or you can use Docker. Please refer internet for more details.



---

**Note:**
This document is updated time to time. Please check the last updated date to see if there are any updates.

Last Updated: 2023/10/05 - 16:21 AM
