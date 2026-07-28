# Eclipse Che Devfiles

Public Devfiles for validating non-root Eclipse Che workspaces.

## Workspaces

- `ghcr.io/jannikpioro/cloud-task/java-workspace:1.0.0`
- `ghcr.io/jannikpioro/cloud-task/python-workspace:1.0.0`

Both runtime containers use UID `10001` with user `user`.

## Repository Layout

- `java/devfile.yaml` - Java workspace definition
- `python/devfile.yaml` - Python workspace definition
- `Hello.java` - Java Hello World example
- `hello.py` - Python Hello World example

## Run The Hello Files

```bash
java Hello.java
```

```bash
python hello.py
```

Or run the Python file directly:

```bash
./hello.py
```
