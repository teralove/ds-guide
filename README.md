# ds-guide
Guide for Dreadspire

## Commands
### `ds [off/on]'
- Toggle off/on
- Default is on

### `ds stream'
- Toggle stream mode (Disable notices and flowers)
- Default is off

See config.json to toggle off specific bosses.

---

## Changelog
<details>

    1.6
	- Fix: Patch 75 compatability
    - Add: Config settings for bosses and flower spawns
    - Fix: Kaprima Backspin message is called out earlier now (during breath attack)
    - Add: Kelsaik Fire aoe grass
    - Add: Kelsaik Ice aoe grass
    - Fix: Darkan Swipe flower safespots were wrong side
    - Fix: Darkan Enrage double swipe was not being called
    - Add: Shandra curl timer
    - Disabled some Shandra skill messages
    - Encounters now support multiple timers.
    1.5
    - Add: Jinn attack grass
    - Add: Meldita line attack grass
    1.4
    - Fix: Akasha Spin message being sent unexpectedly
    - Fix: Lakan's next message would be incorrect if he changed worlds immediately after reversal
    - Add: StreamMode no longer spawns safespots (flowers)
    - Add: Lakan Laser safespots
    - Add: Lakan Begone safe range
    - Add: Darkan Puddle timer
    - Add: Darkan Shout and timer
    - Add: Darkan Ghost and timer
    - Add: Darkan Eviscerate safespots
    - Add: Darkan, warning messages for auto attack combos (single spin and single swipe)
    - Disabled Dakuryon debuff message
    1.3
    - Fix: Spawned flowers would have inconsistent positioning
    - Fix: Initial messages associated with timers were not being sent
    - Fix: (Lakan) Undefined bossAction errors being thrown 
    - Fix: Darkan's extra enrage swipe message was not sending.
    - Fix: Dakuryon Swipe safespots
    - Add: Dakuryon Cage safespots
    - Add: Lakan Begone safe range
    - Add: Shandra stand message and timer
    1.2
    - Fix: Undefined bossInfo error in S_BOSS_GAGE_INFO
    1.1
    - Fix: Boss HP warning messages
    - Fix: Clear timers when boss dies
    - Fix: Lakan's new message at 50% would tell you the normal version even when he was in soul world.
    - Fix: Lakan next messages would be wrong after 50%
    - Add: Kelsaik small jump warning timer    
    - Add: Krakatox plague mechanic message and timer
    - Misc: Old unused Krakatox timer code
    1.0
    - Release

</details>

---

Feel free to fix bugs, make suggestions, report issues, [Donate](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=PXRFYB39SQP4A&lc=US&item_name=teralove&no_note=0&cn=Add%20special%20instructions%20to%20the%20seller%3a&no_shipping=1&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted).
