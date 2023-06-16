
Clean Code, ou código limpo, refere-se a um estilo de programação que enfatiza a legibilidade, a simplicidade e a manutenibilidade do código. Trata-se de escrever código que seja fácil de entender e de manter, tanto para o próprio desenvolvedor quanto para outros membros da equipe. O Clean Code é um princípio importante para produzir software de alta qualidade.

Aqui estão alguns princípios e práticas associados ao Clean Code:

**Nomes significativos:** Escolha nomes claros e descritivos para variáveis, funções, classes e outros elementos do código. Nomes bem escolhidos ajudam a entender a finalidade e o comportamento das partes do código.

**Funções pequenas e coesas:** Escreva funções curtas e focadas em realizar uma única tarefa. Funções menores são mais fáceis de entender, testar e reutilizar.

**Evite repetições:** Evite duplicação de código. Em vez disso, extraia trechos de código duplicados para funções ou classes reutilizáveis. Isso reduz a redundância e facilita as alterações futuras.

**Comentários significativos:** Utilize comentários para explicar partes complexas do código, intenções, restrições ou limitações importantes. No entanto, o código deve ser autoexplicativo sempre que possível, evitando comentários óbvios ou redundantes.

**Formatação consistente:** Siga um estilo de formatação consistente para todo o código. Isso inclui a indentação, a quebra de linha, a colocação de chaves e a organização geral do código. A formatação consistente facilita a leitura e a compreensão do código.

**Testes unitários:** Escreva testes unitários para garantir que o código funcione corretamente. Os testes automatizados ajudam a identificar problemas precocemente e fornecem uma camada adicional de documentação para o código.

**Separação de responsabilidades:** Divida o código em partes distintas e cada parte deve ter uma responsabilidade clara. Isso facilita a manutenção do código e permite que cada componente seja alterado ou substituído independentemente.

**Princípio do mínimo surpreendente:** Escreva o código de forma que ele seja intuitivo para quem o utiliza. Evite surpreender outros desenvolvedores com comportamentos inesperados. O código deve ser previsível e seguir as convenções esperadas.

**Refatoração contínua:** Melhore o código constantemente através de refatorações. Refatorar envolve reestruturar o código existente sem alterar seu comportamento externo, buscando melhorar sua legibilidade, simplicidade e eficiência.

**Atenção à complexidade:** Evite criar código excessivamente complexo. Procure soluções mais simples e diretas. A simplicidade ajuda a reduzir erros, facilita a manutenção e aprimora a legibilidade do código.

Existem diversas práticas e ferramentas que podem auxiliar nesse objetivo, e neste documento, vamos abordar três delas: o Prettier, o ESLint e o EditorConfig.

### **Prettier:**
O Prettier é uma ferramenta de formatação de código. Ele automatiza o processo de ajuste da aparência do código para um estilo consistente em todo o projeto. Com o Prettier, você não precisa se preocupar com a formatação manual do código, pois ele realiza isso de forma automática. Ele suporta várias linguagens de programação e pode ser integrado aos editores de texto que você utiliza. Dessa forma, o Prettier ajuda a eliminar discussões sobre estilo de código e mantém a formatação consistente em toda a base de código.

No contexto da VTEX, é utilizada uma configuração específica chamada **@vtex/prettier-config**, que define as opções de formatação para garantir que o código esteja em conformidade com as diretrizes de estilo da VTEX.

### **ESLint:**
O ESLint é uma ferramenta de análise estática de código. Ele verifica o código em busca de erros, padrões de código incorretos e possíveis problemas de segurança. O ESLint permite configurar regras personalizadas e aplicá-las ao código-fonte. Com o ESLint, é possível definir um conjunto de regras de estilo de código e obter mensagens de erro e aviso diretamente no editor de código. Isso facilita a correção de problemas e ajuda a manter um código limpo e sem erros.

No arquivo de configuração do ESLint, são definidas as regras e configurações específicas que devem ser aplicadas ao código. Ele estende um conjunto de regras chamado "vtex" e utiliza a regra "prettier/prettier" para garantir que o código esteja em conformidade com as configurações do Prettier.

### **EditorConfig:**
O EditorConfig é um arquivo de configuração que ajuda a manter a consistência de estilo entre diferentes editores de texto e IDEs. Com o EditorConfig, é possível definir configurações como indentação, estilo de quebra de linha, tamanho da indentação e outros detalhes de formatação do código. Essas configurações são compartilhadas entre os membros da equipe, garantindo que todos utilizem o mesmo estilo de codificação. O EditorConfig é suportado por vários editores e IDEs populares.

No arquivo de configuração do EditorConfig, são definidas algumas opções comuns, como a indentação com espaços, o tamanho da indentação e a codificação do arquivo.