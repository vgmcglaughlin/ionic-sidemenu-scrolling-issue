# Ionic Side Menu Android Scrolling Issue

On Android, using `overflow-scroll="true"` on an `ion-side-menu` element's `ion-content` child doesn't allow the contents of the side menu to scroll.

You can check out the tags below to see the difference in behavior.

[Side menu scrolling works in base beta14](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/tree/scrolling-works-beta14)

[Side menu scrolling fails in beta14 nightly build](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/tree/scrolling-broken-beta14-nightly-1102) - the changes in this commit are all from bumping the Ionic version from the base beta14 build to the nightly build

[Side menu scrolling works in beta14 nightly if you use Ionic's custom scrolling](https://github.com/vgmcglaughlin/ionic-sidemenu-scrolling-issue/tree/scrolling-works-beta14-nightly-1102)