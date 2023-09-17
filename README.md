# API de Geração Automática de Descrições e Títulos de Vídeos

Esta é uma API Node.js desenvolvida para automatizar a geração de descrições e títulos para vídeos. Ela utiliza algoritmos de Inteligência Artificial (IA) para criar conteúdo textual de alta qualidade, economizando tempo e esforço para criadores de conteúdo.

## Como Funciona

A API opera da seguinte forma:

1. **Upload de Vídeo:** Os usuários fazem o upload de seus vídeos para a API.

2. Conversao do video em audio

3. **Processamento de IA:** A IA analisa o conteúdo do audio, identificando temas, palavras-chave e outros elementos relevantes.

4. **Geração de Conteúdo:** Com base na análise, a IA cria automaticamente descrições atraentes e títulos sugestivos para o vídeo.

5. **Resultado Personalizável:** Os usuários têm a opção de revisar e personalizar as descrições e títulos gerados ou usar o conteúdo gerado sem modificações.

6. **Download ou Integração:** Após a geração de conteúdo, os usuários podem fazer o download das descrições e títulos ou integrá-los diretamente em suas plataformas de compartilhamento de vídeos.

## Tecnologias Utilizadas

- Node.js: Plataforma de desenvolvimento para o servidor.
- TypeScript.
- Express.js: Framework web para construir a API.
- Bibliotecas de IA (OpenAI): Utilizadas para análise de vídeo e geração de texto.
- SQLite: Banco de dados utilizado para armazenar informações sobre os vídeos e os conteúdos gerados.

## Configuração e Uso

1. **Clone o Repositório:**

git clone https://github.com/LuizHpCaldas/upload-ai-api

markdown


2. **Instale as Dependências:**

npm install

markdown


3. **Configure as Variáveis de Ambiente:**

Crie um arquivo `.env` na raiz do projeto e configure as variáveis de ambiente necessárias, como credenciais de IA e configurações de banco de dados.

4. **Inicie o Servidor:**

npm start

markdown


5. **Uso da API:**

Acesse a API através de endpoints como `/upload`, `/gerar-descricao` e `/gerar-titulo`. Consulte a documentação da API para obter detalhes sobre como utilizar cada recurso.

## Documentação da API

A documentação completa da API, incluindo exemplos de solicitações e respostas, pode ser encontrada em [LINK_PARA_DOCUMENTACAO](https://link-para-documentacao-api.com).

## Contribuição

Contribuições são bem-vindas! Se você deseja contribuir para este projeto, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma branch para sua contribuição: `git checkout -b minha-contribuicao`.
3. Faça suas modificações e adicione novos recursos.
4. Certifique-se de que os testes passam: `npm test`.
5. Envie suas mudanças: `git push origin minha-contribuicao`.
6. Crie um pull request explicando suas alterações.

## Licença

Este projeto está sob a licença [MIT](LICENSE.md).

---
