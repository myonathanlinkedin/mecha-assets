# 🤖 mecha-assets — PUBLIC 3D GLTF/GLB ASSET CDN

> **Autonomous 3D Gundam-Like Mecha CAD Asset Store & 8-Zone Modular Manifest**  
> **Live 3D WebGL Engineering Hangar:** [https://myonathanlinkedin.github.io/mecha.html](https://myonathanlinkedin.github.io/mecha.html)  
> **Last Synchronized:** `2026-11-21 21:06 UTC` • **Baselines:** `2` • **Unique Modular Parts:** `22`

---

## 📦 Repository Structure

```
mecha-assets/
├── data/
│   └── mecha_catalog.json              # Authoritative SHA-256 verified 3D catalog manifest
└── models/
    ├── baselines/                      # Smooth Auto-Normal Hero & Rival Movable Frames (.glb)
    ├── enemies/                        # Zeon & Neo-Zeon Mono-Eye Mobile Suits (Zaku-II, Gouf, Sazabi)
    └── parts/                          # 8-Zone Full-Body Gunpla Snap-Fit Adapters & Modular Parts (.glb)
```

---

## 🦾 8-Zone Full-Body Modular Parts Catalog (22 Non-Duplicate Assets)

| Serial | Part Name | Body Zone (`UHIS`) | Physical Adapter | Mass | SHA-256 | Binary GLB |
| :--- | :--- | :--- | :--- | :---: | :---: | :--- |
| `GXM-MPK-AERO-01` | **Type-A Atmospheric Superiority Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,200 kg | `ca38bca48ac2…` | [`mission_pack_type_a_aero.glb`](models/parts/mission_pack_type_a_aero.glb) |
| `GXM-MPK-SPAC-02` | **Type-S High-Mobility Space Interceptor Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 6,800 kg | `ca6b3740302e…` | [`mission_pack_type_s_space.glb`](models/parts/mission_pack_type_s_space.glb) |
| `GXM-MPK-ARTY-03` | **Type-H Heavy Bombardment Artillery Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 9,500 kg | `35d25e58c585…` | [`mission_pack_type_h_artillery.glb`](models/parts/mission_pack_type_h_artillery.glb) |
| `GXM-MPK-EWRN-04` | **Type-E Electronic Reconnaissance & Radome Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 3,400 kg | `c092e08df6e1…` | [`mission_pack_type_e_recon.glb`](models/parts/mission_pack_type_e_recon.glb) |
| `GXM-MPK-CQCP-05` | **Type-C Close-Quarters Combat Breacher Pack** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 5,100 kg | `37e5ada71987…` | [`mission_pack_type_c_cqc.glb`](models/parts/mission_pack_type_c_cqc.glb) |
| `GXM-WPN-BRIF-06` | **RX-78 Ver.Ka Long-Barrel Beam Rifle (E-Pac)** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 920 kg | `88123fbb617a…` | [`weapon_beam_rifle_rx.glb`](models/parts/weapon_beam_rifle_rx.glb) |
| `GXM-ARM-SHLD-07` | **Gundarium Hexagonal Federation Composite Shield** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 2,150 kg | `726f6cf84839…` | [`armor_tower_shield_fed.glb`](models/parts/armor_tower_shield_fed.glb) |
| `GXM-PRV-FINB-08` | **Twin Wing-Binder Psycho-Fin Vernier Array** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,950 kg | `0277c14d63b8…` | [`propulsion_vernier_wing_pod.glb`](models/parts/propulsion_vernier_wing_pod.glb) |
| `GXM-HED-CIWS-09` | **60mm Cranial Vulcan Pod & Psycho-Sensor Crest** | `head_sensor` (`HP-01`) | `ADP-HP01-CRANIAL` | 680 kg | `ee3780e0a076…` | [`head_vulcan_crest_pod.glb`](models/parts/head_vulcan_crest_pod.glb) |
| `GXM-ARM-CHOB-10` | **FA-78 Chobham Reactive Breastplate & Callidus Emitter** | `chest_armor` (`HP-09`) | `ADP-HP09-PECTORAL` | 3,150 kg | `a951a80e324d…` | [`chest_chobham_reactive_armor.glb`](models/parts/chest_chobham_reactive_armor.glb) |
| `GXM-WPN-SHPD-11` | **Twin 6-Tube Micro-Missile & Vernier Shoulder Pods (L+R)** | `shoulder_pods` (`HP-03`) | `ADP-HP03-SHOULDER` | 3,350 kg | `974e21210cb5…` | [`shoulder_missile_pauldron_pods.glb`](models/parts/shoulder_missile_pauldron_pods.glb) |
| `GXM-WPN-XIPH-12` | **Xiphias-3 Folding Hip Electromagnetic Railguns (L+R)** | `waist_ordnance` (`HP-13`) | `ADP-HP13-WAIST` | 2,850 kg | `72df5a5a907c…` | [`waist_xiphias_hip_railguns.glb`](models/parts/waist_xiphias_hip_railguns.glb) |
| `GXM-PRV-CLFP-13` | **FA-78 Dual Calf Missile & Supersonic Booster Pods (L+R)** | `leg_thrusters` (`HP-24`) | `ADP-HP24-CALF` | 3,650 kg | `098b63a20470…` | [`leg_calf_vernier_missile_pods.glb`](models/parts/leg_calf_vernier_missile_pods.glb) |
| `GXM-AGH-F182` | **HD-F182 Cranial 65mm CIWS Vulcan & High-Gain Sensor Crest** | `head_sensor` (`HP-01`) | `ADP-HP01-CRANIAL` | 884 kg | `09dfd68219d4…` | [`agentic_head_crest_f18218.glb`](models/parts/agentic_head_crest_f18218.glb) |
| `GXM-AGS-337E` | **SH-337E Twin 6-Tube Micro-Missile & Vernier Shoulder Pods (L+R)** | `shoulder_pods` (`HP-03`) | `ADP-HP03-SHOULDER` | 3,270 kg | `ecece8d91a40…` | [`agentic_shoulder_pods_337ee5.glb`](models/parts/agentic_shoulder_pods_337ee5.glb) |
| `GXM-AGD-AA6B` | **SD-AA6B Anti-Beam Gundarium Hexagonal Tower Shield** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 2,483 kg | `7ca3ec781b5e…` | [`agentic_shield_aa6bbe.glb`](models/parts/agentic_shield_aa6bbe.glb) |
| `GXM-AGB-F980` | **BR-F980 High-Output 5.5MW Long-Barrel Mega Beam Rifle** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 1,311 kg | `5b8135643ba3…` | [`agentic_beam_rifle_f980bc.glb`](models/parts/agentic_beam_rifle_f980bc.glb) |
| `GXM-AGR-796A` | **WS-796A Xiphias Mach-8.4 Folding Hip Electromagnetic Railguns (L+R)** | `waist_ordnance` (`HP-13`) | `ADP-HP13-WAIST` | 2,991 kg | `8df9c68bc09a…` | [`agentic_waist_railguns_796afa.glb`](models/parts/agentic_waist_railguns_796afa.glb) |
| `GXM-AGW-A92B` | **Type-A/A92B Variable-Sweep Delta Wing Pack (125mm Span)** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,695 kg | `ffff9529be20…` | [`agentic_aero_wing_a92bc1.glb`](models/parts/agentic_aero_wing_a92bc1.glb) |
| `GXM-AGL-2450` | **LG-2450 FA-78 Dual Calf Missile & High-G Vernier Booster Pods (L+R)** | `leg_thrusters` (`HP-24`) | `ADP-HP24-CALF` | 3,524 kg | `af3638f72f5b…` | [`agentic_leg_boosters_245060.glb`](models/parts/agentic_leg_boosters_245060.glb) |
| `GXM-AGA-BAE5` | **Type-H/BAE5 Twin 422mm Over-Shoulder Rail Cannon Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 10,350 kg | `f2b6f95c31f4…` | [`agentic_artillery_bae549.glb`](models/parts/agentic_artillery_bae549.glb) |
| `GXM-AGH-974B` | **HD-974B Cranial 58mm CIWS Vulcan & High-Gain Sensor Crest** | `head_sensor` (`HP-01`) | `ADP-HP01-CRANIAL` | 785 kg | `f5523b131927…` | [`agentic_head_crest_974b09.glb`](models/parts/agentic_head_crest_974b09.glb) |
