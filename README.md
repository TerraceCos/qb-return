# qb-return (public pages for the Intuit app)

Master copy of the small public pages the Intuit developer app needs. Published, only with Tim's approval, to a
separate public repository served by GitHub Pages at https://terracecos.github.io/qb-return/.

| Page | Intuit setting |
|---|---|
| `index.html` | Production redirect URI: `https://terracecos.github.io/qb-return/` (forwards the browser to the local app) |
| `launch.html` | Launch URL and Reconnect URL |
| `disconnect.html` | Disconnect URL |
| `eula.html` | End-user license agreement URL (approved by Tim 10-19-26) |
| `privacy.html` | Privacy policy URL (approved by Tim 10-19-26) |

Rules: no secrets, no scripts or styles from other sites, no tracking. The return page only forwards to
`http://127.0.0.1:3000/intuit/callback`; the code it passes is single-use, short-lived and useless without the app's
client secret, which stays on Tim's computer.
