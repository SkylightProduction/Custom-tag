# Custom tag
### Custom tag is a datapack that allows you to create your own tag for any item(s).

### What is a tag for and what is it?
A tag is used to create a specific area that contains certain information. Example: a tag `#minecraft:planks` (or `forge:planks`) would only contain information about all planks.
It is mostly used in crafting recipes. When you view a recipe for crafting a solar panel from IC2 in JEI or REI, do you see the blocks of glass sort of shimmering? That is the tag, that is the block to which the `#forge:glass` tag is assigned, and it means that the solar panel can be created from any glass, from any mod. If you create a mod that has a glass block and don't give it a tag, you can't create a solar panel of glass from your mod.
But why would you create a tag for yourself, and even more so why would you give it to an object? You may want to open portal in Twilight forest with diamond, planks and neserite. And that all of these options are available at any given moment. Almost the same example you can give for crafting recipes.

### Guide:
- [Download and open the archive.](https://github.com/SkylightProduction/Custom-tag/releases/tag/CT)
- Go to: data/abobka/tags/items (The folder "abobka" can be named as you like.)
- Open the file "file.json" (you can also name it whatever you want)
- Instead of minecraft:diamond write the item you want.

In order to get the details of the item you want to replace the diamond with.
This can be done by typing on your keyboard combination F3+H (when Minecraft is on), and hovering over the desired item in your inventory.

![](https://cdn.discordapp.com/attachments/1014200166473023540/1061988799753756682/2023-01-09_18.20.4467.png)

- You can add more than one item. Simply write a second, third, and so on exactly below the item you just wrote down. Don't forget the inverted commas and commas. Use Visual studio code for quicker error correction. You can also see an example code, [here](https://www.curseforge.com/minecraft/customization/custom-tag/screenshots).

### How do I recognise a tag that has just been created?
Install the [CraftTweaker](https://www.curseforge.com/minecraft/mc-mods/crafttweaker) mod, pick up the item(s) you've added to the tag and type the command `/ct hand` into chat.
After executing this command, you may get a lot of text (or little) written into your chat. You want the text that is written in blue. Among all of this, find the tag that uses the name of your folder. (In my case it's the "abobka" folder).

![](https://cdn.discordapp.com/attachments/1014200166473023540/1062256885333512212/2023-01-10_132912.png)
![](https://cdn.discordapp.com/attachments/1014200166473023540/1062257080444125184/2023-01-10_1329128.png)

##### (I don't know English well, so I used a translator. Sorry if there are mistakes.)
