# crud

{module} = Product / Post / News / User

1. make a model of that module.... 
------ php artisan make:model {module} -m
2. make folder and files
------ {views/Backend/Module} --> make 3 files

                                  1. index.blade.php
                                  2. create.blade.php
                                  3. edit.blade.php
3. create {ModeleController}
---- php artisan make:controller Backend/{ModuleController} -r
4. Open {ModuleController} and add these 3 views
                                  1. index.blade.php
                                  2. create.blade.php
                                  3. edit.blade.php


