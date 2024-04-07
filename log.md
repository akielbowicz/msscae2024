**2024-04-07**



Hay un problema, si el sistema esta completo `move_agent_single!` no sirve.

Completo el setup de Schelling con Agents.jl.

**2024-04-02**


- Configuro repo para publicar los documentos que genera quarto con GHA
https://quarto.org/docs/publishing/github-pages.html#github-action


**2024-03-14** (π day!)

- Configuro el ambiente de python con jupyter para poder usar Quarto Preview en VSCode
    ```
    python -m venv .venv
    ./.venv/Scripts/Activate.ps1 # En pwsh
    python -m pip install -r requirements.txt
    ```
- Configuro el devcontainer con las extensiones necesarias 
- Configuro el ambiente de julia para usar Quarto y Pluto 
[](https://www.paltmeyer.com/blog/posts/tips-and-tricks-for-using-quarto-with-julia/)