![postman-logo text-320x132](https://user-images.githubusercontent.com/4249709/29496848-63ad446c-85b1-11e7-904e-a4ddad25e9db.png)


## Características: 
  	-  Criar um projeto de automação utilizando a API pública 
	-  Criar um empregado.
  	-  Validar se o empregado foi criado corretamente.
	-  Exclua esse usuário.
	-  Validar sempre o Status Code e a mensagem exibida.
   	-  Gerar relatório dos testes executados.
	

## Newman 

	Objetivo:
	É um comando de linha utilizado para rodar as collection do Postman. A partir deste comando é possível inserir iterações,gerar relatórios em html, json etc.. 



![Capturar](https://user-images.githubusercontent.com/20347604/82456489-abfefa80-9a8a-11ea-8fde-2669bc841ed9.PNG)


## Rodar os Testes via Newman 

	Exemplo: 
	newman run ame.postman_collection.json -e variable.postman_environment.json --reporters=cli,htmlextra
