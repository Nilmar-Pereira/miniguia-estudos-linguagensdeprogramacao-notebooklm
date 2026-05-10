# Miniguia de Estudo — Linguagens de Programação

> Resultado final consolidado do caderno temático criado no NotebookLM. Contém resumos estruturados, glossário e prompts reutilizáveis para futuras revisões.
---
## 1. Resumos Estruturados

### 1.1 O que são linguagens de programação?

Uma linguagem de programação é um conjunto de regras e instruções formais que permite a comunicação entre humanos e computadores. Ela é composta fundamentalmente por:

- **Variáveis** — armazenam dados durante a execução do programa
- **Sintaxe** — regras gramaticais para escrever o código corretamente
- **Semântica** — o significado que o computador traduz para um formato legível por máquina

Seu papel no desenvolvimento de software é central — é considerada o coração de qualquer aplicação. Por meio dela, a lógica escrita pelo programador é transformada em software funcional para desktops, dispositivos móveis ou sistemas de IoT.

As linguagens se dividem em dois grandes grupos:

| Tipo | Características | Exemplos |
|---|---|---|
| **Alto nível** | Abstraem detalhes do hardware, maior produtividade | Python, Java, JavaScript |
| **Baixo nível** | Maior controle sobre memória e arquitetura | Assembly, C |
---
### 1.2 Paradigmas de programação

Paradigmas são estilos ou abordagens para resolver problemas por meio de código. A escolha de um paradigma influencia diretamente como o código é organizado e mantido.

| Paradigma | Foco | Uso típico |
|---|---|---|
| **Imperativo** | Como fazer (passo a passo) | Sistemas embarcados, baixo nível |
| **Declarativo** | O que obter (resultado final) | SQL, consultas de dados |
| **Funcional** | Funções puras e imutabilidade | Processamento de dados, paralelização |
| **Orientado a Objetos (POO)** | Modelagem de entidades do mundo real | Sistemas complexos, aplicações empresariais |
| **Lógico** | Fatos e regras de lógica formal | Inteligência artificial, sistemas especialistas |
| **Reativo** | Eventos e mudanças de estado | Interfaces gráficas responsivas |
| **Concorrente** | Múltiplas tarefas simultâneas | Servidores de alto desempenho |
| **Procedural** | Funções e procedimentos reutilizáveis | Programas estruturados em geral |

> Linguagens modernas como Python e JavaScript são **híbridas** — permitem misturar paradigmas conforme a necessidade do projeto.
---
### 1.3 Linguagens usadas por grandes empresas

Grandes empresas escolhem suas linguagens com base em performance, escalabilidade, segurança e domínio do negócio.

| Empresa | Linguagens principais | Motivo |
|---|---|---|
| **Google** | Go, Python, Java | Go para infraestrutura concorrente; Python para IA |
| **Meta** | Python, JavaScript (React) | Python para ML; React para interfaces modernas |
| **Amazon** | Java, Python, C++ | Java para escalabilidade; C++ para máxima performance |

Fatores que guiam essas escolhas:
- **Domínio e bibliotecas** — aproveitar ferramentas já prontas para cada área
- **Arquitetura de microsserviços** — usar a linguagem ideal para cada serviço
- **Disponibilidade de profissionais** — linguagens populares garantem equipes qualificadas
---
### 1.4 Exemplos de código

O mesmo problema — exibir uma mensagem na tela — resolvido em três linguagens diferentes:

**Python** — sintaxe minimalista, resolve em uma linha:
```python
print("Hello World")
```

**JavaScript** — essencial para interatividade na web:
```javascript
console.log("Hello World");
```

**Java** — orientada a objetos, exige estrutura de classe e método principal:
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```
> Essa comparação ilustra como o mesmo objetivo pode ser atingido com diferentes níveis de verbosidade e estrutura dependendo da linguagem escolhida.
---

## 2. Glossário

| Termo | Definição |
|---|---|
| **Linguagem de programação** | Conjunto de regras formais que permite escrever instruções para um computador executar |
| **Sintaxe** | Regras gramaticais que definem como o código deve ser escrito em uma linguagem |
| **Semântica** | O significado das instruções escritas, interpretado pelo computador |
| **Paradigma** | Estilo ou abordagem para organizar e resolver problemas por meio de código |
| **Linguagem de alto nível** | Linguagem que abstrai detalhes do hardware, mais próxima da linguagem humana |
| **Linguagem de baixo nível** | Linguagem que oferece controle direto sobre o hardware e a memória |
| **POO** | Programação Orientada a Objetos — paradigma que modela entidades como objetos com atributos e métodos |
| **Encapsulamento** | Princípio da POO que oculta detalhes internos de um objeto |
| **Herança** | Princípio da POO que permite que uma classe herde características de outra |
| **Polimorfismo** | Princípio da POO que permite que objetos diferentes respondam ao mesmo método de formas distintas |
| **Imutabilidade** | Conceito da programação funcional onde dados não podem ser alterados após criados |
| **Microsserviços** | Arquitetura de software onde a aplicação é dividida em serviços independentes e especializados |
| **Prototipagem** | Desenvolvimento rápido de uma versão inicial de um software para validar ideias |
| **Compilada** | Linguagem cujo código é traduzido inteiramente para código de máquina antes de ser executado |
| **Interpretada** | Linguagem cujo código é traduzido e executado linha a linha em tempo real |
---
## 3. Prompts Reutilizáveis para Futuras Revisões
Use estes prompts em qualquer caderno do NotebookLM ou ferramenta de IA para revisar o tema:
### Revisão geral
- *"Explique o que é uma linguagem de programação e qual é o seu papel no desenvolvimento de software, com exemplos práticos."*
- *"Quais são as diferenças entre linguagens de alto nível e baixo nível? Dê exemplos de cada."*

### Paradigmas
- *"Liste os principais paradigmas de programação com uma descrição curta e um exemplo de linguagem para cada um."*
- *"Compare a programação orientada a objetos com a programação funcional com um exemplo de código simples."*
- *"O que significa uma linguagem ser híbrida em termos de paradigmas? Cite exemplos."*

### Aplicações reais
- *"Quais linguagens de programação são usadas por grandes empresas de tecnologia e por quê?"*
- *"Como a arquitetura de microsserviços influencia a escolha de linguagens de programação em grandes empresas?"*

### Exemplos de código
- *"Mostre o mesmo problema resolvido em Python, JavaScript e Java e explique as diferenças de sintaxe."*
- *"Qual linguagem é mais adequada para desenvolvimento web? E para inteligência artificial? Justifique."*

### Aprofundamento
- *"Explique os quatro pilares da programação orientada a objetos com exemplos práticos."*
- *"O que é programação concorrente e em quais cenários ela é utilizada?"*
- *"Quais são as vantagens da programação funcional para o processamento de grandes volumes de dados?"*