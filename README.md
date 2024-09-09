# One-Bus-Desenvolvimento

# One Bus

**One Bus** é um aplicativo e site que visa integrar e simplificar o acesso a informações sobre transporte público, proporcionando uma experiência mais eficiente e conveniente para os usuários. O sistema oferece informações em tempo real sobre a localização dos ônibus, suas rotas, horários e os pontos de ônibus mais próximos, centralizando tudo em uma única plataforma.

## Motivação

Atualmente, a obtenção de informações sobre ônibus e transporte público é um processo ineficiente e fragmentado. As pessoas precisam acessar múltiplos sites ou usar diferentes aplicativos para saber o horário, a rota ou a localização dos ônibus. O **One Bus** resolve esse problema ao fornecer todas essas informações de forma centralizada e em tempo real.

## Funcionalidades

- **Visualização em Tempo Real**: Veja a localização dos ônibus em tempo real e receba notificações sobre a chegada iminente do ônibus no ponto de espera.
- **Consulta de Rotas e Horários**: Consulte rotas completas, horários de partida e chegada de qualquer linha de ônibus.
- **Pontos de Ônibus Próximos**: Encontre os pontos de ônibus mais próximos e as linhas que passam por eles.
- **Notificações de Atrasos**: Receba notificações sobre atrasos ou mudanças nos horários dos ônibus.
- **Interface Intuitiva**: Navegação fácil e rápida para encontrar todas as informações necessárias sobre o transporte público.

## Tecnologias Utilizadas

- **Frontend**: React (para o site) e React Native (para o aplicativo mobile)
- **Backend**: Node.js com Express
- **Banco de Dados**: MongoDB
- **Mapas e Geolocalização**: APIs do Google Maps e OpenStreetMap
- **Outras Ferramentas**: WebSockets para atualização em tempo real, Firebase para notificações push

## Instalação

### Pré-requisitos

- **Node.js** (v14 ou superior)
- **npm** ou **yarn**
- **MongoDB** (local ou serviço na nuvem)
- **API Key** para Google Maps e/ou OpenStreetMap

### Passos para Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/one-bus.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd one-bus
    ```

3. Instale as dependências:

    ```bash
    npm install
    ```

    ou

    ```bash
    yarn install
    ```

4. Configure as variáveis de ambiente:

    Crie um arquivo `.env` na raiz do projeto e adicione suas chaves de API e configurações de banco de dados.

5. Inicie o servidor backend:

    ```bash
    npm run server
    ```

6. Inicie o frontend (site):

    ```bash
    npm start
    ```

## Uso

1. Abra o aplicativo mobile ou site.
2. Permita o acesso à sua localização para encontrar pontos de ônibus próximos.
3. Pesquise por linhas de ônibus, horários e rotas.
4. Receba notificações sobre a chegada do ônibus no seu ponto e possíveis atrasos.

## Contribuição

Sinta-se à vontade para contribuir com o **One Bus**! Você pode fazer isso de várias maneiras:

- Reportando problemas
- Sugerindo novas funcionalidades
- Enviando pull requests

### Como Contribuir

1. Fork o projeto
2. Crie um branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para o branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## Contato


Obrigado por usar o **One Bus**! Vamos tornar o transporte público mais eficiente e acessível para todos.
