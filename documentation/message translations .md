# https://spartan.top

## How to Apply:
```
1. Copy all the options from one of the translations below.
3. Navigate to the directory "/plugins/Spartan" in your server's files.
4. Open the messages.yml file.
5. Delete everything in the messages.yml file.
6. Paste all the options you copied before to the now empty messages.yml file.
7. Save the file.
8. Run the command “/spartan reload” and you are ready!
```

## Simplified Chinese:
<details>
  <summary>Click to view messages.yml</summary>
  
```
server_name: '&4Minecraft伺服器'
violations_reset: '&8[&2{prefix}&8]&c VLs &7已被重置&8!'
config_reload: '&8[&2{prefix}&8]&e 設定檔成功重新加載。'
configuration_recommendations: '&8[&2{prefix}&8]&e {amount} 重要的設定建議。打開管理介面並研究說明的物品以獲得更多資訊。'
kick_reason: '&8[&2{prefix}&8]&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 因為&4 {reason} &7被踢除'
no_permission: '&c你沒有權限。'
ping_command_message: '&2{player}&7 延遲&8:&a {ping}ms'
player_not_found_message: '&c查無此玩家。'
non_console_command: '&c這個指令只有玩家可以使用。'
player_violation_reset_message: '&8[&2{prefix}&8]&a違規行為已成功重啟&8: &2{player} &a此玩家!'
blocked_command_message: '&c不允許你發送此指令。'
blocked_word_message: '&c你不允許打字。'
detection_notification: '&8[&2{prefix}&8] &c{player} 失敗的 {detection} x{vls:detection}
  &8[&7(&fSilent: {silent:detection}&7)&8, §7(&fPing: {ping}ms&7)&8, &7(&fTPS: {tps}&7)&8,
  &7(&fPlib: {plib}&7)&8, &7(&f{info}&7)&8]'
notifications_clickable_command: /spartan spectate {player}
mining_notification: '&8[&2{prefix}&8] &c{player} &7挖到 &4{material} &7在 &8{material-x}&7,
  &8{material-y}&7, &8{material-z}'
non_existing_check: '&8[&2{prefix}&8] &c此偵測不存在。'
massive_command_reason: '&c原因的文字長度太長。'
check_enable_message: '&8[&2{prefix}&8] &a你啟用了偵測&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c你禁用了偵測&8:&7 {detection}'
warning_message: '&8[&2{prefix}&8]&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 你已警告 &c{player} &7原因為&8: &4{reason}'
bypass_message: '&8[&2{prefix}&8] &c{player} &7現在避開了 &4{detection} &7檢測 &e{time} &7秒。'
ban_message: '&8[&2{prefix}&8]&7 你已封鎖 &c{player} &7原因為 &4{reason}'
unban_message: '&8[&2{prefix}&8]&7 你已解除封鎖 &c{player}'
player_not_banned: '&8[&2{prefix}&8]&c 此玩家沒有被封鎖。'
ban_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 被封鎖，原因為:&4 {reason}'
ban_reason: '&8[&2{prefix}&8]&c {reason}'
chat_cooldown_message: '&c請等待 {time} 秒再打字。'
notifications_enable: '&8[&2{prefix}&8] &a你啟用了訊息通知。'
notifications_disable: '&8[&2{prefix}&8] &c你禁用了訊息通知。'
reconnect_kick_message: '&8[&2{prefix}&8]&c請等待幾秒鐘再登入'
empty_ban_list: '&8[&2{prefix}&8]&c目前沒有被封鎖的玩家。'
command_cooldown_message: '&c請等待 {time} 秒再發送指令。'
wave_start_message: '&8[&2{prefix}&8]&c Wave啟用中...'
wave_end_message: '&8[&2{prefix}&8]&c Wave已結束共 {total} 動作。'
wave_clear_message: '&8[&2{prefix}&8]&c Wave已被清除。'
wave_add_message: '&8[&2{prefix}&8]&a {player} 加入了Wave。'
wave_remove_message: '&8[&2{prefix}&8]&c {player} 已刪除Wave。'
full_wave_list: '&8[&2{prefix}&8]&c Wave列表已額滿。'
empty_wave_list: '&8[&2{prefix}&8]&c Wave列表列表已清空。'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} 沒有加入Wave。'
staff_chat_message: '&8[&4Staff Chat&8]&c {player} &e{message}'
report_message: '&a{player} &7已檢舉 &c{reported} &7原因為&8: &4{reason}'
self_report_message: '&c你不能檢舉你自己。'
debug_player_message: '&8[&2{prefix}&8]&7 除錯 &6{player} &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 啟用除錯 &6{player}&7''s &e{type}'
debug_disable_message: '&8[&2{prefix}&8]&7 禁用除錯 &6{player}&7''s &e{type}'
debug_disable_all_message: '&8[&2{prefix}&8]&7 禁用除錯 &6{player}'
same_message_warning: '&8[&2{prefix}&8]&c 請避免再次傳送相同的訊息。'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c 已達到同IP上限。'
disabled_log_saving: '&8[&2{prefix}&8]&c 禁用所有紀錄保存選像。'
not_enough_saved_logs: '&8[&2{prefix}&8]&c 保存的紀錄不足。 必須至少 {amount} 行。'
unknown_command: '&f錯誤指令，請輸入"/help"獲得幫助。'
failed_command: '&8[&2{prefix}&8]&c 指令失敗。'
awareness_notification: '&8[&2{prefix} 通知&8]&a {info}'
spectating_player: '&8[&2{prefix}&8]&a 你正在旁觀 {player}.'
spectating_ended: '&8[&2{prefix}&8]&c 你不再旁觀某人。'
Chinese:
server_name: '&4Minecraft服务器'
violations_reset: '&8[&2{prefix}&8]&c VLs &7已被重置&8!'
config_reload: '&8[&2{prefix}&8]&e 设定档重新加载。'
configuration_recommendations: '&8[&2{prefix}&8]&e {amount} 重要的设定建议。 打开管理界面并研究说明的物品以获得更多资讯。'
kick_reason: '&8[&2{prefix}&8]&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 因为&4 {reason} &7被踢出'
no_permission: '&c你沒有权限。'
ping_command_message: '&2{player}&7 延迟&8:&a {ping}ms'
player_not_found_message: '&c没有这个玩家。'
non_console_command: '&c此指令只有玩家可以使用。'
player_violation_reset_message: '&8[&2{prefix}&8]&a违规行为已被重启&8: &2{player} &a此玩家!'
blocked_command_message: '&c不允许你发生送此指令。'
blocked_word_message: '&c你不允许打字。'
detection_notification: '&8[&2{prefix}&8] &c{player} 失败的 {detection} x{vls:detection}
  &8[&7(&fSilent: {silent:detection}&7)&8, §7(&fPing: {ping}ms&7)&8, &7(&fTPS: {tps}&7)&8,
  &7(&fPlib: {plib}&7)&8, &7(&f{info}&7)&8]'
notifications_clickable_command: /spartan spectate {player}
mining_notification: '&8[&2{prefix}&8] &c{player} &7挖到 &4{material} &7在 &8{material-x}&7,
  &8{material-y}&7, &8{material-z}'
non_existing_check: '&8[&2{prefix}&8] &c此侦测不存在。'
massive_command_reason: '&c原因的文字长度太。'
check_enable_message: '&8[&2{prefix}&8] &a你启用了侦测&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c你禁用了侦测&8:&7 {detection}'
warning_message: '&8[&2{prefix}&8]&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 你已警告 &c{player} &7原因为&8: &4{reason}'
bypass_message: '&8[&2{prefix}&8] &c{player} &7现在避开了 &4{detection} &7检测 &e{time} &7秒。'
ban_message: '&8[&2{prefix}&8]&7 你已封禁 &c{player} &7原因为 &4{reason}'
unban_message: '&8[&2{prefix}&8]&7 你已解除封锁 &c{player}'
player_not_banned: '&8[&2{prefix}&8]&c 此玩家沒有被封锁。'
ban_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 被封锁，原因为:&4 {reason}'
ban_reason: '&8[&2{prefix}&8]&c {reason}'
chat_cooldown_message: '&c请等待 {time} 秒再打字。'
notifications_enable: '&8[&2{prefix}&8] &a你启用了讯息通知。'
notifications_disable: '&8[&2{prefix}&8] &c你禁用了讯息通知。'
reconnect_kick_message: '&8[&2{prefix}&8]&c请等待几秒钟再登入'
empty_ban_list: '&8[&2{prefix}&8]&c目前沒有被封锁的玩家。'
command_cooldown_message: '&c请等待 {time} 秒再发送指令。'
wave_start_message: '&8[&2{prefix}&8]&c Wave启用用中...'
wave_end_message: '&8[&2{prefix}&8]&c Wave已結束 {total} 动作。'
wave_clear_message: '&8[&2{prefix}&8]&c Wave已被清除。'
wave_add_message: '&8[&2{prefix}&8]&a {player} 加入了Wave。'
wave_remove_message: '&8[&2{prefix}&8]&c {player} 已刪除Wave。'
full_wave_list: '&8[&2{prefix}&8]&c Wave列表名额已滿。'
empty_wave_list: '&8[&2{prefix}&8]&c Wave列表列表已清空。'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} 沒有加入Wave。'
staff_chat_message: '&8[&4Staff Chat&8]&c {player} &e{message}'
report_message: '&a{player} &7已举报 &c{reported} &7原因为&8: &4{reason}'
self_report_message: '&c你不能举报你自己。'
debug_player_message: '&8[&2{prefix}&8]&7 除错 &6{player} &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 启用除错 &6{player}&7''s &e{type}'
debug_disable_message: '&8[&2{prefix}&8]&7 禁用除错 &6{player}&7''s &e{type}'
debug_disable_all_message: '&8[&2{prefix}&8]&7 禁用除错 &6{player}'
same_message_warning: '&8[&2{prefix}&8]&c 请避免再次传送相同的讯息。'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c 已达到同IP上限。'
disabled_log_saving: '&8[&2{prefix}&8]&c 禁用所有记录保存选项。'
not_enough_saved_logs: '&8[&2{prefix}&8]&c 保存的记录不足。 必须至少 {amount} 行。'
unknown_command: '&f错误指令，请輸入"/help"获得帮助。'
failed_command: '&8[&2{prefix}&8]&c 指令失败。'
awareness_notification: '&8[&2{prefix} 通知&8]&a {info}'
spectating_player: '&8[&2{prefix}&8]&a 你正在旁观 {player}.'
spectating_ended: '&8[&2{prefix}&8]&c 你不再旁观某人。'
```
</details>

## French:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Test
no_permission: '&cVous n''avez pas la permission d''interagir avec ceci.'
player_not_found_message: '&cJoueur introuvable.'
staff_chat_message: '&8[&4Staff Chat&8]&c {player} &e{message}'
not_enough_saved_logs: '&8[&2{prefix}&8]&c Pas assez de journaux enregistrés. Il doit y avoir au moins {amount} lignes.'
config_reload: '&8[&2{prefix}&8]&e Configuration rechargée avec succès.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 a été expulsé pour&4 {reason}'
reconnect_kick_message: '&8[&2{prefix}&8]&c Veuillez patienter quelques secondes avant de vous reconnecter.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c La limite de joueurs pour votre adresse IP a été atteinte.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Les violations ont été réinitialisées avec succès pour le joueur&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Les données stockées ont été supprimées avec succès pour le joueur&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &4{player} &cest &4{detection:category:adverb} &cen utilisant &4{detection} x{vls:detection} &8&b| &r&f{ping}ms &8&b| &r&f{tps} TPS &8&b| &r&fsilencieux: {silent:detection}, {info}'
blocked_command_message: '&8[&2{prefix}&8]&c Vous n''êtes pas autorisé à exécuter cette commande.'
blocked_word_message: '&8[&2{prefix}&8]&c Vous n''êtes pas autorisé à taper cela.'
chat_cooldown_message: '&8[&2{prefix}&8]&c Veuillez patienter {time} seconde(s) avant de taper à nouveau.'
command_cooldown_message: '&8[&2{prefix}&8]&c Veuillez patienter {time} seconde(s) avant d''exécuter à nouveau une commande.'
same_message_warning: '&8[&2{prefix}&8]&c Veuillez éviter d''envoyer le même message à nouveau.'
check_enable_message: '&8[&2{prefix}&8] &aVous avez activé la vérification&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cVous avez désactivé la vérification&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cCette vérification n''existe pas.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7ignore maintenant la vérification &4{detection} &7pendant &e{time} &7secondes.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Vous avez averti &c{player} &7pour&8: &4{reason}'
ban_message: '&8[&2{prefix}&8]&7 Vous avez banni &c{player} &7pour &4{reason}'
unban_message: '&8[&2{prefix}&8]&7 Vous avez débanni &c{player}'
player_not_banned: '&8[&2{prefix}&8]&c Ce joueur n''est pas banni.'
ban_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 a été banni pour&4 {reason}'
ban_reason: '&c {reason}'
empty_ban_list: '&8[&2{prefix}&8]&c Il n''y a actuellement aucun joueur banni.'
notifications_enable: '&8[&2{prefix}&8] &aVous avez activé les notifications.'
notifications_modified: '&8[&2{prefix}&8] &eVous avez modifié les notifications.'
notifications_disable: '&8[&2{prefix}&8] &cVous avez désactivé les notifications.'
awareness_notification: '&8[&2{prefix} Notification&8]&a {info}'
suspicion_notification: |-
  &8[&2{prefix}&8] &6{size} joueur(s) &epourrait utiliser des modules de triche&8: &6{players}
  &eExécutez '/spartan menu' pour afficher de futures interactions similaires.
wave_start_message: '&8[&2{prefix}&8]&c La vague commence.'
wave_end_message: '&8[&2{prefix}&8]&c La vague est terminée avec un total de {total} action(s).'
wave_clear_message: '&8[&2{prefix}&8]&c La vague a été effacée.'
wave_add_message: '&8[&2{prefix}&8]&a {player} a été ajouté à la vague.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} a été retiré de la vague.'
full_wave_list: '&8[&2{prefix}&8]&c La liste de la vague est pleine.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} n''est pas ajouté à la vague.'
report_message: '&8[&2{prefix}&8] &a{player} &7a signalé &c{reported} &7pour&8: &4{reason}'
self_report_message: '&8[&2{prefix}&8]&c Vous ne pouvez pas vous signaler vous-même.'
debug_player_message: '&8[&2{prefix}&8]&7 Débogage de &6{player}&7''s &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 Débogage activé pour &6{player}&7''s &e{type}'
debug_disable_message: '&8[&2{prefix}&8]&7 Débogage désactivé pour &6{player}&7''s &e{type}'
debug_disable_all_message: '&8[&2{prefix}&8]&7 Débogage désactivé pour &6{player}'
unknown_command: '&fCommande inconnue. Veuillez taper "/help" pour obtenir de l''aide.'
failed_command: '&8[&2{prefix}&8]&c Échec de la commande. Veuillez vérifier vos arguments et réessayer.'
successful_command: '&8[&2{prefix}&8]&a Commande réussie.'
massive_command_reason: '&8[&2{prefix}&8]&c La raison est trop longue.'
spectating_player: '&8[&2{prefix}&8]&a Vous observez maintenant {player}, tapez "/spectate" pour arrêter.'
spectating_ended: '&8[&2{prefix}&8]&c Vous ne observez plus personne.'
```
</details>

## Russian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
server_name: '&4Еще один Minecraft сервер'
violations_reset: '&8[&2{prefix}&8] &cНарушения &7были сброшены&8!'
config_reload: '&8[&2{prefix}&8]&e Конфиг успешно перезагружен.'
configuration_recommendations: '&8[&2{prefix}&8]&e Есть {amount} важных рекомендаций к конфигурации.
  Открой меню "Управление проверками" и изучи описание пунктов
  для получения дополнительной информации.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 ьыл кикнут за&4 {reason}'
no_permission: '&cНедостаточно полномочий.'
ping_command_message: '&2{player}&7 пинг&8:&a {ping}мс'
player_not_found_message: '&cИгрок не найден.'
non_console_command: '&cЭта команда может быть использована только игроком.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Нарушения игрока &2{player} &aбыли успешно сброшены'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Сохраненные данные игрока&2{player} &aбыли успешно сброшены'
blocked_command_message: '&cИспользовать эту команду запрещено.'
blocked_word_message: '&cЗапрещено писать это в чат.'
detection_notification: '&8[&2{prefix}&8] &c{player} возможно нарушил: {detection} x{vls:detection}
  &8[&7(&fSilent: {silent:detection}&7)&8, §7(&fПинг: {ping}ms&7)&8, &7(&fTPS: {tps}&7)&8,
  &7(&fPlib: {plib}&7)&8, &7(&f{info}&7)&8]'
notifications_clickable_command: /spartan spectate {player}
non_existing_check: '&8[&2{prefix}&8] &cЭтой проверки не существует.'
massive_command_reason: '&cДлина причины слишком велика.'
check_enable_message: '&8[&2{prefix}&8] &aПроверка&7 {detection}&a успешно включена'
check_disable_message: '&8[&2{prefix}&8] &cПроверка&7 {detection}&c успешно выключена'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Ты заварнил &c{player} &7за &4{reason}'
bypass_message: '&8[&2{prefix}&8] &c{player} &7теперь обходит проверку на &4{detection} &7на &e{time} &7секунд.'
ban_message: '&8[&2{prefix}&8]&7 Ты забанил &c{player} &7за &4{reason}'
unban_message: '&8[&2{prefix}&8]&7 Ты разбанил &c{player}'
player_not_banned: '&8[&2{prefix}&8]&c Этот игрок не забанен.'
ban_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 забанили за&4 {reason}'
ban_reason: '&c {reason}'
chat_cooldown_message: '&cПодожди {time} секунд прежде чем писать в чат снова.'
notifications_enable: '&8[&2{prefix}&8] &aТы включил уведомления.'
notifications_disable: '&8[&2{prefix}&8] &cТы выключил уведомления.'
reconnect_kick_message: '&8[&2{prefix}&8]&c Подожди несколько секунд для реконнекта.'
empty_ban_list: '&8[&2{prefix}&8]&c Нет забаненных игроков.'
command_cooldown_message: '&cПодожди {time} секунд прежде чем использовать команду снова.'
wave_start_message: '&8[&2{prefix}&8]&c Старт волны.'
wave_end_message: '&8[&2{prefix}&8]&c Волна закончилась с {total} действиями.'
wave_clear_message: '&8[&2{prefix}&8]&c Волна очищена.'
wave_add_message: '&8[&2{prefix}&8]&a {player} добавлен в волну.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} убран с волны.'
full_wave_list: '&8[&2{prefix}&8]&c Список игроков в волне забит.'
empty_wave_list: '&8[&2{prefix}&8]&c Список игроков в волне пуст.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} не добавлен к волне.'
staff_chat_message: '&8[&4Staff Chat&8]&c {player} &e{message}'
report_message: '&a{player} &7зарепортил &c{reported} &7за &4{reason}'
self_report_message: '&cТы не можешь зарепортить себя.'
debug_player_message: '&8[&2{prefix}&8]&7 Дебаг &6{player}&7 &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 Включен дебаг игрока &6{player} &e{type}'
debug_disable_message: '&8[&2{prefix}&8]&7 Отключен дебаг игрока &6{player} &e{type}'
debug_disable_all_message: '&8[&2{prefix}&8]&7 Отключен дебаг игрока &6{player}'
same_message_warning: '&8[&2{prefix}&8]&c Не флуди.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Лимит игроков с вашим IP был достигнут.'
disabled_log_saving: '&8[&2{prefix}&8]&c Все параметры сохранения лога отключены.'
not_enough_saved_logs: '&8[&2{prefix}&8]&c Недостаточно для сохранения лога,
  Должно быть от {amount} строк.'
unknown_command: '&fUnknown command. Please type "/help" for help.'
failed_command: '&8[&2{prefix}&8]&c Ошибка. Проверь аргументы и попробуй еще раз.'
awareness_notification: '&8[&2{prefix} Notification&8]&a {info}'
spectating_player: '&8[&2{prefix}&8]&a Следим за {player}.'
spectating_ended: '&8[&2{prefix}&8]&c Теперь ты не следишь за кем-либо.'
```
</details>

## German:
<details>
  <summary>Click to view messages.yml</summary>
  
```
server_name: '&4Ein Minecraft Server'
violations_reset: '&8[&2{prefix}&8] &cVerstöße &7wurden zurückgesetzt&8!'
config_reload: '&8[&2{prefix}&8]&e Konfiguration erfolgreich neugeladen.'
configuration_recommendations: '&8[&2{prefix}&8]&e {amount} wichtige Vörschläge. Öffne das "Manage Checks" Menü und lies die Beschreibungen der Items für weitere Informationen.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 wurde für&4 {reason}&7 gekickt.'
no_permission: '&cDu hast keine Rechte damit zu interagieren.'
ping_command_message: '&2{player}&7''s Ping&8:&a {ping}ms'
player_not_found_message: '&cDieser Spieler wurde nicht gefunden.'
non_console_command: '&cDieser Befehl kann nur von einem Spieler ausgeführt werden.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Verstöße von &2{player} &aerfolgreich zurückgesetzt.'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Alle gespeicherten Daten von &2{player} &aerfolgreich gelöscht.'
blocked_command_message: '&cDu hast keine Rechte diesen Befehl auszuführen.'
blocked_word_message: '&cDas darfst du nicht schreiben.'
detection_notification: '&8[&2{prefix}&8] &c{player} hat den {detection} Check ausgelöst x{vls:detection} &8[&7(&fSilent: {silent:detection}&7)&8, §7(&fPing: {ping}ms&7)&8, &7(&fTPS: {tps}&7)&8, &7(&fPlib: {plib}&7)&8, &7(&f{info}&7)&8]'
notifications_clickable_command: /spartan spectate {player}
non_existing_check: '&8[&2{prefix}&8] &cDiesen Check gibt es nicht.'
massive_command_reason: '&cDieser Grund ist zu lang.'
check_enable_message: '&8[&2{prefix}&8] &aDu hast folgenden Check aktiviert&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cDu hast folgenden Check deaktiviert&8:&7 {detection}'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Du hast &c{player} &7für &4{reason} &7gewarnt.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7wird nun für &e{time} &7 Sekunden vom &4{detection} &7Check ignoriert.'
ban_message: '&8[&2{prefix}&8]&7 Du hast &c{player} &7für &4{reason} &7gebannt.'
unban_message: '&8[&2{prefix}&8]&7 Du hast &c{player} &7entbannt.'
player_not_banned: '&8[&2{prefix}&8]&c Dieser Spieler ist nicht gebannt.'
ban_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 würde für&4 {reason} &7gebannt.'
ban_reason: '&c {reason}'
chat_cooldown_message: '&cBitte warte {time} Sekunden bevor du wieder eine Nachricht sendest.'
notifications_enable: '&8[&2{prefix}&8] &aDu hast Benachrichtigungen aktiviert.'
notifications_disable: '&8[&2{prefix}&8] &cDu hast Benachrichtigungen deaktiviert.'
reconnect_kick_message: '&8[&2{prefix}&8]&c Bitte warte einige Sekunden bevor du dich erneut verbindest.'
empty_ban_list: '&8[&2{prefix}&8]&c Derzeit sind keine Spieler gebannt.'
command_cooldown_message: '&cBitte warte {time} Sekunden bevor du wieder einen Befehl ausführst.'
wave_start_message: '&8[&2{prefix}&8]&c Die Bestrafungswelle startet.'
wave_end_message: '&8[&2{prefix}&8]&c Die Bestrafungswelle ist nun beendet, es wurden {total} Aktionen ausgeführt.'
wave_clear_message: '&8[&2{prefix}&8]&c Die Bestrafungswelle wurde gelöscht.'
wave_add_message: '&8[&2{prefix}&8]&a {player} wurde zur Bestrafungswelle hinzugefügt.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} wurde aus der Bestrafungswelle entfernt.'
full_wave_list: '&8[&2{prefix}&8]&c Die Bestrafungswelle ist voll.'
empty_wave_list: '&8[&2{prefix}&8]&c Die Bestrafungswelle ist leer.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} ist nicht der Bestrafungswelle hinzugefügt.'
staff_chat_message: '&8[&4Teamchat&8]&c {player} &e{message}'
report_message: '&a{player} &7hat &c{reported} &7für &4{reason} &7gemeldet.'
self_report_message: '&cDu kannst dich nicht selbst melden.'
debug_player_message: '&8[&2{prefix}&8]&7 Debugging &6{player}&7''s &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 Debugging für &6{player}&7''s &e{type} &7aktiviert.'
debug_disable_message: '&8[&2{prefix}&8]&7 Debugging für &6{player}&7''s &e{type} &7deaktiviert.'
debug_disable_all_message: '&8[&2{prefix}&8]&7 Debugging für &6{player} &7deaktiviert.'
same_message_warning: '&8[&2{prefix}&8]&c Bitte vermeide die selbe Nachricht erneut zu senden.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Das Spieler Limit für deine IP-Adresse ist erreicht.'
disabled_log_saving: '&8[&2{prefix}&8]&c Alle Log Optionen sind deaktiviert.'
not_enough_saved_logs: '&8[&2{prefix}&8]&c Nicht genug gespeicherte Logs. Es müssen mindestens {amount} Zeilen vorhanden sein.'
unknown_command: '&fUnknown command. Please type "/help" for help.'
failed_command: '&8[&2{prefix}&8]&c Befehl fehlgeschlagen. Bitte überprüfe deine Argumente und versuche es erneut.'
awareness_notification: '&8[&2{prefix} Benachrichtigung&8]&a {info}'
spectating_player: '&8[&2{prefix}&8]&a Du beobachtest nun {player}.'
spectating_ended: '&8[&2{prefix}&8]&c Du beobachtest nun niemanden mehr.'
```
</details>

## Spanish:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Console
no_permission: '&cNo tienes permiso para eso.'
player_not_found_message: '&cJugador no encontrado.'
staff_chat_message: '&8[&4StaffChat&8]&c {player} &e{message}'
not_enough_saved_logs: '&8[&2{prefix}&8]&c No hay suficientes registros guardados. Deberian haber minimo
  {amount} rows.'
config_reload: '&8[&2{prefix}&8]&e Config Recargada exitosamente.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 Fue kickeado por&4 {reason}'
reconnect_kick_message: '&8[&2{prefix}&8]&c Espere unos segundos antes de iniciar sesión
   de nuevo '
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Espere unos segundos antes de iniciar sesión
El límite de jugadores de tu IP ha sido alcanzada.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Violaciones recargadas exitosamente para
  for player&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Datos guardados han sido reiniciados exitosamente para
  for player&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &4{player} &cis &4{detection:category:adverb}
  &cusing &4{detection} x{vls:detection} &8&b| &r&f{ping}ms &8&b| &r&f{tps} TPS &8&b|
  &r&fsilent: {silent:detection}, {info}'
blocked_command_message: '&8[&2{prefix}&8]&c No tienes permisos de usar ese comando.'
blocked_word_message: '&8[&2{prefix}&8]&c No tienes permitido escribir eso.'
chat_cooldown_message: '&8[&2{prefix}&8]&c Porfavor espera {time} segundos Antes de escribir eso.'
command_cooldown_message: '&8[&2{prefix}&8]&c Porfavor espera {time} segundos antes de volver a usar ese comando.'
same_message_warning: '&8[&2{prefix}&8]&c Porfavor no reenvies el mismo mensaje tantas veces.'
check_enable_message: '&8[&2{prefix}&8] &aActivaste el checador&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cDesactivaste el checador&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cEste checador no existe'
bypass_message: '&8[&2{prefix}&8] &c{player} &7Esta bypasseando la  &4{detection} &7 checa por &e{time} &7segundos.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Haz advertido &c{player} &7por&8: &4{reason}'
ban_message: '&8[&2{prefix}&8]&7 Baneaste a &c{player} &7Razón: &4{reason}'
unban_message: '&8[&2{prefix}&8]&7 Tu unbaneaste a &c{player}'
player_not_banned: '&8[&2{prefix}&8]&c Este jugador no esta baneado.'
ban_broadcast_message: '&8[&2{prefix}&8]&7El jugador &c {player}&7 Fue baneado por razón&4 {reason}'
ban_reason: '&c {reason}'
empty_ban_list: '&8[&2{prefix}&8]&c No hay jugadores baneados.'
notifications_enable: '&8[&2{prefix}&8] &aActivaste las notificaciones.'
notifications_modified: '&8[&2{prefix}&8] &eModificaste las notificaciones.'
notifications_disable: '&8[&2{prefix}&8] &cDesactivaste las notitificaciones'
awareness_notification: '&8[&2{prefix} Notificacion&8]&a {info}'
suspicion_notification: |-
  &8[&2{prefix}&8] &6{size} player(s) &epuede estar usando módulos de hackeo&8: &6{players}
  &eusa '/spartan menu' para ver interacciones futuras.
wave_start_message: '&8[&2{prefix}&8]&c La ola esta iniciando.'
wave_end_message: '&8[&2{prefix}&8]&c La ola se termino con un total de interacciones {total} action(s).'
wave_clear_message: '&8[&2{prefix}&8]&c La ola fue limpiada'
wave_add_message: '&8[&2{prefix}&8]&a {player}Fue añadido a la ola.'
wave_remove_message: '&8[&2{prefix}&8]&aEl &c{player} Fue eliminado de la ola.'
full_wave_list: '&8[&2{prefix}&8]&c La lista de la ola esta llena.'
wave_not_added_message: '&8[&2{prefix}&8]&a El &c{player} No esta añadido a la ola'
report_message: '&8[&2{prefix}&8] &a{player} &7reported &c{reported} &7for&8: &4{reason}'
self_report_message: '&8[&2{prefix}&8]&c Tu no puedes reportarte a ti mismo.'
debug_player_message: '&8[&2{prefix}&8]&7 Depuración &6{player}&7''s &e{type}&8: &f{info}'
debug_enable_message: '&8[&2{prefix}&8]&7 Comenzando depuración para &6{player}&7''s &e{type}'
debug_disable_message: '&8[&2{prefix}&8]&7 Depuración desactivada para &6{player}&7''s
  &e{type}'
debug_disable_all_message: '&8[&2{prefix}&8]&7 Depuración deshabilitada para &6{player}'
unknown_command: '&fComando no encontrado. Por favor usa "/help" para ayuda.'
failed_command: '&8[&2{prefix}&8]&c Comando erroneo, revise y vuelva a intentarlo.'
successful_command: '&8[&2{prefix}&8]&a Comando exitoso.'
massive_command_reason: '&8[&2{prefix}&8]&c El tamaño de la razón es demasiado grande.'
spectating_player: '&8[&2{prefix}&8]&a Tu ahora estas vigilando a {player}, usa ''/spectate''
  para salir.'
spectating_ended: '&8[&2{prefix}&8]&c Ya no estas vigilando a alguien.'
```
</details>

## Portuguese:
<details>
  <summary>Click to view messages.yml</summary>
  
```
#Translation pt-BR by josegoust
console_name: Console
no_permission: '&8[&2{prefix}&8]&c Você não tem permissão para interagir com isso.'
player_not_found_message: '&8[&2{prefix}&8]&c Jogador não encontrado.'
config_reload: '&8[&2{prefix}&8]&e Configuração recarregada com sucesso'
panic_mode_enable: '&8[&2{prefix}&8]&a Modo pânico ativado, todos os checks estão em modo silencioso
  e não punirão jogadores.'
panic_mode_disable: '&8[&2{prefix}&8]&c Modo pânico desativado, todos os checks irão operar
  no modo padrão de acordo com sua configuração'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 foi kickado por&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Limite de jogador por ip
  foi atingido.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Violações resetadas com sucesso
  para o jogador&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Data armazenada deletada com sucesso
  para o jogador&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8]
  &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Data armazenada deletada com sucesso
  para o check&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aVocê ativou o check&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cVocê desativou o check&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aVocê ativou as prevenções para o
  check&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &caVocê desativou as prevenções para o
  check&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aVocê ativou as punições para o
  check&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cVocê desativou as punições para o
  the check&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cEste check não existe.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7tem "passe livre" para &4{detection}
  &7check por &e{time} &7seconds.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Você alertou &c{player} &7para&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aVocê ativou verbose(detalhamento).'
verbose_disable: '&8[&2{prefix}&8] &cVocê desativou verbose(detalhamento)'
notifications_enable: '&8[&2{prefix}&8] &aVocê ativou as notificações.'
notifications_modified: '&8[&2{prefix}&8] &eVocê modificou as notificações.'
notifications_disable: '&8[&2{prefix}&8] &cVocê desativou as notificações.'
awareness_notification: '&8[&2{prefix} Notificações&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c A onda está iniciando.'
wave_end_message: '&8[&2{prefix}&8]&c A onda terminou com um total de {total} ação(oes).'
wave_clear_message: '&8[&2{prefix}&8]&c A onda foi limpada.'
wave_add_message: '&8[&2{prefix}&8]&a {player} foi adicionado na onda.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} foi removido da onda.'
full_wave_list: '&8[&2{prefix}&8]&c A lista da onda está cheia.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} is not added to the wave.'
unknown_command: '&fUnknown command. Please type "/help" for help.'
failed_command: '&8[&2{prefix}&8]&c Command failed ({command}). Please check your
  arguments and try again.'
successful_command: '&8[&2{prefix}&8]&a Comando com sucesso.'
massive_command_reason: '&8[&2{prefix}&8]&c A escrita do motivo está muito grande.'
```
</details>

## Polish:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsola
no_permission: '&8[&2{prefix}&8]&c Nie masz uprawnień, aby to wykonać.'
player_not_found_message: '&8[&2{prefix}&8]&c Nie znaleziono gracza.'
config_reload: '&8[&2{prefix}&8]&e Konfiguracja została pomyślnie przeładowana.'
panic_mode_enable: '&8[&2{prefix}&8]&a Tryb paniki włączony, wszystkie sprawdzenia są ustawione jako ciche i nie będą karać graczy.'
panic_mode_disable: '&8[&2{prefix}&8]&c Tryb paniki wyłączony, wszystkie sprawdzenia będą działać zgodnie z konfiguracją.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 został wyrzucony za&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Limit graczy z twojego IP został osiągnięty.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Wykroczenia zostały pomyślnie zresetowane dla gracza&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Dane gracza zostały pomyślnie usunięte&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Dane wykrywania zostały pomyślnie usunięte&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aWłączyłeś sprawdzenie&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cWyłączyłeś sprawdzenie&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aWłączyłeś zapobieganie dla sprawdzenia&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cWyłączyłeś zapobieganie dla sprawdzenia&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aWłączyłeś kary dla sprawdzenia&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cWyłączyłeś kary dla sprawdzenia&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cTo sprawdzenie nie istnieje.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7omija teraz sprawdzenie &4{detection} &7przez &e{time} &7sekund.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Ostrzegłeś gracza &c{player} &7za&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aWłączyłeś tryb szczegółowy.'
verbose_disable: '&8[&2{prefix}&8] &cWyłączyłeś tryb szczegółowy.'
notifications_enable: '&8[&2{prefix}&8] &aWłączyłeś powiadomienia.'
notifications_modified: '&8[&2{prefix}&8] &eZmodyfikowałeś powiadomienia.'
notifications_disable: '&8[&2{prefix}&8] &cWyłączyłeś powiadomienia.'
awareness_notification: '&8[&2{prefix} Powiadomienie&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Fala się rozpoczęła.'
wave_end_message: '&8[&2{prefix}&8]&c Fala zakończona z łączną liczbą {total} akcji.'
wave_clear_message: '&8[&2{prefix}&8]&c Fala została wyczyszczona.'
wave_add_message: '&8[&2{prefix}&8]&a {player} został dodany do fali.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} został usunięty z fali.'
full_wave_list: '&8[&2{prefix}&8]&c Lista fali jest pełna.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nie został dodany do fali.'
unknown_command: '&fNieznana komenda. Wpisz "/help", aby uzyskać pomoc.'
failed_command: '&8[&2{prefix}&8]&c Nieudana komenda ({command}). Sprawdź argumenty i spróbuj ponownie.'
successful_command: '&8[&2{prefix}&8]&a Komenda wykonana pomyślnie.'
massive_command_reason: '&8[&2{prefix}&8]&c Powód jest zbyt długi.'
```
</details>

## Turkish:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsol
no_permission: '&8[&2{prefix}&8]&c Bu işlemi gerçekleştirmek için yetkin yok.'
player_not_found_message: '&8[&2{prefix}&8]&c Oyuncu bulunamadı.'
config_reload: '&8[&2{prefix}&8]&e Yapılandırma başarıyla yeniden yüklendi.'
panic_mode_enable: '&8[&2{prefix}&8]&a Panik modu etkinleştirildi, tüm kontroller sessize alındı ve oyuncular cezalandırılmayacak.'
panic_mode_disable: '&8[&2{prefix}&8]&c Panik modu devre dışı bırakıldı, tüm kontroller yapılandırma standartlarına göre çalışacak.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 adlı oyuncu şu nedenle atıldı:&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c IP adresinizin oyuncu limiti aşıldı.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Oyuncunun ihlalleri başarıyla sıfırlandı&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Oyuncunun kayıtlı verileri başarıyla silindi&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Kontrol verisi başarıyla silindi&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aŞu kontrolü etkinleştirdiniz&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cŞu kontrolü devre dışı bıraktınız&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aŞu kontrol için önleme etkinleştirildi&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cŞu kontrol için önleme devre dışı bırakıldı&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aŞu kontrol için cezalar etkinleştirildi&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cŞu kontrol için cezalar devre dışı bırakıldı&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cBu kontrol mevcut değil.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7artık &4{detection} &7kontrolünü &e{time} &7saniyeliğine atlıyor.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 &c{player} &7oyuncusuna şu nedenle uyarı verdiniz&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aAyrıntılı mod etkinleştirildi.'
verbose_disable: '&8[&2{prefix}&8] &cAyrıntılı mod devre dışı bırakıldı.'
notifications_enable: '&8[&2{prefix}&8] &aBildirimler etkinleştirildi.'
notifications_modified: '&8[&2{prefix}&8] &eBildirimler değiştirildi.'
notifications_disable: '&8[&2{prefix}&8] &cBildirimler devre dışı bırakıldı.'
awareness_notification: '&8[&2{prefix} Bildirim&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Dalga başlatıldı.'
wave_end_message: '&8[&2{prefix}&8]&c Dalga sona erdi. Toplam işlem sayısı: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c Dalga temizlendi.'
wave_add_message: '&8[&2{prefix}&8]&a {player} dalgaya eklendi.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} dalgadan çıkarıldı.'
full_wave_list: '&8[&2{prefix}&8]&c Dalga listesi dolu.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} dalgaya eklenmedi.'
unknown_command: '&fBilinmeyen komut. Yardım için "/help" yazın.'
failed_command: '&8[&2{prefix}&8]&c Komut başarısız oldu ({command}). Lütfen argümanları kontrol edip tekrar deneyin.'
successful_command: '&8[&2{prefix}&8]&a Komut başarıyla çalıştırıldı.'
massive_command_reason: '&8[&2{prefix}&8]&c Sebep çok uzun.'
```
</details>

## Indonesian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsol
no_permission: '&8[&2{prefix}&8]&c Kamu tidak memiliki izin untuk melakukan ini.'
player_not_found_message: '&8[&2{prefix}&8]&c Pemain tidak ditemukan.'
config_reload: '&8[&2{prefix}&8]&e Konfigurasi berhasil dimuat ulang.'
panic_mode_enable: '&8[&2{prefix}&8]&a Mode panik diaktifkan, semua pemeriksaan disetel ke diam dan tidak akan menghukum pemain.'
panic_mode_disable: '&8[&2{prefix}&8]&c Mode panik dinonaktifkan, semua pemeriksaan akan berjalan sesuai dengan konfigurasi.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 dikeluarkan karena&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Batas pemain untuk IP kamu telah tercapai.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Pelanggaran berhasil direset untuk pemain&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Data tersimpan berhasil dihapus untuk pemain&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Data tersimpan berhasil dihapus untuk pemeriksaan&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aKamu mengaktifkan pemeriksaan&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cKamu menonaktifkan pemeriksaan&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aKamu mengaktifkan pencegahan untuk pemeriksaan&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cKamu menonaktifkan pencegahan untuk pemeriksaan&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aKamu mengaktifkan hukuman untuk pemeriksaan&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cKamu menonaktifkan hukuman untuk pemeriksaan&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cPemeriksaan ini tidak ada.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7sekarang melewati pemeriksaan &4{detection} &7selama &e{time} &7detik.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Kamu memperingatkan &c{player} &7karena&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aMode verbose diaktifkan.'
verbose_disable: '&8[&2{prefix}&8] &cMode verbose dinonaktifkan.'
notifications_enable: '&8[&2{prefix}&8] &aNotifikasi diaktifkan.'
notifications_modified: '&8[&2{prefix}&8] &eNotifikasi telah diubah.'
notifications_disable: '&8[&2{prefix}&8] &cNotifikasi dinonaktifkan.'
awareness_notification: '&8[&2{prefix} Notifikasi&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Gelombang dimulai.'
wave_end_message: '&8[&2{prefix}&8]&c Gelombang telah berakhir dengan total {total} tindakan.'
wave_clear_message: '&8[&2{prefix}&8]&c Gelombang telah dibersihkan.'
wave_add_message: '&8[&2{prefix}&8]&a {player} telah ditambahkan ke gelombang.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} telah dihapus dari gelombang.'
full_wave_list: '&8[&2{prefix}&8]&c Daftar gelombang sudah penuh.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} belum ditambahkan ke gelombang.'
unknown_command: '&fPerintah tidak dikenal. Ketik "/help" untuk bantuan.'
failed_command: '&8[&2{prefix}&8]&c Perintah gagal ({command}). Silakan periksa argumenmu dan coba lagi.'
successful_command: '&8[&2{prefix}&8]&a Perintah berhasil dijalankan.'
massive_command_reason: '&8[&2{prefix}&8]&c Alasan terlalu panjang.'
```
</details>

## Italian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Console
no_permission: '&8[&2{prefix}&8]&c Non hai il permesso per interagire con questo.'
player_not_found_message: '&8[&2{prefix}&8]&c Giocatore non trovato.'
config_reload: '&8[&2{prefix}&8]&e Configurazione ricaricata con successo.'
panic_mode_enable: '&8[&2{prefix}&8]&a Modalità panico attivata, tutti i controlli sono silenziati e non puniranno i giocatori.'
panic_mode_disable: '&8[&2{prefix}&8]&c Modalità panico disattivata, tutti i controlli funzioneranno secondo la configurazione.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 è stato espulso per&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c È stato raggiunto il limite di giocatori per il tuo IP.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Infrazioni reimpostate con successo per il giocatore&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Dati memorizzati eliminati con successo per il giocatore&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Dati memorizzati eliminati con successo per il controllo&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aHai attivato il controllo&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cHai disattivato il controllo&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aHai attivato le prevenzioni per il controllo&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cHai disattivato le prevenzioni per il controllo&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aHai attivato le punizioni per il controllo&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cHai disattivato le punizioni per il controllo&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cQuesto controllo non esiste.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7ora sta bypassando il controllo &4{detection} &7per &e{time} &7secondi.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Hai avvertito &c{player} &7per&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aHai attivato la modalità verbosa.'
verbose_disable: '&8[&2{prefix}&8] &cHai disattivato la modalità verbosa.'
notifications_enable: '&8[&2{prefix}&8] &aHai attivato le notifiche.'
notifications_modified: '&8[&2{prefix}&8] &eHai modificato le notifiche.'
notifications_disable: '&8[&2{prefix}&8] &cHai disattivato le notifiche.'
awareness_notification: '&8[&2{prefix} Notifica&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c L’ondata è iniziata.'
wave_end_message: '&8[&2{prefix}&8]&c L’ondata è terminata con un totale di {total} azione/i.'
wave_clear_message: '&8[&2{prefix}&8]&c L’ondata è stata cancellata.'
wave_add_message: '&8[&2{prefix}&8]&a {player} è stato aggiunto all’ondata.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} è stato rimosso dall’ondata.'
full_wave_list: '&8[&2{prefix}&8]&c La lista dell’ondata è piena.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} non è stato aggiunto all’ondata.'
unknown_command: '&fComando sconosciuto. Digita "/help" per assistenza.'
failed_command: '&8[&2{prefix}&8]&c Comando fallito ({command}). Controlla gli argomenti e riprova.'
successful_command: '&8[&2{prefix}&8]&a Comando eseguito con successo.'
massive_command_reason: '&8[&2{prefix}&8]&c Il motivo è troppo lungo.'
```
</details>

## Dutch:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Console
no_permission: '&8[&2{prefix}&8]&c Je hebt geen toestemming om dit te doen.'
player_not_found_message: '&8[&2{prefix}&8]&c Speler niet gevonden.'
config_reload: '&8[&2{prefix}&8]&e Configuratie succesvol herladen.'
panic_mode_enable: '&8[&2{prefix}&8]&a Paniekmodus ingeschakeld, alle controles staan op stil en zullen spelers niet straffen.'
panic_mode_disable: '&8[&2{prefix}&8]&c Paniekmodus uitgeschakeld, alle controles draaien nu volgens de configuratie.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 is gekickt vanwege&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Het spelerslimiet voor jouw IP is bereikt.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Overtredingen succesvol gereset voor speler&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Opgeslagen gegevens succesvol verwijderd voor speler&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Opgeslagen gegevens succesvol verwijderd voor controle&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aJe hebt de controle ingeschakeld&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cJe hebt de controle uitgeschakeld&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aJe hebt preventies ingeschakeld voor de controle&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cJe hebt preventies uitgeschakeld voor de controle&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aJe hebt straffen ingeschakeld voor de controle&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cJe hebt straffen uitgeschakeld voor de controle&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cDeze controle bestaat niet.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7omzeilt nu de controle &4{detection} &7voor &e{time} &7seconden.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Je hebt &c{player} &7gewaarschuwd voor&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aJe hebt verbose ingeschakeld.'
verbose_disable: '&8[&2{prefix}&8] &cJe hebt verbose uitgeschakeld.'
notifications_enable: '&8[&2{prefix}&8] &aJe hebt meldingen ingeschakeld.'
notifications_modified: '&8[&2{prefix}&8] &eJe hebt meldingen aangepast.'
notifications_disable: '&8[&2{prefix}&8] &cJe hebt meldingen uitgeschakeld.'
awareness_notification: '&8[&2{prefix} Melding&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c De wave is gestart.'
wave_end_message: '&8[&2{prefix}&8]&c De wave is geëindigd met in totaal {total} actie(s).'
wave_clear_message: '&8[&2{prefix}&8]&c De wave is leeggemaakt.'
wave_add_message: '&8[&2{prefix}&8]&a {player} is toegevoegd aan de wave.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} is verwijderd uit de wave.'
full_wave_list: '&8[&2{prefix}&8]&c De wave-lijst is vol.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} is niet toegevoegd aan de wave.'
unknown_command: '&fOnbekend commando. Typ "/help" voor hulp.'
failed_command: '&8[&2{prefix}&8]&c Commando mislukt ({command}). Controleer je argumenten en probeer het opnieuw.'
successful_command: '&8[&2{prefix}&8]&a Commando succesvol uitgevoerd.'
massive_command_reason: '&8[&2{prefix}&8]&c De reden is te lang.'
```
</details>

## Vietnamese:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Bảng điều khiển
no_permission: '&8[&2{prefix}&8]&c Bạn không có quyền để thực hiện thao tác này.'
player_not_found_message: '&8[&2{prefix}&8]&c Không tìm thấy người chơi.'
config_reload: '&8[&2{prefix}&8]&e Cấu hình đã được tải lại thành công.'
panic_mode_enable: '&8[&2{prefix}&8]&a Đã bật chế độ hoảng loạn, tất cả kiểm tra đều được đặt thành im lặng và sẽ không phạt người chơi.'
panic_mode_disable: '&8[&2{prefix}&8]&c Đã tắt chế độ hoảng loạn, tất cả kiểm tra sẽ chạy theo cấu hình chuẩn.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 đã bị đá khỏi máy chủ vì&4 {reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Đã đạt giới hạn người chơi từ IP của bạn.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Đã đặt lại vi phạm thành công cho người chơi&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Đã xoá dữ liệu lưu trữ thành công cho người chơi&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Đã xoá dữ liệu lưu trữ thành công cho kiểm tra&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aBạn đã bật kiểm tra&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cBạn đã tắt kiểm tra&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aBạn đã bật ngăn chặn cho kiểm tra&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cBạn đã tắt ngăn chặn cho kiểm tra&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aBạn đã bật hình phạt cho kiểm tra&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cBạn đã tắt hình phạt cho kiểm tra&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cKiểm tra này không tồn tại.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7hiện đang bỏ qua kiểm tra &4{detection} &7trong &e{time} &7giây.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Bạn đã cảnh báo &c{player} &7vì&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aBạn đã bật chế độ chi tiết.'
verbose_disable: '&8[&2{prefix}&8] &cBạn đã tắt chế độ chi tiết.'
notifications_enable: '&8[&2{prefix}&8] &aBạn đã bật thông báo.'
notifications_modified: '&8[&2{prefix}&8] &eBạn đã chỉnh sửa thông báo.'
notifications_disable: '&8[&2{prefix}&8] &cBạn đã tắt thông báo.'
awareness_notification: '&8[&2{prefix} Thông báo&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Đợt kiểm tra đã bắt đầu.'
wave_end_message: '&8[&2{prefix}&8]&c Đợt kiểm tra kết thúc với tổng số {total} hành động.'
wave_clear_message: '&8[&2{prefix}&8]&c Đợt kiểm tra đã được xoá.'
wave_add_message: '&8[&2{prefix}&8]&a {player} đã được thêm vào đợt kiểm tra.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} đã bị xoá khỏi đợt kiểm tra.'
full_wave_list: '&8[&2{prefix}&8]&c Danh sách đợt kiểm tra đã đầy.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} chưa được thêm vào đợt kiểm tra.'
unknown_command: '&fLệnh không xác định. Vui lòng nhập "/help" để được trợ giúp.'
failed_command: '&8[&2{prefix}&8]&c Lệnh thất bại ({command}). Hãy kiểm tra lại tham số và thử lại.'
successful_command: '&8[&2{prefix}&8]&a Lệnh đã thực thi thành công.'
massive_command_reason: '&8[&2{prefix}&8]&c Lý do quá dài.'
```
</details>

## Korean:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: 콘솔
no_permission: '&8[&2{prefix}&8]&c 이 작업을 수행할 권한이 없습니다.'
player_not_found_message: '&8[&2{prefix}&8]&c 플레이어를 찾을 수 없습니다.'
config_reload: '&8[&2{prefix}&8]&e 구성 파일이 성공적으로 다시 로드되었습니다.'
panic_mode_enable: '&8[&2{prefix}&8]&a 패닉 모드가 활성화되었습니다. 모든 검사들이 조용히 작동하며 플레이어에게 처벌하지 않습니다.'
panic_mode_disable: '&8[&2{prefix}&8]&c 패닉 모드가 비활성화되었습니다. 모든 검사가 기본 설정에 따라 작동합니다.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 님이 &4{reason} &7으로 서버에서 퇴장당했습니다.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c 귀하의 IP에서 최대 플레이어 수에 도달했습니다.'
player_violation_reset_message: '&8[&2{prefix}&8]&a 플레이어의 위반 기록이 성공적으로 초기화되었습니다&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a 플레이어의 저장된 데이터가 성공적으로 삭제되었습니다&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a 검사에 대한 저장된 데이터가 성공적으로 삭제되었습니다&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &a검사 활성화됨&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c검사 비활성화됨&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a검사의 처벌 기능이 활성화되었습니다&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c검사의 처벌 기능이 비활성화되었습니다&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a검사의 자동 처벌이 활성화되었습니다&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c검사의 자동 처벌이 비활성화되었습니다&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c해당 검사는 존재하지 않습니다.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7님은 &4{detection} &7검사를 &e{time} &7초 동안 우회하고 있습니다.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 {player} 님에게 경고를 보냈습니다&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a상세 모드를 활성화했습니다.'
verbose_disable: '&8[&2{prefix}&8] &c상세 모드를 비활성화했습니다.'
notifications_enable: '&8[&2{prefix}&8] &a알림을 활성화했습니다.'
notifications_modified: '&8[&2{prefix}&8] &e알림 설정이 수정되었습니다.'
notifications_disable: '&8[&2{prefix}&8] &c알림을 비활성화했습니다.'
awareness_notification: '&8[&2{prefix} 알림&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c 웨이브가 시작되었습니다.'
wave_end_message: '&8[&2{prefix}&8]&c 웨이브가 종료되었습니다. 총 처리된 작업 수: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c 웨이브가 초기화되었습니다.'
wave_add_message: '&8[&2{prefix}&8]&a {player} 님이 웨이브에 추가되었습니다.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} 님이 웨이브에서 제거되었습니다.'
full_wave_list: '&8[&2{prefix}&8]&c 웨이브 목록이 가득 찼습니다.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} 님은 웨이브에 추가되지 않았습니다.'
unknown_command: '&f알 수 없는 명령어입니다. "/help" 명령어를 사용하여 도움말을 확인하세요.'
failed_command: '&8[&2{prefix}&8]&c 명령어 실행 실패 ({command}). 인수를 다시 확인해 주세요.'
successful_command: '&8[&2{prefix}&8]&a 명령어가 성공적으로 실행되었습니다.'
massive_command_reason: '&8[&2{prefix}&8]&c 이유가 너무 깁니다.'
```
</details>

## Czech:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konzole
no_permission: '&8[&2{prefix}&8]&c Nemáte oprávnění k provedení této akce.'
player_not_found_message: '&8[&2{prefix}&8]&c Hráč nebyl nalezen.'
config_reload: '&8[&2{prefix}&8]&e Konfigurační soubor byl úspěšně znovu načten.'
panic_mode_enable: '&8[&2{prefix}&8]&a Panický režim byl aktivován. Všechny kontroly tiše běží a nehází žádné tresty.'
panic_mode_disable: '&8[&2{prefix}&8]&c Panický režim byl deaktivován. Všechny kontroly fungují normálně.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 byl vyhozen ze serveru z důvodu: &4{reason}&7.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Byl dosažen maximální počet hráčů pro vaši IP adresu.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Záznamy o porušení hráče byly úspěšně resetovány&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Uložená data hráče byla úspěšně smazána&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Uložená data kontroly byla úspěšně smazána&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aKontrola byla povolena&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cKontrola byla zakázána&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aTrestání kontroly bylo povoleno&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cTrestání kontroly bylo zakázáno&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aAutomatické tresty byly povoleny pro kontrolu&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cAutomatické tresty byly zakázány pro kontrolu&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cTato kontrola neexistuje.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7obchází kontrolu &4{detection} &7po dobu &e{time} &7sekund.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Hráči {player} byla udělena výstraha&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aPodrobný režim byl povolen.'
verbose_disable: '&8[&2{prefix}&8] &cPodrobný režim byl zakázán.'
notifications_enable: '&8[&2{prefix}&8] &aOznámení byla povolena.'
notifications_modified: '&8[&2{prefix}&8] &eNastavení oznámení bylo upraveno.'
notifications_disable: '&8[&2{prefix}&8] &cOznámení byla zakázána.'
awareness_notification: '&8[&2{prefix} Upozornění&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Vlna byla spuštěna.'
wave_end_message: '&8[&2{prefix}&8]&c Vlna skončila. Celkem zpracováno: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c Vlna byla vymazána.'
wave_add_message: '&8[&2{prefix}&8]&a {player} byl přidán do vlny.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} byl odebrán z vlny.'
full_wave_list: '&8[&2{prefix}&8]&c Seznam vlny je plný.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nebyl přidán do vlny.'
unknown_command: '&fNeznámý příkaz. Zkuste "/help" pro seznam příkazů.'
failed_command: '&8[&2{prefix}&8]&c Příkaz se nepodařilo vykonat ({command}). Zkontrolujte argumenty.'
successful_command: '&8[&2{prefix}&8]&a Příkaz byl úspěšně vykonán.'
massive_command_reason: '&8[&2{prefix}&8]&c Zadaný důvod je příliš dlouhý.'
```
</details>

## Thai:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: คอนโซล
no_permission: '&8[&2{prefix}&8]&c คุณไม่มีสิทธิ์ในการดำเนินการนี้'
player_not_found_message: '&8[&2{prefix}&8]&c ไม่พบผู้เล่น'
config_reload: '&8[&2{prefix}&8]&e โหลดไฟล์การตั้งค่าใหม่เรียบร้อยแล้ว'
panic_mode_enable: '&8[&2{prefix}&8]&a โหมดตื่นตระหนกถูกเปิดใช้งาน การตรวจสอบทั้งหมดจะทำงานแบบเงียบ ๆ โดยไม่ลงโทษ'
panic_mode_disable: '&8[&2{prefix}&8]&c โหมดตื่นตระหนกถูกปิดใช้งาน การตรวจสอบทั้งหมดจะกลับสู่ปกติ'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 ถูกเตะออกจากเซิร์ฟเวอร์ด้วยเหตุผล: &4{reason}&7.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c มีจำนวนผู้เล่นสูงสุดที่อนุญาตต่อ IP แล้ว'
player_violation_reset_message: '&8[&2{prefix}&8]&a ล้างข้อมูลการกระทำผิดของผู้เล่นเรียบร้อยแล้ว&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a ลบข้อมูลที่เก็บไว้ของผู้เล่นเรียบร้อยแล้ว&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a ลบข้อมูลของการตรวจสอบเรียบร้อยแล้ว&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aเปิดใช้งานการตรวจสอบแล้ว&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cปิดการใช้งานการตรวจสอบแล้ว&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aเปิดใช้งานโหมดลงโทษแล้ว&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cปิดโหมดลงโทษแล้ว&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aเปิดใช้งานการลงโทษอัตโนมัติสำหรับการตรวจสอบนี้แล้ว&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cปิดการลงโทษอัตโนมัติสำหรับการตรวจสอบนี้แล้ว&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cไม่มีการตรวจสอบนี้อยู่'
bypass_message: '&8[&2{prefix}&8] &c{player} &7กำลังข้ามการตรวจสอบ &4{detection} &7เป็นเวลา &e{time} &7วินาที'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 ผู้เล่น {player} ได้รับคำเตือน&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aเปิดใช้งานโหมดแสดงรายละเอียดแล้ว'
verbose_disable: '&8[&2{prefix}&8] &cปิดโหมดแสดงรายละเอียดแล้ว'
notifications_enable: '&8[&2{prefix}&8] &aเปิดใช้งานการแจ้งเตือนแล้ว'
notifications_modified: '&8[&2{prefix}&8] &eมีการปรับเปลี่ยนการตั้งค่าการแจ้งเตือน'
notifications_disable: '&8[&2{prefix}&8] &cปิดการแจ้งเตือนแล้ว'
awareness_notification: '&8[&2{prefix} แจ้งเตือน&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c เริ่มการกวาดล้างแล้ว'
wave_end_message: '&8[&2{prefix}&8]&c การกวาดล้างเสร็จสิ้นแล้ว รวมทั้งหมด: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c ล้างรายการการกวาดล้างแล้ว'
wave_add_message: '&8[&2{prefix}&8]&a เพิ่ม {player} ไปยังรายการการกวาดล้างแล้ว'
wave_remove_message: '&8[&2{prefix}&8]&c ลบ {player} จากรายการการกวาดล้างแล้ว'
full_wave_list: '&8[&2{prefix}&8]&c รายการการกวาดล้างเต็มแล้ว'
wave_not_added_message: '&8[&2{prefix}&8]&c ไม่สามารถเพิ่ม {player} ไปยังรายการการกวาดล้างได้'
unknown_command: '&fคำสั่งไม่ถูกต้อง ลองใช้ "/help" เพื่อดูคำสั่งที่มีอยู่'
failed_command: '&8[&2{prefix}&8]&c ไม่สามารถดำเนินการคำสั่งได้ ({command}) กรุณาตรวจสอบอาร์กิวเมนต์'
successful_command: '&8[&2{prefix}&8]&a ดำเนินการคำสั่งเรียบร้อยแล้ว'
massive_command_reason: '&8[&2{prefix}&8]&c เหตุผลที่ระบุยาวเกินไป'
```
</details>

## Hungarian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konzol
no_permission: '&8[&2{prefix}&8]&c Nincs jogosultságod ehhez a művelethez'
player_not_found_message: '&8[&2{prefix}&8]&c A játékos nem található'
config_reload: '&8[&2{prefix}&8]&e A konfigurációs fájl sikeresen újratöltve'
panic_mode_enable: '&8[&2{prefix}&8]&a Pánik mód bekapcsolva – minden ellenőrzés csendesen működik, büntetés nélkül'
panic_mode_disable: '&8[&2{prefix}&8]&c Pánik mód kikapcsolva – minden ellenőrzés visszatér a normál működéshez'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 ki lett rúgva a szerverről – ok: &4{reason}&7.'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Az IP-címen engedélyezett játékosok száma elérte a maximumot'
player_violation_reset_message: '&8[&2{prefix}&8]&a A játékos szabálysértési adatai törölve&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a A játékos tárolt adatai törölve&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Az ellenőrzés adatai törölve&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aEllenőrzés engedélyezve&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cEllenőrzés letiltva&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aBüntetési mód engedélyezve&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cBüntetési mód letiltva&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aAutomatikus büntetés engedélyezve ennél az ellenőrzésnél&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cAutomatikus büntetés letiltva ennél az ellenőrzésnél&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cEz az ellenőrzés nem létezik'
bypass_message: '&8[&2{prefix}&8] &c{player} &7átugorja az ellenőrzést &4{detection} &7időtartam: &e{time} &7másodperc'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 {player} figyelmeztetve lett&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aRészletes mód engedélyezve'
verbose_disable: '&8[&2{prefix}&8] &cRészletes mód letiltva'
notifications_enable: '&8[&2{prefix}&8] &aÉrtesítések engedélyezve'
notifications_modified: '&8[&2{prefix}&8] &eÉrtesítési beállítások módosítva'
notifications_disable: '&8[&2{prefix}&8] &cÉrtesítések letiltva'
awareness_notification: '&8[&2{prefix} Figyelmeztetés&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Eltávolítási hullám elindítva'
wave_end_message: '&8[&2{prefix}&8]&c Eltávolítási hullám véget ért – összesen: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c Hullám lista törölve'
wave_add_message: '&8[&2{prefix}&8]&a {player} hozzáadva a hullám listához'
wave_remove_message: '&8[&2{prefix}&8]&c {player} eltávolítva a hullám listáról'
full_wave_list: '&8[&2{prefix}&8]&c A hullám lista megtelt'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nem adható hozzá a hullám listához'
unknown_command: '&fIsmeretlen parancs – használd a "/help" parancsot a lehetőségekhez'
failed_command: '&8[&2{prefix}&8]&c A parancs végrehajtása sikertelen ({command}) – ellenőrizd az argumentumokat'
successful_command: '&8[&2{prefix}&8]&a Parancs sikeresen végrehajtva'
massive_command_reason: '&8[&2{prefix}&8]&c A megadott ok túl hosszú'
```
</details>

## Arabic:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: وحدة التحكم
no_permission: '&8[&2{prefix}&8]&c ليس لديك صلاحية للتفاعل مع هذا.'
player_not_found_message: '&8[&2{prefix}&8]&c لم يتم العثور على اللاعب.'
config_reload: '&8[&2{prefix}&8]&e تم إعادة تحميل الإعدادات بنجاح.'
panic_mode_enable: '&8[&2{prefix}&8]&a تم تفعيل وضع الذعر، جميع الفحوصات أصبحت صامتة ولن تعاقب اللاعبين.'
panic_mode_disable: '&8[&2{prefix}&8]&c تم تعطيل وضع الذعر، جميع الفحوصات ستعمل الآن وفقًا لإعدادات التكوين.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c تم طرد اللاعب {player}&7 بسبب &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c تم الوصول إلى حد عدد اللاعبين على عنوان الـ IP الخاص بك.'
player_violation_reset_message: '&8[&2{prefix}&8]&a تم إعادة تعيين الانتهاكات بنجاح للاعب&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a تم حذف البيانات المخزنة بنجاح للاعب&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a تم حذف البيانات المخزنة بنجاح للفحص&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aلقد قمت بتفعيل الفحص&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cلقد قمت بتعطيل الفحص&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aلقد قمت بتفعيل إجراءات الوقاية للفحص&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cلقد قمت بتعطيل إجراءات الوقاية للفحص&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aلقد قمت بتفعيل العقوبات للفحص&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cلقد قمت بتعطيل العقوبات للفحص&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cهذا الفحص غير موجود.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7يتجاوز الآن فحص &4{detection} &7لمدة &e{time} &7ثانية.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 لقد قمت بتحذير &c{player} &7بسبب&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aلقد قمت بتفعيل الوضع المفصل.'
verbose_disable: '&8[&2{prefix}&8] &cلقد قمت بتعطيل الوضع المفصل.'
notifications_enable: '&8[&2{prefix}&8] &aلقد قمت بتفعيل الإشعارات.'
notifications_modified: '&8[&2{prefix}&8] &eلقد قمت بتعديل الإشعارات.'
notifications_disable: '&8[&2{prefix}&8] &cلقد قمت بتعطيل الإشعارات.'
awareness_notification: '&8[&2{prefix} إشعار&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c بدأ الموجة.'
wave_end_message: '&8[&2{prefix}&8]&c انتهت الموجة بإجمالي {total} إجراء(ات).'
wave_clear_message: '&8[&2{prefix}&8]&c تم مسح الموجة.'
wave_add_message: '&8[&2{prefix}&8]&a تمت إضافة {player} إلى الموجة.'
wave_remove_message: '&8[&2{prefix}&8]&c تمت إزالة {player} من الموجة.'
full_wave_list: '&8[&2{prefix}&8]&c قائمة الموجة ممتلئة.'
wave_not_added_message: '&8[&2{prefix}&8]&c لم تتم إضافة {player} إلى الموجة.'
unknown_command: '&fأمر غير معروف. يرجى كتابة "/help" للمساعدة.'
failed_command: '&8[&2{prefix}&8]&c فشل الأمر ({command}). يرجى التحقق من الوسائط وحاول مرة أخرى.'
successful_command: '&8[&2{prefix}&8]&a تم تنفيذ الأمر بنجاح.'
massive_command_reason: '&8[&2{prefix}&8]&c طول السبب طويل جداً.'
```
</details>

## Japanese:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: コンソール
no_permission: '&8[&2{prefix}&8]&c この操作を行う権限がありません。'
player_not_found_message: '&8[&2{prefix}&8]&c プレイヤーが見つかりません。'
config_reload: '&8[&2{prefix}&8]&e 設定ファイルの再読み込みに成功しました。'
panic_mode_enable: '&8[&2{prefix}&8]&a パニックモードが有効になりました。すべてのチェックはサイレントモードになり、プレイヤーを処罰しません。'
panic_mode_disable: '&8[&2{prefix}&8]&c パニックモードが無効になりました。すべてのチェックは設定通りに実行されます。'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 は &4{reason} &7のためにキックされました。'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c あなたのIPのプレイヤー制限に達しました。'
player_violation_reset_message: '&8[&2{prefix}&8]&a プレイヤー &8: &2{player} の違反が正常にリセットされました。'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a プレイヤー &8: &2{player} の保存データが正常に削除されました。'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a チェック &8: &2{check} の保存データが正常に削除されました。'
check_enable_message: '&8[&2{prefix}&8] &a チェックを有効にしました &8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c チェックを無効にしました &8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a チェックの予防措置を有効にしました &8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c チェックの予防措置を無効にしました &8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a チェックの処罰を有効にしました &8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c チェックの処罰を無効にしました &8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c このチェックは存在しません。'
bypass_message: '&8[&2{prefix}&8] &c{player} は &4{detection} &7チェックを &e{time} &7秒間バイパスしています。'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 {player} に対して警告を行いました &8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a 詳細モードを有効にしました。'
verbose_disable: '&8[&2{prefix}&8] &c 詳細モードを無効にしました。'
notifications_enable: '&8[&2{prefix}&8] &a 通知を有効にしました。'
notifications_modified: '&8[&2{prefix}&8] &e 通知設定を変更しました。'
notifications_disable: '&8[&2{prefix}&8] &c 通知を無効にしました。'
awareness_notification: '&8[&2{prefix} 通知&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c ウェーブが開始されました。'
wave_end_message: '&8[&2{prefix}&8]&c ウェーブが終了しました。合計アクション数: {total}'
wave_clear_message: '&8[&2{prefix}&8]&c ウェーブがクリアされました。'
wave_add_message: '&8[&2{prefix}&8]&a {player} がウェーブに追加されました。'
wave_remove_message: '&8[&2{prefix}&8]&c {player} がウェーブから削除されました。'
full_wave_list: '&8[&2{prefix}&8]&c ウェーブリストが満杯です。'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} はウェーブに追加されていません。'
unknown_command: '&f 不明なコマンドです。"/help" を入力してヘルプを表示してください。'
failed_command: '&8[&2{prefix}&8]&c コマンド実行に失敗しました ({command})。引数を確認してもう一度お試しください。'
successful_command: '&8[&2{prefix}&8]&a コマンドが正常に実行されました。'
massive_command_reason: '&8[&2{prefix}&8]&c 理由が長すぎます。'
```
</details>

## Ukranian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Консоль
no_permission: '&8[&2{prefix}&8]&c У вас немає дозволу для взаємодії з цим.'
player_not_found_message: '&8[&2{prefix}&8]&c Гравця не знайдено.'
config_reload: '&8[&2{prefix}&8]&e Конфігурацію успішно перезавантажено.'
panic_mode_enable: '&8[&2{prefix}&8]&a Режим паніки увімкнено, всі перевірки працюють у прихованому режимі і не карають гравців.'
panic_mode_disable: '&8[&2{prefix}&8]&c Режим паніки вимкнено, всі перевірки тепер працюють згідно з налаштуваннями.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c Гравця {player}&7 було виключено через &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Досягнуто ліміт гравців на вашу IP-адресу.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Порушення гравця успішно скинуто&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Збережені дані гравця успішно видалено&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Збережені дані перевірки успішно видалено&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aВи ввімкнули перевірку&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cВи вимкнули перевірку&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aВи ввімкнули запобігання для перевірки&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cВи вимкнули запобігання для перевірки&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aВи ввімкнули покарання для перевірки&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cВи вимкнули покарання для перевірки&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cТакої перевірки не існує.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7тепер обходить перевірку &4{detection} &7протягом &e{time} &7секунд.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Ви попередили &c{player} &7через&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aВи ввімкнули докладний режим.'
verbose_disable: '&8[&2{prefix}&8] &cВи вимкнули докладний режим.'
notifications_enable: '&8[&2{prefix}&8] &aВи ввімкнули сповіщення.'
notifications_modified: '&8[&2{prefix}&8] &eВи змінили налаштування сповіщень.'
notifications_disable: '&8[&2{prefix}&8] &cВи вимкнули сповіщення.'
awareness_notification: '&8[&2{prefix} Сповіщення&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Хвиля починається.'
wave_end_message: '&8[&2{prefix}&8]&c Хвиля завершилась з загальною кількістю дій {total}.'
wave_clear_message: '&8[&2{prefix}&8]&c Хвиля очищена.'
wave_add_message: '&8[&2{prefix}&8]&a {player} додано до хвилі.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} видалено з хвилі.'
full_wave_list: '&8[&2{prefix}&8]&c Список хвилі заповнений.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} не додано до хвилі.'
unknown_command: '&fНевідома команда. Введіть "/help" для допомоги.'
failed_command: '&8[&2{prefix}&8]&c Команда не виконана ({command}). Будь ласка, перевірте аргументи і спробуйте знову.'
successful_command: '&8[&2{prefix}&8]&a Команда виконана успішно.'
massive_command_reason: '&8[&2{prefix}&8]&c Причина занадто довга.'
```
</details>

## Swedish:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsol
no_permission: '&8[&2{prefix}&8]&c Du har inte behörighet att interagera med detta.'
player_not_found_message: '&8[&2{prefix}&8]&c Spelaren hittades inte.'
config_reload: '&8[&2{prefix}&8]&e Konfigurationen laddades om framgångsrikt.'
panic_mode_enable: '&8[&2{prefix}&8]&a Panikläge aktiverat, alla kontroller är tysta och straffar inte spelare.'
panic_mode_disable: '&8[&2{prefix}&8]&c Panikläge avaktiverat, alla kontroller körs nu enligt konfigurationen.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 blev utkastad på grund av &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Spelargränsen för din IP har nåtts.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Överträdelser återställda för spelaren&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Sparad data raderad för spelaren&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Sparad data raderad för kontrollen&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aDu har aktiverat kontrollen&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cDu har inaktiverat kontrollen&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aDu har aktiverat förebyggande åtgärder för kontrollen&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cDu har inaktiverat förebyggande åtgärder för kontrollen&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aDu har aktiverat straff för kontrollen&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cDu har inaktiverat straff för kontrollen&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cDenna kontroll finns inte.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7går nu förbi kontrollen &4{detection} &7i &e{time} &7sekunder.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Du varnade &c{player} &7för&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aDu har aktiverat detaljerad loggning.'
verbose_disable: '&8[&2{prefix}&8] &cDu har inaktiverat detaljerad loggning.'
notifications_enable: '&8[&2{prefix}&8] &aDu har aktiverat notiser.'
notifications_modified: '&8[&2{prefix}&8] &eDu har ändrat notisinställningarna.'
notifications_disable: '&8[&2{prefix}&8] &cDu har inaktiverat notiser.'
awareness_notification: '&8[&2{prefix} Notis&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Våg startar.'
wave_end_message: '&8[&2{prefix}&8]&c Vågen avslutades med totalt {total} åtgärd(er).'
wave_clear_message: '&8[&2{prefix}&8]&c Vågen rensades.'
wave_add_message: '&8[&2{prefix}&8]&a {player} lades till i vågen.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} togs bort från vågen.'
full_wave_list: '&8[&2{prefix}&8]&c Vågens lista är full.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} har inte lagts till i vågen.'
unknown_command: '&fOkänt kommando. Skriv "/help" för hjälp.'
failed_command: '&8[&2{prefix}&8]&c Kommandot misslyckades ({command}). Kontrollera dina argument och försök igen.'
successful_command: '&8[&2{prefix}&8]&a Kommandot lyckades.'
massive_command_reason: '&8[&2{prefix}&8]&c Anledningen är för lång.'
```
</details>

## Danish:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsol
no_permission: '&8[&2{prefix}&8]&c Du har ikke tilladelse til at interagere med dette.'
player_not_found_message: '&8[&2{prefix}&8]&c Spilleren blev ikke fundet.'
config_reload: '&8[&2{prefix}&8]&e Konfigurationen blev genindlæst med succes.'
panic_mode_enable: '&8[&2{prefix}&8]&a Paniktilstand aktiveret, alle kontroller kører i stille tilstand og straffer ikke spillere.'
panic_mode_disable: '&8[&2{prefix}&8]&c Paniktilstand deaktiveret, alle kontroller kører nu efter konfiguration.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 blev smidt ud på grund af &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Spillertallet for din IP er nået.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Overtrædelser blev nulstillet for spilleren&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Gemte data blev slettet for spilleren&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Gemte data blev slettet for kontrollen&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aDu har aktiveret kontrollen&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cDu har deaktiveret kontrollen&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aDu har aktiveret forebyggelse for kontrollen&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cDu har deaktiveret forebyggelse for kontrollen&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aDu har aktiveret straf for kontrollen&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cDu har deaktiveret straf for kontrollen&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cDenne kontrol findes ikke.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7omgår nu kontrollen &4{detection} &7i &e{time} &7sekunder.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Du advarede &c{player} &7for&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aDu har aktiveret detaljeret logning.'
verbose_disable: '&8[&2{prefix}&8] &cDu har deaktiveret detaljeret logning.'
notifications_enable: '&8[&2{prefix}&8] &aDu har aktiveret notifikationer.'
notifications_modified: '&8[&2{prefix}&8] &eDu har ændret notifikationsindstillinger.'
notifications_disable: '&8[&2{prefix}&8] &cDu har deaktiveret notifikationer.'
awareness_notification: '&8[&2{prefix} Notifikation&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Bølgen starter.'
wave_end_message: '&8[&2{prefix}&8]&c Bølgen er slut med i alt {total} handling(er).'
wave_clear_message: '&8[&2{prefix}&8]&c Bølgen blev ryddet.'
wave_add_message: '&8[&2{prefix}&8]&a {player} blev tilføjet til bølgen.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} blev fjernet fra bølgen.'
full_wave_list: '&8[&2{prefix}&8]&c Bølgens liste er fuld.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} er ikke tilføjet til bølgen.'
unknown_command: '&fUkendt kommando. Skriv "/help" for hjælp.'
failed_command: '&8[&2{prefix}&8]&c Kommandoen mislykkedes ({command}). Tjek dine argumenter og prøv igen.'
successful_command: '&8[&2{prefix}&8]&a Kommandoen lykkedes.'
massive_command_reason: '&8[&2{prefix}&8]&c Årsagen er for lang.'
```
</details>

## Romanian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Consolă
no_permission: '&8[&2{prefix}&8]&c Nu ai permisiunea să interacționezi cu acest lucru.'
player_not_found_message: '&8[&2{prefix}&8]&c Jucătorul nu a fost găsit.'
config_reload: '&8[&2{prefix}&8]&e Configurația a fost reîncărcată cu succes.'
panic_mode_enable: '&8[&2{prefix}&8]&a Modul panică activat, toate verificările sunt în modul silențios și nu vor pedepsi jucătorii.'
panic_mode_disable: '&8[&2{prefix}&8]&c Modul panică dezactivat, toate verificările vor rula acum conform configurației.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c Jucătorul {player}&7 a fost dat afară pentru &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c A fost atinsă limita de jucători pentru IP-ul tău.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Încălcările jucătorului au fost resetate cu succes&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Datele stocate ale jucătorului au fost șterse cu succes&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Datele stocate ale verificării au fost șterse cu succes&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &aAi activat verificarea&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &cAi dezactivat verificarea&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &aAi activat prevențiile pentru verificare&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &cAi dezactivat prevențiile pentru verificare&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &aAi activat pedepsele pentru verificare&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &cAi dezactivat pedepsele pentru verificare&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &cAceastă verificare nu există.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7acum evită verificarea &4{detection} &7pentru &e{time} &7secunde.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Ai avertizat &c{player} &7pentru&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &aAi activat modul detaliat.'
verbose_disable: '&8[&2{prefix}&8] &cAi dezactivat modul detaliat.'
notifications_enable: '&8[&2{prefix}&8] &aAi activat notificările.'
notifications_modified: '&8[&2{prefix}&8] &eAi modificat notificările.'
notifications_disable: '&8[&2{prefix}&8] &cAi dezactivat notificările.'
awareness_notification: '&8[&2{prefix} Notificare&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Valul începe.'
wave_end_message: '&8[&2{prefix}&8]&c Valul s-a terminat cu un total de {total} acțiuni.'
wave_clear_message: '&8[&2{prefix}&8]&c Valul a fost curățat.'
wave_add_message: '&8[&2{prefix}&8]&a {player} a fost adăugat în val.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} a fost eliminat din val.'
full_wave_list: '&8[&2{prefix}&8]&c Lista valului este plină.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nu a fost adăugat în val.'
unknown_command: '&fComandă necunoscută. Te rugăm să tastezi "/help" pentru ajutor.'
failed_command: '&8[&2{prefix}&8]&c Comanda a eșuat ({command}). Verifică argumentele și încearcă din nou.'
successful_command: '&8[&2{prefix}&8]&a Comandă executată cu succes.'
massive_command_reason: '&8[&2{prefix}&8]&c Motivul este prea lung.'
```
</details>

## Slovak:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konzola
no_permission: '&8[&2{prefix}&8]&c Nemáte povolenie na interakciu s týmto.'
player_not_found_message: '&8[&2{prefix}&8]&c Hráč nebol nájdený.'
config_reload: '&8[&2{prefix}&8]&e Konfigurácia bola úspešne znovu načítaná.'
panic_mode_enable: '&8[&2{prefix}&8]&a Panikový režim zapnutý, všetky kontroly sú v tichom režime a nebudú hráčov trestať.'
panic_mode_disable: '&8[&2{prefix}&8]&c Panikový režim vypnutý, všetky kontroly budú teraz bežať podľa konfigurácie.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c Hráč {player}&7 bol vykopnutý z dôvodu &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Dosiahol sa limit hráčov pre vašu IP adresu.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Porušenia úspešne resetované pre hráča&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Uložené údaje úspešne vymazané pre hráča&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Uložené údaje úspešne vymazané pre kontrolu&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &a Aktivovali ste kontrolu&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c Deaktivovali ste kontrolu&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a Aktivovali ste prevenciu pre kontrolu&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c Deaktivovali ste prevenciu pre kontrolu&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a Aktivovali ste tresty pre kontrolu&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c Deaktivovali ste tresty pre kontrolu&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c Táto kontrola neexistuje.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7teraz obchádza kontrolu &4{detection} &7na &e{time} &7sekúnd.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Varovali ste &c{player} &7z dôvodu&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a Aktivovali ste podrobný režim.'
verbose_disable: '&8[&2{prefix}&8] &c Deaktivovali ste podrobný režim.'
notifications_enable: '&8[&2{prefix}&8] &a Aktivovali ste notifikácie.'
notifications_modified: '&8[&2{prefix}&8] &e Zmenili ste nastavenia notifikácií.'
notifications_disable: '&8[&2{prefix}&8] &c Deaktivovali ste notifikácie.'
awareness_notification: '&8[&2{prefix} Notifikácia&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Vlna začína.'
wave_end_message: '&8[&2{prefix}&8]&c Vlna skončila s celkovým počtom {total} akcií.'
wave_clear_message: '&8[&2{prefix}&8]&c Vlna bola vyčistená.'
wave_add_message: '&8[&2{prefix}&8]&a {player} bol pridaný do vlny.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} bol odstránený z vlny.'
full_wave_list: '&8[&2{prefix}&8]&c Zoznam vln je plný.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nebol pridaný do vlny.'
unknown_command: '&f Neznámy príkaz. Napíšte "/help" pre pomoc.'
failed_command: '&8[&2{prefix}&8]&c Príkaz zlyhal ({command}). Skontrolujte argumenty a skúste to znova.'
successful_command: '&8[&2{prefix}&8]&a Príkaz bol úspešný.'
massive_command_reason: '&8[&2{prefix}&8]&c Dĺžka dôvodu je príliš veľká.'
```
</details>

## Hebrew:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: קונסולה
no_permission: '&8[&2{prefix}&8]&c אין לך הרשאה לפעול על כך.'
player_not_found_message: '&8[&2{prefix}&8]&c השחקן לא נמצא.'
config_reload: '&8[&2{prefix}&8]&e התצורה נטענה מחדש בהצלחה.'
panic_mode_enable: '&8[&2{prefix}&8]&a מצב פניקה מופעל, כל הבדיקות במצב שקט ולא יענישו שחקנים.'
panic_mode_disable: '&8[&2{prefix}&8]&c מצב פניקה מושבת, כל הבדיקות יפעלו כעת בהתאם להגדרות.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c {player}&7 הושלך בגלל &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c הושג המגבלה למספר השחקנים מכתובת ה-IP שלך.'
player_violation_reset_message: '&8[&2{prefix}&8]&a ההפרות לאיפוס הצליח עבור השחקן&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a הנתונים שנשמרו נמחקו בהצלחה עבור השחקן&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a הנתונים שנשמרו נמחקו בהצלחה עבור הבדיקה&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &a הפעלת את הבדיקה&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c השבתת את הבדיקה&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a הפעלת מניעת עבירות עבור הבדיקה&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c השבתת מניעת עבירות עבור הבדיקה&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a הפעלת ענישה עבור הבדיקה&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c השבתת ענישה עבור הבדיקה&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c בדיקה זו אינה קיימת.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7עוקף כעת את הבדיקה &4{detection} &7לתקופה של &e{time} &7שניות.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 הזהרת את &c{player} &7על&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a הפעלת מצב פרטי.'
verbose_disable: '&8[&2{prefix}&8] &c השבתת מצב פרטי.'
notifications_enable: '&8[&2{prefix}&8] &a הפעלת התראות.'
notifications_modified: '&8[&2{prefix}&8] &e שינית את הגדרות ההתראות.'
notifications_disable: '&8[&2{prefix}&8] &c השבתת התראות.'
awareness_notification: '&8[&2{prefix} התראה&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c הגל מתחיל.'
wave_end_message: '&8[&2{prefix}&8]&c הגל הסתיים עם סך הכל של {total} פעולה/פעולות.'
wave_clear_message: '&8[&2{prefix}&8]&c הגל נוקה.'
wave_add_message: '&8[&2{prefix}&8]&a {player} נוסף לגל.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} הוסר מהגל.'
full_wave_list: '&8[&2{prefix}&8]&c רשימת הגל מלאה.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} לא נוסף לגל.'
unknown_command: '&f פקודה לא ידועה. הקלד "/help" לקבלת עזרה.'
failed_command: '&8[&2{prefix}&8]&c הפקודה נכשלה ({command}). בדוק את הפרמטרים ונסה שוב.'
successful_command: '&8[&2{prefix}&8]&a הפקודה הצליחה.'
massive_command_reason: '&8[&2{prefix}&8]&c הסיבה ארוכה מדי.'
```
</details>

## Greek:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Κονσόλα
no_permission: '&8[&2{prefix}&8]&c Δεν έχεις άδεια να αλληλεπιδράσεις με αυτό.'
player_not_found_message: '&8[&2{prefix}&8]&c Ο παίκτης δεν βρέθηκε.'
config_reload: '&8[&2{prefix}&8]&e Η ρύθμιση επαναφορτώθηκε με επιτυχία.'
panic_mode_enable: '&8[&2{prefix}&8]&a Ενεργοποιήθηκε η λειτουργία πανικού, όλοι οι έλεγχοι είναι σε αθόρυβη λειτουργία και δεν θα τιμωρούν παίκτες.'
panic_mode_disable: '&8[&2{prefix}&8]&c Απενεργοποιήθηκε η λειτουργία πανικού, όλοι οι έλεγχοι θα τρέχουν πλέον σύμφωνα με τις ρυθμίσεις.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c Ο παίκτης {player}&7 αποβλήθηκε για &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Έχει επιτευχθεί το όριο παικτών για τη διεύθυνση IP σου.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Οι παραβάσεις του παίκτη επαναφέρθηκαν με επιτυχία&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Τα αποθηκευμένα δεδομένα του παίκτη διαγράφηκαν με επιτυχία&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Τα αποθηκευμένα δεδομένα του ελέγχου διαγράφηκαν με επιτυχία&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &a Ενεργοποιήσατε τον έλεγχο&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c Απενεργοποιήσατε τον έλεγχο&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a Ενεργοποιήσατε τις προληπτικές ενέργειες για τον έλεγχο&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c Απενεργοποιήσατε τις προληπτικές ενέργειες για τον έλεγχο&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a Ενεργοποιήσατε τις τιμωρίες για τον έλεγχο&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c Απενεργοποιήσατε τις τιμωρίες για τον έλεγχο&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c Αυτός ο έλεγχος δεν υπάρχει.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7 παρακάμπτει τώρα τον έλεγχο &4{detection} &7για &e{time} &7δευτερόλεπτα.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Προειδοποιήσατε τον &c{player} &7για&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a Ενεργοποιήσατε την λεπτομερή καταγραφή.'
verbose_disable: '&8[&2{prefix}&8] &c Απενεργοποιήσατε την λεπτομερή καταγραφή.'
notifications_enable: '&8[&2{prefix}&8] &a Ενεργοποιήσατε τις ειδοποιήσεις.'
notifications_modified: '&8[&2{prefix}&8] &e Τροποποιήσατε τις ειδοποιήσεις.'
notifications_disable: '&8[&2{prefix}&8] &c Απενεργοποιήσατε τις ειδοποιήσεις.'
awareness_notification: '&8[&2{prefix} Ειδοποίηση&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Η φάση ξεκινάει.'
wave_end_message: '&8[&2{prefix}&8]&c Η φάση ολοκληρώθηκε με συνολικά {total} ενέργειες.'
wave_clear_message: '&8[&2{prefix}&8]&c Η φάση καθαρίστηκε.'
wave_add_message: '&8[&2{prefix}&8]&a Ο παίκτης {player} προστέθηκε στη φάση.'
wave_remove_message: '&8[&2{prefix}&8]&c Ο παίκτης {player} αφαιρέθηκε από τη φάση.'
full_wave_list: '&8[&2{prefix}&8]&c Η λίστα φάσης είναι γεμάτη.'
wave_not_added_message: '&8[&2{prefix}&8]&c Ο παίκτης {player} δεν προστέθηκε στη φάση.'
unknown_command: '&f Άγνωστη εντολή. Πληκτρολογήστε "/help" για βοήθεια.'
failed_command: '&8[&2{prefix}&8]&c Η εντολή απέτυχε ({command}). Ελέγξτε τα επιχειρήματά σας και δοκιμάστε ξανά.'
successful_command: '&8[&2{prefix}&8]&a Η εντολή εκτελέστηκε με επιτυχία.'
massive_command_reason: '&8[&2{prefix}&8]&c Ο λόγος είναι πολύ μεγάλος.'
```
</details>

## Lithuanian:
<details>
  <summary>Click to view messages.yml</summary>
  
```
console_name: Konsolė
no_permission: '&8[&2{prefix}&8]&c Neturite leidimo atlikti šį veiksmą.'
player_not_found_message: '&8[&2{prefix}&8]&c Žaidėjas nerastas.'
config_reload: '&8[&2{prefix}&8]&e Konfigūracija sėkmingai perkrauta.'
panic_mode_enable: '&8[&2{prefix}&8]&a Įjungtas panikos režimas, visi tikrinimai nustatyti į tylųjį režimą ir nebaus žaidėjų.'
panic_mode_disable: '&8[&2{prefix}&8]&c Panikos režimas išjungtas, visi tikrinimai veiks pagal konfigūracijos nustatymus.'
kick_reason: '&c {reason}'
kick_broadcast_message: '&8[&2{prefix}&8]&c Žaidėjas {player}&7 buvo išmestas dėl &4{reason}'
player_ip_limit_kick_message: '&8[&2{prefix}&8]&c Pasiektas jūsų IP žaidėjų limitas.'
player_violation_reset_message: '&8[&2{prefix}&8]&a Pažeidimai sėkmingai atstatyti žaidėjui&8: &2{player}'
player_stored_data_delete_message: '&8[&2{prefix}&8]&a Saugojimo duomenys sėkmingai ištrinti žaidėjui&8: &2{player}'
detection_notification: '&8[&2{prefix}&8] &e{player} &7>> &c{detection:real}§8[{detection:level}§8] &7(§f{info}§7)'
check_stored_data_delete_message: '&8[&2{prefix}&8]&a Saugojimo duomenys sėkmingai ištrinti tikrinimui&8: &2{check}'
check_enable_message: '&8[&2{prefix}&8] &a Įjungėte tikrinimą&8:&7 {detection}'
check_disable_message: '&8[&2{prefix}&8] &c Išjungėte tikrinimą&8:&7 {detection}'
check_silent_disable_message: '&8[&2{prefix}&8] &a Įjungėte prevencijas tikrinimui&8:&7 {detection}'
check_silent_enable_message: '&8[&2{prefix}&8] &c Išjungėte prevencijas tikrinimui&8:&7 {detection}'
check_punishment_enable_message: '&8[&2{prefix}&8] &a Įjungėte bausmes tikrinimui&8:&7 {detection}'
check_punishment_disable_message: '&8[&2{prefix}&8] &c Išjungėte bausmes tikrinimui&8:&7 {detection}'
non_existing_check: '&8[&2{prefix}&8] &c Šis tikrinimas neegzistuoja.'
bypass_message: '&8[&2{prefix}&8] &c{player} &7dabar apeina tikrinimą &4{detection} &7laikui: &e{time} &7sek.'
warning_message: '&c {reason}'
warning_feedback_message: '&8[&2{prefix}&8]&7 Įspėjote &c{player} &7dėl&8: &4{reason}'
verbose_enable: '&8[&2{prefix}&8] &a Įjungėte išsamią informaciją.'
verbose_disable: '&8[&2{prefix}&8] &c Išjungėte išsamią informaciją.'
notifications_enable: '&8[&2{prefix}&8] &a Įjungėte pranešimus.'
notifications_modified: '&8[&2{prefix}&8] &e Pakeitėte pranešimus.'
notifications_disable: '&8[&2{prefix}&8] &c Išjungėte pranešimus.'
awareness_notification: '&8[&2{prefix} Pranešimas&8]&a {info}'
wave_start_message: '&8[&2{prefix}&8]&c Banga prasideda.'
wave_end_message: '&8[&2{prefix}&8]&c Banga baigėsi, atlikta iš viso {total} veiksmo(ai).'
wave_clear_message: '&8[&2{prefix}&8]&c Banga išvalyta.'
wave_add_message: '&8[&2{prefix}&8]&a {player} buvo pridėtas į bangą.'
wave_remove_message: '&8[&2{prefix}&8]&c {player} buvo pašalintas iš bangos.'
full_wave_list: '&8[&2{prefix}&8]&c Bangos sąrašas pilnas.'
wave_not_added_message: '&8[&2{prefix}&8]&c {player} nepridėtas į bangą.'
unknown_command: '&f Nežinoma komanda. Įveskite "/help" pagalbai.'
failed_command: '&8[&2{prefix}&8]&c Komanda nepavyko ({command}). Patikrinkite argumentus ir bandykite dar kartą.'
successful_command: '&8[&2{prefix}&8]&a Komanda sėkminga.'
massive_command_reason: '&8[&2{prefix}&8]&c Priežastis yra per ilga.'
```
</details>


