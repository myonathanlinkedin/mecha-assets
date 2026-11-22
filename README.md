# 🤖 mecha-assets — PUBLIC 3D GLTF/GLB ASSET CDN

> **Autonomous 3D Gundam-Like Mecha CAD Asset Store & 8-Zone Modular Manifest**  
> **Live 3D WebGL Engineering Hangar:** [https://myonathanlinkedin.github.io/mecha.html](https://myonathanlinkedin.github.io/mecha.html)  
> **Last Synchronized:** `2026-11-22 08:20 UTC` • **Baselines:** `2` • **Unique Modular Parts:** `24`

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

## 🦾 8-Zone Full-Body Modular Parts Catalog (24 Non-Duplicate Assets)

| Serial | Part Name | Body Zone (`UHIS`) | Physical Adapter | Mass | SHA-256 | Binary GLB |
| :--- | :--- | :--- | :--- | :---: | :---: | :--- |
| `GXM-MPK-AERO-01` | **Type-A Atmospheric Superiority Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,200 kg | `1a843cd44a27…` | [`mission_pack_type_a_aero.glb`](models/parts/mission_pack_type_a_aero.glb) |
| `GXM-MPK-SPAC-02` | **Type-S High-Mobility Space Interceptor Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 6,800 kg | `e4e0c1afe5b3…` | [`mission_pack_type_s_space.glb`](models/parts/mission_pack_type_s_space.glb) |
| `GXM-MPK-ARTY-03` | **Type-H Heavy Bombardment Artillery Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 9,500 kg | `4d93b3964cb8…` | [`mission_pack_type_h_artillery.glb`](models/parts/mission_pack_type_h_artillery.glb) |
| `GXM-MPK-EWRN-04` | **Type-E Electronic Reconnaissance & Radome Pack** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 3,400 kg | `7428945a331f…` | [`mission_pack_type_e_recon.glb`](models/parts/mission_pack_type_e_recon.glb) |
| `GXM-MPK-CQCP-05` | **Type-C Close-Quarters Combat Breacher Pack** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 5,100 kg | `8775f50449e2…` | [`mission_pack_type_c_cqc.glb`](models/parts/mission_pack_type_c_cqc.glb) |
| `GXM-WPN-BRIF-06` | **RX-78 Ver.Ka Long-Barrel Beam Rifle (E-Pac)** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 920 kg | `e757cc8d1ea2…` | [`weapon_beam_rifle_rx.glb`](models/parts/weapon_beam_rifle_rx.glb) |
| `GXM-ARM-SHLD-07` | **Gundarium Hexagonal Federation Composite Shield** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 2,150 kg | `5a27735d0eec…` | [`armor_tower_shield_fed.glb`](models/parts/armor_tower_shield_fed.glb) |
| `GXM-PRV-FINB-08` | **Twin Wing-Binder Psycho-Fin Vernier Array** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,950 kg | `09d943eb48a4…` | [`propulsion_vernier_wing_pod.glb`](models/parts/propulsion_vernier_wing_pod.glb) |
| `GXM-HED-CIWS-09` | **60mm Cranial Vulcan Pod & Psycho-Sensor Crest** | `head_sensor` (`HP-01`) | `ADP-HP01-CRANIAL` | 680 kg | `92acb61c975c…` | [`head_vulcan_crest_pod.glb`](models/parts/head_vulcan_crest_pod.glb) |
| `GXM-ARM-CHOB-10` | **FA-78 Chobham Reactive Breastplate & Callidus Emitter** | `chest_armor` (`HP-09`) | `ADP-HP09-PECTORAL` | 3,150 kg | `c9a3c6d90f83…` | [`chest_chobham_reactive_armor.glb`](models/parts/chest_chobham_reactive_armor.glb) |
| `GXM-WPN-SHPD-11` | **Twin 6-Tube Micro-Missile & Vernier Shoulder Pods (L+R)** | `shoulder_pods` (`HP-03`) | `ADP-HP03-SHOULDER` | 3,350 kg | `0d8982c612ba…` | [`shoulder_missile_pauldron_pods.glb`](models/parts/shoulder_missile_pauldron_pods.glb) |
| `GXM-ARM-WSB-12` | **FA-78 Side-Skirt Armored Thruster Binders & E-Pac Racks (L+R)** | `waist_ordnance` (`HP-13`) | `ADP-HP13-WAIST` | 2,400 kg | `bbbe02d490c8…` | [`waist_xiphias_hip_railguns.glb`](models/parts/waist_xiphias_hip_railguns.glb) |
| `GXM-PRV-CLFP-13` | **FA-78 Dual Calf Missile & Supersonic Booster Pods (L+R)** | `leg_thrusters` (`HP-24`) | `ADP-HP24-CALF` | 3,650 kg | `e6fd8c277074…` | [`leg_calf_vernier_missile_pods.glb`](models/parts/leg_calf_vernier_missile_pods.glb) |
| `GXM-WPN-BSBR-14` | **RX-78 Iconic High-Output Beam Saber (Laser Sword)** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 680 kg | `8c024216cfa9…` | [`weapon_beam_saber_rx.glb`](models/parts/weapon_beam_saber_rx.glb) |
| `GXM-LLM-BAZ-15` | **Hyper Bazooka Mk.II Auxiliary Hyper-Launcher** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 3,450 kg | `ea573e97baac…` | [`llm_weapon_hyper_bazooka.glb`](models/parts/llm_weapon_hyper_bazooka.glb) |
| `GXM-LLM-NAG-16` | **RX-78 Beam Naginata Auxiliary Weapon Pack** | `aux_weapon` (`HP-11`) | `ADP-HP11-WEAPON` | 1,380 kg | `e378ddce54e0…` | [`llm_weapon_beam_naginata.glb`](models/parts/llm_weapon_beam_naginata.glb) |
| `GXM-LLM-GAT-17` | **Twin-Gatling Shield Aux-Unit HP-07** | `aux_shield` (`HP-07`) | `ADP-HP07-FOREARM` | 3,950 kg | `f5ab27d10541…` | [`llm_shield_twin_gatling.glb`](models/parts/llm_shield_twin_gatling.glb) |
| `GXM-LLM-RLC-18` | **HP-03A Shoulder Rail Cannon Mk.II** | `shoulder_pods` (`HP-03`) | `ADP-HP03-SHOULDER` | 3,900 kg | `671fe3b09f66…` | [`llm_shoulder_rail_cannons.glb`](models/parts/llm_shoulder_rail_cannons.glb) |
| `GXM-LLM-OBV-19` | **RX-78-2 Overboost Leg Vernier Kit – HP-24 Calf Thruster** | `leg_thrusters` (`HP-24`) | `ADP-HP24-CALF` | 3,450 kg | `f718846300d3…` | [`llm_leg_overboost_verniers.glb`](models/parts/llm_leg_overboost_verniers.glb) |
| `GXM-LLM-CMD-21` | **Commander Twin Blade Crest - Head Sensor Module** | `head_sensor` (`HP-01`) | `ADP-HP01-CRANIAL` | 640 kg | `2792089bfd9d…` | [`llm_head_commander_crest.glb`](models/parts/llm_head_commander_crest.glb) |
| `GXM-LLM-PLS-21` | **RX-78-9 Reactive Collar Plastron Mk.II** | `chest_armor` (`HP-09`) | `ADP-HP09-PECTORAL` | 3,400 kg | `34d22b677ad0…` | [`llm_chest_reactive_plastron.glb`](models/parts/llm_chest_reactive_plastron.glb) |
| `GXM-LLM-WST-23` | **RX-78-3 Waist Plasma Rail Skirt Mk.II** | `waist_ordnance` (`HP-13`) | `ADP-HP13-WAIST` | 2,550 kg | `29003218a979…` | [`llm_waist_plasma_skirts.glb`](models/parts/llm_waist_plasma_skirts.glb) |
| `GXM-LLM-FNL-23` | **HP-00 Dorsal Heavy Funnel Container Mk.II** | `dorsal_pack` (`HP-00`) | `ADP-HP00-DORSAL` | 4,850 kg | `6d7deb94efe3…` | [`llm_dorsal_funnel_containers.glb`](models/parts/llm_dorsal_funnel_containers.glb) |
| `GXM-LLM-RLC-24` | **HP-03B Shoulder Rail Cannon Mk.III – Hyper Velocity Variant** | `shoulder_pods` (`HP-03`) | `ADP-HP03-SHOULDER` | 3,892 kg | `6a463ba5b3f0…` | [`llm_evo_shoulder_rail_cannon_g02_44aa8c.glb`](models/parts/llm_evo_shoulder_rail_cannon_g02_44aa8c.glb) |
