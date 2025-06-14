🧘‍♂️ CloakCalm
CloakCalm is a science-based Magisk module that subtly reduces eye strain, screen fatigue, and background sensor activity — without turning your phone into a burnt-orange mess.

Designed for people who want a calmer smartphone experience without sacrificing usability.

🌙 What it does
🔵 Reduces blue light using a soft kernel-level gamma shift

🔕 Disables sensors (e.g., ambient light, proximity) via Android's sensors_off setting

🌘 Dims brightness and extends screen-off timeout

📋 Auto-starts on boot (from v1.6)

📜 Logs all actions to /data/adb/cloakcalm_log.txt

🧠 Based on scientific recommendations for screen comfort and circadian rhythm support

📖 Why not just use Night Light?
Because this is:

✅ Subtle (doesn’t nuke your color balance)

✅ Consistent across apps and reboots

✅ Play-nice with root setups, custom ROMs, and battery savers

✅ Actually rooted in research — 2700K–3400K is the sweet spot

🚀 Usage
bash
Copy
Edit
su
sh /data/adb/modules/cloakcalm/service.sh on      # activate
sh /data/adb/modules/cloakcalm/service.sh off     # deactivate
sh /data/adb/modules/cloakcalm/service.sh status  # check current state
sh /data/adb/modules/cloakcalm/service.sh set 180 130 100  # set custom gamma
🔒 Notes
Works best on devices where gamma control is exposed (write-only is okay)

Sensors will be disabled using Android's native global toggle

Gamma values are not readable on some kernels — this is expected and harmless

