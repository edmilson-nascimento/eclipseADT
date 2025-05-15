# Eclipse ADT | Versão França
Eclipse ADT | Versão França

~~A Versão França não tem nenhum vínculo com o país França, é apenas uma versão personalizada do Eclipse ADT com plugins pré-configurados para desenvolvimento ABAP.~~

![Static Badge](https://img.shields.io/badge/eclipse-4.35.0-2C2255?logo=eclipse&logoColor=white)
![Static Badge](https://img.shields.io/badge/eclipse%20adt-4.35.0-2C2255?logo=eclipse&logoColor=white)

![Static Badge](https://img.shields.io/badge/development-abap-blue)
![Static Badge](https://img.shields.io/badge/SAP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/ABAP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/Eclipse_ADT-2C2255?logo=eclipse&logoColor=white)
![Static Badge](https://img.shields.io/badge/BTP-0FAAFF?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/Cloud-0089D6?logo=sap&logoColor=white)
![Static Badge](https://img.shields.io/badge/SAP_DevOps-050002?logo=sap&logoColor=white)

[![ABAP Cleaner](https://img.shields.io/github/stars/SAP/abap-cleaner?label=ABAP%20Cleaner&style=social)](https://github.com/SAP/abap-cleaner)
[![abapGit](https://img.shields.io/github/stars/larshp/abapGit?label=abapGit&style=social)](https://github.com/larshp/abapGit)

Este repositório contém uma versão personalizada do Eclipse ADT com plugins pré-configurados para desenvolvimento ABAP. As atualizações serão realizadas de forma controlada para garantir a estabilidade do ambiente.

> Ainda em testes, mas fiz a instalação do temurin jdk 24 e do eclipse 4.35.0, ambos com suporte a java 21.
```winget
winget install EclipseAdoptium.Temurin.24.JDK
```

### ![Static Badge](https://img.shields.io/badge/SAP-ADT-0FAAFF?logo=sap&logoColor=white) ABAP Development Tools (ADT)

O **ABAP Development Tools (ADT)** é uma extensão do Eclipse que fornece um ambiente moderno e eficiente para o desenvolvimento ABAP. Ele é essencial para desenvolvedores que trabalham com sistemas SAP, oferecendo uma interface intuitiva e ferramentas avançadas para codificação, depuração e gerenciamento de objetos ABAP.

**Principais benefícios:**
- Ambiente de desenvolvimento integrado (IDE) moderno e eficiente.
- Suporte para desenvolvimento em sistemas SAP S/4HANA e SAP NetWeaver.
- Ferramentas avançadas para depuração e análise de código.
- Integração com outras ferramentas, como abapGit e ABAP Cleaner.
- Melhor experiência de desenvolvimento em comparação ao SE80.

**Instalação:**
1. Faça o download do **Eclipse IDE for Java Developers** no site oficial: [Eclipse Downloads](https://www.eclipse.org/downloads/packages/release/2025-03/r/eclipse-ide-java-developers).
2. Após instalar o Eclipse, vá para **Help → Install New Software**.
3. Adicione o seguinte repositório:  
   ```
   https://tools.hana.ondemand.com/latest
   ```
4. Na lista de plugins disponíveis, selecione **ABAP Development Tools (ADT)** e clique em **Next**.
5. Siga as instruções para concluir a instalação.
6. Após a instalação, reinicie o Eclipse.

**Como usar:**
- Após a instalação, conecte-se ao sistema SAP usando a opção **File → New → ABAP Project**.
- Configure o sistema SAP e comece a desenvolver seus objetos ABAP diretamente no Eclipse.

Para mais informações, consulte o [tutorial oficial do ADT](https://developers.sap.com/tutorials/abap-install-adt.html).

### ![Static Badge](https://img.shields.io/badge/SAP-ABAP_Cleaner-0FAAFF?logo=sap&logoColor=white) ABAP Cleaner

O ABAP Cleaner é uma ferramenta essencial para desenvolvedores ABAP que automatiza a formatação e melhoria do código. 

**Principais benefícios:**
- Formatação consistente do código ABAP
- Alinhamento automático de declarações e operações
- Remoção de espaços em branco desnecessários
- Organização de declarações de variáveis
- Melhoria na legibilidade do código
- Aplicação de boas práticas de desenvolvimento

**Instalação:**
1. No Eclipse, vá para Help → Install New Software
2. Adicione o repositório: 
   ```
   https://sap.github.io/abap-cleaner/updatesite
   ```
3. Selecione "ABAP Cleaner" e complete a instalação

Para mais informações, visite o [repositório oficial](https://github.com/SAP/abap-cleaner).


### ![Static Badge](https://img.shields.io/badge/Git-abapGit-F05032?logo=git&logoColor=white) abapGit Plugin

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

> Parece que eu tive que instalar o **abapGit** mais de uma vez e ele fez downgrade no Eclise, mas, os erros não apareceram mais.

**Como usar:**
- Após a instalação, o abapGit estará disponível no menu **Window → Show View → Other → abapGit Repositories**.
- Configure um repositório Git e comece a versionar seus objetos ABAP.

Para mais informações, consulte o [tutorial oficial do abapGit Plugin](https://developers.sap.com/tutorials/abap-install-abapgit-plugin.html).


### Plugins Instalados

A seguir, uma lista organizada dos plugins essenciais para o desenvolvimento ABAP no Eclipse. Esses plugins foram cuidadosamente selecionados para otimizar a produtividade e melhorar a experiência de desenvolvimento.

> A propria busca do Eclipse Marketplace não esta funcionando, então é possivel buscar os apps na ultima abap **Research at the Eclipse** e isso faz uma busca no google direto no site ~~ou vai dar erro na mesma e eu estou apenas perdendo tempo~~.

1. ~~**Eclipse Marketplace Client**~~  
   - ~~**Descrição:** Cliente indispensável para a instalação e gerenciamento de plugins no Eclipse.~~  
   - ~~**Instalação:** [Eclipse Marketplace Client](https://marketplace.eclipse.org/content/eclipse-marketplace-client#external-install-button)~~

2. ~~**ABAP ADT Extensions**~~  
   - ~~**Descrição:** Fornece extensões adicionais para os ABAP Development Tools, aprimorando recursos essenciais para o desenvolvimento ABAP.~~  
   - ~~**Instalação:** [ABAP ADT Extensions](https://marketplace.eclipse.org/content/abap-adt-extensions#external-install-button)~~

3. ~~**ABAP Favorites**~~  
   - ~~**Descrição:** Otimiza o gerenciamento e acesso aos objetos ABAP favoritos, aumentando a produtividade do desenvolvedor.~~  
   - ~~**Instalação:** [ABAP Favorites](https://marketplace.eclipse.org/content/abap-favorites#external-install-button)~~

4. **ABAP Quickfix S/4 Conversion** 
   - **Descrição:** Facilita a migração de código ABAP para S/4HANA com correções rápidas, garantindo consistência e acelerando processos de conversão.  
   - **Instalação:** [ABAP Quickfix S/4 Conversion](https://marketplace.eclipse.org/content/abap-quick-fix/help)
   Esse tem varios componentes e não precisa ser instalado, apenas o **ABAP Quickfix S/4 Conversion**.
   ![ABAP Quickfix S/4 Conversion](abap%20quick%20fix.png)

5. ~~**ADT Classic Outline**~~  
   - ~~**Descrição:** Oferece uma visualização clássica e simplificada da estrutura do código ABAP, facilitando o entendimento dos componentes.~~  
   - ~~**Instalação:** [ADT Classic Outline](https://marketplace.eclipse.org/content/adt-classic-outline#external-install-button)~~

6. **Darkest Dark Theme**  
   - **Descrição:** Tema escuro que aprimora a visualização do código, reduzindo a fadiga visual durante longas sessões de desenvolvimento.  
   - **Instalação:** [Darkest Dark Theme](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle#external-install-button)

7. ~~**EclEmma Java Code Coverage**~~   
   - ~~**Descrição:** Ferramenta essencial para análise da cobertura de código, permitindo identificar áreas com menor teste e garantindo a qualidade do software.~~
   - ~~**Instalação:** [EclEmma Java Code Coverage](https://marketplace.eclipse.org/content/eclemma-java-code-coverage#external-install-button)~~

8. ~~**Eclipse XML Editors and Tools**~~  
   ~~- **Descrição:** Conjunto de ferramentas avançadas para edição e manipulação de arquivos XML, oferecendo maior flexibilidade dentro do Eclipse.~~  
   ~~- **Instalação:** [Eclipse XML Editors and Tools](https://marketplace.eclipse.org/content/eclipse-xml-editors-and-tools#external-install-button)~~

9. ~~**EGit**~~  
   ~~- **Descrição:** Integração completa com o Git, possibilitando o controle de versão diretamente no Eclipse.~~  
   - ~~**Recursos Adicionais:**~~  
      - ~~[EGit User Guide](https://wiki.eclipse.org/EGit/User_Guide/)~~  
      - ~~[Git no Eclipse (Vogella)](https://www.vogella.com/tutorials/EclipseGit/article.html)~~  
   - **Instalação:** [EGit](https://marketplace.eclipse.org/content/egit-git-integration-eclipse#external-install-button)

10. ~~**Relative Line Number Ruler**~~  
    - ~~**Descrição:** Exibe números de linha em formato relativo, facilitando a navegação e referências durante a edição do código.~~  
    - ~~**Instalação:** [Relative Line Number Ruler](https://marketplace.eclipse.org/content/relative-line-number-ruler#external-install-button)~~