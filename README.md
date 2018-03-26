# Erlang 中文版

## 安裝環境

Install Erlang OTP

Go to https://www.erlang-solutions.com/resources/download.html

Choose Mac OS X

## 確認安裝

Open terminal and type 

```
$erl
```

```
Erlang/OTP 18 [erts-7.0] [source-4d83b58] [64-bit] [smp:4:4] [async-threads:10] [hipe] [kernel-poll:false]

Eshell V7.0 (abort with ^G)

1>
```

## 安裝 IDE

Go to https://www.jetbrains.com/idea/download/

Open .dmg and follow steps to install

## 設定 IDE 支持 Erlang

IDE is up and you see its Welcome screen, go to Configure | Plugins, then click Browse repositories,

locate the Erlang plugin and install it: After installing the plugin, restart IntelliJ IDEA.

## IDE 內設定 SDK

Configure Erlang SDK inside IntelliJ

To do that, change the structure of the default
project. Open the default project structure in one
of the two ways:

On the Welcome screen, go to Configure |
Project Defaults | Project Structure

On the main menu, choose File | Other
Settings | Default Project Structure

Then, add an Erlang SDK by specifying the path
to the Erlang OTP installation directory.

## 設置 rebar

The final adjustment you have to do is to specify
the path to Rebar, so that IntelliJ IDEA can run
Rebar commands from the IDE.

You can do it via Configure | Preferences | Other
Settings → Erlang External Tools

## References

https://www.jetbrains.com/help/idea/getting-started-with-erlang.html#d207953e18