# mainsail-theme-elegance

This theme allows you to easily select or create your own colour scheme.

Please edit theme.css to try another colour, animated gradient transition theme, SVG image theme. The screenshots don't do the schemes justice, so please, try each of them out.

## Install
- Create or clear the ".theme" folder inside your Klipper config folder. Example: `~/printer_data/config/.theme/`
- Copy all files from here inside the ".theme" folder.
- Edit custom.css to modify the colour scheme. VSCode has a built in colour picker.
- `background: linear-gradient(225deg, #2CD8D5 0%, #6B8DD6 48%, #8E37D7 100%);`

## Why this theme?
- We found the stock theme a little too dark.
- Certain elements have a higher contrast to lessen them blending.
- Some rarely used elements were distracting being different colours.
- Transparent navigation panels.

## Gallery
Blue theme 1
![image](https://user-images.githubusercontent.com/7228980/202162850-c2c43bc3-233b-4435-92c5-0523ff998a50.png)

Blue theme 2
![image](https://user-images.githubusercontent.com/7228980/202162971-c866a8e4-5797-497e-a236-ac7ac05b153c.png)

Blue theme 3
![image](https://user-images.githubusercontent.com/7228980/202165262-900a656f-c9b7-43d6-bf06-7db31cac6e9e.png)

Purple theme 1
![image](https://user-images.githubusercontent.com/7228980/202164065-e4ecbd42-bd02-40c3-af5e-0032f8b41430.png)

Purple theme 2
![image](https://user-images.githubusercontent.com/7228980/202163763-74a6c389-6389-4f68-bff6-e6cdc324474d.png)

SVG theme
![image](https://user-images.githubusercontent.com/7228980/202162454-886846e6-b922-4ea3-b745-868a47537920.png)

Animated gradient theme
(no image)

## Try out different themes - edit custom.css
```
    /* Find this and uncomment the background colour you'd like */
    main#content {
        background-size: 100% 100%;

        /* Blue theme 1 - Default */
        background: linear-gradient(to left, #8f94fb, #4e54c8);
        /* Blue theme 2 */
        /*background: linear-gradient(45deg, #001f5c, #55bbff);*/
        /* Blue theme 3 */
        /*background: linear-gradient(225deg, #2CD8D5 0%, #6B8DD6 48%, #8E37D7 100%);*/
        /* Purple theme 1 */
        /*background: linear-gradient(45deg, #ab19ff, #9019ff, #5a02ff);*/
        /* Purple theme 2 */
        /*background: linear-gradient(270deg, #9019ff, #b253ff, #5a02ff);*/
    }
    ...
 ```
