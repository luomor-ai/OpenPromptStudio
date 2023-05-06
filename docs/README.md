```shell
sudo docker build -t yiluxiangbei/open-prompt-studio:latest -f docker1/dockerfile .
sudo docker run -d -p 12833:12833 -p 39011:39011 --name open-prompt-studio yiluxiangbei/open-prompt-studio:latest

sudo docker-compse up -d

Web 访问端口：12833
翻译服务端口：39011

https://www.notion.so/zh-cn
https://bobtranslate.com/service/translate/tencent.html
```