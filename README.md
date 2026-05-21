# Agrupador de Planilhas — Windows

Aplicação que consolida vários arquivos `.xlsx` de uma pasta em uma única planilha, identificando colunas equivalentes mesmo com pequenas variações de digitação. Roda 100% local, sem necessidade de internet após a instalação. A interface é aberta no navegador padrão da máquina.

---

## 📦 Downloads

Há duas versões disponíveis. Escolha a que melhor se encaixa no seu perfil:

### ✅ Versão Portátil (recomendada para a maioria dos usuários)
**`agrupador-windows.zip`**

- Não requer instalação de Python
- Basta extrair o zip e dar duplo-clique em `iniciar.bat`
- Pronto para usar em ~5 segundos

### 🛠️ Versão Manual (para usuários avançados)
**`agrupador-windows-manual.zip`**

- Requer Python 3.12 instalado separadamente
- Instalação via `pip` em ambiente virtual isolado
- Indicada para quem já usa Python ou precisa de mais controle sobre o ambiente

---

## 🖥️ Requisitos

| | Versão Portátil | Versão Manual |
|---|---|---|
| Windows | 10 ou superior (64 bits) | 10 ou superior (64 bits) |
| Python | **Não precisa** (incluso no zip) | 3.12 instalado separadamente |
| Internet | Não precisa após extração | Não precisa após instalação |

---

## 🚀 Como usar (Versão Portátil)

1. Baixe e extraia `agrupador-windows.zip` em qualquer pasta
2. Dê duplo-clique em `iniciar.bat`
3. Aguarde o navegador abrir automaticamente (~5 segundos)
4. Para fechar: feche a aba do navegador **e** a janela preta do terminal

---

## 🚀 Como usar (Versão Manual)

Consulte o arquivo `LEIA-ME.txt` incluído no zip para o passo a passo completo de instalação e uso.

---

## ⚙️ Funcionalidades

- Seleciona uma pasta com múltiplos arquivos `.xlsx` e consolida tudo em um único arquivo
- Identifica colunas equivalentes com variações de digitação (correspondência aproximada)
- Filtra linhas por regras configuráveis (manter ou excluir por coluna e palavras-chave)
- Salva configurações como presets para reutilização
- Permite renomear colunas, definir abas e ajustar o limiar de similaridade

---

## ❓ Problemas comuns

**O `iniciar.bat` piscou e fechou (Versão Portátil)**
Certifique-se de que extraiu o zip completo antes de executar. Não rode de dentro do arquivo zip. A pasta `python` precisa estar no mesmo nível do `iniciar.bat`.

**O antivírus reclamou do `.bat`**
O Windows às vezes desconfia de arquivos `.bat`. Clique em "Mais informações" → "Executar assim mesmo".

**Versão Manual: `python` não é reconhecido como comando**
O Python foi instalado sem marcar "Add to PATH". Desinstale e reinstale marcando essa opção.
