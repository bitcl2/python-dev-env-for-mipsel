# python-dev-env-for-mipsel<br>
Some python dependents run in mipsel cpu,better in a mipsR2 ,1004k,1.06Ghz.<br>
----------------------
  Begain
  ---------------------
  >>Some times you may find,we can't install some libs by 'pip install'	especially when it's in a Embedded system.<br> 
  >>The libs as fllows can run in mips/mipsel based on mipsR2,1004k.<br>
  >>In fact,you can run them on other cpu as if it's based on mips with linux-GUN.<br>
  >>That's all.Then to install it.<br>

  Install
  -------------------
  >>1.pip -r reqiure.txt<br>
  >>2.pip install xxxx.whl<br>
  (xxx is what you wanna to install.<br>
  ----------------------
  #好久没有跟新了，当初编译这个的初衷是在执行文件的时候库缺失，由于mipsel架构下本身库不全，安装也无法安装，最后通过虚拟环境交叉编译出可用的
  文件，再提取。
  后来的有空放上来。
  
