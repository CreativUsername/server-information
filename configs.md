The config options that have been changed or added. I tried to include all of them here, but might have missed a few.

If you want to know what a config does, look through the documentation of the mod that adds it.

## /commandaliases/

### banme.yaml

```
schemaVersion: 1
commandMode: COMMAND_CUSTOM
command: banme
actions:
  - command: 'tempban $executor_name() 1h You banned yourself!'
    commandType: SERVER
```

### kickme.yaml

```
schemaVersion: 1
commandMode: COMMAND_CUSTOM
command: kickme
actions:
  - command: 'kick $executor_name() You kicked yourself!'
    commandType: SERVER
```

### killme.yaml

```
schemaVersion: 1
commandMode: COMMAND_CUSTOM
command: killme
actions:
  - command: 'kill $executor_name()'
    commandType: SERVER
```

### muteme.yaml

```
schemaVersion: 1
commandMode: COMMAND_CUSTOM
command: muteme
actions:
  - command: 'tempmute $executor_name() 1h You muted yourself!'
    commandType: SERVER
```

### nick.yaml

```
schemaVersion: 1
commandMode: COMMAND_REDIRECT
command: nick
redirectTo: nickname
```

## /TabTPS/display-configs/default.conf

| config | default | changed |
| --- | --- | --- |
| `action-bar-settings/modules` | `"tps,mspt,ping"` | `"tps,mspt,memory,ping,cpu"` |
| `boss-bar-settings/modules` | `"tps,mspt,ping"` | `"tps,mspt,memory,ping,cpu"` |
| `tab-settings/modules` | `"tps,mspt"` | `"tps,mspt,memory,ping,cpu"` |

## /EssentialCommands.properties

| config | default | changed |
| --- | --- | --- |
| `enable_day` | `true` | `false` |
| `enable_enderchest` | `true` | `false` |
| `enable_fly` | `true` | `false` |
| `enable_invuln` | `true` | `false` |
| `enable_rtp` | `true` | `false` |
| `enable_top` | `true` | `false` |
| `enable_wastebin` | `true` | `false` |
| `enable_workbench` | `true` | `false` |
| `nickname_prefix` | `{"color"\:"red","text"\:"~"}` | `""` |
| `use_permissions_api` | `false` | `true` |

## /grindenchantments.json

| config | default | changed |
| --- | --- | --- |
| `disenchant_to_book/cost_function/factor` | `0.3` | `0` |
| `disenchant_to_book/cost_function/offset` | `8.0` | `0` |
| `move_enchantments/cost_function/factor` | `0.5` | `0` |
| `move_enchantments/cost_function/offset` | `0.5` | `0` |

## /rightclickharvest.json

| config | default | changed |
| --- | --- | --- |
| `requireHoe` | `true` | `false` |
| `useHunger` | `true` | `false` |
