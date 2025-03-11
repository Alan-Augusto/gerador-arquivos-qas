# Gerador de Arquivos Para Testes

Um aplicativo web simples e elegante para gerar arquivos de diferentes tamanhos e formatos para testes e desenvolvimento.

## Visão Geral

Esta ferramenta permite criar arquivos dummy com tamanho e formato específicos, úteis para:
- Testar sistemas de upload de arquivos
- Simular dados para sistemas de armazenamento
- Testar velocidades de download/upload
- Avaliar compressão de arquivos
- Simular vários tipos de arquivos para verificação de tipo MIME

## Características

- **Interface Minimalista**: Design limpo e moderno inspirado em shadcn/ui
- **Diversos Formatos**: Suporte para mais de 40 extensões de arquivo diferentes
- **Tamanho Personalizável**: Especifique o tamanho exato em KB, MB ou GB
- **Download Individual**: Baixe cada arquivo separadamente
- **Download em Lote**: Opção para baixar todos os arquivos em um único ZIP
- **Feedback Visual**: Barra de progresso para acompanhar a geração

## Extensões Suportadas

### Documentos
- doc, docx, docm
- xls, xlsx, xlsm
- ppt
- odt, rtf, pdf, xml

### Imagens
- bmp, jpg, jpeg, png, gif, svg

### Arquivos de Texto
- csv, txt, re

### Arquivos de Segurança
- ekp, pfx

### Arquivos Compactados
- zip, rar, 7z
- tar, gz, bz2, xz, z
- tgz, tbz2, tlz, lzma

### Arquivos de Sistema
- cab, iso, dmg, lz, wim
- apk, xpi, deb, rpm, cpio

## Como Usar

1. Abra o arquivo HTML em qualquer navegador moderno
2. Digite o nome base para os arquivos
3. Especifique o tamanho desejado e selecione a unidade (KB, MB, GB)
4. Selecione as extensões de arquivo desejadas
5. Clique em "Gerar Arquivos"
6. Baixe os arquivos individualmente ou todos juntos em formato ZIP

## Limitações

- O tamanho máximo recomendado é de 2GB devido às limitações de memória dos navegadores
- Os arquivos contêm dados aleatórios e não são arquivos válidos dos formatos indicados (apenas a extensão é correta)
- O processo de geração ocorre no navegador e utiliza recursos do cliente

## Requisitos Técnicos

- Navegador moderno com suporte a JavaScript ES6+
- JSZip (incluído via CDN)
- Não requer instalação ou configuração de servidor

## Desenvolvimento

Este projeto usa vanilla JavaScript e não requer frameworks ou compilação. Para modificar:

1. Clone o repositório
2. Edite o arquivo HTML conforme necessário
3. Teste em seu navegador local
4. Faça o commit das alterações

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter detalhes.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar problemas
- Sugerir novos recursos
- Enviar pull requests

## Contato

Se você tiver dúvidas ou sugestões, abra uma issue no GitHub.

---

**Nota**: Esta ferramenta foi projetada para fins de teste e desenvolvimento. Os arquivos gerados contêm apenas dados aleatórios e não são estruturalmente válidos para seus respectivos formatos.