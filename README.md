# Canvas (ES Version)
Canvas is a theme for Emulation Station (Batocera/Knulli) that aims to provide a modern and easy to use interface with a variety of color schemes. It also provides easy customization for users to swap out wallpapers/art to their own liking.

This is a port of the EmulationStation-DE theme Canvas-es-de located [here](https://github.com/Siddy212/canvas-es-de).

### **Preview of some of the Variants, Font Sizes, and Color Schemes**

| Color | Variant | SystemView | GamelistView |
| :---: | :---: | :---: | :---: |
|Retro| System Grid & Grid|![VirtualBox_Batocera_v39_22_06_2024_10_51_59](https://github.com/Siddy212/canvas-es/assets/60283021/4c845459-2a4d-44fa-aa74-ca5d1b5f97b6)|![VirtualBox_Batocera_v39_22_06_2024_10_52_33](https://github.com/Siddy212/canvas-es/assets/60283021/3fb78fba-dc39-4c79-9865-b9f26263e0ca)|
|Neon| System Carousel & Detailed: Grid|![VirtualBox_Batocera_v39_22_06_2024_10_54_28](https://github.com/Siddy212/canvas-es/assets/60283021/5d836900-edaf-4a93-b1da-4f7de2387de4)|![VirtualBox_Batocera_v39_22_06_2024_10_56_07](https://github.com/Siddy212/canvas-es/assets/60283021/c047cd70-54bd-43a8-a1d5-9a790c13a7ab)|
|Pastel| System Carousel & Detailed|![VirtualBox_Batocera_v39_22_06_2024_10_44_18](https://github.com/Siddy212/canvas-es/assets/60283021/5e9c6ff2-e5e9-4cc0-ba54-30d9aa6fe46b)|![VirtualBox_Batocera_v39_22_06_2024_10_48_44](https://github.com/Siddy212/canvas-es/assets/60283021/6481ea4a-ac52-40e2-bd24-be190264ed63)|
|Light| System Grid & GameCarousel|![VirtualBox_Batocera_v39_22_06_2024_10_57_50](https://github.com/Siddy212/canvas-es/assets/60283021/3f9baa51-aecf-48e5-87a0-a5df214e2d15)|![VirtualBox_Batocera_v39_22_06_2024_10_57_25](https://github.com/Siddy212/canvas-es/assets/60283021/5ab2ef59-b85b-42a6-ba92-25f03789d57c)|

# **Configuration Options**


- This theme has a simple set of options that can be changed directly from the UI Settings menu of EmulationStation.
   ## **Gamelist Style**
   - `Gamelist View Style` - sets the style of the gamelist View.
      - `Detailed` - A simple text list of games and metadata on the left.
      - `GameCarousel` - A carousel of game marquees and metadata on the left.
      - `Grid` - A grid of boxart and minimal metadata below for games. No metadata images.
      - `Grid-Detailed` - A grid of boxart and detailed metadata on the left for games.
     
   - `Default Grid Style` - Sets the rows/columns of the grid views. The theme will scale optimally based on the `Automatic Grid Rows/Columns` below if left as `Automatic`.
     
    ## **Theme Options**
   - `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
      - `16:9`
      - `4:3`
      - `16:10`
      - `1:1` (In Process)
    
    - `Distribution` - sets the file path for customization files to be accessed.
      - `Retrobat`
      - `Batocera/Knulli`
   
   - `System View` - sets the style of the System View.
      - `Grid` - A system grid with either System Icons or Game Artwork.
      - `Carousel` - A system carousel with either System Icons or Game Artwork.
   
   - `System Grid Size` - sets the size of the `Grid` within the System View.
      - `Automatic` - Recommended sizing based on your aspect ratio.
      - `3x1, 3x2, 3x3, 4x2, 4x3, 4x4, 5x4` - Other available sizes.
      
   - `System Icon Style` - sets the style of the icons in the System View
      - `Art` - Box of iconic art for each system with Logo beneath.
      - `Icons` - Controller and Logo for each system.
     

   - `Theme Color Scheme` - There are 8 color schemes to choose from that each change the color palette and wallpaper of the theme across all views. Each wallpaper can easily be swapped out by the user for further customization. Alternate options are included within the theme as examples:
     
      - `Light` - A light grayscale color scheme.
      - `Dark` - A dark grayscale color scheme.
      - `Neon` - A retro neon color scheme.
      - `Pastel` - A light and bright color scheme.
      - `Sony` - A blue/white style using PSP colors.
      - `SNES` - A gray/purple style using Super Nintendo colors.
      - `Famicom` - A red/gold style using Nintendo Famicom colors.
      - `Retro` - A striped vintage color scheme.
      - `Custom` - Directs to the theme-customizations folder for your `Distribution`. Custom `colors.xml`, `Art` folders, `Icon` folders, and a `wallpaper` can be set.
    
   - `Theme Font Size` - enables you to change the size of the fonts displayed in the theme. It will also scale the size of the system carousel.
      - `Small` - good for display on tvs and  large handheld screens at 6 inches or larger.
      - `Medium` - good for display on handheld screens at 3.5 inches or larger.
      - `Large` - good for display on small handheld screens at 3.5 inches or smaller.
   
        
   - `Metadata` - enables you to disable the game details and only display the image.
      - `On`
      - `Off`
           
   - `Metadata Rating/Playtime` - A toggle to either display the game's metacritic rating or your playtime.
      - `Rating`
      - `Playtime`
     
   ## **Gamelist Theme Options**
     
   - `Metadata Image Type` - enables you to change the image above the metadata.
      - `Image` - Show only the scraped game image.
      - `Miximage` - Compile a Miximage with boxart, marquee, and screenshot.
           
   - `Automatic Grid Size` - enables you to change the number of rows for the `Grid` view when `Default Grid Size` is set to `Automatic`. It will scale correctly to optimize screen space per system.
      - `Automatic` - Will select an optimized row choice for your aspect ratio.
      - `2 Rows`
      - `3 Rows`
      - `4 Rows`
        
   - `Automatic Grid-Detailed Size` - enables you to change the number of columns for the `Grid-Detailed` view when `Default Grid Size` is set to `Automatic`. It will scale correctly to optimize screen space per system.
      - `Automatic` - Will select an optimized column choice for your aspect ratio.
      - `2 Columns`
      - `3 Columns`
      - `4 Columns`
     



## **Theme Customizations**

This theme allows customizations to artwork without the need to edit the source XML. This follows the default Art-Book-Next customization directions for alignment.
Make sure the Distribution setting is set to the correct value for your current OS (e.g. Batocera/Knulli or RetroBat)
- This value determines the folder where you will add your customizations:
   - `Batocera/Knulli` = /userdata/theme-customizations/canvas/
   - `Retrobat` = C:\RetroBat\emulationstation\.emulationstation\theme-customizations\canvas\

Create the folders that match your distribution and then move on to the options below...

### System View Art
- Create the folder called `artwork` in the theme customization directory chosen above.
- Create your custom artwork as a 1-1 aspect ratio square image.
- Export your final images as webp, pngs, or jpgs.
- They can be named:
   - ${system.theme}.webp
   - ${system.theme}.png
   - ${system.theme}.jpg
- The theme will look them them up in that order. If a given image is not found in your folder then the the images from the theme will be used as a fallback. This allows you to customize only the images you want and still have images displayed for all systems.
- ${system.theme}.webp should be named for the system you are looking to override. For example if you wanted to override the artwork for snes you would create an image called snes.webp in the artwork folder. Once your images are in place you turn on custom images by changing the `System Icon Style` setting to `Custom (Art)`.

### System View Icons
- Create the folder called `icons` in the theme customization directory chosen above.
- Create your custom icon following the other systems location and size.
- Export your final images as webp or pngs.
- They can be named:
   - ${system.theme}.webp
   - ${system.theme}.png
- The theme will look them them up in that order. If a given image is not found in your folder then the the images from the theme will be used as a fallback. This allows you to customize only the images you want and still have images displayed for all systems.
- ${system.theme}.webp should be named for the system you are looking to override. For example if you wanted to override the icons for snes you would create an image called snes.webp in the icons folder. Once your images are in place you turn on custom images by changing the `System Icon Style` setting to `Custom (Icons)`.

### Wallpapers and Color Schemes
- Locate the folder `wallpapers` within Emulation Stations' theme directory at: `share/themes/canvas-es/wallpapers`
- Inside are .webp images named after the color schemes.
- Save over any of these with your new wallpaper (or a new jpg image) to change that color scheme look.
- Alternate wallpapers are also stored in the "Alternate" folder as an example.

- Alternatively, use the color scheme `Custom` to point to a .jpg or .webp file named `custom` within `theme-customizations\canvas\wallpapers` as determined by the distribution choice above. The theme will default to `themes\canvas-es\wallpapers\custom` if no wallpaper is found.
- Choosing `Custom` also allows a new color scheme to be created within  `theme-customizations\canvas\colors.xml`. If no file is present, it will default to the custom color scheme within `themes\canvas-es\colors.xml` however this will be overriden if the theme is updated. 


## **Acknowledgments**

**Code structure, file layouts, tips, and theme paths** were guided by the outlines from [Ant - ArtBookNext](https://github.com/anthonycaccese/art-book-next-es)

**Artwork was designed and created by the following artists and credit is provided to them.**
   - A lot of the original artwork and layouts were designed and created by [fagnerpc](https://github.com/fagnerpc)
   - Light/Dark wallpaper by [Pretty In Pixel](https://prettyinpixel.wordpress.com/page/2/)
   - Retro wallpaper by [Hadair Ahmad](https://www.vecteezy.com/members/aspctstyle)
   - Sony wallpaper by [Winterbird](https://www.deviantart.com/winterbird/art/PSP-wallpaper-24161542)
   - Pastel wallpaper by [simax-jr](https://www.reddit.com/r/dbrand/comments/ypa90k/palettes_design_as_wallpaper_at_4k_res_3840_x/)
   - Donkey Kong Country 2 art for SNES: Created by [Renato Giacomo](https://www.artstation.com/renatogiacomini)
   - Yoshi Mario Kart on Wii: Modifications made to art by [Yoshiyaki](https://www.deviantart.com/yoshiyaki) & [Renato Giacomo](https://www.artstation.com/renatogiacomini)
   - Delfino Plaza wallpaper on Gamecube: Created by [Vincent Moubeche](https://www.artstation.com/artwork/Xn4Xo3)
   - Mario on Gamecube: Created by [SonicJeremy](https://www.deviantart.com/sonicjeremy)
   - Tyranitar for GBC Hacks: [Chris Silva](https://www.artstation.com/artwork/obBlyB)
   - Wallpaper for Gameboy Hacks: [trollkarl3] (https://www.deviantart.com/trollkarl3/art/Realistic-Super-Mario-Bros-1-first-stage-Wallpaper-375538304)
   - Haohmaru for ngp - [jlcryu](https://www.deviantart.com/jlcryu/art/Haohmaru-919703925)
   - Glados for Steam - [EliteRobo](https://www.deviantart.com/eliterobo/art/Portal-SFM-Simple-GLaDOS-Render-794265716)
   - ScummVM Classic - [mikimontllo](https://twitter.com/mikimontllo)
   - System Icons (Dragon32, BBCMicro, etc) - [PangolinWrestler](https://github.com/PangolinWrestler)
   - Other publicly available wallpapers or characters are credited to their original creators.
     
## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
