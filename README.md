# Ionic Side Menu Android Scrolling Issue

On Android, using `overflow-scroll="true"` on an `ion-side-menu` element's `ion-content` child doesn't allow the contents of the side menu to scroll.

You can check out the commits below to see the difference in behavior.

[Side menu scrolling works in base beta14](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/commit/ac1962c73ab779a550545716f881d8e1f89d394f)

[Side menu scrolling fails in beta14 nightly build](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/commit/0da0bc6321942e956c7df9179157adff5c237d80) - the changes in this commit are all from bumping the Ionic version from the base beta14 build to the nightly build

[Side menu scrolling works in beta14 nightly if you use Ionic's custom scrolling](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/commit/0ebcc2b7a73896c10b532d3dbc9c39097536c89d)