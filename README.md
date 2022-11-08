# Caching
Programinha simples para testar o redis no .net.

Mantém dados em cache por 1 minuto. Caso os valores estejam em cache, não busca no banco de dados, caso estejam, busca do cache.

# Rodando a aplicação
Com o docker instalado, executar o seguinte comando para rodar o servidor redis:

```docker run --name my-redis -p 5002:6379 -d redis```

Para rodar a aplicação .net, basta executar o comando ```dotnet run``` na pasta raiz do projeto.

