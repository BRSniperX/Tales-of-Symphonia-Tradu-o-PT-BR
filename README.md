<img width="1254" height="1254" alt="Imagem do ChatGPT 7 de out  de 2026, 20_14_44" src="https://github.com/user-attachments/assets/14867b34-8b91-436f-911a-6be4d063b183" />
# Tales of Symphonia — Tradução PT-BR v1.1

Tradução para português do Brasil de **Tales of Symphonia** (PC / Steam, 2016).

O jogo inteiro: a história, as skits, os menus e a arte.

> ⚠️ **O jogo precisa estar em ESPANHOL.** Esta tradução ocupa o lugar do idioma
> espanhol — ela não acrescenta um idioma novo. No jogo, escolha **Español**.

---

## Novidades da v1.1

**7.366 falas que tinham ficado em espanhol, em 39 cenas.**

Um jogador avisou que a casa do Dirk estava em espanhol. A causa era um erro na ferramenta que lê as cenas: em 39 dos 499 arquivos ela confundia um número solto no código com a lista de falas, achava a cena vazia e a pulava sem avisar. O erro foi corrigido e conferido nos 499 arquivos, e as 39 cenas foram traduzidas como o resto do jogo: japonês × português, depois a leitura só do português.

O que entrou:

- a casa do Dirk: o Brasão-Chave, a lembrança da mãe do Lloyd, o Anel Eterno e as espadas, a Coleção de Figuras e a customização;
- Palmacosta: a gincana, a academia, a casa do governador-geral, a execução da Chocolat e o barco a vapor;
- Meltokio: a chegada do Zelos, a despedida da Shihna, o Coliseu e os moradores da capital;
- Mizuho: o acordo com o vice-chefe Tiga, a Ilha Ganryu e o quimono do duelo;
- Heimdall: a noite antes do duelo com o Kratos;
- os selos com o Remiel, o pacto com a Ondina e Asgard;
- Izoold (Max e Lyla), Flanoir (Lágrima de Celsius e Luvas de Pinguim), a Floresta de Ymir, a vila dos Katz e a mina de Toize;
- a masmorra do Livro de Niflheim.

Quem já tem a v1.0 instala do mesmo jeito: copia a pasta P12E da v1.1 por cima. Só o texto muda; os saves continuam valendo.

---

## O que está traduzido

| | |
|---|---|
| Falas das cenas da história | 45.194 |
| Skits (as conversas com os retratos) | 3.397 falas em 391 skits |
| Conversas de pousada e eventos de batalha | 623 |
| Sistema — menus, itens, ars, monstros, títulos, tutoriais, sinopse | 5.931 |
| Nomes dos golpes dos inimigos | 106 |
| Artes — placas de cidade, menu da tela-título, Blackjack, caça-níquel, HUD | 67 |

---

## Traduzida do japonês, não do inglês do jogo

O PC não tem o texto japonês das cenas. Ele veio do **PS3 japonês**: as
46.340 falas das cenas foram casadas, uma a uma, com o japonês original. O
inglês e o espanhol serviram de testemunhas — quem decide o sentido é o japonês.

**Onde o inglês se afasta do original:**

| Japonês | Aqui | O inglês do jogo |
|---|---|---|
| `神子にはデリス・カーラーンへ来てもらわねばならん` | **A Escolhida tem que vir a Derris-Kharlan.** | "We will take the Chosen as the new body for Martel." |
| `ユニコーンの術で調合し` | combinados **pela arte do unicórnio** | "fused using Boltzman's technique" |
| `原人物語` | **Contos do Homem Primitivo** | "Fabulae Aboriginarum" |
| `セイヴァー` (golpe de inimigo) | **Salvador** | "Saber" |

### Os nomes são os do japonês

| Japonês | Aqui | Inglês |
|---|---|---|
| ジーニアス | **Genius** | Genis |
| リフィル | **Refill** | Raine |
| しいな | **Shihna** — a grafia que o próprio jogo usa no Teste de Som | Sheena |

Por isso a recomendação: **jogue com as vozes em japonês.** Os nomes do texto
batem com o que se ouve.

O espanhol renomeia personagens — Dirk vira *Galarr*, Altessa vira *Fjalar*.
Aqui ficam os nomes do original. E onde o espanhol deixou golpes de chefe em
inglês, eles foram traduzidos do japonês: **Campo do Leão**, **Campo
Flutuante**, **Dragão Rompe-Céu**.

### Os termos

Quando o japonês diz outra coisa que o inglês, vale o japonês:

- 大いなる実り, *Great Seed* → **Grande Fruto**
- 五聖刃, *Grand Cardinals* → **Cinco Lâminas Sagradas**
- 精霊, *Summon Spirit* → **Espírito**

Os termos da série seguem o **Tales of Vesperia — Definitive Edition**, que tem
tradução oficial em português do Brasil: **Ars**, **Superação**, **Gald**,
**Ondina**, **Ifrite**, **Sílfide**, **Gnomo**.

---

## A arte

- **28 placas de cidade**, montadas com as **letras originais** das placas do
  jogo. Só foi desenhado o que a fonte não tinha. Os subtítulos seguem o japonês
  da placa: **A Cidade Flutuante** (空中都市), **A Vila Oculta dos Elfos**,
  **A Cidade Renascida**.
- **O menu da tela-título**: Novo jogo, Carregar jogo, Opções, Sair do jogo,
  Teste de som.
- **O cassino**: as letras do Blackjack (**VITÓRIA**, **DERROTA**, **EMPATE**) e os
  botões do caça-níquel (**GIRAR**, **AP. MÁX.**, **AP. UMA**).
- **O HUD da batalha.**
- **Os nomes dos golpes dos inimigos**, que ficam gravados nos arquivos de cada
  monstro.

---

## Verificação

```
texto      55.145 textos, 0 erros no QA (códigos, largura, caracteres da fonte)
formato    os textos que o jogo monta na hora (%s, %d) seguem a estrutura do espanhol,
           e os símbolos de 2 bytes do jogo (×, →) estão preservados
largura    caixa medida no jogo: até 54 letras por linha
fonte      ã, õ, ç, « » aparecem no jogo
pacote     cada arquivo é conferido com o que foi instalado e testado
```

Cada bloco da tradução passou por **duas leituras**: a primeira, japonês ×
português, fala por fala; a segunda, só o português, na ordem da cena, para
pegar o que soa traduzido.

---

## Instalação

1. Feche o jogo.
2. Abra a pasta do jogo: na Steam, botão direito no jogo → **Gerenciar** →
   **Explorar arquivos locais** (a pasta onde fica o `TOS.exe`).
3. Copie a pasta **`P12E`** do zip para dentro dela, aceitando **substituir** os
   arquivos.
4. No jogo, escolha o idioma **Español**.

```
...\steamapps\common\Tales of Symphonia\
```

**A Steam desfaz a instalação:** a verificação de integridade, ou uma atualização
do jogo, devolve os arquivos originais e o jogo volta ao espanhol. Basta copiar
a pasta de novo.

**Desinstalar:** na Steam, botão direito no jogo → **Propriedades** →
**Arquivos instalados** → **Verificar integridade dos arquivos do jogo**.

Versão de outra loja ou de console não é suportada por este pacote.

---

## Sobre os arquivos

O pacote substitui **4 arquivos** do jogo: o `TLFILE.TLDAT` e o
`FILEHEADER.TOFHDB` dos pacotes `R01` (textos de sistema) e `R03` (espanhol).
Não há instalador, programa, script nem DLL. O `ARQUIVOS.txt` traz o SHA-256 de
cada arquivo.

O zip tem ~980 MB porque o pacote `R01` do jogo, de 1 GB, vai inteiro.

Para sua segurança, o zip completo foi verificado no VirusTotal:
<LINK_VIRUSTOTAL>

---

## O que ficou de fora, de propósito

- Os **menus de depuração** (e o mapa de testes, que o jogador nunca vê) ficam em inglês,
  como no jogo original.
- O **logotipo** do jogo.

Achou algo além disso? Um print da tela resolve mais rápido que qualquer descrição.

---

*Tales of Symphonia ©Kosuke Fujishima ©BANDAI NAMCO Entertainment Inc. Todos os
direitos reservados. Projeto de fã, gratuito e sem fins lucrativos, sem vínculo
com a Bandai Namco ou os detentores da obra.*
