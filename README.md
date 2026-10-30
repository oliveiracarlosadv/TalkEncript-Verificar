# TalkEncript - Verificar

Página pública de verificação dos relatórios de integridade gerados pelo **GestorLaw - TalkEncript**.

Endereço: https://oliveiracarlosadv.github.io/TalkEncript-Verificar/

O QR code impresso em cada relatório abre esta página com o número do relatório e o código de verificação. Quem recebe o relatório arrasta para a página o pacote do relatório (ZIP ou pasta) e os arquivos da conversa, e a página confere:

- se o arquivo de dados do relatório corresponde ao código de verificação do QR code;
- se cada arquivo é idêntico ao registrado, pelos códigos SHA-256 e SHA3-512.

Toda a conferência é feita no navegador de quem acessa: **nenhum arquivo é enviado pela internet**. A assinatura digital do relatório em PDF deve ser conferida no validador oficial do ITI (https://validar.iti.gov.br).

Este repositório contém apenas a página de verificação, gerada a partir do código do TalkEncript (`npm run build:verificador`). Componentes de código aberto embutidos: hash-wasm (MIT) e fflate (MIT).

TalkEncript, criado por Carlos Alexandre Albuquerque Oliveira, advogado, OAB/PA 33.996.
