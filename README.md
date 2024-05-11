# Teste para um site responsivel ao chat

Atuamente os chats são periféricos ao site do qual fazem parte, podem ser iguinorados.
A ideia é fazer com que o frontend receba do site insumos que possam ser utilizados na leitura de um json no formato 

~~~~JSON
{
    "url": "http://exemplo.exemplo.com",
    "title": "{O titulo da página}",
    "sugestion": "{Uma sugestão a ser printada dentro do site}",
    "response": "A resposta no chat"
}
~~~~

> O modelo atual não completa o frontend, serve apenas para testar e treinar como configurar o modelo do LLM.
> 
