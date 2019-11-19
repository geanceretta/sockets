# sockets

Implemente o problema do Jantar de Gauleses usando Sockets
Utilize sockets Unix (sugerido) ou na interface 127.0.0.1
Deve, obrigatóriamente ter um executável, código fonte separado para o produtor e outro para o consumidor
O programa deve permitir um 1 produtor e N consumidores
O tempo do produtor e do consumidor deve ser aleatório
Para alcançar sincronização os o processos Gaules enviam mensagens vazias para o Cozinheiro para cada Javali Grelhado comido. O Cozinheiro então acordará quando M mensagens vazias estiverem chegado (M javalis grelhados), cozinhará os Javalis as os enviará para os Gauleses. Caso não haja M mensagens vazias Cozinheiro dorme.
O controle do consumidor que enviou a mensagem pode ser feito usando a própria mensagem (cabeçalho) ou pela estrutura de resposta do método conect ou utilizando uma arquitetura do tipo mailbox.
