# FYD Connect

Protótipo responsivo da plataforma digital da **Follow Your Dreams Idiomas**, desenvolvido em HTML, CSS e JavaScript.

## Funcionalidades

- Painel do aluno e do professor;
- Agenda de aulas e acesso ao Google Meet;
- Biblioteca de materiais;
- Progresso e feedbacks;
- Registro obrigatório do feedback do professor;
- Demonstração da sincronização com o Emusys;
- Layout responsivo para computador e celular;
- Logo oficial da Follow Your Dreams.

## Como executar

Baixe o repositório e abra o arquivo `index.html` no navegador. Também é possível usar a extensão **Live Server** no VS Code.

## GitHub Pages

O projeto funciona como demonstração no GitHub Pages. Nessa modalidade, os feedbacks ficam salvos apenas no navegador do usuário.

## Integração real com o Emusys

O token do Emusys não deve ser colocado no `script.js`. A versão em produção precisa de um backend protegido, responsável por chamar a API do Emusys sem expor as credenciais no navegador.
