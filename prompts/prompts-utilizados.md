# Prompts Utilizados - Notebook LM

> Documentação dos prompts testados no caderno temático sobre Linguagens de Programação. Cada entrada registra um o prompt, a resposta obtida, as fontes referenciadas pelo NotebookLM e as dificuldades encontradas.

---
## Objetivo 1 - O que são linguagens de programação
### Prompt 1.1 
#### Pergunta feita: 
> O que é uma linguagem de programação e qual é o seu papel no desenvolvimento de software?
#### Resposta obtida:
Uma linguagem de programação é um conjunto de conhecimentos escritos e formais que seguem regras e instruções específicas para o desenvolvimento de programas. Ela funciona como um meio de comunicação com os computadores, permitindo que humanos forneçam instruções ou comandos para que a máquina execute tarefas específicas. Essas linguagens são compostas fundamentalmente por variáveis, sintaxe (regras gramaticais para escrever o código) e semântica (o significado que o computador traduz para um formato legível por máquina). 
O papel de uma linguagem de programação no desenvolvimento de software é central, sendo considerada o coração de qualquer aplicação. Suas principais funções e impactos incluem:
- **Transformação de lógica em software**: Programar consiste em escrever um texto seguindo as características de uma linguagem; esse código é então interpretado pelo hardware e transformado em um software funcional para desktops, dispositivos móveis ou sistemas de IoT.
- **Definição da estrutura e lógica**: A escolha da linguagem e de seu paradigma (estilo de abordagem) dita como os problemas serão resolvidos e como o código será organizado para ser eficiente, claro e fácil de manter.
- **Abstração e produtividade**: Linguagens de alto nível (como Java e Python) abstraem detalhes complexos do hardware, permitindo que os desenvolvedores foquem na funcionalidade do programa, o que aumenta a produtividade e reduz erros.
- **Controle de recursos**: Linguagens de baixo nível (como Assembly ou C) oferecem maior controle sobre a arquitetura do sistema e o gerenciamento de memória, sendo essenciais para sistemas operacionais e drivers.
- **Evolução tecnológica**: Elas evoluem continuamente para oferecer otimizações de segurança, melhor desempenho e compatibilidade com novas plataformas e ferramentas.
#### Fontes referênciadas:
- https://www.somosicev.com/blogs/10-linguagens-de-programacao-mais-usadas-no-mercado-de-tecnologia/
- https://www.splunk.com/en_us/blog/learn/programming-languages.html

---
## Objetivo 2 - Paradigmas de programação
### Prompt 2.1 
#### Pergunta feita:
> Quais são os principais paradigmas de programação e o que diferencia cada um?
#### Resposta obtida:
Paradigmas de programação são estilos ou abordagens para resolver problemas por meio de código, funcionando como "receitas" que definem a estrutura e a lógica de um programa. A escolha de um paradigma influencia como o código é organizado, tornando-o mais claro, eficiente ou fácil de manter, dependendo da complexidade do projeto.
Os principais paradigmas e suas diferenciações, conforme as fontes, são:
- **Paradigma Imperativo**: Foca em detalhar cada passo que o computador deve executar e na ordem em que devem ser feitos. É comparado a uma receita culinária onde todas as etapas precisam ser seguidas rigorosamente para atingir o objetivo. É muito utilizado em programação de baixo nível e sistemas embarcados.
- **Paradigma Declarativo**: Ao contrário do imperativo, o foco está no resultado final ("o quê") e não no processo detalhado ("como"). O programador define o que deseja, e a linguagem ou o sistema cuida da execução. Exemplos comuns incluem linguagens de consulta como SQL.
- **Programação Funcional**: É um subconjunto do paradigma declarativo focado em funções matemáticas puras e imutabilidade. Ela evita mudanças no estado do software e efeitos colaterais, sendo ideal para processamento de grandes volumes de dados e aplicações que exigem paralelização.
- **Programação Orientada a Objetos (POO)**: Baseia-se na modelagem de entidades do mundo real como "objetos". Cada objeto possui atributos (dados) e métodos (comportamentos). Seus pilares principais são abstração, encapsulamento, herança e polimorfismo, o que facilita o reaproveitamento de código em sistemas complexos.
- **Programação Lógica**: Utiliza fatos e regras de lógica formal para que o computador deduza novas informações e resolva problemas. É o paradigma predominante no desenvolvimento de inteligência artificial e sistemas especialistas.
- **Programação Reativa**: Focada em eventos e mudanças de estado. O sistema é projetado para reagir dinamicamente a entradas, como cliques de usuários ou mensagens, sendo essencial para interfaces gráficas responsivas.
- **Programação Concorrente**: Permite que múltiplas tarefas sejam executadas simultaneamente, aumentando a eficiência em sistemas de alto desempenho, como servidores que atendem muitas requisições ao mesmo tempo.
- **Paradigma Procedural**: Considerado uma variação do imperativo, utiliza uma série de funções ou procedimentos sistemáticos para resolver problemas, permitindo que blocos de código sejam reutilizados em diferentes partes do programa.

Muitas linguagens modernas, como Python e JavaScript, são consideradas híbridas, pois permitem que o desenvolvedor misture diferentes paradigmas conforme a necessidade do projeto.
#### Fontes referênciadas:
- https://www.rocketseat.com.br/blog/artigos/post/paradigmas-de-programacao-qual-o-melhor
- https://guia.dev/pt/pillars/languages-and-tools/programming-languages.html
- https://www.splunk.com/en_us/blog/learn/programming-languages.html

---
## Objetivo 3 - Aplicações e serviços reais
### Prompt 3.1 
#### Pergunta feita:
> Quais linguagens de programação são usadas por grandes empresas como Google, Amazon e Meta, e por quê?
#### Resposta obtida:
Grandes empresas de tecnologia, como Google, Amazon e Meta, selecionam suas linguagens de programação com base em critérios técnicos rigorosos, como performance, escalabilidade, segurança e o domínio do negócio.
Abaixo estão as linguagens e os motivos de seu uso por essas gigantes, conforme as fontes:
###### Google e a Criação do Go
O Google é o criador da linguagem Go (ou Golang), desenvolvida especificamente para resolver desafios de infraestrutura da empresa.
- Por que usam: Go é uma linguagem compilada que oferece alta performance e é excelente para programação concorrente. Ela utiliza "goroutines" (threads leves), o que permite que servidores de alto desempenho executem múltiplas tarefas simultaneamente de forma eficiente. Além disso, Go ajuda a reduzir a complexidade em sistemas de grande escala.
###### Linguagens Predominantes na Indústria (Amazon, Meta e Google)
As fontes destacam que Java, Python e JavaScript são as linguagens que dominam o mercado de grandes organizações devido à sua maturidade e ecossistema.
- **Java**: É amplamente utilizada em sistemas corporativos complexos devido à sua robustez e escalabilidade. Sua capacidade de adaptação ao crescimento do software e a retrocompatibilidade (código antigo funciona em versões novas) a tornam ideal para as infraestruturas massivas de empresas como a Amazon. Além disso, é a base do sistema operacional Android.
- **Python**: Tornou-se essencial para o desenvolvimento de Inteligência Artificial (IA) e Machine Learning, áreas centrais para o Google e a Meta. Sua popularidade se deve à sintaxe simples, que permite o desenvolvimento rápido (prototipagem), e à vasta disponibilidade de bibliotecas que facilitam tarefas complexas.
- **JavaScript**: Domina o ambiente web e é fundamental para criar a interatividade das plataformas dessas empresas. Organizações de grande porte frequentemente utilizam bibliotecas baseadas em JavaScript, como React (tecnologia desenvolvida pela Meta), para construir interfaces de usuário modernas e responsivas.
- **C++**: Utilizada quando é necessário controle total do hardware e máxima performance em aplicações robustas que integram servidores.
##### Por que escolher uma linguagem específica?
A escolha dessas empresas não se baseia apenas em "preferência", mas em fatores estratégicos:
- **Domínio e Bibliotecas**: Algumas linguagens já possuem bibliotecas prontas para domínios específicos, como finanças ou ciência de dados, o que evita "reinventar a roda".
- **Arquitetura de Microsserviços**: Com a evolução para arquiteturas distribuídas, essas empresas podem usar linguagens diferentes para serviços distintos, escolhendo a ferramenta que melhor resolve cada problema técnico específico.
- **Disponibilidade de Profissionais**: Escolher linguagens populares garante que a empresa encontrará desenvolvedores qualificados no mercado para manter e evoluir seus sistemas.
#### Fontes referênciadas:
- https://www.splunk.com/en_us/blog/learn/programming-languages.html
- https://guia.dev/pt/pillars/languages-and-tools/programming-languages.html
- https://www.somosicev.com/blogs/10-linguagens-de-programacao-mais-usadas-no-mercado-de-tecnologia/
- https://www.alura.com.br/artigos/hello-world-em-varias-linguagens?srsltid=AfmBOopH1pg_0mZGpAhVi7LOLmfaeCgUtfzf1EoJVGIDt0S0S69qkAW8
- https://www.rocketseat.com.br/blog/artigos/post/paradigmas-de-programacao-qual-o-melhor

---
## Objetivo 4 - 
### Prompt 4.1 
#### Pergunta feita: 
> Mostre um exemplo de código simples em Python, JavaScript e Java que resolva o mesmo problema.
#### Resposta obtida:
O problema clássico e mais simples utilizado para demonstrar a sintaxe de diferentes linguagens é o "Hello World" (ou "Olá, Mundo"), que funciona como uma tradição para dar boas-vindas ao aprendizado e verificar se o ambiente de programação está funcionando corretamente.
Abaixo estão os exemplos de como resolver esse "problema" nas três linguagens solicitadas:
1. **Python**:
Python é uma linguagem de alto nível conhecida por sua sintaxe simples e minimalista, o que permite resolver o problema em apenas uma linha.
``` python
print("Hello World")
```
2. **JavaScript**:
JavaScript é essencial para a interatividade na Web e, embora seja uma linguagem de script interpretada, possui uma sintaxe direta para saídas de console.
``` javascript
console.log("Hello World");
```
3. **Java**:
Java é uma linguagem orientada a objetos mais robusta e verbosa, exigindo a definição de uma classe e de um método principal (main) para executar qualquer instrução.
``` java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
#### Fontes referênciadas:
- https://www.somosicev.com/blogs/10-linguagens-de-programacao-mais-usadas-no-mercado-de-tecnologia/
- https://www.alura.com.br/artigos/hello-world-em-varias-linguagens?srsltid=AfmBOopH1pg_0mZGpAhVi7LOLmfaeCgUtfzf1EoJVGIDt0S0S69qkAW8


