1. VirtualBox Версия 6.1.26_Ubuntu r145957.  
2. Vagrant 2.2.19 (apt install vagrant).  
3. Терминал GNOME 3.36.2.  
4. Ubuntu 20.04.3 LTS (GNU/Linux 5.4.0-91-generic x86_64).  
5. 
- Оперативная память: 1024МБ  
- Процессоры: 2  
- Видеопамять: 4 МБ  
- Жесткий диск: 64.00 ГБ  
6. vim Vagrantfile  
- config.vm.provider "virtualbox" do |vb|  
  - vb.memory = "1536"  
  - vb.cpus = 3  
- end  
7. vagrant ssh  
- ls -lha  
- whoami  
- touch readme  
- mkdir test  
8. HISTFILESIZE - 627  
  HISTSIZE - 630  
  ignoreboth - это сокращение для ignorespace и ignoredups.  
- ignorespace - строки, начинающиеся с пробела не сохраняются.  
- ignoredups - строки, соответствующие предыдущей записи истории, не сохраняются.   
9. строка: 206.  
Выполняется в текущей среде оболочки. Выполняет подстановку элементов из списка. {list;}   
10. touch {1..100000}.txt  
  максимум: 116098 файлов. Больше нельзя, слишком длинный список аргументов
11. проверяет наличие каталога /tmp. 1 или 0 (true, false)  
12. vagrant@vagrant:~$ mkdir /tmp/new_path_directory/  
vagrant@vagrant:~$ cp /bin/bash /tmp/new_path_directory/  
vagrant@vagrant:~$ PATH=/tmp/new_path_directory/:$PATH  
vagrant@vagrant:~$ type -a bash  
bash is /tmp/new_path_directory/bash  
bash is /usr/bin/bash  
bash is /bin/bash  
13. at – это утилита командной строки, которая позволяет планировать выполнение команд в определенное время.  
batch - ланирует задания и выполняет их в очереди пакетов, когда позволяет уровень загрузки системы. По умолчанию задания выполняются, когда средняя загрузка системы ниже 1,5.  
14. vagrant halt  

    
    
