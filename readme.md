# Hook

> build and tested for macOS (might work on linux as well)

## Install

make the tool executable

```
chmod +x .folder-hooker
```

add the following to your `.bash_profile`

```
source [PATH-WHERE-HOOK-IS-LIVING].folder-hooker
```

## Usage

### 👷 Create a new hook:

- Go to folder you want to create a hook for
- Type `hook` followed by the hook-name, e.g. `hook myProject`

### 🏃 Use a hook:

- Type the hook-name, e.g. `myProject`

### 🤔 List all hooks

- Type `hooks`

### 💀 Delete hook

- Type `unhook` followed by the hook-name, e.g. `unhook myProject`
