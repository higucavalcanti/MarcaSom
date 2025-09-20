# MarcaSom - Encontre Músicos para seu Evento

O MarcaSom é um aplicativo móvel desenvolvido como projeto acadêmico para a disciplina de "Dispositivos Móveis". A plataforma conecta clientes a artistas e bandas, facilitando a busca, o agendamento e a contratação de músicos para diversos tipos de eventos.

O aplicativo foi construído com o framework **Flutter** e a linguagem **Dart**, resultando em uma aplicação multiplataforma com uma única base de código para Android e iOS.

## ✨ Principais Funcionalidades

O MarcaSom oferece um ecossistema completo para clientes e artistas, incluindo:

* **🎤 Perfis de Artista:** Cada artista pode criar um perfil detalhado, incluindo nome, gênero musical, avaliação e agenda de disponibilidade.
* **🔍 Busca e Filtro Inteligente:** Os clientes podem buscar por artistas utilizando filtros por nome, gênero musical, localização e data disponível, facilitando encontrar o som perfeito para seu evento.
* **🗓️ Sistema de Agendamento:** Funcionalidade completa para que os clientes possam solicitar e confirmar reservas diretamente com os artistas através de um calendário interativo.
* **👤 Perfis de Usuário:** Sistema de cadastro e login para clientes e artistas, permitindo o gerenciamento de informações pessoais.
* **📅 Gerenciamento de Reservas:** Uma área para os usuários visualizarem suas reservas ativas e também um histórico de reservas arquivadas.
* **🎨 Interface Intuitiva:** O design do aplicativo foi pensado para ser amigável e de fácil navegação, com componentes visuais claros e uma identidade visual bem definida.

## 🚀 Tecnologias Utilizadas

* **Framework:** [Flutter](https://flutter.dev/)
* **Linguagem:** [Dart](https://dart.dev/)
* **Gerenciamento de Pacotes:** [Pub](https://pub.dev/)
* **Ícones:** [Flutter SVG](https://pub.dev/packages/flutter_svg) e [Font Awesome Flutter](https://pub.dev/packages/font_awesome_flutter)

## ⚙️ Estrutura do Projeto

O código-fonte está organizado de forma modular para facilitar a manutenção e escalabilidade:

* `lib/main.dart`: Ponto de entrada principal da aplicação.
* `lib/screens/`: Contém todas as telas (telas) da aplicação, como login, cadastro, busca, perfil do artista, etc.
* `lib/widgets/`: Armazena os componentes reutilizáveis da interface, como a barra de navegação, cards de reserva e filtros.
* `assets/`: Diretório com todos os recursos visuais da aplicação, incluindo ícones SVG e imagens.
* `pubspec.yaml`: Arquivo de configuração do projeto, onde são declaradas as dependências e os assets.

## 🛠️ Como Executar o Projeto

Para executar este projeto localmente, você precisará ter o [Flutter SDK](https://flutter.dev/docs/get-started/install) instalado em sua máquina.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/MarcaSom.git](https://github.com/seu-usuario/MarcaSom.git)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd MarcaSom
    ```

3.  **Instale as dependências:**
    ```bash
    flutter pub get
    ```

4.  **Execute o aplicativo:**
    ```bash
    flutter run
    ```

O aplicativo será compilado e executado em um emulador ou dispositivo conectado.

---
**Desenvolvido como projeto para a disciplina de Dispositivos Móveis.**
