1 - Lembre-se de trabalhar sempre com ambientes virtuais para cada atividade:
  - `python -m venv ./<namevenv>`: criação
  - `source ./<namevenv>/bin/activate`: ativação
  - `source deactivate`: desativação

2 - Instale as dependências necessárias (como o pandas e o jupyter, por exemplo)

3 - Faça com que o Jupyter reconheça o kernel instalado no ambiente virtual:
  - `ipython kernel install --user --name=<namevenv>` ou
  - `python -m ipykernel install --user --name=<namevenv>`
