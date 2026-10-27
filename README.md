# Bitdsk Miner Archive

Firmware archive for the Bitdsk miner line. **Binaries only — no pages live here.**

- Firmware index (sizes + SHA256 for every file): <https://bitdsk.org/firmware.html>
- Browser flashing for S1 / U1 / U2: <https://bitdsk.github.io/Bitdsk-Flash_For_U1U2/>
- S1 firmware source (MIT): <https://github.com/bitdsk/Bitdsk-s1-Miner>

## Layout

```
firmware/
├─ n5-series/     N5.Rex / N5.Rexi / D12 / D12-T
├─ n8-series/     N8 / N8-T / N5.Rexi-T
│  └─ blackbox/   BLACKBOX debug builds
├─ u-series/      U1 / U2 OTA images and UI theme backgrounds
├─ legacy/        Discontinued boards: n_update n_www n_miner d_update d_www d_miner d9 n5
├─ tools/         PC batch manager
└─ hardware/      PCB Gerber files
```

The full-device **flash images** for S1 / U1 / U2 are not stored here — they live next to the
flasher in [Bitdsk-Flash_For_U1U2](https://github.com/bitdsk/Bitdsk-Flash_For_U1U2).

## Downloading

The [firmware index](https://bitdsk.org/firmware.html) is the page to start from: every file is
listed with its size and SHA256. Direct links work too, either straight from this repository or
through the jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/bitdsk/Bitdsk_Miner_Archive@main/firmware/n5-series/all.3.3_sec.zip
```

## Notes

- **Version dates may be slightly off.** The version numbers are accurate, but the dates beside
  them were carried over from the old site's download tables during the migration, so they can be
  a few days out. Treat the version string as the source of truth.
- Filenames are unchanged from the original releases, so existing links and SHA256 records still
  match.
- This repository only distributes builds. Firmware source is not maintained here — see
  [Bitdsk-s1-Miner](https://github.com/bitdsk/Bitdsk-s1-Miner) for the S1.
- These files used to be served from the old WordPress site at bitdsk.org, which is being retired.
  Nothing here depends on it any more.
