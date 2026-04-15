# <img src="https://flagcdn.com/w40/br.png" width="40"> 🧩 Plugin ST-Cookies para GLPI

- O ST-Cookies adiciona um banner de preferências de cookies ao fluxo de login do GLPI e fornece uma página administrativa para configurar a mensagem de consentimento exibida aos usuários.

<img width="1913" height="924" alt="image" src="https://github.com/user-attachments/assets/d4953b84-c1aa-4d74-8124-66b1eef2cbe6" />

<img width="1915" height="931" alt="image" src="https://github.com/user-attachments/assets/031fbd87-50e1-47fa-80ab-058aba883fee" />

## Funcionalidades

- Banner de consentimento de cookies na tela de login
- Tratamento separado para cookies obrigatórios e opcionais
- Consentimento opcional para **Lembrar de mim**
- Página administrativa para personalizar a mensagem do banner
- Registro em log com data/hora, IP, usuário (quando disponível) e categorias aceitas

### 📋 Compatibilidade

- 📥 [Plugin para versão 10 do GLPI] (Em breve)
- 📥 [Plugin para versão 11 do GLPI](https://github.com/serviceticst/stcookies/releases/tag/v2.0.0)

## Instalação

1. Copie a pasta **stcookies** do pacote do plugin para o diretório de plugins do GLPI.
2. Limpe o cache do GLPI.
3. Habilite o plugin em **Configurar > Plug-ins**.
4. Abra a página de configuração do plugin e ajuste a mensagem de consentimento, se necessário.

## Logs

- Por padrão, o plugin grava os eventos de consentimento em arquivo de log, conforme a configuração do seu ambiente.
- Em produção, o ideal é usar rotação com `logrotate` ou mecanismo equivalente.

<img width="1338" height="76" alt="image" src="https://github.com/user-attachments/assets/f8e0f008-3b3b-4478-b07c-d98ef361d232" />

## Licença

- Este repositório está licenciado sob **[GPL v3](https://github.com/serviceticst/stcookies/blob/main/LICENSE)**. 

## Aviso de marca

- **GLPI** é marca da **Teclib'**. Este projeto é um plugin independente e não é afiliado nem endossado pela Teclib', salvo indicação explícita.

***
### Desenvolvido por: Service TIC Soluções Tecnológicas

- [![E-mail](https://img.icons8.com/ios-filled/16/ffffff/mail.png)](mailto:contato@servicetic.com.br) **E-mail**: [contato@servicetic.com.br](mailto:contato@servicetic.com.br)
- [![Website](https://img.icons8.com/ios-filled/16/ffffff/domain.png)](http://www.servicetic.com.br) **Site**: [www.servicetic.com.br](http://www.servicetic.com.br)
- [![LinkedIn](https://img.icons8.com/ios-filled/16/ffffff/linkedin-circled.png)](https://www.linkedin.com/company/serviceticst) **LinkedIn**: [@serviceticst](https://www.linkedin.com/company/serviceticst)
- [![Instagram](https://img.icons8.com/ios-filled/16/ffffff/instagram-new.png)](https://www.instagram.com/serviceticst) **Instagram**: [@serviceticst](https://www.instagram.com/serviceticst)
- [![Facebook](https://img.icons8.com/ios-filled/16/ffffff/facebook-new.png)](https://www.facebook.com/serviceticst) **Facebook**: [@serviceticst](https://www.facebook.com/serviceticst)
- [![X](https://img.icons8.com/ios-filled/16/ffffff/x.png)](https://x.com/serviceticst) **Twitter**: [@serviceticst](https://x.com/serviceticst)
- [![YouTube](https://img.icons8.com/ios-filled/16/ffffff/youtube-squared.png)](https://youtube.com/c/serviceticst) **YouTube**: [@serviceticst](https://youtube.com/c/serviceticst)
- [![WhatsApp](https://img.icons8.com/ios-filled/16/ffffff/whatsapp.png)](https://whatsapp.com/channel/0029VaAkV3P59PwXAiDepu3N) **WhatsApp Channel**: [Clique aqui](https://whatsapp.com/channel/0029VaAkV3P59PwXAiDepu3N)

[![image](https://github.com/user-attachments/assets/17192a13-f0b6-4531-add0-99c7f46c24b0)](https://servicetic.com.br/links/)








