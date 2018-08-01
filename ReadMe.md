# How to fix iterm2 MacOS keys

Refer to [iTerm 2: How to set keyboard shortcuts to jump to beginning/end of line? Answer](https://stackoverflow.com/a/29403520/1092815).

I followed instructions, took the first suggestion each time and generated this iTerm2 profile.

```bash
git clone https://github.com/GabLeRoux/iterm2-macos-dynamic-profile.git
cd iterm2-macos-dynamic-profile
cp ./fix-iterm2-keys-profile.json ~/Library/Application\ Support/iTerm2/DynamicProfiles
```

* Open iTerm2 Preferences -> Profiles
* Select the new dynamic profile from the list
* Click `Other Actions` -> `Bulk Copy from Selected Profile...`
* Check `Keys` checkbox
* Select your profile
* Hit Copy button
* Enjoy a much better life with your keyboard

![Bulk Copy from Selected Profile...](./doc/bulk-copy-example.png)

![Copy Keys to your profile](./doc/copy-keys-to-new-profile.png)

See [iterm2 dynamic profiles documentation](https://www.iterm2.com/documentation-dynamic-profiles.html) for more details.