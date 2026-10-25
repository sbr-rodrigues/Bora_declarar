# Bora_declarar
Claro, amor! 💙 Vou te deixar um README com cara de projeto profissional para colocar no GitHub e entregar junto com o desafio da DIO.

📊 Simulador de Imposto de Renda no Excel
📖 Descrição

Este projeto foi desenvolvido como desafio prático da DIO (Digital Innovation One) com o objetivo de construir um Simulador de Imposto de Renda utilizando Microsoft Excel.

A aplicação permite registrar informações do contribuinte, rendimentos, despesas dedutíveis e gerar automaticamente uma estimativa do imposto devido, além de calcular uma possível restituição ou imposto a pagar.

🎯 Objetivo

Desenvolver uma solução em Excel capaz de:

Organizar informações do contribuinte;
Registrar diferentes fontes de rendimento;
Registrar despesas dedutíveis;
Calcular a base de cálculo do imposto;
Simular o imposto estimado;
Simular restituição ou imposto a pagar;
Gerar um relatório consolidado.
🛠️ Tecnologias Utilizadas
Microsoft Excel
Fórmulas e Funções do Excel
Hiperlinks para navegação entre páginas
Formatação Condicional
Dashboard Visual
📂 Estrutura da Planilha
✅ Dados do Contribuinte

Responsável pelo cadastro das informações básicas do usuário.

Campos utilizados:

Nome Completo
CPF
Data de Nascimento
Estado Civil
Telefone
E-mail
Endereço

✅ Rendimentos

Registro dos ganhos do contribuinte.

Trabalho
Salário Mensal
Meses Trabalhados
Férias
Participação nos Lucros (PLR)
Outras Rendas
Aluguel Recebido
Meses de Aluguel
Aposentadoria
Pró-Labore
Pensão Recebida
Rendimentos Autônomos
Investimentos
Rendimentos de Aplicações Financeiras
✅ Despesas Dedutíveis

Registro das despesas que reduzem a base de cálculo.

Saúde
Plano de Saúde
Meses Utilizados
Consultas Médicas
Exames
Educação
Mensalidade Escolar
Faculdade
Meses Pagos
Previdência
Previdência Privada
Tempo de Contribuição
✅ Resumo do IR

Área responsável pelos cálculos automáticos.

Indicadores:

Rendimentos Totais
Deduções Totais
Base de Cálculo
Imposto Estimado
IR Retido na Fonte
Restituição Estimada
Imposto a Pagar
✅ Relatório Final

Painel consolidado com os valores calculados nas demais planilhas.

Exibe:

Rendimentos
Trabalho
Outras Rendas
Investimentos
Deduções
Saúde
Educação
Previdência
Resultado
Base de Cálculo
Imposto Estimado
Restituição Estimada
🧮 Fórmulas Utilizadas
Salário Anual
=SalarioMensal*MesesTrabalhados

Aluguel Recebido
=ValorAluguel*MesesAluguel

Total das Deduções
=SOMA(...)

Base de Cálculo
=Rendimentos-Deducoes

Imposto Estimado
=SE(BaseCalculo<0;0;BaseCalculo*15%)

IR Retido na Fonte
=Rendimentos*12%

Restituição ou Imposto a Pagar
=IRRetido-ImpostoEstimado

Resultado Automático
=SE(IRRetido>ImpostoEstimado;"✅ Restituição";"⚠️ Imposto a Pagar")

🎨 Design

Foi utilizada uma identidade visual baseada em tons corporativos:

Azul Petróleo (#1F4E79)
Azul Claro (#5B9BD5)
Verde (#70AD47)
Branco (#FFFFFF)

O objetivo foi criar um visual limpo, profissional e adequado para um sistema financeiro.

🚀 Aprendizados

Durante o desenvolvimento deste projeto foi possível praticar:

Organização de dados no Excel;
Referência entre planilhas;
Criação de dashboards;
Utilização de funções matemáticas;
Estruturação de relatórios;
Experiência do usuário (UX) em planilhas.
👨‍💻 Autor

Projeto desenvolvido por Sabrina Rodrigues como parte dos desafios práticos da DIO - Digital Innovation One.

✨ Observação: Os cálculos utilizados possuem caráter educacional e foram simplificados para fins de aprendizado e demonstração das funcionalidades do Excel.
