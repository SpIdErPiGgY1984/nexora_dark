# Nexora Dark — onderhoud na phpBB-goedkeuring

De stijl is goedgekeurd. Deze wijziging verwerkt de twee informatieve opmerkingen van het phpBB Styles Team. De bestaande versie in style.cfg blijft behouden.

## Installeren of bijwerken

1. Maak een back-up van je huidige nexora_dark-stijlmap.
2. Upload de bestanden uit deze ZIP naar styles/nexora_dark/.
3. Verwijder bij een bestaande installatie ook onderstaande bestanden uit styles/nexora_dark/template/. Alleen overschrijven verwijdert oude bestanden niet.
4. Leeg de phpBB-cache via het ACP.
5. Controleer de normale header, privéberichten, avatarinstellingen en moderatiepagina's op je testforum.

Verwijderde overrides (identiek aan prosilver 3.3.19):

- mcp_footer.html
- mcp_message.html
- posting_review.html
- posting_topic_review.html
- ucp_auth_link_oauth.html
- ucp_avatar_options_gravatar.html
- ucp_avatar_options_local.html
- ucp_avatar_options_remote.html
- ucp_avatar_options_upload.html
- ucp_footer.html
- ucp_pm_history.html
- ucp_pm_message_footer.html
- ucp_pm_viewmessage.html

De stijl blijft afhankelijk van de parent prosilver. De verwijderde templates worden voortaan daarvan geladen.

## Header Banner

De standaard header bevat geen HEADERBANNER_SELECT- of HEADERBANNER_BACKGROUND-afhankelijkheid meer. De daarbij horende stijlregels zijn verwijderd. Een Header Banner-extensie moet haar integratie en eventuele stijlspecifieke CSS zelf via de phpBB-events leveren. Test deze extensie apart indien je haar gebruikt.
