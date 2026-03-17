# losmuertos-stylus

Custom CSS overrides for the [Stylus](https://github.com/openstyles/stylus) browser extension. These styles target sites that don't expose their own theming options.

---

## Styles

| Style | Description |
|-------|-------------|
| [Dockhand Dark](https://cdn.jsdelivr.net/gh/StelianMorariu/losmuertos-stylus@main/styles/dockhand-true-dark.user.css) | True Dark mode for [Dockhand](https://dockhand.pro/) — pushes all backgrounds to near-black (#111 and below), styles the sidebar, header, data grid, modals, dropdowns, inputs, tabs, terminal pane, and scrollbars |
| [Shlink Modern Dark](https://cdn.jsdelivr.net/gh/StelianMorariu/losmuertos-stylus@main/styles/shlink-modern-dark.user.css) | Modern dark theme for the [Shlink](https://shlink.io/) web client — dark surfaces with Shlink's blue accent, styles the navbar, sidebar, cards, tables, forms, buttons, badges, dropdowns, modals, tabs, pagination, alerts, and scrollbars |

---

## How to use with Stylus

1. Install the [Stylus extension](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) for Chrome (or the equivalent for your browser).
2. Click the style name in the table above — Stylus will intercept the request and show an install dialog.
3. Click **Install style**.
4. In the Stylus editor, update the `@-moz-document domain(...)` value to your instance's domain or IP.
5. Click **Save**.

---

## Refreshing / updating styles

Styles include an `@updateURL` pointing to the jsDelivr CDN. To check for updates:

1. Open the Stylus dashboard and click **Check all styles for updates**.
2. If a newer version is available, Stylus will prompt you to update.
