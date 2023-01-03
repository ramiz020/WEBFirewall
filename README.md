# WEBFirewall (DJANGO)

![alt text](https://cdn.freelogodesign.org/files/4835a2b3c7814aeb9d0527ea5c23e472/thumb/logo_200x200.png?v=0)

This WEBAPP allows you to control inbound and outbound by adding rules to your firewall. 

# INSTALLATION

run this commands in cmd
```cmd
$ pip install -r requirements.txt
```


```cmd
$ python manage.py runserver
```

and after starting server go to your browser and type **127.0.0.1:8000**

# HOW TO USE

You must login for using this app. If you haven't account click REGISTRATION  button and after registration click login. After login your account you'll redirect HOME page.
Click ADD RULES button and add your rules. After clicking SAVE button your rules will appear in home page.


| Buttons       | Do           |
| ------------- |:-------------:|
| START         | add your added rules to firewall and enable them |
| STOP          | disable your added rules      |
| BlOCK ALL     | Block all inbound or outbound ports and protocols      |
| ALLOW ALL     | Allow all inbound or outbound ports and protocols      |
| BlOCK PING    | Block ICMP echo in your inbound or outbound rules      |
