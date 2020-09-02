Este projeto é uma versão em construção que visa adaptar para o ambiente R Markdown o modelo latex para textos acadêmicos desenvolvido pelo professor Carlos Alberto Maziero da UFPR para o PPGINF. O objetivo é combinar os ambientes para ampliar a utilziação de recursos. (https://gitlab.c3sl.ufpr.br/maziero/tese). 

Questões a resolver:
1 - Documento não está assumindo as Fontes Times e Arial
2 - Não está sendo realizada as automações de acordo com a versão do documento (final, defesa, metadados)
3 - Resolver erro com o comando `\graphicspath{\currfiledir/figuras/}` (Resolvido parcialmente)
4 - Resolver erro com o comando `\lstinputlisting{exemplo.c}` 
5 - Resolver erro com o environment `algorithm` (Resolvido)
5 - Resolver erro com o environment `\begin{longtable}[l]{p{0.2\linewidth}p{0.7\linewidth}}` (Resolvido)
6 - Alguns environments se apresentam em inglês
7 - Subitens não seguindo a numeração correta
8 - O padrão de referências não está se adaptando ao formato do modelo
09 - Não está gerando folha de rosto
10 - O esquema de numeração deve ser reconfigurado
-----



