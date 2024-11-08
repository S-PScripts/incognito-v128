# incognito-v128
v128 "incognito".

# Requirements:
-> Access to chrome://flags <br>
-> Be on chromeOS v128

# Incognito captive portal

## Getting set up:
1. Go to chrome://flags/#captive-portal-popup-window.
2. Enable it.
3. Restart.
4. If the flag didn’t reset, you can continue. Else you cannot.

## Method A:
1. Go to Settings.
2. Click Wifi in the Network section.
3. Click your wifi.
4. Click Network.
5. Set Name servers to Custom name servers.
6. Set the boxes to 150.136.163.0.
7. A sign-in pop-up should appear from your wifi. Click Sign in.
8. Wait until the white screen goes. This may take a minute. A black background with red borders and yellow button should show.
9. Click the blue "Webview link for tests" text.
10. Set Name servers back to what it was before. You may also need to disconnect and reconnect to your wifi.
11. Wait until Google shows up. This may take a minute.
12. You have successfully completed this exploit.
    
## Method B:
### THIS WILL ONLY WORK IF YOU HAVE A CAPTIVE PORTAL WIFI THAT CAN GET TO GOOGLE. I AM USING EE WIFI IN THE UK.
1. Connect to EE Wifi.
2. A sign in pop up should appear from your Wifi. Click Sign in.
3. CTRL+T is pointless since it now opens a normal tab. You will need to follow the following instructions (and yes, this is the same as the ee-exploit).
4. Accept all cookies.
5. Click Buy Now. You can click any of them.
6. Change your Wifi back.
7. Click the EE icon at the top left of the page. You will be at EE's hotspot home page.
8. Scroll to the bottom. You will see that you can go to the EE STORE. Click Shop now.
9. You will now be at the EE STORE home page. Accept all cookies.
10. Scroll to the bottom and click Privacy policy - this is under the Information header at the right.
11. Click "Please click here to view the BT Privacy Policy."
12. You will now be at BT's privacy policy page. Accept all cookies.
13. Click Contact BT at the bottom of the page - it's at the bottom left.
14. At the bottom of this BT page, click the SMALL Youtube icon - it's at the bottom right.
15. You are now on Youtube! You're very close Click Accept all.
16. In Youtube's sidebar, click Privacy.
17. Scroll to the bottom of Google's privacy page.
18. Click the small Google text.
19. Click Accept Cookies on Google's search page and you have successfully completed this exploit.

## Method C:
#### Requirements:
-> Task manager and end process button unblocked. <br>
-> The ability to change your DNS settings. <br>

1. Go to chrome://flags.
2. Find the temporarily unexpire flag V126 and enable it. Once you've done that, restart.
3. Go back to chrome://flags and search for captive portal. Find the captive portal flag, enable it and restart again.
4. Use any DNS to get a captive portal. You can use the 150.136.163.0 DNS.
5. When you get to the captive portal page, go to task manager.
6. Find incognito tab.
7. Click it and click end process.
8. Go back to your wifi settings and change your DNS back.
9. Go back to the left open captive portal page which is dead because you killed it.
10. Click the blue Learn more button.
11. Go to privacy and policy.
12. Scroll all the way down until you find the Google thing on the bottom left.
13. Click that Google thing and you're done.

# Incognito 'normal' window
1. On the captive portal window, search for openallurls.
2. Go to openallurls.com
3. Put any link.
4. Click on Open all URLs, then click it again.
5. This will open the link as a tab in a normal window which isn't incognito... but it will be unblocked anyway!

## Cool facts/Notes:
- Although the tab isn't incognito, it will not show in history and like I said before it will be unblocked.
- Reloading will not block it.
- Going to other blocked pages on the same tab will not block.
- Clicking on a blocked link that opens in a new tab on this tab will also unblock that blocked link.

## Getting rid of the captive portal
Let's say you don't want to use the captive portal anymore to open each link. Here's a quick bypass:
1. Open the link "openallurls.com" on openallurls.com on the captive portal.
2. You will have an openallurls.com tab, and like I mentioned earlier, if you go to a blocked link that opens in a new tab it will also be unblocked.

## More notes:
- You may notice that if you go to a website you are signed in normally (e.g. outlook) in openallurls.com, you will be signed out. It seems like the 'normal' tab in the window is some sort of hybrid between incognito and not incognito.
- Maybe I should call this exploit UNCOGNITO?

## Credits
- Credits in https://github.com/S-PScripts/incognito-v123
- Credits to S-PScripts (me) for finding these new methods.
- Credits to brandonprather4930 (Brandon Prather) for finding Method 3.
