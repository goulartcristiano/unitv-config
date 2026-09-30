# Gerador local

Versão estática em HTML, CSS, JavaScript e Web Components. Não usa Python, servidor nem bibliotecas externas.

## Abrir

Abra `index.html` em um navegador moderno. A tela contém o gerador individual e os downloads de aplicativos.

## Arquivos

- `core.js`: geração dos arquivos e criação de ZIP.
- `simple-app.js`: componentes e interações da interface.
- `styles.css`: tema escuro e layout responsivo.
- `index.html`: ponto de entrada.

O botão **Baixar .config** cria um nome como `CONFIG_20260930_185313_4284.config`; a extensão `.config` fica no final do nome. **Salvar arquivos** usa o seletor de diretório quando disponível; se o navegador não oferecer essa função, baixa um ZIP.

Os cards de APK usam arquivos da pasta `../apps/` do projeto, que deve permanecer ao lado de `newversion/`.