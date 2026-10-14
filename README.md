# lwe-which-error
Looking at LWE errors and when error sampling could break. Currently just me toying around in SageMath

Reminder to myself on how to run this thing (Fedora 44):
```bash
# already done
# Install MiniForge, add to PATH
# Modify such that mamba would init on shell load:
#  mamba shell init --shell zsh --root-prefix=~/.local/share/mamba
# Shut down shell, restart; create mamba environment
#  mamba create -n sage sage

# Activate the mamba (basically like Conda) venv with sage
mamba activate sage

# Run Sage's Jupyter environment (because it seems like SageMath VSCodium extension doesn't readily exist)
#  which needs to be opened in browser
sage -n jupyter
```
