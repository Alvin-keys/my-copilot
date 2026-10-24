# 💡 Sobre o Copiloto

O uso da IA no desenvolvimento de software vem ganhando cada vez mais espaço, impulsionado pela busca das empresas por produtividade, eficiência e agilidade na entrega de soluções e ,nesse cenário, saber utilizar a IA vai além de conhecer ferramentas ou escrever bons prompts. Envolve compreender como integrá-la ao processo de desenvolvimento de maneira estratégica, aproveitando sua capacidade de sugerir soluções, gerar código, analisar problemas e automatizar tarefas.

Este projeto parte da ideia de que **a IA oferece seu maior potencial quando atua como copiloto do desenvolvedor**: uma parceira que auxilia na compreensão dos problemas, no planejamento, na implementação e na validação das soluções, enquanto o profissional mantém uma participação ativa nas decisões e no processo de aprendizagem.

Recursos como Ask, Plan e Agent permitem explorar diferentes níveis de colaboração, desde a investigação de dúvidas e o planejamento de soluções até a execução de tarefas mais complexas. Saber quando e como utilizar cada abordagem faz parte do desenvolvimento de uma relação produtiva e consciente com a tecnologia.

O objetivo é explorar práticas, prompts e experiências que ajudem a integrar a IA ao desenvolvimento de software, buscando mais produtividade sem perder de vista a qualidade, o pensamento crítico e a autonomia do desenvolvedor.


# 🧩 Modos do Copiloto (Ask, Edit, Plan, Agent e Study)

O Copiloto oferece diferentes **modos de interação** para você escolher como quer trabalhar: desde **tirar dúvidas sem mexer no código**, até **editar trechos específicos**, **planejar mudanças maiores** ou **delegar tarefas mais complexas** com um modo mais autônomo. A ideia é simples: você seleciona o modo que melhor combina com seu objetivo no momento e ganha velocidade com mais controle.

---

# ❓ Ask
O modo **Ask** é para fazer perguntas e entender coisas, **sem alterar seu código**. Você pode perguntar sobre um arquivo específico, um erro, uma função, uma stack trace ou até conceitos gerais.

O Copiloto lê o contexto do projeto (arquivos abertos, seleção, etc.) e responde como um **“mentor técnico”**, explicando o que está acontecendo e por quê. **Ele não modifica nada** — só analisa e explica.

📄 **Prompt:** [prompts/prompt-ask.md](prompts/prompt-ask.md)

---

# ✏️ Edit
O modo **Edit** serve para **alterar código existente**. Você seleciona um trecho (ou um arquivo inteiro), descreve o que quer mudar, e o Copiloto aplica a modificação diretamente.

Ideal para:
- refactors
- ajustes de lógica
- melhoria de performance
- mudança de estilo
- conversão de linguagem
- adicionar logs
- tratar erros

Aqui o foco é: **“pegue isso que já existe e transforme”**.

📄 **Prompt:** [prompts/prompt-edit.md](prompts/prompt-edit.md)

---

# 🧭 Plan
Quando você pede algo mais complexo, o Copiloto pode entrar em um modo de **planejamento**, onde ele **pensa e descreve os passos antes de sair codando**.

Ele:
- divide o problema em etapas
- explica o que vai fazer
- só depois executa

Isso é muito útil para **mudanças grandes**, **novas features** ou quando você quer **validar a abordagem** antes de mexer no código.

📄 **Prompt:** [prompts/prompt-plan.md](prompts/prompt-plan.md)

---

# 🤖 Agent
O **Agent** é o modo mais “autônomo”. Ele pode **navegar pelo projeto**, **criar arquivos**, **modificar múltiplos pontos** e **manter contexto entre passos**, como se fosse um dev júnior trabalhando com você.

Você dá um objetivo (ex.: “implemente login com JWT”) e ele decide o que precisa ser feito em vários arquivos para chegar lá.

📄 **Prompt:** [prompts/prompt-agent.md](prompts/prompt-agent.md)

---

# 📚 Study
O modo **Study** é focado em **aprendizado ativo**, não só em chegar à resposta ou ao código final.

Em vez de simplesmente explicar ou executar, ele:
- ensina e guia o raciocínio
- destaca conceitos e trade-offs
- faz perguntas reflexivas
- avança em progressão gradual de dificuldade

Funciona quase como um **tutor particular**.

📄 **Prompt:** [prompts/prompt-study.md](prompts/prompt-study.md)

---

# 🧠 Resumo mental rápido
- **Ask** → entender  
- **Plan** → planejar antes de agir  
- **Edit** → mudar código  
- **Agent** → executar tarefas grandes sozinho  
- **Study** → entendimento ativo 