#  Lesson 31

1) Eles são acessaddos pela própria classe e não precisam instanciar um objeto da classe

2) Um protocolo define um ou mais métodos e podendo ser acessado por uma classe ou struct

3) UITableViewDataSource e o UITableViewDelegate

4) numberOfRowsInSection = define o numero de linhas na seção
   cellForRowAt = define o que vai dentro de cada célula
   
5) Dentro do método a var/let so existe dentro do contexto do método. No struct/class tu pode ser acessado passando o nome do struct/class para um variável assim as var/let podem ser usadas acessadas no novo arquivo ou também pode ser acessados por meio de herança

6) 

7) São todas as partes que a view passa, antes de carregar, carregada, depois de carregada e etc...

8) Carregar a view quando ela não existe é invocado antes da viewDidLoad. Usado quando a view não existe  e precisamos carregar ela, não é recomendado usar a loadView quando a view ja existe. É executado apenas uma vez

9) É executado quando a view foi carregada. Podemos definir alguns layouts para a view, invocar outros métodos e etc... e é invocado apenas uma vez
 
10) É tudo o que tu vai fazer antes da view aparecer, após a viewDidLoad. E é executado todas vez que uma view irá aparecer.

11) viewWillLayoutSubviews avisa que irá acontecer uma modificação de layout na subview

12) Notificar a viewController de que sua visualização acabou de apresentar suas subviews.

13) Após a viewWillAppear, notifica de que sua exibição foi adicionada, usualmento usado  para começar uma animação ou video

14) viewWillDisappear é chamado quando é solicitado a remoção de uma view e notifica o controlador de exibição que sua exibição será removida\

15) Quando tu quer notificar de que sua exibição foi removida, encerrar algumas notificações ou sons, audio e etc

16) Desinicializador e o init inicializa as propriedades ocupando espaço na memória e o deinit desinicializa elas liberando o espaço da memória

17) didReceiveMemoryWarning avisando que a memória esta ficando muito cheia com a possibilidade do app crashar

18) loadView, viewDidLoad, viewWillAppear, viewDidAppear

19) Porque é importante saber quais métodos são executados em diferentes momentos para assim fazer as devidas alterações nos lugares corretos.
