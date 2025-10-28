# Restaurante SAVORE - Site Gourmet

Este repositório contém o código-fonte do projeto final da disciplina de Desenvolvimento Mobile. O objetivo é criar um site responsivo e interativo para o restaurante gourmet fictício "SAVORE", aplicando conceitos avançados de front-end e integração de plugins JavaScript.

## 👥 Integrantes do Grupo

  * Gabriel Ortiz Gomes da Silva
  * Natã de Jesus Felicio Peralta
  * Andrey Guilherme Garcia Pires

-----

## Tabela de Conteúdos

1.  [Tecnologias Utilizadas](#-tecnologias-utilizadas)
2.  [Estrutura do Site (Páginas)](#-estrutura-do-site-páginas)
3.  [Funcionalidades e Plugins](#-funcionalidades-e-plugins)
4.  [Formulários](#-formulários)
5.  [Como Executar](#-como-executar)

-----

## 🛠️ Tecnologias Utilizadas

Este projeto é construído primariamente com tecnologias front-end, focando em interatividade e responsividade.

  * **Base:** HTML5, CSS3, JavaScript (Vanilla)
  * **Frameworks & Bibliotecas:**
      * **jQuery:** Utilizado para manipulação do DOM em funcionalidades como o filtro de pratos, accordion e menu hamburguer.
      * **Bootstrap:** Utilizado para componentes de UI, como o Modal de agradecimento e, opcionalmente, o filtro e accordion.
      * **Swiper.js:** Para a implementação do slider/carrossel de pratos na Home.
      * **Flatpickr:** Para a criação de um seletor de data (Date Picker) moderno no formulário de reservas.
      * **AOS.js (Animate On Scroll):** Para implementar animações sutis durante a rolagem da página.

-----

## 🗺️ Estrutura do Site (Páginas)

O site é composto pelas seguintes páginas e seções:

  * **Layout Global:**

      * **Header:** Contém o logo e o menu de navegação principal (com funcionalidade de menu hamburguer em dispositivos móveis).
      * **Footer:** Inclui informações de contato rápidas, links de navegação secundária e redes sociais.

  * **Páginas Principais:**

      * **Home:** Página inicial com uma *Hero Section*, slider de pratos (Swiper) e animações de entrada.
      * **Cardápio:** Apresenta os pratos com um sistema de filtro interativo por categoria.
      * **Chef:** Página dedicada ao chef, com sua biografia e uma galeria de fotos.
      * **Reservas:** Contém um formulário completo para agendamento de mesas, incluindo o Date Picker.
      * **Delivery:** Página informativa sobre o serviço de entrega.
      * **Blog:** Exibição de posts e artigos gastronômicos.
      * **Galeria de Pratos:** Galeria de imagens focada nos pratos do restaurante.
      * **Galeria do Ambiente:** Galeria de imagens mostrando o ambiente e decoração.
      * **Sobre:** Detalha a história, os valores e a missão do SAVORE.
      * **Localização:** Apresenta um mapa (Google Maps) e pontos de referência.
      * **Contato:** Informações de contato (telefone, email) e, opcionalmente, um formulário simples.
      * **Feedback:** Página para avaliação do cliente, incluindo um formulário de satisfação e um FAQ sobre alérgenos.

-----

## ✨ Funcionalidades e Plugins

O projeto integra 7 funcionalidades principais baseadas em plugins JavaScript para garantir uma experiência de usuário moderna e fluida.

✅ **Slider de pratos (Home)**

  * **Plugin:** `Swiper.js`
  * **Descrição:** Carrossel interativo na Home page com autoplay e botões de navegação para destacar os pratos principais.

✅ **Filtro de Pratos (Cardápio)**

  * **Plugin:** `jQuery` ou `Bootstrap`
  * **Descrição:** Sistema que permite ao usuário filtrar os pratos exibidos por tipo (ex: Entradas, Prato Principal, Sobremesas).

✅ **Date Picker (Reservas)**

  * **Plugin:** `Flatpickr`
  * **Descrição:** Substitui o input de data padrão por um calendário interativo e estilizado, garantindo consistência visual entre navegadores.

✅ **Accordion FAQ (Feedback)**

  * **Plugin:** `jQuery` ou `Bootstrap`
  * **Descrição:** Seção de Perguntas Frequentes (FAQ) sobre alérgenos, onde as respostas são reveladas ao clicar na pergunta.

✅ **Animações On Scroll**

  * **Plugin:** `AOS.js`
  * **Descrição:** Efeitos de *fade*, *slide* e *zoom* aplicados a elementos em todas as páginas conforme o usuário rola a tela.

✅ **Modal de Agradecimento**

  * **Plugin:** `Bootstrap`
  * **Descrição:** Janela pop-up exibida para o usuário após o envio bem-sucedido dos formulários de Reserva ou Feedback.

✅ **Menu Hamburguer (Header)**

  * **Plugin:** `jQuery`
  * **Descrição:** Menu de navegação responsivo que se transforma em um ícone "hamburguer" em dispositivos móveis, revelando os links ao ser clicado.

-----

## 📋 Formulários

O site possui dois formulários complexos para interação com o cliente:

### 1\. Formulário de Reservas

  * **Total de Campos:** 7
  * **Campos:**
    1.  Nome
    2.  Email
    3.  Telefone
    4.  Data (com Flatpickr)
    5.  Horário
    6.  Número de Pessoas
    7.  Observações (opcional)

### 2\. Formulário de Feedback

  * **Total de Campos:** 10
  * **Campos:**
    1.  Nome
    2.  Email
    3.  Avaliação Geral (ex: estrelas)
    4.  Qualidade da Experiência
    5.  Qualidade do Prato
    6.  Qualidade do Atendimento
    7.  Qualidade do Ambiente
    8.  Você voltaria? (Sim/Não)
    9.  Comentários Adicionais
    10. Você nos recomendaria? (Sim/Não)

-----

## 🚀 Como Executar

Este é um projeto front-end estático. Não é necessário um *build* ou um servidor back-end para visualizá-lo.

1.  Clone o repositório para sua máquina local:

    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```

2.  Navegue até o diretório do projeto:

    ```bash
    cd [NOME_DA_PASTA_DO_PROJETO]
    ```

3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).
