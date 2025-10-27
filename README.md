# Automação de Envio de Emails

⚠️ **Atenção:** Este repositório contém apenas uma parte do código do projeto.  
O programa completo está funcionando no vídeo demonstrativo abaixo.

📺 **Assista ao vídeo do projeto completo aqui:** [[link do vídeo](https://youtu.be/6e_SPgRu8Bc)]

---

## Descrição

Este projeto é um **script de automação de envio de emails** em Python, que permite gerenciar e enviar mensagens de forma programada.  

Funcionalidades principais:

- Permite **deixar emails programados** para envio em datas e horários específicos.  
- Envia emails **imediatamente** se desejado.  
- **Verifica data e hora** para enviar os emails automaticamente quando programados.  
- Permite **editar ou excluir emails programados** antes do envio.  
- Envia emails para **todos os contatos de planilhas** (CSV ou Excel) localizadas em uma pasta específica.  
- Suporta múltiplas planilhas na pasta, facilitando envios em massa.

---

## Tecnologias utilizadas

- **Python** – linguagem principal do projeto  
- **smtplib** e **email** – para envio de emails  
- **pandas** e **openpyxl** – para manipulação de planilhas Excel/CSV  
- **numpy** – usado internamente pelo **pandas**  
- **python-dateutil**, **pytz** e **tzdata** – para manipulação de datas e horários  
- **schedule** – para agendamento de envios automáticos  
- **requests**, **urllib3**, **certifi**, **charset-normalizer**, **idna**, **six**, **et_xmlfile** – dependências auxiliares necessárias para integração com planilhas e conexões HTTP  


