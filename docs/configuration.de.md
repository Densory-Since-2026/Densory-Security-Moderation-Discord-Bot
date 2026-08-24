# Densory Security — Konfiguration

Die folgenden Einstellungen stehen für dieses Produkt zur Verfügung:

Alle folgenden Einstellungen konfigurierst du in deinem [Control Center](https://densory.com/dashboard).

| Key | Typ | Default | Beschreibung |
| --- | --- | --- | --- |
| `locale` | `string` | `""` | Sprache |
| `default_color` | `hexColor` | `#444444` | Standard-Farbe |
| `success_color` | `hexColor` | `#2bfc71` | Erfolgs-Farbe |
| `warning_color` | `hexColor` | `#ffd621` | Warnungs-Farbe |
| `error_color` | `hexColor` | `#fc251e` | Fehler-Farbe |
| `success_img` | `image` | `/uploads/assets/product-images/discord-bots/default/success.png` | Erfolgs-Bild |
| `warning_img` | `image` | `/uploads/assets/product-images/discord-bots/default/warning.png` | Warnungs-Bild |
| `error_img` | `image` | `/uploads/assets/product-images/discord-bots/default/error.png` | Fehler-Bild |
| `role_hierarchy` | `hierarchy` | `[]` | Gruppen-Hierarchie |
| `infractions_log_channel` | `channel` | `""` | Verwarnungs-Log-Kanal |
| `infractions_dm_notify` | `string` | `enabled` | DM-Benachrichtigung |
| `infractions_mod_min_group` | `group_select` | `0` | Moderator Mindest-Gruppe |
| `infractions_warn_expire_days` | `number` | `30` | Verwarnungs-Ablauf (Tage) |
| `infractions_escalation` | `array` | `[{"threshold":3,"action":"timeout","duration_minutes":60},{"threshold":5,"action":"kick","duration_minutes":null},{"threshold":7,"action":"ban","duration_minutes":null}]` | Auto-Eskalation (JSON) |
| `lockdown_log_channel` | `channel` | `""` | Lockdown Log-Kanal |
| `lockdown_min_group` | `group_select` | `0` | Lockdown Mindest-Gruppe |
| `lockdown_default_duration` | `number` | `60` | Standard-Dauer (Min.) |
| `log_mod_channel` | `channel` | `""` | Moderations-Log |
| `log_message_channel` | `channel` | `""` | Nachrichten-Log |
| `log_member_channel` | `channel` | `""` | Mitglieder-Log |
| `log_server_channel` | `channel` | `""` | Server-Log |
| `log_ignored_channels` | `channels` | `[]` | Ignorierte Kanäle |
| `log_ignored_roles` | `roles` | `[]` | Ignorierte Rollen |
| `antinuke_status` | `string` | `disabled` | Anti-Nuke Schutz |
| `antinuke_action` | `string` | `strip_roles` | Anti-Nuke Aktion |
| `antinuke_log_channel` | `channel` | `""` | Anti-Nuke Log-Kanal |
| `antinuke_trusted_roles` | `roles` | `[]` | Vertrauenswürdige Rollen |
| `antinuke_trusted_groups` | `group_multi_select` | `[]` | Vertrauenswürdige Gruppen |
| `antinuke_channel_delete_threshold` | `number` | `3` | Kanal-Löschungen (Schwelle) |
| `antinuke_channel_delete_interval` | `number` | `10` | Kanal-Löschungen (Intervall Sek.) |
| `antinuke_role_delete_threshold` | `number` | `3` | Rollen-Löschungen (Schwelle) |
| `antinuke_role_delete_interval` | `number` | `10` | Rollen-Löschungen (Intervall Sek.) |
| `antinuke_ban_threshold` | `number` | `5` | Bans (Schwelle) |
| `antinuke_ban_interval` | `number` | `10` | Bans (Intervall Sek.) |
| `antinuke_kick_threshold` | `number` | `5` | Kicks (Schwelle) |
| `antinuke_kick_interval` | `number` | `10` | Kicks (Intervall Sek.) |
| `antiraid_status` | `string` | `disabled` | Anti-Raid Schutz |
| `antiraid_log_channel` | `channel` | `""` | Anti-Raid Log-Kanal |
| `antiraid_join_gate_enabled` | `string` | `enabled` | Neue-Account-Filter beim Join |
| `antiraid_min_account_age` | `number` | `7` | Min. Account-Alter (Tage) |
| `antiraid_young_account_action` | `string` | `quarantine` | Aktion bei jungen Accounts |
| `antiraid_raid_detection_enabled` | `string` | `enabled` | Raid-Erkennung (Join-Wellen) |
| `antiraid_raid_threshold` | `number` | `10` | Joins bis Raid-Alarm |
| `antiraid_raid_window` | `number` | `60` | Zeitfenster (Sek.) |
| `antiraid_raid_mode_response` | `string` | `alert` | Aktion bei Raid |
| `antiraid_raid_mode_duration` | `number` | `15` | Raid-Modus Dauer (Min.) |
| `antiraid_quarantine_role` | `role` | `""` | Quarantäne-Rolle |
| `antiraid_quarantine_duration` | `number` | `24` | Quarantäne-Dauer (Std.) |
| `antiraid_quarantine_expiry_action` | `string` | `release` | Nach Ablauf der Quarantäne |
| `custom_automod_status` | `string` | `disabled` | Custom AutoMod |
| `custom_automod_log_channel` | `channel` | `""` | AutoMod Log-Kanal |
| `custom_automod_rules` | `array` | `[]` | AutoMod Regeln |
| `automod_status` | `string` | `disabled` | AutoMod |
| `automod_log_channel` | `channel` | `""` | AutoMod Log-Kanal |
| `automod_native_rules` | `array` | `[]` | Discord AutoMod Regeln |
| `antispam_status` | `string` | `disabled` | Anti-Spam |
| `antispam_log_channel` | `channel` | `""` | Anti-Spam Log-Kanal |
| `antispam_action` | `string` | `timeout` | Spam Aktion |
| `antispam_message_rate` | `number` | `5` | Nachrichten (max.) |
| `antispam_message_interval` | `number` | `5` | Zeitfenster (Sek.) |
| `antispam_duplicate_threshold` | `number` | `3` | Duplikat-Schwelle |
| `antispam_caps_percent` | `number` | `70` | Großbuchstaben (max. %) |
| `antispam_emoji_limit` | `number` | `10` | Emoji-Limit |
| `antispam_mention_limit` | `number` | `5` | Mention-Limit |
| `antispam_max_lines` | `number` | `20` | Max. Zeilenanzahl |
| `antispam_trusted_groups` | `group_multi_select` | `[]` | Vertrauenswürdige Gruppen |
| `antispam_exempt_roles` | `roles` | `[]` | Ausgenommene Rollen |
| `antispam_exempt_channels` | `channels` | `[]` | Ausgenommene Kanäle |
| `phishing_status` | `string` | `disabled` | Phishing-Schutz |
| `phishing_log_channel` | `channel` | `""` | Phishing Log-Kanal |
| `phishing_action` | `string` | `delete_warn` | Phishing Aktion |
| `phishing_timeout_duration` | `number` | `10` | Timeout-Dauer (Min) |
| `phishing_scan_redirects` | `string` | `enabled` | Redirects prüfen |
| `phishing_exempt_roles` | `roles` | `[]` | Ausgenommene Rollen |
| `phishing_custom_blocklist` | `array` | `[]` | Eigene Blocklist |
| `phishing_whitelist` | `array` | `[]` | Whitelist |
| `privesc_status` | `string` | `enabled` | Rechte-Eskalation Schutz |
| `privesc_log_channel` | `channel` | `""` | Rechte-Eskalation Log-Kanal |
| `privesc_action` | `string` | `alert` | Eskalations-Aktion |
| `privesc_permissions` | `permission_matrix` | `{"monitored":["ADMINISTRATOR","BAN_MEMBERS","KICK_MEMBERS","MANAGE_GUILD","MANAGE_ROLES","MANAGE_CHANNELS","MANAGE_WEBHOOKS","MENTION_EVERYONE","MANAGE_MESSAGES","MODERATE_MEMBERS","VIEW_AUDIT_LOG","MANAGE_NICKNAMES","MANAGE_GUILD_EXPRESSIONS","MANAGE_EVENTS","MANAGE_THREADS","DEAFEN_MEMBERS","MOVE_MEMBERS","MUTE_MEMBERS","VIEW_GUILD_INSIGHTS","CREATE_INSTANT_INVITE"],"groupExemptions":{}}` | Berechtigungs-Matrix |
| `verification_status` | `string` | `disabled` | Verifikations-System |
| `verification_method` | `string` | `button` | Verifikations-Methode |
| `verification_role` | `role` | `""` | Verifizierte-Rolle |
| `verification_log_channel` | `channel` | `""` | Verifikations-Log |
| `verification_min_account_age` | `number` | `0` | Min. Account-Alter (Tage) |
| `verification_timeout_hours` | `number` | `24` | Timeout (Stunden) |
| `verification_auto_kick` | `string` | `disabled` | Auto-Kick bei Timeout |
| `verification_embed` | `embed` | `{"title":"","description":"","color":"#2b82d6","author":{"name":"","icon_url":""},"footer":{"text":"","icon_url":""},"thumbnail":{"url":""},"image":{"url":""},"fields":[]}` | Verifikations-Embed |
