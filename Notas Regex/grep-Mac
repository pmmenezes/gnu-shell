#!/bin/bash
## Filtra os enderecos MAC usando o comando ip addres show 
ip address show | grep -oE '([[:xdigit:]]{2}:){5}[[:xdigit:]]{2}' | grep -Ev '((f|0){2}:){5}\2{2}'
