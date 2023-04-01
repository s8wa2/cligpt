# CliGPT

Streamline your terminal experience by generating Linux commands from natural language queries, reducing the need to leave the terminal for manual web searches.

# Demo

![](https://s2.gifyu.com/images/ezgif.com-crop1.gif)

# Setup

```
chmod +x install.sh
./install.sh
```

This will create a symbolic link for CliGPT in the ${HOME}/.local/bin directory, making it accessible system-wide.

If a previous version is already installed, the symbolic link will be updated.

I might tweak the prompt in this repository from time to time.

You might want to tweak it too and suggest changes through a Pull Request.

**Make sure you have the OPENAI_API_KEY environment variable set.**

You can do so by running:

```export OPENAI_API_KEY=<your key here>```

Or by adding the above command to your shell .rc file, or whatever other environment variable setup you prefer. 

# Run

```cligpt <linux related question>```

You will be asked to confirm if you want to run the command or not, no need to copy and paste it.

## Thanks for being here

If you enjoyed this, you might like [GitGPT](https://github.com/Luanf/gitgpt) - to get suggestions for Git, altough CliGPT can work with Git commands as well.
