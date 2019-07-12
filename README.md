# Analisando o Resultado de uma Campanha de Marketing
### https://www.datascienceacademy.com.br

A “ABC Advertising Corporation” é uma empresa de publicidade que usa métodos de redirecionamento para enviar anúncios para usuários on-line. Um produto da empresa, chamado Remarketing do Call Center, usa os dados de registro do call center para fazer o que em Marketing se chama “retarget” (investir em outras campanhas de Marketing) para marcar aqueles consumidores on-line que não fizeram uma compra.

O objetivo é determinar os resultados de uma das campanhas de publicidade da empresa, para o cliente “Agência de Viagens Borboleta Feliz”. Os resultados da campanha publicitária da “Agência de Viagens Borboleta Feliz” são apresentados nos dois conjuntos de dados seguintes:

Dataset 1: call_sem_vendas.csv
As observações neste datasetsãodeindivíduos que chamaram o call center da Agência de Viagens, mas não fizeram uma compra.

Dataset 2: call_vendas_reservas.csv
As observações neste datasetsão os clientes que telefonaram para o call center Agência de Viagens Borboleta Felize fizeram uma reserva.

O esquema de dados para ambos os datasets é fornecido abaixo:

Caller_ID - Um ID exclusivo gerado para cada chamada telefônica recebida para o call center
Sessão - O ano / mês / dia / hora de cada chamada telefônica recebida para o call center
Incoming_Phone - Número de telefone identificado usando a identificação do chamador
Contact_Phone - Número de telefone que o chamador envia
Test_Control - Etiqueta da experiência

Definição do Problema de Negócio:
A Agência de Viagens Borboleta Feliz possui os dados de todos os clientes que receberam campanhas de Marketing da empresa, mas que não comparam um pacote de férias.

Problema de negócio: Devemos continuar investindo nesses clientes (retarget)?
