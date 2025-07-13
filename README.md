# OCTRA教程
如果没有新的github账号去创建个，然后按下列步骤操作

打开：https://github.com/codespaces 创建空白模版

终端指令处输入：

     sudo apt install python3 python3-pip python3-venv python3-dev -y


输入：

          
     git clone https://github.com/octra-labs/octra_pre_client.git
     cd octra_pre_client

     python3 -m venv venv
     source venv/bin/activate
     pip install -r requirements.txt

     cp wallet.json.example wallet.json

     
接着修改文件导入钱包和B64秘钥+CTRL+O+enter+x保存退出

          nano wallet.json

启动UI界面

          python3 -m venv venv
          source venv/bin/activate
          python3 cli.py

![629cb61c93a42b8a4cee6a2bc690917](https://github.com/user-attachments/assets/ce89df3d-3d1f-4ecc-87b5-f063ae26d9b8)




     
     
