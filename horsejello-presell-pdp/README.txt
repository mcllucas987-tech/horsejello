HORSE JELLO FUNNEL

Structure:
/index.html       = Horse Jello age-verification presell
/pdp/index.html   = Horse Jello product page
/pdp/images       = PDP assets
/pdp/fonts        = PDP fonts
/pdp/video        = PDP videos

Flow:
Traffic -> /index.html -> YES -> /pdp/ -> checkout

Tracking:
1. Query-string parameters arriving on the presell are forwarded to /pdp/.
2. On the PDP, incoming parameters are appended to checkout links without replacing parameters already present in the affiliate buy link.
3. The original Horse Jello checkout affiliate parameters remain intact.

Upload the CONTENTS of this folder to the web root, keeping the /pdp/ folder intact.
