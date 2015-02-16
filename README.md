sumo_live_moderation
====================

Helper addon for forum contributors:

- notification for new incoming questions in the support forum for selected products/languages
- notification for contributors about updates in threads where they have partcipated before
- set keywords in new questions that will cause an alert in any case
- shows a notification/thank you note when your solution count increases (only works while you're logged in to sumo)
- shows some statistics about your account when you hover over the toolbar icon (only while you're logged in to sumo)



use https://developer.mozilla.org/en-US/Add-ons/SDK/ to build the extension

cfx command to build the addon with auto-updates:
cfx xpi --update-link https://github.com/philipp-sumo/sumo_live_helper/raw/master/sumo_live_helper.xpi --update-url https://github.com/philipp-sumo/sumo_live_helper/raw/master/sumo_live_helper.update.rdf
