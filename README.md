# An-lise_SESC

Análise SESC
Descrição
Este projeto foi desenvolvido para analisar as execuções orçamentárias do SESC utilizando Python e ferramentas de análise de dados. O projeto envolve a captação, tratamento e análise dos dados financeiros disponíveis no Portal da Transparência do SESC.

Estrutura do Projeto:

  analise_do_orcamento.ipynb: Jupyter Notebook contendo as análises financeiras realizadas.
  
  requisicoes_api_sesc.ipynb: Jupyter Notebook para a captação de dados via API do Portal da Transparência do SESC.
  
  api_transparencia_sistemas2018-utrlj.json: Arquivo JSON com os dados captados da API.

Observações Importantes:

  Não é necessário rodar o código requisicoes_api_sesc.ipynb, pois o JSON gerado pela requisição já se encontra no repositório.
  
  A conta do Amazon S3 foi desativada para evitar custos adicionais, então o código relacionado ao S3 pode não funcionar corretamente.
  
  Atenção ao caminho do arquivo .json usado na análise; recomendamos executar o código no Google Colab para facilitar o acesso e a execução.

Resultados:
  Os resultados das análises ajudam a entender os padrões de gastos e receitas do SESC, promovendo maior transparência e eficiência na gestão de recursos.
