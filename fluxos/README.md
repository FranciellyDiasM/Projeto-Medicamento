### O Aplicativo
O aplicativo possui dois tipos de login:
* Paciente: Pessoa que tomará os medicamentos
* Responsável: Responsável pelo paciente e abastecimento do sistema

### Sistema
* O sistema notifica o paciente e responsável lembrando o horário dos medicamentos
* O sistema dispara alarmes em toda situação de pendência.
* O alarme possui recorrência até a atividade ser completada
* O sistema informa como o responsável deverá abastecer a caixa
* O sistema lembrará o responsável dos momentos de abastecer a caixa

### O Paciente
* O paciente receberá uma notificação minutos antes do horário do medicamento
* O sistema enviará uma senha para abrir a caixa
* A senha abrirá somente o compartimento correto com os medicamentos daquele ciclo.
* A caixa informará uma contra-senha para desativar o alarme do paciente
* O paciente grava um vídeo tomando os medicamentos
* Caso o paciente não abra a caixa, ele não receberá a contra-senha para desativar o alarme. Sem colocar a contra-senha no aplicativo, o alarme tocará até o paciente tomar os remédios
* O paciente envia o vídeo para o responsável.

### O Responsável
* O responsável receberá uma notificação no horário do medicamento
* Aguardará o vídeo do paciente tomando os medicamentos
* Assim que o responsável receber o vídeo do paciente, ele deverá confirmar no aplicativo que o paciente tomou os medicamentos de forma correta
* Caso o responsável não confirme no aplicativo o recebimento do video, o aplicativo irá disparar o alarme de tempos até a confirmação(forçando o responsável a tomar medidas caso o paciente não tome os medicamentos no horário programado)