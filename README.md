BPMN - Fluxograma de processo
<img width="1011" height="412" alt="image" src="https://github.com/user-attachments/assets/7608e678-56d2-47db-902b-96ac021345da" />


# Desenvolvimento dos Chamados  / Suporte Técnico

Este documento descreve o fluxo padrão para análise, desenvolvimento, testes e validação de chamados, garantindo qualidade, rastreabilidade e alinhamento com o cliente.

---

## 🎯 Objetivo

Padronizar o tratamento de chamados desde a abertura até a validação final, reduzindo retrabalho, riscos técnicos e falhas de comunicação entre atendimento e desenvolvimento.

---

## 1. Abertura do Chamado (Atendimento)

O chamado deve ser criado pelo atendimento contendo, obrigatoriamente:

- Descrição clara da demanda  
- Problema que o cliente deseja resolver  
- Contexto de uso ou exemplo prático  
- Prioridade e prazo solicitado.  

>  !! Chamados com informações incompletas **não seguem para análise técnica**.

---

## 🔍 2. Análise de Viabilidade Técnica

Responsável: **Equipe Técnica**

### 2.1 Verificação de funcionalidade existente
- Avaliar se a demanda já é atendida pelo sistema  
- Verificar soluções alternativas sem necessidade de customização  

**Possíveis resultados:**
- ✅ Demanda já atendida → retorno ao atendimento com orientação  
- ➡️ Demanda não atendida → continuar análise  

---

### 2.2 Avaliação técnica
- Estimativa de tempo de execução  
- Impacto no sistema  
- Riscos técnicos ou estruturais  

**Possíveis resultados:**
- ❌ Não viável tecnicamente → retorno ao atendimento com justificativa  
- ✅ Viável → continuar processo  

---

### 2.3 Alinhamento de escopo
- Validar se a solução proposta resolve a real necessidade do cliente  
- Sugerir ajustes ou alternativas quando necessário  

**Possíveis resultados:**
- 🔄 Escopo não alinhado → ajuste e nova validação  
- ✅ Escopo alinhado → seguir para execução  

---

## 💾 3. Backup do Sistema

Antes de qualquer alteração:

- Realizar backup completo dos arquivos do site  
- O backup é **obrigatório**, independentemente do tamanho ou complexidade da alteração  
- Registrar:
  - Data e hora  
  - Responsável  
  - Local do backup  

---

## 🧪 4. Definição e Execução de Casos de Teste

### 4.1 Definição dos testes
Os testes devem cobrir, no mínimo:

- Fluxo principal da funcionalidade  
- Cenários de erro  
- Impactos em funcionalidades relacionadas  

---

### 4.2 Execução dos testes
- Executar testes manuais e/ou automatizados  
- Registrar resultados e evidências  

**Possíveis resultados:**
- ❌ Testes reprovados → correção e nova execução  
- ✅ Testes aprovados → seguir para validação  

---

### 4.3 Documentação dos testes
- Registrar os casos de teste executados  
- Indicar o resultado final  
- Anexar evidências (prints, logs, etc.), quando aplicável  

---

## 📤 5. Envio para Validação do Atendimento

Após a aprovação dos testes, o chamado deve ser enviado ao atendimento contendo:

- Descrição do que foi implementado  
- Casos de teste executados  
- Impactos conhecidos ou observações relevantes  

---

## ✔️ 6. Validação do Atendimento

O atendimento valida a entrega conforme o cenário do cliente.

**Possíveis resultados:**
- ✅ Aprovado → chamado concluído  
- ❌ Reprovado → retorno para ajustes conforme feedback  

> Alterações de escopo podem exigir nova análise de viabilidade.

---

## 🔚 7. Encerramento do Chamado

O chamado é encerrado somente após:

- Validação do atendimento  
- Registro do resultado final  

Todo o histórico deve permanecer documentado para consulta futura.

---

## 📌 Considerações Gerais

- Reprovação também é uma entrega válida, desde que justificada  
- Todo o processo deve ser rastreável  
- A melhoria contínua do processo é responsabilidade de todos os envolvidos  

