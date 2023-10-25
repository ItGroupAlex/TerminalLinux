
# Подключение к GitHub используя SSH:   

1.) генерируем SSH-key: заходим, например в Git Bush, и вводим:   
							    `$ ssh-keygen`  
						  	  * при желании назначаем пароль;   
						  	  * открываем созданный публичный ключ *.pub и копируем содержимое текста.  
2.) вставляем в настройках Git Hub - SSH  
3.) подгружаем данные login & e-mail:  
		  `$ git config --global user.name "ItGroupAlex"`  
		  `$ git config --global user.email "ItGroupAlex@gmail.com"`  
