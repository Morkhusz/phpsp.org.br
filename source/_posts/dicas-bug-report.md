
### 5 dicas para escrever um bom *bug report*

1.  Um report deve ser reproduzível

> Não irá servir de muita coisa um report ser feito e o time de desenvolvimento não conseguir reproduzir o comportamento para poder pensar em tratativas. Defina com a equipe de qualidade como estruturar o passo-a-passo para a reprodução do bug encontrado.

2. Relate o comportamento atual e o esperado

> É muito comum encontrar tickets com a mensagem "pagamento não funciona" e nada mais... Este tipo de mensagem só pode agregar uma coisa: retrabalho! O time de desenvolvimento obrigatoriamente terá que ou contatar a qualidade ou sair testando os fluxos de pagamento para entender o que não está funcionando de fato. Procure sempre detalhar o comportamento atual para o desenvolvimento se achar e também relatar qual o comportamento esperado para o desenvolvimento poder guiar sua tratativa com uma base sólida do que se espera.

3. Um bug por report

> Se eu pudesse dar apenas uma dica, seria essa! Enquanto desenvolvedor posso afirmar que é terrível receber uma listinha de bugs num card e cuidar de tudo como se fosse uma coisa só. Procure organizar os bugs de forma que fique um bug por relatório/atividade pois desta forma o desenvolvimento terá um foco maior e até melhorará a rastreabilidade deste bug futuramente. Em casos muito específicos um bug pode estar relacionado a outro, neste cenário não vejo problema em ter mais de um bug por atividade mas procure pensar com carinho se não seria possível tratar cada um isoladamente.

4. Use sempre o build mais atual e evite duplicidade

> É muito comum um report que foi testado em um ambiente que ainda não está atualizado, criar o report e quando o desenvolvimento vai olhar este bug já foi tratado no build atual, principalmente se existe a cultura de priorização de bugs! Outra coisa comum de acontecer é report de bug que já foi reportado anteriormente, ao invés de fazer um novo report procure atualizar o antigo (se for necessário) e dependendo até aumente a prioridade. Quando for executar uma bateria de testes de forma preventiva ou estiver "caçando" bugs busque sempre utilizar a versão mais atual da aplicação para evitar este comportamento.

5. Use fatos e evite personificações

> Ao reportar um bug procure sempre se utilizar de fatos que aconteceram durante a fase de descoberta deste bug e procure não ser opinativo, lembre das dicas 1 e 2! Evite ao máximo "dar nome aos bois", mesmo que você saiba quem desenvolveu a funcionalidade que acabou retornando com bug. Relatórios de bug são uma forma de documentação do seu sistema e não vai agregar em nada citar o nome de fulano ou do time XPTO nesta documentação. Isso irá evitar conflitos entre as equipes e evitar que alguém do time de desenvolvimento fique achando que alguém do time de qualidade está apenas pegando no pé.
