# cybersec-kali
Repositório de testes de cybersegurança utilizando Kali Linux e Metasploitable 2

Nos primeiros testes utilizamos nMap e Medusa como ferramentas de ataques do tipo Brute-Force e Password Spraying.\n
No nMap utilizamos o comando nmap -sV -p 21,22,80,445,139 <ip> para varrer as portes indicadas no comando e visualizar sua condição;\n
Com o Medusa, utilizando uma wordlist básica, aplicamos as técnicas em serviços de FTP e SMB para identificar usuários e senhas possíveis de acesso. O comando utilizado foi: medusa -h <ip> -U <file-users> -P <file-passwords> -M <protocol> -t <threads> -T <time>.\n
As imagens com resultados estão disponibilizadas abaixo. 

<img width="1173" height="840" alt="kali-nmap" src="https://github.com/user-attachments/assets/5f1b34f7-7173-412d-90d6-b274460725b8" />
<img width="1173" height="840" alt="kali-2" src="https://github.com/user-attachments/assets/03067160-2a2c-4f4c-a01c-5affe66a638d" />
<img width="1173" height="840" alt="kali-3" src="https://github.com/user-attachments/assets/c2432415-827c-4da0-b792-18377ec8adc7" />
