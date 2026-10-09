# Deconstructing-Machine
A machine that deconstructs what had been constructed.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Can you deconstruct is for me, machine?" \
  | uvx deconstructing-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install deconstructing-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
deconstructing-machine -a multilogue.txt
```
Or:
```bash
deconstructing-machine multilogue.txt > response.txt
```
Or:
```bash
deconstructing-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import deconstructing_machine
```
