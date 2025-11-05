
<h1 align="center">Vib3</h1>

<p align="center">
  <img src="favicon.ico" width="120" alt="Vib3 Icon"/><br><br>
  <b>Download de músicas e playlists do Spotify de forma simples e profissional.</b><br>
  Desenvolvido para uso em rádios indoor e projetos musicais automatizados.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.8+-green.svg"/>
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg"/>
  <img src="https://img.shields.io/badge/license-MIT-orange.svg"/>
  <img src="https://img.shields.io/badge/platform-Windows-lightgrey.svg"/>
</p>

---

## Instalação

### Pré-requisitos

- **Python 3.8+** (apenas se for rodar o código fonte)
- **FFmpeg** (necessário para conversão de áudio)

```bash
winget install Gyan.FFmpeg
````

> O executável (`Vib3.exe`) já vem com todas as dependências Python incluídas.
> Basta extrair e executar o arquivo.

---

##  Como Usar

### Baixar uma Música

1. Execute `Vib3.exe`
2. Escolha a opção **1** (Música individual)
3. Cole a **URL** ou **ID** da música
   Exemplo:

   ```
   https://open.spotify.com/track/6EF9PYqEk5SdbCCQJ9q8jT
   ```
4. Confirme com **s**
5. Música salva em `C:\Users\SeuUsuario\Downloads\Músicas`

### Baixar uma Playlist

1. Execute `Vib3.exe`
2. Escolha **2** (Playlist completa)
3. Cole a URL ou ID

   ```
   https://open.spotify.com/playlist/37i9dQZF1DXcBWIGoYBM5M
   ```
4. Confirme com **s**
5. Acompanhe a barra de progresso e aguarde o relatório final

---

## Local de Salvamento

As músicas são salvas em:

```
C:\Users\SeuUsuario\Downloads\Músicas\
```

Incluem:

* Qualidade até **320kbps**
* Metadados (título, artista, álbum)
* Capa do álbum
* Formato **MP3**

---

## Recursos

* Download individual ou de playlists completas
* Interface colorida e intuitiva
* Logs detalhados de erros
* Sistema remoto de autorização
* Alta estabilidade e desempenho

---

## FAQ

**Por que preciso do FFmpeg?**
Necessário para converter os arquivos para MP3.

**Preciso ter Python instalado?**
Não, se estiver usando o executável.

**Qualidade das músicas?**
Até **320kbps** com capa e metadados.

**Falhas no download?**
Podem ocorrer se a música não estiver disponível na região ou tiver restrição de fonte.

**Compatibilidade?**
Atualmente otimizado para **Windows**.

---

## Aviso Legal

Este projeto é apenas para fins **educacionais e uso pessoal**.
O download de músicas protegidas por direitos autorais pode violar os termos do Spotify.
Recomenda-se o **Spotify Premium** para uma experiência legal e completa.

---

## Autor

**eueliseeu**
🔗 [GitHub](https://github.com/eueliseeu)

---

<p align="center">
Feito por <a href="https://github.com/eueliseeu">eueliseeu</a><br>
Se gostou do projeto, deixe uma estrela!
</p>
