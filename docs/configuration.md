# Densory Security — Configuration

The following settings are available for this product:

All settings below are configured in your [Control Center](https://densory.com/dashboard).

| Key | Type | Default | Description |
| --- | --- | --- | --- |
| `locale` | `string` | `""` | Language |
| `default_color` | `hexColor` | `#444444` | Default Color |
| `success_color` | `hexColor` | `#2bfc71` | Success Color |
| `warning_color` | `hexColor` | `#ffd621` | Warning Color |
| `error_color` | `hexColor` | `#fc251e` | Error Color |
| `success_img` | `image` | `/uploads/assets/product-images/discord-bots/default/success.png` | Success Image |
| `warning_img` | `image` | `/uploads/assets/product-images/discord-bots/default/warning.png` | Warning Image |
| `error_img` | `image` | `/uploads/assets/product-images/discord-bots/default/error.png` | Error Image |
| `role_hierarchy` | `hierarchy` | `[]` | Role Hierarchy |
| `infractions_log_channel` | `channel` | `""` | Infractions Log Channel |
| `infractions_dm_notify` | `string` | `enabled` | DM Notification |
| `infractions_mod_min_group` | `group_select` | `0` | Moderator Min. Group |
| `infractions_warn_expire_days` | `number` | `30` | Warning Expiry (Days) |
| `infractions_escalation` | `array` | `[{"threshold":3,"action":"timeout","duration_minutes":60},{"threshold":5,"action":"kick","duration_minutes":null},{"threshold":7,"action":"ban","duration_minutes":null}]` | Auto-Escalation (JSON) |
| `lockdown_log_channel` | `channel` | `""` | Lockdown Log Channel |
| `lockdown_min_group` | `group_select` | `0` | Lockdown Min. Group |
| `lockdown_default_duration` | `number` | `60` | Default Duration (min.) |
| `log_mod_channel` | `channel` | `""` | Moderation Log |
| `log_message_channel` | `channel` | `""` | Message Log |
| `log_member_channel` | `channel` | `""` | Member Log |
| `log_server_channel` | `channel` | `""` | Server Log |
| `log_ignored_channels` | `channels` | `[]` | Ignored Channels |
| `log_ignored_roles` | `roles` | `[]` | Ignored Roles |
| `antinuke_status` | `string` | `disabled` | Anti-Nuke Protection |
| `antinuke_action` | `string` | `strip_roles` | Anti-Nuke Action |
| `antinuke_log_channel` | `channel` | `""` | Anti-Nuke Log Channel |
| `antinuke_trusted_roles` | `roles` | `[]` | Trusted Roles |
| `antinuke_trusted_groups` | `group_multi_select` | `[]` | Trusted Groups |
| `antinuke_channel_delete_threshold` | `number` | `3` | Channel Deletes (Threshold) |
| `antinuke_channel_delete_interval` | `number` | `10` | Channel Deletes (Interval sec.) |
| `antinuke_role_delete_threshold` | `number` | `3` | Role Deletes (Threshold) |
| `antinuke_role_delete_interval` | `number` | `10` | Role Deletes (Interval sec.) |
| `antinuke_ban_threshold` | `number` | `5` | Bans (Threshold) |
| `antinuke_ban_interval` | `number` | `10` | Bans (Interval sec.) |
| `antinuke_kick_threshold` | `number` | `5` | Kicks (Threshold) |
| `antinuke_kick_interval` | `number` | `10` | Kicks (Interval sec.) |
| `antiraid_status` | `string` | `disabled` | Anti-Raid Protection |
| `antiraid_log_channel` | `channel` | `""` | Anti-Raid Log Channel |
| `antiraid_join_gate_enabled` | `string` | `enabled` | New-Account Filter on Join |
| `antiraid_min_account_age` | `number` | `7` | Min. Account Age (Days) |
| `antiraid_young_account_action` | `string` | `quarantine` | Action for Young Accounts |
| `antiraid_raid_detection_enabled` | `string` | `enabled` | Raid Detection (Join Waves) |
| `antiraid_raid_threshold` | `number` | `10` | Joins to trigger Raid |
| `antiraid_raid_window` | `number` | `60` | Time Window (sec.) |
| `antiraid_raid_mode_response` | `string` | `alert` | Action on Raid |
| `antiraid_raid_mode_duration` | `number` | `15` | Raid Mode Duration (min.) |
| `antiraid_quarantine_role` | `role` | `""` | Quarantine Role |
| `antiraid_quarantine_duration` | `number` | `24` | Quarantine Duration (hrs.) |
| `antiraid_quarantine_expiry_action` | `string` | `release` | After Quarantine Expires |
| `custom_automod_status` | `string` | `disabled` | Custom AutoMod |
| `custom_automod_log_channel` | `channel` | `""` | AutoMod Log Channel |
| `custom_automod_rules` | `array` | `[]` | AutoMod Rules |
| `automod_status` | `string` | `disabled` | AutoMod |
| `automod_log_channel` | `channel` | `""` | AutoMod Log Channel |
| `automod_native_rules` | `array` | `[]` | Discord AutoMod Rules |
| `antispam_status` | `string` | `disabled` | Anti-Spam |
| `antispam_log_channel` | `channel` | `""` | Anti-Spam Log Channel |
| `antispam_action` | `string` | `timeout` | Spam Action |
| `antispam_message_rate` | `number` | `5` | Messages (max.) |
| `antispam_message_interval` | `number` | `5` | Time Window (sec.) |
| `antispam_duplicate_threshold` | `number` | `3` | Duplicate Threshold |
| `antispam_caps_percent` | `number` | `70` | Caps Lock (max. %) |
| `antispam_emoji_limit` | `number` | `10` | Emoji Limit |
| `antispam_mention_limit` | `number` | `5` | Mention Limit |
| `antispam_max_lines` | `number` | `20` | Max. Line Count |
| `antispam_trusted_groups` | `group_multi_select` | `[]` | Trusted Groups |
| `antispam_exempt_roles` | `roles` | `[]` | Exempt Roles |
| `antispam_exempt_channels` | `channels` | `[]` | Exempt Channels |
| `phishing_status` | `string` | `disabled` | Phishing Protection |
| `phishing_log_channel` | `channel` | `""` | Phishing Log Channel |
| `phishing_action` | `string` | `delete_warn` | Phishing Action |
| `phishing_timeout_duration` | `number` | `10` | Timeout Duration (min) |
| `phishing_scan_redirects` | `string` | `enabled` | Check Redirects |
| `phishing_exempt_roles` | `roles` | `[]` | Exempt Roles |
| `phishing_custom_blocklist` | `array` | `[]` | Custom Blocklist |
| `phishing_whitelist` | `array` | `[]` | Whitelist |
| `privesc_status` | `string` | `enabled` | Privilege Escalation Protection |
| `privesc_log_channel` | `channel` | `""` | Privilege Escalation Log Channel |
| `privesc_action` | `string` | `alert` | Escalation Action |
| `privesc_permissions` | `permission_matrix` | `{"monitored":["ADMINISTRATOR","BAN_MEMBERS","KICK_MEMBERS","MANAGE_GUILD","MANAGE_ROLES","MANAGE_CHANNELS","MANAGE_WEBHOOKS","MENTION_EVERYONE","MANAGE_MESSAGES","MODERATE_MEMBERS","VIEW_AUDIT_LOG","MANAGE_NICKNAMES","MANAGE_GUILD_EXPRESSIONS","MANAGE_EVENTS","MANAGE_THREADS","DEAFEN_MEMBERS","MOVE_MEMBERS","MUTE_MEMBERS","VIEW_GUILD_INSIGHTS","CREATE_INSTANT_INVITE"],"groupExemptions":{}}` | Permission Matrix |
| `verification_status` | `string` | `disabled` | Verification System |
| `verification_method` | `string` | `button` | Verification Method |
| `verification_role` | `role` | `""` | Verified Role |
| `verification_log_channel` | `channel` | `""` | Verification Log |
| `verification_min_account_age` | `number` | `0` | Min. Account Age (Days) |
| `verification_timeout_hours` | `number` | `24` | Timeout (Hours) |
| `verification_auto_kick` | `string` | `disabled` | Auto-Kick on Timeout |
| `verification_embed` | `embed` | `{"title":"","description":"","color":"#2b82d6","author":{"name":"","icon_url":""},"footer":{"text":"","icon_url":""},"thumbnail":{"url":""},"image":{"url":""},"fields":[]}` | Verification Embed |
