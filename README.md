# kazoo-archive

The upstream history of Kazoo 5 as [2600Hz](https://github.com/2600hz) published it, kept so that it stays available to [Reprise](https://github.com/reprise-voice/reprise), the fork that continues it.

Nothing here was changed: every branch points at an upstream commit, with upstream's own commit ids. The branches are the `kazoo5` umbrella repository and one branch per component repository, each at the revision Reprise's baseline commits were taken from.

Reprise's `scripts/graft-upstream-history.sh` fetches this repository and attaches these histories to its baseline commits, so that `git blame` and `git log` in a Reprise clone reach the original authors.

| Branch | Upstream repository | Commit | Path in Reprise |
|---|---|---|---|
| `kazoo5` | [2600hz/kazoo5](https://github.com/2600hz/kazoo5) | `1e9aaa36e6a2d75bd38ba179dbcc48c6eff476b5` | `(repository root)` |
| `components/core` | [2600hz/kazoo-core](https://github.com/2600hz/kazoo-core) | `5defa1df755ea9cf4d0f3f81f8145bd8a0c7dd72` | `core` |
| `components/ecallmgr` | [2600hz/kazoo-ecallmgr](https://github.com/2600hz/kazoo-ecallmgr) | `fb8eba201b41762ce8fae928c61bd5d22379a1bc` | `applications/ecallmgr` |
| `components/ecallmgr_extension` | [2600hz/kazoo-ecallmgr-extension](https://github.com/2600hz/kazoo-ecallmgr-extension) | `e5072ae57c3c13b0b54ac9c961680a13c54d5b4b` | `applications/ecallmgr_extension` |
| `components/konami` | [2600hz/kazoo-konami](https://github.com/2600hz/kazoo-konami) | `8cebd1572f25a5cd1fb69fd279282785c470e8bb` | `applications/konami` |
| `components/amqp_dist` | [2600hz/erlang-amqp_dist](https://github.com/2600hz/erlang-amqp_dist) | `b26715d7387368c0bc48e9906f56b6eb77a58a3e` | `vendor/amqp_dist` |
| `components/configs-kamailio` | [2600hz/kazoo-configs-kamailio](https://github.com/2600hz/kazoo-configs-kamailio) | `c23ab5355bfb3a9fa91d0ec8404319700ad11c8a` | `configs/kamailio` |
| `components/configs-freeswitch` | [2600hz/kazoo-configs-freeswitch](https://github.com/2600hz/kazoo-configs-freeswitch) | `8862c1a642f9a4507c1b01b847ad6943f6bd54b8` | `configs/freeswitch` |
| `components/webhooks` | [2600hz/kazoo-webhooks](https://github.com/2600hz/kazoo-webhooks) | `20c596630ae30531b9c4d962a37ca7667ee7a83d` | `applications/webhooks` |
| `components/trunkstore` | [2600hz/kazoo-trunkstore](https://github.com/2600hz/kazoo-trunkstore) | `561049e6cee08dd0878e2175dd0d4794a72e2a37` | `applications/trunkstore` |
| `components/teletype` | [2600hz/kazoo-teletype](https://github.com/2600hz/kazoo-teletype) | `5ef62a9dbf46121df41bd2237ad48ba3c45fe372` | `applications/teletype` |
| `components/tasks` | [2600hz/kazoo-tasks](https://github.com/2600hz/kazoo-tasks) | `cc13e0ab4250fcbc532c9e2364690c6c80239790` | `applications/tasks` |
| `components/sysconf` | [2600hz/kazoo-sysconf](https://github.com/2600hz/kazoo-sysconf) | `0b4c597d90d6baa3efb8fa9f2500c90c7572da65` | `applications/sysconf` |
| `components/stepswitch` | [2600hz/kazoo-stepswitch](https://github.com/2600hz/kazoo-stepswitch) | `b04805b6354b2e0bbab8aca72c8514dcf6e1d828` | `applications/stepswitch` |
| `components/stats` | [2600hz/kazoo-stats](https://github.com/2600hz/kazoo-stats) | `497f47cd51265dd731bc4279243ebef432a2583f` | `applications/stats` |
| `components/skel` | [2600hz/kazoo-skel](https://github.com/2600hz/kazoo-skel) | `5647444d2c775f0f1de9ccc4aed0bbf1dcc44372` | `applications/skel` |
| `components/reorder` | [2600hz/kazoo-reorder](https://github.com/2600hz/kazoo-reorder) | `844435e07467f191fb56134dc1e6c0ae789e1741` | `applications/reorder` |
| `components/registrar` | [2600hz/kazoo-registrar](https://github.com/2600hz/kazoo-registrar) | `31c06112b06ad659d53657b3fc4d5979131f610c` | `applications/registrar` |
| `components/pusher` | [2600hz/kazoo-pusher](https://github.com/2600hz/kazoo-pusher) | `aedbbb5e1f89330c657ee64f49c244662d822990` | `applications/pusher` |
| `components/pivot` | [2600hz/kazoo-pivot](https://github.com/2600hz/kazoo-pivot) | `8fda52d159f29b32c57617924a003f191acaeab1` | `applications/pivot` |
| `components/omnipresence` | [2600hz/kazoo-omnipresence](https://github.com/2600hz/kazoo-omnipresence) | `c044b1655e1e6fa39e572173b34f0c729b10c0e3` | `applications/omnipresence` |
| `components/milliwatt` | [2600hz/kazoo-milliwatt](https://github.com/2600hz/kazoo-milliwatt) | `9ca21219af610da75c43f95792f545ebdead57a4` | `applications/milliwatt` |
| `components/media_mgr` | [2600hz/kazoo-media-mgr](https://github.com/2600hz/kazoo-media-mgr) | `6e10a3468b23daa13036314df76ecaa5257d5c5d` | `applications/media_mgr` |
| `components/jonny5` | [2600hz/kazoo-jonny5](https://github.com/2600hz/kazoo-jonny5) | `673ce50b0efc19faf51803564822d3fb072654a4` | `applications/jonny5` |
| `components/hotornot` | [2600hz/kazoo-hotornot](https://github.com/2600hz/kazoo-hotornot) | `74d60c5586bfa718db7b410744d68c5533e6636f` | `applications/hotornot` |
| `components/hangups` | [2600hz/kazoo-hangups](https://github.com/2600hz/kazoo-hangups) | `6bd8b6ba37c623ead09f10c53dabf5e979710523` | `applications/hangups` |
| `components/fax` | [2600hz/kazoo-fax](https://github.com/2600hz/kazoo-fax) | `a50ca0acd5f5a53cc6a57db8de46d04c14feb88c` | `applications/fax` |
| `components/doodle` | [2600hz/kazoo-doodle](https://github.com/2600hz/kazoo-doodle) | `0e2c26e5fdc1120c4004372b7d3600c80da18818` | `applications/doodle` |
| `components/crossbar` | [2600hz/kazoo-crossbar](https://github.com/2600hz/kazoo-crossbar) | `2ac862830f9b626d2170d08daf1991b0ca33dba7` | `applications/crossbar` |
| `components/conference` | [2600hz/kazoo-conference](https://github.com/2600hz/kazoo-conference) | `a49f3ff20400cb7fe62235b70db8cba30a560f6b` | `applications/conference` |
| `components/cdr` | [2600hz/kazoo-cdr](https://github.com/2600hz/kazoo-cdr) | `5e317c9a0b9aba87db78a3549ea340d8f790c502` | `applications/cdr` |
| `components/callflow` | [2600hz/kazoo-callflow](https://github.com/2600hz/kazoo-callflow) | `a18d4f5bb10c6710013494e9fb928afc4cad4025` | `applications/callflow` |
| `components/call_inspector` | [2600hz/kazoo-call-inspector](https://github.com/2600hz/kazoo-call-inspector) | `a9bb4dcbd6cdd6ef5bd30f657496832227a611d5` | `applications/call_inspector` |
| `components/blackhole` | [2600hz/kazoo-blackhole](https://github.com/2600hz/kazoo-blackhole) | `4e3f02a5ab01c09a44c287f4f93b15d2782f5614` | `applications/blackhole` |

This branch (`main`) holds only this file. Kazoo is licensed under the Mozilla Public License 2.0; see the license files on each branch. Kazoo and 2600Hz are trademarks of their owner; this archive is not affiliated with or endorsed by 2600Hz.
