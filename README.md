
```
scoop bucket add 3xkesg https://github.com/3xKEsGJQsmEQLAfuMv9QikF8i9y7Bf1D6NjguXg/scoop-3xke
```

- `spacious-start-menu` : .NET LTS version
- `spacious-start-menu-net6` : .NET 6 fixed
- 

<details>
<summary>Quick reference</summary>

```
# Install Scoop
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod get.scoop.sh | Invoke-Expression

# Add bucket
scoop bucket add 3xkesg https://github.com/3xKEsGJQsmEQLAfuMv9QikF8i9y7Bf1D6NjguXg/scoop-3xke

# Listed bucket
scoop bucket list

# Search app
scoop search spacious-start-menu

# Detailed information display
scoop info spacious-start-menu

# Install app
# scoop install spacious-start-menu

# List of installed apps
scoop list

# Update
scoop update
scoop spacious-start-menu

# Uninstall app
scoop uninstall spacious-start-menu

# Remove bucket3xkesg
scoop bucket rm 3xkesg

# Cleanup
scoop cache rm *
scoop cleanup *
```

</details>
