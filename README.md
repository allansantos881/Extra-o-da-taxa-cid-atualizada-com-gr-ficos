Taxa CDI Scraper
Este é um script em Python desenvolvido para capturar a taxa CDI do site da B3 (www2.cetip.com.br) e armazená-la em um arquivo CSV local. A taxa CDI é obtida em diferentes momentos ao longo de 10 iterações, e os dados são registrados no arquivo "taxa-cdi.csv".

Funcionalidades Principais
Obtenção da Data e Hora Atuais: Utiliza o módulo datetime para obter a data e hora atuais.

Captura da Taxa CDI: Faz uma requisição ao site da B3 para obter a taxa CDI, com tratamento de exceções em caso de erro na requisição.

Verificação da Existência do Arquivo CSV: Verifica se o arquivo "taxa-cdi.csv" existe. Se não existir, cria o arquivo e adiciona um cabeçalho.

Armazenamento dos Dados no Arquivo CSV: Salva a data, hora e a taxa CDI no arquivo "taxa-cdi.csv".

Espera Aleatória: Aguarda um tempo aleatório entre 1.5 e 2.5 segundos antes da próxima iteração.

Mensagem de Sucesso: Exibe "Sucesso" ao finalizar a execução do loop.

Como Usar
Certifique-se de ter o Python instalado no seu ambiente.
Instale as bibliotecas necessárias com o comando: pip install requests.
Execute o script com o comando: python nome_do_script.py.
Notas Importantes
Certifique-se de ter permissões de escrita no diretório onde o script está sendo executado para criar e escrever no arquivo "taxa-cdi.csv".

Este script é fornecido "como está", sem garantias expressas ou implícitas. Use por sua própria conta e risco.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, propor melhorias ou fazer pull requests.
