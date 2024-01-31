# Winter CS Camp

This is a winter cs camp held in National Chengchi University on 2024/1/31 ~ 2024/2/2. The main purpose is to let the students who are interested in computer science know about what you should have to learn before you choose computer science as your major.

## 💻 設備需求

| Computers | Pre-installed softwares |
| --------- | ----------------------- |
| Windows   | Powershell or CMD       |
| Mac       | Iterm2                  |

## 📣 Schedule

Schedule's link [here](https://docs.google.com/document/d/11QHqGS9etAwiPgg4OhzGZhMZ6HjQMVGupI8I3ZCp3ac/edit)

## 📘 講義

### 📅 第一天「人與電腦的協作、Unix commands and Shell Script」

#### 📎 人與電腦的協作

- Slides's link [here](https://docs.google.com/presentation/d/1mMqcRotUqBH4X1Jyjz_BD4xcPibSxdonCQ933J3eQd8/edit#slide=id.p)

- 課程內容所需之套件

  - **字型下載**: [MesloLGS NF Regular](https://www.google.com/url?q=https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%2520NF%2520Regular.ttf&sa=D&source=editors&ust=1704195459976407&usg=AOvVaw1ZqnwQ0ZB2yCDr8pLKZ51D)
  - **Iterm2**: [下載連結](https://iterm2.com)
  - **Brew**: [下載連結](https://brew.sh)
  - **upload**: [上傳設計圖](https://docs.google.com/presentation/d/19UVVNFsg4vdvqkoa3aU9ZaJx5RfCF5RlEOnXATT9eso/edit#slide=id.p)

- 開啟虛擬機設定
  ```shell
  Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
  Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform
  Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux

  ```

- 安裝 Oh-my-zsh

  ```shell
  wget https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh
  sh install.sh
  ```

- 安裝 Power10k

  ```shell
  git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
  sh install.sh
  ```

  #### 📎 Unix commands tutorial

- Slide's link [here](https://www.canva.com/design/DAF7PqK4W1U/CqISUGn-D7JJNauk1v2lQA/view?utm_content=DAF7PqK4W1U&utm_campaign=designshare&utm_medium=link&utm_source=editor)
- Practice1

  ```shell
  git clone https://github.com/bear7066/unix_practice 
  ```

  #### 📎 Vscode - 1

- Slide [here](https://docs.google.com/presentation/d/1iSpYdzzZ-hl0GxLNo_U3k-Bx-ZFQynHTT3E1D7jZh2Y/edit?usp=sharing)

### 📅 第二天

#### 📎 Vscode - 2 and NVIM

- Slide [here](https://docs.google.com/presentation/d/1iSpYdzzZ-hl0GxLNo_U3k-Bx-ZFQynHTT3E1D7jZh2Y/edit?usp=sharing)
- Slide [here](https://docs.google.com/presentation/d/1xMphq9y7CBEhoEdZldoZYM4rqefK0IjYmwH_tjGol7I/edit?usp=sharing)

#### 📎 程式基礎教學

- Class of C++ beginner
  - Slide [here](https://docs.google.com/presentation/d/1Gsacjz0jBTtGtYkE2geQMWR2OqwW1TD9FZf3boeXvIU/edit?usp=sharing)
  - 
- Class of C++ advancer
  - Slide [here](https://docs.google.com/presentation/d/1T3sX-2wM_9wf5vsotUIlcCwE8o_RVlafrXun2KAesbE/edit?usp=sharing)
  - 語法概要
    - [I/O](https://onlinegdb.com/GFnvFYdjB)
    - [迴圈](https://onlinegdb.com/qWroYH7C9)
    - [實作1(回文練習)](https://onlinegdb.com/SDNab9UDBv) 
  - 進階C++語法
    - [Pointer(含pointer問答+實作2)](https://onlinegdb.com/cHwKXaL2J)
    - [Vector](https://onlinegdb.com/ex5t0nSJM)
    - 課後自主學習資料/補充資料
      - [STL(標準模板庫)](https://jasonblog.github.io/note/c++/c++_stl_xue_xi_zong_7d5028_quan_976229.html)
      - [Template](https://www.geeksforgeeks.org/templates-cpp/)
  - OOP基本概念
    - []()
    - []()
    - []()
    - []()
      - 課後自主學習資料/補充資料
        - []()
        - []()   
  - Makefile



