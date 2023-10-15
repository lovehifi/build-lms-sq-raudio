# Build LMS-rAudio for Pi 2 and Pi 3

This guide explains how to build LMS-rAudio for Raspberry Pi 2 and Pi 3. Follow the steps below to set up LMS-rAudio.

## Instructions

1. **Flash rAudio IMG:**
   Flash the rAudio IMG to your memory card.
>
> https://github.com/rern/rAudio
>
> https://github.com/rern/rAudio/releases
>
2. **Install script LMS and Squeezelite (32bit):**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/raudiolms-32bit/main/install-archlinux.sh | sh

3. **Update script LMS and Squeezelite (32bit):**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/raudiolms-32bit/main/update | sh

4. **Tidal Connect for rAudio:**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/tidal-raudio/main/install.sh | sh

5. **Activate Material Skin Plugin:**
   To activate the Material Skin plugin, follow these steps:
   - Open LMS at http://ip:9000 or http://raudio:9000
   - Navigate to the menu: Server > Basic Settings > Plugins
   - Activate the Material Skin plugin

6. **BubLMSV9 (Connect to BubbleUPnP Server):**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/lmsbub9/main/install.sh | sh

7. **Material Skin Mod:**
   ```bash
   wget -O- https://raw.githubusercontent.com/lovehifi/picoreaddon/main/mskin | sudo sh

8. **12-band Parametric EQ Eqfa12 LMS:**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/addraudio/main/eqfa12lms32 | sh

9. **Configure GUI LMS:**
   ```bash
   wget -O - https://raw.githubusercontent.com/lovehifi/addraudio/main/configgui | sh
