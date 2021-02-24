# stalker-anomaly-ammocheck-anims
Custom check ammo animations designed for Zukuu's ammo check addon; [Moddb](https://www.moddb.com/mods/stalker-anomaly/addons/ammocheck-rc18), [Github](https://github.com/WrkX/Stalker_Ammo_Check).

### Weapons
9a91 | abakan(an94) | ace21 | aek971 | mp5sd | ak/aks | ak12 | ak74 | aks74 | ak74m

### Script entries
```
gamedata/configs/defines.ltx
===========================
--9a91
anm_ammoCheck_wpn_9a91												= sparco_hands_9a91_check_ammo, sparco_9a91_check_ammo, 1
--abakan
anm_ammoCheck_wpn_abakan											= sparco_hands_abakan_check_ammo, sparco_abakan_check_ammo, 1
--ak/s
anm_ammoCheck_wpn_ak													= sparco_hands_ak_check_ammo, sparco_ak_check_ammo, 1
anm_ammoCheck_wpn_ak_gl												= sparco_hands_ak_check_ammo_gl, sparco_ak_check_ammo, 1
anm_ammoCheck_wpn_aks													= sparco_hands_ak_check_ammo, sparco_ak_check_ammo, 1
anm_ammoCheck_wpn_aks_gl											= sparco_hands_ak_check_ammo_gl, sparco_ak_check_ammo, 1
--ace21
anm_ammoCheck_wpn_ace21												= sparco_hands_ace21_check_ammo, sparco_ace21_check_ammo, 1
--aek
anm_ammoCheck_wpn_aek													= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_camo										= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_duty										= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_gl											= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_camo_gl									= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_duty_gl									= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo, 1
anm_ammoCheck_wpn_aek_empty										= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo_empty, 1
anm_ammoCheck_wpn_aek_camo_empty							= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo_empty, 1
anm_ammoCheck_wpn_aek_duty_empty							= sparco_hands_aek971_check_ammo, sparco_aek971_check_ammo_empty, 1
anm_ammoCheck_wpn_aek_gl_empty								= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo_empty, 1
anm_ammoCheck_wpn_aek_camo_gl_empty						= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo_empty, 1
anm_ammoCheck_wpn_aek_duty_gl_empty						= sparco_hands_aek971_check_ammo_gl, sparco_aek971_check_ammo_empty, 1
--ak12
anm_ammoCheck_wpn_ak12												= sparco_hands_ak12_check_ammo, sparco_ak12_check_ammo, 1
anm_ammoCheck_wpn_ak12_gl											= sparco_hands_ak12_check_ammo_gl, sparco_ak12_check_ammo, 1
anm_ammoCheck_wpn_ak12_empty									= sparco_hands_ak12_check_ammo, sparco_ak12_check_ammo_empty, 1
anm_ammoCheck_wpn_ak12_gl_empty								= sparco_hands_ak12_check_ammo_gl, sparco_ak12_check_ammo_empty, 1
--ak74
anm_ammoCheck_wpn_ak74												= sparco_hands_ak74_check_ammo, sparco_ak74_check_ammo, 1
anm_ammoCheck_wpn_ak74_gl											= sparco_hands_ak74_check_ammo_gl, sparco_ak74_check_ammo, 1
anm_ammoCheck_wpn_ak74_empty									= sparco_hands_ak74_check_ammo, sparco_ak74_check_ammo_empty, 1
anm_ammoCheck_wpn_ak74_gl_empty								= sparco_hands_ak74_check_ammo_gl, sparco_ak74_check_ammo_empty, 1
--ak74m
anm_ammoCheck_wpn_ak74m												= sparco_hands_aks74_check_ammo, sparco_aks74_check_ammo, 1
anm_ammoCheck_wpn_ak74m_empty									= sparco_hands_aks74_check_ammo, sparco_aks74_check_ammo_empty, 1
anm_ammoCheck_wpn_ak74m_gl										= sparco_hands_aks74_check_ammo_gl, sparco_aks74_check_ammo, 1
anm_ammoCheck_wpn_ak74m_gl_empty							= sparco_hands_aks74_check_ammo_gl, sparco_aks74_check_ammo_empty, 1
--ak74m_alternatives
anm_ammoCheck_wpn_ak74m_alternative						= sparco_hands_ak74m_sk4_check_ammo, sparco_ak74m_sk4_check_ammo, 1
anm_ammoCheck_wpn_ak74m_alternative_empty			= sparco_hands_ak74m_sk4_check_ammo, sparco_ak74m_sk4_check_ammo, 1
anm_ammoCheck_wpn_ak74m_alternative_gl				= sparco_hands_ak74m_sk4_check_ammo_gl, sparco_ak74m_sk4_check_ammo, 1
anm_ammoCheck_wpn_ak74m_alternative_gl_empty	= sparco_hands_ak74m_sk4_check_ammo_gl, sparco_ak74m_sk4_check_ammo, 1
--mp5sd
anm_ammoCheck_wpn_mp5sd												= sparco_hands_mp5sd_check_ammo, sparco_mp5sd_check_ammo, 1
anm_ammoCheck_wpn_mp5sd_empty									= sparco_hands_mp5sd_check_ammo, sparco_mp5sd_check_ammo, 1
```

```
gamedata/configs/items/weapons/w_anm_config.ltx
===============================================
[9a91]
snd = weapons\9a91\sparco_9a91_check_ammo
tm = 4

[abakan]
snd = weapons\abakan\sparco_abakan_check_ammo
tm = 4

[ak]
snd = weapons\ak\sparco_ak_check_ammo
tm = 3

[aks]:ak

[ace21]
snd = weapons\ace21\sparco_ace21_check_ammo
tm = 4

[aek]
snd = weapons\aek971\sparco_aek971_check_ammo
tm = 3.87

[ak12]
snd = weapons\ak12\sparco_ak12_check_ammo
tm = 5.33

[ak74]
snd = weapons\ak74\sparco_ak74_check_ammo
tm = 5.23

[aks74]
snd = weapons\ak74\sparco_aks74_check_ammo
tm = 4.87

[ak74m]:aks74
[ak74m_alternative]:aks74

[mp5sd]
snd = weapons\mp5sd\sparco_mp5sd_check_ammo
tm = 3
```
### Contact
Discord: Sparco#3596
