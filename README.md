## updated 1/17/2025 v0.9.3 :ramen:

#### Create user.cfg in KingdomComeDeliverance folder and copy paste

#### delete cache folder %userprofile%/Saved Games/kingdomcome/shaders

#### Add launch commands: +exec user.cfg -devmode

#### and restart after getting to main menu

#### all mods i use are under the config

---

```python
## create user.cfg in kingdomcomedeliverance folder and copy paste
## delete cache folder %userprofile%/saved games/kingdomcome/shaders
## add launch commands: +exec user.cfg -devmode
## and restart after getting to main menu
## "" means changed ## means sudo default max spec this is a ultra high config

##
Con_Restricted=0 ##
Sys_Maxfps=158 ## 0 ""

##
Q_Quality=3 ## ""
Sys_Spec_Full=7 ## ""
Sys_Spec_Quality=4 ## 4 ""

##
Sys_Spec=0 ## "Custom"

##
Sys_Spec_Gameeffects=7 ##
Sys_Spec_Light=7 ##
Sys_Spec_Objectdetail=7 ##
Sys_Spec_Particles=7 ##
Sys_Spec_Physics=7 ##
Sys_Spec_Postprocessing=7 ##
Sys_Spec_Shading=7 ##
Sys_Spec_Shadows=7 ##
Sys_Spec_Sound=7 ##
Sys_Spec_Texture=7 ##
Sys_Spec_Textureresolution=7 ## "7 Hd Textures"
Sys_Spec_Vegetation=7 ##
Sys_Spec_Volumetriceffects=7 ##
Sys_Spec_Water=7 ##

##
Q_Renderer=3 ##
Q_Shaderfx=3 ##
Q_Shadergeneral=3 ##
Q_Shaderglass=3 ##
Q_Shaderhdr=3 ##
Q_Shaderice=3 ##
Q_Shadermetal=3 ##
Q_Shaderpostprocess=3 ##
Q_Shadershadow=3 ##
Q_Shadersky=3 ##
Q_Shaderterrain=3 ##
Q_Shadervegetation=3 ##
Q_Shaderwater=3 ## 2 ""

##
Bind 0 G_Showhud 0 ##
Bind 9 G_Showhud 1 ##
Bind f1 Sys_Maxfps 158 ##
Bind f2 Sys_Maxfps 60 ##
Bind f3 "exec Test1.cfg" ## "Make"
Bind f4 "exec Test2.cfg" ## "Make"
Bind f6 R_Reloadshaders 1 ## "Make"

##
Cl_Sensitivity=10 ##
G_Skipintro=1 ## 0 ""
I_Mouse_Accel=0 ##
I_Mouse_Smooth=0 ##
R_Displayinfo=0 ##
R_Vsync=0 ##

##
Cl_Fov=68 ## 60 ""
Pl_Movement.Power_Sprint_Targetfov=68 ## 55 ""
R_Drawnearfov=68 ## 60 ""

##
E_Streamcgfpoolsize=1024 ## 512 "Ram,Test"
R_Rendertargetpoolsize=1024 ## 0 "Vram,Test"
R_Texturesstreamingmaxrequestedmb=1024 ## 20 "Vram,Test"
R_Texturesstreampooldefragmentationmaxamount=3145728 ## 2097152 "Vram,Test"
R_Texturesstreampooldefragmentationmaxmoves=15 ## 10 "Vram,Test"
R_Texturesstreampoolsize=6144 ## 4096 "Vram,Test"
Sys_Budget_Streamingthroughput=3000 ## 1024 "Ram,Test"
Sys_Budget_Sysmem=0 ## 512 "Ram,Debug,Test"
Sys_Budget_Videomem=0 ## 90 "Ram,Debug,Test"
Sys_Pakstreamcache=1 ## 0 "Ram,Test"
Sys_Streaming_Max_Bandwidth=2000 ## 0 "Vram,Test"

##
## E_Vegetationminsize=0 ## 0.1 "Pickable Vegetation"
## R_Dyntexatlasspritesmaxsize=32 ## 32 "Not Real"
## R_Hdrbrightlevel=1 ## 1 "Not Real"
## R_Silhouettepom=0 ## 0 ""
## S_Obstructionmaxvalue=0 ## 0 "Not Real"
E_Coveragebufferterrainexpand=0 ## 0.025 ""
E_Lodfaceareatargetsize=0.0006 ## 0.001 ""
E_Lodratio=70 ## 60 "70 Max Slider"
E_Mergedmeshesinstancedist=32 ## 16 ""
E_Mergedmesheslodratio=16 ## 8 ""
E_Mergedmeshesviewdistratio=100 ## 85 "100 Max Slider"
E_Particlesmotionblur=0 ## 1 ""
E_Physproxytrilimit=1000 ## 10000 ""
E_Shadowscastviewdistratio=1.3 ## 1.6 ""
E_Shadowsmaxtexres=1872 ## 1024 ""
E_Svoti_Lowspecmode=4 ## 1 ""
E_Svoti_Skycolormultiplier=-0.2 ## -1.0001 "Overall Lighting"
E_Svoti_Ssaoamount=1.5 ## 1 ""
E_Svoti_Voxelizeunderterrain=0 ## 1 ""
E_Terraindetailmaterialsviewdistz=120 ## 100 ""
E_Viewdistmin=10 ## 5 ""
E_Viewdistratio=150 ## 125 "150 Max Slider"
E_Volumetricfog=0 ## 0 "Volumetric Fog"
E_Wateroceanfft=0 ## 1 ""
Es_Maxphysdist=100 ## 200 ""
Es_Maxphysdistcloth=100 ## 300 ""
Log_Enableremoteconsole=0 ## 1 ""
Log_Writetofileverbosity=0 ## 1 ""
P_Num_Bodies_Large_Group=10 ## 100 ""
P_Num_Threads=7 ## 2 ""
R_Antialiasingmode=3 ## 2 ""
R_Antialiasingtaapattern=3 ## 1 ""
R_Antialiasingtaasharpening=0 ## 0.2 ""
R_Depthoffield=0 ## 2 ""
R_Drawnearzrange=0.1 ## 0.001 ""
R_Hdrvignetting=0 ## 1 ""
R_Motionblur=0 ## 2 ""
R_Motionblurquality=0 ## 2 ""
R_Multigpu=0 ## 1 ""
R_Rainamount=2 ## 1 ""
R_Raindistmultiplier=2.5 ## 2 ""
R_Rainmaxviewdist_Deferred=170 ## 150 ""
R_Ssdoamountambient=2 ## 1 ""
R_Ssdoamountreflection=5 ## 4 ""
R_Ssdohalfres=3 ## 2 ""
R_Ssdoradiusmin=0.04 ## 0.1 ""
R_Ssreflections=0 ## 1 ""
R_Ssreflhalfres=1 ## 0 ""
R_Supersampling=0 ## 1 ""
R_Terrainao=0 ## 7 ""
R_Texpreallocateatlases=1 ## 0 ""
R_Texturesstreamingresidencythrottle=0.8 ## 0.5 ""
R_Texturesstreamingresidencytime=60 ## 10 ""
R_Texturesstreampooldefragmentation=2 ## 2 ""
R_Usemergedposts=0 ## 1 ""
R_Volumetricfogtexdepth=16 ## 32 ""
R_Volumetricfogtexscale=20 ## 10 ""
R_Watervolumecaustics=0 ## 1 ""
S_Occlusionmaxdistance=150 ## 500 ""
Sys_Flash_Address_Space=131072 ## 65536 ""
Sys_Flash_Check_Filemodtime=1 ## 0 ""
Sys_Streaming_Cpu_Worker=7 ## 5 ""
Wh_Ai_Lod_Distancemax=160 ## "90,110,130"
Wh_Ai_Lod_Distancemin=130 ## "60,80,100"
Wh_Env_Raindiffusedarkening=0.3 ## 0.2 ""
Wh_Env_Raindropsspeedbase=3 ## 1.5 ""
Wh_Horse_Cameracentering=0 ## 0.2 ""
Wh_Pl_Showfirecursor=1 ## 0 ""

##
## Wh_Sequence_Fmod_Event_Name=Event:/Music/Music ##
## Wh_Snd_Audio_Xmls_Dir=/Libs/Gameaudio/ ##
Ca_Attachmentcullingration=450 ## 450
Ca_Clothblending=1 ## 1
Ca_Clothbypasssimulation=0 ## 0
Ca_Clothmaxchars=10 ## 10
Ca_Keepmodels=0 ## 0
Ca_Usedecals=0 ## 0
Ca_Usephysics=1 ## 1
E_Autoprecachecgf=1 ## 1
E_Brushes=1 ## 1
E_Charlodmin=0 ## 0
E_Clouds=1 ## 1
E_Coveragebuffer=1 ## 1
E_Coveragebufferearlyout=1 ## 1
E_Coveragebufferreproj=6 ## 6
E_Coveragebufferterrain=0 ## 0
E_Coveragebufferterrainlodshift=2 ## 2
E_Coveragebufferversion=2 ## 2
E_Cullvegactivation=50 ## 50
E_Decalsallowgamedecals=1 ## 1
E_Decalsdeffereddynamic=1 ## 1
E_Decalsdefferedstatic=1 ## 1
E_Decalsforcedeferred=0 ## 0
E_Decalslifetimescale=2 ## 2
E_Decalsoverlapping=1 ## 1
E_Decalsplacementtestareasize=0.08 ## 0.08
E_Decalsrange=20 ## 20
E_Deformableobjects=1 ## 1
E_Dissolve=2 ## 2
E_Dissolvedistband=3 ##
E_Dissolvedistmax=8 ##
E_Dissolvedistmin=2 ##
E_Dynamiclights=1 ## 1
E_Dynamiclightsmaxentitylights=16 ## 16
E_Fog=1 ## 1
E_Fogvolumes=1 ## 1
E_Fogvolumestiledinjection=1 ## 1
E_Foliagewindactivationdist=25 ## 25
E_Geomcaches=1 ## 1
E_Gi=0 ## 0
E_Giamount=0.6 ## 0.6
E_Gicache=7 ## 7
E_Giiterations=6 ## 6
E_Gimaxdistance=100 ## 100
E_Ginumcascades=1 ## 1
E_Gsmlodsnum=5 ## 5
E_Gsmrange=3 ## 3
E_Hwocclusioncullingwater=1 ## 1
E_Lightvolumes=1 ## 1
E_Lodcompmaxsize=6 ## 6
E_Lodmax=5 ## 5
E_Lodmin=0 ## 0
E_Lodminttris=300 ## 300
E_Lods=1 ## 1
E_Lodsforceuse=1 ## 1
E_Maxviewdistspeclerp=1 ## 1
E_Mergedmeshespool=16384 ## 16384
E_Mergedmeshesusespines=1 ## 1
E_Objfastregister=1 ## 1
E_Objquality=4 ## 4
E_Objshadowcastspec=7 ## 7
E_Occlusioncullingviewdistratio=1 ## 1
E_Particlesanimblend=1 ## 1
E_Particlescullagainstocclusionbuffer=1 ## 1
E_Particlesgi=1 ## 1
E_Particleslayeredupdatemul=5 ## 5
E_Particleslod=1 ## 1
E_Particlesmaxdrawscreen=2 ## 2
E_Particlesmaxscreenfill=160 ## 160
E_Particlesmindrawpixels=1 ## 1
E_Particlesobjectcollisions=2 ## 2
E_Particlespoolsize=16384 ## 16384
E_Particlespreload=0 ## 0
E_Particlesquality=4 ## 4
E_Particlesshadows=1 ## 1
E_Particlessoftintersect=1 ## 1
E_Particlessortquality=0 ## 0 
E_Particlesthread=1 ## 1
E_Physoceancell=0.5 ## 0.5
E_Precachelevel=0 ## 0
E_Preloaddecals=1 ## 1
E_Preloadmaterials=1 ## 1
E_Procvegetation=0 ## 0
E_Shadows=1 ## 1
E_Shadowsadaptscale=2.72 ## 2.72
E_Shadowsblendcascades=2 ## 2
E_Shadowscacheobjectlod=0 ## 0
E_Shadowscacherendercharacters=0 ## 0
E_Shadowscastviewdistratiolights=0.8 ## 0.8
E_Shadowscastviewdistratiomulinvis=0.6 ## 0.6
E_Shadowsclouds=1 ## 1
E_Shadowslodbiasfixed=0 ## 0
E_Shadowsonalphablend=0 ## 0
E_Shadowsonwater=0 ## 0
E_Shadowsperobject=0 ## 0
E_Shadowspoolsize=4096 ## 4096
E_Shadowsresscale=4 ## 4
E_Shadowsslopebias=1 ## 1
E_Shadowsslopebiashq=0.25 ## 0.25
E_Shadowstessellatecascades=1 ## 1
E_Shadowstessellatedlights=0 ## 0
E_Shadowsupdateviewdistratio=100 ## 100
E_Skybox=1 ## 1
E_Skyquality=1 ## 1
E_Skytype=1 ## 1
E_Skyupdaterate=1 ## 1
E_Statobjbufferrendertasks=1 ## 1
E_Statobjmerge=1 ## 1
E_Statobjpreload=1 ## 1
E_Streamcgf=1 ## 1
E_Streaminstancesminloadednodes=2048 ## 2048
E_Sun=1 ## 1
E_Sunangleclamp=20 ## 20
E_Svoti_Conemaxlength=35 ## 35
E_Svoti_Diffuse_Cache=0 ## 0
E_Svoti_Diffuseamplifier=1 ## 1
E_Svoti_Diffuseconewidth=6 ## 6
E_Svoti_Distantssaoamount=1 ## 1
E_Svoti_Dualtracing=0 ## 0
E_Svoti_Emissivemultiplier=4 ## 4
E_Svoti_Integrationmode=0 ## 0
E_Svoti_Rsmconemaxlength=12 ## 12
E_Svoti_Saturation=0.8 ## 0.8
E_Svoti_Skipnongilights=0 ## 0
E_Svoti_Specularamplifier=1 ## 1
E_Svovoxelpoolresolution=128 ## 128
E_Svovoxgenres=512 ## 512
E_Terrainao=0 ## 0
E_Terraindetailmaterialsviewdistxy=2048 ## 2048
E_Terrainlodratio=0.2 ## 0.2
E_Terraintexturelodratio=1 ## 1
E_Tessellation=1 ## 1
E_Tessellationmaxdistance=30 ## 30
E_Uberloddistanceratio=2.5 ## 2.5
E_Vegetationuseterraincolor=1 ## 1
E_Vegetationuseterraincolordistance=80 ## 80
E_Viewdistratiocustom=150 ## 150
E_Viewdistratiodetail=125 ## 125
E_Viewdistratiolights=80 ## 80
E_Viewdistratiovegetation=65 ## 65
E_Waterocean=1 ## 1
E_Wateroceanbottom=1 ## 1
E_Watertessellationamount=10 ## 10
E_Watertessellationamountx=85 ## 85
E_Watertessellationamounty=85 ## 85
E_Watertessellationswathwidth=10 ## 10
E_Watervolumes=1 ## 1
E_Waterwaves=0 ## 0
E_Waterwavestessellationamount=5 ## 5
E_Wind=1 ## 1
Es_Debrislifetimescale=1 ## 1
Es_Maxphysdistinvisible=25 ## 25
G_Breakage_Particles_Limit=160 ## 160
G_Radialblur=0 ## 1
G_Tree_Cut_Reuse_Dist=0 ## 0
Gpu_Particle_Physics=1 ## 1
I_Iceeffects=0 ## 0
I_Particleeffects=1 ## 1
I_Precache=1 ## 1
I_Rejecteffects=1 ## 1
Mfx_Enable=1 ## 1
Mfx_Enableattachedeffects=1 ## 1
Mfx_Enablefgeffects=1 ## 1
Mfx_Timeout=0.01 ## 0.01
P_Cull_Distance=100 ## 100
P_Gravity_Z=-9.81 ## -9.81
P_Max_Mc_Iters=6000 ## 6000
P_Max_Object_Splashes=3 ## 3
P_Max_Substeps=5 ## 5
P_Max_Substeps_Large_Group=5 ## 5
P_Splash_Dist0=7 ## 7
P_Splash_Dist1=30 ## 30
P_Splash_Force0=10 ## 10
P_Splash_Force1=100 ## 100
P_Splash_Vel0=4.5 ## 4.5
P_Splash_Vel1=10 ## 10
R_Batching=1 ## 1
R_Batchtype=1 ## 1
R_Beams=1 ## 1
R_Chromaticaberration=0 ## 0
R_Cloudsupdatealways=0 ## 0
R_Colorbits=32 ## 32
R_Colorgrading=2 ## 2
R_Colorgradingchartscache=0 ## 0
R_Conditionalrendering=0 ## 0
R_Customresmaxsize=4096 ## 4096
R_Deferredshadingarealights=1 ## 1
R_Deferredshadingfiltergbuffer=0 ## 0
R_Deferredshadingsss=1 ## 1
R_Deferredshadingtiled=2 ## 2
R_Deferredshadingtiledhairquality=1 ## 1
R_Depthoffielddilation=0 ## 0
R_Detaildistance=8 ## 8
R_Drawnearshadows=1 ## 1
R_Dyntexatlascloudsmaxsize=32 ## 32
R_Dyntexatlasdyntexsrcsize=16 ## 16
R_Dyntexatlasvoxterrainmaxsize=250 ## 250
R_Dyntexmaxsize=160 ## 160
R_Envcmresolution=2 ## 2
R_Envtexresolution=3 ## 3
R_Envtexupdateinterval=0.05 ## 0.05
R_Flarehqshafts=1 ## 1
R_Flares=0 ## 0
R_Flarestessellationratio=1 ## 1
R_Fogshadows=0 ## 0
R_Fogshadowsmode=0 ## 0
R_Fogshadowswater=1 ## 1
R_Hdrbloom=1 ## 1
R_Hdreyeadaptationmode=1 ## 1
R_Hdreyeadaptationspeed=3 ## 3
R_Hdrgrainamount=0 ## 0
R_Hdrrendering=1 ## 1
R_Imposterratio=1 ## 1
R_Lightpropagationvolumes=1 ## 1
R_Materialsbatching=1 ## 1
R_Mergerenderchunks=1 ## 1
R_Meshprecache=1 ## 1
R_Motionblurmaxviewdist=32 ## 32
R_Motionblurshutterspeed=125 ## 125 
R_Msaa=0 ## 0
R_Msaa_Quality=0 ## 0
R_Msaa_Samples=0 ## 0
R_Multithreaded=1 ## 1
R_Particleshalfres=0 ## 0
R_Particlestessellation=1 ## 1
R_Postprocesseffects=1 ## 1
R_Postprocessfilters=1 ## 1
R_Postprocessgamefx=1 ## 1
R_Postprocesshud3Dcache=0 ## 0
R_Rain=2 ## 2
R_Raindropseffect=1 ## 1
R_Rainoccludersizetreshold=10 ## 10
R_Refraction=1 ## 1
R_Shadowblur=3 ## 3
R_Shadowcastinglightsmaxcount=28 ## 28
R_Shadowjittering=2.5 ## 2.5
R_Shadowpoolmaxframes=5 ## 5
R_Shadowpoolmaxtimeslicedupdatesperframe=120 ## 120
R_Shadowsbias=0.00008 ## 8E-05,0.00008
R_Shadowscache=0 ## 0
R_Shadowscacheresolutions=6324,4214,2810,1872,624 ## 6324,4214,2810,1872,624
R_Shadowspcfiltering=1 ## 1
R_Shadowsscreenspace=2 ## 2
R_Shadowsuseclipvolume=1 ## 1
R_Sharpening=0 ## 0
R_Snow=2 ## 2
R_Ssdo=1 ## 1
R_Ssdoamountdirect=1.5 ## 1.5
R_Ssdocolorbleeding=1 ## 1
R_Ssdoradius=0.3 ## 0.3
R_Ssdoradiusmax=2 ## 2
R_Sunshafts=2 ## 2
R_Supersamplingfilter=0 ## 0
R_Terrainao_Fadedist=8 ## 8
R_Tessellationtrianglesize=8 ## 8
R_Texatlassize=2048 ## 2048
R_Texmaxanisotropy=16 ## 16
R_Texminanisotropy=16 ## 16
R_Texnoanisoalphatest=0 ## 0
R_Textureloddistanceratio=-1 ## -1
R_Texturesskiplowermips=0 ## 0
R_Texturesstreaming=1 ## 1
R_Texturesstreamingminusablemips=8 ## 8
R_Texturesstreamingmipbias=0 ## 0
R_Texturesstreamingresidencyenabled=1 ## 1
R_Texturesstreamingskipmips=0 ## 0
R_Transpdepthfixup=1 ## 1
R_Unlit=0 ## 0
R_Usedisplacementfactor=0.2 ## 0.2
R_Useesram=1 ## 1
R_Usehwskinning=1 ## 1
R_Usemateriallayers=2 ## 2
R_Useshadowspool=1 ## 1
R_Usezpass=2 ## 2
R_Volumetricfogdownscaledsunshadow=1 ## 1
R_Volumetricfogdownscaledsunshadowratio=1 ## 1
R_Volumetricfogminimumlightbulbsize=0.4 ## 0.4
R_Volumetricfogreprojectionblendfactor=0.9 ## 0.9
R_Volumetricfogreprojectionmode=1 ## 1
R_Volumetricfogsample=0 ## 0
R_Volumetricfogshadow=1 ## 1
R_Volumetricfogsunlightcorrection=1 ## 1
R_Watercaustics=0 ## 0
R_Watergodrays=0 ## 0
R_Waterreflections=1 ## 1
R_Waterreflectionsquality=0 ## 0
R_Watertessellationhw=1 ## 1
R_Waterupdatedistance=0.2 ## 0.2
R_Waterupdatefactor=0 ## 0
R_Waterupdatethread=5 ## 5
R_Watervolumecausticsdensity=256 ## 256
R_Watervolumecausticsmaxdist=35 ## 35
R_Watervolumecausticsres=1024 ## 1024
R_Watervolumecausticssnapfactor=1 ## 1
R_Zfightingdepthscale=0.995 ## 0.995
R_Zfightingextrude=0.001 ## 0.001
R_Zpassdepthsorting=1 ## 1
R_Zprepassmaxdist=16 ## 16
Sys_Budget_Soundcpu=15 ## 15
Sys_Flash_Allow_Reset_Mesh_Cache=1 ## 1
Sys_Flash_Curve_Tess_Error=2 ## 2
Sys_Flash_Edgeaa=1 ## 1
Sys_Flash_Newstencilclear=1 ## 1
Sys_Flash_Static_Pool_Size=0 ## 0
Sys_Flash_Use_Arenas=1 ## 1
Sys_Job_System_Enable=1 ## 1
Sys_Limit_Phys_Thread_Count=0 ## 0
Sys_Physics_Cpu=0 ## 0
Sys_Preload=0 ## 0
Sys_Streaming_Cpu=1 ## 1
T_Smoothing=1 ## 1
V_Vehicle_Quality=4 ## 4
Wh_Cc_Characterdetailreduction=0 ## 0
Wh_Cc_Lodforattachmentstreamout=6 ## 6
Wh_Cc_Lodforitemstreamoutbase=20 ## 20
Wh_Cs_Playerlockdisabled=0 ## 0
Wh_Env_Dirtcreationspeed=0.05 ## 0.05
Wh_Env_Dirtdryupspeed=0.05 ## 0.05
Wh_Env_Puddlecreationdelay=1000 ## 1000
Wh_Env_Puddlecreationspeed=0.005 ## 0.005
Wh_Env_Puddledryupdelay=0 ## 0 
Wh_Env_Puddledryupspeed=0.005 ## 0.005
Wh_Env_Puddlemaskmin=0 ## 0
Wh_Env_Raindropsamountmul=15 ## 15
Wh_Env_Raindropsspeedmul=7 ## 7
Wh_Env_Rainlayers=3 ## 3
Wh_Env_Rainwindstrength=10 ## 10
Wh_Horse_Collisionavoidance=0 ## 0
Wh_Item_Viewdistratio=100 ## 100
Wh_Pl_Fowenabled=1 ## 1
Wh_Pl_Fowvisibilityradius=100 ## 100
Wh_Player_Deepwaterlevel=0.85 ## 0.85
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
