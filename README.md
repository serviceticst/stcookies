# ST-Cookies
## Plugin de aceite de cookies para GLPI

## Visão geral

O ST-Cookies adiciona um banner de preferências de cookies ao fluxo de login do GLPI e fornece uma página administrativa para configurar a mensagem de consentimento exibida aos usuários.

<img width="1913" height="924" alt="image" src="https://github.com/user-attachments/assets/d4953b84-c1aa-4d74-8124-66b1eef2cbe6" />

<img width="1915" height="931" alt="image" src="https://github.com/user-attachments/assets/031fbd87-50e1-47fa-80ab-058aba883fee" />

## Funcionalidades

- Banner de consentimento de cookies na tela de login
- Tratamento separado para cookies obrigatórios e opcionais
- Consentimento opcional para **Lembrar de mim**
- Página administrativa para personalizar a mensagem do banner
- Registro em log com data/hora, IP, usuário (quando disponível) e categorias aceitas

## Compatibilidade

- 📥 [Plugin para versão 10 do GLPI (Em breve)
- 📥 [Plugin para versão 11 do GLPI](https://github.com/serviceticst/stcookies/releases/tag/v2.0.0)

## Instalação

1. Copie a pasta `stcookies` do **pacote GLPI 10** para o diretório de plugins do seu GLPI.
2. Limpe o cache do GLPI.
3. Habilite o plugin em **Configurar > Plug-ins**.
4. Abra a página de configuração do plugin e ajuste a mensagem de consentimento, se necessário.

## Logs

Por padrão, o plugin grava os eventos de consentimento em arquivo de log, conforme o layout do seu ambiente.
Em produção, o ideal é usar rotação com `logrotate` ou mecanismo equivalente.

<img width="1338" height="76" alt="image" src="https://github.com/user-attachments/assets/f8e0f008-3b3b-4478-b07c-d98ef361d232" />

## Licença

Este repositório está licenciado sob **GPL v3**.

## Aviso de marca

**GLPI** é marca da **Teclib'**.
Este projeto é um plugin independente e não é afiliado nem endossado pela Teclib', salvo indicação explícita.







