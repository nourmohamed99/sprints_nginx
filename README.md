# sprints_nginx

- create basic website to print hello sprints in index.html
- install nginx
- sudo apt update
- sudo apt install nginx 

![change in html file](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/19d5f92e-d238-423c-b10d-8e22c49e9c4e)

![htmlcode](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/ba25b7e3-6f0a-4e13-ae74-54f32b4ee528)

![html](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/81330d53-0b28-404f-941d-74572eae5141)


 - configure the same website to serve traffic with SSL self signed certificate
 (with the same steps as above)
 
 
 - open notepad++ as adminstrator then open c:/windows/system32/drivers/etc/hosts
 - and add the public ip of the instance running and domain
 - ![localhost](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/abcde1ef-180b-42bb-82d3-8a6d6895ac19)

 
 ![bash](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/a171e3cf-3f56-460d-805a-68159f3d9cab)
![bash code](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/b13cf2fc-acb3-4762-b8c8-172e9a571921)

![path of the key](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/307a906a-a627-4ddd-8819-d7322a988e03)



![change in the default file command](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/da3921ec-6ac6-43be-a735-8d959dc0afe6)

![default file](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/a59fe073-9710-4be3-a8ca-f2e33202ea04)

- copy the rootCA.crt in a textfile (desktop) and the change extension instead of .txt to .crt 

![rootCa](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/4c949d34-c628-4350-b1de-7f70a718c204)
- then open manager user certificates 
- right click in a empty space 
- select all tasks
- select import
- next
- browse certificate created in desktop 
- then next and finish 

-open terminal in instances and restart nginx
- sudo nginx -t
- sudo systemctl restart nginx

- open microsoft edge private browser 
- and type https://nour.com
- it should change from this  
- ![notsecure](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/9f63aa36-c27c-48a3-ac2e-ccf4320dfd3f)
- to this 
![secure](https://github.com/nourmohamed99/sprints_nginx/assets/88977873/bd76570c-27f0-4add-95e6-9396ff802efc)

