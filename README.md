#GreenHouse Projetc – IoT UFSCAR
###############################
Este relatório visa introduzir ao leitor o projeto de estufa inteligente desenvolvido pelos alunos do grupo de IoT  no ambiente da UFSCar. O intuito do projeto é desenvolver uma estufa, isto é, um ambiente controlado, onde serão inseridos três plantas para que seu crescimento seja observado analisado pelos alunos ou por terceiros. Isso sera feito utilizando dos recursos tecnológicos forcencidos pela placa integrada Galileo com a adição de diferentes módulos. As informações tais como a umidade do solo vão ser registradas em um banco de dados e repassadas em uma página web orgnizando os diferentes dados retirados e facilitando o acompanhamento feito sob o projeto.

###Detalhamento do processo

O processo adotado pelos alunos visa solidificar as bases do desenvolvimento e então de forma progressiva implementar a Estufa. Para isso primeiro deve ser feita a aquisição do ambiente e a seleção dos vegetais que serão utilizados no periodo de acompanhamento. Tanto o vegetal como o ambiente da estufa ja foram selecionados, e serão utilizadas, portanto, um vetegal da espécie cassia fistula e uma caixa de plástico de porte para 55L totalmente transparente para permitir a passagem de luz e circulação do ar. No que tange ao ambiente interno, a estufa espera-se apenas a coleta de dados por parte da equipe com exceção da inserção de luzes LED de cores pré-escolhidas como verde, vermelho e liláz para as diferentes plantas visto que sabe-se que a frequência da cor que incide no vegetal influencia diretamente na realização da fotossintese e, por sua vez, no seu crescimento. Fora isso serão medidos: A umidade do ar, a umidade do solo, o ph do solo e a temperatura ambiente. Todos os dados deverão ser coletatos pelo Galileo que será parte fundamental para a relação tecnologia-equipe.

###Apresentação de resultados

Após a aquisição e desenvolvimento da captura de informações ambientais pelo Galileo, será necessario organizar os dados de forma sucinta para facilitar o acompanhamento do estudo. Para isso, todos os dados capturados serão armazenados em um banco de dados e transmitidos dinâmicamente a uma página da web. O ambiente construído pela equipe possui apenas duas páginas, as quais a principal se trata de uma dashboard que apresenta ao usuário as informações mais recentes da estufa, como umidade do ar e temperatura. Para auxiliar ainda mais o processor de acompanhamento visa-se também permitir que sejam enviado tweets alertando das necessidades mais cruciais como a de manter o solo umido. Na página principal também constam outros gráficos a fim de permitir que não só o estado atual do acompanhamento seja analisado, mas o processo como um todo mostrando o progresso da planta em torno do período de análise. A segunda página é crucial para que o sistema possa discenir como exibir a informação, isso porque se trata de um cadastro dos vegetais que serão analisados, permitindo assim, que o sistema possa informar corretamente ao usuário dos valores que são considerados ideais para a planta, sendo que diferentes espécies se adaptam melhor a ambientes específicos. Deseja-se também implementar um auto-complete baseado em um banco de dados como http://plants.usda.gov para auxiliar no processo de monitoramento e de cadastro.

###Tempo de composição e distribuição de tarefas

O tempo destinado a realização do projeto ronda em torno de três semanas. Esse tempo é suficiente para a implementação de acordo com a distribuição de tarefas pelo grupo. Pretende-se distribuir aos alunos tarefas mais especificas para que em conjunto possam compor o projeto como um todo. Assim, parte do grupo será resposável pela distribuição do vegetal e aquisição de informações pelo galileo enquanto parte se destinará ao desenvolvimento da página e a seleção de conteúdo do banco de dados bem como sua disposição.
