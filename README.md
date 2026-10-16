# Snapix

**Baixe vídeos e áudios do YouTube, do X, do Instagram, do Facebook e de mais de mil outros sites direto no Android, sem anúncios.**

[![Versão mais recente](https://img.shields.io/github/v/release/helveciopereira/snapix?style=for-the-badge&color=8B5CF6&label=Vers%C3%A3o)](https://github.com/helveciopereira/snapix/releases/latest)
![Android 7.0+](https://img.shields.io/badge/Android-7.0%2B-0F131D?style=for-the-badge)

---

## 📥 Download

Baixe o APK na aba [**Releases**](https://github.com/helveciopereira/snapix/releases/latest):

| Arquivo | Para quem |
|---|---|
| `Snapix-v<versão>-arm64-v8a.apk` | **Quase todos os celulares atuais** (Samsung, Xiaomi, Motorola…). Se estiver em dúvida, é este. |
| `Snapix-v<versão>-armeabi-v7a.apk` | Celulares antigos, de 32 bits |
| `Snapix-v<versão>-x86_64.apk` | Emuladores no PC |

Para atualizar, instale o APK novo por cima do antigo. Seus downloads e o histórico ficam.

---

## ✨ O que o Snapix faz hoje

- 🎨 **Visual Nordic Minimal:** tema escuro em ardósia e violeta, com cartões finos e translúcidos. Todas as resoluções e os áudios aparecem numa grade compacta, sem rolar, e o botão **Baixar** fica sempre à vista com o formato e o tamanho. A opção marcada segue a **Resolução padrão** que você escolhe nas Configurações. Na gaveta, **Copiar Link** copia o endereço do vídeo.
- 📲 **Compartilhar → Snapix:** no YouTube, no X ou no navegador, toque em Compartilhar e escolha o Snapix. Uma gaveta abre por cima do app, já com as opções. Você toca em **Baixar** e volta para onde estava; o download segue em segundo plano.
- 🎵 **Áudio:**
  - **MP3 320 kbps** (alta qualidade) ou **192 kbps**, com título e artista gravados no arquivo;
  - ou o **áudio original** do site (M4A/AAC ou Opus), sem conversão e sem perda.
- 🎬 **Vídeo MP4 em todas as resoluções que o site oferecer**, de 144p até 4K.
  - Escolha nas Configurações o **Codec de vídeo preferido**: **H.264** (compatibilidade total: toca em qualquer aparelho, TV e no WhatsApp) ou **AV1** (ultra-econômico: economiza até 50% de espaço e dados móveis em celulares modernos).
  - 1440p e 4K saem em VP9/AV1, porque é assim que o YouTube entrega. O app avisa quando o formato exige decodificação moderna.
- 🔊 **Áudio do vídeo sempre em AAC:** quando o site só tem Opus, o Snapix converte só o áudio para AAC 192 kbps. A imagem é copiada sem perda.
- 🌐 **Idioma original:** nos vídeos do YouTube com dublagem automática, o áudio baixado é o do idioma original.
- 🌐 **Mais de mil sites:** redes sociais, sites de vídeo e de áudio, sites adultos e links diretos para arquivos de vídeo. Quando o site não informa a resolução, aparece a opção **Original do site**. Quando um link não baixa, o app diz o motivo em português (login exigido, bloqueio anti-robô, post só com foto…).
- 📡 **Monitor de conexões:** toque num download em andamento para ver as conexões abertas, a velocidade com gráfico ao vivo, quanto já baixou e o tempo restante.
- ⚡ **Várias conexões ao mesmo tempo:** cada arquivo é baixado em **4, 8, 10 ou 16 partes simultâneas** (aria2c), à sua escolha nas Configurações. A velocidade fica limitada pela sua internet, não por uma conexão só.
- 🗂️ **Fila:** até **5 downloads ao mesmo tempo**; o resto espera a vez. Dá para **pausar e retomar** de onde parou, mesmo depois de fechar o app, e para cancelar, o que apaga os pedaços já baixados.
- 🌙 **Tela desligada:** o download continua com a tela apagada.
- 🔔 **Notificação** com o progresso e o botão "Pausar tudo". É preciso permitir as notificações do Snapix.
- 📁 **Organização:** os arquivos vão para `Download/Snapix/Snapix Video` e `Download/Snapix/Snapix Audio` e aparecem na hora na galeria e no tocador de música.
- 🔄 **Motor sempre em dia:** o extrator (yt-dlp) se atualiza sozinho uma vez por dia. Quando um site muda, normalmente não é preciso instalar um APK novo.

---

## 🛠️ Próximas melhorias

- 🖼️ **Capa do vídeo dentro do MP3**, que aparece no tocador de música.
- 🎚️ **MP3 mais leve** (128 kbps), para economizar espaço.
- ⬆️ **Atualização do app pelo próprio app:** ele avisa quando sai versão nova aqui no GitHub.
- 🧭 **Navegador embutido com detector de vídeo:** você abre a página, e o Snapix encontra o vídeo.
- 📚 **Biblioteca:** busca, filtros e reprodução dos arquivos baixados.

---

## 📲 Como instalar

1. Baixe o `.apk` da aba [Releases](https://github.com/helveciopereira/snapix/releases/latest).
2. Abra o arquivo pela notificação ou pelo gerenciador de arquivos.
3. Se o Android pedir, permita "instalar apps desta fonte".
4. Toque em **Instalar**.

## 📋 Requisitos

- Android **7.0** ou mais novo.
- Espaço livre de pelo menos o dobro do vídeo durante o download, porque vídeo e áudio são juntados no celular.
- Internet (Wi-Fi ou dados móveis).

## ⚠️ Limitações conhecidas

- Conteúdo que exige login (posts sensíveis do X, Reddit, Instagram privado) não baixa: o Snapix não usa sua conta.
- Sites com proteção anti-robô (Dailymotion, PornHub e outros) só baixam no APK **arm64-v8a**, que traz o componente que imita um navegador. Nos APKs de 32 bits e de emulador eles continuam bloqueados.
- Fotos não são baixadas, só vídeo e áudio.
- O tamanho mostrado antes de baixar é uma estimativa e pode variar um pouco.

## ⚖️ Uso responsável

O Snapix é uma ferramenta para uso pessoal. Baixe mídias que são suas, que estão sob licença aberta (Creative Commons) ou cujo download o autor autoriza.
