# deepl-free-translate-service
免token无限次使用deepl,根据网页版JavaScript加密算法开发的服务;所以只要官网的算法不该,理论上就可以无限使用;

token free unlimited use of deepl, according to the web version of JavaScript encryption algorithm developed services; So as long as the official website algorithm should not, theoretically can be unlimited use


<img width="1922" alt="image" src="https://user-images.githubusercontent.com/84266551/219991183-7ea20190-f77c-45de-a9c5-678bc3f32a2a.png">


request params:

{
    "text": "Node.js is similar in design to, and influenced by, systems like Ruby's Event Machine and Python's Twisted. Node.js takes the event model a bit further. It presents an event loop as a runtime construct instead of as a library. In other systems, there is always a blocking call to start the event-loop. ",
    "source_lang": "EN",
    "target_lang": "ZH"
}

response:

{
    "id": 104473000,
    "jsonrpc": "2.0",
    "result": {
        "detectedLanguages": {
            "EN": 1.0
        },
        "lang": "EN",
        "lang_is_confident": true,
        "texts": [
            {
                "alternatives": [],
                "text": "Node.js在设计上类似于Ruby的Event Machine和Python的Twisted等系统，并受到其影响。Node.js在事件模型上更进一步。它将事件循环作为一种运行时结构，而不是作为一个库。在其他系统中，总是有一个阻塞的调用来启动事件循环。"
            }
        ]
    }
}
