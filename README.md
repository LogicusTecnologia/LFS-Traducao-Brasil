# LFS-Traducao-Brasil


Criado por Gerard Beekmans

Editador por Bruce Dubbs

Traduzido por Logicus Tecnologia e Satus Tecnologia

Copyright © 1999-2016 Gerard Beekmans


## Tabela de conteúdos

### Prefácio

Público

LFS e arquiteturas do alvo

LFS e padrões

Pacotes utilizados neste livro

Pré-requisitos

Requisitos do sistema anfitrião

Tipografia

Estrutura

Errata


### I. Introdução

Introdução

Como criar um sistema LFS

O que há de novo nesta versão

Changelog

Recursos

Ajuda

### II. Preparando-se para a Compilação

#### Preparando a nova Partição

Introdução

Criando a nova Partição

Criando o sistema de arquivos para a partição

Setando a Variavel $LFS

Montando a nova partição

#### Pacotes e "Patches"(Remendos)

Introdução

Todos os Pacotes

"Patches"(Remendos) Nessesários

#### Preparativos Finais

Introdução

Criando o Diretório $LFS/tools

Adicionando o usuário LFS

Configuração de Ambiente

Sobre SBU`s

Sobre conjuntos de testes

#### Construindo o Sistema Temporário

Introdução

Nota Tecnica da Pasta de Construção

Instrução Geral de Compilação

Binutils-2.26 - Passo 1 

GCC-5.3.0 - Passo 1

Linux-4.4.2 API Headers

Glibc-2.23

Libstdc++-5.3.0

Binutils-2.26 - Passo 2

Gcc-5.3.0 - Passo 2

Tcl-core-8.6.4

Expect-5.45

DejaGNU-1.5.3

Check-0.10.0

Ncurses-6.0

Bash-4.3.30

Bzip2-1.0.6

Coreutils-8.25

Diffutils-3.3

File-5.25

Findutils-4.6.0

Gawk-4.1.3

Gettext-0.19.7

Grep-2.23

Gzip-1.6

M4-1.4.17

Make-4.1

Patch-2.7.5

Perl-5.22.1

Sed-4.2.2

Tar-1.28

Texinfo-6.1

Util-linux-2.27.1

Xz-5.22

Limpeza

Alterando a Propriedade

### III. Construindo o Sistema LFS

#### Instalando os Programas Basico do Sistemas

Introdução 

Preparando o Núcleo Virtual do Sistema de Arquivos

Gerenciador de Pacotes

Entrando no Ambiente de Jaula

Criando Diretórios

Criando Links e Arquivos Essenciais

Linux-4.4.2 API Header

Man-Pages-4.04

Glibc-2.23

Ajustando a Pasta de Contrução

Zlib-1.2.8

File-5.25

Binutils-2.26

GMP-6.1.0

MPFR-3.1.3

MPC-1.0.3

GCC-5.3.0

Bzip2-1.0.6

Pkg-config-0.29

Ncurses-6.0

Attr-2.4.47

Acl-2.2.52

Libcap-2.25

Sed-4.2.2

Shadow-4.2.1

Psmisc-22.21

Iana-Etc-2.30

M4-1.4.17

Bison-3.0.4

Flex-2.6.0

Grep-2.23

Readline-6.3

Bash-4.3.30

Bc-1.06.95

Libtool-2.4.6

GDBM-1.11

Gperf-3.0.4

Expat-2.1.0

Intutils-1.9.4

Perl-5.22.1

Xml::Parser-2.44

Intltool-0.51.0

Autoconf-2.69

Automake-1.15

Xz-5.2.2

Kmod-22

Gettext-0.19.7

Systemd-229

Procps-ng-3.3.11

E2fsprogs-1.42.13

Coreutils-8.25

Diffutils-3.3

Gawk-4.1.3

Findutils-4.6.0

Groff-1.22.3

GRUB-2.02~beta2

Less-481

Gzip-1.6

IPRoute2-4.4.0

Kbd-2.0.3

Libpipeline-1.4.1

Make-4.1

Patch-2.7.5

D-Bus-1.10.6

Util-linux-2.27.1

Man-DB-2.7.5

Tar-1.28

Texinfo-6.1

Vim-7.4

Sobre Símbolos de Depuração

Limpeza Mais Uma Vez

Pondo em Ordem

#### Sistemas Basico de Configuração

Introdução

Configuração Geral de Rede

Dispositivos e Módulos de Manipulação do Sistemas LFS

Criando Link Simbólico Personalizado para os Dispositivos

Configurando o Relógio do Sistema

Configurando o Console do Linux

Configurando as Localidados do Sistema

Criando o Arquivo /etc/inputrc

Criando o Arquivo /etc/shells

Configurando e Usando o Systemd

#### Fazendo o Sistema LFS Inicializável

Introdução

Criando o Arquivo /etc/fstab

Linux-4.4.2

Usando o GRUB para Configurar o Processo de Inicialização

#### O Fim

O Fim

Registre-se

Reiniciando o Systema

E Agora?


### IV. Anexos

A. Siglas e Termos

B. Agradecimentos

C. Dependências

#### D. Licensas LFS

Criando Licenças Comuns

A Licença MIT

## Índice



