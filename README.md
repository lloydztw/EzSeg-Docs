# Eazy Segmentation (Demo)
[![LeTian Space](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://lloydztw.github.io/mysite/)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
[![LeTian FB](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/letian.chang)
[![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lloydz.tw@gmail.com)

A segmentation server written in pytorch.

------------------------------------------------------------------

## History
- 12 July 2023 - Version 1.0.0.3
    - 使用多線程 Demo
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>

- 10 July 2023 - Version 1.0.0.0
    - 創建版
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>
<br>

------------------------------------------------------------------
# 【Windows 平台相關工具套件】
## 請預先安裝以下套件
- visual studio 2022
- anaconda (https://www.anaconda.com/download)
    - 必須安裝在 C:\anaconda3 資料夾
- nVidia CUDA tool kits 11.7 (或 11.3)
    - https://developer.nvidia.com/cuda-11-7-0-download-archive
- nVidia cuDnn 11.x
    - https://developer.nvidia.com/login

<br/><br/>

------------------------------------------------------------------
# 【從 JetEazy Ftp Server 下載相關安裝檔案】
- https://download.jeteazy.com/LeTian/EzSeg/
- https://download.jeteazy.com/LeTian/EzSeg/EzSegDemo_Setup_1.0.0.3.exe
- https://download.jeteazy.com/LeTian/EzSeg/requirements.txt 
<br/>
<br/>
至暫存資料夾, d:\tmp
<br/>

------------------------------------------------------------------
# 【安裝 Python 環境】

按下 &#8984; + R 鍵, 然後輸入 cmd, 來開啟 Windows 終端機 視窗.<br/>
依序 鍵入 以下指令: <br/>
(1.0) 跳到 暫存資料夾, d:\tmp
```
d:
cd d:\tmp
```
(1.1) 安裝 python 3.8 名稱為 ez_seg 的虛擬環境,<br/> 
    (如果之前已經建好 ez_seg 的虛擬環境, 可跳過此步驟.)

```
conda create -n ez_seg python=3.8
```
(1.2) 進入 ez_seg 虛擬環境<br/>
成功後,手動鍵入:
```    
conda activate ez_seg
```
------------------------------------------------------------------
(2) 安裝 pytorch<br/>
(2.1) 如果 CUDA 安裝的版本是 11.7, 請輸入以以下指令:
```
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
```
(2.2) 如果 CUDA 安裝的版本是 11.3, 請輸入以以下指令:
```
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch
```
------------------------------------------------------------------
(3) 安裝 python 第三方套件<br/>
(3.1) 套件組 I
```
conda install -c conda-forge ultralytics
```
(3.2) 套件組 II
```
pip install -r requirements.txt
```

------------------------------------------------------------------
(4) 安裝 C# 程式專案,<br/>
    執行安裝包:

```
EzSeg_Setup_1.0.0.3.exe
```
------------------------------------------------------------------
(5) 執行背景服務程式

```
"D:\AUTOMATION\Eazy Segmentation\Bin\EzSegServerStarter.exe"
```
------------------------------------------------------------------
(6) 用網頁瀏覽器 開啟 http://127.0.0.1:9001/
- 設定註冊碼

------------------------------------------------------------------
(7) 用 visual studio 2022 開啟 演示 專案
- D:\AUTOMATION\Eazy Segmentation\C#\EzSegClientDemo_CN.sln

------------------------------------------------------------------
# Author
**[LeTian Chang](mailto:lloydz.tw@gmail.com)**
<br/>
    
