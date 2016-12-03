# learn-elixir
Learn Elixir to build dynamic, functional, scalable and maintainable web applications!

<img src="http://elixir-lang.org/images/logo/logo.png" width="70%">

## *Why*?
Elixir is scalable, efficient, and fault-tolerant. Things *will* go wrong with
code, and Elixir provides supervisors which describe how to restart parts of
your system when things don't go as planned.

## *What*?
[_**"Elixir is a dynamic, functional language designed for building scalable and
 maintainable applications."**_](http://elixir-lang.org/)

#### Background links:
* [Introduction and Setup](http://elixir-lang.org/getting-started/introduction.html)
* [Getting started](http://elixir-lang.org/getting-started/basic-types.html)

## *How*?
You can see how to install Elixir [here](http://elixir-lang.org/getting-started/introduction.html)

#### Installation basics:
###### Mac:
`brew install elixir`

###### Ubuntu:
* **_Add_ Erlang Solutions repo**: wget https://packages.erlang-solutions.com/erlang-solutions_1.0_all.deb && sudo dpkg -i erlang-solutions_1.0_all.deb
* _**Run**_: sudo apt-get update
* **_Install_ the Erlang/OTP platform and all of its applications**: sudo apt-get install esl-erlang
* **_Install_ Elixir**: sudo apt-get install elixir

## *Handy Tips*

#### Interactive Terminal
After installing Elixir you can open the interactive shell by typing: `iex`

#### Function Documentation
If you want to see some information about a built in function you can just type `h` and the `function` name to get information on how to use it!

Try typing `h round` into the (iex) terminal and you should see something like this:

![elixir-h](https://cloud.githubusercontent.com/assets/14013616/20860273/fc801b14-b96b-11e6-9b17-7e26666d5d94.png)

#### Information about values
If you want to see some information about a value in your code, type `i` followed by the value name:

![elixir-i](https://cloud.githubusercontent.com/assets/14013616/20860322/3c01d984-b96d-11e6-8cc4-a46c8657f5b4.png)

## *Basic Types*

Elixir has 7 basic types:

* `integers`
* `floats`
* `booleans`
* `atoms`
* `strings`
* `lists`
* `tuples`

#### Working with numbers:

try typing `1 + 2` into the terminal (after opening `iex`) and it should look like this
```elixir
iex> 1 + 2
3
```

Some more examples

```elixir
iex> 5 * 5
10

iex> 10 / 2
5.0
```

When using the `/` with two integers this gives a `float` (5.0). If you want to do integer division or get the division remainder you can use the `div` or `rem` functions

```elixir
iex> div(10, 2)
5

iex> div 10, 2
5

iex> rem 10, 3
1
```
