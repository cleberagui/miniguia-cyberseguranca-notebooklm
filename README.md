# 🧠 Miniguia de Cybersegurança com NotebookLM

## 🎯 Objetivo

Criar um "cérebro de aprendizado" utilizando IA para estudar cybersegurança, reunindo conceitos, boas práticas e caminhos de carreira de forma estruturada.

---

## 📚 Fontes utilizadas

### 📄 Conteúdo em texto

* CERT.br – Cartilha de Segurança para Internet: [https://cartilha.cert.br/](https://cartilha.cert.br/livro/cartilha-seguranca-internet.pdf)
* OWASP Top 10: https://owasp.org/www-project-top-ten/
* Google Safety Center: https://safety.google/intl/pt-BR_ALL/safety/

### 🎥 Conteúdo em vídeo

* CONHEÇA A PROFISSÃO CIBERSEGURANÇA | DOCUMENTÁRIO: https://www.youtube.com/watch?v=NBPOCB05o9E&pp=ygUPY3liZXJzZWd1cmFuw6dh
* ROADMAP: Como aprender Cybersecurity em 2025: https://www.youtube.com/watch?v=Z6LBLB4y-aE&pp=ygUSY2liZXJzZWd1cmFuw6dhIGVu
* Cybersecurity Mastery: Complete Course in a Single Video: https://www.youtube.com/watch?v=s19BxFpoSd0&pp=ygUNY3liZXJzZWN1cml0eQ%3D%3D
* Cyber Security Full Course - 11 Hours | Edureka: https://www.youtube.com/watch?v=lpa8uy4DyMo&pp=ugMICgJwdBABGAHKBQ1jeWJlcnNlY3VyaXR5

---

## 🤖 Engenharia de Prompts

### Prompt 1:

O que é cybersegurança?
**Resposta:** A cybersegurança é a prática de proteger computadores, servidores, redes, programas e dados contra ataques digitais, roubos, danos ou acessos não autorizados. Tecnicamente, ela consiste em um corpo de tecnologias, processos e práticas projetados para garantir a segurança de ativos digitais e reduzir o risco de exploração de vulnerabilidades.
Os fundamentos e pilares da área, conforme detalhados nas fontes, incluem:
1. Os Três Pilares (Tríade CIA)
A base de qualquer política de segurança reside em três princípios fundamentais:
Confidencialidade: Garante que a informação seja acessível apenas por pessoas ou sistemas explicitamente autorizados.
Integridade: Assegura que os dados permaneçam precisos e não sejam alterados de forma indevida durante o armazenamento ou transmissão.
Disponibilidade: Garante que os recursos, sistemas e dados estejam prontos para uso sempre que necessário pelos usuários autorizados.
2. Ameaças Comuns
A cybersegurança busca defender indivíduos e empresas de uma vasta gama de ameaças, tais como:
Malware: Códigos maliciosos como vírus, worms, cavalos de Troia e ransomware.
Phishing: Uso de mensagens fraudulentas e engenharia social para "pescar" dados sensíveis.
Ataques de Negação de Serviço (DoS/DDoS): Tentativas de sobrecarregar um sistema ou rede até torná-lo inoperante.
Roubo de Identidade: Ato de se passar por outra pessoa para obter vantagens indevidas.
3. Mecanismos de Defesa
Para combater essas ameaças, utilizam-se diversas ferramentas e estratégias:
Criptografia: Codificação de dados para que apenas quem possui a chave correta possa lê-los.
Firewalls: Barreiras que filtram o tráfego de rede para bloquear acessos suspeitos.
Autenticação Multifator (MFA): Camadas extras de segurança além da senha, como biometria ou tokens.
Gestão de Vulnerabilidades: Processo contínuo de identificar, avaliar e corrigir falhas nos sistemas.
4. Um Campo em Evolução Real
As fontes enfatizam que a cybersegurança não é algo apenas "virtual", mas um campo com consequências reais no mundo físico, afetando a privacidade, a economia e a reputação de pessoas e governos. Atualmente, o cenário está em constante mudança devido ao uso de Inteligência Artificial (utilizada tanto por defensores quanto por atacantes) e à crescente superfície de ataque gerada pela Internet das Coisas (IoT). Por isso, o aprendizado contínuo e a adoção de uma "mentalidade de hacker" para prever ataques são essenciais para os profissionais da área.

### Prompt 2:

Explique phishing com exemplo
**Resposta:** O phishing (ou phishing-scam) é um tipo de fraude no qual um golpista tenta obter dados pessoais e financeiros de um usuário através da utilização combinada de meios técnicos e engenharia social. A palavra vem de uma analogia com a "pescaria" (fishing), onde mensagens eletrônicas são usadas como "iscas" para "pescar" senhas e dados bancários.
Esses ataques geralmente ocorrem por meio de mensagens que tentam se passar por comunicações oficiais de instituições conhecidas, como bancos, redes sociais ou empresas de comércio eletrônico. As mensagens frequentemente informam que o usuário precisa realizar um procedimento urgente para evitar o cancelamento de uma conta ou uma inscrição em serviços de proteção de crédito.
Abaixo estão alguns exemplos detalhados de como o phishing funciona na prática:
Exemplo da Amazon: O usuário recebe um e-mail com a etiqueta "Amazon", mas ao inspecionar o endereço real do remetente, percebe que ele vem de algo como "management@maisoncanada.ca". Ao passar o mouse sobre o link da mensagem, o endereço de destino revela-se como um site falso, como "www.fakeamazon.com".
Exemplo de Login do Facebook: Um atacante clona o código-fonte da página de login do Facebook e cria um site idêntico. Ele envia um e-mail afirmando que as credenciais do usuário foram comprometidas e que a conta foi bloqueada por segurança. Quando a vítima insere seu e-mail e senha na página falsa, um código no back-end (como PHP) salva esses dados em um arquivo de log para o criminoso, enquanto o usuário é redirecionado para a página real do Facebook sem perceber o roubo.
Exemplo de Help Desk: Um e-mail enviado supostamente pelo suporte de uma empresa ou instituição de ensino alega que contas inativas serão deletadas para abrir espaço no servidor. A mensagem solicita que o usuário envie por e-mail dados sensíveis como nome, senha e data de nascimento para manter o serviço ativo.
Exemplo Bancário: O usuário recebe um e-mail de um "banco" (com o qual ele pode nem ter conta) solicitando o recadastramento de dados ou a atualização de um "módulo de segurança". A mensagem contém um link para uma página Web falsa que solicita o número da conta e a senha.
Além do e-mail, o phishing possui variantes como o smishing (via SMS), o vishing (via voz) e o pharming, que redireciona a navegação do usuário para sites falsos por meio de alterações no serviço de DNS, tornando a fraude "transparente" para a vítima.

### Prompt 3:

Como iniciar na carreira de cybersegurança?
**Resposta:** Iniciar uma carreira em cibersegurança exige uma combinação de base técnica sólida, certificações estratégicas, prática constante e o desenvolvimento de uma mentalidade analítica. As fontes fornecem um roteiro detalhado para quem deseja ingressar nesse mercado em crescimento:
1. Construa uma Base Sólida em TI
Antes de se especializar em segurança, você deve dominar os fundamentos da tecnologia, pois não é possível proteger o que você não entende como funciona.
Redes de Computadores: Este é frequentemente citado como o primeiro passo essencial. Você precisa entender protocolos (TCP/IP, UDP, DNS, DHCP, HTTP/HTTPS), subnets e a arquitetura de redes.
Sistemas Operacionais: É fundamental ter proficiência em Windows e, principalmente, em Linux (especialmente distribuições como Kali Linux ou Parrot OS), dominando o uso da linha de comando (CLI).
Programação: Embora não precise ser um desenvolvedor mestre, um profissional de segurança deve ser um "pau para toda obra" em codificação. As linguagens mais recomendadas incluem Python (para automação e análise), JavaScript, SQL (para entender injeções de banco de dados), C/C++ e PHP.
2. Formação Acadêmica e Certificações
O mercado valoriza tanto o conhecimento teórico quanto as validações de mercado.
Educação: Muitos cargos exigem um bacharelado em Cibersegurança, Ciência da Computação ou TI, mas a barreira de entrada está se tornando mais flexível para quem possui certificações e demonstra competência técnica.
Certificações: São consideradas essenciais para que seu currículo seja selecionado em processos de triagem.
Iniciais: CompTIA Security+ (muito recomendada para o início), CCNA e GSEC.
Intermediárias/Ofensivas: CEH (Certified Ethical Hacker), OSCP e SSCP.
Gestão e Avançadas: CISM, CISA e o CISSP (considerado o "padrão ouro" do setor).
3. Prática e Experiência Mão na Massa
A cibersegurança é uma área extremamente prática.
Laboratórios e CTFs: Utilize plataformas de "Capture the Flag" como TryHackMe e Hack The Box para treinar em ambientes controlados e gamificados.
Rede Doméstica: Monte seu próprio ambiente de testes com controladores de domínio, firewalls e máquinas vulneráveis (como o Metasploitable) para experimentar sem riscos legais.
Roadmaps: Utilize guias estruturados como o roadmap.sh para organizar sua trilha de estudos e não se perder entre os diversos tópicos da área.
4. Habilidades Comportamentais (Soft Skills) e Mindset
Pensar como um Atacante: Para ser um bom defensor, você deve adotar a mentalidade de hacker (ethical hacking), antecipando como um invasor exploraria uma brecha.
Resolução de Problemas e Persistência: A capacidade de aceitar falhas, pesquisar soluções criativas e persistir até resolver problemas complexos é vital.
Comunicação: Você precisará reportar riscos e vulnerabilidades de forma clara tanto para equipes técnicas quanto para executivos.
5. Atualização e Comunidade
A área evolui semanalmente com novas ameaças e tecnologias (como o uso de IA para criar ou detectar malwares).
Acompanhe notícias em sites especializados como The Hacker News, Wired e blogs de segurança.
Participe de comunidades de segurança para trocar experiências e se manter informado sobre novos ataques de "dia zero" ou técnicas de engenharia social.
Um ponto importante destacado pelas fontes é que não há limite de idade para começar e o conhecimento profundo de matemática nem sempre é um pré-requisito para o treinamento básico na área.

---

## ⚠️ Cicatrizes (aprendizado)

* Perguntas muito genéricas geram respostas vagas
* Prompts mais específicos melhoram muito a qualidade

---

## 📘 Miniguia de Cybersegurança

### 🔹 Conceitos principais

* Tríade CIA: Os três pilares da segurança são Confidencialidade (dados acessíveis apenas a autorizados), Integridade (dados precisos e não alterados) e Disponibilidade (sistemas prontos para uso).
* Vulnerabilidade, Ameaça e Risco: Uma vulnerabilidade é uma fraqueza em um sistema; uma ameaça é um evento com potencial de causar dano; e o risco é o potencial de perda quando uma ameaça explora uma vulnerabilidade
* Zero Trust (Confiança Zero): Um modelo de segurança que opera sob o princı́pio de "nunca confiar, sempre verificar" cada tentativa de acesso, independentemente de sua origem
* Defesa em Profundidade: Estratégia de implementar múltiplas camadas de proteção para que, se uma falhar, as outras garantam a segurança

---

### 🔹 Boas práticas

* Gestão de Senhas: Use senhas fortes (mı́nimo de 12 caracteres, com letras maiúsculas, minúsculas, números e sı́mbolos). Nunca reutilize a mesma senha em diferentes serviços
* Autenticação de Dois Fatores (MFA/2FA): Ative sempre uma segunda camada de verificação para impedir acessos mesmo que a senha seja descoberta
* Atualizações Constantes: Mantenha sistemas operacionais e aplicativos atualizados com as versões mais recentes e os últimos patches de segurança
* Backup (Estratégia 3-2-1): Mantenha pelo menos três cópias dos dados, em dois tipos de mı́dia diferentes, com uma cópia fora do local (off-site) ou na nuvem
* Cuidado com Phishing: Desconfie de mensagens urgentes, verifique o e-mail real do remetente e passe o mouse sobre links para ver o destino real antes de clicar

---

### 🔹 Exemplos reais

* WannaCry: Um ataque de ransomware que afetou milhares de computadores em 150 paı́ses, causando prejuı́zos bilionários
* Stuxnet: Um worm sofisticado que visou o programa nuclear do Irã, manipulando centrı́fugas para falharem fisicamente
* Ataque à Adobe (2013): Resultou no roubo de dados de cerca de 150 milhões de contas e de parte do código-fonte de produtos como o Photoshop
* Phishing em Redes Sociais: Uso de perfis falsos ou mensagens de "redefinição de senha" para sequestrar contas de usuários e solicitar dinheiro a contatos

---

### 🔹 Roadmap de aprendizado

1. Fundamentos de TI: Estude o funcionamento de hardware e sistemas operacionais (Windows, Linux/Kali Linux e MacOS)
2. Redes de Computadores: É o passo inicial obrigatório. Domine protocolos como TCP/IP, UDP, DNS, ARP e DHCP
3. Programação: Aprenda linguagens úteis para automação e análise de segurança, como Python, C/C++, SQL e JavaScript
4. Segurança Ofensiva e Defensiva: Entenda as funções do Blue Team (defesa e monitoramento) e do Red Team (testes de invasão e ética hacker)
5. Certificações: Busque validações de mercado como CompTIA Security+, Microsoft SC-900 ou CCNA para nı́veis iniciais, progredindo para CEH ou OSCP
6. Prática: Utilize plataformas de desafios como TryHackMe ou Hack The Box para ganhar experiência "mão na massa"

---

### 🔹 Glossário

* Malware: Termo genérico para qualquer código malicioso (vı́rus, worms, trojans, etc.).
* Phishing: Golpe que usa mensagens falsas como "iscas" para "pescar" dados sensı́veis dos usuários.
* Ransomware: Malware que sequestra (criptografa) dados e exige o pagamento de um resgate para devolvê-los.
* Pentest (Teste de Invasão): Ataque simulado e autorizado contra um sistema para encontrar e reportar falhas.
* Engenharia Social: Técnica de manipulação psicológica para induzir pessoas a realizar ações ou divulgar informações confidenciais.
* Botnet: Rede de computadores infectados (zumbis) controlados remotamente por um atacante para ataques de larga escala

---

### 🔁 Prompts reutilizáveis

- Explique **cybersegurança** de forma simples  
- Liste problemas reais e formas de prevenção sobre **phishing**  
- Crie um guia prático sobre **iniciar uma carreira na área de pentest**  
- Explique **malware** com exemplos reais

---

## 🤖 Uso do NotebookLM

O NotebookLM foi utilizado para centralizar as fontes e gerar respostas baseadas nos materiais selecionados, permitindo aprendizado ativo por meio de perguntas estratégicas (prompts).
