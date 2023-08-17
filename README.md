# Desafio-FieldPro - Marcelo Montes

Objetivo: análise de dados e modelo para determinação de chuvas a partir de variáveis coletadas.

O script elaborado está dividido em:

### Data wrangling
Coleta de dados dos dois arquivos, conversão de time zones, merge, limpeza inicial e demais transformações.

### Estatística descritiva, visualização das dispersões e histogramas
Foi possível observar peculiaridades como: inflação de zeros em chuvas, entre outras.
  
### Boxplot para analisar outliers
Necessário entendimento com área técnica sobre se é necessário eliminar.

### Eliminação de dias não chuvosos 
Ficou claro que o modelo performa melhor eliminando-se os dias não chuvosos. Necessário entender com a engenharia porque isso ocorre e qual a melhor abordagem.

### Mapa de calor (correlações)
Deixou claro que o diferencial de dias tem a melhor correlação

### Regressões
A regressão simples (apenas com a variável 'diferença de carga') gerou um r-quadrado de 0,73 e na regressão multipla subiu para 0,75.
É necessário treinamento do modelo com mais dados para confirmar se compensa manter todas as variáveis. Mas foi possível observer inicialmente um bom desempenho.

### Visualizando Predições X Reais
Demonstra aderência muito boa, exceto em alguns picos de chuva.

PRÓXIMOS PASSOS
- Análise de multicolinearidade e redução dimensionalidade;
- Eliminação de duvidas técnicas;
- Split da base em 'treino' e 'testes';
- Testes estatísticos (resíduos, normalidade, heterocedasticidade, outros) para validar o modelo;
- Ajustes e limpeza do script conforme definições.



