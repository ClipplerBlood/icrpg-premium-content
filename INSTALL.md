## Install guide

1. Find where your Foundry Module Data is stored. [Where is my data stored?](https://foundryvtt.com/article/configuration/#:~:text=Where%20Is%20My%20Data%20Stored%3F) By default:
- Windows: `%localappdata%/FoundryVTT/Data/modules`. To go there quickly, you can press Windows+R, paste `%localappdata%/FoundryVTT/Data/modules` and press enter. Alternatively you can manually browse the folder, which is located at: `C:\Users\<YOUR_USER_NAME>\AppData\Local\FoundryVTT\Data\modules`
- macOS:  `~/Library/Application Support/FoundryVTT/Data/modules`
- Linux: `/home/$USER/.local/share/FoundryVTT`, `/home/$USER/FoundryVTT`, `/local/FoundryVTT`

2. After locating where your Foundry install is located, extract the content of the module's zip. After extracting, the modules folder structure should be:
```
FoundryVTT/Data/modules/
├─ icrpg-premium-content/
│  ├─ module.json
│  ├─ assets/
│  ├─ module/
│  ├─ packs/
│  ├─ styles/
```
Note: the extracted folder's name in FoundryVTT/Data/modules/ must be icrpg-premium-content!

3. You are all set! Restart your foundry application and enable the module in your game settings.

---

### Troubleshooting
#### The module doesn't show up under modules
- Make sure you restarted the Foundry server or application
- Make sure that the module folder name matches `icrpg-premium-content` and that it contains the `module.json` file
