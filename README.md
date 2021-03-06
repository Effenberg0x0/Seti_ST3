# Seti

`SublimeText 3 Theme` Port of Seti_UI by [jesseweed](https://github.com/jesseweed/seti-ui)

### Seti

![Seti Screenshot](./Resource/screenshot-1.png)

### Seti_orig

![Seti Screenshot](./Resource/screenshot-2.png)

## Notes

* Any thing less than 'ST3 Build 3062' wont get the sidebar icons to work.
* if you used any of the resources in this repo into your own release ,plz appreciate the hard work and mention the original authors.
* A New/Better syntax Highlight released under [Seti_UX](https://sublime.wbond.net/packages/Seti_UX).
* [Seti_JetBrains](https://github.com/zchee/Seti_JetBrains) by [zchee](https://github.com/zchee) :tophat:.

## Install

### Via Package Control

Theme is listed as [Seti_UI](https://packagecontrol.io/packages/Seti_UI) on Will Bond's [Sublime Package Control](https://packagecontrol.io).

### Manual

1. [Download the .zip](https://github.com/ctf0/Seti_ST3/archive/master.zip).
2. Unzip and rename the folder to `Seti_UI`.
3. Copy the folder into `Packages` directory, which you can find using the menu item `Preferences -> Browse Packages...` in Sublime Text.
4. copy the (Resource/fold.png) "or edit it to ur liking" to `Packages/Theme - Default` to override the default code folding icon.

## Setup

Activate the `Theme` by modifying your user preferences file, which you can find using the menu item `Preferences -> Settings - User` in Sublime Text or use `Schemr` & `Themr` by [Ben Weier](https://github.com/benweier).

### Example settings

```json
{
    "theme": "Seti_orig.sublime-theme"
}
```

#### Options

`Themr` have an option call ``Themr: Toggle Theme Settings`` to change theme settings on-the-fly , or manually add what you need from below.
* note that not all the settings are available in both themes.

```js
// tabs
  "Seti_no_blue_bar"               // remove the blue bar under the un-saved tabs "not available with accents"
  "Seti_tabs_small"                // tabs height = 35
  "Seti_tabs_med"                  // tabs height = 40
  "Seti_tabs_big"                  // tabs height = 54
  "Seti_tabs_no_min_width"         // (issues/223)
  "Seti_tab_font_12"               // tab font size = 12
  "mouse_wheel_tabswitch"          // scroll through opened tabs
  "Seti_no_scroll_icons"           // remove the l/r arrows & the drop down list button, effective when ("enable_tab_scrolling": true)
  "Seti_orange_button"             // change un-saved blue tab buttons to orange

// tab label
  "Seti_blue_label"                // change the un-saved tab label to blue
  "Seti_orange_label"		       // change un-saved label color to orange
  "Seti_bold_slctdtab_labels"      // make active tab label font in bold

// scrollbar
  "Seti_SB_med"                    // scrollbars width / height = 6
  "Seti_SB_big"                    // scrollbars width / height = 10
  "Seti_SB_blue"                   // scrollbars in blue
  "Seti_SB_orange"                 // scrollbars in orange

// sidebar
  "Seti_ClosedFolder_same"         // same icon as the Opened_folder
  "Seti_ClosedFolder_remove"       // remove closed_folder icon
  "Seti_ClosedFolder_dots"         // change closed_folder icon to dot
  "Seti_ClosedFolder_anim"         // animate closed_folder icon (available with accents)
  "Seti_sb_small_padding"          // sidebar entries padding = 3
  "Seti_sb_big_padding"            // sidebar entries padding = 10
  "Seti_sb_tree_med"               // sidebar tree padding = 15
  "Seti_sb_tree_small"             // sidebar tree padding = 10
  "Seti_sb_tree_tiny"              // (issues/88)
  "Seti_sb_tree_miny"              // (issues/88)
  "Seti_show_group_arrows"         // show the folder/group arrows in sidebar
  "Seti_sb_no_icons"               // (issues/133)
  "Seti_sb_blank"                  // (issues/133)
  "Seti_bold_slctdfile_labels"     // make the sidebar selected file text in bold
  "Seti_sidebar_font_size_12"      // (issues/115)
  "Seti_sidebar_font_size_13"      // (issues/115)
  "Seti_sidebar_font_size_14"      // (issues/115)
  "Seti_sidebar_font_Ubuntu"       // (issues/115)
  "Seti_sidebar_font_Fira"         // (issues/115)
  "Seti_sidebar_font_Hack"         // (issues/115)
  "Seti_sidebar_font_Source"       // (issues/115)
  "Seti_heading_font_12"           // heading font size = 12
  "Seti_bold_heading"              // make heading font in bold
  "Seti_top_heading_big"           // sidebar top header img
  "Seti_top_heading_small"         // sidebar top header img small
  "Seti_top_heading_anim"          // sidebar top header img animate on hover "not available with accents"
  "Seti_alt_tree_row"              // alternative sidebar row highlight

// view
  "Seti_pad_5"                     // use with line_padding_bottom / line_padding_top = 5
  "Seti_pad_3"                     // use with line_padding_bottom / line_padding_top = 3
  "Seti_panel_nrml"                // remove the padding top/down from quick panel

// accents
  "Seti_accent"                    // general options for accents
  "Seti_accent_yellow"
  "Seti_accent_red"
  "Seti_accent_indigo"
  "Seti_accent_purple"
  "Seti_accent_teal"
  "Seti_accent_lime"
```

## Credits

* Ported based on `Glacier` by [joeyfigaro](https://github.com/joeyfigaro/glacier-theme) among many others.
* Special thanx for [Anthony Garand](https://github.com/garand) for the widget files (took me 2 days to understand what they actually do O_o and fix the god dame text input thing).
* `ScopeHunter` by [facelessuser](https://github.com/facelessuser) "YOU ROCK".
* `ColorSchemeEditor` by [Borislav Peev](https://github.com/bobef) "HOF".
* `Neon` by [Matt Morrison](https://github.com/MattDMo/Neon-color-scheme) "HOF".
* `Cyanide` by [lefoy](https://github.com/lefoy/cyanide-theme) "HOF".

## Differences from the original

* No file icon in the opened tabs, ST lacks this.
* Current line number highlight color, ST lacks this.

## Issue A Ticket

1. What version of ST are you using? (nothing lower than 3062).
2. Have you restarted ST after you installed the theme?
3. If you still have bad render, have you removed the cache folder (found right next to the packages folder)?
4. Have you copied the files from the `Ext` folder to your User folder?
