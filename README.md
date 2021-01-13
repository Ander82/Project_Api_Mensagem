# Project_Api_Mensagem
Checar a comparação de texto conforme requisitos.
mensagens com telefone inválido deverão ser bloqueadas(DDD+NUMERO);
mensagens que estão na blacklist deverão ser bloqueadas; (ver blacklist)
mensagens para o estado de São Paulo deverão ser bloqueadas;
mensagens com agendamento após as 19:59:59 deverão ser bloqueadas;
as mensagens com mais de 140 caracteres deverão ser bloqueadas;
caso possua mais de uma mensagem para o mesmo destino, apenas a mensagem apta com o menor horário deve ser considerada;
o id_broker será definido conforme a operadora; (ver broker x operadora)
