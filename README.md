# Eazy Segmentation (Demo)
[![LeTian Space](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://lloydztw.github.io/mysite/)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
[![LeTian FB](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/letian.chang)
[![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lloydz.tw@gmail.com)

A segmentation server written in pytorch.

------------------------------------------------------------------

## History
- 15 July 2023 - Version 1.0.1.2
    - 重新製作 中國牆內專用 pytorch + cuda 一鍵式 安裝
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>

- 13 July 2023 - Version 1.0.1.0
    - 更新默認的訓練模型檔
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>

- 12 July 2023 - Version 1.0.0.3
    - 使用多線程 Demo
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>

- 10 July 2023 - Version 1.0.0.0
    - 創建版
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>

------------------------------------------------------------------
# 【Windows 平台相關工具套件】
## 請預先安裝以下套件
- Visual Studio 2022
    - 請選用 community 版本
- Anaconda (https://www.anaconda.com/download)
    - 必須安裝在 C:\anaconda3 資料夾
    - 安裝完成後, 請設定 系統環境變量 path 必須包含 c:\Anaconda3 與 c:\Anaconda3\Scripts

- nVidia CUDA tool kits 11.7 (或 11.3)
    - https://developer.nvidia.com/cuda-11-7-0-download-archive
- nVidia cuDnn 11.x
    - https://developer.nvidia.com/rdp/cudnn-download

<br/><br/>

------------------------------------------------------------------
# 【從 JetEazy Ftp Server 下載 相關安裝檔案】
- 請下載以下資料夾下面所有檔案
    - https://download.jeteazy.com/LeTian/EzSeg/install
- 或者分次下載以下個別檔案
    - https://download.jeteazy.com/LeTian/EzSeg/install/install_pytorch_cuda.cmd
    - https://download.jeteazy.com/LeTian/EzSeg/install/.condarc_zju
    - https://download.jeteazy.com/LeTian/EzSeg/install/requirements.txt
    - https://download.jeteazy.com/LeTian/EzSeg/install/EzSegDemo_Setup_1.0.1.2.exe
<br/>
<br/>
至暫存資料夾, d:\tmp\EzSeg
<br/>

------------------------------------------------------------------
# 【一鍵式 安裝 Python 環境】

按下 &#8984; + R 鍵, 然後輸入 cmd, 來開啟 Windows 終端機 視窗.<br/>
依序 鍵入 以下指令: <br/>
(1.0) 跳到 暫存資料夾, d:\tmp\EzSeg
```
d:
cd d:\tmp\EzSeg
```
(1.1) 如果是 CUDA v11.3, 輸入以下指令 <br/>     
```
install_pytorch_cuda.cmd
```
(1.2) 如果是 CUDA v11.7, 輸入以下指令 <br/>  
```    
install_pytorch_cuda.cmd 11.7
```
(1.3) 請耐心等待 偉大的防火牆 辛勞的 為人民服務, 成功後, 最後會出現以下類似的版本訊息:
```    
torch= 1.12.1
cuda= 11.3
gpu= 1
```

------------------------------------------------------------------
(2) 安裝 C# 程式專案,<br/>
    執行安裝包:

```
EzSeg_Setup_1.0.1.2.exe
```
------------------------------------------------------------------
(3) 執行背景服務程式

```
"D:\AUTOMATION\Eazy Segmentation\Bin\EzSegServerStarter.exe"
```
------------------------------------------------------------------
(4) 用網頁瀏覽器 開啟 http://127.0.0.1:9001/
- 設定註冊碼

------------------------------------------------------------------
(5) 用 visual studio 2022 開啟 演示 專案
- D:\AUTOMATION\Eazy Segmentation\C#\EzSegClientDemo_CN.sln

------------------------------------------------------------------
# Author
**[LeTian Chang](mailto:lloydz.tw@gmail.com)**
<br/>
    
