# Repositório GoShare - Compartilhando Projetos da Comunidade Dev'sCafé

Bem-vindo ao repositório GoShare! Este é um espaço destinado à comunidade Dev'sCafé para compartilhar e descobrir projetos interessantes desenvolvidos por seus membros. Para manter a qualidade e relevância dos projetos compartilhados, algumas regras e limitações foram estabelecidas. Por favor, leia atentamente antes de contribuir ou utilizar os recursos deste repositório.

## Descrição

O GoShare é um repositório no GitHub criado pela comunidade Dev'sCafé para compartilhar projetos desenvolvidos por seus membros. Ele serve como um espaço de exposição para projetos em diversas áreas, como software, inteligência artificial, hardware, sistemas operacionais, web, redes, desenvolvimento de baixo nível, entre outros.

## Regras e Limitações

1. **Aprovação de Projeto:** Antes de adicionar um projeto ao repositório GoShare, é necessário obter a aprovação de um responsável da comunidade Dev'sCafé. Isso garante a relevância e qualidade dos projetos compartilhados.

2. **Estrutura de Pastas:** Os projetos devem ser organizados de acordo com suas respectivas categorias, dentro das pastas específicas do repositório. Cada projeto deve ter sua própria pasta com o nome do autor.

3. **Conteúdo da Pasta do Projeto:** Dentro da pasta de cada projeto, deve haver exatamente dois arquivos:
   - `readme.md`: Este arquivo deve conter uma descrição detalhada do projeto, sua funcionalidade, instruções de uso e quaisquer outras informações relevantes. Também devem ser incluídos links para o projeto, de forma clara e evidente.
   - `project-meta.json`: Este arquivo contém metadados do projeto, que serão utilizados para exibição na página do GoShare no site do Dev'sCafé. Os detalhes específicos sobre o formato deste arquivo devem ser fornecidos pelo responsável da comunidade.

4. **Conteúdo Permitido:** A página do projeto (dentro do `readme.md`) pode conter textos, imagens, gifs e outros elementos visuais que ajudem a apresentar o projeto de forma eficaz. No entanto, é importante que todo o conteúdo esteja de acordo com as diretrizes de conduta da comunidade Dev'sCafé e não viole nenhuma regra de direitos autorais.

5. **Contribuições:** As contribuições são bem-vindas e encorajadas. No entanto, os contribuidores devem seguir as mesmas regras de aprovação de projeto e estrutura de pastas mencionadas acima.

## Estrutura de Diretórios

O repositório GoShare possui a seguinte estrutura de diretórios:
```
📁 software
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 ai-ml
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 hardware
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 so
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 web
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 redes-web
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

📁 lowlevel
  📁 projeto-autor
    📄 readme.md
    📄 project-meta.json

```

Por favor, siga essa estrutura ao adicionar novos projetos ao repositório.
---

## Formato JSON para project-meta.json

```json
{
  "title": "Título do Projeto",
  "description": "Descrição do Projeto",
  "longDescription": "Descrição mais detalhada do projeto.",
  "author": "Nome do Autor",
  "repository": "Link para o Repositório",
  "license": "Tipo de Licença",
  "version": "Versão do Projeto",
  "tags": ["tag1", "tag2", "tag3"],
  "image": "URL da Imagem do Projeto"
}
```

- `"title"`: O título do projeto.
- `"description"`: Uma breve descrição do projeto.
- `"longDescription"`: Uma descrição mais detalhada do projeto.
- `"author"`: O nome do autor ou dos autores do projeto.
- `"repository"`: O link para o repositório do projeto.
- `"license"`: O tipo de licença sob a qual o projeto está distribuído.
- `"version"`: A versão atual do projeto.
- `"tags"`: Uma lista de tags ou palavras-chave que descrevem o projeto. 3 a 5 tags.
- `"image"`: URL de uma imagem representativa do projeto.

Certifique-se de preencher essas informações adequadamente ao criar ou atualizar o arquivo `project-meta.json` para seu projeto.

---

## Contribuindo

Se você tem um projeto interessante que gostaria de compartilhar com a comunidade Dev'sCafé, siga as regras de contribuição e envie sua proposta para aprovação.

Obrigado por fazer parte desta comunidade e por contribuir para o GoShare!

**Nota:** Este documento está sujeito a alterações e atualizações. Certifique-se de consultar a versão mais recente antes de contribuir ou utilizar o repositório.


