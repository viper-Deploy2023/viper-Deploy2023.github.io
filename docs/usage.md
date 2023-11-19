# Usage

To use this program, you need to create a [Discord Application](https://discord.com/developers/applications).
Navigate to the Bot section, and find the token. To import the token as an environment
variable, run the following in the shell:

```shell
$ echo "export DISCORD_TOKEN='yourtoken'" >> ~/.bashrc
$ source ~/.bashrc
$ exec bash
```

Then, you can execute by running:

```shell
$ python main.py
```