# maketh
A short introduction to understanding the blockchain by building one yourself. Maketh
uses [Python](#) and [Jupyer Notebooks](#) to give an education implementation of a 
barebones cryptocurrency that leverages the concept that is a "blockchain."

By the end of this tutorial you will have:
- Understood the core concepts of blockchain (in the context of Bitcoin)
- Implemented several key blockchain algorithms on a high-level
- Built a rudimentary, hackable blockchain (don't worry, you'll hack it yourself first)

The currency that you will build today is similar to Bitcoin. As such, I will explain 
core blockchain concepts in the context of Bitcoin. Since I'll often use specefic examples, 
certain parts of this guide may not be true for another cryptocurrency or project implemented 
on a blockchain. The cryptocurrency that you build will feature only the minimal funtionality 
required to be considered a **local** cryptocurrency. This means that it can only be run on 
a singular node, and is constrained to, your computer. Consider this tutorial an educational 
introduction to the various elements that comprise a blockchain:

1. Wallets
1. Transactions
1. Blocks
1. Mining
1. Consensus

We'll start with the smallest elements then work our way to more macro concepts, building 
incrementally on what we've learned.

## Prerequisites
Maketh was built in Python 3. This can be most easily installed using Homebrew.
```bash
$ brew install python3
```

## Installation (Mac OS)
Start by cloning the repository. Optionally, you can fork your own version of the repository
and clone that version instead.
```bash
$ git clone https://github.com/Meeshbhoombah/maketh.git
Cloning into 'maketh'...
remote: Counting objects: 39, done.
```

Create a virtual envrionment and install Jupyter Notebooks. The simplest way is to use
[Conda](https://conda.io/docs/index.html), instructions for installation can be found 
[here](https://conda.io/docs/user-guide/install/macos.html#install-macos-silent).
```bash
$ conda create --name maketh
```

Which can then be activated.
```
$ source activate maketh
```

## Todo
- [] Add detailed explainer of the wallet

