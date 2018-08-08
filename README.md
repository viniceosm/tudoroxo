# Tudo roxo
## Custom Material Theme

![Screenshot_1](Screenshot_1.png)

### Change Custom title bar here

For use custom bar title of [Version 1.25](https://code.visualstudio.com/updates/v1_25):

1. File > Preferences > Settings (Ctr+,)
2. Look for `"window.titleBarStyle": "native"`, copy it to your user settings & change it to `"window.titleBarStyle": "custom"`
3. In your user settings add the following.

```json
"workbench.colorCustomizations": {
	"[Tudoroxo]": {
		"titleBar.activeBackground": "#322053",
		"titleBar.activeForeground":"#ffffff"
	}
}
```
