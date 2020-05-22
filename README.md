# LinuxShell_semaphore
send signal by using KILL 

* 指令操作語法

          [kill [-signal] pid]

* 終止

          ^C
          
          ^D // Unix 不支援

          [kill [-1] pid] // 掛斷

          [kill [-9] pid] // 強迫終止

          [kill [-9] pid] // 終止

* 暫停

          ^Z

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
