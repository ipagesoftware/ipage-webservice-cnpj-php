# ipage-webservice-cnpj-php
Busca dados da empresa e do endereço pelo CNPJ da empresa

Como funciona um Web Service?
Web Service é uma solução utilizada na integração de sistemas e na comunicação entre aplicações diferentes. Com esta tecnologia é possível que novas aplicações possam interagir com aquelas que já existem e que sistemas desenvolvidos em plataformas diferentes sejam compatíveis.

A que se destina este Web Service?
Este Web Service tem por finalidade consultar Códigos de endereçamento Postal (CEP) de todo o Brasil de forma simples e descomplicada. Estas informações podem ser acessadas pelo CNPJ da empresa.
As informações retornadas após a consulta ao Web Service possui diversos formatos, são eles: XML, JSON, JavaScript, formato texto PIPED, formato texto Querty.

#Definição dos parâmetros.
O CNPJ informado deve conter apenas números, em caso de valores inválidos passados ao Web Service o mesmo realizará automaticamente um filtro, deixando passar apenas números. Se mesmo assim o valor informado não satisfazer o critério, uma mensagem de erro será reportada.

O formato a ser retornado pela consulta deve ser passado na URL junto com o CNPJ e deve ser compatível com o esperado pelo Web Service.
Os valores válidos são: XML, JSON, JavaScript, formato texto PIPED, formato texto Querty.

A chave de acesso ao Web Service é obrigatória e deve ser passada na URL junto com o CNPJ, Caso não possua uma chave de acesso, solicite no nosso web site: https://rapidapi.com/diogenes/api/ipage_cep/details

Os principais formatos de retorno são:
PIPED, JSON, Querty, XML, Javascript

Veja no site o exemplo antes de realizar o download: https://www.ipage.com.br/ws/exemplos/php/cnpj/

