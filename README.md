# SOHO Router Administration Simulator

A self-contained educational networking game that simulates configuring a small office/home router.

## Run locally
Open `index.html` in any modern browser.

## Publish with GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` (and optionally this README).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. GitHub will provide the public Pages address after deployment.

No server, database, npm install, or build process is required.

## A+ Troubleshooting Scenarios
The simulator now includes APIPA/DHCP failure, DNS/name-resolution failure, and WAN/Internet connectivity troubleshooting tickets with instant student feedback.

## LAN Troubleshooting Update
The LAN setup now begins with an intentional misconfiguration:
- Router: 192.168.1.1 / 255.255.255.0
- Broken DHCP pool: 192.168.2.100–192.168.2.150

Students must recognize that the DHCP pool is on the wrong /24 subnet and repair it before the router accepts the LAN configuration.
