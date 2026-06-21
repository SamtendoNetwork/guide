---
prev: true
next: true
---

# SD Preparation

It's time to get the files ready. Please remove your SD Card from your Wii U and insert it into your PC.

### Section I - Deleting conflicting files

Using your favourite file explorer, open up your SD Card's drive. From there, navigate to **SD:/wiiu/environments/aroma/plugins**. What do you see?

::: danger

If you see a file named *Electrode-samtendo.wps*, **STOP** - you already have Samtendo Network installed. Ask for update instructions in the [Samtendo Network Discord server](https://discord.gg/jDKvdtVyzK).

:::

::: danger

If you see a file named *Inkay-pretendo.wps*, you have Pretendo Network installed. Delete this file.

:::

::: danger

If you see a file named *RichPrescence.wps*, delete it as it may interfere with UDP connections. The Samtendo version is provided in Section II if you'd like to redownload it.

:::

::: tip

If you see none of these files, you can continue.

:::

Now navigate to **SD:/wiiu/environments/aroma/modules**. What do you see?

::: danger

If you see a file named *Electrode-samtendo.wms*, **STOP** - you already have Samtendo Network installed. Ask for update instructions in the [Samtendo Network Discord server](https://discord.gg/jDKvdtVyzK).

:::

::: danger

If you see a file named *Inkay-pretendo.wms*, you have Pretendo Network installed. Delete this file.

:::

::: tip

If you see none of these files, you can continue.

:::

You should have now deleted any conflicting plugins that modify your selected network.

### Section II - Downloading files

These files are **required**:

- [Electrode-samtendo.wps](https://github.com/SamtendoNetwork/Electrode/releases/download/v0.0.6/Electrode-samtendo.wps) (Electrode plugin, required to connect to Samtendo Network)
- [Electrode-samtendo.wms](https://github.com/SamtendoNetwork/Electrode/releases/download/v0.0.6/Electrode-samtendo.wms) (Electrode module, required for the plugin to function)

You may choose to download these files, but they are not required:
- [RichPresence](https://github.com/sam51210/RichPresenceWUPS/releases/latest) (Place *RichPresence.wps* in **SD:/wiiu/environments/aroma/plugins**. *discord-script.py* should just be ran on your computer in the background.)

Your folders should now look something like this:

![Plugins folder](/assets/img/guide/plugins.png)
![Modules folder](/assets/img/guide/modules.png)

Now, please safely eject your SD Card and place it back into your Wii U.