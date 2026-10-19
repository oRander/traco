# Traço

Um quadro de desenho para explicar ideias, montar diagramas e conectar conceitos.

**[Abrir o Traço](https://orander.github.io/traco/)**

## Recursos

- Desenho à mão livre com correção automática de círculos, retângulos, triângulos e linhas.
- Opção **Corrigir desenhos** para ligar ou desligar o ajuste dos traços.
- Ferramentas de círculo, retângulo, triângulo, seta e texto.
- Balde de tinta para preencher formas e traços fechados com a cor escolhida.
- Cores personalizadas, espessura do traço e preenchimento ao desenhar formas.
- Camadas com seleção, visibilidade e ordenação por arraste ou pelos botões de subir e descer.
- Movimentação dos elementos e redimensionamento pelas alças nos cantos.
- Abas de quadros para separar assuntos, cada uma com seu histórico de desfazer e refazer durante a sessão.
- Botão **Zerar quadro**, com possibilidade de recuperar usando Desfazer.
- Importação de imagens e colagem de prints.
- Salvamento de projetos editáveis em JSON e exportação em PNG.
- Interface adaptada para celular, com ferramentas na parte inferior e painéis de camadas e cores.

## Como usar

1. Abra o site e desenhe no quadro.
2. Use **+ Novo quadro** para começar outro desenho sem apagar o anterior. Edite o nome no campo do topo.
3. Para manter o rabisco original, desmarque **Corrigir desenhos**. A escolha fica salva neste navegador e afeta os próximos traços à mão livre.
4. Para pintar uma forma, escolha uma cor, selecione **Balde** e clique dentro dela. O balde preenche formas do quadro e traços fechados; não pinta regiões dentro de uma imagem importada.
5. Use **Selecionar** para arrastar elementos ou redimensioná-los pelos cantos.
6. Clique em **Salvar projeto** para baixar o quadro atual em JSON. Use **Abrir** para carregá-lo novamente, substituindo o conteúdo da aba atual.
7. Use **Exportar PNG** para baixar uma imagem do quadro atual.

No celular, use **Camadas** e **Cores e opções** para abrir os painéis. **Importar imagem** permite escolher uma imagem da galeria.

## Atalhos

Os números funcionam tanto na fileira acima das letras quanto no teclado numérico.

| Tecla | Ação |
| --- | --- |
| 1 | Selecionar |
| 2 | Desenhar à mão livre |
| 3 | Círculo |
| 4 | Retângulo |
| 5 | Seta |
| 6 | Texto |
| 7 | Triângulo |
| 8 | Balde de tinta |
| Ctrl+Z | Desfazer |
| Ctrl+Y ou Ctrl+Shift+Z | Refazer |
| Ctrl+V | Colar uma imagem copiada, inclusive prints |
| Delete ou Backspace | Excluir o elemento selecionado |
| Setas | Mover o elemento selecionado em 1 unidade do quadro |
| Shift+setas | Mover em 10 unidades |
| Esc | Limpar a seleção e ativar Selecionar |
| Shift ao redimensionar | Manter a proporção |
| Alt+clique com o balde | Remover o preenchimento |

Ao desenhar círculos ou retângulos com suas ferramentas, segure **Shift** para manter largura e altura iguais.

## Salvamento e privacidade

Os quadros e a preferência de correção são salvos no armazenamento local do navegador. Os desenhos e as imagens importadas **não são enviados ao GitHub nem sincronizados entre dispositivos**.

- Outro navegador, perfil ou computador tem seu próprio armazenamento.
- Limpar os dados do site remove os quadros salvos localmente. Em navegação anônima, os dados normalmente são descartados ao encerrar a sessão.
- Abas do navegador não se atualizam em tempo real; editar em várias delas pode sobrescrever o salvamento local.
- O histórico de desfazer/refazer e a opção de reabrir um quadro fechado valem durante a sessão; não são preservados após recarregar.
- **Salvar projeto** baixa apenas o quadro atual. Faça uma cópia de cada quadro importante, especialmente se usar muitas imagens e atingir o limite de armazenamento.
- Para continuar em outro dispositivo ou endereço, salve o JSON e abra-o no destino.

## Executar localmente

Baixe ou clone o repositório e abra `index.html` em um navegador moderno. Não há dependências para instalar nem etapa de compilação.

O site usa HTML, CSS, JavaScript e SVG. A colagem pelo botão pode depender das permissões do navegador; use **Ctrl+V** ou **Importar imagem** como alternativa.

## Publicação

O site é hospedado no GitHub Pages a partir da branch `main`, pasta raiz. Alterações nessa branch são publicadas automaticamente.

Para publicar uma cópia, acesse **Settings → Pages**, escolha **Deploy from a branch**, selecione a branch desejada e a pasta **/ (root)** e salve.
