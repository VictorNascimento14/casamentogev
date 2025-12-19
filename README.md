# 💍 Casamento G&V

Uma aplicação web moderna e elegante para celebrar e compartilhar todos os detalhes do casamento de Graziella e Victor.

## ✨ Demonstração

![Screenshot Principal](casamento.png)

## 🎯 Sobre o Projeto

Este site foi desenvolvido para proporcionar aos convidados uma experiência única e interativa, centralizando todas as informações importantes do casamento em um único lugar. Com um design moderno e responsivo, os visitantes podem confirmar presença, acessar a lista de presentes e obter todas as informações sobre a cerimônia.

### 🌟 Funcionalidades

- 📱 **Design Responsivo** - Interface otimizada para todos os dispositivos
- 💌 **Confirmação de Presença** - Sistema de RSVP integrado
- 🎁 **Lista de Presentes** - Visualização e seleção de presentes
- 📍 **Localização** - Informações e mapas dos locais do evento
- 📅 **Cronograma** - Horários detalhados da cerimônia e festa
- 📸 **Galeria** - Fotos do casal e momentos especiais
- 🎨 **Interface Moderna** - Design elegante com animações suaves

## 🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias:

- **[React](https://reactjs.org/)** - Biblioteca JavaScript para construção de interfaces
- **[TypeScript](https://www.typescriptlang.org/)** - Superset JavaScript com tipagem estática
- **[Vite](https://vitejs.dev/)** - Build tool moderna e rápida
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitário
- **[shadcn/ui](https://ui.shadcn.com/)** - Componentes de UI reutilizáveis e estilizados

## 📦 Instalação

### Pré-requisitos

Certifique-se de ter o Node.js instalado em sua máquina. Recomendamos usar o [nvm](https://github.com/nvm-sh/nvm) para gerenciar versões do Node.js.

### Passo a passo

1. **Clone o repositório**
```bash
git clone https://github.com/VictorNascimento14/casamentogev.git
```

2. **Navegue até o diretório do projeto**
```bash
cd casamentogev
```

3. **Instale as dependências**
```bash
npm install
# ou
bun install
```

4. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
# ou
bun dev
```

5. **Acesse a aplicação**
Abra seu navegador e acesse `http://localhost:5173`

## 🛠️ Scripts Disponíveis

```bash
# Inicia o servidor de desenvolvimento
npm run dev

# Cria a build de produção
npm run build

# Visualiza a build de produção localmente
npm run preview

# Executa o linter
npm run lint
```

## 📁 Estrutura do Projeto

```
casamentogev/
├── public/              # Arquivos estáticos
├── src/
│   ├── components/      # Componentes React reutilizáveis
│   ├── pages/          # Páginas da aplicação
│   ├── styles/         # Estilos globais
│   ├── utils/          # Funções utilitárias
│   ├── App.tsx         # Componente principal
│   └── main.tsx        # Ponto de entrada da aplicação
├── index.html
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```

## 🎨 Personalização

Para personalizar o projeto para o seu próprio casamento:

1. **Cores e Tema**: Edite o arquivo `tailwind.config.ts`
2. **Conteúdo**: Atualize os textos nos componentes da pasta `src/components/`
3. **Imagens**: Substitua as imagens na pasta `public/`
4. **Informações**: Modifique os dados do evento nos arquivos de configuração

## 🌐 Deploy

Este projeto pode ser facilmente deployado em diversas plataformas:

### Lovable (Recomendado)
1. Acesse [Lovable](https://lovable.dev/projects/4dab50b8-6c7f-41e9-aa64-56ab823b4093)
2. Clique em Share -> Publish

### Netlify
```bash
npm run build
# Faça upload da pasta 'dist' no Netlify
```

### Vercel
```bash
npm run build
# Deploy usando o Vercel CLI ou interface web
```

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Se você tem alguma sugestão para melhorar este projeto:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Autores

**Victor Nascimento**
- GitHub: [@VictorNascimento14](https://github.com/VictorNascimento14)

## 💝 Agradecimentos

- À comunidade React e suas incríveis ferramentas
- Aos designers e desenvolvedores que inspiram com seus trabalhos
- A todos que contribuíram com sugestões e feedback

---

<div align="center">
  Feito com ❤️ para celebrar um amor especial
  <br/>
  <strong>Geovana & Victor</strong>
</div>
