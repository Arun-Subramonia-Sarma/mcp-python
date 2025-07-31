# mcp

## install vu
<details>
<summary> Expand to install uv</summary>

```shell
brew instll uv
```
</details>

## Init using uv init
<details>
<summary> Expand to init uv</summary>

```shell
uv init
```
</details>

## Create virtual Environment
<details>
<summary> Expand to create virtual environment</summary>

```shell
uv venv
```
</details>

## Activate Virtual Environment
<details>
<summary> Expand to activate virtual environment</summary>

```shell
source .venv/bin/activate
```
</details>

</details>

## Installing libraries
<details>
<summary> Expand to Install requirement library</summary>

1. Create the requirement.txt

```shell
touch  requirements.txt
```

2. Add the following libraries in the requirements.txt

```shell
langchain-groq
langchain-mcp-adaptors
mcp
```
 2. Install the library using the following command
 
 ```shell
 uv add -r requirements.txt
 ```
</details>
