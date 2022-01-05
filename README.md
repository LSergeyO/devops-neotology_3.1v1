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
9. vagrant halt  

    
    
