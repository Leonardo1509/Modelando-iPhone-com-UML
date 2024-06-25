# Modelando-o-iPhone-com-UMLUML
## POO - Desafio

### Modelagem e Diagramação de um Componente iPhone

Neste desafio, você será responsável por modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

### Exemplo de Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        void + tocar()
        void + pausar()
        void + selecionarMusica()
    }

    class AparelhoTelefonico {
        void + ligar()
        void + atender()
        void + iniciarCorreioVoz()
    }

    class NavegadorInternet {
         void + exibirPagina()
         void + adicionarNovaAba()
         void + atualizarPagina()
    }

    class iPhone {
         void + tocar()
         void + pausar()
         void + ligar()
         void + atender()
         void + iniciarCorreioVoz()
         void + exibirPagina()
         void + adicionarNovaAba()
         void + atualizarPagina()
      
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```
