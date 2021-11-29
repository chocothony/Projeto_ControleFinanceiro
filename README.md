## Introdução
'Controle Financeiro' é um aplicativo para o gerenciamento de finanças, adicionando entradas e saídas a fim de apresentar o saldo, alertando se positivo ou negativo. <br>
Focado no planejamento financeiro, desenvolvido como tema de projeto para a aula de Programação de Dispositivos Móveis I, da Fatec Ferraz de Vasconcelos.

## Telas e Funcionalidades
- **Splash:** <br>
Plenamente decorativa, exibida na inicialização por 1.5s.

- **Home:** <br>
Exibe o total da soma das *entradas* e *saídas*, exibindo sua diferença no formato de *saldo*. <br>
É possível filtrar os totais de um determinado mês e ano no inferior da tela.

- **Add:** <br>
Responsável pela criação de novas movimentações na base de dados.

- **List:** <br>
Lista todas as movimentações criadas, exibindo seu tipo (entrada ou saída), nome, valor e data. <br>
No menu superior, é possível excluir, filtrar e editar os dados, sendo a edição realizada em uma tela separada

- **Edit:** <br>
Usada para editar uma movimentação, sendo inicializada com os dados antigos.

## Dificuldades e Aprendizado
- **AndroidManifest:** Utilização de temas customizados
- **Estilização:** Fontes personalizadas e fundo com gradiente
- **Layout:** 
	- AppCompatButton: design superior ao Button
	- Funcionamento da RelativeLayout, ScrollView e layout_weight
- **Códigos:**
	- Menu de navegação personalizado
	- Seleção de data (mês e ano) em uma tela de diálogo personalizada
	- Delegação, invocação e reflexão
	- Uso e aplicação de variáveis globais no contexto do app
	- Atualização de dados com Anko
