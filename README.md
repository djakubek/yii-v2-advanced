# yii-v2-advanced - Instalacja i uruchomienie na Windows (xampp)


1. Download archive yii-advaced from http://www.yiiframework.com/download/
2. Rozpakuj archiwum do katalogu w lokalzacji c:\xampp\htdoc\6\
3. Uruchom wiersz polecenia i przejdź do katalogu c:\xampp\htdoc\6\
4. Uruchom polecenie init ( jeślś pojawi się problem z php.exe oznacza to brak zmiennej środowiskowej w systemie windows). Do zmieninnej PATH dodać ścieżkę c:\xampp\php. Problem powinien ustąpić.
5. Uruchom środowisko Deweloperskie
```batch
Yii Application Initialization Tool v1.0

Which environment do you want the application to be initialized in?

  [0] Development
  [1] Production

  Your choice [0-1, or "q" to quit] 0

  Initialize the application under 'Development' environment? [yes|no] y

  Start initialization ...

   generate backend/config/main-local.php
   generate backend/config/params-local.php
   generate backend/config/test-local.php
   generate backend/web/index-test.php
   generate backend/web/index.php
   generate backend/web/robots.txt
   generate common/config/main-local.php
   generate common/config/params-local.php
   generate common/config/test-local.php
   generate console/config/main-local.php
   generate console/config/params-local.php
   generate frontend/config/main-local.php
   generate frontend/config/params-local.php
   generate frontend/config/test-local.php
   generate frontend/web/index-test.php
   generate frontend/web/index.php
   generate frontend/web/robots.txt
   generate yii
   generate yii_test
   generate yii_test.bat
   generate cookie validation key in backend/config/main-local.php
   generate cookie validation key in frontend/config/main-local.php
      chmod 0777 backend/runtime
      chmod 0777 backend/web/assets
      chmod 0777 frontend/runtime
      chmod 0777 frontend/web/assets
      chmod 0755 yii
      chmod 0755 yii_test

  ... initialization completed.

Press any key to continue . . .

```

6. Uruchom przeglądarkę WEB http://localhost/6/frontend/web/index.php

