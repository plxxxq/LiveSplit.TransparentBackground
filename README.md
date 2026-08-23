# LiveSplit.TransparentBackground

[English](#english) | [Português](#português)

## English

A lightweight LiveSplit component that makes the timer window background transparent. It was created for people who use a single monitor or do not want to configure Chroma Key in their recording or streaming software.

### Installation

1. Download `LiveSplit.TransparentBackground.dll` from the [latest Release](https://github.com/plxxxq/LiveSplit.TransparentBackground/releases/latest).
2. Close LiveSplit.
3. Open the folder where LiveSplit is installed.
4. Copy `LiveSplit.TransparentBackground.dll` to:

   ```text
   LiveSplit\Components
   ```

5. Open LiveSplit again. The DLL works automatically and does not need to be added to the layout.

### Required configuration

Right-click LiveSplit, open **Edit Layout > Layout Settings** and set the background to pure black:

```text
#000000
```

If **Background Color** and **Background Color 2** are available, set both to black. Black will become transparent; any other color will remain visible.

### Moving the window

After the background becomes transparent, the window can only be moved by dragging directly over LiveSplit text or numbers.

### Uninstallation

Close LiveSplit and delete `LiveSplit.TransparentBackground.dll` from the `Components` folder.

### License

Distributed under the [MIT License](LICENSE).

---

## Português

Um componente leve para LiveSplit que deixa transparente o fundo da janela do cronômetro. Foi criado para quem utiliza apenas um monitor ou não quer configurar Chroma Key no programa de gravação ou transmissão.

### Instalação

1. Baixe `LiveSplit.TransparentBackground.dll` na [Release mais recente](https://github.com/plxxxq/LiveSplit.TransparentBackground/releases/latest).
2. Feche o LiveSplit.
3. Abra a pasta onde o LiveSplit está instalado.
4. Copie `LiveSplit.TransparentBackground.dll` para:

   ```text
   LiveSplit\Components
   ```

5. Abra o LiveSplit novamente. A DLL funciona automaticamente e não precisa ser adicionada ao layout.

### Configuração obrigatória

Clique com o botão direito no LiveSplit, abra **Edit Layout > Layout Settings** e deixe a cor de fundo em preto puro:

```text
#000000
```

Se aparecerem as opções **Background Color** e **Background Color 2**, deixe as duas em preto. O preto ficará transparente; qualquer outra cor continuará visível.

### Movendo a janela

Depois que o fundo ficar transparente, a janela só poderá ser movimentada arrastando diretamente por cima de algum texto ou número do LiveSplit.

### Desinstalação

Feche o LiveSplit e apague `LiveSplit.TransparentBackground.dll` da pasta `Components`.

### Licença

Distribuído sob a [Licença MIT](LICENSE).
