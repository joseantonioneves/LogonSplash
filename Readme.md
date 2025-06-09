# LogonSplash

Contém um projeto Windows Forms em C# chamado **LogonSplash**. O objetivo do projeto é criar uma janela de logon (tela de autenticação) com um splash visual, provavelmente para uso em aplicações desktop no Windows.

## Estrutura do Projeto

- **Logon.cs / Logon.Designer.cs**: Implementam o formulário principal de logon (frm_Logon), incluindo o design visual e a lógica de inicialização.
- **Program.cs**: Ponto de entrada da aplicação, inicializa e exibe o formulário de logon.
- **Properties/**: Contém recursos do projeto, como strings, imagens e configurações (Properties/Resources.resx, Properties/Settings.settings).
- **icone/**: Pasta com ícones utilizados na aplicação.
- **App.config**: Arquivo de configuração da aplicação.
- **LogonSplash.csproj**: Arquivo de projeto do Visual Studio.

## Como Instalar

1. **Pré-requisitos**:
   - Visual Studio (recomendado 2019 ou superior)
   - .NET Framework 4.x (compatível com Windows Forms)

2. **Abrir o Projeto**:
   - Abra o Visual Studio.
   - Selecione "Abrir Projeto/Solução" e escolha o arquivo LogonSplash.sln.

3. **Restaurar Dependências**:
   - O projeto usa apenas bibliotecas padrão do .NET Framework, então não há dependências externas a restaurar.

4. **Compilar**:
   - No Visual Studio, pressione `Ctrl+Shift+B` ou clique em "Compilar Solução".

## Como Operar

1. **Executar**:
   - Pressione `F5` ou clique em "Iniciar Depuração" no Visual Studio.
   - A aplicação abrirá a janela de logon (frm_Logon).

2. **Funcionalidade**:
   - A janela de logon é fixa, com ícone personalizado e título "LogonSplash".
   - O evento de carregamento (`Form1_Load`) está definido, mas atualmente não possui lógica implementada.
   - O formulário pode ser customizado para adicionar campos de usuário/senha e lógica de autenticação conforme necessário.

## Observações

- O projeto é um template básico de tela de logon, pronto para ser expandido.
- Para personalizar, edite o formulário em Logon.cs e Logon.Designer.cs.
- Recursos visuais (ícones, imagens) podem ser alterados na pasta icone.

Se precisar de detalhes sobre como adicionar autenticação ou customizar a interface, posso ajudar!