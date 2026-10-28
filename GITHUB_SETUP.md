# Upload to vdatdv/locket-spotify

Upload all files and the `scripts/` folder to the repository root on branch `main`.

The Locket JS script-path URLs in both .conf and .sgmodule now use:
https://raw.githubusercontent.com/vdatdv/locket-spotify/main/scripts/

The three Spotify script URLs still point to app2smile/rules, because their JS source files are NOT present in the input ZIP. Do not change these URLs to the new repo until you have actually added the corresponding files.

DNS profile uses https://my.ublockdns.com/z451ak95 and is unchanged. A DNS profile does not fetch scripts from GitHub.

To publish from macOS (assuming you already cloned the new empty repo):
cd ~/Downloads/locket-spotify
unzip -o ~/Downloads/locket-spotify_GitHub_ready.zip -d .
git add .
git commit -m "Add Locket Spotify Shadowrocket configuration and DNS"
git push origin main
