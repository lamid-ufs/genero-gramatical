## Dicionário de dados - [`Deslocamentos_2019_[substantivo][etiquetado].csv`](../data/Deslocamentos_2019_[substantivo][etiquetado].csv)

| coluna | descrição |
| :--- | :--- |
| `contexto` | Trecho de texto em que a palavra anotada foi encontrada. |
| `palavra` | O substantivo extraído para a anotação. |
| `classe` | A classe gramatical atribuída automaticamente à palavra. |
| `genero` | O gênero gramatical atribuído automaticamente à palavra. |
| `correcao_classe` | Correção manual da classe gramatical, caso a atribuição automática estivesse incorreta. |
| `correcao_palavra` | Correção manual da palavra, para casos de erros de digitação ou segmentação. |
| `genero_derivacao` | Indica se o gênero é marcado por um sufixo derivacional (ex: *atriz*, *galinha*). |
| `tipo_nome` | Subclassificação do substantivo (comum, próprio, estrangeirismo, deverbal, derivação imprópria). |
| `correcao_genero` | O gênero final do substantivo após a correção manual, classificado como: masculino, feminino ou masculino e feminino. |
| `animacidade` | Distingue se o substantivo designa um ser vivo ([+ animado]) ou uma entidade inanimada ([- animado]). |
| `marca_genero_raiz` | Indica se o substantivo possui um gênero único, inerente à sua raiz. |
| `marca_genero_desinencia`| Indica se a diferenciação de gênero é feita por um sufixo flexional (ex: *-o/-a*). |
| `marca_genero_concord` | Indica se o gênero é diferenciado pela concordância com um elemento adjacente (ex: *o/a turista*). |
| `forma_heteronimo` | Indica se o substantivo apresenta sua contraparte de gênero por meio de uma palavra diferente (ex: *bode/cabra*). |
| `tipo_substantivo` | Classifica a forma do substantivo como **biforme** (duas formas, ex: *menino/menina*) ou **uniforme** (uma forma, ex: *livro*). |
| `qual_heteronimo` | Especifica qual é o heterônimo do substantivo, caso `forma_heteronimo` seja "sim". |