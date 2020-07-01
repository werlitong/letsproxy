# LetsProxy

Sem firula, instale o Go v1.12+ caso não tenha-o, clone o repositório e execute "go build" dentro da pasta diretório.

# Requisitos

Porta 80 e 443 desbloqueada no Firewall.
Mais info em> https://letsencrypt.org/pt-br/docs/challenge-types/


## Utilização
>
./letsproxy --domain example.com --to http://localhost:3000
ou
./letsproxy -d example.com -t http://localhost:9090

# Varios hosts
./letsproxy --domain example1.com,example2.com,example3.com -t http://localhost:8080

