# GitHub user site (AdMob `app-ads.txt`)

AdMob requires this file at **`https://patguettler.github.io/app-ads.txt`** (domain root), not under `/unicorn-arcade/`.

## One-time setup

1. On GitHub, create a **new public repository** named exactly: **`patguettler.github.io`** (under account **PatGuettler**).
2. Do **not** add a README (empty repo).
3. From this machine:

```bash
cd /home/pat/dev/patguettler.github.io
git push -u origin main
```

4. In GitHub → repo **Settings → Pages** → Source: **Deploy from branch** → **main** → **/ (root)**.
5. Confirm in a browser: `https://patguettler.github.io/app-ads.txt` shows:

```text
google.com, pub-2846735043546429, DIRECT, f08c47fec0942fa0
```

6. In AdMob → **Verify app** → **Check for updates**.

## Play Console

Set store **Website** to **`https://patguettler.github.io`** (or ensure it uses that domain) so it matches the `app-ads.txt` host.

**Shared privacy policy (all Grapegames apps):**

- Privacy policy: `https://patguettler.github.io/privacy-policy.html`
- Data deletion URL: `https://patguettler.github.io/privacy-policy.html#data-deletion`

Use those URLs in Play Console for Unicorn Arcade, Peregrine, Pigeon, and future apps unless an app needs its own policy.

Unicorn Arcade’s game site remains at `https://patguettler.github.io/unicorn-arcade/`.
