**Atividade para compor a nota da prova da disciplina de Tópicos Integradores.**


**BRUNO MURILO RODRIGUES LUCENA
01356457**


\1. Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?

\2. O que são testes unitários?

\3. O que são testes automatizados?

\4. Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.

1- Os testes automatizados são menos suscetíveis a falhas humanas porque são sempre repetidos exatamente da mesma maneira que foram programados. Isso resulta em uma qualidade de produto consistentemente confiável, o que simplifica o processo de desenvolvimento e lançamento do aplicativo. O teste automatizado também é uma forma de garantir o nível de segurança do aplicativo, já que o rigor dos testes não varia de um teste para outro. Isso é importante para garantir que os produtos estejam em conformidade com o LGPD e outros requisitos legais.

2- Eles podem testar unidades de código-fonte individuais. Uma unidade pode ser um método, classe, propriedade, módulo etc. Depende muito de qual parte do software pode ser testada. O principal objetivo do teste de unitário é mostrar que cada unidade cumpre corretamente seu objetivo principal.

3- O teste automatizado é definido como o procedimento de realizar testes em softwares em construção de maneira combinada, sem intervenção humana. Isso ocorre porque eles têm a capacidade de testar intuitivamente todos os aspectos da plataforma para garantir o desempenho adequado.

4-

![Aprendendo sobre testes de softwares - DEV Community 👩‍💻👨‍💻](Aspose.Words.e861aa41-5f70-4103-b22d-e3eeb6e99423.001.png)


Começando pela base da pirâmide, o Unit (Testes unitários), são os testes feitos na menor parte testável de um programa, independe da sua interação com outras partes do código. Já que fazem testes em menores pedaços do código isoladamente, testes unit tendem ser pequenos e de criação mais rápida e execução. Essa vantagem faz que, caso algum dos testes falhe, seja possível olhar com precisão o local do problema.

Integration (Testes de integração) têm como objetivo testar um grupo de unidades interagindo entre si. Conforme pesquisado, é que existe o fato de os testes unitários não serem suficientes, pois podemos ter duas unidades funcionando conforme esperado, mas momento em que elas precisam interagir entre si, podem não apresentar um comportamento esperado.

(E2E) Testes de Ponta a Ponta têm como principal objetivo fazer o comportamento de um usuário final em nossa aplicação. São testes que simulam o ambiente real, iniciam a aplicação ou abrem o navegador, navegam dentro da aplicação, clicam em botões, preenchem formulários etc.
os testes E2E tem uma complexidade maior e um tempo mais elevado para que possam ser executados.
