Colab运行时添加这两行代码到第一行gitclone下面即可</br>
!git clone https://github.com/wdigfuew/Novelai-ToChinese </br>
!cp -r /content/Novelai-ToChinese/** /content/stable-diffusion-webui/</br>
此项目是B站up：只剩一瓶辣椒酱 的汉化包</br>
</br>
Colab笔记本：
https://colab.research.google.com/drive/116NIJSwF3q2AW-T4qJPhKwMxdkYjHd35?usp=sharing
</br>
本地联网部署方法：
打开webui-user.bat【改成txt后缀或用编译器打开】</br>
![image](https://user-images.githubusercontent.com/49783267/196210118-8f2b2a24-4ffc-4703-adc7-60c89571200d.png)</br>
在 COMMANDLINE_AGS=后输入"--share"是互联网部署  "--listen"是局域网部署，ipv4地址+:7860【例192.168.2.1:7860】
