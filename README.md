# Coded Glass
_Coded Glass_ explores the urgency of the #metoo movement, the role of social technology, and the ways in which individual narratives can shape the web as a form of community building and reflection through stained glass imagery, a rich art historical material. Using collected data and analysis of 2,629,581 #metoo tweets from October 1, 2017 to August 15, 2018 as source material, this visual exhibit by artist and activist [Liss LaFleur](https://www.lisslafleur.com/) showcases stained glass windows of protest signs, emojis, and hashtags from the #metoo movement as a form of data visualization and metaphor for creating communal sacred spaces.

## About
_Coded Glass_ is a web-based visual application built at NCSU Libraries as part of the [Immersive Scholar project](https://www.immersivescholar.org/) and is responsively designed for exhibit across a diverse range of large-scale displays. _Coded Glass_ is primarily featured in the [iPearl Immersion Theater](https://github.com/NCSU-Libraries/visualization_templates/blob/master/HuntLibraryVideoWallGuide.md#ipearl-immersion-theater) at the James B. Hunt Jr. Library at NC State University.

This application was built using Webpack 3 and is optimized to run in the Chrome browser. It is designed for both non-interactive large-scale displays and interactive personal devices (i.e. desktops, laptops, tablets, and phones) but not optimized for all sizes and aspect ratios yet.

_Coded Glass_ is hosted on GitHub Pages and can be run via the following link: https://immersive-scholar.github.io/coded-glass/.

## Large-scale display specifications and guidelines
Here, a "large-scale display" is defined as a screen with a viewport height greater than or equal to 2100px (vh ≥ 2100px). Anything below 2100px high is considered a "personal device" screen size.

The properties below indicate considerations with regard to optimal display of this content on large-scale displays.

**Content type:** web application available via URL

**Required software:** modern web browser (Chrome suggested)

**Optimal aspect ratio range:** 8:5 - 4:1 (square to landscape)

**Optimal screen width:** 2500px - 10000px

**Optimal screen height:** 2100px - 3000px

**Optimal viewing distance:** near to moderate distance

## Environmental differences
**Large-scale:** The large-scale display is designed for non-interactive video walls and plays automatically. It begins at the index page with thumbnails of the windows, which are randomly ordered each time the display is loaded. The order they are displayed in in the matrix determines the order that they will be played in. After a minute elapses, the display starts to play the slideshows of each window in the specified order. Each image in the slideshow is zoomed in on and panned across so viewers can see the details of the glass. Once all the windows have been played, the display will return to the index page. The display continuously loops between the slideshows of each window and the index page.

**Personal-sized:** The personal-sized display is designed for smaller, interactive devices, such as desktops, laptops, and handhelds. Hovering over a window's image will display the window's title. Clicking/tapping on a thumbnail will play that window's slideshow. The user can choose which windows they want to play.

## Authors
Liss LaFleur

Jasmine Lang

Walt Gurley
