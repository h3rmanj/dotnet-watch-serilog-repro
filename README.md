# dotnet-watch-serilog-repro

Run `dotnet watch run` in WebApplication1. Browser will not be launched.

Comment out `.UseSerilog()` in [Program.cs on line 26](https://github.com/h3rmanj/dotnet-watch-serilog-repro/blob/main/WebApplication1/Program.cs#L26), and run `dotnet watch run` again. The browser will now launch correctly
