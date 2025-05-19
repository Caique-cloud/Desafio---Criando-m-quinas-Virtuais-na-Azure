# 💻 Desafio DIO: Criação de Máquina Virtual na Azure

Este repositório tem como objetivo documentar todo o processo de criação, configuração e gerenciamento de uma máquina virtual (VM) na plataforma **Microsoft Azure**, conforme proposto no desafio prático da DIO.

---

## 🧠 Objetivos de Aprendizagem

- Aplicar os conceitos aprendidos nas aulas práticas da DIO;
- Criar uma VM no Microsoft Azure via Portal Web;
- Documentar o passo a passo de forma clara e reutilizável;
- Utilizar o GitHub como repositório de apoio e estudo contínuo.

---

## 🛠️ Etapas Realizadas

1. **Acesso ao Portal do Azure**
   - [https://portal.azure.com](https://portal.azure.com)

2. **Criação do Grupo de Recursos**
   - Nome sugerido: `rg-desafio-azure`

3. **Criação da Máquina Virtual**
   - Nome: `vm-desafio`
   - SO: Windows 10/11 ou Windows Server (conforme preferido)
   - Tamanho: B1s (uso gratuito para testes)
   - Usuário e senha criados para acesso remoto

4. **Configuração de Rede**
   - Criação de IP público
   - Liberação da porta 3389 (RDP)

5. **Conexão com a VM**
   - Utilização do Remote Desktop (RDP)

6. **Testes Realizados**
   - Acesso remoto bem-sucedido
   - Instalação de atualizações
   - Criação de arquivos para validação da persistência

---

## 📁 Estrutura do Repositório

```
📁 desafio-azure-dio/
│
├── README.md                # Este arquivo com o resumo do projeto
├── /images                  # Capturas de tela das etapas (opcional)
│   ├── criacao-vm.png
│   ├── acesso-rdp.png
│   └── configuracao-rede.png
└── notas.md                 # Notas e dicas adicionais sobre Azure
```

---

## 📌 Dicas Importantes

- Utilize sempre o **grupo de recursos** para facilitar o gerenciamento;
- Após testar a VM, **exclua os recursos** para não gerar cobranças;
- Explore o **Azure Cost Management** para verificar consumo;
- Crie **snapshots** para backup da VM se for continuar usando.

---

## 🧾 Recursos Utilizados

- [Documentação Oficial Microsoft: Criar VM Windows](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [Guia Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
- [GitHub Quick Start](https://github.com/git-guides)

---

## ✅ Conclusão

Este repositório servirá como base de consulta para futuros projetos na nuvem usando o Microsoft Azure, consolidando o aprendizado adquirido no desafio DIO.
