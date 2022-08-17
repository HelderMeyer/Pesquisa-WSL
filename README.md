# **O que é o WSL?**


<div align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O Subsistema do Windows para Linux (do inglês Windows Subsystem for Linux ou também conhecido pela abreviação WSL) é um módulo de sistemas operacionais que visa disponibilizar um ambiente Linux compatível com o sistema da Microsoft, permitindo que os desenvolvedores executem o GNU (Sistema operacional do tipo Unix cuja finalidade é oferecer um sistema operacional completo e de software livre)/Linux, no sistema operacional Windows, que incluem a maioria das ferramentas de linha de comando, utilitários e aplicativos, diretamente no Windows, sem modificações e sem a sobrecarga de uma máquina virtual tradicional ou instalação dual boot (nome dado à instalação de dois sistemas operacionais na mesma máquina).
</div>

# **O que é o WSL 2?**

<div align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O WSL 2 é uma nova versão do Subsistema do Windows para Linux, na qual capacita o WSL a executar binários ELF64 Linux (ELF, também chamado de Extensible Linking Format, em português Formato Executável e de Ligação, é um padrão comum de arquivo para executáveis, código objeto, bibliotecas compartilhadas, e core dumps) no Windows. Os objetivos principais são aumentar o desempenho do sistema de arquivos e melhorar a compatibilidade com a solicitação do sistema. Além disso, o WSL 2 fornece a mesma experiência de usuário do WSL 1.
</div>

# **Comandos básicos para o WSL**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os comandos do WSL a seguir são listados em um formato compatível com o Prompt de Comando do Windows ou PowerShell:

#### Instalar (Instalar o WSL e a distribuição Ubuntu do Linux):
  
`
wsl --install
`  

#### Instalar uma distribuição do Linux específica:

`
wsl --install --distribution <nome_da_distribuição>
`  

#### Listar as distribuições do Linux disponíveis:

`
wsl --list --online
`

#### Listar distribuições do Linux instaladas:

`
wsl --list --verbose
`

#### Definir versão do WSL como 1 ou 2:
  
`
wsl --set-version <distribution name> <versionNumber>
`

#### Atualizar o WSL:

`
wsl --update
` 

#### Verificar o status do WSL:
  
`
wsl --status
`

#### Comando Help (serão listadas opções e comandos disponíveis com o WSL):
  
`
wsl --help
`
<br>
> #### **Referências:** [Microsoft WSL](https://docs.microsoft.com/pt-br/windows/wsl/about#what-is-wsl-2)

