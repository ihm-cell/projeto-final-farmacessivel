🎯 Canvas do Projeto Final — App Android
	

Integrantes (3 a 4) Ikalímony Helissa, Ana Beatriz Costa, Estefani Maria>
Turma	3º ano — Ensino Médio
Repositório	https:(https://github.com/ihm-cell/projeto-final-farmacessivel)
Data de preenchimento	09/09/2026
Entrega final	10/12/2026
🧩 Bloco 1 — Nome e pitch do app

Nome do app: FarmaAcessível

Pitch em uma frase:

"O FarmaAcessível ajuda idosos e pessoas com deficiência a consultar medicamentos e produtos de farmácia de forma simples e acessível, sem precisar enfrentar dificuldades para ler e encontrar as informações."

😖 Bloco 2 — Problema

Muitos idosos e pessoas com deficiência encontram dificuldades ao utilizar aplicativos e serviços de farmácia devido a textos pequenos, pouco contraste, botões difíceis de tocar e excesso de informações.

Essas dificuldades podem tornar a busca por medicamentos e informações sobre produtos mais demorada e confusa.

Como esse problema é resolvido hoje (sem o app)?

A pessoa precisa ir pessoalmente à farmácia ou utilizar aplicativos que nem sempre possuem recursos adequados de acessibilidade.
👥 Bloco 3 — Público-alvo

Para quem é o app?

Perfil principal: Idosos e pessoas com deficiência visual, motora ou que tenham dificuldade para utilizar aplicativos convencionais.
Quando/onde usam: Em casa ou na farmácia, principalmente quando precisam pesquisar medicamentos, produtos e preços.
Uma pessoa real que testaria o app: <nome e relação com o grupo>
💡 Bloco 4 — Solução em uma tela

Descreva o que a tela principal mostra e o que o usuário consegue fazer nela.

A tela principal lista: Medicamentos e produtos disponíveis na farmácia, com nome, imagem e preço.
A ação principal do usuário é: Pesquisar e selecionar um produto para consultar suas informações.
Depois de agir, o usuário vê: A tela de detalhes do produto, com informações apresentadas de forma grande, clara e organizada.
✅ Bloco 5 — Funcionalidades do MVP
#	Funcionalidade	Essencial?	Quem faz
F1	Listar medicamentos e produtos	Sim	<integrante>
F2	Pesquisar produtos pelo nome	Sim	<integrante>
F3	Exibir detalhes e preço do produto	Sim	<integrante>
F4	Interface com recursos de acessibilidade	Sim	<integrante>
🚫 Bloco 6 — Fora do escopo
❌ Pagamento de medicamentos pelo aplicativo.
❌ Entrega de medicamentos em domicílio.
❌ Cadastro e gerenciamento de receitas médicas.
❌ Integração com estoque em tempo real ou sistema de uma farmácia real.
⚙️ Bloco 7 — Caminho técnico
 Opção A — Room: dados salvos no próprio celular.
 Opção B — Retrofit: dados vindos de uma API pública.
 Opção C — Desafio: API + salvar favoritos localmente.

Se escolheu B ou C — qual API?

Não se aplica. O aplicativo utilizará dados armazenados localmente.

Bibliotecas que o grupo vai usar:

Kotlin
Jetpack Compose
Room
Android Jetpack

Onde entra o try/catch?

Pode falhar: Operações de leitura ou gravação dos produtos no banco de dados e ações que possam gerar erros durante o uso do aplicativo.
O usuário vê a mensagem: "Não foi possível carregar os produtos. Tente novamente."

🎨 Bloco 8 — Identidade visual
Item	Definição do grupo
Nome exibido (strings.xml)	FarmaAcessível
Cor principal (hex, em Color.kt)	#2E7D32
Ideia do ícone (512×512)	Uma cruz de farmácia combinada com um símbolo de acessibilidade, utilizando cores de alto contraste
applicationId	br.edu.ifpe.farmaacessivel
Versão inicial	1.0 (versionCode 1)

👤 Bloco 9 — Equipe, papéis e riscos
Integrante	Papel principal	Responsável por
<Nome 1>	Dev / telas	Desenvolvimento das telas e navegação
<Nome 2>	Dev / dados	Banco de dados e organização dos produtos
<Nome 3>	Design e identidade visual	Cores, ícone e acessibilidade visual


Todos programam. O "papel" define quem responde por aquela parte, não quem trabalha sozinho.

Riscos — o que pode dar errado e o plano B:

Risco	Plano B
Dificuldade para implementar o banco Room	Reduzir a quantidade de dados e funcionalidades, mantendo apenas os produtos essenciais
Problemas de acessibilidade ou interface	Testar com pessoas de fora do grupo e simplificar as telas e componentes
🤖 Bloco 10 — Acordo de trabalho com IA

Três regras que vamos escrever no nosso AGENTS.md:

Toda alteração feita com auxílio de IA deve ser revisada e compreendida pelos integrantes.
A IA não deve adicionar funcionalidades que não estejam definidas no Canvas ou PRD sem autorização do grupo.
Nenhuma senha, chave de API ou informação pessoal deve ser enviada para ferramentas de IA.

Combinados do grupo:

 Ninguém clica Accept no Agent Mode sem ler a mudança inteira.
 Quem aceitou o código escreve o comentário de fronteira do arquivo.
 Antes de cada marco, revisamos juntos: alguém aqui não entende alguma parte?
 Nenhuma chave de API ou senha vai para o prompt.
 Todos os integrantes devem testar e compreender as funcionalidades desenvolvidas.

Como vamos garantir que todos entendem tudo:

O integrante responsável por uma parte apresenta o código aos demais integrantes.
O grupo revisará as alterações antes de considerá-las concluídas.
Os integrantes irão se revezar nas tarefas para que todos tenham contato com diferentes partes do projeto.
🗓️ Bloco 11 — Marcos até 10/12
Marco	Prazo	Como se comprova no GitHub
M1 — Canvas preenchido + repositório criado	16/09	CANVAS.md no main
M2 — PRD aprovado + telas rascunhadas	30/09	PRD.md + imagens em docs/
M3 — Funcionalidade base rodando	21/10	Tela principal lista produtos + pesquisa + try/catch
M4 — Dados completos (Room) e erros tratados	11/11	Commits da camada de dados
M5 — Identidade visual + .apk de release testado	25/11	Ícone, cores e .apk testado por 2 pessoas de fora
M6 — .aab + material de loja + README.md	02/12	Pasta loja/ + README.md completo
Entrega e apresentação	10/12	Tag v1.0 no repositório
🏁 Bloco 12 — Definição de pronto
 O app abre e não fecha sozinho depois de 5 minutos de uso.
 A tela principal mostra dados reais dos produtos.
 A pesquisa de produtos funciona e o resultado aparece na tela.
 A seleção de um produto mostra seus detalhes.
 Quando algo falha, aparece uma mensagem clara — o app não quebra.
 O app tem nome, ícone e cores próprios.
 Duas pessoas de fora do grupo instalaram o .apk e conseguiram usar sem explicação.
 O README.md explica o que o app faz, com o que foi feito e como gerar o build.
 O docs/USO_DE_IA.md e o AGENTS.md estão preenchidos.
 Cada integrante consegue abrir o projeto e fazer uma mudança pequena sozinho.
 Todo arquivo nosso tem o comentário de fronteira escrito por nós.
✍️ Validação do professor
	
Data	
Situação	( ) Aprovado ( ) Aprovado com ajustes ( ) Refazer
Observações
