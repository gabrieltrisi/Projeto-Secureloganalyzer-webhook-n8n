# 🔐 SecureLog Analyzer

Projeto de **Segurança da Informação e Automação**, desenvolvido em **Python**, com foco na **análise automatizada de logs de autenticação**, detecção de atividades suspeitas e geração de alertas para ambientes corporativos.

---

## 🎯 Objetivo

Simular práticas utilizadas em ambientes de **SOC / SIEM / SOAR**, automatizando a identificação de comportamentos anômalos em logs de autenticação e reduzindo a necessidade de análise manual.

---

## 🧠 Como funciona

1. O sistema recebe arquivos de **logs de autenticação**
2. Realiza a análise automática dos eventos
3. Identifica padrões suspeitos, como:
   - Tentativas repetidas de login
   - Possível força bruta
4. Classifica o nível de risco
5. Gera alertas automáticos
6. Envia notificações via **webhook**, integrando com ferramentas como **n8n**

---

## ⚙️ Tecnologias Utilizadas
- **Python**
- **Regex**
- **Automação de processos**
- **Webhooks**
- **n8n**
- Conceitos de **Segurança da Informação**

---

## 📌 Funcionalidades
- ✔️ Análise de logs de autenticação
- ✔️ Detecção de força bruta
- ✔️ Classificação de risco
- ✔️ Geração de relatórios
- ✔️ Integração via webhook
- ✔️ Simulação de ambiente SOC

---

## 🖥️ Demonstração

![SecureLog Analyzer Demo](assets/securelog-demo.gif)

---

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/gabrieltrisi/securelog-analyzer.git

# Acesse o diretório
cd securelog-analyzer

# Execute o script
python securelog_analyzer.py
