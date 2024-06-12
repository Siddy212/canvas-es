# Canvas (ES Version)
Canvas is a theme for Emulation Station (Batocera/Knulli) that aims to provide a modern and easy to use interface with a variety of color schemes. It also provides easy customization for users to swap out wallpapers/art to their own liking.

This is a port of the EmulationStation-DE theme Canvas-es-de located [here](https://github.com/Siddy212/canvas-es-de).

## **Preview**

| System View | Gamelist View |
| --- | --- |
|![Main-System](https://github.com/Siddy212/canvas-es/assets/60283021/145a9266-0c50-4f3a-975b-73a5f77afb09)|![Detailed-Dark](https://github.com/Siddy212/canvas-es/assets/60283021/d10fd39a-e451-40f2-b601-ef5bbefd7a4c)|




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
      - `16:10` (In Process)
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
           
   - `Metadata` - enables you to disable the game details and only display the image.
      - `On`
      - `Off`
     
   ## **Gamelist Theme Options**
     
   - `Metadata Image Type` - enables you to change the image above the metadata.
      - `Image` - Show only the scraped game image.
      - `Miximage` - Compile a Miximage with boxart, marquee, and screenshot.
           
   - `Automatic Grid Size` - enables you to change the number of rows for the `Grid` view when `Default Grid Size` is set to `Automatic`. It will scale correctly to optimize screen space per system.
      - `2 Rows`
      - `3 Rows`
      - `4 Rows`
      - 
     - `Automatic Grid-Detailed Size` - enables you to change the number of columns for the `Grid-Detailed` view when `Default Grid Size` is set to `Automatic`. It will scale correctly to optimize screen space per system.
      - `2 Rows`
      - `3 Rows`
      - `4 Rows`
     
### **Preview of Variants and Color Schemes**

| Color | Variant | SystemView | GamelistView |
| :---: | :---: | :---: | :---: |
|Retro|[Grid] Grid: Simple|![MainRetro](https://github.com/Siddy212/canvas-es-de/assets/60283021/ffa38fa6-6aba-4563-a007-65621c5585a6)|![GameRetroLarge](https://github.com/Siddy212/canvas-es-de/assets/60283021/efd77be4-7e98-4e46-a4e8-8ad694df7f8f)|
|[Icon] Dark| [Carousel] Textlist|![MainDarkIcon](https://github.com/Siddy212/canvas-es-de/assets/60283021/1a0442fc-dccc-4113-a394-5a70b58925d0)|![GameDark](https://github.com/Siddy212/canvas-es-de/assets/60283021/128df83f-62c2-4a00-be07-bcd1d125d219)|

### Preview of Font Sizes 

| Small | Medium |
| :---: | :---: |
|![Small](https://github.com/Siddy212/canvas-es-de/assets/60283021/8a78e2d6-99de-4cf9-a088-2791c065b07d)|![Medium](https://github.com/Siddy212/canvas-es-de/assets/60283021/7354e1a5-cc59-481a-a01a-0b626699a63a)|
| **Large** |

## **Theme Customizations**

This theme allows customizations to artwork without the need to edit the source XML. 

### Wallpapers
- Use the folder called `wallpapers` in ES-DE's theme directory at: `share/themes/canvas-es`
- Inside are .webp images named after the color schemes.
- Save over any of these with your new wallpaper to change that color scheme look.
- Alternate wallpapers are also stored in the "Alternate" folder as an example.


## **Acknowledgments**

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
