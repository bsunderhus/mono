# Motivação

1. crescimento da computação pervasiva.
2. cenário proposto que se beneficiária?
3. número cada vez maior de sensores disponibilizando informação em tempo real.
4. ambientes sensiveis a situação que permitem desenvolvimento de sistemas complexos de interação.

O atual crescimento de areas da computação que lidam com interações do cotidiano, como a computação pervasiva e aplicações sensíveis a contexto,
dá-se devido ao número cada vez maior de agentes coletores e produtores de informação em tempo real disponiveis na socieade, como aparelhos __smart__ (tv, geladeira, freezer, etc...) e móveis.

Estes ambientes ricos em informação contextual regem alterações de estado em aplicações sensíveis a contexto, que se adaptam para melhor atender seus usuários. A complexidade, entretanto, pode ser gerada devido ao incremental número de variaveis introduzido em tal aplicação, apresenta uma certa dificuldade ao trabalhar com tamanho volume de dados.

O seguinte cenário ilustra o potencial de complexidade.

  >Uma cirurgião plástica tem em seu escritório um freezer onde ela guarda um estoque de seringas de uma substância volátil extremamente sensível a altas temperaturas. Caso o freezer alcance uma temperatura superior a 10 graus a substância deve ser considerada inapropriada para o uso e deve ser substituída, o que pode acarretar um problema grave. Devido ao alto risco e ao preço elevado de tal substância, a cirurgiã decide instalar sensores de temperatura em seu freezer para acompanhar o estado da substância ao longo do dia. Com a ajuda de uma aplicação de monitoramento ela pode vizualizar em tempo real a temperatura do freezer e tomar medidas caso chegue em um estado crítico.

  >Em poucos dias a cirurgiã se vê farta de ter que olhar constantemente para a tela de seu monitor para garantir o estado de segurança de suas substâncias. Ela gostaria de ser avisada caso o problema esteja perto de acontecer, para que então não precisasse gastar tanto tempo observando um sensor que quase nunca muda e acima de tudo, gostaria de poder fazer o mesmo do conforto de seu aparelho eletrônico móvel, para que não necessite estar o tempo todo do lado do freezer. Com alguma complexidade a mais a cirurgiã consegue por as mãos em uma aplicação que promete ler informações do sensor e notifica-la caso a temperatura ultrapasse um determinado limite que ela impôs (8 graus por exemplo). Mais uma vez a cirurgiã se sente satisfeita com sua nova solução e praticidade, ela descobre que raramente o freezer chega a tais temperaturas e que normalmente quando chega é devido ao congelamento que impossibilita a ventilação adequada. Com a ajuda de um técnico ela descobre que o seu freeze tem uma rotina de descongelamento, porém a rotina não é muito confiavél e normalmente a temperatura do freezer sobe bastante antes de voltar a cair, o que volta a fazer com que a cirurgiã tenha que estar olhando a tela de seu celular para garantir que o freezer não está prestes a ter suas vias entupidas.

  > Mais uma vez farta com a solução precária e querendo melhorar ainda mais seu conforto a cirurgiã (que aparentemente também é uma puta cientista da computação pra mexer com uns sistemas desses...) decide testar uma aplicaçào sensível ao contexto que lhe indicaram. Nessa aplicação ela declarou seu sensor de temperatura, o limite indesejavel e também o fato de querer analisar no celular. A aplicaçao automáticamente identificou que ela também tinha em seu celular um sensor do tipo GPS que poderia informar em tempo real a localizaçao dela. Agora com mais uma variável introduzida ao problema, a cirurgiã usa a aplicação para fazer um balanceamento baseado em sua localização de GPS e a temperatura. A aplicação então calcula o tempo estimado que vai levar para o freezer alcançar a temperatura indesejável, e também o tempo estimado que levaria para ela chegar até o freezer. Baseado nessas duas estimativas a aplicação entao dispara a notificação.

Ambientes como Scene propõem simplificar o mapeamento de tal volume de dados em detecção de situações que dirão de uma forma mais clara e limpa à aplicação em que estado a mesma deveria se encontrar. 
