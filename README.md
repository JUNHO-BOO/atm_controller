from google.colab import drive
drive.mount('/content/drive')
%cd /content/drive/MyDrive

!git clone https://github.com/JUNHO-BOO/atm_controller

%run /content/drive/MyDrive/atm_controller/atm_controller.py
%run /content/drive/MyDrive/atm_controller/atm_controller_test.py
