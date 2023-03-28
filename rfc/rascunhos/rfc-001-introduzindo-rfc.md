# RFC-001: Introdução do processo de RFC para a cooperativa

- RFC: 001
- Autor(es): Guilherme Jordan, Victor Scandolara
- Status: Rascunho
- Data de envio: <24/03/2023>
- Última atualização: <28/03/2023>

## Resumo

Este RFC propõe a adoção do processo de Request For Comments (RFC, solicitação de comentários) na nossa cooperativa para aprimorar nossa habilidade de colaborar efetivamente, promover transparência e responsabilidade, além de entregar soluções de alta qualidade. Inspirado pelo sucesso do processo RFC na comunidade do software livre, este documento ressalta os benefícios do processo e como ele pode ser aplicado ao nosso trabalho em tópicos complexos como estratégia, planejamento, design de funcionalidades, elaboração de políticas, arquitetura de software e adoção de melhores práticas. 

## Motivação

Nós estamos comprometidos a colaborar de uma maneira transparente e inclusiva, mas estamos enfrentando dificuldades para adotar processos claros que nos permitam uma organização efetiva do trabalho. Nossa plataforma atual, Discord, tem limitações que tornam desafiador engajar mais profundamente em tópicos complexos e preservar nosso conhecimento de uma maneira estruturada. Enquanto o Discord é útil para comunicação breve, muitos de nossos membros não tem tempo disponível para engajar em discussões completamente síncronas, requerindo espaços de tempo maiores para contribuir com a discussão. para além disso, o trabalho produzido no Discord não é duravel, difícil de buscar, e foge do nosso controle, uma vez que trata-se de um software proprietário, do qual podemos perder acesso a qualquer momento.

## Proposta

Nós propomos a adoção do processo de RFC como uma maneira de aprimorar a capacidade de colaboração efetiva e promoção de transparência e responsabilidade da nossa cooperativa. O processo de RFC é uma abordagem estruturada usada na comunidade do software livre para permitir colaboração e tomada de decisão distribuídas. Envolve criar um documento que ressalte um problema, uma proposta de solução, e algumas questões para feedback e discussão. Este documento é então circulado por comentários e sugestões de todos os membros da cooperativa. Abraçando o processo de RFC, nós podemos criar um ambiente mais democratico, decentralizado, e aberto que nos permita enfrentar tópicos complexos como estratégia, planejamento, design de funcionalidades, elaboração de politicas, arquitetura de software, e adoção de melhores práticas enquanto preservamos nosso conhecimento e evoluimos com o tempo.

O processo de RFC provê uma documentação durável, pesquisável e aberta do nosso trabalho que pode ser acessada e modificada por todos os membros da cooperativa. Isso garante que nosso conhecimento será preservado e estruturado, e que todos os membros terão acesso igualitário a ele. Criando um fórum de discussão aberta, processo de RFC também permite que membros contribuam para a discussão em seu próprio ritmo e em seu próprio tempo, o que é essencial para membros com tempo limitado. Para além disso, o processode RFC nos permite tomar decisões informadas e participativas baseadas em feedback e sugestões de todos os membros da cooperativa, o que promove transparência e responsabilidade.

Em resumo, o processo de RFC oferece uma abordagem poderosa e plexível para organizar nosso trabalho e fomentar colaboração. Adotando este processo, nós podemos ajudar a destravar o potencial da nossa cooperativa e alcançar nossa visão compartilhada de democracia, decentralização, abertura, igualdade e justiça social.


## Implementação

Para implementar o processo de RFC, nós propomos o uso do Git e a funcionalidade de "issues" do GitHub. Isso nos permitirá tirar vantagem da colaboração e do controle de versões poderosas do Git, enquanto também provê uma plataforma transparente e organizada para discussões e feedback usando as "issues" do GitHub. Este repositório servirá como o hub central para todos os RFCs e discussões relacionadas. Nós recomendamos o uso da seguinte estrutura:

```
📁 rfc
├── 📄 template_rfc.md
├── 📁 rascunhos/
│ ├── 📄 rfc-001-introduzindo-rfcs.md
└── 📁 em_revisao/
└── 📁 aprovadas/
└── 📁 rejeitadas/
```

Você pode começar com o [RFC template](/rfc/template_rfc.md). 

1. **Enviando um RFC**: Qualquer membro da cooperativa pode enviar um RFC criando uma nova branch no repositório e copiando o modelo RFC para esta branch. Eles podem então preencher o modelo e enviar um pull request para discussão e feedback.

2. **Discutindo e iterando um RFC**: Uma vez que um RFC é enviado, ele passará por um processo de discussão e feedback. Membros da cooperativa podem revisar e comentar no RFC, e o autor pode responder a esses comentários e fazer mudanças na proposta. Este processo pode levar quanto tempo for necessário para garantir que todas as preocupações e feedbacks foram considerados.

3. **Aprovando um RFC**: Uma vez que um RFC passou pelo processo de discussão e feedback, ele pode ser aprovado por concenso dos membros da cooperativa. O consenso pode ser alcançado através do voto ou um período de silêncio onde nenhuma objeção seja feita.

4. **Implementando um RFC**: Uma vez que um RFC foi aprovado, ele pode ser implementado criando uma nova branch no repositório principal da cooperativa e fazendo as mudanças necessárias. O RFC também deve ser atualizado com detalhes da implementação e quaisquer desafios ou compensações encontradas durante a mesma.

5. **Melhorando contínuamente o processo**: Nós devemos constantemente validar e melhorar o processo de RFC para garantir que o mesmo atenda nossas necessidades e circunstâncias evolutivas. Isto pode incluir revisar o modelo de RFC, validar a efetividade da discussão e do processo de feedback e analizar o impacto de RFCs aprovadas nos projetos e objetivos da cooperativa.
