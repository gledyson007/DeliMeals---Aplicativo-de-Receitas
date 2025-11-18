# 🍽️ DeliMeals - Aplicativo de Receitas

> Aplicativo mobile de receitas culinárias desenvolvido com Flutter

## 📋 Sobre

DeliMeals é um aplicativo completo para exploração de receitas culinárias, oferecendo uma experiência intuitiva e moderna. Desenvolvido como projeto do curso de Flutter na Udemy, demonstra conceitos fundamentais do framework como navegação, gerenciamento de estado e widgets customizados.

---

## ⚡ Funcionalidades

- **📂 Categorias**: Explore 10+ categorias (Italiana, Asiática, Francesa, Hamburgers, etc.)
- **⭐ Favoritos**: Salve e acesse rapidamente suas receitas preferidas
- **🔍 Filtros**: Personalize por Sem Glúten, Sem Lactose, Vegano ou Vegetariano
- **📖 Detalhes**: Ingredientes, modo de preparo passo a passo, tempo, complexidade e custo
- **🎨 Interface Moderna**: Design clean com gradientes, animações e navegação fluida

---

## 🛠️ Tecnologias

- **Flutter** 3.9.2 - Framework multiplataforma
- **Dart** 3.9.2 - Linguagem de programação
- **Material Design** - Sistema de design
- **Fontes**: Raleway e Roboto Condensed

---

## 📱 Estrutura do Projeto

```
lib/
├── main.dart                           # Entrada e configuração
├── components/                         # Widgets reutilizáveis
│   ├── category_item.dart
│   ├── main_drawer.dart
│   └── meal_item.dart
├── data/
│   └── dummy_data.dart                # Dados mockados
├── models/                            # Modelos de dados
│   ├── category.dart
│   ├── meal.dart
│   └── settings.dart
├── screens/                           # Telas
│   ├── categories_screen.dart
│   ├── categories_meals_screen.dart
│   ├── meal_detail_screen.dart
│   ├── favorite_screen.dart
│   ├── settings_screen.dart
│   └── tabs_screens.dart
└── utils/
    └── app_routes.dart               # Rotas nomeadas
```

---

## 🎯 Conceitos Flutter Aplicados

**Navegação**
- Rotas nomeadas, passagem de argumentos, Bottom Navigation, Drawer

**Widgets**
- GridView, ListView.builder, Stack, Container, Card, InkWell, FloatingActionButton

**Estado**
- StatefulWidget, setState(), Lifting State Up, Callbacks

**Estilização**
- ThemeData customizado, fontes personalizadas, gradientes

---

## 🚀 Como Executar

### Pré-requisitos
- Flutter SDK 3.9.2+
- Dart SDK 3.9.2+
- VS Code ou Android Studio
- Emulador ou dispositivo físico

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/meals.git
cd meals

# Instale as dependências
flutter pub get

# Execute
flutter run
```

### Comandos Úteis

```bash
flutter doctor                    # Verificar instalação
flutter clean                     # Limpar cache
flutter build apk --release       # Build Android
flutter build ios --release       # Build iOS
```

---

## 📚 Aprendizados

- Arquitetura e organização de projetos Flutter
- Navegação complexa com múltiplas telas
- Gerenciamento de estado em aplicações reais
- Componentes reutilizáveis e boas práticas
- Customização de temas e estilos

---

## 🔮 Melhorias Futuras

- [ ] Persistência local (SQLite/Hive)
- [ ] Integração com Firebase
- [ ] Busca por nome/ingrediente
- [ ] Adicionar receitas personalizadas
- [ ] Compartilhamento social
- [ ] Lista de compras automática
- [ ] Timer de cozinha
- [ ] Modo escuro
- [ ] Suporte multilíngue (i18n)
- [ ] Testes automatizados

---

## 👨‍💻 Autor

Desenvolvido com ❤️ e ☕ durante o curso de Flutter na Udemy.

## 📄 Licença

MIT License - Open Source

---

<div align="center">
  <p>Feito com Flutter 💙</p>
  <p>⭐ Deixe uma estrela se gostou do projeto!</p>
</div>
