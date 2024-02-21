# Arquitetura em cloud de uma solução IOT

Primeiros passos antes de criar uma Arquitetura do 0, é primeiro
ṕegar uma arquitetura de referenência, pois não precisamos e não devemos
reiventar a roda, pois cloud == $money$ e nã podemos arriscar.

Dado um caso de uso, temos

O primeiro passo é termos um dispositivo IOT que enviará dados para nosso cloud gateaway,
esse cara será responsável por entender o tipo de requisição que ele recebeu e estinar para
o caminho especifico.
