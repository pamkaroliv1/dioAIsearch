# dioAIsearch
Azure AI service
criamos um novo recurso em AI search, criamos um novo  nome e escolhe em price opção basic e cria e aguarda finalizar.
No segunda parte criamos um recurso, em AI+ Machine leaning, escolhemos serviços cognitivos e criamos um novo recurso, depois criamos uma conta de armazenamento em storage account
escolher o grupo de recursos que vc criou anteriormente, colocar um nome que não seja generico, a região bom deixar padrão.
desempenho escolher o standard
redundancia: LRS(armazenamento com redundancia local)
depois cria.
vamos em nossa storage account vamos em configuração.
e em Permitir acesso anônimo ao Blob habilitamos e salva.
em Armazenamento de dados vamos em containeres e em criar novos containeres, colocamos o nome do containe com letras minusculas e sem caracteres especiais, e o o nivel de acesso container(acesso de leitura anonimo para containeres de blob) e cria.
Depois de pronto clica no que foi criado, e faz o uplaod dos reviews, que esta no link de documentação https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html
depois de carregar os arquivos, vamos no mecanismo em AI search escolhe o criamos e vamos em importar dados.
ao abrirmos a pesquisa conseguimos filtrar com palavras chaves, nomes, o que tiver nas reviews eles filtram.
