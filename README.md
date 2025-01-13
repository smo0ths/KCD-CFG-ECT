## updated 1/12/2025x2 for KCD v1.9.6 :ramen: 

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
# Create user.cfg in KingdomComeDeliverance folder and copy paste
# delete cache folder %userprofile%/Saved Games/kingdomcome/shaders
# Add launch commands: +exec user.cfg -devmode
# and restart after getting to main menu

#
con_restricted=0#
sys_MaxFPS=158# 🔵 def 0
sys_spec=0# 🔵 sets custom spec

#
sys_spec_GameEffects=7#
sys_spec_Light=7#
sys_spec_ObjectDetail=7#
sys_spec_Particles=7#
sys_spec_Physics=7#
sys_spec_PostProcessing=7#
sys_spec_Shading=7#
sys_spec_Shadows=7#
sys_spec_Sound=7#
sys_spec_Texture=7#
sys_spec_TextureResolution=7# 🔵 HD textures on
sys_spec_Vegetation=7#
sys_spec_VolumetricEffects=7#
sys_spec_Water=7#

#
#q_Quality=#
q_Renderer=3#
q_ShaderFX=3#
q_ShaderGeneral=3#
q_ShaderGlass=3#
q_ShaderHDR=3#
q_ShaderIce=3#
q_ShaderMetal=3#
q_ShaderPostProcess=3#
q_ShaderShadow=3#
q_ShaderSky=3#
q_ShaderTerrain=3#
q_ShaderVegetation=3#
q_ShaderWater=3# 🔵 wh def 2 🔴

#
Bind 0 g_showHUD 0#
Bind 9 g_showHUD 1#
Bind f1 sys_MaxFPS 158#
Bind f2 sys_MaxFPS 60#
Bind f3 "exec TEST1.cfg"#
Bind f4 "exec TEST2.cfg"#

#
cl_fov=68# 🔵 def 60
cl_sensitivity=10#
g_skipIntro=1# 🔵 def 0
i_mouse_accel=0#
i_mouse_smooth=0#
pl_movement.power_sprint_targetFOV=68# 🔵 def 55
r_DrawNearFOV=68# 🔵 def 60
r_Vsync=0#

#
wh_cs_PlayerLockDisabled=0# 🔵 def 0
wh_horse_CameraCentering=0# 🔵 def 0.2
wh_pl_showfirecursor=1# 🔵 def 0

# 🔴 edited sys
sys_budget_sysmem=2048# 🔵 def 512 🔴 RAM
sys_budget_videomem=8192# 🔵 def 90 🔴 VRAM
sys_flash_check_filemodtime=1# 🔵 wh def 0 🔴
sys_PakStreamCache=0# 🔵 def 0 🔴 RAM
sys_streaming_CPU_worker=7# 🔵 def 5 🔴

# 🔵 def sys
sys_budget_soundCPU=15# 🔵 def 15
sys_flash_address_space=65536# 🔵 def 65536
sys_flash_allow_reset_mesh_cache=1# 🔵 def 1
sys_flash_curve_tess_error=2# 🔵 wh def 2
sys_flash_edgeaa=1# 🔵 def 1
sys_flash_newstencilclear=1# 🔵 def 1
sys_flash_static_pool_size=0# 🔵 def 0
sys_flash_use_arenas=1# 🔵 def 1
sys_limit_phys_thread_count=0# 🔵 def 0
sys_physics_CPU=0# 🔵def 0
sys_spec_Quality=4# 🔵 def 4
sys_streaming_CPU=1# 🔵 def 1

# 🔴 edited engine
e_StreamCgfPoolSize=1024# 🔵 wh def 512 🔴 RAM
p_num_threads=7# 🔵 def 2 🔴
r_MultiGPU=0# 🔵 def 1 🔴
r_RenderTargetPoolSize=512# 🔵 def 0 🔴

# 🔵 def engine
e_HwOcclusionCullingWater=1# 🔵 def 1
e_ParticlesThread=1# 🔵 def 1
e_ShadowsPoolSize=4096# 🔵 def 4096
gpu_Particle_Physics=1# 🔵 def 1
p_cull_distance=100# 🔵 wh def 100
r_MergeRenderChunks=1# 🔵 def 1
r_ShadersDX11=1# 🔵 def 1
r_WaterUpdateThread=5# 🔵 def 5

# 🔴 edited texture
r_TexPreallocateAtlases=1# 🔵 wh def 0 🔴
r_TexturesStreamingMaxRequestedMB=512# 🔵 wh def 20 🔴
r_TexturesStreamingResidencyThrottle=1# 🔵 def 0.5 🔴
r_TexturesStreamingResidencyTime=256# 🔵 wh def 10 🔴
r_TexturesStreamPoolSize=10240# 🔵 wh def 4096 🔴 VRAM

# 🔵 def texture
r_TexturesSkipLowerMips=0# 🔵 def 0
r_TexturesStreaming=1# 🔵 def 1
r_TexturesStreamingResidencyEnabled=1# 🔵 def 1
r_TexturesStreamingSkipMips=0# 🔵 def 0
r_TexturesStreampoolDefragmentation=2# 🔵 def 2

# 🔴 edited graphics
e_CoverageBufferTerrainExpand=1# 🔵 wh def 0.025 🔴
e_Fog=1# 🔵 def 1 🔴
e_LodFaceAreaTargetSize=0.0006# 🔵 def 0.001 🔴
e_LodRatio=70# 🔵 wh def 60 🔴 max slider 70
e_MergedMeshesInstanceDist=32# 🔵 wh def 16 🔴
e_MergedMeshesLodRatio=16# 🔵 wh def 8 🔴
e_MergedMeshesViewDistRatio=100# 🔵 wh 85 🔴 max slider 100
e_ParticlesMotionBlur=0# 🔵 def 1 🔴
e_PhysProxyTriLimit=1000# 🔵 wh def 10000 🔴
e_ShadowsMaxTexRes=1872# 🔵 wh def 1024 🔴
e_svoTI_SSAOAmount=1.5# 🔵 def 1 🔴
e_ViewDistRatio=150# 🔵 wh def 125 🔴 max slider 150
e_VolumetricFog=0# 🔵 def 0 🔴
e_WaterOceanFFT=0# 🔵 def 1 🔴
es_MaxPhysDist=100# 🔵 wh def 200 🔴
es_maxphysdistcloth=100# 🔵 wh def 300 🔴
p_num_bodies_large_group=10# 🔵 wh def 100 🔴
r_AntialiasingMode=3# 🔵 wh def 2 🔴
r_AntialiasingTAASharpening=0# 🔵 def 0.2 🔴
r_HDRVignetting=0# 🔵 def 1 🔴
r_MotionBlur=0# 🔵 def 2 🔴
r_MotionBlurQuality=0# 🔵 def 2 🔴
r_RainAmount=2# 🔵 def 1 🔴
r_RainDistMultiplier=2.5# 🔵 wh def 2 🔴
r_RainMaxViewDist_Deferred=170# 🔵 def 150 🔴
r_ssdoAmountAmbient=2# 🔵 def 1 🔴
r_ssdoAmountDirect=4# 🔵 def 1.5 🔴
r_ssdoAmountReflection=5# 🔵 def 4 🔴
r_ssdoRadiusMin=0.02# 🔵 def 0.1 🔴
r_SSReflections=0# 🔵 def 1 🔴
r_SSReflHalfRes=1# 🔵 def 0 🔴
r_TerrainAO=0# 🔵 def 7 🔴
r_VolumetricFogTexDepth=4# 🔵 def 32 🔴
r_VolumetricFogTexScale=20# 🔵 def 1 🔵 wh def 10 🔴
r_WaterVolumeCaustics=0# 🔵 def 1 🔴
WH_AI_LOD_DistanceMax=160# 🔴 90,110,130
WH_AI_LOD_DistanceMin=130# 🔴 60,80,100
wh_env_RainDiffuseDarkening=0.25# 🔵 wh def 0.2 🔴
wh_env_RainDropsSpeedBase=3# 🔵 wh def 1.5 🔴

# 🔵 def graphics
ca_AttachmentCullingRation=425# 🔵 wh def 425
e_Brushes=1# 🔵 def 1
e_Clouds=1# 🔵 def 1
e_CoverageBufferEarlyOut=1# 🔵 def 1
e_DynamicLights=1# 🔵 def 1
e_GI=0# 🔵 wh def 0
e_GIAmount=0.6# 🔵 def 0.6
e_GICache=7# 🔵 def 7
e_GIIterations=6# 🔵 def 6
e_GIMaxDistance=100# 🔵 def 100
e_GINumCascades=1# 🔵 def 1
e_LightVolumes=1# 🔵 def 1
e_MergedMeshesPool=16384# 🔵 wh def 16384
e_ObjFastRegister=1# 🔵 def 1
e_ParticlesCullAgainstOcclusionBuffer=1# 🔵 def 1
e_ParticlesGI=1# 🔵 def 1
e_ParticlesObjectCollisions=2# 🔵 def 2
e_ParticlesPoolSize=16384# 🔵 def 16384
e_ParticlesQuality=4# 🔵 def 4
e_ParticlesShadows=1# 🔵 def 1
e_ParticlesSortQuality=0# 🔵 def 0 
e_ShadowsCastViewDistRatio=1.6# 🔵 wh def 1.6
e_ShadowsCastViewDistRatioLights=0.8# 🔵 wh def 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6# 🔵 wh def 0.6
e_SkyQuality=1# 🔵 def 1
e_SkyUpdateRate=1# 🔵 def 1
e_StatObjMerge=1# 🔵 def 1
e_TerrainAo=0# 🔵 def 0
e_Tessellation=1# 🔵 def 1
e_TessellationMaxDistance=30# 🔵 def 30
e_Wind=1# 🔵 def 1
es_MaxPhysDistInvisible=25# 🔵 wh def 25
g_radialBlur=0# 🔵 def 1
i_particleeffects=1# 🔵 def 1
r_AntialiasingTAAPattern=1# 🔵 def 1
r_ChromaticAberration=0# 🔵 def 0
r_DepthOfField=2# 🔵 def 2
r_FlareHqShafts=1# 🔵 def 1
r_Flares=0# 🔵 wh def 0
r_FlaresTessellationRatio=1# 🔵 def 1
r_FogShadows=0# 🔵 def 0
r_FogShadowsMode=0# 🔵 def 0
r_FogShadowsWater=0# 🔵 def 1
r_HDRBloom=1# 🔵 def 1
r_HDRGrainAmount=0# 🔵 def 0
r_ParticlesHalfRes=0# 🔵 def 0
r_ParticlesTessellation=1# 🔵 def 1
r_RainDropsEffect=1# 🔵 def 1
r_Refraction=1# 🔵 def 1
r_Sharpening=0# 🔵 def 0
r_SilhouettePOM=0# 🔵 def 0
r_ssdoRadius=0.3# 🔵 def 0.3
r_TerrainAO_FadeDist=8# 🔵 def 8
r_TessellationTriangleSize=8# 🔵 def 8
r_Unlit=0# 🔵 wh def 0
r_UseMaterialLayers=2# 🔵 def 2
r_VolumetricFogSunLightCorrection=1# 🔵 def 1
r_WaterCaustics=0# 🔵 def 0
r_WaterGodRays=0# 🔵 def 0
r_WaterReflectionsQuality=0# 🔵 def 0
r_WaterTessellationHW=1# 🔵 def 1
wh_cc_LodForAttachmentStreamOut=6# 🔵 def 6
wh_cc_LodForItemStreamOutBase=20# 🔵 def 20
wh_env_RainDropsAmountMul=15# 🔵 wh def 15
wh_env_RainLayers=3# 🔵 wh def 3
wh_pl_FOWEnabled=1# 🔵 wh def 1
wh_pl_FOWVisibilityRadius=100# 🔵 wh def 100
```

---

#### Create a mod folder in KingdomComeDeliverance/Mods

[Cooking cauldron flickering smoke Fix](https://www.nexusmods.com/kingdomcomedeliverance/mods/1177)

[Arrows go fast](https://www.nexusmods.com/kingdomcomedeliverance/mods/1240)

[Remove Those Stupid Trails](https://www.nexusmods.com/kingdomcomedeliverance/mods/7)

removed Instant Herb Picking with hand movement (completely changed in update ipl_patch_010900.pak)

[Alternate Food Spoil (Updated)](https://www.nexusmods.com/kingdomcomedeliverance/mods/1065)

[Inventoried](https://www.nexusmods.com/kingdomcomedeliverance/mods/797)

[Bushes- Collision Remover](https://www.nexusmods.com/kingdomcomedeliverance/mods/591)

[NoTimedDecisions](https://www.nexusmods.com/kingdomcomedeliverance/mods/1343)

[MuttBeQuiet](https://www.nexusmods.com/kingdomcomedeliverance/mods/1322)

[HelmetVision](https://www.nexusmods.com/kingdomcomedeliverance/mods/1337)

[No Blood On Screen (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/58)
<- remove blood_hit_1_ui.dds in zzz_fuxsart_no_blood_on_screen.pak (was changed in ipl_patch_010902.pak)

[No Drunk Sharpen Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/105)

[No Stamina Visual Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/10)

UI edits in KingdomComeDeliverance\Data\GameData.pak\Libs\UI\Textures\Hud_main.dds (make mod folder edit dds files if you want)

---

## edit Quicksave (defaultprofile.xml)

[Quicksave](https://www.nexusmods.com/kingdomcomedeliverance/mods/1282)

#### replace defaultprofile.xml and edit lines in Quicksave\Data\Data.pak\Libs\Config\defaultprofile.xml

```python
updated to latest KingdomComeDeliverance\Data\patch\ipl_patch_010800.pak\libs\config\defaultprofile.xml
then added:
<action consoleCmd="1" keyboard="f5" name="quicksave" onPress="1" />
under <actionmap name="default" version="22">

also had to add:
<action name="call_horse" onPress="1" onRelease="1"
<action name="horse_dismount" onPress="1" onRelease="1"
the onRelease="1" part after those to fix getting off a horse...
```

---

## Added all these mods in one rpg_param.xml (make your own so there is no conflicts):

BaseInventoryCapacity set to 999999
<br>
HarmlessFallHeight, InjuringFallHeight and FatalFallHeight set to 9000
<br>
[More Faster XP](https://www.nexusmods.com/kingdomcomedeliverance/mods/1129)
<br>
[Easy Sharpening](https://www.nexusmods.com/kingdomcomedeliverance/mods/336)
<br>
[Ultimate Repair Kit 2.0 Plus](https://www.nexusmods.com/kingdomcomedeliverance/mods/1292)

```python
<?xml version="1.0" encoding="us-ascii"?>
<database name="hammerheart">
  <table name="rpg_param" version="1">
    <header>
      <column name="item_category" type="character varying" />
      <column name="skill_id" type="integer" />
      <column name="perk_id" type="uuid" />
      <column name="rpg_param_key" type="character varying" />
      <column name="rpg_param_value" type="real" />
    </header>
    <rows>
      <row rpg_param_key="BaseInventoryCapacity" rpg_param_value="999999" />
      <row item_category="armor.horse_bridle.*" skill_id="8" />
      <row item_category="armor.horse_saddle.*" skill_id="8" />
      <row rpg_param_key="RepairKitCapacity" rpg_param_value="999999999" />
      <row rpg_param_key="RepairKitItemHealthBestLimit" rpg_param_value="0" />
      <row perk_id="01c3b32a-5751-4c98-b6ab-258d02370382" rpg_param_key="RepairKitCapacity" rpg_param_value="999999999" />
      <row perk_id="01c3b32a-5751-4c98-b6ab-258d02370382" rpg_param_key="RepairKitItemHealthBestLimit" rpg_param_value="0" />
      <row rpg_param_key="AlchemyXPPerSuccessfullBrewing" rpg_param_value="60" />
      <row rpg_param_key="AlchemyXPPerAutocookBrewingRelative" rpg_param_value="0.2" />
      <row rpg_param_key="FactionAngrinessDecayExp" rpg_param_value="3" />
      <row rpg_param_key="HerbGatherXP" rpg_param_value="15" />
      <row rpg_param_key="HorseRidingXPPerDistance" rpg_param_value="18.8" />
      <row rpg_param_key="HoundmasterXPContextCommand" rpg_param_value="3" />
      <row rpg_param_key="HoundmasterXPFeed" rpg_param_value="38" />
      <row rpg_param_key="HoundmasterXPFetch" rpg_param_value="7.5" />
      <row rpg_param_key="HoundmasterXPHit" rpg_param_value="3" />
      <row rpg_param_key="HoundmasterXPKill" rpg_param_value="30" />
      <row rpg_param_key="HoundmasterXPPlay" rpg_param_value="22.5" />
      <row rpg_param_key="HoundmasterXPPOIDiscovery" rpg_param_value="30" />
      <row rpg_param_key="HoundmasterXPPraise" rpg_param_value="22.5" />
      <row rpg_param_key="HunterXPKill" rpg_param_value="22.5" />
      <row rpg_param_key="LockPickingStealthXP" rpg_param_value="12" />
      <row rpg_param_key="LockPickingSuccessXPMulCoef" rpg_param_value="27" />
      <row rpg_param_key="NonSkillBookXP" rpg_param_value="45" />
      <row rpg_param_key="PickpocketingFailXPMod" rpg_param_value="0.5" />
      <row rpg_param_key="PickpocketingStealthXP" rpg_param_value="18" />
      <row rpg_param_key="PickpocketingXP" rpg_param_value="22.5" />
      <row rpg_param_key="ReadingXpPerHour" rpg_param_value="30" />
      <row rpg_param_key="SecondaryStatXPRatio" rpg_param_value="0.8" />
      <row rpg_param_key="SkillXPBlock" rpg_param_value="3" />
      <row rpg_param_key="SkillXPComboHit" rpg_param_value="6" />
      <row rpg_param_key="SkillXPHit" rpg_param_value="3" />
      <row rpg_param_key="SkillXPKill" rpg_param_value="18" />
      <row rpg_param_key="SkillXPPerfectBlock" rpg_param_value="12" />
      <row rpg_param_key="SkillXPRiposte" rpg_param_value="12" />
      <row rpg_param_key="SkillXPUseRepairKit" rpg_param_value="7.5" />
      <row rpg_param_key="StatXPComboHit" rpg_param_value="6" />
      <row rpg_param_key="StatXPHit" rpg_param_value="3" />
      <row rpg_param_key="StatXPKill" rpg_param_value="12" />
      <row rpg_param_key="StatXPSpeechPerSequence" rpg_param_value="2" />
      <row rpg_param_key="StatXPVitalityPerDistance" rpg_param_value="12" />
      <row rpg_param_key="StatXPVitalityPerJump" rpg_param_value="0.8" />
      <row rpg_param_key="StatXPVitalityPerKill" rpg_param_value="22.5" />
      <row rpg_param_key="StatXPVitalityPerVault" rpg_param_value="1.1" />
      <row rpg_param_key="StealthAttackFailXp" rpg_param_value="15" />
      <row rpg_param_key="StealthAttackMaxXp" rpg_param_value="75" />
      <row rpg_param_key="StealthAttackMinXp" rpg_param_value="37.5" />
      <row rpg_param_key="SharpeningMinIdealAngle" rpg_param_value="0" />
      <row rpg_param_key="SharpeningMaxIdealAngle" rpg_param_value="0.98" />
      <row rpg_param_key="SharpeningMinDestructionAngle" rpg_param_value="0.99" />
      <row rpg_param_key="SharpeningMaxDestructionAngle" rpg_param_value="1" />
      <row rpg_param_key="HarmlessFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="InjuringFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="FatalFallHeight" rpg_param_value="9000" />
      <row rpg_param_key="FullClothDirtyingOnFullSpeed" rpg_param_value="5000" />
    </rows>
  </table>
</database>
```

---
