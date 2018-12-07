# SimpleServer

**A very barebones server in Elixir, just to see what it can do :)**

## How to use

Just run this in the terminal:
```elixir
iex -S mix
```
Then, using the curl command, or a web browser:
```
localhost:8080/hello 
```
gives you a "world" response (200), and anything else a 404.

To get a 201 try running this:

```
curl -v -H 'Content-Type: application/json' "http://localhost:8080/post" -d '{"message": "hello world" }'
```

This website ( https://www.jungledisk.com/blog/2018/03/19/tutorial-a-simple-http-server-in-elixir/ ) inspired me to do this!
