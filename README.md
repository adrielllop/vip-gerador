# 🎮 Gerador de Sensi VIP - MestreXit.ia

Bem-vindo ao **Gerador de Sensibilidade VIP** para Free Fire! Uma solução profissional e segura para gerar configurações personalizadas de sensibilidade.

## 📋 Características

✨ **Autenticação por Key**
- Tela de login com validação em tempo real
- Integração com Firebase Realtime Database
- Status de verificação: Válida, Inválida, Pausada, Expirada

🎨 **Interface Premium**
- Design futurista e responsivo
- Animações suaves e intuitivas
- Logo personalizada como fundo

⚙️ **Gerador Avançado**
- Sliders para sensibilidade horizontal
- Sliders para sensibilidade vertical
- Controle de velocidade de mira
- Download de configuração em arquivo TXT

🔐 **Segurança**
- Armazenamento seguro de keys
- Validação em tempo real
- Sessão persistente com localStorage

## 🚀 Como Usar

### 1. Instalação
Extraia os arquivos do ZIP em uma pasta de sua escolha.

### 2. Abrir no Navegador
Abra o arquivo `index.html` em seu navegador web (Chrome, Firefox, Edge, Safari).

### 3. Autenticação
- Insira sua Key de Acesso na tela de login
- Aguarde a verificação (a barra de carregamento aparecerá)
- Se válida, você será redirecionado automaticamente

### 4. Usar o Gerador
- Acesse a aba "Gerador"
- Ajuste os sliders para sua sensibilidade preferida
- Visualize a configuração em tempo real
- Clique em "Baixar Configuração" para salvar

## 📁 Estrutura de Arquivos

```
gerador-sensi-vip/
├── index.html          # Arquivo principal (HTML + CSS + JS)
├── logo.png            # Logo personalizada
├── README.md           # Este arquivo
└── styles.css          # CSS complementar (opcional)
```

## 🔧 Configuração Firebase

O gerador utiliza Firebase Realtime Database para validar as keys. A configuração está incluída no `index.html`.

**Dados necessários no Firebase:**
```
keys/
  ├── KEY1234/
  │   ├── status: "active" | "paused" | "expired"
  │   ├── category: "bronze" | "silver" | "gold"
  │   └── created: timestamp
```

## 🎯 Funcionalidades da Tela de Key

| Status | Descrição |
|--------|-----------|
| ✅ Válida | Key ativa e pronta para uso |
| ❌ Inválida | Key não encontrada no banco |
| ⏸️ Pausada | Key pausada pelo administrador |
| ⏱️ Expirada | Key expirou e não é mais válida |

## 📊 Configurações de Sensibilidade

O gerador permite ajustar:

- **Sensibilidade Horizontal**: 1-100%
- **Sensibilidade Vertical**: 1-100%
- **Velocidade de Mira**: 1-100%

Cada configuração é salva em um arquivo `.txt` com timestamp.

## 🌐 Compatibilidade

✅ Chrome/Chromium
✅ Firefox
✅ Safari
✅ Edge
✅ Mobile (iOS/Android)

## 🔐 Segurança

- Keys são validadas em tempo real
- Dados armazenados localmente com localStorage
- Sem armazenamento de senhas
- Integração segura com Firebase

## 📞 Suporte

Para problemas ou dúvidas, entre em contato com o administrador.

## 📝 Licença

Todos os direitos reservados © MestreXit.ia VIP

---

**Versão**: 1.0.0
**Última atualização**: 2026
**Desenvolvido por**: MestreXit.ia Team
