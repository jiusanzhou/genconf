<p align="center">
    <img src="./logo/genconf.png" width="200" height="200" />
</p>
<h2 align="center">genconf</h2>
<p align="center">Genconf is a tool to generate config code from configuration file.</p>


---

| Don't repeat yourself, every piece of knowledge must have a single, unambiguous, authoritative representation within a system. |
| - |

<details>
<summary>Install</summary>

### Requirements:

1. Golang

### Install:

1. Download latest code with `go get` 
    ```bash
    go get -u go.zoe.im/genconf
    ```
2. Install `genconf` with `go install`
    ```bash
    go install go.zoe.im/genconf
    ```
3. Make sure you have install `genconf` success
    ```bash
    genconf version
    ```
</details>

<details>
<summary>Usage</summary>

### Steps

1. Write your configuration with extend name we supported
    1. `json`: JSON file.
    2. `yaml`, `yml`: YAML file. :tada: **RECOMMAND**
    3. `toml`: TOML file. :tada: **RECOMMAND**
2. Generate code with command
    ```bash
    genconf
    ```

### Examples

</details>