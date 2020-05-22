# LinuxShell_semaphore
send signal by using KILL 

* 指令操作語法

          [kill [-signal] pid]

* 終止

          ^C
          
          ^D // Unix 不支援

          [kill [-1] pid] // 掛斷 訊號名稱：SIGHUP

          [kill [-9] pid] // 強迫終止 訊號名稱：SIGKILL

          [kill [-15] pid] // 終止 訊號名稱：SIGTERM

* 暫停

          ^Z // 暫停執行 suspend
          
          
* execution in foreground


      $ fg <cmd>
             
   https://github.com/QueenieCplusplus/LinuxShell_fgbg/blob/master/README.md#foreground-前景執行
         
         
* execution in background


      $ bg <cmd> 
        
  https://github.com/QueenieCplusplus/LinuxShell_fgbg/blob/master/README.md#background-背景執行     
        

* help

          ✗ kill -l

         HUP 
         INT 
         QUIT 
         ILL 
         TRAP 
         ABRT 
         EMT 
         FPE 
         KILL 
         BUS 
         SEGV 
         SYS 
         PIPE 
         ALRM 
         TERM 
         URG 
         STOP 
         TSTP 
         CONT 
         CHLD 
         TTIN 
         TTOU 
         IO 
         XCPU 
         XFSZ 
         VTALRM 
         PROF 
         WINCH 
         INFO 
         USR1 
         USR2
