# sensu-demo
Sensu demo para Edrans


#Generate sha-512 password

python -c "from passlib.hash import sha512_crypt; print sha512_crypt.encrypt(raw_input('clear-text password: '))"
