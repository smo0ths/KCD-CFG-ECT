Create a folder in KingdomComeDeliverance/Mods

NoFallDamage
these lines added to Unlimited Weights rpg_param.xml
      <row rpg_param_key="HarmlessFallHeight" rpg_param_value="8000" />
      <row rpg_param_key="InjuringFallHeight" rpg_param_value="8000" />
      <row rpg_param_key="FatalFallHeight" rpg_param_value="10000" />
      <row rpg_param_key="FallDamageMultiplierAtMaxiAgility" rpg_param_value="0.20" />

Quicksave
https://www.nexusmods.com/kingdomcomedeliverance/mods/1282

Definitive Repair Kit
https://www.nexusmods.com/kingdomcomedeliverance/mods/938

Cooking cauldron flickering smoke Fix
https://www.nexusmods.com/kingdomcomedeliverance/mods/1177

Instant Herb Picking
https://www.nexusmods.com/kingdomcomedeliverance/mods/367

Arrows go fast
https://www.nexusmods.com/kingdomcomedeliverance/mods/1240

Alternate Food Spoil (Updated)
https://www.nexusmods.com/kingdomcomedeliverance/mods/1065

Easy Sharpening
https://www.nexusmods.com/kingdomcomedeliverance/mods/336

More Faster XP
https://www.nexusmods.com/kingdomcomedeliverance/mods/1129

Inventoried
https://www.nexusmods.com/kingdomcomedeliverance/mods/797

No Blood On Screen
https://www.nexusmods.com/kingdomcomedeliverance/mods/58

No Vignettes
https://www.nexusmods.com/kingdomcomedeliverance/mods/78

No Helmet Vision
https://www.nexusmods.com/kingdomcomedeliverance/mods/28

No Drunk Sharpen Effects
https://www.nexusmods.com/kingdomcomedeliverance/mods/105

No Stamina Visual Effects
https://www.nexusmods.com/kingdomcomedeliverance/mods/10

Unlimited Weight
https://www.nexusmods.com/kingdomcomedeliverance/mods/12

Bushes- Collision Remover
https://www.nexusmods.com/kingdomcomedeliverance/mods/591

Remove Those Stupid Trails
https://www.nexusmods.com/kingdomcomedeliverance/mods/7

~~~~~~

Create a file in KingdomComeDeliverance/user.cfg and copy/paste this:

;Add launch commands: +exec user.cfg -devmode
con_restricted=0;
sys_spec=0;------sets custom
;sys_spec_Full=3;------sets all spec
sys_spec_GameEffects=3;
sys_spec_Light=3;
sys_spec_ObjectDetail=3;
sys_spec_Particles=3;
sys_spec_Physics=3;
sys_spec_PostProcessing=3;
sys_spec_Shading=3;
sys_spec_Shadows=3;
sys_spec_Sound=3;------default 3
sys_spec_Texture=3;
sys_spec_TextureResolution=7;------HD textures on
sys_spec_Vegetation=3;
sys_spec_VolumetricEffects=3;
sys_spec_Water=3;
;sys_spec_Quality=4;------sets all q_
;q_Quality=3;------sets all q_
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
sys_main_CPU=0;------default 0
sys_physics_CPU=1;------default 1
sys_streaming_CPU=1;------default 1
sys_streaming_CPU_worker=5;------default 5
sys_limit_phys_thread_count=1;------default 1
p_num_threads=2;------default 2
sys_job_system_enable=1;------default 1
sys_job_system_max_worker=8;------default 8
ca_thread=1;------default 1
ca_thread0Affinity=5;------default 5
ca_thread1Affinity=3;------default 3
sys_TaskThread0_CPU=3;------default 3
sys_TaskThread1_CPU=5;------default 5
sys_TaskThread2_CPU=4;------default 4
sys_TaskThread3_CPU=3;------default 3
sys_TaskThread4_CPU=2;------default 2
sys_TaskThread5_CPU=1;------default 1
sys_affinity=0;------default 0
e_ParticlesThread=1;------default 1
gpu_Particle_Physics=0;------default 0
r_ShadersAsyncMaxThreads=1;------default 1
r_WaterUpdateThread=5;------default 5
ai_NavigationSystemMT=1;------default 1
gfx_loadtimethread=1;------default 1
e_StatObjMergeUseThread=1;------default 1
e_StatObjMerge=1;------default 1
e_StatObjMergeMaxTrisPerDrawCall=500;------default 500
e_StatObjValidate=0;------default 0
r_BatchType=1;------default 1
r_RenderTargetPoolSize=0;------default 0
r_ShadersAsyncActivation=0;------default 0
r_ShadersAsyncCompiling=3;------system 3
r_ShadersDX11=1;------default 1
r_ShadersPreactivate=3;------default 3
sys_PakStreamCache=1;------default 0
sys_preload=1;------default 0
e_PreloadMaterials=1;------default 1
e_PreloadDecals=1;------default 1
e_StatObjPreload=1;------default 1
r_MultiGPU=0;------default 0
r_MultiThreaded=1;------default 1
r_ConditionalRendering=0;------default 0
sys_MaxFPS=90;------default 0
cl_fov=59;------default 60
r_DrawNearFOV=59;------default 60
pl_movement.power_sprint_targetFOV=59;------default 55
i_mouse_smooth=0;
i_mouse_accel=0;
cl_sensitivity=10;
g_skipIntro=1;------default 0 changed to 1*
wh_pl_showfirecursor=1;------default 0 changed to 1*
wh_horse_CameraCentering=0;------default 0.2 changed to 0*
r_Vsync=0;
r_UseZPass=2;------default 2
r_ColorGrading=2;------default 2
r_ColorGradingChartsCache=0;------default 0
r_Sharpening=0;------default 0
r_ChromaticAberration=0;
r_Gamma=1;------default 1
r_Contrast=0.5;------default 0.5
r_Brightness=0.5;------default 0.5
r_HDRRendering=1;------default 1
r_HDRGrainAmount=0;
r_HDRVignetting=0;------default 1 changed to 0*
r_HDRBloom=0;------default 1 changed to 0*
r_HDRBloomQuality=2;------default 2
e_DecalsRange=10;------default 20 changed to 10*
e_DecalsLifeTimeScale=1;------default 2 changed to 1*
r_DepthOfField=2;------default 2
r_MotionBlur=0;
r_UseMaterialLayers=2;------default 2
e_ParticlesVertexPoolSize=256;------default 256
e_ParticlesIndexPoolSize=16;------default 16
e_ParticlesLightMinRadiusThreshold=0;------default 0
e_ParticlesLightMinColorThreshold=0;------default 0
e_ParticlesQuality=4;------default 4
e_ParticlesSortQuality=0;------default 0
e_ParticlesMotionBlur=0;------default 0
e_ParticlesShadows=1;------default 1
r_ParticlesHalfRes=0;------default 0
r_ParticlesTessellation=1;------default 1
e_ParticlesObjectCollisions=2;------default 2
e_ParticlesPoolSize=16384;------default 16384
e_ParticlesAnimBlend=1;------default 1
e_ParticlesGI=1;------default 1
es_maxphysdistcloth=100;------default 300 changed to 100*
es_MaxPhysDist=100;------default 100
es_MaxPhysDistInvisible=25;------default 25
es_DebrisLifetimeScale=0.6;------default 1 changed to 0.6*
g_breakage_particles_limit=80;------default 160 changed to 80*
g_tree_cut_reuse_dist=0;------default 0
p_max_MC_iters=4000;------default 6000 changed to 4000*
e_PhysFoliage=2;------default 2
e_FoliageWindActivationDist=25;------default 25
e_ProcVegetation=0;------default 0
e_MergedMeshes=1;------default 1
e_MergedMeshesPool=16384;------default 8192 change to 16384
e_MergedMeshesViewDistRatio=90;------default 70 changed to 90*
e_MergedMeshesLodRatio=5;------system 1 default 5
e_MergedMeshesInstanceDist=8;------system 1 default 8
e_MergedMeshesActiveDist=250;------default 250
e_MergedMeshesTesselationSupport=0;------default 0
e_Tessellation=0;------default 0
e_TessellationMaxDistance=30;------default 30
r_TessellationTriangleSize=8;------default 8
e_CoverageBufferTerrainLodShift=0;------default 2 changed to 0*
r_SSReflections=0;------default 1 changed to 0*
r_SSReflHalfRes=1;------default 1
r_Reflections=1;------default 1
r_ReflectionsQuality=3;------default 3
r_Refraction=1;
r_DynTexAtlasCloudsMaxSize=32;------default 32
r_DynTexAtlasSpritesMaxSize=32;------default 32
r_EnvCMResolution=2;------default 2
r_EnvTexResolution=3;------default 3
r_ImposterRatio=1;------default 1
r_TexAtlasSize=2048;------default 2048
r_TexMinAnisotropy=8;------default 4 changed to 8*
r_TexMaxAnisotropy=8;------default 4 changed to 8*
r_TexNoAnisoAlphaTest=1;------default 0 changed to 1*
r_DetailTextures=1;------default 1
r_TexturesStreamPoolSize=4096;------default 4096
r_TexturesStreaming=1;------default 1
r_TexturesStreamingMaxRequestedMB=20;------default 20
r_TexturesStreamingMipBias=0;------default 0
r_TexturesStreamingSkipMips=0;------default 0
r_TexturesstreamingMinUsableMips=8;------default 8
r_TexturesStreamingResidencyTime=10;------default 10
r_TexturesStreamingDeferred=1;------default 1
r_TexturesStreamingResidencyEnabled=1;------default 1
r_TexturesStreamingResidencyThrottle=0.5;------default 0.5
r_DeferredShading3PL=2;------default 2
r_DeferredShadingSortLights=0;------default 0
r_DeferredShadingAreaLights=1;------default 1
r_DeferredShadingTiledHairQuality=1;------default 1
r_DeferredShadingFilterGBuffer=0;------default 0
r_DeferredShadingSSS=1;------default 1
r_DeferredShadingTiled=2;------default 2
e_VolumetricFog=1;------default 0 changed to 1*
r_VolumetricFogTexDepth=8;------default 32 changed to 8*
r_VolumetricFogTexScale=25;------default 10 changed to 25*
r_VolumetricFogSunLightCorrection=0;------default 1 changed to 0*
r_Flares=0;------default 0
e_Fog=1;------default 1
e_FogVolumes=1;------default 1
e_FogVolumesTiledInjection=1;------default 1*
r_FogShadows=0;------default 0*
r_SuperSampling=0;------default 1 changed to 0*
r_AntialiasingMode=3;------default 1 changed to 3*
r_AntialiasingTAAPattern=3;------default 1 changed to 3*
r_AntialiasingTAAFalloffHiFreq=6;------default 6*
r_AntialiasingTAAFalloffLowFreq=4;------default 2 changed to 4*
r_AntialiasingTAASharpening=0;------default 0.2 changed to 0*
r_silhouettePOM=0;------default 0
wh_pl_FOWEnabled=1;------default 1
wh_pl_FOWVisibilityRadius=100;------default 100
r_WaterCaustics=0;------default 1
r_WaterVolumeCaustics=0;------default 0
r_WaterGodRays=0;------default 1
r_WaterReflections=1;------default 1
r_WaterReflectionsQuality=3;------default 4 changed to 3*
r_WaterReflectionsMGPU=0;------default 0
e_WaterOceanFFT=0;------default 1
r_FogShadowsWater=1;------default 0 changed to 1*
r_WaterTessellationHW=0;------default 1
e_WaterTessellationAmount=10;------default 10
e_WaterTessellationAmountX=10;------default 10
e_WaterTessellationAmountY=10;------default 10
e_PhysMinCellSize=4;------default 4
e_PhysOceanCell=0.5;------default 4
r_ColorBits=32;------default 32
r_DepthBits=24;------default 24
r_ShadowTexFormat=0;------default 0
r_ShadowsPCFiltering=1;------default 1
e_ShadowsResScale=4;------default 4
r_UseShadowsPool=1;------default 1
e_ShadowsPoolSize=4096;------default 4096
r_ShadowsCacheResolutions=6324,4214,2810,1872,624;------default 6324,4214,2810,1872,624
e_ShadowsMaxTexRes=2048;------default 1024 changed to 2048*
r_DynTexMaxSize=160;------default 160
r_ShadowsBias=0.00001;------default 0.00008 changed to 0.00001*
r_ShadowsScreenSpace=1;------default 2 changed to 1*
e_ObjShadowCastSpec=2;------default 3 changed to 2*
e_GsmRangeStep=2.5;------default 3 changed to 2.5*
e_GsmRange=3;------default 3
e_GsmLodsNum=5;------default 5
r_ShadowJittering=2.5;------default 2.5
e_ShadowsMasksLimit=0;------default 0
e_ShadowsUpdateViewDistRatio=128;------default 100 changed to 128*
r_ShadowCastingLightsMaxCount=16;------default 16
e_ShadowsCastViewDistRatio=0.8;------default 1 changed to 0.8*
e_ShadowsCastViewDistRatiolights=0.2;------default 0.2
e_ShadowsBlendCascades=0;------default 2 changed to 0*
r_ForceAllLightsShadows=0;------default 0
e_streamCgf=1;------default 1
e_StreamCgfPoolSize=1024;------system 512 changed to 1024*
e_StreamInstancesMinLoadedNodes=2048;------default 2048
e_CoverageBufferReproj=6;------default 6
e_CheckOcclusion=1;------default 1
e_CheckOcclusionQueueSize=8192;------default 8192
e_CheckOcclusionOutputQueueSize=16384;------default 16384
r_MeshPrecache=1;------default 1
r_MeshPoolSize=0;------default 0
r_MeshInstancePoolSize=0;------default 0
e_VegetationUseTerrainColor=1;------default 1
e_VegetationUseTerrainColorDistance=175;------default 0 changed to 175*
e_TerrainDetailMaterialsViewDistXY=2048;------default 2048
e_TerrainDetailMaterialsViewDistZ=100;------default 80 changed to 100*
e_TerrainOcclusionCullingMaxDist=150;------default 200 changed to 150*
e_TerrainLodRatio=0.5;------default 0.3 changed to 0.5*
e_CullVegActivation=30;------default 50 changed to 30*
e_LodMin=0;------default 0
e_LodRatio=40;------default 25 changed to 40*
e_VegetationMinSize=0;------default 0
e_OcclusionCullingViewDistRatio=1;------default 1
e_ViewDistMin=5;------default 5
e_ViewDistRatio=100;------default 100
e_ViewDistRatioVegetation=100;------system 50 default 55 changed to 100*
e_ViewDistRatioDetail=100;------default 100
e_ViewDistRatioLights=50;------default 50
e_ViewDistRatioCustom=100;------default 100
e_ViewDistRatioPortals=100;------default 100
e_LodFaceAreaTargetSize=0.0006;------default 0.001 changed to 0.0006*
e_UberlodSystemMode=0;------default 0
e_UberlodDistanceMargin=16;------default 16
e_UberlodMinUpdateDistance=16;------default 16
e_UberlodDistanceRatio=1.9;------default 1.8 changed to 1.9*
e_UberlodUpdateBudget=2000;------default 2000
wh_env_RainLayers=3;------default 3
r_RainMaxViewDist_Deferred=170;------default 150 changed to 170*
e_ViewDistCompMaxSize=64;------default 64
e_MaxViewDistSpecLerp=1;------default 1
e_MaxViewDistance=-1;------default -1
ca_AttachmentCullingRation=340;------default 360 changed to 340*
wh_cc_CharacterDetailReduction=1;------default 0 changed to 1*
wh_cc_LodForItemStreamOutBase=15;------default 15
wh_cc_LodForAttachmentStreamOut=4;------default 4
WH_AI_LOD_DistanceMin=60;------default 60
WH_AI_LOD_DistanceMax=90;------default 90
v_vehicle_quality=4;------default 4
e_ObjQuality=3;------default 3
r_DetailDistance=8;------default 8
e_PhysProxyTriLimit=5000;------default 10000 changed to 5000*
e_SkyQuality=1;------default 2 changed to 1*
e_DynamicLightsMaxEntityLights=16;------default 16
e_GI=0;------default 0
e_GIAmount=0.6;------default 0.6
e_GIMaxDistance=100;------default 100
e_GINumCascades=1;------default 1
e_GICache=7;------default 7
e_TerrainAO=0;------default 0
r_TerrainAO=7;------default 7
r_TerrainAO_FadeDist=8;------default 8
r_ssdo=1;
r_ssdoColorBleeding=1;
r_ssdoHalfRes=2;
r_ssdoAmountAmbient=2;------system 1 beta 2
r_ssdoAmountDirect=4;------system 1.5 beta 4
r_ssdoAmountReflection=5;------system 1.5 beta 5
r_ssdoRadius=1;------system 0.3 beta 1
r_ssdoRadiusMax=2;------system 2 beta 2
r_ssdoRadiusMin=0.02;------system 0.1 beta 0.05 changed to 0.02*
e_svoTI_DistantSsaoAmount=1;------system 1
e_svoTI_SSAOAmount=1.5;------default 1 changed to 1.5*
e_svoTI_ResScaleBase=2;------default 2
e_svoTI_LowSpecMode=4;------default 4
e_svoTI_ConeMaxLength=25;------default 25
e_svoTI_DiffuseConeWidth=12;------default 12
e_svoTI_SpecularAmplifier=1;------default 1
e_svoTI_MinReflectance=0.2;------default 0.2
e_svoTI_DiffuseAmplifier=1;------default 1
e_svoTI_MinVoxelOpacity=0.01;------system 0.01
e_svoTI_VegetationMaxOpacity=1;------system 1
e_svoTI_TemporalFilteringBase=0.5;------system 0.5
e_svoTI_RsmConeMaxLength=6;------system 6
e_svoMaxAreaMeshSizeKB=20000;------system 20000
Bind 8 "g_showHUD 0";
Bind 9 "g_showHUD 1";
Bind 0 "exec user.cfg";
Bind f1 "sys_MaxFPS 90";
Bind f2 "sys_MaxFPS 163";
Bind f3 "exec TEST1.cfg";
Bind f4 "exec TEST2.cfg";
