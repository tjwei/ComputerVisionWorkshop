# ComputerVisionWorkshop
Code for Computer Vision Workshop
### 安裝環境

* 下載並且安裝 Anaconda 3.x 版本， 請盡量安裝 64-bit 版本。
* clone 或者下載並解開（右邊偏上綠色的 Clone or download, 選 Download zip）本 repo
* 在 anaconda console 下， cd 到本專案目錄， 執行 conda env create -f environment.yml
* 如果需要更新或者網路中斷，可以 conda env update -f environment.yml
* 最後執行 . activate opencv_intro (windows 直接打 activate opencv_intro)
* 然後輸入 `jupyter notebook --NotebookApp.iopub_data_rate_limit=10000000000` 打開 notebook

如果安裝上有困難， 可以用 Microsoft 帳號， 使用雲端環境執行 https://notebooks.azure.com/tjwei/libraries/fm00AFlHGT0 進入 azure notebook 後，Clone 然後執行 setup.py 後，即可使用(部份功能)
