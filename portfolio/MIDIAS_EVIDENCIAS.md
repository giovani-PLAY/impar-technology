# Evidências visuais — publicação controlada

## Materiais já localizados

Foram recuperados três arquivos visuais do PDF `Portfolio_Giovani_Barbare.pdf`, fornecido anteriormente pelo titular:

| Arquivo planejado | Origem | Interpretação correta | Estado no GitHub |
| --- | --- | --- | --- |
| `portfolio/media/educa-brasil-entrada.webp` | Tela da prévia visual do Educa Brasil de 19/10/2026 | Primeiro acesso com Google **simulado**, sem uso de banco real | **Aguardando upload da imagem** |
| `portfolio/media/educa-brasil-cadastro.webp` | Tela da mesma prévia | Etapa visual do cadastro; não comprova fluxo de produção | **Aguardando upload da imagem** |
| `portfolio/media/operacao-horizonte-quadro.webp` | Quadro produzido pela rotina de desenho do jogo v1.0.13 | Render do próprio protótipo; não comprova desempenho em aparelho físico | **Aguardando upload da imagem** |

O pacote de arquivos foi entregue ao titular em ZIP na conversa. Esta proposta de portfólio não deve exibir essas imagens enquanto os arquivos não estiverem no repositório e autorizados para exposição pública.

## Vídeos reais ainda necessários

| Projeto | Nome do arquivo a enviar | Roteiro de 20–40 segundos |
| --- | --- | --- |
| Ímpar Turbo | `portfolio/media/impar-turbo-demo.mp4` | Abrir o aplicativo no Samsung, navegar pelo painel e uma função comprovadamente operacional, sem revelar dados ou APK |
| Educa Brasil | `portfolio/media/educa-brasil-demo.mp4` | Gravar a execução da prévia educacional, com o Google simulado claramente identificado |
| Operação Horizonte | `portfolio/media/operacao-horizonte-demo.mp4` | Registrar a versão real em execução, incluindo movimento e tiros por toque |

**Não há vídeos de execução comprovados anexados nesta etapa.** Não criar slideshow ou vídeo sintético para substituí-los.

## Comportamento do site

As páginas PT-BR e EN carregam as imagens somente após confirmação de que cada arquivo existe, e incorporam vídeo somente após confirmação da existência do MP4. Assim, o visitante não verá mídias quebradas nem um botão de reprodução fictício.

As páginas usam caminhos relativos; a versão em inglês aponta para a pasta `../media/`.

## Antes de qualquer publicação

1. Confirmar que as capturas são autênticas e podem ser exibidas publicamente.
2. Remover notificações, contas, dados de alunos e dados sensíveis de qualquer gravação.
3. Carregar os arquivos individuais em `portfolio/media/` na branch de proposta, não na `main`.
4. Conferir as duas páginas em smartphone, teclado e desktop com as mídias reais presentes.
5. Exigir aprovação específica antes do merge e da publicação via GitHub Pages.

Nenhum vídeo foi gravado ou publicado por este documento. Nenhum código privado, APK ou segredo deve ser incluído.
