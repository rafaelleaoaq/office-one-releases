# Office One — versões

Instalador e versões publicadas do **Office One**: Word One, Excel One e PowerPoint One, aplicativos para Windows
compatíveis com os arquivos do Microsoft Office, em português do Brasil.

## Instalar

Baixe o instalador:
**[Office-One-Instalador.exe](https://github.com/rafaelleaoaq/office-one-releases/releases/latest/download/Office-One-Instalador.exe)**

Ele pergunta se a instalação é para todos os usuários do computador (pede permissão de administrador) ou só para
você (sem permissão de administrador), deixa escolher os aplicativos — os três ou só alguns — e baixa as versões mais
novas durante a instalação.

## Atualizações

Depois de instalados, os aplicativos se atualizam sozinhos: uma vez por dia procuram uma versão nova e, quando há,
mostram as novidades e baixam só o pacote daquele aplicativo. Não é preciso baixar o instalador de novo.

## Conteúdo deste repositório

Só as versões (o código-fonte fica em outro repositório). Cada release traz:

- o pacote do aplicativo que mudou (`WordOne-<versão>.zip`, `ExcelOne-<versão>.zip` ou `PowerPointOne-<versão>.zip`);
- o `latest.json`, com a versão, o endereço, o tamanho e o SHA-256 de cada aplicativo e do instalador;
- o instalador, sempre com o nome `Office-One-Instalador.exe`.

Os aplicativos e o instalador só aceitam pacotes deste repositório cujo SHA-256 confere com o `latest.json`.

© 2026 Rafael Leão Alencar Queiroz — rafaelleao@gmail.com. Baseado em projetos de código aberto (MIT OR
Apache-2.0); os avisos de licença acompanham cada aplicativo (`THIRD-PARTY-LICENSES.txt`). Sem vínculo com a Microsoft.
