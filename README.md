# CeSIUM Newsletter

Modo de utilização:
- Editar Newsletter.html mantendo a estrutura, adicionando css dentro do cabeçalho do próprio ficheiro.
- Converter o código todo para colocar o css inline em todos os elementos no site http://zurb.com/ink/inliner.php
- Colocar o código convertido dentro da variável _message_ do ficheiro send_mail.rb.
- Editar as configurações de SMTP no topo do ficheiro send_mail.rb
- Correr no terminal ruby send_mail.rb
