# 🛡️ Simulação Educativa de Phishing: O Perigo da Engenharia Social na Era das IAs

## 📒 Descrição
Projeto desenvolvido para o desafio **"Natural ou Fake Natty?"** da [Digital Innovation One (DIO)](https://dio.me). 

O objetivo deste projeto foi explorar o poder das IAs Generativas para criar um cenário realista de ataque de engenharia social (phishing corporativo) com propósito estritamente defensivo e educacional, acompanhado de um checklist detalhado de identificação e resposta a incidentes.

---

## 🤖 Tecnologias Utilizadas
- **Kimi K2.7 Code:** IA Generativa utilizada para estruturar o cenário, redigir o e-mail convincente e criar o checklist de defesa.
- **Markdown / GitHub:** Para documentação, versionamento e publicação do portfólio.

---

## 🧐 Processo de Criação
Utilizando conceitos de **Engenharia de Prompt**, instruí a IA a assumir o papel de especialista em segurança da informação e conscientização corporativa. 

O prompt foi desenhado para explorar dois dos gatilhos psicológicos mais explorados em golpes reais:
1. **Autoridade:** Falso comunicado vindo do suporte interno de TI.
2. **Urgência:** Ameaça de bloqueio de acesso em 24 horas para forçar uma ação impensada.

Para garantir conformidade com as boas práticas de cibersegurança, o conteúdo gerado aplicou a técnica de *defanging* (desarmar URLs maliciosas usando colchetes, como `[.]`), garantindo que o material seja seguro para treinamento.

---

## 🚀 Resultados

O material completo gerado está disponível neste repositório no arquivo `treinamento-simulacao-de-e-mail-de-phishing.pdf`. Abaixo está a síntese do exercício:

### 1. E-mail Simulado (Cenário de Ataque)
* **De:** TI Suporte `<ti-suporte@empresa-seguranca[.]com>`
* **Assunto:** 🚨 URGENTE: Sua conta de e-mail será bloqueada em 24 horas — Atualize sua senha agora
* **Mensagem:**
  > Prezado(a) Colaborador(a),  
  > Identificamos atividades suspeitas em sua conta corporativa de e-mail e, por medida de segurança, será necessário redefinir sua senha imediatamente.  
  > ⚠️ Caso a atualização não seja realizada em até 24 horas, sua conta será bloqueada.  
  > Para evitar o bloqueio, clique no link: `http://portal-colaborador-empresa[.]secure-update[.]net/redefinir-senha`

---

### 2. Anatomia do Golpe (Checklist de Defesa)
- **Remetente Falso:** O domínio `@empresa-seguranca.com` tenta imitar o domínio oficial da empresa (`empresa.com.br`).
- **Urgência Excessiva:** Palavras como "URGENTE" e prazo curto forçam a vítima a agir sem pensar.
- **Link Malicioso:** O link real direciona para `secure-update.net`, uma página externa clonada para roubo de credenciais.
- **Solicitação Insegura:** Setores de TI sérios não solicitam redefinição de senhas diretamente por links não solicitados.
- **Resposta Direta:** O atacante pede resposta para confirmar que o e-mail do colaborador está ativo.

---

### 3. O que fazer diante da ameaça?
1. **Pare:** Não clique em links nem baixe anexos.
2. **Verifique o remetente:** Inspecione o domínio completo.
3. **Desconfie da urgência:** Prazos curtos são o principal indicativo de golpe.
4. **Valide por canal oficial:** Entre em contato com a equipe de TI por outro meio.
5. **Reporte:** Encaminhe a mensagem para a equipe de segurança (`seguranca@empresa.com.br`).

---

## 💭 Reflexão (Natty or Not?)
Este experimento comprovou o quão **"Natty" (natural e convincente)** a IA Generativa pode ser. No passado, ataques de phishing eram facilmente identificados por erros graves de português ou formatações toscas. Hoje, a IA permite que criminosos criem comunicações impecáveis e altamente personalizadas. 

Por outro lado, o projeto também demonstra o papel da IA como aliada dos defensores: ela permite estruturar treinamentos internos completos de conscientização em poucos minutos, nivelando o jogo a favor da segurança.
