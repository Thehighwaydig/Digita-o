# THE Highway - Treino de Digitação Premium

Um site moderno e responsivo para treino de digitação focado em praticar separadamente as fileiras do teclado. Desenvolvido com **HTML, CSS e JavaScript puro** (vanilla) com design **Cyberpunk Minimalista**.

## 🎯 Objetivo

O site oferece treinos específicos para cada fileira do teclado (central, superior e inferior), com foco em repetição inteligente, feedback visual em tempo real e progresso mensurável. Ideal para desenvolver memória muscular e aumentar velocidade de digitação com precisão profissional.

## ✨ Características Principais

### Treinos por Fileira
- **Fileira Central (Home Row)**: Base de toda digitação rápida - posição de repouso dos dedos
- **Fileira Superior (Top Row)**: Pratique alcançando para cima mantendo a posição base
- **Fileira Inferior (Bottom Row)**: Desenvolva memória muscular para as teclas inferiores

### Modos de Treino
- **Caracteres**: Sequências aleatórias de caracteres para treino básico
- **Palavras**: Palavras reais para contexto prático de digitação
- **Cronometrado**: Desafios com limite de tempo

### Níveis de Dificuldade
- **Fácil**: 20 caracteres - perfeito para iniciantes
- **Médio**: 50 caracteres - intermediário
- **Difícil**: 100 caracteres - avançado

### Estatísticas em Tempo Real
- **WPM (Palavras por Minuto)**: Velocidade de digitação
- **Precisão (%)**: Porcentagem de acertos
- **Erros**: Contagem de caracteres digitados incorretamente
- **Tempo**: Duração da sessão

### Teclado Virtual Interativo
- Visualização em tempo real das teclas sendo pressionadas
- Guia de posicionamento de dedos com código de cores
- Indicador de próxima tecla a digitar
- Feedback visual de acertos e erros

### Sistema de Progresso
- Rastreamento de sessões completadas
- Melhor WPM alcançado
- Precisão média
- Sequência de dias de treino
- Sistema de conquistas (achievements)

### Design Premium
- Tema escuro (Cyberpunk Minimalista) com cores vibrantes (roxo/laranja)
- Tema claro alternativo para preferência do usuário
- Efeitos visuais neon e glitch sutis
- Animações fluidas e responsivas
- Interface totalmente responsiva (desktop, tablet, mobile)

### Experiência Interativa
- Feedback sonoro opcional para acertos/erros
- Transições suaves entre abas
- Componentes bem espaçados e organizados
- Tipografia confortável e legível

## 🚀 Como Executar

### Opção 1: Abrir Diretamente no Navegador (Recomendado)

1. **Extraia o arquivo ZIP do projeto**
   ```bash
   unzip the-highway.zip
   cd the-highway
   ```

2. **Abra o arquivo `index.html` no navegador**
   - Clique duas vezes em `index.html`, ou
   - Arraste `index.html` para o navegador, ou
   - Clique com botão direito em `index.html` → "Abrir com" → Escolha seu navegador

3. **Pronto!** O site está funcionando

### Opção 2: Usar um Servidor Local (Melhor Performance)

Se você tem Python instalado:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Depois acesse: `http://localhost:8000`

Se você tem Node.js instalado:

```bash
# Instale http-server globalmente
npm install -g http-server

# Inicie o servidor
http-server

# Acesse em http://localhost:8080
```

## 📁 Estrutura do Projeto

```
the-highway/
├── index.html           # Arquivo HTML principal
├── css/
│   └── styles.css       # Estilos Cyberpunk Minimalista
├── js/
│   └── app.js           # Lógica da aplicação
├── assets/
│   └── logo.png         # Logo THE Highway
└── README.md            # Este arquivo
```

## 🎨 Design System

### Paleta de Cores (Cyberpunk Minimalista)
- **Fundo**: Preto profundo (#0a0e27)
- **Primário**: Laranja vibrante (#ff6b35)
- **Secundário**: Roxo elétrico (#7c3aed)
- **Acentos**: Ciano (#06b6d4)
- **Erros**: Vermelho (#ef4444)

### Tipografia
- **Títulos**: Space Mono (bold, 700)
- **Corpo**: Inter (regular, 400)
- **Números**: JetBrains Mono (monospace)

### Animações
- Duração padrão: 150-250ms
- Easing: cubic-bezier(0.23, 1, 0.32, 1) para entrada
- Efeitos: glow, pulse, glitch, scan

## 💡 Dicas de Uso

### Para Iniciantes
1. Comece com a **Fileira Central** em dificuldade **Fácil**
2. Foque em **precisão** antes de velocidade
3. Pratique **30 minutos por dia** regularmente
4. Use o **teclado virtual** como guia

### Metas de Digitação
- **Iniciante**: 20-40 WPM
- **Intermediário**: 40-60 WPM
- **Avançado**: 60-100 WPM
- **Profissional**: 100+ WPM

### Boas Práticas
- Mantenha os dedos na **posição correta** (Home Row)
- **Não olhe para o teclado** durante o treino
- Aumente a dificuldade **gradualmente**
- Pratique todas as fileiras para **desenvolvimento completo**

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos e animações
- **JavaScript Vanilla**: Lógica e interatividade
- **Google Fonts**: Tipografia (Space Mono, Inter, JetBrains Mono)

## 📊 Funcionalidades Técnicas

### Performance
- Sem dependências externas (100% vanilla)
- Carregamento instantâneo
- Otimizado para todos os navegadores modernos

### Acessibilidade
- Suporte a teclado completo
- Contraste de cores adequado
- Feedback visual claro
- Estrutura semântica HTML

### Responsividade
- Mobile-first design
- Breakpoints: 480px, 768px
- Touch-friendly em dispositivos móveis
- Testes em múltiplos tamanhos de tela

## 🎮 Como Começar a Treinar

1. **Selecione a Fileira**: Escolha entre Central, Superior ou Inferior
2. **Escolha o Modo**: Caracteres, Palavras ou Cronometrado
3. **Defina a Dificuldade**: Fácil, Médio ou Difícil
4. **Comece a Digitar**: Clique no campo de entrada e comece
5. **Acompanhe o Progresso**: Veja WPM, precisão e erros em tempo real
6. **Consulte o Teclado Virtual**: Use como guia de posicionamento de dedos

## 🏆 Sistema de Conquistas

Desbloqueie conquistas conforme você progride:
- 🚀 **Primeiro Passo**: Complete sua primeira sessão
- ⚡ **Velocista**: Atinja 60 WPM
- 🎯 **Mestre da Precisão**: Mantenha 95% de precisão
- 🔥 **Consistente**: Mantenha uma sequência de 7 dias
- 🏃 **Maratonista**: Complete 50 sessões
- 👑 **Lenda**: Atinja 100 WPM

## 💾 Armazenamento de Dados

O progresso é salvo automaticamente no **localStorage** do navegador:
- Sessões completadas
- Melhor WPM
- Precisão média
- Preferência de tema

Os dados persistem mesmo após fechar o navegador.

## 🐛 Troubleshooting

### O site não carrega
- Certifique-se de que todos os arquivos estão na mesma pasta
- Verifique se a pasta `assets/` contém `logo.png`
- Tente abrir em outro navegador

### Sons não funcionam
- Verifique as permissões de áudio do navegador
- Alguns navegadores bloqueiam áudio até interação do usuário
- Desative sons nas configurações se necessário

### Progresso não está sendo salvo
- Verifique se o localStorage está habilitado
- Tente limpar o cache do navegador
- Use um navegador diferente

## 📱 Compatibilidade

- ✅ Chrome/Chromium (recomendado)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera
- ✅ Navegadores móveis

## 📝 Licença

Este projeto é fornecido como está para uso pessoal e educacional.

## 🤝 Suporte

Para problemas ou sugestões, consulte a documentação do projeto.

---

**THE Highway © 2026** - Treino de Digitação Premium  
*Desenvolvido para ajudar você a dominar o teclado*

### Versão
- **Versão**: 1.0.0
- **Tipo**: HTML/CSS/JavaScript Vanilla
- **Data**: Maio 2026
