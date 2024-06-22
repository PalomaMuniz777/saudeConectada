<h1 align="center">
<img src="Saúde Conectada.png" >
<p>Sistema Automatizado de Check-in e Triagem de Pacientes👩‍⚕️👨‍⚕️</p>
</h1>

## Equipe:
<img src="./Equipe.png">


- **Maria Beatriz Mota Rios Pereira**
UX/UI Designer
mariabeatrizmota@gmail.com

- **Paloma Muniz Mendes**
Dev - IA Engenharia de Prompt
palomamendespp@gmail.com

- **Samille Leão dos Santos Negrão** 
Ux Designer
samille_sleao@hotmail.com

- **Wendy Barbosa Conceição**
Gestora de Negócios
eng.wendyconceicao@gmail.com

## 🟢[Slide Deck (Clique Aqui)](https://www.canva.com/design/DAGInn03a6E/-z5iJdVTPKdpRXXIZGbnSA/edit?utm_content=DAGInn03a6E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## 🟢[Documentação & Códigos (Clique Aqui)](https://docs.google.com/document/d/15MtYBp7sGZS8Ym6zl8YY1vqxWogQprvWmMsF-Tpo_FE/edit#heading=h.ppmdzeim78w9)


## About ✔
Este projeto demonstra um sistema automatizado de check-in e triagem de pacientes que utiliza identificação biométrica, inteligência artificial (IA) e localização por GPS para otimizar o processo de admissão e gestão de consultas em clínicas e hospitais.

🟢**Funcionalidades:**

**Identificação Biométrica:** Permite o registro e autenticação de pacientes através de reconhecimento facial.

**Previsão de Tempo de Espera:** Utiliza modelos de IA para estimar o tempo de espera com base no número de pacientes.

**Localização por GPS:** Obtém a localização do paciente para otimizar agendamentos e fornecer direções.

**Agendamento:** Permite agendar consultas com base na disponibilidade e na localização dos pacientes.

**Triagem Inteligente:** Prioriza pacientes com base na gravidade do caso e na proximidade.

**Requisitos:**
Python 3.x

**Bibliotecas:**
face_recognition
sklearn
requests
flask (opcional para API)

**Instalação:**
Instale o Python: https://www.python.org/downloads/

**Instale as bibliotecas:**
      pip install face_recognition scikit-learn requests flask
    content_copyUse code with caution.Bash

**Execução:**

**Identificação Biométrica:**
Execute o script biometria.py:
      python biometria.py
content_copyUse code with caution.Bash
Ajuste o caminho para a imagem do paciente no script.
O script realiza o reconhecimento facial e compara com um banco de dados de codificações faciais (a ser implementado em um projeto real).

**Previsão de Tempo de Espera:**
Execute o script previsao_espera.py:
      python previsao_espera.py
 content_copyUse code with caution.Bash
Ajuste os dados de treinamento no script para refletir cenários reais.
O script cria um modelo de regressão linear e prevê o tempo de espera com base no número de pacientes.

**Obtenção de Localização:**
Execute o script localizacao.py:
      python localizacao.py
   
 content_copyUse code with caution.Bash
O script utiliza a API ip-api.com para obter a localização do dispositivo.

**Agendamento (API):**
Execute o script app.py:
      python app.py
   
 content_copyUse code with caution.Bash
Acesse a API RESTful através de um cliente HTTP ou um navegador.
Utilize o método POST para criar um novo agendamento e o método GET para obter todos os agendamentos.

**Observações:**
Os exemplos de código são simplificados para demonstração.
Um sistema completo exigiria um desenvolvimento mais extenso, incluindo um banco de dados, interface gráfica e implementação de API completa.
Este projeto serve como base para o desenvolvimento de um sistema real.

**Contribuições:**
Contribuições para este projeto são bem-vindas! Você pode contribuir com:
Correção de bugs
Melhoria de código
Implementação de novas funcionalidades
Licença:
Este projeto está sob a licença MIT.
Agradecimento:
Agradecemos a todos os contribuidores deste projeto!

## Manual Completo do App "Saúde Conectada"


Bem-vindo ao "Saúde Conectada", seu aplicativo para um atendimento médico mais ágil e seguro!
Este manual detalhado irá guiá-lo pelas funcionalidades do aplicativo, ajudando-o a aproveitar ao máximo suas vantagens e garantir uma experiência de saúde mais fluida e eficiente.

**1. Introdução**
"Saúde Conectada" é um aplicativo inovador que utiliza tecnologia de ponta para transformar a experiência do paciente em clínicas e hospitais. Com recursos como check-in biométrico, triagem inteligente, comunicação automatizada em emergências e agendamento personalizado, o aplicativo visa otimizar o fluxo de pacientes, reduzir filas, melhorar a comunicação e garantir um atendimento mais rápido e seguro.
**2. Download e Cadastro**

Baixe o Aplicativo: Acesse a loja de aplicativos do seu dispositivo (Google Play ou App Store) e procure por "Saúde Conectada". Baixe e instale o aplicativo.
Crie sua Conta: Abra o aplicativo e siga as instruções para criar uma conta. Você precisará fornecer algumas informações pessoais, como nome completo, data de nascimento, e-mail e telefone. Defina uma senha segura para acessar sua conta.
**3. Check-in Biométrico**

Acesso Rápido: Abra o aplicativo e toque no botão "Check-in". Posicione seu rosto dentro do círculo da câmera para iniciar o reconhecimento facial.
Autenticação Segura: O aplicativo utiliza tecnologia de reconhecimento facial para confirmar sua identidade. Se o reconhecimento for bem-sucedido, você será direcionado para a próxima tela.
Facilidade e Eficiência: O check-in biométrico elimina a necessidade de preencher formulários, agilizando o processo e reduzindo filas.
**4. Triagem Inteligente**

Classificação de Risco: Após o check-in, responda às perguntas da triagem com atenção e sinceridade. O aplicativo utiliza algoritmos de IA para analisar seus sintomas e classificar a gravidade da sua situação.
Direcionamento Adequado: Você receberá uma classificação de risco (leve, moderado, grave) e orientações sobre o próximo passo. Se necessário, o aplicativo poderá direcioná-lo para o atendimento de emergência.
Atendimento Personalizado: A triagem inteligente permite que você receba o atendimento médico mais adequado às suas necessidades.

**5. Emergência Automatizada**
Segurança em Situações Críticas: Em caso de emergência, clique no botão "Emergência" na tela. Confirme que precisa de uma ambulância.
Comunicação Direta: O aplicativo solicitará sua localização via GPS e você poderá gravar uma mensagem de áudio para fornecer informações adicionais sobre sua situação.
Alerta Automático: O aplicativo enviará automaticamente um alerta para o hospital mais próximo com sua localização e informações relevantes, garantindo que você receba ajuda rápida.

**6. Agendamento de Consultas**
Agendamento Online: Acesse a tela de "Agendamento" e selecione a especialidade médica desejada.
Horários e Localização: Escolha a data e o horário que melhor lhe convêm, considerando a disponibilidade do profissional. O aplicativo mostrará os horários disponíveis e a localização da consulta.
Confirmação: Confirme seu agendamento e receba notificações com lembretes da consulta.

**7. Histórico de Consultas**
Controle do Atendimento: Acesse a tela de "Histórico" e visualize a lista de suas consultas agendadas, realizadas e canceladas.
Detalhes da Consulta: Ao clicar em uma consulta, você pode acessar os detalhes, como o diagnóstico, medicamentos receitados e orientações do profissional.

**8. Notificações**
Mantenha-se Informado: O aplicativo enviará notificações para lembrá-lo de consultas, informar sobre alterações no tempo de espera e fornecer informações importantes sobre seu atendimento.

**9. Configurações**
Atualização de Informações: Acesse as "Configurações" para atualizar suas informações pessoais, como nome, data de nascimento, telefone, e-mail e endereço.
Preferências de Notificação: Configure as preferências de notificação para receber lembretes e alertas específicos.
Contatos de Emergência: Adicione contatos de emergência, como familiares ou amigos, para que eles sejam notificados em situações de urgência.

**10. Dicas para Usar o Aplicativo**

Mantenha seu dispositivo carregado e com acesso à internet para utilizar o aplicativo com eficiência.
Leia atentamente as instruções e mensagens do aplicativo.
Se você tiver alguma dúvida, acesse a seção de ajuda do aplicativo ou entre em contato com o suporte técnico.
O aplicativo "Saúde Conectada" é uma ferramenta para auxiliar no atendimento médico. Em caso de dúvidas, procure atendimento médico profissional.

**11. Considerações Importantes**

O aplicativo "Saúde Conectada" foi desenvolvido para oferecer segurança e privacidade aos seus dados. Todas as informações pessoais são armazenadas de forma segura e criptografada.
A equipe de desenvolvimento do aplicativo está comprometida com a melhoria contínua da plataforma. Novas funcionalidades e atualizações serão adicionadas ao longo do tempo.

**12. Contato**

Para sugestões, dúvidas ou informações adicionais, entre em contato com a equipe de suporte através do email [endereço de email do suporte].
Aproveite ao máximo as vantagens do aplicativo "Saúde Conectada" e tenha uma experiência de saúde mais prática, segura e eficiente!
Aproveite ao máximo as vantagens do aplicativo "Saúde Conectada" e tenha uma experiência de saúde mais prática, segura e eficiente!


