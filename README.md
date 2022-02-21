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
sys_MaxFPS=90;------default 0 changed to 90*
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
Bind f1 "sys_MaxFPS 90";
Bind f2 "sys_MaxFPS 163";
Bind f3 "exec TEST1.cfg";
Bind f4 "exec TEST2.cfg";
ca_AttachmentCullingRation=300;------default 360 changed to 300*
cl_fov=59;------default 60 changed to 59*
cl_sensitivity=10;
e_CoverageBufferTerrainLodShift=0;------default 2 changed to 0*
e_CullVegActivation=30;------default 50 changed to 30*
e_DecalsLifeTimeScale=1;------default 2 changed to 1*
e_DecalsRange=10;------default 20 changed to 10*
e_GsmRangeStep=2.5;------default 3 changed to 2.5*
e_LodFaceAreaTargetSize=0.0006;------default 0.001 changed to 0.0006*
e_LodRatio=40;------default 25 changed to 40*
e_MergedMeshesInstanceDist=4;------default 8 changed to 4*
e_MergedMeshesLodRatio=5;------default 5 changed to 4*
e_MergedMeshesPool=16384;------default 8192 change to 16384
e_MergedMeshesViewDistRatio=85;------default 70 changed to 85*
e_ObjShadowCastSpec=2;------default 3 changed to 2*
e_PhysProxyTriLimit=5000;------default 10000 changed to 5000*
e_ShadowsBlendCascades=0;------default 2 changed to 0*
e_ShadowsCastViewDistRatio=0.8;------default 1 changed to 0.8*
e_ShadowsMaxTexRes=2048;------default 1024 changed to 2048*
e_ShadowsUpdateViewDistRatio=80;------default 100 changed to 80*
e_SkyQuality=1;------default 2 changed to 1*
e_StreamCgfPoolSize=1024;------default 512 changed to 1024*
e_svoTI_SSAOAmount=1.5;------default 1 changed to 1.5*
e_TerrainDetailMaterialsViewDistZ=100;------default 80 changed to 100*
e_TerrainLodRatio=0.5;------default 0.3 changed to 0.5*
e_TerrainOcclusionCullingMaxDist=150;------default 200 changed to 150*
e_UberlodDistanceRatio=1.9;------default 1.8 changed to 1.9*
e_ViewDistRatioVegetation=65;------default 50 default 55 changed to 65*
e_VolumetricFog=1;------default 0 changed to 1*
es_DebrisLifetimeScale=0.6;------default 1 changed to 0.6*
es_maxphysdistcloth=100;------default 300 changed to 100*
g_breakage_particles_limit=80;------default 160 changed to 80*
g_skipIntro=1;------default 0 changed to 1*
gpu_Particle_Physics=1;------default 0 changed to 1*
i_mouse_accel=0;
i_mouse_smooth=0;
p_max_MC_iters=4000;------default 6000 changed to 4000*
pl_movement.power_sprint_targetFOV=59;------default 55 changed to 59*
r_AntialiasingMode=3;------default 1 changed to 3*
r_AntialiasingTAAPattern=3;------default 1 changed to 3*
r_AntialiasingTAASharpening=0;------default 0.2 changed to 0*
r_DepthBits=32;------default 24 changed to 24
r_DrawNearFOV=59;------default 60 changed to 59*
r_FogShadowsWater=1;------default 0 changed to 1*
r_HDRBloom=0;------default 1 changed to 0*
r_HDRVignetting=0;------default 1 changed to 0*
r_MotionBlur=0;
r_RainMaxViewDist_Deferred=170;------default 150 changed to 170*
r_ShadowsBias=0.00001;------default 0.00008 changed to 0.00001*
r_ShadowsScreenSpace=1;------default 2 changed to 1*
r_ssdoAmountAmbient=2;------default 1 changed to 2*
r_ssdoAmountDirect=4;------default 1.5 changed to 4*
r_ssdoAmountReflection=5;------default 4 changed to 5*
r_ssdoRadius=1;------default 0.3 changed to 1*
r_ssdoRadiusMin=0.02;------default 0.1 changed to 0.02*
r_SSReflections=0;------default 1 changed to 0*
r_SuperSampling=0;------default 1 changed to 0*
r_TexMaxAnisotropy=8;------default 4 changed to 8*
r_TexMinAnisotropy=8;------default 4 changed to 8*
r_TexNoAnisoAlphaTest=1;------default 0 changed to 1*
r_VolumetricFogSunLightCorrection=0;------default 1 changed to 0*
r_VolumetricFogTexDepth=8;------default 32 changed to 8*
r_VolumetricFogTexScale=25;------default 10 changed to 25*
r_Vsync=0;
r_WaterCaustics=0;------default 1 changed to 0
r_WaterGodRays=0;------default 1 changed to 0
r_WaterReflectionsQuality=3;------default 4 changed to 3*
r_WaterTessellationHW=0;------default 1 changed to 0
wh_cs_PlayerLockDisabled=0;------default 0
wh_horse_CameraCentering=0;------default 0.2 changed to 0*
wh_pl_showfirecursor=1;------default 0 changed to 1*







