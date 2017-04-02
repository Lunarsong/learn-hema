---

---
<link rel="import" href="/bower_components/polymer/polymer.html">

<link rel="import" href="/bower_components/paper-styles/demo-pages.html">
  <link rel="import" href="/bower_components/paper-menu/paper-menu.html">
  <link rel="import" href="/bower_components/paper-menu/paper-submenu.html">
  <link rel="import" href="/bower_components/paper-item/paper-item.html">
  <link rel="import" href="/bower_components/paper-button/paper-button.html">
  <link rel="import" href="/bower_components/iron-collapse/iron-collapse.html">

<dom-module id="navigation-bar">
  <template>
<style is="custom-style">
    .horizontal-section {
      padding: 0 !important;
    }

    .avatar {
      display: inline-block;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      overflow: hidden;
      background: #ccc;
    }

    paper-item {
      --paper-item: {
        cursor: pointer;
      };
    }

    .sublist paper-item {
      padding-left: 30px;
    }

    .sublist2 paper-item {
      padding-left: 50px;
    }

    .paper-item-link {
    color: inherit;
    text-decoration: none;
  }
  </style>
        <paper-menu attr-for-item-title="label" multi>
          <paper-submenu>
            <paper-item class="menu-trigger">Guards</paper-item>
              <paper-menu class="menu-content sublist">
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Vom Tag</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Ochs</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Pflug</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Alber</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Zornhut</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Langort</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Wechsel</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Nebenhut</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Eisenport</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Hangetort</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Schlüssel</paper-item>
                </a>
                <a class="paper-item-link" href="#inbox" tabindex="-1">
                  <paper-item>Einhorn</paper-item>
                </a>
              </paper-menu>
            </paper-submenu>
              <paper-submenu>
                <paper-item class="menu-trigger">Strikes</paper-item>
                <paper-menu class="menu-content sublist2">
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Oberhau / Over Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Unterhau / Under Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Mittelhau / Middle Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Zornhau / Wrath Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Schielhauw / Squinting Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Krumphauw / Crooked Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Zwerchhau / Thwart Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Kurtzhauw / Short Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Glützhauw / Slide Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Prellhauw / Bounce Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Blendthauw / Blind Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Windthauw / Wound Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Kronhauw / Crown Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Kniechelhauw / Knuckle Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Sturzhauw / Plunge Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Wechselhauw / Change Strike</paper-item>
                  </a>
                  <a class="paper-item-link" href="#inbox" tabindex="-1">
                    <paper-item>Zeckrur / Twitch Strike</paper-item>
                  </a>
                </paper-menu>
              </paper-submenu>
          </paper-menu>
        </paper-submenu>
      </paper-menu>

  </template>

  <script>

    Polymer({

      is: 'navigation-bar'

    });

  </script>

</dom-module>