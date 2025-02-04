---
marp: true
theme: default
class: 
  - lead
backgroundImage: url('./assets/if_back1.png')

paginate: true
---
 
# Teste Funcional e de Integração
### Prof. Dr. Valério Gutemberg
#### :pencil: Discentes: Andriéria Dantas, Bruno Pithon,
#### Guilherme Aurélio, João Paulo e Kelvin Marques
#### :pencil: Disciplina de Testes de Software
:pencil2: Curso de Sistemas para Internet

---

# O que é Teste Funcional?

Os testes funcionais em testes de software são uma forma de determinar se o software ou uma aplicação funciona como esperado. Esse teste não se preocupa com a forma como o processamento ocorre, mas sim se o processamento está fornecendo os resultados corretos ou se tem algum bug, ou seja, um teste de caixa preta, onde o foco é apenas as entradas e saídas do sistema, sem se preocupar com a estrutura interna do programa.

---

# Por que Teste Funcional é Importante?

### Em suma, o teste funcional permite identificar:

- Funções incorretas ou ausentes;
- Erros de interface;
- Erros em estruturas de dados;
- Erros em acessos a bancos de dados externos;
- Erros de comportamento ou desempenho;
- Erros de inicialização e término.

---

# Por que Teste Funcional é Importante?

- Testes de funcionalidade bem-sucedidos ajudam a proporcionar uma experiência de usuário mais positiva, pois o software funciona de maneira **previsível e confiável**.

- Verifica se o software atende aos **requisitos funcionais especificados** no início do projeto, assegurando que todos os recursos esperados estejam implementados corretamente.

---

# O que é Teste de Integração?

O Teste de Integração avalia a funcionalidade de vários módulos quando integrados para formar uma única unidade. Este teste valida transições suaves entre vários componentes integrados do software. O objetivo do teste de integração é encontrador defeitos e falhas entre várias interfaces do software.

---

# Por que Teste de Integração é Importante?

- Os defeitos nos módulos integrados são difíceis de encontrar e complexos de corrigir.

- Corrigir bugs em módulos integrados pode eliminar o número geral de bugs e diminuir a contagem de alterações de código no próximo nível de teste do sistema.

- O teste de integração nos permite verificar a integração de vários componentes do software que ajudam a    avaliar o ciclo de ponta a ponta do software.

- Essa abordagem de teste também reduz o risco de falha de software.

---

# Por que Teste de Integração é Importante?

- Ele também valida o impacto das mudanças estruturais quando o usuário final muda de um módulo para outro.

- Isso ajuda a validar a funcionalidade correta das ferramentas API de terceiros no software.

- Aborda problemas que foram ignorados nos testes de unidade, como interceptação de erros, interfaces de hardware, formatação de dados e interfaces de terceiros. O teste de integração também verifica o comportamento funcional e não funcional das interfaces integradas.

---

# Introdução ao PHPUnit

PHPUnit é uma estrutura de testes unitários para a linguagem de programação PHP. Desenvolvido por Sebastian Bergmann, PHPUnit é a ferramenta padrão para escrever testes automatizados em PHP, facilitando a escrita de testes de unidade, testes de integração e testes funcionais.

---

# Características do PHPUnit

- **Open source** e gratuito.
- Integração com frameworks PHP como Laravel, Symfony, etc.
- Suporte a testes unitários, testes funcionais e testes de integração.
- Facilidade na criação de mocks e stubs.
- Geração de relatórios detalhados.

---

# Como Usar o PHPUnit para Teste de Funcionalide e de Integração

1. **Planeje seu teste**: 
- Defina os casos de uso, as funcionalidades e as integrações que precisam ser testadas e identifique as entradas e saídas esperadas.
2. **Instale o PHPUnit**: 
Via Composer: `composer require --dev phpunit/phpunit`

---

# Como Usar o PHPUnit para Teste de Funcionalide e de Integração

3. **Configure o arquivo `phpunit.xml`**:
- Localize o arquivo na raiz do projeto.
- Defina configurações básicas, como diretórios de testes e configurações de ambiente.
4. **Escrevendo os testes de funcionalide e de integração**:
- Crie classes de teste para diferentes funcionalidades e integrações.

---

# Como Usar o PHPUnit para Teste de Funcionalide e de Integração

5. **Rode os testes**:
- No terminal, execute: `phpunit` ou `php artisan test`
- PHPUnit buscará e executará todos os testes no diretório configurado.
6. **Monitoramento**:
- Verifique os resultados dos testes e asserções no terminal.
- Corrija quaisquer falhas identificadas.

---

# Conclusão

Os testes de funcionalidade e de integração são essenciais para garantir a qualidade e a confiabilidade de sistemas e aplicações. O PHPUnit é uma ferramenta poderosa e versátil que permite realizar esses testes de maneira eficaz, ajudando a identificar e corrigir problemas antes que eles afetem os usuários finais.

---

![teste de banco de teste (banco de dados)](assets/test-images/teste-banco-de-teste-sqlite.jpg)

---

![test-mysql-database-connection](assets/test-images/test-mysql-database-connection.jpg)

---

![test-update-shopping-list-not-found](assets/test-images/test-update-shopping-list-not-found.jpg)

---

![test-can-delete-shopping-list](assets/test-images/test-can-delete-shopping-list.jpg)

---

![test-can-update-shopping-list](assets/test-images/test-can-update-shopping-list.jpg)

---

![test-can-store-shopping-list](assets/test-images/test-can-store-shopping-list.jpg)

---

![test-can-show-shopping-list](assets/test-images/test-can-show-shopping-list.jpg)

---

![shopping-list-controller-test](assets/test-images/shopping-list-controller-test.jpg)

---

![teste-update-list-item-not-found](assets/test-images/teste-update-list-item-not-found.jpg)

---

![teste-destroy-item-not-found](assets/test-images/teste-destroy-item-not-found.jpg)

---

![test-show-item-not-found](assets/test-images/test-show-item-not-found.jpg)

---

![test-can-delete-item](assets/test-images/test-can-delete-item.jpg)

---

![test-can-update-item](assets/test-images/test-can-update-item.jpg)

---

![test-can-update-item](assets/test-images/test-can-store-item.jpg)

---

![test-can-show-item](assets/test-images/test-can-show-item.jpg)

---

![test-can-list-items](assets/test-images/test-can-list-items.jpg)

---

![test-migrations](assets/test-images/test-migrations.jpg)

---


![test-code-coverage-console](assets/test-images/test-code-coverage-console.jpg)

---

# Teste Code Coverage

![test-code-coverage-html](assets/test-images/test-code-coverage-html.jpg)

---


# Obrigado!

Dúvidas?

---

# REFERÊNCIAS

[O que é o Teste Funcional - ZapTest](https://www.zaptest.com/pt-br/o-que-e-o-teste-funcional-tipos-exemplos-lista-de-verificacao-e-implementacao)

[Principais técnicas de testes funcionais - TreinaWeb](https://www.treinaweb.com.br/blog/principais-tecnicas-de-testes-funcionais)

[Teste de Integração: tudo o que você precisa saber para começar - Tecnisys](https://www.tecnisys.com.br/teste-de-integracao-tudo-o-que-voce-precisa-saber-para-comecar/)

[Testes de Integração: tipos, importância e vantagens - Casa do Desenvolvedor](https://blog.casadodesenvolvedor.com.br/testes-de-integracao-tipos-importancia-e-vantagens/)

