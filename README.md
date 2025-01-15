





































//////////
/////////////
///////////////


still need to mess with shadows




## updated 1/14/2025 v0.9.1 :ramen:

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
## Create user.cfg in KingdomComeDeliverance folder and copy paste
## delete cache folder %userprofile%/Saved Games/kingdomcome/shaders
## Add launch commands: +exec user.cfg -devmode
## and restart after getting to main menu
## "" means changed ## means sudo default max spec this is a ultra high config

con_restricted=0 ##
r_DisplayInfo=0 ##
sys_MaxFPS=158 ## 0 ""

## sys_spec_full=4 ## "change per"
sys_spec=0 ## "sets custom spec"
sys_spec_GameEffects=7 ##
sys_spec_Light=7 ##
sys_spec_ObjectDetail=7 ##
sys_spec_Particles=7 ##
sys_spec_Physics=7 ##
sys_spec_PostProcessing=7 ##
sys_spec_Shading=7 ##
sys_spec_Shadows=7 ##
sys_spec_Sound=7 ##
sys_spec_Texture=7 ##
sys_spec_TextureResolution=7 ## "7 HD textures"
sys_spec_Vegetation=7 ##
sys_spec_VolumetricEffects=7 ##
sys_spec_Water=7 ##

## q_Quality=3 ## "change per"
q_Renderer=3 ##
q_ShaderFX=3 ##
q_ShaderGeneral=3 ##
q_ShaderGlass=3 ##
q_ShaderHDR=3 ##
q_ShaderIce=3 ##
q_ShaderMetal=3 ##
q_ShaderPostProcess=3 ##
q_ShaderShadow=3 ##
q_ShaderSky=3 ##
q_ShaderTerrain=3 ##
q_ShaderVegetation=3 ##
q_ShaderWater=3 ## 2 ""

Bind 0 g_showHUD 0 ##
Bind 9 g_showHUD 1 ##
Bind f1 sys_MaxFPS 158 ##
Bind f2 sys_MaxFPS 60 ##
Bind f3 "exec TEST1.cfg" ## "make"
Bind f4 "exec TEST2.cfg" ## "make"
cl_fov=68 ## 60
cl_sensitivity=10 ##
g_skipIntro=1 ## 0
i_mouse_accel=0 ##
i_mouse_smooth=0 ##
pl_movement.power_sprint_targetFOV=68 ## 55 ""
r_DrawNearFOV=68 ## 60 ""
r_Vsync=0 ##
wh_cs_PlayerLockDisabled=0 ## 0
wh_horse_CameraCentering=0 ## 0.2 ""
wh_pl_showfirecursor=1 ## 0

## e_VegetationMinSize=0 ## 0.1 "pickable vegetation"
## r_DynTexAtlasSpritesMaxSize=32 ## 32 "not real"
## r_HDRBrightLevel=1 ## 1 "not real"
## r_SilhouettePOM=0 ## 0 ""
## s_ObstructionMaxValue=0 ## 0 "not real"
e_CoverageBufferTerrainExpand=1 ## 0.025 ""
e_LodFaceAreaTargetSize=0.0006 ## 0.001 ""
e_LodRatio=70 ## 60 "70 max slider"
e_MergedMeshesInstanceDist=32 ## 16 ""
e_MergedMeshesLodRatio=16 ## 8 ""
e_MergedMeshesViewDistRatio=100 ## 85 "100 max slider"
e_ParticlesMotionBlur=0 ## 1 ""
e_PhysProxyTriLimit=1000 ## 10000 ""
e_ShadowsMaxTexRes=1872 ## 1024 ""
e_StreamCgfPoolSize=1024 ## 512 "RAM"
e_svoTI_IntegrationMode=0 ## 0
e_svoTI_LowSpecMode=2 ## 1 ""
e_svoTI_Saturation=1 ## 0.8 ""
e_svoTI_SkyColorMultiplier=-0.6 ## -1.0001 ""
e_svoTI_SSAOAmount=1.5 ## 1 ""
e_svoTI_VoxelizeUnderTerrain=0 ## 1 ""
e_svoVoxelPoolResolution=128 ## 128
e_TerrainDetailMaterialsViewDistZ=120 ## 100 ""
e_ViewDistMin=10 ## 5 ""
e_ViewDistRatio=150 ## 125 "150 max slider"
e_VolumetricFog=0 ## 0 ""
e_WaterOceanFFT=0 ## 1 ""
es_MaxPhysDist=100 ## 200 ""
es_maxphysdistcloth=100 ## 300 ""
p_num_bodies_large_group=10 ## 100 ""
p_num_threads=7 ## 2 ""
r_AntialiasingMode=3 ## 2 ""
r_AntialiasingTAASharpening=0 ## 0.2 ""
r_DrawNearZRange=0.1 ## 0.001 ""
r_FogShadowsWater=1 ## 1 ""
r_HDRVignetting=0 ## 1 ""
r_MotionBlur=0 ## 2 ""
r_MotionBlurQuality=0 ## 2 ""
r_MultiGPU=0 ## 1 ""
r_RainAmount=2 ## 1 ""
r_RainDistMultiplier=2.5 ## 2 ""
r_RainMaxViewDist_Deferred=170 ## 150 ""
r_RenderTargetPoolSize=512 ## 0 ""
r_ssdoAmountAmbient=1.5 ## 1 ""
r_ssdoAmountDirect=4 ## 1.5 ""
r_ssdoAmountReflection=5 ## 4 ""
r_ssdoHalfRes=0 ## 2 ""
r_ssdoRadiusMin=0.02 ## 0.1 ""
r_SSReflections=0 ## 1 ""
r_SSReflHalfRes=1 ## 0 ""
r_TerrainAO=0 ## 7 ""
r_TexPreallocateAtlases=1 ## 0 ""
r_TexturesStreamingMaxRequestedMB=500 ## 20 ""
r_TexturesStreamingResidencyThrottle=1 ## 0.5 ""
r_TexturesStreamingResidencyTime=90 ## 10 ""
r_TexturesStreampoolDefragmentation=2 ## 2 "1,2 CPU,GPU"
r_TexturesStreampoolDefragmentationMaxAmount=3145728 ## 2097152 "testing"
r_TexturesStreampoolDefragmentationMaxMoves=15 ## 10 "testing"
r_TexturesStreamPoolSize=11264 ## 4096 "set to 70% of VRAM and round down"
r_VolumetricFogTexDepth=4 ## 32 ""
r_VolumetricFogTexScale=20 ## 10 ""
r_WaterVolumeCaustics=0 ## 1 ""
s_OcclusionMaxDistance=150 ## 500 ""
sys_budget_streamingthroughput=2048 ## 1024 "testing"
sys_budget_sysmem=1024 ## 512 "debug"
sys_budget_videomem=1024 ## 90 "debug"
sys_flash_address_space=131072 ## 65536 ""
sys_flash_check_filemodtime=1 ## 0 ""
sys_PakStreamCache=0 ## 0 "" RAM
sys_streaming_CPU_worker=7 ## 5 ""
WH_AI_LOD_DistanceMax=160 ## "90,110,130"
WH_AI_LOD_DistanceMin=130 ## "60,80,100"
wh_env_RainDiffuseDarkening=0.33 ## 0.2 ""
wh_env_RainDropsSpeedBase=3 ## 1.5 ""

ca_AttachmentCullingRation=450 ## 450
ca_KeepModels=0 ## 0
ca_useDecals=0 ## 0
ca_UsePhysics=1 ## 1
e_AutoPrecacheCgf=1 ## 1
e_Brushes=1 ## 1
e_CharLodMin=0 ## 0
e_Clouds=1 ## 1
e_CoverageBuffer=1 ## 1
e_CoverageBufferEarlyOut=1 ## 1
e_CoverageBufferReproj=6 ## 6
e_CoverageBufferTerrain=0 ## 0
e_CoverageBufferTerrainLodShift=2 ## 2
e_CoverageBufferVersion=2 ## 2
e_CullVegActivation=50 ## 50
e_DecalsAllowGameDecals=1 ## 1
e_DecalsDefferedDynamic=1 ## 1
e_DecalsDefferedStatic=1 ## 1
e_DecalsForceDeferred=0 ## 0
e_DecalsLifeTimeScale=2 ## 2
e_DecalsOverlapping=1 ## 1
e_DecalsPlacementTestAreaSize=0.08 ## 0.08
e_DecalsRange=20 ## 20
e_DeformableObjects=1 ## 1
e_Dissolve=2 ##
e_Dissolve=2 ## 2
e_DissolveDistband=3 ##
e_DissolveDistMax=8 ##
e_DissolveDistMin=2 ##
e_DynamicLights=1 ## 1
e_DynamicLightsMaxEntityLights=16 ## 16
e_Fog=1 ## 1
e_FogVolumes=1 ## 1
e_FoliageWindActivationDist=25 ## 25
e_GeomCaches=1 ## 1
e_GI=0 ## 0
e_GIAmount=0.6 ## 0.6
e_GICache=7 ## 7
e_GIIterations=6 ## 6
e_GIMaxDistance=100 ## 100
e_GINumCascades=1 ## 1
e_GsmLodsNum=5 ## 5
e_GsmRange=3 ## 3
e_HwOcclusionCullingWater=1 ## 1
e_LightVolumes=1 ## 1
e_LodCompMaxSize=6 ## 6
e_LodMax=5 ## 5
e_LodMin=0 ## 0
e_LodMinTtris=300 ## 300
e_Lods=1 ## 1
e_LodsForceUse=1 ## 1
e_MaxViewDistSpecLerp=1 ## 1
e_MergedMeshesPool=16384 ## 16384
e_MergedMeshesUseSpines=1 ## 1
e_ObjFastRegister=1 ## 1
e_ObjQuality=4 ## 4
e_ObjShadowCastSpec=7 ## 7
e_OcclusionCullingViewDistRatio=1 ## 1
e_ParticlesAnimBlend=1 ## 1
e_ParticlesCullAgainstOcclusionBuffer=1 ## 1
e_ParticlesGI=1 ## 1
e_ParticlesLayeredUpdateMul=5 ## 5
e_ParticlesLod=1 ## 1
e_ParticlesMaxDrawScreen=2 ## 2
e_ParticlesMaxScreenFill=160 ## 160
e_ParticlesMinDrawPixels=1 ## 1
e_ParticlesObjectCollisions=2 ## 2
e_ParticlesPoolSize=16384 ## 16384
e_ParticlesPreload=0 ## 0
e_ParticlesQuality=4 ## 4
e_ParticlesShadows=1 ## 1
e_ParticlesSoftIntersect=1 ## 1
e_ParticlesSortQuality=0 ## 0 
e_ParticlesThread=1 ## 1
e_PhysOceanCell=0.5 ## 0.5
e_PrecacheLevel=0 ## 0
e_PreloadDecals=1 ## 1
e_PreloadMaterials=1 ## 1
e_ProcVegetation=0 ## 0
e_Shadows=1 ## 1
e_ShadowsBlendCascades=2 ## 2
e_ShadowsCastViewDistRatio=1.6 ## 1.6
e_ShadowsCastViewDistRatioLights=0.8 ## 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6 ## 0.6
e_ShadowsClouds=1 ## 1
e_ShadowsLodBiasFixed=0 ## 0
e_ShadowsOnAlphaBlend=0 ## 0
e_ShadowsPoolSize=4096 ## 4096
e_ShadowsResScale=4 ## 4
e_ShadowsTessellateCascades=1 ## 1
e_ShadowsTessellateDLights=0 ## 0
e_ShadowsUpdateViewDistRatio=100 ## 100
e_SkyBox=1 ## 1
e_SkyQuality=1 ## 1
e_SkyUpdateRate=1 ## 1
e_StatObjBufferRenderTasks=1 ## 1
e_StatObjMerge=1 ## 1
e_StatObjPreload=1 ## 1
e_StreamCgf=1 ## 1
e_StreamInstancesMinLoadedNodes=2048 ## 2048
e_Sun=1 ## 1
e_SunAngleClamp=20 ## 20
e_svoTI_ConeMaxLength=35 ## 35
e_svoTI_Diffuse_Cache=0 ## 0
e_svoTI_DiffuseAmplifier=1 ## 1
e_svoTI_DiffuseConeWidth=6 ## 6
e_svoTI_DistantSsaoAmount=1 ## 1
e_svoTI_DualTracing=0 ## 0
e_svoTI_EmissiveMultiplier=4 ## 4
e_svoTI_RsmConeMaxLength=12 ## 12
e_svoTI_SkipNonGILights=0 ## 0
e_svoTI_SpecularAmplifier=1 ## 1
e_svoVoxGenRes=512 ## 512
e_TerrainAo=0 ## 0
e_TerrainLodRatio=0.2 ## 0.2
e_TerrainTextureLodRatio=1 ## 1
e_Tessellation=1 ## 1
e_TessellationMaxDistance=30 ## 30
e_UberlodDistanceRatio=2.5 ## 2.5
e_VegetationUseTerrainColor=1 ## 1
e_VegetationUseTerrainColorDistance=80 ## 80
e_ViewDistRatioCustom=150 ## 150
e_ViewDistRatioDetail=125 ## 125
e_ViewDistRatioLights=80 ## 80
e_ViewDistRatioVegetation=65 ## 65
e_WaterOcean=1 ## 1
e_WaterOceanBottom=1 ## 1
e_WaterTessellationAmount=10 ## 10
e_WaterTessellationAmountX=85 ## 85
e_WaterTessellationAmountY=85 ## 85
e_WaterTessellationSwathWidth=10 ## 10
e_WaterVolumes=1 ## 1
e_WaterWavesTessellationAmount=5 ## 5
e_Wind=1 ## 1
es_DebrisLifetimeScale=1 ## 1
es_MaxPhysDistInvisible=25 ## 25
g_breakage_particles_limit=160 ## 160
g_radialBlur=0 ## 1
g_tree_cut_reuse_dist=0 ## 0
gpu_Particle_Physics=1 ## 1
i_iceeffects=0 ## 0
i_particleeffects=1 ## 1
i_precache=1 ## 1
i_rejecteffects=1 ## 1
mfx_Enable=1 ## 1
mfx_EnableAttachedEffects=1 ## 1
mfx_EnableFGEffects=1 ## 1
mfx_Timeout=0.01 ## 0.01
p_cull_distance=100 ## 100
p_gravity_z=-9.81 ## -9.81
p_max_MC_iters=6000 ## 6000
p_max_object_splashes=3 ## 3
p_max_substeps=5 ## 5
p_max_substeps_large_group=5 ## 5
p_splash_dist0=7 ## 7
p_splash_dist1=30 ## 30
p_splash_force0=10 ## 10
p_splash_force1=100 ## 100
p_splash_vel0=4.5 ## 4.5
p_splash_vel1=10 ## 10
r_AntialiasingTAAPattern=1 ## 1
r_Batching=1 ## 1
r_BatchType=1 ## 1
r_Beams=1 ## 1
r_ChromaticAberration=0 ## 0
r_CloudsUpdateAlways=0 ## 0
r_ColorGrading=2 ## 2
r_ColorGradingChartsCache=0 ## 0
r_ConditionalRendering=0 ## 0
r_CustomResMaxSize=4096 ## 4096
r_DeferredShadingAreaLights=1 ## 1
r_DeferredShadingFilterGBuffer=0 ## 0
r_DeferredShadingSSS=1 ## 1
r_DeferredShadingTiled=2 ## 2
r_DeferredShadingTiledHairQuality=1 ## 1
r_DepthOfField=2 ## 2
r_DepthOfFieldDilation=0 ## 0
r_DetailDistance=8 ## 8
r_DrawNearShadows=1 ## 1
r_DynTexAtlasCloudsMaxSize=32 ## 32
r_DynTexAtlasDynTexSrcSize=16 ## 16
r_DynTexAtlasVoxTerrainMaxSize=250 ## 250
r_DynTexMaxSize=160 ## 160
r_EnvCMResolution=2 ## 2
r_EnvTexResolution=3 ## 3
r_EnvTexUpdateInterval=0.05 ## 0.05
r_FlareHqShafts=1 ## 1
r_Flares=0 ## 0
r_FlaresTessellationRatio=1 ## 1
r_FogShadows=0 ## 0
r_FogShadowsMode=0 ## 0
r_HDRBloom=1 ## 1
r_HDREyeAdaptationMode=1 ## 1
r_HDREyeAdaptationSpeed=3 ## 3
r_HDRGrainAmount=0 ## 0
r_HDRRendering=1 ## 1
r_ImposterRatio=1 ## 1
r_LightPropagationVolumes=1 ## 1
r_MergeRenderChunks=1 ## 1
r_MeshPrecache=1 ## 1
r_MotionBlurMaxViewDist=32 ## 32
r_MotionBlurShutterSpeed=125 ## 125 
r_MSAA=0 ## 0
r_MSAA_quality=0 ## 0
r_MSAA_samples=0 ## 0
r_MultiThreaded=1 ## 1
r_ParticlesHalfRes=0 ## 0
r_ParticlesTessellation=1 ## 1
r_PostProcessEffects=1 ## 1
r_PostProcessFilters=1 ## 1
r_PostProcessGameFx=1 ## 1
r_PostProcessHUD3DCache=0 ## 0
r_Rain=2 ## 2
r_RainDropsEffect=1 ## 1
r_RainOccluderSizeTreshold=10 ## 10
r_Refraction=1 ## 1
r_ShadowBlur=3 ## 3
r_ShadowCastingLightsMaxCount=28 ## 28
r_ShadowJittering=2.5 ## 2.5
r_ShadowPoolMaxFrames=5 ## 5
r_ShadowPoolMaxTimeslicedUpdatesPerFrame=120 ## 120
r_ShadowsCache=0 ## 0
r_ShadowsCacheResolutions=6324,4214,2810,1872,624 ## 6324,4214,2810,1872,624
r_ShadowsPCFiltering=1 ## 1
r_ShadowsScreenSpace=2 ## 2
r_ShadowsUseClipVolume=1 ## 1
r_Sharpening=0 ## 0
r_ssdo=1 ## 1
r_ssdoColorBleeding=1 ## 1
r_ssdoRadius=0.3 ## 0.3
r_ssdoRadiusMax=2 ## 2
r_SunShafts=2 ## 2
r_TerrainAO_FadeDist=8 ## 8
r_TessellationTriangleSize=8 ## 8
r_TexAtlasSize=2048 ## 2048
r_TexMaxAnisotropy=16 ## 16
r_TexMinAnisotropy=16 ## 16
r_TexNoAnisoAlphaTest=0 ## 0
r_TextureLodDistanceRatio=-1 ## -1
r_TexturesSkipLowerMips=0 ## 0
r_TexturesStreaming=1 ## 1
r_TexturesstreamingMinUsableMips=8 ## 8
r_TexturesStreamingMipBias=0 ## 0
r_TexturesStreamingResidencyEnabled=1 ## 1
r_TexturesStreamingSkipMips=0 ## 0
r_TranspDepthFixup=1 ## 1
r_Unlit=0 ## 0
r_UseHWSkinning=1 ## 1
r_UseMaterialLayers=2 ## 2
r_UseMergedPosts=1 ## 1
r_UseZPass=2 ## 2
r_VolumetricFogSunLightCorrection=1 ## 1
r_WaterCaustics=0 ## 0
r_WaterGodRays=0 ## 0
r_WaterReflections=1 ## 1
r_WaterReflectionsQuality=0 ## 0
r_WaterTessellationHW=1 ## 1
r_WaterUpdateDistance=0.2 ## 0.2
r_WaterUpdateFactor=0 ## 0
r_WaterUpdateThread=5 ## 5
r_WaterVolumeCausticsDensity=256 ## 256
r_WaterVolumeCausticsMaxDist=35 ## 35
r_WaterVolumeCausticsRes=1024 ## 1024
r_WaterVolumeCausticsSnapFactor=1 ## 1
sys_budget_soundCPU=15 ## 15
sys_flash_allow_reset_mesh_cache=1 ## 1
sys_flash_curve_tess_error=2 ## 2
sys_flash_edgeaa=1 ## 1
sys_flash_newstencilclear=1 ## 1
sys_flash_static_pool_size=0 ## 0
sys_flash_use_arenas=1 ## 1
sys_job_system_enable=1 ## 1
sys_limit_phys_thread_count=0 ## 0
sys_physics_CPU=0 ## 0
sys_preload=0 ## 0
sys_spec_Quality=4 ## 4
sys_streaming_CPU=1 ## 1
sys_streaming_max_bandwidth=0 ## 0
v_vehicle_quality=4 ## 4
wh_cc_CharacterDetailReduction=0 ## 0
wh_cc_LodForAttachmentStreamOut=6 ## 6
wh_cc_LodForItemStreamOutBase=20 ## 20
wh_env_DirtCreationSpeed=0.05 ## 0.05
wh_env_DirtDryupSpeed=0.05 ## 0.05
wh_env_PuddleCreationDelay=1000 ## 1000
wh_env_PuddleCreationSpeed=0.005 ## 0.005
wh_env_PuddleDryupDelay=0 ## 0 
wh_env_PuddleDryupSpeed=0.005 ## 0.005
wh_env_puddleMaskMin=0 ## 0
wh_env_RainDropsAmountMul=15 ## 15
wh_env_RainDropsSpeedMul=7 ## 7
wh_env_RainLayers=3 ## 3
wh_env_RainWindStrength=10 ## 10
wh_item_ViewDistRatio=100 ## 100
wh_pl_FOWEnabled=1 ## 1
wh_pl_FOWVisibilityRadius=100 ## 100
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









//////////////////////////



better





## updated 1/14/2025 v0.9.0 :ramen:

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
## Create user.cfg in KingdomComeDeliverance folder and copy paste
## delete cache folder %userprofile%/Saved Games/kingdomcome/shaders
## Add launch commands: +exec user.cfg -devmode
## and restart after getting to main menu

con_restricted=0 ##
r_DisplayInfo=0 ##
sys_MaxFPS=158 ## 0 ""

sys_spec=0 ## "sets custom spec"
sys_spec_GameEffects=7 ##
sys_spec_Light=7 ##
sys_spec_ObjectDetail=7 ##
sys_spec_Particles=7 ##
sys_spec_Physics=7 ##
sys_spec_PostProcessing=7 ##
sys_spec_Shading=7 ##
sys_spec_Shadows=7 ##
sys_spec_Sound=7 ##
sys_spec_Texture=7 ##
sys_spec_TextureResolution=7 ## "7 HD textures"
sys_spec_Vegetation=7 ##
sys_spec_VolumetricEffects=7 ##
sys_spec_Water=7 ##

## q_Quality=3 ## "change per"
q_Renderer=3 ##
q_ShaderFX=3 ##
q_ShaderGeneral=3 ##
q_ShaderGlass=3 ##
q_ShaderHDR=3 ##
q_ShaderIce=3 ##
q_ShaderMetal=3 ##
q_ShaderPostProcess=3 ##
q_ShaderShadow=3 ##
q_ShaderSky=3 ##
q_ShaderTerrain=3 ##
q_ShaderVegetation=3 ##
q_ShaderWater=3 ## 2 ""

Bind 0 g_showHUD 0 ##
Bind 9 g_showHUD 1 ##
Bind f1 sys_MaxFPS 158 ##
Bind f2 sys_MaxFPS 60 ##
Bind f3 "exec TEST1.cfg" ## "make"
Bind f4 "exec TEST2.cfg" ## "make"
cl_fov=68 ## 60
cl_sensitivity=10 ##
g_skipIntro=1 ## 0
i_mouse_accel=0 ##
i_mouse_smooth=0 ##
pl_movement.power_sprint_targetFOV=68 ## 55 ""
r_DrawNearFOV=68 ## 60 ""
r_Vsync=0 ##
wh_cs_PlayerLockDisabled=0 ## 0
wh_horse_CameraCentering=0 ## 0.2 ""
wh_pl_showfirecursor=1 ## 0

## e_VegetationMinSize=0 ## 0.1 "pickable vegetation"
## r_DynTexAtlasSpritesMaxSize=32 ## 32 "not real"
## r_HDRBrightLevel=1 ## 1 "not real"
## r_SilhouettePOM=0 ## 0 ""
## s_ObstructionMaxValue=0 ## 0 "not real"
e_CoverageBufferTerrainExpand=1 ## 0.025 ""
e_LodFaceAreaTargetSize=0.0006 ## 0.001 ""
e_LodRatio=70 ## 60 "70 max slider"
e_svoTI_IntegrationMode=0 ## 0
e_svoVoxelPoolResolution=128 ## 128
e_MergedMeshesInstanceDist=32 ## 16 ""
e_MergedMeshesLodRatio=16 ## 8 ""
e_MergedMeshesViewDistRatio=100 ## 85 "100 max slider"
e_ParticlesMotionBlur=0 ## 1 ""
e_PhysProxyTriLimit=1000 ## 10000 ""
e_ShadowsMaxTexRes=1872 ## 1024 ""
e_StreamCgfPoolSize=1024 ## 512 "RAM"
e_svoTI_LowSpecMode=2 ## 1 ""
e_svoTI_Saturation=1 ## 0.8 ""
e_svoTI_SkyColorMultiplier=-0.6 ## -1.0001 ""
e_svoTI_SSAOAmount=1.5 ## 1 ""
e_svoTI_VoxelizeUnderTerrain=0 ## 1 ""
e_TerrainDetailMaterialsViewDistZ=120 ## 100 ""
e_ViewDistMin=10 ## 5 ""
e_ViewDistRatio=150 ## 125 "150 max slider"
e_VolumetricFog=0 ## 0 ""
e_WaterOceanFFT=0 ## 1 ""
es_MaxPhysDist=100 ## 200 ""
es_maxphysdistcloth=100 ## 300 ""
p_num_bodies_large_group=10 ## 100 ""
p_num_threads=7 ## 2 ""
r_AntialiasingMode=3 ## 2 ""
r_AntialiasingTAASharpening=0 ## 0.2 ""
r_DrawNearZRange=0.1 ## 0.001 ""
r_FogShadowsWater=1 ## 1 ""
r_HDRVignetting=0 ## 1 ""
r_MotionBlur=0 ## 2 ""
r_MotionBlurQuality=0 ## 2 ""
r_MultiGPU=0 ## 1 ""
r_RainAmount=2 ## 1 ""
r_RainDistMultiplier=2.5 ## 2 ""
r_RainMaxViewDist_Deferred=170 ## 150 ""
r_RenderTargetPoolSize=512 ## 0 ""
r_ssdoAmountAmbient=1.5 ## 1 ""
r_ssdoAmountDirect=4 ## 1.5 ""
r_ssdoAmountReflection=5 ## 4 ""
r_ssdoHalfRes=0 ## 2 ""
r_ssdoRadiusMin=0.02 ## 0.1 ""
r_SSReflections=0 ## 1 ""
r_SSReflHalfRes=1 ## 0 ""
r_TerrainAO=0 ## 7 ""
r_TexPreallocateAtlases=1 ## 0 ""
r_TexturesStreamingMaxRequestedMB=500 ## 20 ""
r_TexturesStreamingResidencyThrottle=1 ## 0.5 ""
r_TexturesStreamingResidencyTime=90 ## 10 ""
r_TexturesStreampoolDefragmentation=2 ## 2 "1,2 CPU,GPU"
r_TexturesStreampoolDefragmentationMaxAmount=3145728 ## 2097152 "testing"
r_TexturesStreampoolDefragmentationMaxMoves=15 ## 10 "testing"
r_TexturesStreamPoolSize=11264 ## 4096 "set to 70% of VRAM and round down"
r_VolumetricFogTexDepth=4 ## 32 ""
r_VolumetricFogTexScale=20 ## 10 ""
r_WaterVolumeCaustics=0 ## 1 ""
s_OcclusionMaxDistance=150 ## 500 ""
sys_budget_sysmem=1024 ## 512 "debug"
sys_budget_videomem=1024 ## 90 "debug"
sys_flash_address_space=131072 ## 65536 ""
sys_flash_check_filemodtime=1 ## 0 ""
sys_PakStreamCache=0 ## 0 "" RAM
sys_streaming_CPU_worker=7 ## 5 ""
WH_AI_LOD_DistanceMax=160 ## "90,110,130"
WH_AI_LOD_DistanceMin=130 ## "60,80,100"
wh_env_RainDiffuseDarkening=0.33 ## 0.2 ""
wh_env_RainDropsSpeedBase=3 ## 1.5 ""

ca_AttachmentCullingRation=450 ## 450
e_Brushes=1 ## 1
e_Clouds=1 ## 1
e_CoverageBufferEarlyOut=1 ## 1
e_CoverageBufferReproj=6 ## 6
e_CullVegActivation=50 ## 50
e_DecalsAllowGameDecals=1 ## 1
e_DecalsLifeTimeScale=2 ## 2
e_DecalsOverlapping=1 ## 1
e_Dissolve=2 ## 2
e_DynamicLights=1 ## 1
e_DynamicLightsMaxEntityLights=16 ## 16
e_Fog=1 ## 1
e_FoliageWindActivationDist=25 ## 25
e_GI=0 ## 0
e_GIAmount=0.6 ## 0.6
e_GICache=7 ## 7
e_GIIterations=6 ## 6
e_GIMaxDistance=100 ## 100
e_GINumCascades=1 ## 1
e_GsmLodsNum=5 ## 5
e_GsmRange=3 ## 3
e_HwOcclusionCullingWater=1 ## 1
e_LightVolumes=1 ## 1
e_LodMin=0 ## 0
e_MaxViewDistSpecLerp=1 ## 1
e_MergedMeshesPool=16384 ## 16384
e_MergedMeshesUseSpines=1 ## 1
e_ObjFastRegister=1 ## 1
e_ObjQuality=4 ## 4
e_ObjShadowCastSpec=7 ## 7
e_OcclusionCullingViewDistRatio=1 ## 1
e_ParticlesCullAgainstOcclusionBuffer=1 ## 1
e_ParticlesGI=1 ## 1
e_ParticlesLayeredUpdateMul=5 ## 5
e_ParticlesMaxScreenFill=160 ## 160
e_ParticlesMinDrawPixels=1 ## 1
e_ParticlesObjectCollisions=2 ## 2
e_ParticlesPoolSize=16384 ## 16384
e_ParticlesQuality=4 ## 4
e_ParticlesShadows=1 ## 1
e_ParticlesSortQuality=0 ## 0 
e_ParticlesThread=1 ## 1
e_PhysOceanCell=0.5 ## 0.5
e_PreloadMaterials=1 ## 1
e_ProcVegetation=0 ## 0
e_Shadows=1 ## 1
e_ShadowsBlendCascades=2 ## 2
e_ShadowsCastViewDistRatio=1.6 ## 1.6
e_ShadowsCastViewDistRatioLights=0.8 ## 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6 ## 0.6
e_ShadowsClouds=1 ## 1
e_ShadowsLodBiasFixed=0 ## 0
e_ShadowsOnAlphaBlend=0 ## 0
e_ShadowsPoolSize=4096 ## 4096
e_ShadowsResScale=4 ## 4
e_ShadowsTessellateCascades=1 ## 1
e_ShadowsTessellateDLights=0 ## 0
e_ShadowsUpdateViewDistRatio=100 ## 100
e_SkyQuality=1 ## 1
e_SkyUpdateRate=1 ## 1
e_StatObjBufferRenderTasks=1 ## 1
e_StatObjMerge=1 ## 1
e_StreamCgf=1 ## 1
e_StreamInstancesMinLoadedNodes=2048 ## 2048
e_SunAngleClamp=20 ## 20
e_svoTI_ConeMaxLength=35 ## 35
e_svoTI_Diffuse_Cache=0 ## 0
e_svoTI_DiffuseAmplifier=1 ## 1
e_svoTI_DiffuseConeWidth=6 ## 6
e_svoTI_DistantSsaoAmount=1 ## 1
e_svoTI_DualTracing=0 ## 0
e_svoTI_EmissiveMultiplier=4 ## 4
e_svoTI_RsmConeMaxLength=12 ## 12
e_svoTI_SkipNonGILights=0 ## 0
e_svoTI_SpecularAmplifier=1 ## 1
e_svoVoxGenRes=512 ## 512
e_TerrainAo=0 ## 0
e_TerrainLodRatio=0.2 ## 0.2
e_Tessellation=1 ## 1
e_TessellationMaxDistance=30 ## 30
e_UberlodDistanceRatio=2.5 ## 2.5
e_VegetationUseTerrainColor=1 ## 1
e_VegetationUseTerrainColorDistance=80 ## 80
e_ViewDistRatioCustom=150 ## 150
e_ViewDistRatioDetail=125 ## 125
e_ViewDistRatioLights=80 ## 80
e_ViewDistRatioVegetation=65 ## 65
e_WaterTessellationAmount=10 ## 10
e_WaterTessellationAmountX=85 ## 85
e_WaterTessellationAmountY=85 ## 85
e_WaterTessellationSwathWidth=10 ## 10
e_Wind=1 ## 1
es_DebrisLifetimeScale=1 ## 1
es_MaxPhysDistInvisible=25 ## 25
g_breakage_particles_limit=160 ## 160
g_radialBlur=0 ## 1
g_tree_cut_reuse_dist=0 ## 0
gpu_Particle_Physics=1 ## 1
i_particleeffects=1 ## 1
mfx_Timeout=0.01 ## 0.01
p_cull_distance=100 ## 100
p_gravity_z=-9.81 ## -9.81
p_max_MC_iters=6000 ## 6000
p_max_object_splashes=3 ## 3
p_max_substeps=5 ## 5
p_max_substeps_large_group=5 ## 5
p_splash_dist0=7 ## 7
p_splash_dist1=30 ## 30
p_splash_force0=10 ## 10
p_splash_force1=100 ## 100
p_splash_vel0=4.5 ## 4.5
p_splash_vel1=10 ## 10
r_AntialiasingTAAPattern=1 ## 1
r_Beams=1 ## 1
r_ChromaticAberration=0 ## 0
r_ColorGrading=2 ## 2
r_ColorGradingChartsCache=0 ## 0
r_CustomResMaxSize=4096 ## 4096
r_DeferredShadingAreaLights=1 ## 1
r_DeferredShadingFilterGBuffer=0 ## 0
r_DeferredShadingSSS=1 ## 1
r_DeferredShadingTiled=2 ## 2
r_DeferredShadingTiledHairQuality=1 ## 1
r_DepthOfField=2 ## 2
r_DepthOfFieldDilation=0 ## 0
r_DetailDistance=8 ## 8
r_DrawNearShadows=1 ## 1
r_DynTexAtlasCloudsMaxSize=32 ## 32
r_DynTexAtlasDynTexSrcSize=16 ## 16
r_DynTexAtlasVoxTerrainMaxSize=250 ## 250
r_DynTexMaxSize=160 ## 160
r_EnvCMResolution=2 ## 2
r_EnvTexResolution=3 ## 3
r_EnvTexUpdateInterval=0.05 ## 0.05
r_FlareHqShafts=1 ## 1
r_Flares=0 ## 0
r_FlaresTessellationRatio=1 ## 1
r_FogShadows=0 ## 0
r_FogShadowsMode=0 ## 0
r_HDRBloom=1 ## 1
r_HDREyeAdaptationMode=1 ## 1
r_HDREyeAdaptationSpeed=3 ## 3
r_HDRGrainAmount=0 ## 0
r_HDRRendering=1 ## 1
r_ImposterRatio=1 ## 1
r_MergeRenderChunks=1 ## 1
r_MotionBlurMaxViewDist=32 ## 32
r_MotionBlurShutterSpeed=125 ## 125 
r_ParticlesHalfRes=0 ## 0
r_ParticlesTessellation=1 ## 1
r_PostProcessHUD3DCache=0 ## 0
r_RainDropsEffect=1 ## 1
r_RainOccluderSizeTreshold=10 ## 10
r_Refraction=1 ## 1
r_ShadersDX11=1 ## 1
r_ShadowBlur=3 ## 3
r_ShadowCastingLightsMaxCount=28 ## 28
r_ShadowJittering=2.5 ## 2.5
r_ShadowPoolMaxFrames=5 ## 5
r_ShadowPoolMaxTimeslicedUpdatesPerFrame=120 ## 120
r_ShadowsCache=0 ## 0
r_ShadowsCacheResolutions=6324,4214,2810,1872,624 ## 6324,4214,2810,1872,624
r_ShadowsPCFiltering=1 ## 1
r_ShadowsScreenSpace=2 ## 2
r_ShadowsUseClipVolume=1 ## 1
r_Sharpening=0 ## 0
r_ssdo=1 ## 1
r_ssdoColorBleeding=1 ## 1
r_ssdoRadius=0.3 ## 0.3
r_ssdoRadiusMax=2 ## 2
r_SunShafts=2 ## 2
r_TerrainAO_FadeDist=8 ## 8
r_TessellationTriangleSize=8 ## 8
r_TexAtlasSize=2048 ## 2048
r_TexMaxAnisotropy=16 ## 16
r_TexMinAnisotropy=16 ## 16
r_TexNoAnisoAlphaTest=0 ## 0
r_TexturesSkipLowerMips=0 ## 0
r_TexturesStreaming=1 ## 1
r_TexturesstreamingMinUsableMips=8 ## 8
r_TexturesStreamingResidencyEnabled=1 ## 1
r_TexturesStreamingSkipMips=0 ## 0
r_TranspDepthFixup=1 ## 1
r_Unlit=0 ## 0
r_UseMaterialLayers=2 ## 2
r_UseZPass=2 ## 2
r_VolumetricFogSunLightCorrection=1 ## 1
r_WaterCaustics=0 ## 0
r_WaterGodRays=0 ## 0
r_WaterReflectionsQuality=0 ## 0
r_WaterTessellationHW=1 ## 1
r_WaterUpdateDistance=0.2 ## 0.2
r_WaterUpdateFactor=0 ## 0
r_WaterUpdateThread=5 ## 5
r_WaterVolumeCausticsDensity=256 ## 256
r_WaterVolumeCausticsMaxDist=35 ## 35
r_WaterVolumeCausticsRes=1024 ## 1024
r_WaterVolumeCausticsSnapFactor=1 ## 1
sys_budget_soundCPU=15 ## 15
sys_flash_allow_reset_mesh_cache=1 ## 1
sys_flash_curve_tess_error=2 ## 2
sys_flash_edgeaa=1 ## 1
sys_flash_newstencilclear=1 ## 1
sys_flash_static_pool_size=0 ## 0
sys_flash_use_arenas=1 ## 1
sys_limit_phys_thread_count=0 ## 0
sys_physics_CPU=0 ## 0
sys_preload=0 ## 0
sys_spec_Quality=4 ## 4
sys_streaming_CPU=1 ## 1
v_vehicle_quality=4 ## 4
wh_cc_CharacterDetailReduction=0 ## 0
wh_cc_LodForAttachmentStreamOut=6 ## 6
wh_cc_LodForItemStreamOutBase=20 ## 20
wh_env_DirtCreationSpeed=0.05 ## 0.05
wh_env_DirtDryupSpeed=0.05 ## 0.05
wh_env_PuddleCreationDelay=1000 ## 1000
wh_env_PuddleCreationSpeed=0.005 ## 0.005
wh_env_PuddleDryupDelay=0 ## 0 
wh_env_PuddleDryupSpeed=0.005 ## 0.005
wh_env_puddleMaskMin=0 ## 0
wh_env_RainDropsAmountMul=15 ## 15
wh_env_RainDropsSpeedMul=7 ## 7
wh_env_RainLayers=3 ## 3
wh_env_RainWindStrength=10 ## 10
wh_pl_FOWEnabled=1 ## 1
wh_pl_FOWVisibilityRadius=100 ## 100
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
















//////////////////////////////////////



big change seems good




## updated 1/14/2025 for KCD v1.9.6 :ramen: 

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
## Create user.cfg in KingdomComeDeliverance folder and copy paste
## delete cache folder %userprofile%/Saved Games/kingdomcome/shaders
## Add launch commands: +exec user.cfg -devmode
## and restart after getting to main menu

con_restricted=0 ##
r_DisplayInfo=0 ##
sys_MaxFPS=158 ## 0 ""

sys_spec=0 ## "sets custom spec"
sys_spec_GameEffects=7 ##
sys_spec_Light=7 ##
sys_spec_ObjectDetail=7 ##
sys_spec_Particles=7 ##
sys_spec_Physics=7 ##
sys_spec_PostProcessing=7 ##
sys_spec_Shading=7 ##
sys_spec_Shadows=7 ##
sys_spec_Sound=7 ## EDIT
sys_spec_Texture=7 ##
sys_spec_TextureResolution=7 ## "7 HD textures"
sys_spec_Vegetation=7 ##
sys_spec_VolumetricEffects=7 ##
sys_spec_Water=7 ##

## q_Quality=3 ## "change per"
q_Renderer=3 ##
q_ShaderFX=3 ##
q_ShaderGeneral=3 ##
q_ShaderGlass=3 ##
q_ShaderHDR=3 ##
q_ShaderIce=3 ##
q_ShaderMetal=3 ##
q_ShaderPostProcess=3 ##
q_ShaderShadow=3 ##
q_ShaderSky=3 ##
q_ShaderTerrain=3 ##
q_ShaderVegetation=3 ##
q_ShaderWater=3 ## 2 ""

Bind 0 g_showHUD 0 ##
Bind 9 g_showHUD 1 ##
Bind f1 sys_MaxFPS 158 ##
Bind f2 sys_MaxFPS 60 ##
Bind f3 "exec TEST1.cfg" ## "make"
Bind f4 "exec TEST2.cfg" ## "make"
cl_fov=68 ## 60
cl_sensitivity=10 ##
g_skipIntro=1 ## 0
i_mouse_accel=0 ##
i_mouse_smooth=0 ##
pl_movement.power_sprint_targetFOV=68 ## 55 ""
r_DrawNearFOV=68 ## 60 ""
r_Vsync=0 ##
wh_cs_PlayerLockDisabled=0 ## 0
wh_horse_CameraCentering=0 ## 0.2 ""
wh_pl_showfirecursor=1 ## 0

## e_VegetationMinSize=0 ## 0.1 "pickable vegetation"
## r_DynTexAtlasSpritesMaxSize=32 ## 32 "not real"
## r_HDRBrightLevel=1 ## 1 "not real"
## r_SilhouettePOM=0 ## 0 ""
## s_ObstructionMaxValue=0 ## 0 "not real"
e_CoverageBufferTerrainExpand=1 ## 0.025 ""
e_LodFaceAreaTargetSize=0.0006 ## 0.001 ""
e_LodRatio=70 ## 60 "70 max slider"
e_MergedMeshesInstanceDist=32 ## 16 ""
e_MergedMeshesLodRatio=16 ## 8 ""
e_MergedMeshesViewDistRatio=100 ## 85 "100 max slider"
e_ParticlesMotionBlur=0 ## 1 ""
e_PhysProxyTriLimit=1000 ## 10000 ""
e_ShadowsMaxTexRes=1872 ## 1024 ""
e_StreamCgfPoolSize=1024 ## 512 "RAM"
e_svoti_LowSpecMode=4 ## 1 ""
e_svoTI_SSAOAmount=1.5 ## 1 ""
e_TerrainDetailMaterialsViewDistZ=120 ## 100 ""
e_ViewDistMin=10 ## 5 ""
e_ViewDistRatio=150 ## 125 "150 max slider"
e_VolumetricFog=0 ## 0 ""
e_WaterOceanFFT=0 ## 1 ""
es_MaxPhysDist=100 ## 200 ""
es_maxphysdistcloth=100 ## 300 ""
p_num_bodies_large_group=10 ## 100 ""
p_num_threads=7 ## 2 ""
r_AntialiasingMode=3 ## 2 ""
r_AntialiasingTAASharpening=0 ## 0.2 ""
r_DrawNearZRange=0.1 ## 0.001 ""
r_FogShadowsWater=1 ## 1 ""
r_HDRVignetting=0 ## 1 ""
r_MotionBlur=0 ## 2 ""
r_MotionBlurQuality=0 ## 2 ""
r_MultiGPU=0 ## 1 ""
r_RainAmount=2 ## 1 ""
r_RainDistMultiplier=2.5 ## 2 ""
r_RainMaxViewDist_Deferred=170 ## 150 ""
r_RenderTargetPoolSize=512 ## 0 ""
r_ssdoAmountAmbient=2 ## 1 ""
r_ssdoAmountDirect=4 ## 1.5 ""
r_ssdoAmountReflection=5 ## 4 ""
r_ssdoRadiusMin=0.02 ## 0.1 ""
r_SSReflections=0 ## 1 ""
r_SSReflHalfRes=1 ## 0 ""
r_TerrainAO=0 ## 7 ""
r_TexPreallocateAtlases=1 ## 0 ""
r_TexturesStreamingMaxRequestedMB=500 ## 20 ""
r_TexturesStreamingResidencyThrottle=1 ## 0.5 ""
r_TexturesStreamingResidencyTime=90 ## 10 ""
r_TexturesStreampoolDefragmentation=2 ## 2 "1,2 CPU,GPU"
r_TexturesStreampoolDefragmentationMaxAmount=3145728 ## 2097152 "testing"
r_TexturesStreampoolDefragmentationMaxMoves=15 ## 10 "testing"
r_TexturesStreamPoolSize=11264 ## 4096 "set to 70% of VRAM and round down"
r_VolumetricFogTexDepth=4 ## 32 ""
r_VolumetricFogTexScale=20 ## 10 ""
r_WaterVolumeCaustics=0 ## 1 ""
s_OcclusionMaxDistance=150 ## 500 ""
sys_budget_sysmem=1024 ## 512 "debug"
sys_budget_videomem=1024 ## 90 "debug"
sys_flash_address_space=131072 ## 65536 ""
sys_flash_check_filemodtime=1 ## 0 ""
sys_PakStreamCache=0 ## 0 "" RAM
sys_streaming_CPU_worker=7 ## 5 ""
WH_AI_LOD_DistanceMax=160 ## "90,110,130"
WH_AI_LOD_DistanceMin=130 ## "60,80,100"
wh_env_RainDiffuseDarkening=0.33 ## 0.2 ""
wh_env_RainDropsSpeedBase=3 ## 1.5 ""

ca_AttachmentCullingRation=450 ## 450
e_Brushes=1 ## 1
e_Clouds=1 ## 1
e_CoverageBufferEarlyOut=1 ## 1
e_CoverageBufferReproj=6 ## 6
e_CullVegActivation=50 ## 50
e_DecalsAllowGameDecals=1 ## 1
e_DecalsLifeTimeScale=2 ## 2
e_DecalsOverlapping=1 ## 1
e_Dissolve=2 ## 2
e_DynamicLights=1 ## 1
e_DynamicLightsMaxEntityLights=16 ## 16
e_Fog=1 ## 1
e_FoliageWindActivationDist=25 ## 25
e_GI=0 ## 0
e_GIAmount=0.6 ## 0.6
e_GICache=7 ## 7
e_GIIterations=6 ## 6
e_GIMaxDistance=100 ## 100
e_GINumCascades=1 ## 1
e_GsmLodsNum=5 ## 5
e_GsmRange=3 ## 3
e_HwOcclusionCullingWater=1 ## 1
e_LightVolumes=1 ## 1
e_LodMin=0 ## 0
e_MaxViewDistSpecLerp=1 ## 1
e_MergedMeshesPool=16384 ## 16384
e_MergedMeshesUseSpines=1 ## 1
e_ObjFastRegister=1 ## 1
e_ObjQuality=4 ## 4
e_ObjShadowCastSpec=7 ## 7
e_OcclusionCullingViewDistRatio=1 ## 1
e_ParticlesCullAgainstOcclusionBuffer=1 ## 1
e_ParticlesGI=1 ## 1
e_ParticlesLayeredUpdateMul=5 ## 5
e_ParticlesMaxScreenFill=160 ## 160
e_ParticlesMinDrawPixels=1 ## 1
e_ParticlesObjectCollisions=2 ## 2
e_ParticlesPoolSize=16384 ## 16384
e_ParticlesQuality=4 ## 4
e_ParticlesShadows=1 ## 1
e_ParticlesSortQuality=0 ## 0 
e_ParticlesThread=1 ## 1
e_PhysOceanCell=0.5 ## 0.5
e_PreloadMaterials=1 ## 1
e_ProcVegetation=0 ## 0
e_Shadows=1 ## 1
e_ShadowsBlendCascades=2 ## 2
e_ShadowsCastViewDistRatio=1.6 ## 1.6
e_ShadowsCastViewDistRatioLights=0.8 ## 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6 ## 0.6
e_ShadowsLodBiasFixed=0 ## 0
e_ShadowsOnAlphaBlend=0 ## 0
e_ShadowsPoolSize=4096 ## 4096
e_ShadowsResScale=4 ## 4
e_ShadowsTessellateCascades=1 ## 1
e_ShadowsTessellateDLights=0 ## 0
e_ShadowsUpdateViewDistRatio=100 ## 100
e_SkyQuality=1 ## 1
e_SkyUpdateRate=1 ## 1
e_StatObjBufferRenderTasks=1 ## 1
e_StatObjMerge=1 ## 1
e_StreamCgf=1 ## 1
e_StreamInstancesMinLoadedNodes=2048 ## 2048
e_SunAngleClamp=20 ## 20
e_svoTI_ConeMaxLength=35 ## 35
e_svoTI_DiffuseConeWidth=6 ## 6
e_svoTI_DistantSsaoAmount=1 ## 1
e_svoTI_RsmConeMaxLength=12 ## 12
e_TerrainAo=0 ## 0
e_TerrainLodRatio=0.2 ## 0.2
e_Tessellation=1 ## 1
e_TessellationMaxDistance=30 ## 30
e_UberlodDistanceRatio=1.8 ## 1.8
e_VegetationUseTerrainColor=1 ## 1
e_VegetationUseTerrainColorDistance=80 ## 80
e_ViewDistRatioCustom=150 ## 150
e_ViewDistRatioDetail=125 ## 125
e_ViewDistRatioLights=80 ## 80
e_ViewDistRatioVegetation=65 ## 65
e_WaterTessellationAmount=10 ## 10
e_WaterTessellationAmountX=85 ## 85
e_WaterTessellationAmountY=85 ## 85
e_WaterTessellationSwathWidth=10 ## 10
e_Wind=1 ## 1
es_DebrisLifetimeScale=1 ## 1
es_MaxPhysDistInvisible=25 ## 25
g_breakage_particles_limit=160 ## 160
g_radialBlur=0 ## 1
g_tree_cut_reuse_dist=0 ## 0
gpu_Particle_Physics=1 ## 1
i_particleeffects=1 ## 1
mfx_Timeout=0.01 ## 0.01
p_cull_distance=100 ## 100
p_gravity_z=-9.81 ## -9.81
p_max_MC_iters=6000 ## 6000
p_max_object_splashes=3 ## 3
p_max_substeps=5 ## 5
p_max_substeps_large_group=5 ## 5
p_splash_dist0=7 ## 7
p_splash_dist1=30 ## 30
p_splash_force0=10 ## 10
p_splash_force1=100 ## 100
p_splash_vel0=4.5 ## 4.5
p_splash_vel1=10 ## 10
r_AntialiasingTAAPattern=1 ## 1
r_Beams=1 ## 1
r_ChromaticAberration=0 ## 0
r_ColorGrading=2 ## 2
r_ColorGradingChartsCache=0 ## 0
r_CustomResMaxSize=4096 ## 4096
r_DeferredShadingAreaLights=1 ## 1
r_DeferredShadingFilterGBuffer=0 ## 0
r_DeferredShadingTiled=2 ## 2
r_DeferredShadingTiledHairQuality=1 ## 1
r_DepthOfField=2 ## 2
r_DepthOfFieldDilation=0 ## 0
r_DetailDistance=8 ## 8
r_DrawNearShadows=1 ## 1
r_DynTexAtlasCloudsMaxSize=32 ## 32
r_DynTexAtlasDynTexSrcSize=16 ## 16
r_DynTexAtlasVoxTerrainMaxSize=250 ## 250
r_DynTexMaxSize=160 ## 160
r_EnvCMResolution=2 ## 2
r_EnvTexResolution=3 ## 3
r_EnvTexUpdateInterval=0.05 ## 0.05
r_FlareHqShafts=1 ## 1
r_Flares=0 ## 0
r_FlaresTessellationRatio=1 ## 1
r_FogShadows=0 ## 0
r_FogShadowsMode=0 ## 0
r_HDRBloom=1 ## 1
r_HDRGrainAmount=0 ## 0
r_HDRRendering=1 ## 1
r_ImposterRatio=1 ## 1
r_MergeRenderChunks=1 ## 1
r_MotionBlurMaxViewDist=32 ## 32
r_MotionBlurShutterSpeed=125 ## 125 
r_ParticlesHalfRes=0 ## 0
r_ParticlesTessellation=1 ## 1
r_PostProcessHUD3DCache=0 ## 0
r_RainDropsEffect=1 ## 1
r_RainOccluderSizeTreshold=10 ## 10
r_Refraction=1 ## 1
r_ShadersDX11=1 ## 1
r_ShadowBlur=3 ## 3
r_ShadowCastingLightsMaxCount=28 ## 28
r_ShadowJittering=2.5 ## 2.5
r_ShadowPoolMaxFrames=5 ## 5
r_ShadowPoolMaxTimeslicedUpdatesPerFrame=120 ## 120
r_ShadowsCache=0 ## 0
r_ShadowsCacheResolutions=6324,4214,2810,1872,624 ## 6324,4214,2810,1872,624
r_ShadowsPCFiltering=1 ## 1
r_ShadowsScreenSpace=2 ## 2
r_ShadowsUseClipVolume=1 ## 1
r_Sharpening=0 ## 0
r_ssdo=1 ## 1
r_ssdoHalfRes=2 ## 2
r_ssdoRadius=0.3 ## 0.3
r_ssdoRadiusMax=2 ## 2
r_SunShafts=2 ## 2
r_TerrainAO_FadeDist=8 ## 8
r_TessellationTriangleSize=8 ## 8
r_TexAtlasSize=2048 ## 2048
r_TexMaxAnisotropy=16 ## 16
r_TexMinAnisotropy=16 ## 16
r_TexNoAnisoAlphaTest=0 ## 0
r_TexturesSkipLowerMips=0 ## 0
r_TexturesStreaming=1 ## 1
r_TexturesstreamingMinUsableMips=8 ## 8
r_TexturesStreamingResidencyEnabled=1 ## 1
r_TexturesStreamingSkipMips=0 ## 0
r_TranspDepthFixup=1 ## 1
r_Unlit=0 ## 0
r_UseMaterialLayers=2 ## 2
r_UseZPass=2 ## 2
r_VolumetricFogSunLightCorrection=1 ## 1
r_WaterCaustics=0 ## 0
r_WaterGodRays=0 ## 0
r_WaterReflectionsQuality=0 ## 0
r_WaterTessellationHW=1 ## 1
r_WaterUpdateDistance=0.2 ## 0.2
r_WaterUpdateFactor=0 ## 0
r_WaterUpdateThread=5 ## 5
r_WaterVolumeCausticsDensity=256 ## 256
r_WaterVolumeCausticsMaxDist=35 ## 35
r_WaterVolumeCausticsRes=1024 ## 1024
r_WaterVolumeCausticsSnapFactor=1 ## 1
sys_budget_soundCPU=15 ## 15
sys_flash_allow_reset_mesh_cache=1 ## 1
sys_flash_curve_tess_error=2 ## 2
sys_flash_edgeaa=1 ## 1
sys_flash_newstencilclear=1 ## 1
sys_flash_static_pool_size=0 ## 0
sys_flash_use_arenas=1 ## 1
sys_limit_phys_thread_count=0 ## 0
sys_physics_CPU=0 ## 0
sys_preload=0 ## 0
sys_spec_Quality=4 ## 4
sys_streaming_CPU=1 ## 1
v_vehicle_quality=4 ## 4
wh_cc_CharacterDetailReduction=0 ## 0
wh_cc_LodForAttachmentStreamOut=6 ## 6
wh_cc_LodForItemStreamOutBase=20 ## 20
wh_env_DirtCreationSpeed=0.05 ## 0.05
wh_env_DirtDryupSpeed=0.05 ## 0.05
wh_env_PuddleCreationDelay=1000 ## 1000
wh_env_PuddleCreationSpeed=0.005 ## 0.005
wh_env_PuddleDryupDelay=0 ## 0 
wh_env_PuddleDryupSpeed=0.005 ## 0.005
wh_env_puddleMaskMin=0 ## 0
wh_env_RainDropsAmountMul=15 ## 15
wh_env_RainDropsSpeedMul=7 ## 7
wh_env_RainLayers=3 ## 3
wh_env_RainWindStrength=10 ## 10
wh_pl_FOWEnabled=1 ## 1
wh_pl_FOWVisibilityRadius=100 ## 100
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







//////////////////////



has dupes
big steppah




## updated 1/13/2025 for KCD v1.9.6 :ramen: 

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
r_DisplayInfo=0#
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
#q_Quality=3# 🔵 change per
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
sys_budget_sysmem=16384# 🔵 def 512 🔴 RAM
sys_budget_videomem=16384# 🔵 def 90 🔴 VRAM
sys_flash_address_space=131072# 🔵 wh def 65536 🔴
sys_flash_check_filemodtime=1# 🔵 wh def 0 🔴
sys_PakStreamCache=0# 🔵 def 0 🔴 RAM
sys_streaming_CPU_worker=7# 🔵 def 5 🔴

# 🔵 def sys
sys_budget_soundCPU=15# 🔵 def 15
sys_flash_allow_reset_mesh_cache=1# 🔵 def 1
sys_flash_curve_tess_error=2# 🔵 wh def 2
sys_flash_edgeaa=1# 🔵 def 1
sys_flash_newstencilclear=1# 🔵 def 1
sys_flash_static_pool_size=0# 🔵 def 0
sys_flash_use_arenas=1# 🔵 def 1
sys_limit_phys_thread_count=0# 🔵 def 0
sys_physics_CPU=0# 🔵def 0
sys_preload=0# 🔵 wh def 0
sys_spec_Quality=4# 🔵 def 4
sys_streaming_CPU=1# 🔵 def 1

# 🔴 edited engine
e_StreamCgfPoolSize=1024# 🔵 wh def 512 🔴 RAM
p_num_threads=7# 🔵 def 2 🔴
r_MultiGPU=0# 🔵 def 1 🔴
r_RenderTargetPoolSize=512# 🔵 def 0 🔴
s_OcclusionMaxDistance=150# 🔵 wh def 500 🔴

# 🔵 def engine
e_HwOcclusionCullingWater=1# 🔵 def 1
e_ParticlesThread=1# 🔵 def 1
e_PreloadMaterials=1# 🔵 def 1
e_ShadowsPoolSize=4096# 🔵 def 4096
e_StreamCgf=1# 🔵 def 1
gpu_Particle_Physics=1# 🔵 def 1
p_cull_distance=100# 🔵 wh def 100
r_MergeRenderChunks=1# 🔵 def 1
r_ShadersDX11=1# 🔵 def 1
r_UseZPass=2# 🔵 wh def 2
r_WaterUpdateThread=5# 🔵 def 5

# 🔴 edited texture
r_TexPreallocateAtlases=1# 🔵 wh def 0 🔴
r_TexturesStreamingMaxRequestedMB=500# 🔵 wh def 20 🔴
r_TexturesStreamingResidencyThrottle=1# 🔵 def 0.5 🔴
r_TexturesStreamingResidencyTime=90# 🔵 wh def 10 🔴
r_TexturesStreampoolDefragmentation=1# 🔵 def 2 🔴
r_TexturesStreamPoolSize=12288# 🔵 wh def 4096 🔴 VRAM

# 🔵 def texture
r_TexAtlasSize=2048# 🔵 def 2048
r_TexMaxAnisotropy=16# 🔵 def 16
r_TexMinAnisotropy=16# 🔵 def 16
r_TexNoAnisoAlphaTest=0# 🔵 def 0
r_TexturesSkipLowerMips=0# 🔵 def 0
r_TexturesStreaming=1# 🔵 def 1
r_TexturesstreamingMinUsableMips=8# 🔵 def 8
r_TexturesStreamingResidencyEnabled=1# 🔵 def 1
r_TexturesStreamingSkipMips=0# 🔵 def 0

# 🔴 edited graphics
#e_VegetationMinSize=0# 🔵 def 0.1 🔴 pickable vegetation
#r_DynTexAtlasSpritesMaxSize=32# 🔵 def 32 🔴 not real
#r_HDRBrightLevel=1# 🔵 def 1 🔴 not real
#r_SilhouettePOM=0# 🔵 def 0 🔴
#s_ObstructionMaxValue=0# 🔵 def 0 🔴 not real
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
e_svoti_LowSpecMode=4# 🔵 wh def 1 🔴
e_svoTI_SSAOAmount=1.5# 🔵 def 1 🔴
e_TerrainDetailMaterialsViewDistZ=120# 🔵 def 100 🔴
e_ViewDistMin=10# 🔵 def 5 🔴
e_ViewDistRatio=150# 🔵 wh def 125 🔴 max slider 150
e_VolumetricFog=0# 🔵 wh def 0 🔴
e_WaterOceanFFT=0# 🔵 wh def 1 🔴
es_MaxPhysDist=100# 🔵 wh def 200 🔴
es_maxphysdistcloth=100# 🔵 wh def 300 🔴
p_num_bodies_large_group=10# 🔵 wh def 100 🔴
r_AntialiasingMode=3# 🔵 wh def 2 🔴
r_AntialiasingTAASharpening=0# 🔵 def 0.2 🔴
r_DrawNearZRange=0.1# 🔵 wh def 0.001 🔴
r_FogShadowsWater=1# 🔵 wh def 1 🔴
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
wh_env_RainDiffuseDarkening=0.33# 🔵 wh def 0.2 🔴
wh_env_RainDropsSpeedBase=3# 🔵 wh def 1.5 🔴

# 🔵 def graphics
ca_AttachmentCullingRation=450# 🔵 wh def 450
e_Brushes=1# 🔵 def 1
e_Clouds=1# 🔵 def 1
e_CoverageBufferEarlyOut=1# 🔵 def 1
e_CoverageBufferReproj=6# 🔵 def 6
e_CullVegActivation=50# 🔵 def 50
e_DecalsAllowGameDecals=1# 🔵 def 1
e_DecalsLifeTimeScale=2# 🔵 def 2
e_DecalsOverlapping=1# 🔵 def 1
e_Dissolve=2# 🔵 def 2
e_DynamicLights=1# 🔵 def 1
e_DynamicLightsMaxEntityLights=16# 🔵 def 16
e_FoliageWindActivationDist=25# 🔵 def 25
e_GI=0# 🔵 wh def 0
e_GIAmount=0.6# 🔵 def 0.6
e_GICache=7# 🔵 def 7
e_GIIterations=6# 🔵 def 6
e_GIMaxDistance=100# 🔵 def 100
e_GINumCascades=1# 🔵 def 1
e_GsmLodsNum=5# 🔵 def 5
e_GsmRange=3# 🔵 def 3
e_LightVolumes=1# 🔵 def 1
e_LodMin=0# 🔵 def 0
e_MaxViewDistSpecLerp=1# 🔵 def 1
e_MergedMeshesPool=16384# 🔵 wh def 16384
e_MergedMeshesUseSpines=1# 🔵 def 1
e_ObjFastRegister=1# 🔵 def 1
e_ObjQuality=4# 🔵 def 4
e_ObjShadowCastSpec=7# 🔵 def 7
e_OcclusionCullingViewDistRatio=1# 🔵 def 1
e_ParticlesCullAgainstOcclusionBuffer=1# 🔵 def 1
e_ParticlesGI=1# 🔵 def 1
e_ParticlesLayeredUpdateMul=5# 🔵 def 5
e_ParticlesMaxScreenFill=160# 🔵 def 160
e_ParticlesMinDrawPixels=1# 🔵 def 1
e_ParticlesObjectCollisions=2# 🔵 def 2
e_ParticlesPoolSize=16384# 🔵 def 16384
e_ParticlesQuality=4# 🔵 def 4
e_ParticlesShadows=1# 🔵 def 1
e_ParticlesSortQuality=0# 🔵 def 0 
e_PhysOceanCell=0.5# 🔵 def 0.5
e_ProcVegetation=0# 🔵 def 0
e_Shadows=1# 🔵 def 1
e_ShadowsBlendCascades=2# 🔵 def 2
e_ShadowsCastViewDistRatio=1.6# 🔵 wh def 1.6
e_ShadowsCastViewDistRatioLights=0.8# 🔵 wh def 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6# 🔵 wh def 0.6
e_ShadowsLodBiasFixed=0# 🔵 def 0 
e_ShadowsOnAlphaBlend=0# 🔵 def 0
e_ShadowsResScale=4# 🔵 def 4
e_ShadowsTessellateCascades=1# 🔵 def 1
e_ShadowsTessellateDLights=0# 🔵 def 0
e_ShadowsUpdateViewDistRatio=100# 🔵 def 100
e_SkyQuality=1# 🔵 def 1
e_SkyUpdateRate=1# 🔵 def 1
e_StatObjBufferRenderTasks=1# 🔵 def 1
e_StatObjMerge=1# 🔵 def 1
e_StreamInstancesMinLoadedNodes=2048# 🔵 def 2048
e_SunAngleClamp=20# 🔵 def 20
e_svoTI_ConeMaxLength=35# 🔵 def 35
e_svoTI_DiffuseConeWidth=6# 🔵 def 6
e_svoTI_DistantSsaoAmount=1# 🔵 def 1
e_svoTI_RsmConeMaxLength=12# 🔵 def 12
e_TerrainAo=0# 🔵 def 0
e_TerrainLodRatio=0.2# 🔵 def 0.2
e_Tessellation=1# 🔵 def 1
e_TessellationMaxDistance=30# 🔵 def 30
e_UberlodDistanceRatio=1.8# 🔵 def 1.8
e_VegetationUseTerrainColor=1# 🔵 def 1
e_VegetationUseTerrainColorDistance=80# 🔵 def 80
e_ViewDistRatioCustom=150# 🔵 wh def 150
e_ViewDistRatioDetail=125# 🔵 wh def 125
e_ViewDistRatioLights=80# 🔵 wh def 80
e_ViewDistRatioVegetation=65# 🔵 wh def 65
e_WaterTessellationAmount=10# 🔵 def 10
e_WaterTessellationAmountX=85# 🔵 def 85
e_WaterTessellationAmountY=85# 🔵 def 85
e_WaterTessellationSwathWidth=10# 🔵 def 10
e_Wind=1# 🔵 def 1
es_DebrisLifetimeScale=1# 🔵 def 1
es_MaxPhysDistInvisible=25# 🔵 wh def 25
g_breakage_particles_limit=160# 🔵 def 160
g_radialBlur=0# 🔵 def 1
g_tree_cut_reuse_dist=0# 🔵 def 0
i_particleeffects=1# 🔵 def 1
mfx_Timeout=0.01# 🔵 def 0.01
p_gravity_z=-9.81# 🔵 def -9.81
p_max_MC_iters=6000# 🔵 def 6000
p_max_object_splashes=3# 🔵 def 3
p_max_substeps=5# 🔵 def 5
p_max_substeps_large_group=5# 🔵 def 5 
p_splash_dist0=7# 🔵 def 7
p_splash_dist1=30# 🔵 def 30
p_splash_force0=10# 🔵 def 10
p_splash_force1=100# 🔵 def 100
p_splash_vel0=4.5# 🔵 def 4.5
p_splash_vel1=10# 🔵 def 10
r_AntialiasingTAAPattern=1# 🔵 def 1
r_Beams=1# 🔵 def 1
r_ChromaticAberration=0# 🔵 def 0
r_ColorGrading=2# 🔵 def 2
r_ColorGradingChartsCache=0# 🔵 def 0
r_CustomResMaxSize=4096# 🔵 def 4096
r_DeferredShadingAreaLights=1# 🔵 def 1
r_DeferredShadingFilterGBuffer=0# 🔵 def 0
r_DeferredShadingTiled=2# 🔵 def 2
r_DeferredShadingTiledHairQuality=1# 🔵 def 1
r_DepthOfField=2# 🔵 def 2
r_DepthOfFieldDilation=0# 🔵 def 0
r_DepthOfFieldDilation=0# 🔵 def 0 
r_DetailDistance=8# 🔵 def 8
r_DrawNearShadows=1# 🔵 def 1
r_DynTexAtlasCloudsMaxSize=32# 🔵 def 32
r_DynTexAtlasDynTexSrcSize=16# 🔵 def 16
r_DynTexAtlasVoxTerrainMaxSize=250# 🔵 def 250
r_DynTexMaxSize=160# 🔵 def 160
r_DynTexMaxSize=160# 🔵 def 160
r_EnvCMResolution=2# 🔵 def 2
r_EnvTexResolution=3# 🔵 def 3
r_EnvTexUpdateInterval=0.05# 🔵 def 0.05
r_FlareHqShafts=1# 🔵 def 1
r_Flares=0# 🔵 wh def 0
r_FlaresTessellationRatio=1# 🔵 def 1
r_FogShadows=0# 🔵 def 0
r_FogShadowsMode=0# 🔵 def 0
r_HDRBloom=1# 🔵 def 1
r_HDRGrainAmount=0# 🔵 def 0
r_HDRRendering=1# 🔵 def 1
r_HDRRendering=1# 🔵 def 1
r_ImposterRatio=1# 🔵 def 1
r_MotionBlurMaxViewDist=32# 🔵 def 32
r_MotionBlurShutterSpeed=125# 🔵 def 125 
r_ParticlesHalfRes=0# 🔵 def 0
r_ParticlesTessellation=1# 🔵 def 1
r_PostProcessHUD3DCache=0# 🔵 def 0
r_RainDropsEffect=1# 🔵 def 1
r_RainOccluderSizeTreshold=10# 🔵 def 10
r_Refraction=1# 🔵 def 1
r_ShadowBlur=3# 🔵 def 3
r_ShadowCastingLightsMaxCount=28# 🔵 wh def 28
r_ShadowJittering=2.5# 🔵 def 2.5
r_ShadowPoolMaxFrames=5# 🔵 def 5
r_ShadowPoolMaxTimeslicedUpdatesPerFrame=120# 🔵 def 120
r_ShadowsCache=0# 🔵 def 0
r_ShadowsCacheResolutions=6324,4214,2810,1872,624# 🔵 def 6324,4214,2810,1872,624
r_ShadowsPCFiltering=1# 🔵 def 1
r_ShadowsScreenSpace=2# 🔵 def 2
r_ShadowsUseClipVolume=1# 🔵 def 1
r_Sharpening=0# 🔵 def 0
r_ssdo=1# 🔵 def 1
r_ssdoHalfRes=2# 🔵 def 2
r_ssdoRadius=0.3# 🔵 def 0.3
r_ssdoRadiusMax=2# 🔵 def 2
r_SunShafts=2# 🔵 def 2
r_TerrainAO_FadeDist=8# 🔵 def 8
r_TessellationTriangleSize=8# 🔵 def 8
r_TranspDepthFixup=1# 🔵 def 1
r_Unlit=0# 🔵 wh def 0
r_UseMaterialLayers=2# 🔵 def 2
r_VolumetricFogSunLightCorrection=1# 🔵 def 1
r_WaterCaustics=0# 🔵 def 0
r_WaterGodRays=0# 🔵 def 0
r_WaterReflectionsQuality=0# 🔵 def 0
r_WaterTessellationHW=1# 🔵 def 1
r_WaterUpdateDistance=0.2# 🔵 def 0.2
r_WaterUpdateFactor=0# 🔵 def 0
r_WaterVolumeCausticsDensity=256# 🔵 def 256
r_WaterVolumeCausticsMaxDist=35# 🔵 def 35
r_WaterVolumeCausticsRes=1024# 🔵 def 1024
r_WaterVolumeCausticsSnapFactor=1# 🔵 def 1
v_vehicle_quality=4# 🔵 def 4
wh_cc_CharacterDetailReduction=0# 🔵 wh def 0
wh_cc_LodForAttachmentStreamOut=6# 🔵 wh def 6
wh_cc_LodForItemStreamOutBase=20# 🔵 wh def 20
wh_env_DirtCreationSpeed=0.05# 🔵 wh def 0.05
wh_env_DirtDryupSpeed=0.05# 🔵 wh def 0.05
wh_env_PuddleCreationDelay=1000# 🔵 wh def 1000
wh_env_PuddleCreationSpeed=0.005# 🔵 wh def 0.005
wh_env_PuddleDryupDelay=0# 🔵 wh def 0 
wh_env_PuddleDryupSpeed=0.005# 🔵 wh def 0.005
wh_env_puddleMaskMin=0# 🔵 wh def 0
wh_env_RainDropsAmountMul=15# 🔵 wh def 15
wh_env_RainDropsSpeedMul=7# 🔵 wh def 7
wh_env_RainLayers=3# 🔵 wh def 3
wh_env_RainWindStrength=10# 🔵 wh def 10
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



















//////////////////////////////////////
///////////////////////////
///////////////

goood


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














////////////////
///////
////////////
////////////
/////////////////



## updated 1/12/2025 for KCD v1.9.6 :ramen:

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
Bind f3 exec TEST1.cfg#
Bind f4 exec TEST2.cfg#

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
sys_budget_sysmem=1024# 🔵 def 512 🔴 RAM
sys_budget_videomem=4096# 🔵 def 90 🔴 VRAM
sys_flash_check_filemodtime=1# 🔵 wh def 0 🔴
sys_PakStreamCache=1# 🔵 def 0 🔴 RAM

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
sys_streaming_CPU_worker=5# 🔵 def 5

# 🔴 edited engine
e_ParticlesThread=2# 🔵 def 1 🔴
e_ShadowsPoolSize=4096# 🔵 def 4096 🔴 VRAM
e_StreamCgfPoolSize=1024# 🔵 wh def 512 🔴 RAM
p_num_threads=6# 🔵 def 2 🔴
r_MultiGPU=0# 🔵 def 1 🔴
r_RenderTargetPoolSize=512# 🔵 def 0 🔴
r_ShadersAsyncMaxThreads=4# 🔵 def 1 🔴

# 🔵 def engine
e_HwOcclusionCullingWater=1# 🔵 def 1
gpu_Particle_Physics=1# 🔵 def 1
p_cull_distance=100# 🔵 wh def 100
r_MergeRenderChunks=1# 🔵 def 1
r_ShadersDX11=1# 🔵 def 1
r_WaterUpdateThread=5# 🔵 def 5

# 🔴 edited texture
r_TexPreallocateAtlases=1# 🔵 wh def 0 🔴
r_TexturesStreamingMaxRequestedMB=512# 🔵 wh def 20 🔴
r_TexturesStreamingResidencyThrottle=1# 🔵 def 0.5 🔴
r_TexturesStreamingResidencyTime=120# 🔵 wh def 10 🔴
r_TexturesStreamPoolSize=8192# 🔵 wh def 4096 🔴 VRAM

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
e_ParticlesPoolSize=16384# 🔵 def 16384 🔴
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
wh_cc_LodForItemStreamOutBase=15# 🔵 def 20 🔴
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
wh_cc_LodForAttachmentStreamOut=4# 🔵 def 6
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
































//////////
////////////////
//////////////
///////////////////////////////
/////////////////


after good clean backup wip

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
Bind f3 exec TEST1.cfg#
Bind f4 exec TEST2.cfg#

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
sys_budget_sysmem=1024# 🔵 def 512 🔴 RAM
sys_budget_videomem=4096# 🔵 def 90 🔴 VRAM
sys_flash_check_filemodtime=1# 🔵 wh def 0 🔴
sys_PakStreamCache=1# 🔵 def 0 🔴 RAM

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
sys_streaming_CPU_worker=5# 🔵 def 5

# 🔴 edited engine
e_ParticlesThread=2# 🔵 def 1 🔴
e_ShadowsPoolSize=4096# 🔵 def 4096 🔴 VRAM
e_StreamCgfPoolSize=1024# 🔵 wh def 512 🔴 RAM
p_num_threads=6# 🔵 def 2 🔴
r_MultiGPU=0# 🔵 def 1 🔴
r_RenderTargetPoolSize=512# 🔵 def 0 🔴
r_ShadersAsyncMaxThreads=4# 🔵 def 1 🔴

# 🔵 def engine
e_HwOcclusionCullingWater=1# 🔵 def 1
gpu_Particle_Physics=1# 🔵 def 1
p_cull_distance=100# 🔵 wh def 100
r_MergeRenderChunks=1# 🔵 def 1
r_ShadersDX11=1# 🔵 def 1
r_WaterUpdateThread=5# 🔵 def 5

# 🔴 edited texture
r_TexPreallocateAtlases=1# 🔵 wh def 0 🔴
r_TexturesStreamingMaxRequestedMB=512# 🔵 wh def 20 🔴
r_TexturesStreamingResidencyThrottle=1# 🔵 def 0.5 🔴
r_TexturesStreamingResidencyTime=120# 🔵 wh def 10 🔴
r_TexturesStreamPoolSize=8192# 🔵 wh def 4096 🔴 VRAM

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
e_ParticlesPoolSize=16384# 🔵 def 16384 🔴
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
WH_AI_LOD_DistanceMax=90# 🔴 90,110,130
WH_AI_LOD_DistanceMin=60# 🔴 60,80,100
wh_cc_LodForItemStreamOutBase=15# 🔵 def 20 🔴
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
wh_cc_LodForAttachmentStreamOut=4# 🔵 def 6
wh_env_RainDropsAmountMul=15# 🔵 wh def 15
wh_env_RainLayers=3# 🔵 wh def 3
wh_pl_FOWEnabled=1# 🔵 wh def 1
wh_pl_FOWVisibilityRadius=100# 🔵 wh def 100



////////////
////////////
//////////////
///////////////////////



🟡 good no stutter could have better ssdo/lods/fps


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
q_ShaderWater=3#

#
Bind 0 g_showHUD 0#
Bind 9 g_showHUD 1#
Bind f1 sys_MaxFPS 158#
Bind f2 sys_MaxFPS 60#
Bind f3 exec TEST1.cfg#
Bind f4 exec TEST2.cfg#

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

#
e_ParticlesThread=2# 🔵 def 1 🔴
e_ShadowsPoolSize=4096# 🔵 def 4096 🔴 VRAM
e_StreamCgfPoolSize=1024# 🔵 wh def 512 🔴 RAM
gpu_Particle_Physics=1#
r_MultiGPU=0# 🔵 def 1
r_RenderTargetPoolSize=512# 🔵 def 0 🔴
r_ShadersAsyncMaxThreads=4# 🔵 def 1 🔴
r_TexturesStreaming=1# 🔵 def 1
r_TexturesStreamingMaxRequestedMB=512# 🔵 wh def 20 🔴
r_TexturesStreamingResidencyEnabled=1# 🔵 def 1
r_TexturesStreamingResidencyThrottle=1# 🔵 def 0.5 🔴
r_TexturesStreamPoolSize=8192# 🔵 wh def 4096 🔴 VRAM
r_WaterUpdateThread=0# 🔵 def 5 🔴
sys_budget_sysmem=1024# 🔵 def 512 🔴 RAM
sys_budget_videomem=4096# 🔵 def 90 🔴 VRAM
sys_limit_phys_thread_count=0# 🔵 def 1 🔴
sys_PakStreamCache=1# 🔵 def 0 🔴
sys_physics_CPU=2# 🔵 def 1 🔴
sys_streaming_CPU=2# 🔵 def 1 🔴
sys_streaming_CPU_worker=6# 🔵 def 5 🔴

#
ca_AttachmentCullingRation=425# 🔵 wh def 425
e_Clouds=1# 🔵 def 1
e_Fog=1# 🔵 def 1 🔴
e_GI=0#
e_GIAmount=0.6#
e_GICache=7# 🔵 def 7
e_GIIterations=6# 🔵 def 6
e_GIMaxDistance=100#
e_GINumCascades=1#
e_LodFaceAreaTargetSize=0.0006# 🔵 def 0.001
e_LodRatio=70# 🔵 max slider 70 🔵 wh def 60
e_MergedMeshesInstanceDist=32# 🔵 wh def 16
e_MergedMeshesLodRatio=16# 🔵 wh def 8
e_MergedMeshesPool=16384# 🔵 wh def 16384
e_MergedMeshesViewDistRatio=100# 🔵 max slider 100 🔵 wh 85
e_ParticlesGI=1# 🔵 def 1
e_ParticlesMotionBlur=0#
e_ParticlesObjectCollisions=2# 🔵 def 2
e_ParticlesPoolSize=16384# 🔵 def 16384 🔴
e_ParticlesQuality=4# 🔵 def 4
e_ParticlesShadows=1# 🔵 def 1
e_PhysProxyTriLimit=1000# 🔵 wh def 10000 🔴
e_ShadowsCastViewDistRatio=1.6# 🔵 wh def 1.6
e_ShadowsCastViewDistRatioLights=0.8# 🔵 wh def 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6# 🔵 wh def 0.6
e_ShadowsMaxTexRes=1872#
e_SkyQuality=1#
e_SkyUpdateRate=1#
e_svoTI_SSAOAmount=1.5# 🔵 def 1
e_TerrainAo=0#
e_Tessellation=1# 🔵 def 1
e_TessellationMaxDistance=30# 🔵 def 30
e_ViewDistRatio=150# 🔵 max slider 150 🔵 wh 125
e_VolumetricFog=0# 🔵 def 0 🔴
e_WaterOceanFFT=0# 🔵 def 1
es_MaxPhysDist=100# 🔵 wh def 200 🔴
es_maxphysdistcloth=100# 🔵 wh def 300 🔴
es_MaxPhysDistInvisible=25# 🔵 wh def 25
p_num_bodies_large_group=10# 🔵 wh def 100 🔴
r_AntialiasingMode=3#
r_AntialiasingTAAPattern=1#
r_AntialiasingTAASharpening=0# 🔵 def 0.2
r_ChromaticAberration=0#
r_DepthOfField=2#
r_FogShadows=0# 🔵 def 0
r_FogShadowsMode=0# 🔵 def 0
r_FogShadowsWater=0# 🔵 def 1
r_HDRBloom=1#
r_HDRGrainAmount=0#
r_HDRVignetting=0# 🔵 def 1
r_MotionBlur=0#
r_MotionBlurQuality=0#
r_ParticlesHalfRes=0# 🔵 def 0
r_ParticlesTessellation=1# 🔵 def 1
r_RainAmount=2# 🔵 def 1
r_RainDistMultiplier=2.5# 🔵 wh def 2
r_RainMaxViewDist_Deferred=170# 🔵 def 150
r_Refraction=1# 🔵 def 1
r_SilhouettePOM=0#
r_ssdoAmountAmbient=2# 🔵 def 1
r_ssdoAmountDirect=4# 🔵 def 1.5
r_ssdoAmountReflection=5# 🔵 def 4
r_ssdoRadius=0.3# 🔵 def 0.3
r_ssdoRadiusMin=0.02# 🔵 def 0.1
r_SSReflections=0#
r_SSReflHalfRes=1#
r_TerrainAO=0# 🔵 def 7
r_TerrainAO_FadeDist=8#
r_TessellationTriangleSize=8# 🔵 def 8
r_UseMaterialLayers=2# 🔵 def 2
r_VolumetricFogSunLightCorrection=1# 🔵 def 1
r_VolumetricFogTexDepth=4# 🔵 def 32
r_VolumetricFogTexScale=20# 🔵 def 1 🔵 wh def 10
r_WaterCaustics=0#
r_WaterGodRays=0#
r_WaterReflectionsQuality=0#
r_WaterTessellationHW=1#
r_WaterVolumeCaustics=0# 🔵 def 1
sys_spec_Quality=4#
WH_AI_LOD_DistanceMax=90# 🔴 wh 90,110,130
WH_AI_LOD_DistanceMin=60# 🔴 wh 60,80,100
wh_cc_LodForAttachmentStreamOut=4# 🔵 def 6
wh_cc_LodForItemStreamOutBase=15# 🔵 def 20
wh_env_RainDiffuseDarkening=0.25# 🔵 wh def 0.2
wh_env_RainDropsAmountMul=15# 🔵 wh def 15
wh_env_RainDropsSpeedBase=3# 🔵 wh def 1.5
wh_env_RainLayers=3# 🔵 wh def 3
wh_pl_FOWEnabled=1# 🔵 wh def 1
wh_pl_FOWVisibilityRadius=100# 🔵 wh def 100







///////
/////////////
//////////////



## updated 1/11/2025 for KCD v1.9.6 :ramen:

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
; Create user.cfg in KingdomComeDeliverance folder and copy paste
; delete cache folder %userprofile%/Saved Games/kingdomcome/shaders
; Add launch commands: +exec user.cfg -devmode
; and restart after getting to main menu

;
con_restricted=0;
sys_MaxFPS=158; 🔵 def 0
sys_spec=0; 🔵 sets custom spec

;
sys_spec_GameEffects=7;
sys_spec_Light=7;
sys_spec_ObjectDetail=7;
sys_spec_Particles=7;
sys_spec_Physics=7;
sys_spec_PostProcessing=7;
sys_spec_Shading=7;
sys_spec_Shadows=7;
sys_spec_Sound=7;
sys_spec_Texture=7;
sys_spec_TextureResolution=7; 🔵 HD textures on
sys_spec_Vegetation=7;
sys_spec_VolumetricEffects=7;
sys_spec_Water=7;

;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;

;
Bind 0 g_showHUD 0;
Bind 9 g_showHUD 1;
Bind f1 sys_MaxFPS 158;
Bind f2 sys_MaxFPS 60;
Bind f3 exec TEST1.cfg;
Bind f4 exec TEST2.cfg;

;
cl_fov=68; 🔵 def 60
cl_sensitivity=10;
g_skipIntro=1; 🔵 def 0
i_mouse_accel=0;
i_mouse_smooth=0;
pl_movement.power_sprint_targetFOV=68; 🔵 def 55
r_DrawNearFOV=68; 🔵 def 60
r_Vsync=0;

;
wh_cs_PlayerLockDisabled=0; 🔵 def 0
wh_horse_CameraCentering=0; 🔵 def 0.2
wh_pl_showfirecursor=1; 🔵 def 0

;
e_ParticlesThread=2; 🔵 def 1 🔴
e_ShadowsPoolSize=4096; 🔵 def 4096 🔴 VRAM
e_StreamCgfPoolSize=1024; 🔵 wh def 512 🔴 RAM
gpu_Particle_Physics=1;
r_MultiGPU=0; 🔵 def 1
r_RenderTargetPoolSize=512; 🔵 def 0 🔴
r_ShadersAsyncMaxThreads=4; 🔵 def 1 🔴
r_TexturesStreaming=1; 🔵 def 1
r_TexturesStreamingMaxRequestedMB=512; 🔵 wh def 20 🔴
r_TexturesStreamingResidencyEnabled=1; 🔵 def 1
r_TexturesStreamingResidencyThrottle=1; 🔵 def 0.5 🔴
r_TexturesStreamPoolSize=8192; 🔵 wh def 4096 🔴 VRAM
r_WaterUpdateThread=0; 🔵 def 5 🔴
sys_budget_sysmem=1024; 🔵 def 512 🔴 RAM
sys_budget_videomem=4096; 🔵 def 90 🔴 VRAM
sys_limit_phys_thread_count=0; 🔵 def 1 🔴
sys_PakStreamCache=1; 🔵 def 0 🔴
sys_physics_CPU=2; 🔵 def 1 🔴
sys_streaming_CPU=2; 🔵 def 1 🔴
sys_streaming_CPU_worker=6; 🔵 def 5 🔴

;
ca_AttachmentCullingRation=425; 🔵 wh def 425
e_Clouds=1; 🔵 def 1
e_Fog=1; 🔵 def 1 🔴
e_GI=0;
e_GIAmount=0.6;
e_GICache=7; 🔵 def 7 min 0
e_GIIterations=6; 🔵 def 6 max 32
e_GIMaxDistance=100;
e_GINumCascades=1;
e_LodFaceAreaTargetSize=0.0006; 🔵 def 0.001
e_LodRatio=70; 🔵 max slider 70 🔵 wh def 60
e_MergedMeshesInstanceDist=32; 🔵 wh def 16
e_MergedMeshesLodRatio=16; 🔵 wh def 8
e_MergedMeshesPool=16384; 🔵 wh def 16384
e_MergedMeshesViewDistRatio=100; 🔵 max slider 100 🔵 wh 85
e_ParticlesGI=1; 🔵 def 1
e_ParticlesMotionBlur=0;
e_ParticlesObjectCollisions=2; 🔵 def 2
e_ParticlesPoolSize=16384; 🔵 def 16384 🔴
e_ParticlesQuality=4; 🔵 def 4
e_ParticlesShadows=1; 🔵 def 1
e_PhysProxyTriLimit=1000; 🔵 wh def 10000 🔴
e_ShadowsCastViewDistRatio=1.6; 🔵 wh def 1.6
e_ShadowsCastViewDistRatioLights=0.8; 🔵 wh def 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6; 🔵 wh def 0.6
e_ShadowsMaxTexRes=1872;
e_SkyQuality=1;
e_SkyUpdateRate=1;
e_svoTI_SSAOAmount=1.5; 🔵 def 1
e_TerrainAo=0;
e_Tessellation=1; 🔵 def 1
e_TessellationMaxDistance=30; 🔵 def 30
e_ViewDistRatio=150; 🔵 max slider 150 🔵 wh 125
e_VolumetricFog=0; 🔵 def 0 🔴
e_WaterOceanFFT=0; 🔵 def 1
es_MaxPhysDist=100; 🔵 wh def 200 🔴
es_maxphysdistcloth=100; 🔵 wh def 300 🔴
es_MaxPhysDistInvisible=25; 🔵 wh def 25
p_num_bodies_large_group=10; 🔵 wh def 100 🔴
r_AntialiasingMode=3;
r_AntialiasingTAAPattern=1;
r_AntialiasingTAASharpening=0; 🔵 def 0.2
r_ChromaticAberration=0;
r_DepthOfField=2;
r_FogShadows=0; 🔵 def 0
r_FogShadowsMode=0; 🔵 def 0
r_FogShadowsWater=0; 🔵 def 1
r_HDRBloom=1;
r_HDRGrainAmount=0;
r_HDRVignetting=0; 🔵 def 1
r_MotionBlur=0;
r_MotionBlurQuality=0;
r_ParticlesHalfRes=0; 🔵 def 0
r_ParticlesTessellation=1; 🔵 def 1
r_RainAmount=2; 🔵 def 1
r_RainDistMultiplier=2.5; 🔵 wh def 2
r_RainMaxViewDist_Deferred=170; 🔵 def 150
r_Refraction=1; 🔵 def 1
r_SilhouettePOM=0;
r_ssdoAmountAmbient=2; 🔵 def 1
r_ssdoAmountDirect=4; 🔵 def 1.5
r_ssdoAmountReflection=5; 🔵 def 4
r_ssdoRadius=0.3; 🔵 def 0.3
r_ssdoRadiusMin=0.02; 🔵 def 0.1
r_SSReflections=0;
r_SSReflHalfRes=1;
r_TerrainAO=0; 🔵 def 7
r_TerrainAO_FadeDist=8;
r_TessellationTriangleSize=8; 🔵 def 8
r_UseMaterialLayers=2; 🔵 def 2
r_VolumetricFogSunLightCorrection=1; 🔵 def 1
r_VolumetricFogTexDepth=4; 🔵 def 32
r_VolumetricFogTexScale=20; 🔵 def 1 🔵 wh def 10
r_WaterCaustics=0;
r_WaterGodRays=0;
r_WaterReflectionsQuality=0;
r_WaterTessellationHW=1;
r_WaterVolumeCaustics=0; 🔵 def 1
sys_spec_Quality=4;
WH_AI_LOD_DistanceMax=90; 🔴 wh 90,110,130
WH_AI_LOD_DistanceMin=60; 🔴 wh 60,80,100
wh_cc_LodForAttachmentStreamOut=4; 🔵 def 6
wh_cc_LodForItemStreamOutBase=15; 🔵 def 20
wh_env_RainDiffuseDarkening=0.25; 🔵 wh def 0.2
wh_env_RainDropsAmountMul=15; 🔵 wh def 15
wh_env_RainDropsSpeedBase=3; 🔵 wh def 1.5
wh_env_RainLayers=3; 🔵 wh def 3
wh_pl_FOWEnabled=1; 🔵 wh def 1
wh_pl_FOWVisibilityRadius=100; 🔵 wh def 100
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














//////////
/////////////////
///////////////////////////


fix dupe and r_ssdoRadius=



## updated 1/11/2025 :ramen:

### my config and stuff for kcd hf updated for wh_sys_version = "1.9.6"

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
; Add launch commands: +exec user.cfg -devmode

; and restart after getting to main menu

; def is usually max settings

;
con_restricted=0;
sys_MaxFPS=158; 🔵 def 0
sys_spec=0; 🔵 sets custom spec

;
sys_spec_GameEffects=7;
sys_spec_Light=7;
sys_spec_ObjectDetail=7;
sys_spec_Particles=7;
sys_spec_Physics=7;
sys_spec_PostProcessing=7;
sys_spec_Shading=7;
sys_spec_Shadows=7;
sys_spec_Sound=7;
sys_spec_Texture=7;
sys_spec_TextureResolution=7; 🔵 HD textures on
sys_spec_Vegetation=7;
sys_spec_VolumetricEffects=7;
sys_spec_Water=7;

;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;

;
Bind 0 g_showHUD 0;
Bind 9 g_showHUD 1;
Bind f1 sys_MaxFPS 158;
Bind f2 sys_MaxFPS 60;
Bind f3 exec TEST1.cfg;
Bind f4 exec TEST2.cfg;

;
cl_fov=68; 🔵 def 60
cl_sensitivity=10;
g_skipIntro=1; 🔵 def 0
i_mouse_accel=0;
i_mouse_smooth=0;
pl_movement.power_sprint_targetFOV=68; 🔵 def 55
r_DrawNearFOV=68; 🔵 def 60
r_Vsync=0;

;
wh_cs_PlayerLockDisabled=0; 🔵 def 0
wh_horse_CameraCentering=0; 🔵 def 0.2
wh_pl_showfirecursor=1; 🔵 def 0

; doubled test
e_StreamCgfPoolSize=1024;
r_TexturesStreamPoolSize=8192;

;
ca_AttachmentCullingRation=425; 🔵 wh def 425
e_Clouds=1; 🔵 def 1
e_Fog=1; 🔵 def 1 🔵 test yourself
e_GI=0;
e_GIAmount=0.6;
e_GICache=7; 🔵 def 7 min 0
e_GIIterations=6; 🔵 def 6 max 32
e_GIMaxDistance=100;
e_GINumCascades=1;
e_LodFaceAreaTargetSize=0.0006; 🔵 def 0.001
e_LodRatio=70; 🔵 max slider 70 🔵 wh 60
e_MergedMeshesInstanceDist=32; 🔵 wh 16
e_MergedMeshesLodRatio=16; 🔵 wh 8
e_MergedMeshesPool=16384; 🔵 wh 16384
e_MergedMeshesViewDistRatio=100; 🔵 max slider 100 🔵 wh 85
e_ParticlesMotionBlur=0;
e_PhysProxyTriLimit=1000; 🔵 wh def 10000 🔴
e_ShadowsCastViewDistRatio=1.6; 🔵 wh def 1.6
e_ShadowsCastViewDistRatioLights=0.8; 🔵 wh def 0.8
e_ShadowsCastViewDistRatioMulInvis=0.6; 🔵 wh def 0.6
e_ShadowsMaxTexRes=1872; 🔵 2048 causes flicker indoors
e_SkyQuality=1;
e_SkyUpdateRate=1;
e_svoTI_SSAOAmount=1.5; 🔵 def 1
e_TerrainAo=0;
e_ViewDistRatio=150; 🔵 max slider 150 🔵 wh 125
e_ViewDistRatioCustom=150;
e_ViewDistRatioDetail=150;
e_ViewDistRatioLights=150;
e_VolumetricFog=0; 🔵 test yourself
e_WaterOceanFFT=0; 🔵 def 1
es_MaxPhysDist=200; 🔵 wh def 100
es_MaxPhysDistInvisible=35; 🔵 wh def 25
gpu_Particle_Physics=1;
p_num_bodies_large_group=10; 🔵 wh def 100 🔴
r_AntialiasingMode=3;
r_AntialiasingTAAPattern=1;
r_AntialiasingTAASharpening=0; 🔵 def 0.2
r_ChromaticAberration=0;
r_DepthOfField=2;
r_FogShadows=0; 🔵 def 0
r_FogShadowsMode=0; 🔵 def 0
r_FogShadowsWater=0; 🔵 def 1
r_HDRBloom=1;
r_HDRVignetting=0;
r_MotionBlur=0;
r_MotionBlurQuality=0;
r_RainAmount=2; 🔵 def 1
r_RainDistMultiplier=2.5; 🔵 wh def 2
r_RainMaxViewDist_Deferred=170; 🔵 def 150
r_SilhouettePOM=0;
r_ssdoAmountAmbient=2; 🔵 def 1
r_ssdoAmountDirect=4; 🔵 def 1.5
r_ssdoAmountReflection=5; 🔵 def 4
r_ssdoRadius=0.3; 🔵 def 0.3
r_ssdoRadiusMin=0.02; 🔵 def 0.1
r_SSReflections=0;
r_SSReflHalfRes=1;
r_VolumetricFogSunLightCorrection=1; 🔵 def 1
r_VolumetricFogTexDepth=4; 🔵 default 32
r_VolumetricFogTexScale=20; 🔵 def 1 🔵 wh def 10
r_WaterCaustics=0;
r_WaterGodRays=0;
r_WaterReflectionsQuality=0;
r_WaterTessellationHW=1;
r_WaterVolumeCaustics=0; 🔵 def 1
sys_spec_Quality=4;
WH_AI_LOD_DistanceMax=90; 🔵 wh def 130 🔵 90,110,130
WH_AI_LOD_DistanceMin=60; 🔵 wh def 100 🔵 60,80,100
wh_cc_LodForAttachmentStreamOut=4; 🔵 def 6
wh_cc_LodForItemStreamOutBase=15; 🔵 def 20
wh_env_RainDiffuseDarkening=0.25; 🔵 wh def 0.2
wh_env_RainDropsAmountMul=25; 🔵 wh def 15
wh_env_RainDropsSpeedBase=3; 🔵 wh def 1.5
wh_env_RainLayers=3; 🔵 wh def 3
wh_pl_FOWEnabled=1; 🔵 wh def 1
wh_pl_FOWVisibilityRadius=100; 🔵 wh def 100
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






















/////////
///////////////
///////////////





## updated 1/10/2025 :ramen:

### my config and stuff for kcd hf updated for wh_sys_version = "1.9.6"

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
;Add launch commands: +exec user.cfg -devmode
;and restart after getting to main menu

;
con_restricted=0;

;
sys_MaxFPS=158; 🔵 def 0 🔴

;
sys_spec=0; 🔵 sets custom spec

;
sys_spec_GameEffects=7;
sys_spec_Light=7;
sys_spec_ObjectDetail=7;
sys_spec_Particles=7;
sys_spec_Physics=7;
sys_spec_PostProcessing=7;
sys_spec_Shading=7;
sys_spec_Shadows=7;
sys_spec_Sound=7;
sys_spec_Texture=7;
sys_spec_TextureResolution=7; 🔵 HD textures on
sys_spec_Vegetation=7;
sys_spec_VolumetricEffects=7;
sys_spec_Water=7;

;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;

;
Bind 0 g_showHUD 0;
Bind 9 g_showHUD 1;
Bind f1 sys_MaxFPS 158;
Bind f2 sys_MaxFPS 60;
Bind f3 exec TEST1.cfg;
Bind f4 exec TEST2.cfg;

;
cl_fov=68; 🔵 def 60 🔴
cl_sensitivity=10;
g_skipIntro=1; 🔵 def 0 🔴
i_mouse_accel=0;
i_mouse_smooth=0;
pl_movement.power_sprint_targetFOV=68; 🔵 def 55 🔴
r_DrawNearFOV=68; 🔵 def 60 🔴
r_Vsync=0;
wh_cs_PlayerLockDisabled=0; 🔵 def 0
wh_horse_CameraCentering=0; 🔵 def 0.2 🔴
wh_pl_showfirecursor=1; 🔵 def 0 🔴

;
e_GI=1;
e_ObjQuality=4;
e_ObjShadowCastSpec=7;
e_ParticlesMotionBlur=0;
e_ShadowsMaxTexRes=1872; 🔵 2048 causes flicker indoors
e_SkyQuality=1;
e_TerrainAo=1;
e_ViewDistRatioVegetation=125;
e_VolumetricFog=1; 🔵 toggle this to your liking
gpu_Particle_Physics=1;
r_AntialiasingMode=3;
r_AntialiasingTAAPattern=1;
r_AntialiasingTAASharpening=0.2;
r_ChromaticAberration=0;
r_DepthOfField=2;
r_HDRBloom=1;
r_HDRVignetting=1;
r_MotionBlur=0;
r_MotionBlurQuality=0;
r_SilhouettePOM=0;
r_SSReflections=1;
r_SSReflHalfRes=1;
r_TexturesStreamPoolSize=6144;
r_VolumetricFogSunLightCorrection=1;
r_WaterCaustics=0;
r_WaterGodRays=0;
r_WaterReflectionsQuality=0;
sys_spec_Quality=4;
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
















////////////////////////
//////////////////////////////////////



## updated 1/9/2025 :ramen:

### my config and stuff for kcd hf updated for wh_sys_version = "1.9.6"

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
;Add launch commands: +exec user.cfg -devmode
;and restart after getting to main menu

;
con_restricted=0;

;
sys_MaxFPS=158; 🔵 def 0 🔴

;
sys_spec=0; 🔵 sets custom spec

;
sys_spec_GameEffects=7;
sys_spec_Light=7;
sys_spec_ObjectDetail=7;
sys_spec_Particles=7;
sys_spec_Physics=7;
sys_spec_PostProcessing=7;
sys_spec_Shading=7;
sys_spec_Shadows=7;
sys_spec_Sound=7;
sys_spec_Texture=7;
sys_spec_TextureResolution=7; 🔵 HD textures on
sys_spec_Vegetation=7;
sys_spec_VolumetricEffects=7;
sys_spec_Water=7;

;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;

;
Bind 0 g_showHUD 0;
Bind 9 g_showHUD 1;
Bind f1 sys_MaxFPS 158;
Bind f2 sys_MaxFPS 60;
Bind f3 exec TEST1.cfg;
Bind f4 exec TEST2.cfg;

;
cl_fov=68; 🔵 def 60 🔴
cl_sensitivity=10;
g_skipIntro=1; 🔵 def 0 🔴
i_mouse_accel=0;
i_mouse_smooth=0;
pl_movement.power_sprint_targetFOV=68; 🔵 def 55 🔴
r_DrawNearFOV=68; 🔵 def 60 🔴
r_Vsync=0;
wh_cs_PlayerLockDisabled=0; 🔵 def 0
wh_horse_CameraCentering=0; 🔵 def 0.2 🔴
wh_pl_showfirecursor=1; 🔵 def 0 🔴

;
e_GI=1;
e_ObjQuality=4;
e_ObjShadowCastSpec=7;
e_ParticlesMotionBlur=0;
e_ShadowsMaxTexRes=2048;
e_SkyQuality=1;
e_TerrainAo=1;
e_ViewDistRatioVegetation=125;
e_VolumetricFog=1;
gpu_Particle_Physics=1;
r_AntialiasingMode=3;
r_AntialiasingTAAPattern=1;
r_AntialiasingTAASharpening=0.2;
r_ChromaticAberration=0;
r_HDRBloom=1;
r_HDRVignetting=1;
r_MotionBlur=0;
r_MotionBlurQuality=0;
r_SilhouettePOM=0;
r_SSReflections=1;
r_SSReflHalfRes=1;
r_TexturesStreamPoolSize=6144;
r_VolumetricFogSunLightCorrection=1;
r_WaterCaustics=0;
r_WaterGodRays=0;
r_WaterReflectionsQuality=0;
sys_spec_Quality=4;
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











//////////////////
//////////////
/////////////
//////////////
///////////////////////////





#### updated 1/29/2024 :ramen:

###### my config and stuff for kcd hf

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
;Add launch commands: +exec user.cfg -devmode
con_restricted=0;
sys_MaxFPS=152;------def 0------changed to 152*
sys_spec=0;------sets custom spec
sys_spec_GameEffects=3;
sys_spec_Light=3;
sys_spec_ObjectDetail=3;
sys_spec_Particles=3;
sys_spec_Physics=3;
sys_spec_PostProcessing=3;
sys_spec_Shading=3;
sys_spec_Shadows=3;
sys_spec_Sound=3;
sys_spec_Texture=3;
sys_spec_TextureResolution=7;------HD textures on
sys_spec_Vegetation=3;
sys_spec_VolumetricEffects=3;
sys_spec_Water=3;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;
Bind 0 "exec user.cfg";
Bind 8 "g_showHUD 0";
Bind 9 "g_showHUD 1";
Bind f1 "sys_MaxFPS 111";
Bind f2 "sys_MaxFPS 152";
Bind f3 "exec TEST1.cfg";
Bind f4 "exec TEST2.cfg";
cl_fov=68;------def 60------changed to 68*
pl_movement.power_sprint_targetFOV=68;------def 55------changed to 68*
r_DrawNearFOV=68;------def 60------changed to 68*
cl_sensitivity=10;
i_mouse_accel=0;
i_mouse_smooth=0;
g_skipIntro=1;------def 0------changed to 1*
r_Vsync=0;
wh_cs_PlayerLockDisabled=0;------def 0
wh_horse_CameraCentering=0;------def 0.2------changed to 0*
wh_pl_showfirecursor=1;------def 0------changed to 1*
ca_AttachmentCullingRation=300;------def 360------changed to 300*
e_CoverageBufferTerrainLodShift=0;------def 2------changed to 0*
e_CullVegActivation=30;------def 50------changed to 30*
e_DecalsLifeTimeScale=1;------def 2------changed to 1*
e_DecalsRange=10;------def 20------changed to 10*
e_GsmRangeStep=2.5;------def 3------changed to 2.5*
e_LodFaceAreaTargetSize=0.0006;------def 0.001------changed to 0.0006*
e_LodRatio=25;------def 25
e_MergedMeshesInstanceDist=5;------def 8------changed to 5*
e_MergedMeshesLodRatio=1;------def 5------changed to 1*
e_MergedMeshesPool=16384;------def 8192 change to 16384
e_MergedMeshesViewDistRatio=85;------def 70------changed to 85*
e_ObjShadowCastSpec=2;------def 3------changed to 2*
e_PhysProxyTriLimit=5000;------def 10000------changed to 5000*
e_ShadowsBlendCascades=0;------def 2------changed to 0*
e_ShadowsCacheUpdate=1;------def 2------changed to 1*
e_ShadowsCastViewDistRatio=0.8;------def 1------changed to 0.8*
e_ShadowsCastViewDistRatioMulInvis=0.2;------def 0.4------changed to 0.2*
e_ShadowsMaxTexRes=1024;------def 1024
e_ShadowsUpdateViewDistRatio=80;------def 100------changed to 80*
e_SkyQuality=2;------def 2------1 for PERFORMANCE
e_StreamCgfPoolSize=1024;------def 512------changed to 1024*
e_svoTI_SSAOAmount=1.5;------def 1------changed to 1.5*
e_TerrainDetailMaterialsViewDistZ=100;------def 80------changed to 100*
e_TerrainLodRatio=0.5;------def 0.3------changed to 0.5*
e_TerrainOcclusionCullingMaxDist=150;------def 200------changed to 150*
e_UberlodDistanceRatio=1.9;------def 1.8------changed to 1.9*
e_ViewDistRatioVegetation=65;------def 55------changed to 65*
e_VolumetricFog=0;------def 0
es_DebrisLifetimeScale=0.6;------def 1------changed to 0.6*
es_maxphysdistcloth=100;------def 300------changed to 100*
g_breakage_particles_limit=80;------def 160------changed to 80*
gpu_Particle_Physics=0;------def 0
p_max_MC_iters=4000;------def 6000------changed to 4000*
r_AntialiasingMode=3;------def 1------changed to 3*
r_AntialiasingTAAPattern=3;------def 1------changed to 3*
r_AntialiasingTAASharpening=0;------def 0.2------changed to 0*
r_BatchType=1;------def 1
r_DeferredShadingAreaLights=1;------def 1
r_DepthBits=32;------def 24------changed to 32*
r_FogShadowsWater=1;------def 0------changed to 1*
r_HDRBloom=0;------def 1------changed to 0*
r_HDRVignetting=0;------def 1------changed to 0*
r_MotionBlur=0;
r_RainMaxViewDist_Deferred=170;------def 150------changed to 170*
r_ShadowCastingLightsMaxCount=12;------def 16------changed to 12*
r_ShadowsBias=0.00001;------def 0.00008------changed to 0.00001*
r_ShadowsCacheResolutions=6324,4214,2810,1872,624;------def 6324,4214,2810,1872,624
r_ShadowsScreenSpace=1;------def 2------changed to 1*
r_ssdoAmountAmbient=2;------def 1------changed to 2*
r_ssdoAmountDirect=4;------def 1.5------changed to 4*
r_ssdoAmountReflection=5;------def 4------changed to 5*
r_ssdoRadius=1;------def 0.3------changed to 1*
r_ssdoRadiusMin=0.02;------def 0.1------changed to 0.02*
r_SSReflections=0;------def 1------changed to 0*
r_SuperSampling=1;------def 1
r_TexMaxAnisotropy=8;------def 4------changed to 8*
r_TexMinAnisotropy=8;------def 4------changed to 8*
r_TexNoAnisoAlphaTest=0;------def 0------1 for PERFORMANCE
r_VolumetricFogSunLightCorrection=0;------def 1------changed to 0*
r_VolumetricFogTexDepth=8;------def 32------changed to 8*
r_VolumetricFogTexScale=25;------def 10------changed to 25*
r_WaterCaustics=0;------def 1------changed to 0
r_WaterGodRays=0;------def 1------changed to 0
r_WaterReflectionsQuality=3;------def 4------changed to 3*
r_WaterTessellationHW=0;------def 1------changed to 0*
```

---

#### Create a mod folder in KingdomComeDeliverance/Mods

[Cooking cauldron flickering smoke Fix](https://www.nexusmods.com/kingdomcomedeliverance/mods/1177)

[Arrows go fast](https://www.nexusmods.com/kingdomcomedeliverance/mods/1240)

[Remove Those Stupid Trails](https://www.nexusmods.com/kingdomcomedeliverance/mods/7)

[Instant Herb Picking with hand movement](https://www.nexusmods.com/kingdomcomedeliverance/mods/367)

[Alternate Food Spoil (Updated)](https://www.nexusmods.com/kingdomcomedeliverance/mods/1065)

[Inventoried](https://www.nexusmods.com/kingdomcomedeliverance/mods/797)

[Bushes- Collision Remover](https://www.nexusmods.com/kingdomcomedeliverance/mods/591)

[NoTimedDecisions](https://www.nexusmods.com/kingdomcomedeliverance/mods/1343)

[MuttBeQuiet](https://www.nexusmods.com/kingdomcomedeliverance/mods/1322)

[HelmetVision](https://www.nexusmods.com/kingdomcomedeliverance/mods/1337)

[No Helmet Vision](https://www.nexusmods.com/kingdomcomedeliverance/mods/28) (removed)

[No Blood On Screen (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/58)

[No Drunk Sharpen Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/105)

[No Stamina Visual Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/10)

UI edits in KingdomComeDeliverance\Data\GameData.pak\Libs\UI\Textures\Hud_main.dds (make mod folder)

<details><summary>Quicksave (click for edits and link)</summary>
<p>

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
</p>
</details>

---

#### Added all these mods in one rpg_param.xml (make your own so there is no conflicts):

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

























////////////////
//////////////
///////////////
////////////
//////////////////
//////////////
///////////////
////////////
//////////////////
////////
//////////////
////////////
/////////////////////





















#### updated 12/4/2022 :ramen:

###### my config and stuff for kcd hf

###### Use Nvidia Image Scaling and turn down in game res for more fps

#### Create a file in KingdomComeDeliverance/user.cfg and copy paste this and add launch commands (+exec user.cfg -devmode):

---

```python
con_restricted=0;
sys_MaxFPS=162;------def 0------changed to 162*
sys_spec=0;------sets custom spec
sys_spec_GameEffects=3;
sys_spec_Light=3;
sys_spec_ObjectDetail=3;
sys_spec_Particles=3;
sys_spec_Physics=3;
sys_spec_PostProcessing=3;
sys_spec_Shading=3;
sys_spec_Shadows=3;
sys_spec_Sound=3;
sys_spec_Texture=3;
sys_spec_TextureResolution=7;------HD textures on
sys_spec_Vegetation=3;
sys_spec_VolumetricEffects=3;
sys_spec_Water=3;
q_Renderer=3;
q_ShaderFX=3;
q_ShaderGeneral=3;
q_ShaderGlass=3;
q_ShaderHDR=3;
q_ShaderIce=3;
q_ShaderMetal=3;
q_ShaderPostProcess=3;
q_ShaderShadow=3;
q_ShaderSky=3;
q_ShaderTerrain=3;
q_ShaderVegetation=3;
q_ShaderWater=3;
Bind 0 "exec user.cfg";
Bind 8 "g_showHUD 0";
Bind 9 "g_showHUD 1";
Bind f1 "sys_MaxFPS 111";
Bind f2 "sys_MaxFPS 162";
Bind f3 "exec TEST1.cfg";
Bind f4 "exec TEST2.cfg";
cl_fov=73;------def 60------changed to 73*
pl_movement.power_sprint_targetFOV=73;------def 55------changed to 73*
r_DrawNearFOV=73;------def 60------changed to 73*
cl_sensitivity=10;
i_mouse_accel=0;
i_mouse_smooth=0;
g_skipIntro=1;------def 0------changed to 1*
r_Vsync=0;
wh_cs_PlayerLockDisabled=0;------def 0
wh_horse_CameraCentering=0;------def 0.2------changed to 0*
wh_pl_showfirecursor=1;------def 0------changed to 1*
ca_AttachmentCullingRation=300;------def 360------changed to 300*
e_CoverageBufferTerrainLodShift=0;------def 2------changed to 0*
e_CullVegActivation=30;------def 50------changed to 30*
e_DecalsLifeTimeScale=1;------def 2------changed to 1*
e_DecalsRange=10;------def 20------changed to 10*
e_GsmRangeStep=2.5;------def 3------changed to 2.5*
e_LodFaceAreaTargetSize=0.0006;------def 0.001------changed to 0.0006*
e_LodRatio=25;------def 25
e_MergedMeshesInstanceDist=5;------def 8------changed to 5*
e_MergedMeshesLodRatio=1;------def 5------changed to 1*
e_MergedMeshesPool=16384;------def 8192 change to 16384
e_MergedMeshesViewDistRatio=85;------def 70------changed to 85*
e_ObjShadowCastSpec=2;------def 3------changed to 2*
e_PhysProxyTriLimit=5000;------def 10000------changed to 5000*
e_ShadowsBlendCascades=0;------def 2------changed to 0*
e_ShadowsCacheUpdate=1;------def 2------changed to 1*
e_ShadowsCastViewDistRatio=0.8;------def 1------changed to 0.8*
e_ShadowsCastViewDistRatioMulInvis=0.1;------def 0.4------changed to 0.1*
e_ShadowsMaxTexRes=1024;------def 1024
e_ShadowsUpdateViewDistRatio=80;------def 100------changed to 80*
e_SkyQuality=2;------def 2------1 for PERFORMANCE
e_StreamCgfPoolSize=1024;------def 512------changed to 1024*
e_svoTI_SSAOAmount=1.5;------def 1------changed to 1.5*
e_TerrainDetailMaterialsViewDistZ=100;------def 80------changed to 100*
e_TerrainLodRatio=0.5;------def 0.3------changed to 0.5*
e_TerrainOcclusionCullingMaxDist=150;------def 200------changed to 150*
e_UberlodDistanceRatio=1.9;------def 1.8------changed to 1.9*
e_ViewDistRatioVegetation=65;------def 55------changed to 65*
e_VolumetricFog=0;------def 0
es_DebrisLifetimeScale=0.6;------def 1------changed to 0.6*
es_maxphysdistcloth=100;------def 300------changed to 100*
g_breakage_particles_limit=80;------def 160------changed to 80*
gpu_Particle_Physics=0;------def 0
p_max_MC_iters=4000;------def 6000------changed to 4000*
r_AntialiasingMode=3;------def 1------changed to 3*
r_AntialiasingTAAPattern=3;------def 1------changed to 3*
r_AntialiasingTAASharpening=0;------def 0.2------changed to 0*
r_BatchType=1;------def 1
r_DeferredShadingAreaLights=1;------def 1
r_DepthBits=32;------def 24------changed to 32*
r_FogShadowsWater=1;------def 0------changed to 1*
r_HDRBloom=0;------def 1------changed to 0*
r_HDRVignetting=0;------def 1------changed to 0*
r_MotionBlur=0;
r_RainMaxViewDist_Deferred=170;------def 150------changed to 170*
r_ShadowCastingLightsMaxCount=12;------def 16------changed to 12*
r_ShadowsBias=0.00001;------def 0.00008------changed to 0.00001*
r_ShadowsCacheResolutions=6324,4214,2810,1872,624;------def 6324,4214,2810,1872,624
r_ShadowsScreenSpace=1;------def 2------changed to 1*
r_ssdoAmountAmbient=2;------def 1------changed to 2*
r_ssdoAmountDirect=4;------def 1.5------changed to 4*
r_ssdoAmountReflection=5;------def 4------changed to 5*
r_ssdoRadius=1;------def 0.3------changed to 1*
r_ssdoRadiusMin=0.02;------def 0.1------changed to 0.02*
r_SSReflections=0;------def 1------changed to 0*
r_SuperSampling=1;------def 1
r_TexMaxAnisotropy=8;------def 4------changed to 8*
r_TexMinAnisotropy=8;------def 4------changed to 8*
r_TexNoAnisoAlphaTest=0;------def 0------1 for PERFORMANCE
r_VolumetricFogSunLightCorrection=0;------def 1------changed to 0*
r_VolumetricFogTexDepth=8;------def 32------changed to 8*
r_VolumetricFogTexScale=25;------def 10------changed to 25*
r_WaterCaustics=0;------def 1------changed to 0
r_WaterGodRays=0;------def 1------changed to 0
r_WaterReflectionsQuality=3;------def 4------changed to 3*
r_WaterTessellationHW=0;------def 1------changed to 0*
```

---

#### Create a mod folder in KingdomComeDeliverance/Mods

[Cooking cauldron flickering smoke Fix](https://www.nexusmods.com/kingdomcomedeliverance/mods/1177)

[Arrows go fast](https://www.nexusmods.com/kingdomcomedeliverance/mods/1240)

[Remove Those Stupid Trails](https://www.nexusmods.com/kingdomcomedeliverance/mods/7)

[Instant Herb Picking with hand movement](https://www.nexusmods.com/kingdomcomedeliverance/mods/367)

[Alternate Food Spoil (Updated)](https://www.nexusmods.com/kingdomcomedeliverance/mods/1065)

[Inventoried](https://www.nexusmods.com/kingdomcomedeliverance/mods/797)

[Bushes- Collision Remover](https://www.nexusmods.com/kingdomcomedeliverance/mods/591)

[NoTimedDecisions](https://www.nexusmods.com/kingdomcomedeliverance/mods/1343)

[MuttBeQuiet](https://www.nexusmods.com/kingdomcomedeliverance/mods/1322)

[HelmetVision](https://www.nexusmods.com/kingdomcomedeliverance/mods/1337)

[No Helmet Vision](https://www.nexusmods.com/kingdomcomedeliverance/mods/28) (removed)

[No Blood On Screen (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/58)

[No Drunk Sharpen Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/105)

[No Stamina Visual Effects (make Data folder then add the .pak)](https://www.nexusmods.com/kingdomcomedeliverance/mods/10)

UI edits in KingdomComeDeliverance\Data\GameData.pak\Libs\UI\Textures\Hud_main.dds (make mod folder)

<details><summary>Quicksave (click for edits and link)</summary>
<p>

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
</p>
</details>

<details><summary>Ride horse threw rivers (make mod folder)</summary>
<p>

#### zzzz_horse_ignore_water_barrier\Data\zzzz_horse_ignore_water_barrier.pak\Libs\MaterialEffects\SurfaceTypes.xml

```python
add  horse_ignore="1" in here

  <SurfaceType name="mat_deep_water_barrier">
    <Physics friction="0.5" elasticity="0.050000001"  pierceability="11"  dbg_color="123,103,65" horse_ignore="1" />
    <Barrier distance="3" slowdown="1" monologMetaroleId="335"/>
  </SurfaceType>
```
</p>
</details>

---

#### Added all these mods in one rpg_param.xml (make your own so there is no conflicts):

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
