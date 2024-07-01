- If you are facing issue while signing in docker desktop then run docker login in ur terminal 
- then ``` gpg --full-generate-key ```
- select 1(RSA and RSA (default))
- then enter then 0 then y then give your Name, Email, Comment (docker) then ok. And set your password
- then copy ur gpg-id public key ![alt text](image.png)  or run this command to get the public-key ```gpg --list-keys```.

- then ```pass init <your_generated_gpg-id_public_key>```

- again ```docker login``` give uy credentials and password. And open docker desktop

# Error 40:43
- ```docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker ```  This command is giving error.  

- solution: use sudo in front of the command
``` sudo docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker ```



