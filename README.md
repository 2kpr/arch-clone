# arch-clone
Clones and creates a bootable iso from an existing Arch installation

Install by git cloning this repo somewhere
<br /><i>(I usually place it in /tmp so that it isn't 'picked up' during the cloning process)</i>
```
git clone https://github.com/2kpr/arch-clone
```

Then make sure to view and edit to your liking at least the 2 included config files:
```
- settings.conf, which handles the basic config options/paths
- exclude.conf, which lists the files/folders excluded during creation of the iso
```

When you have the settings to your liking just run it
```
sudo ./arch-clone
```