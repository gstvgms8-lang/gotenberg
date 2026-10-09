# Gotenberg: aplicações nos nossos sistemas

Documentação complementar de gstvgms8-lang, preparada em 09/10/2026 para estudo. As aplicações abaixo são propostas de avaliação, não funcionalidades já integradas aos nossos sistemas.

[Repositório original](https://github.com/gotenberg/gotenberg) · [Nosso fork](https://github.com/gstvgms8-lang/gotenberg) · [README oficial](https://github.com/gotenberg/gotenberg/blob/main/README.md) · [Documentação](https://gotenberg.dev/docs/getting-started/introduction) · [Biblioteca](https://github.com/gstvgms8-lang/referencias-projetos)

## Finalidade

**Área:** Conversão em PDF.

API baseada em Docker para converter documentos em PDF, usando componentes como Chromium e LibreOffice.

## Possíveis aplicações

- Pesquisar geração de relatórios de inventário a partir de HTML.
- Avaliar conversão de documentos de escritório em um serviço auxiliar da API.
- Definir modelos com paginação, cabeçalhos, fontes e tabelas, verificando PDFs de saída.

## O que avaliar antes de integrar

- O fork não inicia contêineres nem cria endpoints no nosso backend.
- Antes de operar o serviço, avaliar isolamento, autenticação, limites de arquivos e tempo, acesso a URLs e retenção de documentos.
- Validar fontes, acentos, quebras de página e fidelidade do conteúdo; considerar licenças dos componentes distribuídos com a imagem.

## Estado e próximos passos

O fork é uma referência para estudo e documentação. Nenhum pacote, skill, serviço ou integração foi instalado em nossos aplicativos nesta organização. A próxima etapa exige escolher o projeto-alvo, registrar requisitos e critérios de aceitação e avaliar uma prova de conceito isolada. Mudanças futuras devem preservar funcionalidades atuais e passar por revisão e testes de regressão.

## Preservação, créditos e manutenção

O código, os READMEs oficiais, avisos, licenças e históricos pertencem aos autores e colaboradores do [projeto original](https://github.com/gotenberg/gotenberg). Esta documentação própria não representa afiliação ou endosso. Consulte o [arquivo de licença original](https://github.com/gotenberg/gotenberg/blob/main/LICENSE); dependências e componentes adicionais podem ter condições próprias.

Manter este guia separado como `README-NOSSOS-PROJETOS.md`, sem substituir documentação ou licença original. Para atualizar o fork, conferir mudanças do upstream e resolver conflitos sem apagar customizações ou reescrever o histórico. Atualizar o fork não atualiza automaticamente os aplicativos.
