# Body After 40 — landing AlkaBurn

Página estática (sem build), feita para publicar na Vercel. Mesmo esquema da landing do ProstaVive.

## Antes de divulgar
1. Abra `index.html`, procure o bloco **CONFIG** e troque `PASTE_ALKABURN_HOPLINK_HERE` pelo seu HopLink do ClickBank.
2. Em `about.html` e `privacy.html`, troque `contact@your-domain.com` pelo seu e-mail de contato.

## Como funciona
- Hero com o gancho → 5 perguntas → resultado (Mild / Moderate / Significant) → recomendação de pacote (1, 3 ou 6 frascos) → botão para o HopLink.
- Resultado leve sugere 3 frascos; moderado ou alto sugere 6 frascos. Os 3 pacotes sempre aparecem.
- O pacote escolhido não é pré-selecionado na página do fabricante (o ClickBank não permite); ele vai só no rastreio.

## Links para o ManyChat (palavra BURN)
- `https://SEU-PROJETO.vercel.app/?src=fb01dm&h=photos`
- Troque `fb01` pelo número do vídeo. Ganchos disponíveis (`h=`): photos, diet, belly.

## Rastreio no ClickBank (TID)
`src` + `ab` + pacote. Ex.: `fb01dmab6` = vídeo 01 do Facebook, veio do Messenger, clicou no pacote de 6.
Veja em ClickBank → Reporting → Analytics, filtrando por TID.

## Eventos (Vercel Analytics → Events)
`quiz_start`, `quiz_done`, `click_1`, `click_3`, `click_6`, `click_sticky`.
