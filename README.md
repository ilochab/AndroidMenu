AndroidMenu
===========

Android style menu app skeleton


Code skeleton to implement an Android app with kivy's ActionBar and side panel menu using Alexander Taylor's work downloaded from https://github.com/kivy-garden/garden.navigationdrawer.

You have a main_panel that shows on your screen that has an action-bar on the top and an app-area over the other part of the screen.

Touching the left part of the action-bar you'll show a side panel menu with a list of menu items. Each one of them sustitutes the main app panel with its own specific panel anf hides the side panel again. 
In the far right of the bar you'll find the exit button.

Into SidePanel_AppMenu dictionary you configure the correspondance between menu items descriptions and methods that actually implement the specific function and function specific panels to be shown instead of the first main_panel

SidePanel_AppMenu = {'MenuItemText1':['AppMenu_METHOD_1',None],
                     'MenuItemText2':['AppMenu_METHOD_2',None],
                     'MenuItemText3':['AppMenu_METHOD_3',None],
                     }
                     
                     
