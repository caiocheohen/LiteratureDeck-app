<div align="center">

# LiteratureDeck

**Seu acervo acadêmico no bolso. Offline, sem conta, sem nuvem.**

Organize artigos e livros, leia PDFs com anotações e gere citações em 8 estilos.

[**⬇ Baixar a última versão**](../../releases/latest)

</div>

<!--
CAPTURAS DE TELA: crie a pasta docs/ no repositório, envie 3 a 4 imagens (biblioteca, leitor de PDF, citações)
e descomente o bloco abaixo ajustando os nomes dos arquivos.

<p align="center">
  <img src="docs/biblioteca.png" width="24%" alt="Biblioteca">
  <img src="docs/leitor.png" width="24%" alt="Leitor de PDF">
  <img src="docs/citacoes.png" width="24%" alt="Citações">
</p>
-->

## Por que o LiteratureDeck

- **Seus dados ficam com você.** Biblioteca, PDFs e anotações ficam no aparelho. Não há conta, anúncio nem rastreamento.
- **Tudo em um lugar.** Referências, PDFs, notas e citações no mesmo app.
- **Feito para pesquisa.** Estilos de citação acadêmicos, importação e exportação de formatos padrão e backup completo em um arquivo.

## Recursos

**Biblioteca**
- Busca e filtros por categoria, tag, coleção, status de leitura e prioridade
- Coleções, categorias e tags
- Preenchimento automático de metadados por DOI, ISBN ou URL (usa a internet só quando você aciona)

**Leitura**
- Leitor de PDF com marca-texto, sublinhado, desenho à mão e notas
- Progresso de leitura e anotações salvos por documento
- Notas gerais por referência

**Citações e interoperabilidade**
- 8 estilos: APA 7, ABNT NBR 6023, Vancouver, Nature, IEEE, Chicago 17, Harvard e MLA 9
- Importação de BibTeX e RIS
- Exportação em BibTeX, RIS, CSL-JSON e CSV
- Exportação de PDFs em lote (tudo, ou por categoria, coleção, tag ou status)

**Backup**
- Backup completo em um único arquivo `.literaturedeck.zip`, com referências, PDFs, anotações e notas
- **Restauração sem duplicatas:** restaurar o mesmo backup várias vezes não cria cópias, e a edição mais recente de cada referência prevalece
- Compartilhamento do backup por Bluetooth, Quick Share e outros apps
- PDFs armazenados no aparelho ou no cartão de memória

## Instalação

1. Acesse a página de [**Releases**](../../releases/latest) e baixe `LiteratureDeck-x.y.apk`.
2. Quando o Android pedir, permita a instalação de apps desta fonte.
3. Abra o arquivo baixado e toque em **Instalar**.

Requer **Android 7.0** ou superior.

### Verificar a integridade do arquivo

Cada release informa o **SHA-256** do APK nas notas e traz o arquivo `.sha256`. Para conferir:

```bash
# Linux ou macOS
sha256sum LiteratureDeck-x.y.apk

# Windows (PowerShell)
Get-FileHash LiteratureDeck-x.y.apk -Algorithm SHA256
```

O resultado deve ser idêntico ao publicado na release.

### Atualizar

Instale o novo APK por cima do atual. Seus dados são mantidos. Por segurança, faça um backup antes (Configurações → Criar backup).

## Versão para computador (Linux)

Existe uma versão em arquivo único `LiteratureDeck.html`, que roda no navegador (Chrome, Edge, Brave ou Firefox) e usa o **mesmo formato de backup**. Assim você leva sua biblioteca entre o celular e o computador: crie o backup em um e restaure no outro. Quando disponível, o arquivo fica anexado às releases.

## Perguntas frequentes

**Onde ficam meus PDFs?**
Na pasta privada do app, no aparelho ou no cartão de memória (você escolhe em Configurações). Para tirá-los do celular, use "Exportar PDFs" ou "Criar backup".

**O app envia meus dados para algum lugar?**
Não. A única conexão de rede é a busca de metadados por DOI, ISBN ou URL, que você mesmo aciona.

**Como passo minha biblioteca para outro aparelho?**
Crie um backup em Configurações, envie o arquivo `.literaturedeck.zip` para o outro aparelho e use "Restaurar backup" lá. Restaurar mais de uma vez não duplica nada.

**Posso importar de outro gerenciador de referências?**
Sim, se ele exportar em BibTeX ou RIS, como a maioria faz.

**O app é gratuito?**
Sim.

## Privacidade

O LiteratureDeck funciona offline. Não há contas, anúncios nem rastreamento. Seus dados permanecem no seu aparelho.

## Suporte e sugestões

Encontrou um problema ou tem uma ideia? Abra uma [issue](../../issues) informando a versão do app, o modelo do aparelho e a versão do Android.

## Licença

© Caio Cheohen. Todos os direitos reservados. O código-fonte não é público.
