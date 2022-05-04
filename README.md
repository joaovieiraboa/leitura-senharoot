ENTRAR E DEFINIR ACESSO ROOT:  
 
1 - Primeiro Comando para entra em acesso root. 
  
sudo -i 
___ 
2 - Segundo comando para alterar Senha root. 
  
bash <(wget -qO- https://raw.githubusercontent.com/leitura/senharoot/main/senharoot.sh)  
___ 
  
  
3 Comando ABRIR PORTAS SERVER ORACLE:  
  
1° - sudo apt-get update  
2° - sudo apt install firewalld    
3°  
 
sudo firewall-cmd --zone=public --permanent --add-port=1194/tcp && sudo firewall-cmd --zone=public --permanent --add-port=7505/tcp && sudo firewall-cmd --zone=public --permanent --add-port=80/tcp && sudo firewall-cmd --zone=public --permanent --add-port=443/tcp && sudo firewall-cmd --zone=public --permanent --add-port=8088/tcp && sudo firewall-cmd --zone=public --permanent --add-port=8080/tcp && sudo firewall-cmd --zone=public --permanent --add-port=444/tcp && sudo firewall-cmd --zone=public --permanent --add-port=8799/tcp && sudo firewall-cmd --zone=public --permanent --add-port=7300/udp && sudo firewall-cmd --zone=public --permanent --add-port=7900/udp && sudo firewall-cmd --zone=public --permanent --add-port=7600/udp && sudo firewall-cmd --zone=public --permanent --add-port=7500/udp 
___ 
 
4° Dar este comando depois que abrir todas as portas 
 
 sudo firewall-cmd --reload  
___ 
 
5° Lista todas as portas abertas  
 sudo firewall-cmd --zone=public --list-ports


nosso telegram https://t.me/Vaniosshplus
