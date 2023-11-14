# Eazy Screw (Demo)
[![LeTian Space](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://lloydztw.github.io/mysite/)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
[![LeTian FB](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/letian.chang)
[![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lloydz.tw@gmail.com)

A Screw Detection server written in pytorch.

------------------------------------------------------------------

## History
- 14 Nov 2023 - Version 1.0.0.1
    - 支援純 cpu
    - Revised by [@letian Chang](https://lloydztw.github.io/mysite/).
<br>
<br>

- 12 Nov 2023 - Version 1.0.0.0
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

- 7z 19.00 版 (一定要此版)
    - https://www.7-zip.org/a/7z1900-x64.exe

<br/><br/>

------------------------------------------------------------------
# 【從 JetEazy Ftp Server 下載 相關安裝檔案】
- 下載 C# server 安裝包
    - https://download.jeteazy.com/LeTian/EzSeg/setup_EzScrew/EzScrewDemo_Setup_1.0.0.1.exe

- 下載 預建好的 純 cpu 虛擬環境
    - https://download.jeteazy.com/LeTian/EzSeg/setup_EzScrew/ez_seg_cpu.7z

- 或是 取得 萬子 預建好的 CUDA 11.7 虛擬環境
    - ez_seg.7z

- 分次下載以下個別檔案 (如果使用 連線官網 建置 python 虛擬環境 才需要)
    - https://download.jeteazy.com/LeTian/EzSeg/install/install_pytorch_cuda.cmd
    - https://download.jeteazy.com/LeTian/EzSeg/install/.condarc_zju
    - https://download.jeteazy.com/LeTian/EzSeg/install/requirements.txt
    - https://download.jeteazy.com/LeTian/EzSeg/install/post_check_pytorch.py

<br/>
至暫存資料夾, d:\tmp\EzScrew
<br/>
<br/>

------------------------------------------------------------------
# 【方法 A: 直接複製 預件好的 python 虛擬環境】
- 將解開後的 ez_seg 或 ez_seg_cpu 資料夾, 直接複製到
c:\anaconda3\envs 
下面
<br/>
<br/>
<br/>
------------------------------------------------------------------
# 【方法 B: 連線官網 建置 python 虛擬環境 才需要】
按下 &#8984; + R 鍵, 然後輸入 cmd, 來開啟 Windows 終端機 視窗.
依序 鍵入 以下指令: 
<br/>
<br/>
(B1) 跳到 暫存資料夾, d:\tmp\EzScrew
```
d:
cd d:\tmp\EzScrew
```
(B2) 如果是 CUDA v11.3, 輸入以下指令 <br/>     
```
install_pytorch_cuda.cmd 11.3
```
(B3) 如果是 CUDA v11.7, 輸入以下指令 <br/>  
```    
install_pytorch_cuda.cmd 11.7
```
(B4) 請耐心等待 偉大的防火牆 辛勞的 為人民服務, 成功後, 最後會出現以下類似的版本訊息:
```    
torch= 1.12.1
cuda= 11.3
gpu= 1
```
<br/>
<br/>

------------------------------------------------------------------
(1) 開啟 Anaconda Prompt 的終端機, 輸入以下指令

```
conda init
```

------------------------------------------------------------------
(2) 安裝 C# 程式專案,<br/>
    執行安裝包:

```
EzScrew_Setup_1.0.0.1.exe
```

------------------------------------------------------------------
(3) 執行背景服務程式

```
"D:\AUTOMATION\Eazy Screw\Bin\EzScrewServerStarter.exe"
```

------------------------------------------------------------------
(4) 用網頁瀏覽器 開啟 http://127.0.0.1:9001
- 設定註冊碼
<br/>

------------------------------------------------------------------
(5) 用 visual studio 2022 開啟 演示 專案
- D:\AUTOMATION\Eazy Screw\C#\EzScrewClientDemo_CN.sln
<br/>
<br/>
<br/>

------------------------------------------------------------------
# Author
**[LeTian Chang](mailto:lloydz.tw@gmail.com)**
<br/>
    
