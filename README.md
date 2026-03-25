# rh-copiloto-ia
#      
RH Copiloto IA – Automação de Comunicação Interna com RAG 
##        
Objetivo do Projeto 
Automatizar a criação de comunicações internas do setor de Recursos 
Humanos utilizando Inteligência Artificial Generativa, reduzindo tarefas 
repetitivas e aumentando a produtividade. --- 
##     
Como Funciona 
O sistema integra automação com IA: 
1. Google Forms → coleta de dados   
2. Google Docs → modelo padrão da empresa   
3. Gemini → geração automática do texto   
4. Gmail → envio automático do e-mail   ---

    ## ⚙️ Instalação e Configuração

1. Criar um Google Forms com os campos necessários
2. Criar um modelo padrão no Google Docs
3. Criar um cenário no Make com os módulos:
   - Google Forms (Watch Responses)
   - Google Docs (Get Document)
   - Google Gemini (Generate Content)
   - Gmail (Send Email)
4. Configurar as conexões entre os módulos
5. Inserir o prompt no módulo Gemini
6. Testar a automação com "Executar uma vez"
##      
Passo a Passo de Uso 
1. Preencha o formulário com as informações solicitadas   
2. Envie o formulário   
3. A automação será executada automaticamente   
4. O sistema gera o e-mail baseado no padrão da empresa   
5. O e-mail é enviado automaticamente   --- 
##      
Exemplo de Entrada - assunto do e-mail: aviso   - objetivo da mensagem: aviso sobre Mudança no horário de expediente   - informações principais: informar a alteração   - data: Informar data   - horário: Novo horário das 8h às 17h   - destinatários: colaboradores da empresa - Tom: Formal   --- 
##      
Exemplo de Saída 
> Prezados colaboradores,   
>   
> Informamos que, a partir da próxima semana, o horário de expediente 
será ajustado para das 8h às 17h.   
>   
> Agradecemos a colaboração de todos.   
>   
> Atenciosamente,   
> Recursos Humanos   --- 
##    
Link do Projeto 
(https://us2.make.com/public/shared-scenario/osCFDpPrkve/integration
google-forms) --- 
##         - Make   
Tecnologias Utilizadas - Google Forms   - Google Docs   - Google Gemini   - Gmail   --- 
Este projeto utiliza RAG (Retrieval-Augmented Generation), permitindo que 
a IA gere textos com base em um modelo padrão da empresa, garantindo 
consistência e qualidade na comunicação.
