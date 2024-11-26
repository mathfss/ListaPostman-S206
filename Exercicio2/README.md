## ❓ **Perguntas e Respostas**

### **1. Os testes desenvolvidos são manuais ou automatizados?**
- **Resposta**: Os testes desenvolvidos são automatizados.  
- **Justificativa**: Apesar de serem executados manualmente no Postman inicialmente, os scripts na aba **Tests** validam automaticamente os resultados, tornando-os automatizados.

### **2. Os testes são Fim-a-Fim (End-To-End)?**
- **Resposta**: Não.  
- **Justificativa**: Os testes focam em endpoints isolados da API e não simulam fluxos completos de usuário ou integração entre serviços. Isso os exclui da classificação de End-To-End.

### **3. O que deve ser feito para que os testes funcionem em modo regressão?**
- Configure **automação dos testes** com ferramentas como o **Postman Runner** ou **Newman**.  
- Integre os testes em pipelines de **CI/CD** para execução contínua.  
- Garanta que os arquivos de Collection e Environment estejam atualizados e versionados em um repositório.  
- Use monitoramento do Postman para agendamento recorrente e relatórios automatizados.
