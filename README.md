CHAT GPT
.Net 6 Console


API: https://platform.openai.com/docs/api-reference/completions/create

Comandos usados para criação do projeto

Dotnet --version 
	7.0.102

dotnet new console -n ask

cd ask

dotnet add package Newtonsoft.Json

dotnet add package TextCop

dotnet build

dotnet run --project ask -- "quantas sementes tem uma melancia?"



Gerando um arquivo .exe

dotnet publish -r win-x64

caminho: E:\ask\ask\bin\Debug\net6.0\win-x64\publish\ask.exe

proximo passo colocar nas variaveis de ambiente esse path E:\ask\ask\bin\Debug\net6.0\win-x64\publish

abre o cmd e digita ask "pergunta?"


