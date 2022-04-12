На тонком клиенте
-----------------
Администрация- конфигурация сервера, Серверы
Workflow Process Manager RUS
FINS Object Manager (RUS)

Из командной строки
cd C:\Siebel\8.1.1.11.0\ses\siebsrvr\BIN
srvrmgr /g test.site  /e 01server  /u PUPKIN  /p PUPKIN
srvrmgr /g test.site  /e 07server /u TOROPOVAAA  /p TOROPOVAAA

set evtloglvl % = 4 for component FINSObjMgr_rus
set evtloglvl % = 4 for component WfProcMgrRUS

На толстом клиенте
-----------------
Настраивается в переменных окружения, см скриншот
