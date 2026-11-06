# O Sol no Templo

Simulação interativa da sombra do Sol no Templo de Salomão: as colunas Jachin e Boaz e as doze colunas zodiacais, nos solstícios e equinócios, com o movimento real do Sol ao longo do dia e do ano.

O site é um único arquivo, `index.html`. Não precisa de servidor, banco de dados nem instalação: abra no navegador ou hospede em qualquer serviço de páginas estáticas.

## Como usar

1. **Data** — arraste a barra Data, toque num dos quatro marcos (equinócios e solstícios) ou arraste o Sol na roda do zodíaco.
2. **Hora** — arraste a barra Hora solar ou use Nascer, Meio-dia e Pôr.
3. **Animação** — o botão Dia passa as horas; o botão Ano passa as datas mantendo o momento escolhido.
4. **Leitura** — o texto abaixo da planta explica a sombra do momento; a legenda identifica as marcas do chão; o quadro lateral traz os números.
5. **Cenário** — mude o local, a planta (Templo de Salomão ou loja maçônica), a cobertura e a ordem das colunas.
6. **Roteiros prontos** — na seção "Como usar" da página, cada botão "Ver na planta" monta uma cena pronta.

A hora mostrada é a **hora solar**: 12h00 é quando o Sol cruza o meridiano do lugar. Ela difere da hora do relógio pela longitude, pela época do ano (até cerca de 16 minutos) e pelo horário de verão.

## Como publicar no GitHub Pages

1. Crie um repositório **público** no GitHub (por exemplo, `sol-no-templo`).
2. Na página do repositório: **Add file → Upload files**, arraste `index.html` e este `README.md`, e clique em **Commit changes**.
3. Vá em **Settings → Pages**. Em *Build and deployment*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**, e salve.
4. Em um ou dois minutos o site fica em `https://<seu-usuario>.github.io/sol-no-templo/`.

Para atualizar, envie um novo `index.html` pelo mesmo caminho. Um domínio próprio pode ser ligado em **Settings → Pages → Custom domain**.

## Modelo

Posição do Sol pelo algoritmo simplificado do Almanaque Náutico (precisão melhor que 0,1°), em hora solar verdadeira, sem refração atmosférica; datas de 2026. Dimensões em côvados de 1 Reis 6–7 (côvado comum ≈ 45 cm). A altura das colunas zodiacais e as larguras das portas são ilustrativas. A posição de Jachin e Boaz e a ordem dos signos variam entre ritos.

Fontes tipográficas carregadas do Google Fonts; sem conexão, o navegador usa fontes do sistema.
