# upload.ai

Bem-vindo ao repositório do front-end do projeto upload.ai! Este repositório contém o código-fonte e os recursos relacionados à interface do usuário para a aplicação upload.ai.

## Descrição

O front-end do upload.ai é desenvolvido utilizando tecnologias modernas da web, incluindo Vite, TypeScript, Tailwind CSS, ffmpeg.wasm, Vercel AI SDK, Radix UI, e Lucide. Esta interface proporciona uma experiência de usuário intuitiva e amigável para interagir com a API do servidor Node.js Upload.ai.

## Funcionalidades Principais

- **Interface Intuitiva**: Uma interface de usuário moderna e amigável que permite aos usuários navegar e interagir facilmente com o serviço.

- **Processamento Avançado de Mídias**: Utilize recursos como ffmpeg.wasm para processamento de vídeo avançado e extração de informações de mídias.

- **Integração com a API**: Conecte-se perfeitamente com a API do servidor Node.js Upload.ai para processar e exibir resultados.

- **Integração com Vercel AI SDK**: Explore as capacidades de visão computacional e aprendizado de máquina com a integração do Vercel AI SDK, possibilitando recursos avançados de análise de imagens e vídeos.

## Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado na sua máquina.

## Configuração

Siga estas etapas para configurar e executar o front-end do upload-ai em seu ambiente de desenvolvimento:

1. Clone este repositório:

   ```bash
   git clone https://github.com/pedrokarnoski/upload-ai-web.git

2. Instale as dependências necessárias com o gerenciador de pacotes de sua escolha (escolha um dos seguintes comandos):

   - Usando npm:
     ```bash
     cd upload-ai-web
     npm install
     ```

   - Usando yarn:
     ```bash
     cd upload-ai-web
     yarn
     ```

   - Usando pnpm:
     ```bash
     cd upload-ai-web
     pnpm install
     ```

Siga estas etapas para configurar as variáveis de ambiente necessárias para a integração com a API OpenAI:

1. Crie uma nova conta na [OpenAI](https://platform.openai.com/).

2. Gere uma chave de API para acessar os serviços da OpenAI no [painel de controle da API](https://platform.openai.com/account/api-keys).

3. No projeto, crie um arquivo `.env` na raiz, se ainda não existir.

4. Adicione a chave de API gerada no arquivo `.env` com o nome "OPENAI_KEY".
