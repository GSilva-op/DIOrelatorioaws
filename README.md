# DIOrelatorioaws
Relatório gerencial de RH em PowerBI e integrado no banco de dados MySQL na nuvem AWS

"Mesclar" (Merge) é usado para juntar colunas de duas tabelas diferentes com base em uma chave comum (como um JOIN em SQL). Usamos isso para enriquecer uma tabela com informações de outra, colocando os dados lado a lado.

"Anexar" (Append) é usado para empilhar linhas de duas tabelas que têm a mesma estrutura de colunas (como um UNION em SQL). Usamos para combinar, por exemplo, vendas de Janeiro com vendas de Fevereiro, colocando as linhas umas embaixo das outras.

Para enriquecer a tabela de localizações com o nome do departamento. Os dados estavam em colunas, em tabelas diferentes, então a única operação correta era Mesclar.
