# cybersec-kali
Repositório de testes de cybersegurança utilizando Kali Linux e Metasploitable 2

Nos primeiros testes utilizamos nMap e Medusa como ferramentas de ataques do tipo Brute-Force e Password Spraying.
No nMap utilizamos o comando nmap -sV -p 21,22,80,445,139 <ip> para varrer as portes indicadas no comando e visualizar sua condição;
Com o Medusa, utilizando uma wordlist básica, aplicamos as técnicas em serviços de FTP e SMB para identificar usuários e senhas possíveis de acesso. O comando utilizado foi: medusa -h <ip> -U <file-users> -P <file-passwords> -M <protocol> -t <threads> -T <time>.
As imagens com resultados estão disponibilizadas na pasta Screenshots. 
