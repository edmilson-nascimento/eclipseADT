# Eclipse ADT

![Static Badge](https://img.shields.io/badge/eclipse-4.35.0-2C2255?logo=eclipse&logoColor=white)
![Static Badge](https://img.shields.io/badge/eclipse%20adt-4.35.0-2C2255?logo=eclipse&logoColor=white)

![Static Badge](https://img.shields.io/badge/SAP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/ABAP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/BTP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/RAP-050002?logo=sap&logoColor=white)

[![ABAP Development Tools](https://img.shields.io/badge/ABAP_Development_Tools-2C2255?logo=eclipse&logoColor=white)](https://tools.hana.ondemand.com/)
[![ABAP Cleaner](https://img.shields.io/badge/ABAP_Cleaner-0FAAFF?logo=sap&logoColor=white)](https://github.com/SAP/abap-cleaner)
[![abapGit](https://img.shields.io/badge/abapGit-F05032?logo=git&logoColor=white)](https://github.com/larshp/abapGit)

Este repositório contém uma versão personalizada do Eclipse ADT com plugins pré-configurados para desenvolvimento ABAP. As atualizações serão realizadas de forma controlada para garantir a estabilidade do ambiente.

## Sumário

- [Download do Eclipse](#-download-do-eclipse)
- [ABAP Development Tools (ADT)](#-abap-development-tools-adt)
- [ABAP Cleaner](#-abap-cleaner)
- [abapGit Plugin](#-abapgit-plugin)
- [ABAP Quickfix S/4 Conversion](#-abap-quickfix-s4-conversion)
- [ABAP Favorites](#-abap-favorites)
- [Darkest Dark Theme (opcional)](#-darkest-dark-theme-opcional)

## ![Static Badge](https://img.shields.io/badge/Eclipse-IDE-2C2255?logo=eclipse&logoColor=white) Download do Eclipse

Antes de instalar os plugins de desenvolvimento ABAP, é necessário ter o **Eclipse IDE for Java Developers** instalado.

> [!NOTE]
> O Eclipse requer um **JDK (Java Development Kit)** instalado para funcionar. Utilize uma versão compatível com a release do Eclipse escolhida.

**Instalação:**
1. Acesse o site oficial das ferramentas SAP para Eclipse: [SAP Development Tools](https://tools.hana.ondemand.com/).
2. Baixe o **Eclipse IDE for Java Developers** na versão recomendada pela SAP (compatível com o ADT).
3. Extraia/instale o Eclipse e execute-o ao menos uma vez para concluir a configuração inicial.
4. Com o Eclipse aberto, prossiga com a instalação dos plugins abaixo.

## ![Static Badge](https://img.shields.io/badge/SAP-ADT-0FAAFF?logo=sap&logoColor=white) ABAP Development Tools (ADT)

O **ABAP Development Tools (ADT)** é uma extensão do Eclipse que fornece um ambiente moderno e eficiente para o desenvolvimento ABAP. Ele é essencial para desenvolvedores que trabalham com sistemas SAP, oferecendo uma interface intuitiva e ferramentas avançadas para codificação, depuração e gerenciamento de objetos ABAP.

**Principais benefícios:**
- Ambiente de desenvolvimento integrado (IDE) moderno e eficiente.
- Suporte para desenvolvimento em sistemas SAP S/4HANA e SAP NetWeaver.
- Ferramentas avançadas para depuração e análise de código.
- Integração com outras ferramentas, como abapGit e ABAP Cleaner.
- Melhor experiência de desenvolvimento em comparação ao SE80.

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o seguinte repositório:  
   ```
   https://tools.hana.ondemand.com/latest
   ```
3. Na lista de plugins disponíveis, selecione **ABAP Development Tools (ADT)** e clique em **Next**.
4. Siga as instruções para concluir a instalação.
5. Após a instalação, reinicie o Eclipse.

**Como usar:**
- Após a instalação, conecte-se ao sistema SAP usando a opção **File → New → ABAP Project**.
- Configure o sistema SAP e comece a desenvolver seus objetos ABAP diretamente no Eclipse.

Para mais informações, consulte o [tutorial oficial do ADT](https://developers.sap.com/tutorials/abap-install-adt.html).

## ![Static Badge](https://img.shields.io/badge/SAP-ABAP_Cleaner-0FAAFF?logo=sap&logoColor=white) ABAP Cleaner

O **ABAP Cleaner** é uma ferramenta essencial para desenvolvedores ABAP que automatiza a formatação e melhoria do código.

**Principais benefícios:**
- Formatação consistente do código ABAP
- Alinhamento automático de declarações e operações
- Remoção de espaços em branco desnecessários
- Organização de declarações de variáveis
- Melhoria na legibilidade do código
- Aplicação de boas práticas de desenvolvimento

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o seguinte repositório:  
   ```
   https://sap.github.io/abap-cleaner/updatesite
   ```
3. Na lista de plugins disponíveis, selecione **ABAP Cleaner** e clique em **Next**.
4. Siga as instruções para concluir a instalação.
5. Após a instalação, reinicie o Eclipse.

Para mais informações, visite o [repositório oficial](https://github.com/SAP/abap-cleaner).


## ![Static Badge](https://img.shields.io/badge/Git-abapGit-F05032?logo=git&logoColor=white) abapGit Plugin

O **abapGit Plugin** é uma ferramenta indispensável para desenvolvedores ABAP que permite o controle de versão de objetos ABAP diretamente no Eclipse. Ele facilita a integração com repositórios Git, promovendo uma abordagem moderna e colaborativa para o desenvolvimento ABAP.

**Principais benefícios:**
- Controle de versão para objetos ABAP
- Integração com repositórios Git (GitHub, GitLab, etc.)
- Suporte para múltiplos desenvolvedores em projetos ABAP
- Migração e transporte de objetos ABAP entre sistemas

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o seguinte repositório:  
   ```
   https://eclipse.abapgit.org/updatesite/
   ```
3. Na lista de plugins disponíveis, selecione **abapGit Plugin** e clique em **Next**.
4. Siga as instruções para concluir a instalação.
5. Após a instalação, reinicie o Eclipse.

> Aparentemente foi necessário instalar o **abapGit** mais de uma vez, e ele realizou um downgrade no Eclipse, mas os erros não voltaram a aparecer.

**Como usar:**
- Após a instalação, o abapGit estará disponível no menu **Window → Show View → Other → abapGit Repositories**.
- Configure um repositório Git e comece a versionar seus objetos ABAP.

Para mais informações, consulte o [tutorial oficial do abapGit Plugin](https://developers.sap.com/tutorials/abap-install-abapgit-plugin.html).


## ![Static Badge](https://img.shields.io/badge/SAP-ABAP_Quickfix_S%2F4-0FAAFF?logo=sap&logoColor=white) ABAP Quickfix S/4 Conversion

O **ABAP Quickfix S/4 Conversion** facilita a migração de código ABAP para S/4HANA com correções rápidas (quick fixes), garantindo consistência e acelerando os processos de conversão.

**Principais benefícios:**
- Correções rápidas para adequação do código ao S/4HANA
- Maior consistência durante a migração de objetos
- Aceleração dos processos de conversão

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o seguinte repositório:  
   ```
   https://fidley.github.io/ADTPluginsUpdateSite/UpdateSite/
   ```
3. Na lista de plugins disponíveis, selecione **ABAP Quickfix S/4 Conversion** e clique em **Next**.
4. Siga as instruções para concluir a instalação.
5. Após a instalação, reinicie o Eclipse.

> Este plugin possui vários componentes, porém apenas o **ABAP Quickfix S/4 Conversion** precisa ser instalado.

![ABAP Quickfix S/4 Conversion](abap%20quick%20fix.png)

Para mais informações, consulte a [página oficial do plugin](https://marketplace.eclipse.org/content/abap-quick-fix/help).

## ![Static Badge](https://img.shields.io/badge/SAP-ABAP_Favorites-0FAAFF?logo=sap&logoColor=white) ABAP Favorites

O **ABAP Favorites** permite armazenar localmente seus favoritos — transações, programas, URLs e objetos de desenvolvimento — funcionando como um substituto do menu de usuário (User Menu) do SAP GUI.

**Principais benefícios:**
- Acesso rápido a objetos de desenvolvimento favoritos
- Organização de transações, programas e URLs
- Substituto do menu de usuário (User Menu) do SAP GUI
- Aumento de produtividade no dia a dia

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o seguinte repositório:  
   ```
   https://fidley.github.io/ADTPluginsUpdateSite/UpdateSite/
   ```
3. Na lista de plugins disponíveis, selecione **ABAP Favorites** e clique em **Next**.
4. Siga as instruções para concluir a instalação.
5. Após a instalação, reinicie o Eclipse.

> Este plugin é distribuído no mesmo update site do **ABAP Quickfix S/4 Conversion**; basta selecionar o componente **ABAP Favorites** na lista.

Para mais informações, consulte a [página oficial do plugin](https://marketplace.eclipse.org/content/abap-favorites).

## ![Static Badge](https://img.shields.io/badge/Eclipse-Darkest_Dark_Theme-2C2255?logo=eclipse&logoColor=white) Darkest Dark Theme (opcional)

O **Darkest Dark Theme** é um tema escuro que aprimora a visualização do código, reduzindo a fadiga visual durante longas sessões de desenvolvimento.

> [!WARNING]
> Este plugin **não possui bom suporte às atualizações de versão do Eclipse**. Após atualizar o Eclipse, ele pode apresentar incompatibilidades ou parar de funcionar. Use-o apenas se o tema for realmente necessário.

**Instalação:**
1. No Eclipse, vá para **Help → Install New Software**.
2. Adicione o repositório a partir da página oficial: [Darkest Dark Theme](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle#external-install-button).
3. Siga as instruções para concluir a instalação.
4. Após a instalação, reinicie o Eclipse.
