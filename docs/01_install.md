# :fontawesome-solid-download:{ .icons } Installation

ALP-aca can be installed with `pip`:

```bash
pip3 install alpaca-ALPs
```

## :fontawesome-solid-boxes-stacked:{ .icons } Optional dependencies

The plotting backends, `matplotlib` and `plotly`, are not included as depencencies of ALP-aca, but they can be installed as optional dependencies. To install with `matplotlib`

```bash
pip3 install alpaca-ALPs[matplotlib]
```

with `plotly`

```bash
pip3 install alpaca-ALPs[plotly]
```

and with both

```bash
pip3 install alpaca-ALPs[matplotlib,plotly]
```

## :fontawesome-solid-terminal:{ .icons } Virtual environments

It is *strongly recommended* to install ALP-aca inside a virtual environment (venv), in order to avoid clashes with conflicting versions of the dependencies. In order to create a venv, execute the following command

```bash
python3 -m venv pathToVenv
```

where `pathToVenv` is the location where the files of the venv will be stored. In order to activate the venv, for Linux or MacOS using `bash` or `zsh`

```bash
source pathToVenv/bin/activate
```

For Windows using ```cmd.exe```

```bat
C:\> pathToVenv\Scripts\Activate.bat
```

And for Windows using ```PowerShell```

```powershell
PS C:\> path_to_venv\Scripts\Activate.ps1
```

Once the venv is activated, ALPaca can be normally installed and used.