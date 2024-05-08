Data Warehouse - Relatório Técnico

Este repositório contém a estrutura e consultas de um Data Warehouse (DW) desenvolvido para armazenar e analisar dados relacionados às atividades físicas e qualidade do sono. O DW foi projetado utilizando o modelo de estrela, com uma tabela de fatos central (FatoAtividadesFisicas) conectada a várias tabelas de dimensão (DimensaoData, DimensaoTipoAtividadeFisica, DimensaoHorarioAtividade e DimensaoQualidadeSono).

Estrutura do Banco de Dados
DimensaoData: Armazena informações sobre datas das atividades.
DimensaoTipoAtividadeFisica: Contém tipos de atividades físicas.
DimensaoHorarioAtividade: Registra os períodos do dia em que as atividades ocorrem.
DimensaoQualidadeSono: Mantém informações sobre a qualidade do sono.
FatoAtividadesFisicas: Tabela central que registra as atividades físicas realizadas, incluindo dados como frequência cardíaca, pressão arterial, duração da atividade, entre outros, e suas respectivas chaves estrangeiras para as dimensões.
Problema
O principal objetivo é descobrir qual tipo de atividade física, em qual intensidade e em qual período do dia gera uma melhor qualidade de sono.

Consultas
Foram elaboradas duas consultas para analisar os dados:

Consulta Geral de Qualidade do Sono: Esta consulta mostra a qualidade do sono de acordo com o tipo de atividade física praticada, período do dia e intensidade da atividade.
Consulta de Atividades que Geram Sono Bom: Essa consulta filtra apenas as atividades que resultam em sono de qualidade 'Bom', exibindo informações semelhantes à consulta geral.
Resultados Esperados
Os resultados dessas consultas podem fornecer insights valiosos para entender como diferentes atividades físicas, em diferentes momentos e intensidades, afetam a qualidade do sono dos indivíduos. Isso pode auxiliar na tomada de decisões relacionadas à saúde e ao bem-estar.

Esse repositório é uma demonstração simplificada de como um Data Warehouse pode ser utilizado para análise de dados, neste caso, focado na saúde e no exercício físico.
