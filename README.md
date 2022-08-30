# Git-Proxy-Issue
Git Proxy Issue when you try to clone the repo in local

# Check the proxy in the global level and unset
git config --list --global --show-origin

git config --global --unset http.proxy

git config --global --unset https.proxy

# Check the proxy in the local and unset
git config --list --local --show-origin

git config --unset http.proxy

git config --unset https.proxy

# Check the proxy in system and unset
git config --list --system --show-origin

git config --system --unset http.proxy

git config --system --unset https.proxy

# Finally if nothing works, Check the System->Environment Variables and Unset

http_proxy in System Variables

# Commands to unset values

git config --global --unset http.proxy

git config --unset http.proxy

http_proxy=""
