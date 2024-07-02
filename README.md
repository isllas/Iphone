classDiagram
    class Reprodutor_Musical{
      +tocar()
      +pausar()
      +selecionarMusica(String musica)
    }
    class Aparelho_Telefonico{
      +ligar(String numero)
      +atender()
      +iniciarCorreioVoz()
    }
    class Navegador_Internet{
      +exibirPagina(String url)
      +adicionarNovaAba()
      +atualizarPagina()
    }
    
    Iphone <|-- Reprodutor_Musical
    Iphone <|-- Aparelho_Telefonico
    Iphone <|-- Navegador_Internet
    Iphone : +Modelo
    Iphone : +Cor
    Iphone: +Memoria
    Iphone: +Armazenamento
