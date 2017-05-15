# Status icons

Icons displayed in panels etc.

For inspiration/icon names, see `Numix/24/status/` (good overview of _a lot_ of icons)

## Icon hierarchy (inheritance)

* Name
    - original icon
        + symlinked, inherited icons

* Wired network
    - nm-device-wired
        + nm-device-wired-autoip
        + wired
    - [ ] nm-device-wired-secure
    - [ ] nm-adhoc
    - nm-no-connection
* Wireless network
    - nm-signal-0
    	+ nm-signal-00
    	+ bad-signal
    	+ both-bad-signal
    	+ gnome-netstatus-0-24
    	+ idle-bad-signal
    	+ network-wireless-signal-none
    	+ no-signal
    	+ receiveing-bad-signal
    	+ transmitting-bad-signal
    	+ wifi-020
    - nm-signal-25
    	+ both-low-signal
    	+ gnome-netstatus-25-49
    	+ idle-low-signal
    	+ low-signal
    	+ network-wireless-signal-weak
    	+ receiveing-low-signal
    	+ transmitting-low-signal
    	+ wifi-040
    - nm-signal-50
    	+ network-wireless-signal-ok
    	+ wifi-060
    - nm-signal-75
    	+ both-good-signal
    	+ gnome-netstatus-50-74
    	+ good-signal
    	+ idle-good-signal
    	+ network-wireless-signal-good
    	+ receiveing-good-signal
    	+ transmitting-good-signal
    	+ wifi-080
    - nm-signal-100
    	+ both-high-signal
    	+ gnome-netstatus-75-100
    	+ high-signal
    	+ idle-high-signal
    	+ network-wireless-signal-excellent
    	+ receiveing-high-signal
    	+ transmitting-high-signal
    	+ wifi-100
* Wireless network (secured)
    - nm-signal-0-secure
    	+ nm-signal-00-secure
    	+ bad-signal-lock
    	+ both-bad-signal-lock
    	+ idle-bad-signal-lock
    	+ receiveing-bad-signal-lock
    	+ transmitting-bad-signal-lock
    - nm-signal-25-secure
    	+ both-low-signal-lock
    	+ idle-low-signal-lock
		+ low-signal-lock
		+ receiveing-low-signal-lock
		+ transmitting-low-signal-lock
    - nm-signal-50-secure
    - nm-signal-75-secure
    	+ both-good-signal-lock
    	+ good-signal-lock
    	+ idle-good-signal-lock
    	+ receiveing-good-signal-lock
    	+ transmitting-good-signal-lock
    - nm-signal-100-secure
    	+ both-high-signal-lock
    	+ high-signal-lock
    	+ idle-high-signal-lock
    	+ receiveing-high-signal-lock
    	+ transmitting-high-signal-lock
* Audio
	- audio-volume-muted
		+ xfce4-mixer-muted
		+ xfce4-mixer-volume-muted
* [ ] Mega `(hardcoded)`
    - megasync-status-ok
    - megasync-status-disconnected
    - megasync-status-paused
    - megasync-status-syncing
* Pamac (updates)
    - [ ] ??
    - [ ] pamac-tray-no-update
    - [ ] pamac-tray-update