# Clínica Skin Lounge — Premium V4

Principais alterações:

## Scroll reveal corrigido
- o site usa um viewport interno de 100svh
- IntersectionObserver observa esse viewport explicitamente
- os elementos já começam ocultos antes do body ser pintado
- fade + translate acontecem somente quando entram no scroll real
- funciona também em previews/iframes que antes tratavam a página inteira como visível

## Agendamento dentro do site
Fluxo interativo:
1. atendimento
2. data
3. horário
4. dados
5. confirmação demonstrativa

IMPORTANTE:
- datas e horários atuais são DEMONSTRATIVOS
- nenhum dado do formulário é enviado ou armazenado
- para produção, o frontend precisa ser conectado à agenda/API/banco da clínica
- WhatsApp ficou somente como canal secundário de suporte

Abra index.html no navegador.
