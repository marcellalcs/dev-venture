# Aula 16

## Objetivos
Reforçar conceitos sobre gestão de processos e threads no Android. Construir uma ViewModel do zero com auxílio de ViewModelProvider e ViewModelFactory. Discutir sobre o conceito de Injeção de Dependências e framworks. Aplicar Koin para injeção de depenências do projeto
 

## Tópicos Abordados
- Gerenciamento de threads
- Coroutines
    - Job
    - Scope
    - Dispatcher
    - Suspend function
- Padrão Observable
    - LiveData
- ViewModel
    - ViewModelProvider
    - ViewModelFactory


## Links e referências

Vídeo [Coroutines](https://youtu.be/ZTDXo0-SKuU)

Documentação [Coroutines e Android](https://developer.android.com/kotlin/coroutines?gclid=CjwKCAjwt8uGBhBAEiwAayu_9dRv0BaMOwPHHJN266cFyLytatSYSnuoi2tZ0rd9UuznRR9Lp4txuhoCig4QAvD_BwE&gclsrc=aw.ds)

Vídeo [ViewModel](https://youtu.be/5qlIPTDE274)

Documentação [Koin](https://insert-koin.io/)

Vídeo [DI Zero from Hero](https://www.youtube.com/watch?v=chCsNkjotfc)

Artigo [DI com Koin](https://medium.com/collabcode/inje%C3%A7%C3%A3o-de-depend%C3%AAncia-no-kotlin-com-koin-4d093f80cb63)

## Atividades
- Implementar a funcionalidade de adicionar um novo item aprendido. Essa funcionalidade deve armazenar o novo item no banco de dados e validar se os dados adicionados não estão vazios.

_Dica_: Use a ViewModel para validar os dados. Injete a viewmodel com auxlílio do Koin. No clique para salvar o item, após a inserção, dispare uma navegação para a tela principal



