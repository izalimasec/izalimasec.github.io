---
title: "Gestão de Identidade com Microsoft Entra ID"
weight: 1
---

# 🔑 SC-300: O Novo Perímetro de Segurança

No modelo **Zero Trust**, a identidade é o primeiro sinal de defesa. Como Engenheira de SecOps, meu foco no Entra ID (antigo Azure AD) é garantir que o acesso certo seja dado à pessoa certa, no momento certo.

## 🛡️ Pilares da Gestão de Acesso

### 1. Acesso Condicional (Conditional Access)
Não basta ter a senha. O sistema analisa:
* **User/Location:** De onde vem o acesso?
* **Device:** O dispositivo é gerenciado e seguro?
* **Application:** Qual recurso está sendo acessado?
* **Risk:** Existe comportamento anómalo? (Integração com ID Protection).

### 2. Privileged Identity Management (PIM)
O conceito de **Just-In-Time (JIT)**. 
* Ninguém tem privilégios de administrador permanentemente.
* O acesso é ativado por tempo limitado e requer aprovação ou MFA.
* **Garantia de Integridade:** Redução drástica da movimentação lateral em caso de comprometimento.

## 📊 Governança e Auditabilidade
Todo log de entrada e alteração de privilégio deve ser ingerido pelo **Microsoft Sentinel** para análise forense e conformidade com a LGPD.

---
> "Identidade é o novo firewall. Se a identidade for comprometida, o perímetro deixa de existir."