# Atos

*Caso o cartório trabalhe com controle de senhas através de dispensador manual, impressora de senha ou totem de atendimento, o Acsiv possui um módulo específico para isso. Entre em contato com nosso suporte técnico para solicitar configuração.*

Em Atos *(Menu Cartório > Atos)*, é possível criar o ato e definir o modelo que será emitido o selo.

O objetivo não será explicar o que é atos e sim, orientar como configurar ele para utilização dentro do Acsiv.

Antes de demonstrar as configurações, vamos mostrar um erro que é apresentado na tela de emissão de selo, caso seu ato não esteja configurado da forma correta:

![erro](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MODELO_NAO_CONFIGURADO.PNG)

### 1. Configurações:


Algumas configurações realizadas dentro do Acsiv serve para qualquer estado, nesse exemplo, será apresentado o estado de Minas e do Pará.

*Obs.:* Não precisa se preocupar com essas configurações, pois elas sempre são configuradas pelo nosso suporte técnico, apenas para informações, vamos demonstrar:

As configurações são definidas pelo *(Menu Notas > Configurações)*

**Minas - (MG)**

**Aba Emolumentos**

Aba emolumentos define o emolumento dos atos conforme imagem abaixo:

![emolumentos](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/CONFIGURACOES_EMOLUMENTOS_NOTAS.PNG)


**a. Autenticação:** Preenchido com emolumento de autenticação de cópia por folha.

**b. Rec. firma:** Preenchido com emolumento de reconhecimento de firma por assinatura. 

**c. Aut. eletrônica:** Preenchido com emolumento de autenticação eletrônica.

**d. Certidão:** Preenchido com emolumento de certidão, nesse caso, não foi preenchida.

**e. Cartão:** Preenchido com emolumento de reconhecimento de firma pela confecção e guarda de cartão ou ficha de assinatura.

**f. Arquivamento:** Preenchido com emolumento de Arquivamento por folha.

**Aba Etiquetas**

Aba Etiquetas é utilizada para selecionar o modelo de etiqueta *(Vamos ensinar mais adiante como criar modelo de etiquetas)* que será utilizado para emissão do selo.

![etiquetas](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/CONFIGURACOES_ETIQUETAS_NOTAS.PNG)

**a: Autenticação:** Utilizado para selecionar etiqueta de autenticação.

**b. Rec. firma:** Utilizado para selecionar etiqueta de reconhecimento de firma.

**c. Aut. eletrônico:** Utilizado para selecionar etiqueta de autenticação eletrônica.

**d. Q. nomes rec.:** Utilizado para definir a quantidades de nomes que serão apresentados na etiqueta de reconhecimento de firma.

**Pará - (PA)**

**Aba Emolumentos**

Aba emolumentos define o emolumento dos atos conforme imagem abaixo:

![aba_emolumentos](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/CONFIGURACOES_NOTAS_ABA_EMOLUMENTOS.PNG)

**a. Autenticação:** Preenchido com emolumento de autenticação de autenticação.

**b. Rec. firma:** Preenchido com emolumento de reconhecimento de firma.

**Aba Etiquetas**

Aba Etiquetas é utilizada para selecionar o modelo de etiqueta *(Vamos ensinar mais adiante como criar modelo de etiquetas)* que será utilizado para emissão do selo.

![modelo_etiquetas](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/CONFIGURACOES_NOTAS_ABA_ETIQUETAS.PNG)

**a. Autenticação:** Utilizado para selecionar etiqueta de selo digital autenticação.

**b. Rec. firma:** Utilizado para selecionar etiqueta de selo digital reconhecimento.

Esses são os campos e configurações que são necessárias para utilização nos atos.

*Antes de demonstrar a criação e configuração de um novo ato dentro do Acsiv, vamos demonstrar como criar modelos de etiquetas e modelos de selos.*

**Minas Gerais - (MG)**

Menu Cartório > Modelos de etiquetas

![modelo_etiquetas](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MENU_CARTORIO_MODELOS_ETIQUETAS.png)

Ao acessar o formulário e clicar em ![pesquisar](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/PESQUISAR.PNG), o sistema vai retornar todas as etiquetas existentes.

![etiquetas_criadas](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MODELO_ETIQUETAS_CRIADAS.PNG)

Para criar um novo modelo, basta clicar em ![novo](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/NOVO.PNG) e selecionar qual modelo gostaria de criar em ![layout](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/MODELOS_LAYOUT.PNG).

![modelo_layout](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/ITENS_LAYOUT.png)

 Note o modelo de autenticação criado:
 
 ![autenticacao](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MODELO_AUTENTICACAO_CRIADO.PNG)
 
 Ao criar, basta salvar e o modelo já estará disponível para utilização.
 
 Agora com o modelo de etiqueta criado, é possível criar o modelo de selo, pelo *(Menu  Cartório > Selo eletrônico > Modelos)*.
 
 ![menu_selo](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/CRIAR_MODELO_SELO.png)
 
 
 ![modelo_selo](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/SELO_ELETRONICO_MODELO_CRIADO.PNG)
 
  Na aba etiqueta, selecione entre os modelos de etiquetas criados no *(Menu Cartório > Modelos de etiquetas)*, nesse foi utilizado o modelo de etiquetas de autenticação eletrônica.
 
 ![modelo_selo](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MODELO_ETIQUETAS.png)


 **Pará - (PA)**
 
 Menu Cartório > Modelos de etiquetas

![modelo_etiquetas](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MENU_CARTORIO_MODELOS_ETIQUETAS.png)

Ao acessar o formulário e clicar em ![pesquisar](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/PESQUISAR.PNG), o sistema vai retornar todas as etiquetas existentes.

![modelo_etiqueta](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/CARTORIO_ATOS_MODELOS_ETIQUETAS.PNG)

Para criar um novo modelo, basta clicar em ![novo](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/NOVO.PNG) e selecionar qual modelo gostaria de criar em ![layout](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/MODELOS_LAYOUT.PNG).

![opcoes_layout](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/LAYOUT_OPCOES.png)

 Note o modelo de selo digital criado:
 
 ![selo_digital](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/MODELOS_ETIQUETAS_CRIADO.PNG)
 
 Ao criar, basta salvar e o modelo já estará disponível para utilização.
 
 Agora com o modelo de etiqueta criado, é possível criar o modelo de selo, pelo *(Menu Selos > Modelos)*.

![selo](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/SELO_MODELO_SELO.png)

![modelo_pronto](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/MODELO_ETIQUETA_PRONTO.PNG)

 Na aba etiqueta, selecione entre os modelos de etiquetas criados no *(Menu Cartório > Modelos de etiquetas)*, nesse foi utilizado o modelo de selo digital.
 
 ![etiquetas_itens](https://github.com/gislenetavaresacsiv/Atos/blob/main/PA/MODELOS_ETIQUETAS_ITENS.png)
 
 Vamos agora entender como criar e configurar um ato dentro do Acsiv.
 
 **Minas - (MG)**
 
 Acesse o *(Menu Cartório > Atos).*
 
 ![menu](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MENU.png)
 
 Ao acessar o menu, basta colocar o código da tabela e clicar em ![pesquisar](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/PESQUISAR.PNG).
 
 O sistema vai retornar a pesquisa como imagem a seguir:
 
 ![pesquisa_atos](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/1.PNG)
 
 Vamos clicar em ![abrir](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/ABRIR.PNG) para configurar o ato para utilização.
 
 ![ato_criado](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/ATO_CRIADO.PNG)
 
 Vamos demonstrar as informações que são necessárias para a utilização do ato na emissão de selos, as outras informações, são preenchidas conforme a necessidade do cartório.
 
 **a. Código:** Código gerado automático pelo sistema.
 
 **b. Descrição:** Utilizado para colocar a descrição do ato.
 
 **c. Selagem física:** Utilizado para colocar a forma de selagem física, nesse caso, como não existe selagem física, selecione a opção *Desativada*.
 
 **d. Selo Eletrônico:** Utilizado para escolher o modelo de selo eletrônico.
 
 ![modelo_selo](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/MODELO_SELO.png)
 
 Nesse exemplo foi utilizado o modelo de autenticação etiq. segurança, esse modelo de selo eletrônico foi criado em *(Menu Cartório > Selo eletrônico > Modelos)*.
 
 Se ao pesquisar o ato pelo código ou descrição da tabela do tribunal, não for encontrado na pesquisa, basta criar um novo ato pelo botão ![novo](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/NOVO.PNG)
 
 Perceba que ao criar um novo ato, a tela será apresentada como a seguir:
 
 ![ato_novo](https://github.com/gislenetavaresacsiv/Atos/blob/main/MG/ATOS_NOVO.PNG).
 
 Agora vamos preencher as devidas informações necessárias:
 
 **Aba Tabelas:** Para colocar o código da tabela, basta clicar em ![inserir](https://github.com/gislenetavaresacsiv/Atos/blob/main/BOTOES/INSERIR.PNG).
 

