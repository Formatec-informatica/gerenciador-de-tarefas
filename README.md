# Gerenciador de Tarefas

**Formatec Solução em Informática**

Um aplicativo para Windows que reúne, num só lugar, as ferramentas que o técnico usa no dia a dia: diagnóstico,
limpeza, otimização, reparo, programas, segurança e pós-formatação. Feito para técnicos e para quem gosta de
explorar as possibilidades do computador, com tudo explicado em linguagem simples e sempre com um jeito de voltar
atrás.

## Download

A versão mais recente fica na pasta [`versao`](versao):

| Arquivo | Para quê |
|---|---|
| [Instalador_Gerenciador_de_Tarefas.exe](https://raw.githubusercontent.com/Formatec-informatica/gerenciador-de-tarefas/main/versao/Instalador_Gerenciador_de_Tarefas.exe) | Instala ou atualiza o programa (recomendado) |
| [Gerenciador_de_Tarefas_Portatil.exe](https://raw.githubusercontent.com/Formatec-informatica/gerenciador-de-tarefas/main/versao/Gerenciador_de_Tarefas_Portatil.exe) | Versão portátil: um arquivo só, sem instalar (ótima para levar no pendrive) |

O SHA-256 de cada arquivo está em [`versao/SHA256SUMS.txt`](versao/SHA256SUMS.txt).

**Requisitos:** Windows 10 ou 11, 64 bits. O programa pede permissão de administrador ao abrir, porque mexe em
configurações do sistema.

## O que ele faz

**Sistema e segurança**
- 📊 **Painel de saúde** — nota de 0 a 100 para o PC, com o que corrigir em um clique.
- 💻 **Computador** — informações completas (processador, memória, discos, placa de vídeo), relatórios em imagem, Word, Excel e HTML.
- 🛠 **Manutenção** e 🚀 **Inicialização** — programas que iniciam com o Windows, com selo do que pode ser desabilitado.
- 🛡️ **Exclusões do Defender**, 🔥 **Firewall** (bloquear programas e pastas) e 🌍 **Hosts**.

**Diagnóstico**
- 📈 **Monitor de desempenho** — barra flutuante com processador, memória, disco e rede.
- 💽 **Saúde dos discos**, 🏁 **Benchmark**, 🔍 **Pendrive/SSD falsificado** e 🧩 **Drivers**.
- 🪟 **Windows 11** — confere os requisitos com as mesmas verificações do app oficial da Microsoft e instala ou atualiza com opções para pular perguntas e configurações (privacidade, conta local, região, requisitos de hardware, BitLocker), além de backup e restauração automática dos drivers.
- 🌍 **Internet e DNS** — teste de velocidade e escolha do DNS mais rápido.

**Programas**
- 📦 **Programas** — instala, atualiza e desinstala (winget), inclusive em lote.
- 🚀 **Pós-formatação** — instala de uma vez os programas do dia a dia.
- 💾 **Backup de drivers e Wi-Fi** e 🧽 **Sobras de programas**.
- 🚚 **Mover programas** — leva programas instalados para outra unidade ou pasta sem reinstalar, com opção de voltar ao local original.

**Otimizar**
- 🧹 **Limpeza**, 🗺️ **Mapa do disco** e 👯 **Arquivos duplicados**.
- ⚡ **Otimizações** do Windows com níveis Seguro, Moderado e Avançado.

**Reparar**
- 🔧 **Reparar o Windows** (SFC, DISM e outras ferramentas), 🕘 **Pontos de restauração** e ↩️ **Central de desfazer**.

## Segurança

- Antes de aplicar um ajuste, o programa guarda como ele estava: tudo pode ser desfeito na Central de desfazer.
- Cria um ponto de restauração do Windows antes de otimizações, correções e instalação de drivers.
- Nunca desliga as proteções do Windows (Defender, Firewall, UAC e SmartScreen).
- A Limpeza pula arquivos em uso; arquivos duplicados vão para a Lixeira.

## Atualização automática

Os programas instalados procuram uma versão nova ao abrir. Quando ela existe, baixam em segundo plano, conferem
o SHA-256 e instalam sozinhos assim que o programa não estiver no meio de uma tarefa. A opção pode ser desligada
em **Sobre e atualizações**.

As informações da versão ficam no arquivo [`atualizacao.json`](atualizacao.json).

## Idiomas

Português, inglês e espanhol, com tema claro ☀️ e escuro 🌙.

## Contato e suporte

- 🌐 Site: [www.formatecsinformatica.com.br](https://www.formatecsinformatica.com.br)
- 💬 WhatsApp (suporte): [(82) 99984-0942](https://wa.me/5582999840942)
- 📷 Instagram: [@formatec.si](https://www.instagram.com/formatec.si)

---

© Formatec Solução em Informática. Todos os direitos reservados.
