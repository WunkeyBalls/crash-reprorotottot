# crash-reprorotottot

---- Minecraft Crash Report ----
// This doesn't make any sense!

Time: 2023-07-02 18:25:20
Description: Initializing game

java.lang.NoClassDefFoundError: Could not initialize class net.minecraft.client.renderer.RenderType
	at net.minecraft.client.gui.font.FontTexture.<init>(FontTexture.java:29) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontSet.m_232556_(FontSet.java:163) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.glyphs.SpecialGlyphs.m_213604_(SpecialGlyphs.java:53) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontSet.m_95071_(FontSet.java:53) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontManager.m_95009_(FontManager.java:43) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,re:classloading,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorFontManager,pl:mixin:A}
	at net.minecraft.Util.m_137469_(Util.java:368) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:kubejs-common.mixins.json:UtilMixin,pl:mixin:APP:yungsbridges.mixins.json:SuppressLogMixin,pl:mixin:APP:bettermineshafts.mixins.json:SuppressLogMixin,pl:mixin:APP:smoothboot.mixins.json:UtilMixin,pl:mixin:A}
	at net.minecraft.client.gui.font.FontManager.<init>(FontManager.java:43) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,re:classloading,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorFontManager,pl:mixin:A}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:482) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,pl:mixin:APP:combatroll.mixins.json:MinecraftClientMixin,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:resourcepackoverrides.common.mixins.json:client.MinecraftMixin,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:chat_heads.mixins.json:MinecraftMixin,pl:mixin:APP:chunkpregen.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftClientMixin,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin,pl:mixin:APP:memoryleakfix.mixins.json:hugeScreenshotLeak.Minecraft_screenshotMixin,pl:mixin:APP:memoryleakfix.mixins.json:targetEntityLeak.Minecraft_targetClearMixin,pl:mixin:APP:physicsmod.mixins.json:MixinMinecraft,pl:mixin:APP:physicsmod.mixins.json:cloth.MixinMinecraft,pl:mixin:APP:physicsmod.mixins.json:fabricapi.MixinMinecraft,pl:mixin:APP:inventorio.mixins.json:client.accessor.MinecraftClientAccessor,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:notenoughcrashes.mixins.json:client.MixinMinecraftClient,pl:mixin:APP:enhancedvisuals.mixins.json:MinecraftMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:betterthirdperson.mixins.json:MinecraftMixin,pl:mixin:APP:accurate_block_placement.mixins.json:MinecraftClientMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:mixin.dynamic_asset_generator.json:MinecraftMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:inventorio.mixins.json:client.MinecraftClientMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.m_239872_(Main.java:176) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:51) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:27) ~[fmlloader-1.19.2-43.2.14.jar%23101!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) [bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at net.minecraft.client.gui.font.FontTexture.<init>(FontTexture.java:29) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontSet.m_232556_(FontSet.java:163) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.glyphs.SpecialGlyphs.m_213604_(SpecialGlyphs.java:53) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontSet.m_95071_(FontSet.java:53) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading}
	at net.minecraft.client.gui.font.FontManager.m_95009_(FontManager.java:43) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,re:classloading,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorFontManager,pl:mixin:A}
	at net.minecraft.Util.m_137469_(Util.java:368) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:kubejs-common.mixins.json:UtilMixin,pl:mixin:APP:yungsbridges.mixins.json:SuppressLogMixin,pl:mixin:APP:bettermineshafts.mixins.json:SuppressLogMixin,pl:mixin:APP:smoothboot.mixins.json:UtilMixin,pl:mixin:A}
	at net.minecraft.client.gui.font.FontManager.<init>(FontManager.java:43) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,re:classloading,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorFontManager,pl:mixin:A}
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:482) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,pl:mixin:APP:combatroll.mixins.json:MinecraftClientMixin,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:resourcepackoverrides.common.mixins.json:client.MinecraftMixin,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:chat_heads.mixins.json:MinecraftMixin,pl:mixin:APP:chunkpregen.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftClientMixin,pl:mixin:APP:fallingleaves.mixins.json:MinecraftClientMixin,pl:mixin:APP:memoryleakfix.mixins.json:hugeScreenshotLeak.Minecraft_screenshotMixin,pl:mixin:APP:memoryleakfix.mixins.json:targetEntityLeak.Minecraft_targetClearMixin,pl:mixin:APP:physicsmod.mixins.json:MixinMinecraft,pl:mixin:APP:physicsmod.mixins.json:cloth.MixinMinecraft,pl:mixin:APP:physicsmod.mixins.json:fabricapi.MixinMinecraft,pl:mixin:APP:inventorio.mixins.json:client.accessor.MinecraftClientAccessor,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:notenoughcrashes.mixins.json:client.MixinMinecraftClient,pl:mixin:APP:enhancedvisuals.mixins.json:MinecraftMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:carryon.mixins.json:MinecraftMixin,pl:mixin:APP:betterthirdperson.mixins.json:MinecraftMixin,pl:mixin:APP:accurate_block_placement.mixins.json:MinecraftClientMixin,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:mixin.dynamic_asset_generator.json:MinecraftMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:APP:inventorio.mixins.json:client.MinecraftClientMixin,pl:mixin:A,pl:runtimedistcleaner:A}
-- Initialization --
Details:
	Modules: 
		ADVAPI32.dll:Advanced Windows 32 Base API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		COMCTL32.dll:User Experience Controls Library:6.10 (WinBuild.160101.0800):Microsoft Corporation
		CRYPT32.dll:Crypto API32:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTBASE.dll:Base cryptographic API DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		CRYPTSP.dll:Cryptographic Service Provider API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		CoreMessaging.dll:Microsoft CoreMessaging Dll:10.0.22621.1635 (WinBuild.160101.0800):Microsoft Corporation
		DBGHELP.DLL:Windows Image Helper:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		DEVOBJ.dll:Device Information Set DLL:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		DNSAPI.dll:DNS Client API DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		GDI32.dll:GDI Client DLL:10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		GLU32.dll:OpenGL Utility Library DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		IMM32.DLL:Multi-User Windows IMM32 API Client DLL:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		IPHLPAPI.DLL:IP Helper API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		KERNEL32.DLL:Windows NT BASE API Client DLL:10.0.22621.1485 (WinBuild.160101.0800):Microsoft Corporation
		KERNELBASE.dll:Windows NT BASE API Client DLL:10.0.22621.1485 (WinBuild.160101.0800):Microsoft Corporation
		MMDevApi.dll:MMDevice API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		MSCTF.dll:MSCTF Server DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		MpOav.dll:IOfficeAntiVirus Module:4.18.23050.5 (b79513656627928b5505482e6c59e640a77adba5):Microsoft Corporation
		NSI.dll:NSI User-mode interface DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		NTASN1.dll:Microsoft ASN.1 API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		OLEAUT32.dll:OLEAUT32.DLL:10.0.22621.608 (WinBuild.160101.0800):Microsoft Corporation
		Ole32.dll:Microsoft OLE for Windows:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		OpenAL.dll:Main implementation library:1.21.1:
		PSAPI.DLL:Process Status Helper:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		Pdh.dll:Windows Performance Data Helper DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		PhysXCommon_64.dll:PhysXCommon 64bit Dynamic Link Library:4.1.2.0:NVIDIA Corporation
		PhysXCooking_64.dll:PhysXCooking 64bit Dynamic Link Library:4.1.2.0:NVIDIA Corporation
		PhysXFoundation_64.dll:PhysXFoundation 64bit Dynamic Link Library:4.1.2.0:NVIDIA Corporation
		PhysXJniBindings_64.dll
		PhysX_64.dll:PhysX 64bit Dynamic Link Library:4.1.2.0:NVIDIA Corporation
		RPCRT4.dll:Remote Procedure Call Runtime:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		SETUPAPI.dll:Windows Setup API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		SHCORE.dll:SHCORE:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		SHELL32.dll:Windows Shell Common Dll:10.0.22621.1635 (WinBuild.160101.0800):Microsoft Corporation
		UMPDC.dll:User Mode Power Dependency Coordinator:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		USER32.dll:Multi-User Windows USER API Client DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		USERENV.dll:Userenv:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		VCRUNTIME140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		VERSION.dll:Version Checking and File Installation Libraries:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		WINHTTP.dll:Windows HTTP Services:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		WINMM.dll:MCI API DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		WINSTA.dll:Winstation Library:10.0.22621.1635 (WinBuild.160101.0800):Microsoft Corporation
		WINTRUST.dll:Microsoft Trust Verification APIs:10.0.22621.1485 (WinBuild.160101.0800):Microsoft Corporation
		WS2_32.dll:Windows Socket 2.0 32-Bit DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		WSOCK32.dll:Windows Socket 32-Bit DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		WTSAPI32.dll:Windows Remote Desktop Session Host Server SDK APIs:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		amsi.dll:Anti-Malware Scan Interface:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		apphelp.dll:Application Compatibility Client Library:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		awt.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		bcrypt.dll:Windows Cryptographic Primitives Library:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		bcryptPrimitives.dll:Windows Cryptographic Primitives Library:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		cfgmgr32.dll:Configuration Manager DLL:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		clbcatq.dll:COM+ Configuration Catalog:2001.12.10941.16384 (WinBuild.160101.0800):Microsoft Corporation
		combase.dll:Microsoft COM for Windows:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		cryptnet.dll:Crypto Network Related API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		dbgcore.DLL:Windows Core Debugging Helpers:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc.DLL:DHCP Client Service:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		dhcpcsvc6.DLL:DHCPv6 Client:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		dinput8.dll:Microsoft DirectInput:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		drvstore.dll:Driver Store API:10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		dwmapi.dll:Microsoft Desktop Window Manager API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		dxcore.dll:DXCore:10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		fwpuclnt.dll:FWP/IPsec User-Mode API:10.0.22621.1635 (WinBuild.160101.0800):Microsoft Corporation
		gdi32full.dll:GDI Client DLL:10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		glfw.dll:GLFW 3.4.0 DLL:3.4.0:GLFW
		icm32.dll:Microsoft Color Management Module (CMM):10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		inputhost.dll:InputHost:10.0.22621.1344 (WinBuild.160101.0800):Microsoft Corporation
		java.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		javaw.exe:OpenJDK Platform binary:17.0.3.0:Microsoft
		jemalloc.dll
		jimage.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		jli.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		jna3418563714067432282.dll:JNA native library:6.1.2:Java(TM) Native Access (JNA)
		jsvml.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		jvm.dll:OpenJDK 64-Bit server VM:17.0.3.0:Microsoft
		kernel.appcore.dll:AppModel API Host:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		lwjgl.dll
		lwjgl_opengl.dll
		lwjgl_stb.dll
		management.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		management_ext.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		msasn1.dll:ASN.1 Runtime APIs:10.0.22621.819 (WinBuild.160101.0800):Microsoft Corporation
		mscms.dll:Microsoft Color Matching System DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		msvcp140.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		msvcp_win.dll:Microsoft® C Runtime Library:10.0.22621.608 (WinBuild.160101.0800):Microsoft Corporation
		msvcrt.dll:Windows NT CRT DLL:7.0.22621.608 (WinBuild.160101.0800):Microsoft Corporation
		mswsock.dll:Microsoft Windows Sockets 2.0 Service Provider:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		napinsp.dll:E-mail Naming Shim Provider:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		ncrypt.dll:Windows NCrypt Router:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		net.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		nio.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		nlansp_c.dll:NLA Namespace Service Provider DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		ntdll.dll:NT Layer DLL:10.0.22621.1485 (WinBuild.160101.0800):Microsoft Corporation
		ntmarta.dll:Windows NT MARTA provider:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		nvoglv64.dll:NVIDIA Compatible OpenGL ICD:31.0.15.3168:NVIDIA Corporation
		nvspcap64.dll:NVIDIA Game Proxy:3.27.0.112:NVIDIA Corporation
		opengl32.dll:OpenGL Client DLL:10.0.22621.1635 (WinBuild.160101.0800):Microsoft Corporation
		perfos.dll:Windows System Performance Objects DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		pfclient.dll:SysMain Client:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		pnrpnsp.dll:PNRP Name Space Provider:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		powrprof.dll:Power Profile Helper DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		profapi.dll:User Profile Basic API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		rasadhlp.dll:Remote Access AutoDial Helper:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		rsaenh.dll:Microsoft Enhanced Cryptographic Provider:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		sechost.dll:Host for SCM/SDDL/LSA Lookup APIs:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		shlwapi.dll:Shell Light-weight Utility Library:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		sunmscapi.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		textinputframework.dll:"TextInputFramework.DYNLINK":10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		ucrtbase.dll:Microsoft® C Runtime Library:10.0.22621.608 (WinBuild.160101.0800):Microsoft Corporation
		uxtheme.dll:Microsoft UxTheme Library:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		vcruntime140_1.dll:Microsoft® C Runtime Library:14.29.30139.0 built by: vcwrkspc:Microsoft Corporation
		verify.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
		win32u.dll:Win32u:10.0.22621.1848 (WinBuild.160101.0800):Microsoft Corporation
		windows.storage.dll:Microsoft WinRT Storage API:10.0.22621.608 (WinBuild.160101.0800):Microsoft Corporation
		winrnr.dll:LDAP RnR Provider DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		wintypes.dll:Windows Base Types DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		wldp.dll:Windows Lockdown Policy:10.0.22621.900 (WinBuild.160101.0800):Microsoft Corporation
		wshbth.dll:Windows Sockets Helper DLL:10.0.22621.1778 (WinBuild.160101.0800):Microsoft Corporation
		wshunix.dll:AF_UNIX Winsock2 Helper DLL:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		xinput1_4.dll:Microsoft Common Controller API:10.0.22621.1 (WinBuild.160101.0800):Microsoft Corporation
		zip.dll:OpenJDK Platform binary:17.0.3.0:Microsoft
Stacktrace:
	at net.minecraft.client.main.Main.m_239872_(Main.java:176) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:51) ~[client-1.19.2-20220805.130853-srg.jar%23687!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:27) ~[fmlloader-1.19.2-43.2.14.jar%23101!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) [bootstraplauncher-1.1.2.jar:?] {}


-- System Details --
Details:
	Minecraft Version: 1.19.2
	Minecraft Version ID: 1.19.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.3, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 379752448 bytes (362 MiB) / 1914699776 bytes (1826 MiB) up to 4294967296 bytes (4096 MiB)
	CPUs: 12
	Processor Vendor: AuthenticAMD
	Processor Name: AMD Ryzen 5 5600X 6-Core Processor             
	Identifier: AuthenticAMD Family 25 Model 33 Stepping 0
	Microarchitecture: Zen 3
	Frequency (GHz): 3.69
	Number of physical packages: 1
	Number of physical CPUs: 6
	Number of logical CPUs: 12
	Graphics card #0 name: NVIDIA GeForce RTX 3050
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x2507
	Graphics card #0 versionInfo: DriverVersion=31.0.15.3168
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 2.13
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 16384.00
	Memory slot #1 clockSpeed (GHz): 2.13
	Memory slot #1 type: DDR4
	Memory slot #2 capacity (MB): 8192.00
	Memory slot #2 clockSpeed (GHz): 2.13
	Memory slot #2 type: DDR4
	Memory slot #3 capacity (MB): 16384.00
	Memory slot #3 clockSpeed (GHz): 2.13
	Memory slot #3 type: DDR4
	Virtual memory max (MB): 56235.21
	Virtual memory used (MB): 17097.95
	Swap memory total (MB): 7168.00
	Swap memory used (MB): 0.00
	JVM Flags: 4 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx4096m -Xms256m
	Launched Version: forge-43.2.14
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce RTX 3050/PCIe/SSE2 GL version 3.2.0 NVIDIA 531.68, NVIDIA Corporation
	Window size: <not initialized>
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	CPU: 12x AMD Ryzen 5 5600X 6-Core Processor 
	ModLauncher: 10.0.8+10.0.8+main.0ef7e830
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.3.jar eventbus PLUGINSERVICE 
		fmlloader-1.19.2-43.2.14.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.19.2-43.2.14.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.19.2-43.2.14.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.19.2-43.2.14.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.19.2-43.2.14.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.8.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.8.jar essential-loader TRANSFORMATIONSERVICE 
		modlauncher-10.0.8.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		javafml@null
		kotlinforforge@3.12.0
		lowcodefml@null
	Mod List: 
		YungsBetterDungeons-1.19.2-Forge-3.2.2.jar        |YUNG's Better Dungeons        |betterdungeons                |1.19.2-Forge-3.2.2  |COMMON_SET|Manifest: NOSIGNATURE
		open-parties-and-claims-forge-1.19.2-0.18.0.jar   |Open Parties and Claims       |openpartiesandclaims          |0.18.0              |COMMON_SET|Manifest: NOSIGNATURE
		UndergroundVillages-1.19.2-1.2.0.jar              |Underground Villages Mod      |underground_villages          |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		player-animation-lib-forge-1.0.2.jar              |Player Animator               |playeranimator                |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		dynamiccrosshair-5.6.2+1.19.2-forge.jar           |Dynamic Crosshair             |dynamiccrosshair              |5.6.2+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		majruszs-difficulty-1.19.2-1.7.7.jar              |Majrusz's Progressive Difficul|majruszsdifficulty            |1.7.7               |COMMON_SET|Manifest: NOSIGNATURE
		paragon-forge-3.0.2-1.19x.jar                     |Paragon                       |paragon                       |3.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		Entity_Collision_FPS_Fix-forge-1.19-2.0.0.0.jar   |Entity Collision FPS Fix      |entitycollisionfpsfix         |2.0.0.0             |COMMON_SET|Manifest: NOSIGNATURE
		modnametooltip-1.19-1.19.0.jar                    |Mod Name Tooltip              |modnametooltip                |1.19.0              |COMMON_SET|Manifest: NOSIGNATURE
		modernfix-forge-5.1.0+mc1.19.2.jar                |ModernFix                     |modernfix                     |5.1.0+mc1.19.2      |COMMON_SET|Manifest: NOSIGNATURE
		dustydecorations-1.0-1.19.2.jar                   |Dusty Decorations             |dustydecorations              |1.19.2-1.0.0        |COMMON_SET|Manifest: NOSIGNATURE
		YungsApi-1.19.2-Forge-3.8.9.jar                   |YUNG's API                    |yungsapi                      |1.19.2-Forge-3.8.9  |COMMON_SET|Manifest: NOSIGNATURE
		nocube's_farmers_compats_1.0.0_Forge_1.19.2.jar   |Farmer's Compats (by NoCube)  |nocubes_farmer_compats        |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		upgradednetherite_items-1.19.2-4.1.0.1-release.jar|Upgraded Netherite : Items    |upgradednetherite_items       |1.19.2-4.1.0.1-relea|COMMON_SET|Manifest: NOSIGNATURE
		ResourcePackOverrides-v4.0.4-1.19.2-Forge.jar     |Resource Pack Overrides       |resourcepackoverrides         |4.0.4               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		balm-forge-1.19.2-4.5.7.jar                       |Balm                          |balm                          |4.5.7               |COMMON_SET|Manifest: NOSIGNATURE
		chat_heads-0.10.16-forge-1.19.2.jar               |Chat Heads                    |chat_heads                    |0.10.16             |COMMON_SET|Manifest: NOSIGNATURE
		bbs-1.19.2-1.1.0-forge.jar                        |Better Block Sounds           |bbs                           |1.19.2-1.0          |COMMON_SET|Manifest: NOSIGNATURE
		cloth-config-8.2.88-forge.jar                     |Cloth Config v8 API           |cloth_config                  |8.2.88              |COMMON_SET|Manifest: NOSIGNATURE
		upgradednetherite-1.19.2-5.1.0.9-release.jar      |Upgraded Netherite            |upgradednetherite             |1.19.2-5.1.0.9-relea|COMMON_SET|Manifest: NOSIGNATURE
		structure_gel-1.19.2-2.7.2.jar                    |Structure Gel API             |structure_gel                 |2.7.2               |COMMON_SET|Manifest: NOSIGNATURE
		AdvancementPlaques-1.19.2-1.4.7.jar               |Advancement Plaques           |advancementplaques            |1.4.7               |COMMON_SET|Manifest: NOSIGNATURE
		TinySkeletons-v4.2.2-1.19.2-Forge.jar             |Tiny Skeletons                |tinyskeletons                 |4.2.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		tenshilib-1.19.2-1.6.15-forge.jar                 |TenshiLib                     |tenshilib                     |1.19.2-1.6.15       |COMMON_SET|Manifest: NOSIGNATURE
		combatroll-forge-1.1.5+1.19.jar                   |Combat Roll                   |combatroll                    |1.1.5+1.19          |COMMON_SET|Manifest: NOSIGNATURE
		morevillagers-forge-1.19-4.0.3.jar                |More Villagers                |morevillagers                 |4.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		BetterCompatibilityChecker-1.0.10-build.50+mc1.19.|Better Compatibility Checker  |bcc                           |1.0.10-build.50+mc1.|COMMON_SET|Manifest: NOSIGNATURE
		toughnessbar-1.19.2-8.jar                         |Toughness Bar                 |toughnessbar                  |1.19.2-8            |COMMON_SET|Manifest: NOSIGNATURE
		BlockRunner-v4.2.2-1.19.2-Forge.jar               |Block Runner                  |blockrunner                   |4.2.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		YungsBridges-1.19.2-Forge-3.1.0.jar               |YUNG's Bridges                |yungsbridges                  |1.19.2-Forge-3.1.0  |COMMON_SET|Manifest: NOSIGNATURE
		resourcefulconfig-forge-1.19.2-1.0.20.jar         |Resourcefulconfig             |resourcefulconfig             |1.0.20              |COMMON_SET|Manifest: NOSIGNATURE
		curios-forge-1.19.2-5.1.4.1.jar                   |Curios API                    |curios                        |1.19.2-5.1.4.1      |COMMON_SET|Manifest: NOSIGNATURE
		nocube's_better_blast_furnace_1.0.0_Forge_1.19.2.j|NoCube's Better Blast Furnace |ncbetterblastfurnace          |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		YungsExtras-1.19.2-Forge-3.1.0.jar                |YUNG's Extras                 |yungsextras                   |1.19.2-Forge-3.1.0  |COMMON_SET|Manifest: NOSIGNATURE
		PingHUD-2.0.jar                                   |PingHUD                       |pinghud                       |2.0                 |COMMON_SET|Manifest: NOSIGNATURE
		betterf3plus-1.0.jar                              |Better F3 Plus                |betterf3plus                  |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		Chunk Pregenerator-1.19-4.3.0.jar                 |Chunk Pregenerator            |chunkpregen                   |1.19-4.3.0          |COMMON_SET|Manifest: NOSIGNATURE
		queen_bee-3.0.3-1.19.2.jar                        |Queen Bee                     |queen_bee                     |3.0.3-1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		YSNS-FFQ-1.0.2.jar                                |You Shall Not Spawn!          |ysns                          |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		worldedit-mod-7.2.12.jar                          |WorldEdit                     |worldedit                     |7.2.12+6240-87f4ae1 |COMMON_SET|Manifest: NOSIGNATURE
		soulfired-1.19.2-3.1.0.0-final-forge.jar          |Soul fire'd                   |soulfired                     |3.1.0.0-final       |COMMON_SET|Manifest: NOSIGNATURE
		pluto-mc1.19.2-0.0.9.jar                          |Pluto                         |pluto                         |0.0.9               |COMMON_SET|Manifest: NOSIGNATURE
		OnlyLooking-1.19.2-4.1.1.jar                      |OnlyLooking                   |onlylooking                   |1.19.2-4.1.1        |COMMON_SET|Manifest: NOSIGNATURE
		FallingTree-1.19.2-3.10.0.jar                     |FallingTree                   |fallingtree                   |3.10.0              |COMMON_SET|Manifest: 3c:8e:df:6c:df:a6:2a:9f:af:64:ea:04:9a:cf:65:92:3b:54:93:0e:96:50:b4:52:e1:13:42:18:2b:ae:40:29
		ShinyHorses-1.19-1.2.jar                          |Shiny Horses Forge - Enchantab|shinyhorses                   |1.2                 |COMMON_SET|Manifest: NOSIGNATURE
		smallernetherportals-1.19.2-3.4.jar               |Smaller Nether Portals        |smallernetherportals          |3.4                 |COMMON_SET|Manifest: NOSIGNATURE
		FastLeafDecay-30.jar                              |FastLeafDecay                 |fastleafdecay                 |30                  |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterMineshafts-1.19.2-Forge-3.2.0.jar      |YUNG's Better Mineshafts      |bettermineshafts              |1.19.2-Forge-3.2.0  |COMMON_SET|Manifest: NOSIGNATURE
		veinmining-forge-1.1.1+1.19.2.jar                 |Vein Mining                   |veinmining                    |1.1.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		sliceanddice-forge-2.2.0.jar                      |Create Slice & Dice           |sliceanddice                  |0.0.0-dev           |ERROR     |Manifest: NOSIGNATURE
		Sophisticated_Wolves-1.19.2-4.1.2.jar             |Sophisticated Wolves Mod      |sophisticated_wolves          |4.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		Essential (forge_1.19.2).jar                      |Essential                     |essential                     |12933+deploy-staging|COMMON_SET|Manifest: NOSIGNATURE
		elytraslot-forge-6.1.1+1.19.2.jar                 |Elytra Slot                   |elytraslot                    |6.1.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		QuarkOddities-1.18.jar                            |Quark Oddities                |quarkoddities                 |1.18                |COMMON_SET|Manifest: NOSIGNATURE
		Kiwi-1.19.1-forge-8.3.4.jar                       |Kiwi                          |kiwi                          |8.3.4               |ERROR     |Manifest: NOSIGNATURE
		BetterAnimationsCollection-v4.0.5-1.19.2-Forge.jar|Better Animations Collection  |betteranimationscollection    |4.0.5               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		Fastload-Reforged-8.2.1+1.19.2.jar                |Fastload                      |fastload                      |8.2.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		jei-1.19.2-forge-11.6.0.1016.jar                  |Just Enough Items             |jei                           |11.6.0.1016         |COMMON_SET|Manifest: NOSIGNATURE
		UniversalBoneMeal-v4.2.0-1.19.2-Forge.jar         |Universal Bone Meal           |universalbonemeal             |4.2.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		AttributeFix-Forge-1.19.2-17.2.6.jar              |AttributeFix                  |attributefix                  |17.2.6              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		goblintraders-1.8.0-1.19.2.jar                    |Goblin Traders                |goblintraders                 |1.8.0               |COMMON_SET|Manifest: NOSIGNATURE
		caelus-forge-1.19.2-3.0.0.6.jar                   |Caelus API                    |caelus                        |1.19.2-3.0.0.6      |COMMON_SET|Manifest: NOSIGNATURE
		Stoneworks-v4.0.1-1.19.2-Forge.jar                |Stoneworks                    |stoneworks                    |4.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		Lighting Glow Squids 1.19.2.jar                   |Lighting Glow Squids          |lighting_glow_squids          |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		immersive_weathering-1.19.2-1.2.9-forge.jar       |Immersive Weathering          |immersive_weathering          |1.19.2-1.2.9        |COMMON_SET|Manifest: NOSIGNATURE
		Fallingleaves-1.19.1-1.3.1.jar                    |Falling Leaves                |fallingleaves                 |1.3.1               |COMMON_SET|Manifest: NOSIGNATURE
		StrawStatues-v4.0.10-1.19.2-Forge.jar             |Straw Statues                 |strawstatues                  |4.0.10              |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		badpackets-forge-0.2.1.jar                        |Bad Packets                   |badpackets                    |0.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		LibX-1.19.2-4.2.8.jar                             |LibX                          |libx                          |1.19.2-4.2.8        |COMMON_SET|Manifest: NOSIGNATURE
		deepslatetweaks-1.2-1.19.2.jar                    |Deepslate Tweaks              |deepslatetweaks               |1.2                 |COMMON_SET|Manifest: NOSIGNATURE
		burninthesun-forge-1.19.2-1.4.3.jar               |Burn in the Sun               |burninthesun                  |1.4.3               |COMMON_SET|Manifest: NOSIGNATURE
		starlight-1.1.1+forge.cf5b10b.jar                 |Starlight                     |starlight                     |1.1.1+forge.a3aea74 |COMMON_SET|Manifest: NOSIGNATURE
		BeeFix-1.19-1.0.7.jar                             |Bee Fix                       |beefix                        |1.0.7               |COMMON_SET|Manifest: NOSIGNATURE
		catalogue-1.7.0-1.19.2.jar                        |Catalogue                     |catalogue                     |1.7.0               |COMMON_SET|Manifest: NOSIGNATURE
		JeiTweaker-forge-1.19.2-4.0.12.jar                |JeiTweaker                    |jeitweaker                    |4.0.12              |COMMON_SET|Manifest: NOSIGNATURE
		dismountentity-1.19.2-3.0.jar                     |Dismount Entity               |dismountentity                |3.0                 |COMMON_SET|Manifest: NOSIGNATURE
		memoryleakfix-forge-1.17+-1.0.0.jar               |Memory Leak Fix               |memoryleakfix                 |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		CraftTweaker-forge-1.19.2-10.1.46.jar             |CraftTweaker                  |crafttweaker                  |10.1.46             |COMMON_SET|Manifest: NOSIGNATURE
		MissingWilds-forge-1.19-1.1.1.jar                 |Missing Wilds                 |missingwilds                  |0.0NONE             |COMMON_SET|Manifest: NOSIGNATURE
		improvedvanilla-forge-1.19.2-1.6.3.jar            |Improved Vanilla              |improvedvanilla               |1.19.2-1.6.3        |COMMON_SET|Manifest: NOSIGNATURE
		dynamicfps-reforged-1.0.jar                       |Dynamic FPS ReForged          |dynamicfps                    |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		More Wandering Trades 1.0.0 - 1.19.2.jar          |More Wandering Trades         |more_wandering_trades         |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		chalk-1.19.2-1.6.0.jar                            |Chalk                         |chalk                         |1.6.0               |COMMON_SET|Manifest: NOSIGNATURE
		block_limit_fix-1.0.3-forge.jar                   |Block Limit Fix               |block_limit_fix               |1.0.3-forge         |COMMON_SET|Manifest: NOSIGNATURE
		ArmorStatues-v4.0.4-1.19.2-Forge.jar              |Armor Statues                 |armorstatues                  |4.0.4               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		DynamicSurroundings-6.0.0.2.jar                   |§3Dynamic Surroundings: Resurr|dsurround                     |6.0.0.2             |COMMON_SET|Manifest: NOSIGNATURE
		radon-0.8.2.jar                                   |Radon                         |radon                         |0.8.2               |COMMON_SET|Manifest: NOSIGNATURE
		fastportals-1.0.2-forge.jar                       |Fast Portals                  |fastportalsforge              |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		voicechat-forge-1.19.2-2.4.13.jar                 |Simple Voice Chat             |voicechat                     |1.19.2-2.4.13       |COMMON_SET|Manifest: NOSIGNATURE
		soundphysics-forge-1.19.2-1.0.18.jar              |Sound Physics Remastered      |sound_physics_remastered      |1.19.2-1.0.18       |COMMON_SET|Manifest: NOSIGNATURE
		TerraBlender-forge-1.19.2-2.0.1.136.jar           |TerraBlender                  |terrablender                  |2.0.1.136           |COMMON_SET|Manifest: NOSIGNATURE
		physics-mod-2.12.3-mc-1.19.2-forge.jar            |Physics Mod                   |physicsmod                    |2.12.3              |COMMON_SET|Manifest: NOSIGNATURE
		MouseTweaks-forge-mc1.19-2.23.jar                 |Mouse Tweaks                  |mousetweaks                   |2.23                |COMMON_SET|Manifest: NOSIGNATURE
		majrusz-library-1.19.2-4.3.2.jar                  |Majrusz Library               |mlib                          |4.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		firstperson-forge-2.2.3-mc1.19.2.jar              |FirstPersonModel Mod          |firstpersonmod                |2.2.3-mc1.19.2      |COMMON_SET|Manifest: NOSIGNATURE
		spectrelib-forge-0.12.4+1.19.2.jar                |SpectreLib                    |spectrelib                    |0.12.4+1.19.2       |COMMON_SET|Manifest: NOSIGNATURE
		inventorio-1.19-forge-1.9.1.jar                   |Inventorio                    |inventorio                    |1.9.1               |COMMON_SET|Manifest: NOSIGNATURE
		kffmod-3.12.0.jar                                 |Kotlin For Forge              |kotlinforforge                |3.12.0              |COMMON_SET|Manifest: NOSIGNATURE
		notenoughanimations-forge-1.6.2-mc1.19.2.jar      |NotEnoughAnimations Mod       |notenoughanimations           |1.6.2               |COMMON_SET|Manifest: NOSIGNATURE
		flywheel-forge-1.19.2-0.6.8.a.jar                 |Flywheel                      |flywheel                      |0.6.8.a             |COMMON_SET|Manifest: NOSIGNATURE
		ecologics-forge-1.19.2-2.1.11.jar                 |Ecologics                     |ecologics                     |2.1.11              |COMMON_SET|Manifest: NOSIGNATURE
		Xaeros_Minimap_23.5.0_Forge_1.19.1.jar            |Xaero's Minimap               |xaerominimap                  |23.5.0              |COMMON_SET|Manifest: NOSIGNATURE
		polymorph-forge-0.46.3+1.19.2.jar                 |Polymorph                     |polymorph                     |0.46.3+1.19.2       |COMMON_SET|Manifest: NOSIGNATURE
		AutoRegLib-1.8.2-55.jar                           |AutoRegLib                    |autoreglib                    |1.8.2-55            |COMMON_SET|Manifest: NOSIGNATURE
		LeaveMyBarsAlone-v4.0.0-1.19.2-Forge.jar          |Leave My Bars Alone           |leavemybarsalone              |4.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		entityculling-forge-1.6.1-mc1.19.2.jar            |EntityCulling                 |entityculling                 |1.6.1               |COMMON_SET|Manifest: NOSIGNATURE
		DoubleSlabs-1.19-6.1.0.jar                        |Double Slabs                  |doubleslabs                   |6.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		canary-mc1.19.2-0.2.7.jar                         |Canary                        |canary                        |0.2.7               |COMMON_SET|Manifest: NOSIGNATURE
		effective_fg-1.3.4.jar                            |Effective (Forge)             |effective_fg                  |1.3.4               |COMMON_SET|Manifest: NOSIGNATURE
		cherryblossomgrotto-0.5.12-v1.19.2.jar            |Cherry Blossom Grotto         |cherryblossomgrotto           |0.5.12              |COMMON_SET|Manifest: NOSIGNATURE
		suggestion-tweaker-1.19.1-1.4.2-forge.jar         |Suggestion Tweaker            |suggestion_tweaker            |1.19.1-1.4.2        |COMMON_SET|Manifest: NOSIGNATURE
		FastFurnace-1.19.2-7.0.0.jar                      |FastFurnace                   |fastfurnace                   |7.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		upgradednetherite_ultimate-1.19.2-4.1.0.4-release.|Upgraded Netherite : Ultimerit|upgradednetherite_ultimate    |1.19.2-4.1.0.4-relea|COMMON_SET|Manifest: NOSIGNATURE
		DamageTilt-1.19-forge-0.1.2.jar                   |DamageTilt                    |damagetilt                    |0.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		PuzzlesLib-v4.4.3-1.19.2-Forge.jar                |Puzzles Lib                   |puzzleslib                    |4.4.3               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		FriendlyFire-Forge-1.19.2-14.0.4.jar              |FriendlyFire                  |friendlyfire                  |14.0.4              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Healing+Bed+1.19.2.jar                            |Healingbed                    |healingbed                    |1.19.2              |COMMON_SET|Manifest: NOSIGNATURE
		betterinvisibility-1.19.2-1.0.4.jar               |Better Invisibility           |betterinvisibility            |1.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		End's Phantasm - BETAv1.2.10.5 - 1.19.2.jar       |End's Phantasm                |phantasm                      |1.2.10.5            |COMMON_SET|Manifest: NOSIGNATURE
		responsiveshields-2.2.jar                         |Responsive Shields            |responsiveshields             |2.2                 |COMMON_SET|Manifest: NOSIGNATURE
		CompletionistsIndex-v4.0.0-1.19.2-Forge.jar       |Completionist's Index         |completionistsindex           |4.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		notenoughcrashes-4.2.1+1.19.2-forge.jar           |Not Enough Crashes            |notenoughcrashes              |4.2.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterWitchHuts-1.19.2-Forge-2.1.0.jar       |YUNG's Better Witch Huts      |betterwitchhuts               |1.19.2-Forge-2.1.0  |COMMON_SET|Manifest: NOSIGNATURE
		v_slab_compat-1.19.2-1.4.jar                      |Vertical Slabs Compat         |v_slab_compat                 |1.19.2-1.4          |COMMON_SET|Manifest: NOSIGNATURE
		netherportalfix-forge-1.19-10.0.1.jar             |NetherPortalFix               |netherportalfix               |10.0.1              |COMMON_SET|Manifest: NOSIGNATURE
		capybaramod-0.0.2-1.19.2.jar                      |Capybara Mod                  |capybaramod                   |0.0.2-1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		deepslatecutting-forge-1.5.0.jar                  |DeepslateCutting              |deepslatecutting_forge        |1.5.0               |COMMON_SET|Manifest: NOSIGNATURE
		UtilitiX-1.19.2-0.7.10.jar                        |UtilitiX                      |utilitix                      |1.19.2-0.7.10       |COMMON_SET|Manifest: NOSIGNATURE
		SuggestionProviderFix-1.19-1.0.0.jar              |Suggestion Provider Fix       |suggestionproviderfix         |1.19-1.0.0          |COMMON_SET|Manifest: NOSIGNATURE
		incontrol-1.19-7.1.9.jar                          |InControl                     |incontrol                     |1.19-7.1.9          |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterOceanMonuments-1.19.2-Forge-2.1.0.jar  |YUNG's Better Ocean Monuments |betteroceanmonuments          |1.19.2-Forge-2.1.0  |COMMON_SET|Manifest: NOSIGNATURE
		sophisticatedcore-1.19.2-0.5.77.346.jar           |Sophisticated Core            |sophisticatedcore             |1.19.2-0.5.77.346   |COMMON_SET|Manifest: NOSIGNATURE
		InsaneLib-1.7.5-mc1.19.2.jar                      |InsaneLib                     |insanelib                     |1.7.5               |COMMON_SET|Manifest: NOSIGNATURE
		HorseExpert-v4.0.0-1.19.2-Forge.jar               |Horse Expert                  |horseexpert                   |4.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		BowInfinityFix-1.19.x-forge-2.5.1.jar             |Bow Infinity Fix              |bowinfinityfix                |2.5.1               |COMMON_SET|Manifest: NOSIGNATURE
		villagernames-1.19.2-5.2.jar                      |Villager Names                |villagernames                 |5.2                 |COMMON_SET|Manifest: NOSIGNATURE
		ElytraPhysicsForge-1.1.1.jar                      |ElytraPhysicsForge            |elytra_physics                |1.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		XaerosWorldMap_1.30.6_Forge_1.19.1.jar            |Xaero's World Map             |xaeroworldmap                 |1.30.6              |COMMON_SET|Manifest: NOSIGNATURE
		JRFTL [1.19.1]-1.4.3.jar                          |JRFTL                         |jrftl                         |1.4.3               |COMMON_SET|Manifest: NOSIGNATURE
		EnhancedVisuals_FORGE_v1.5.9_mc1.19.2.jar         |EnhancedVisuals               |enhancedvisuals               |1.5.9               |COMMON_SET|Manifest: NOSIGNATURE
		Controlling-forge-1.19.2-10.0+7.jar               |Controlling                   |controlling                   |10.0+7              |COMMON_SET|Manifest: NOSIGNATURE
		Prism-1.19.1-1.0.2.jar                            |Prism                         |prism                         |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		Placebo-1.19.2-7.2.0.jar                          |Placebo                       |placebo                       |7.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		themissingvillages-2.0.0-1.19.2.jar               |The Missing Villages          |themissingvillages            |2.0.0-1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		mixinextras-forge-0.2.0-beta.8.jar                |MixinExtras                   |mixinextras                   |0.2.0-beta.8        |COMMON_SET|Manifest: NOSIGNATURE
		elytrabounce-1.19.2-1.0.2.jar                     |Elytra Bounce                 |elytrabounce                  |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		nocube's_better_smoker_1.0.0_forge_1.19.2.jar     |NoCube's Better Smoker        |nocubes_better_smoker         |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		Bookshelf-Forge-1.19.2-16.3.20.jar                |Bookshelf                     |bookshelf                     |16.3.20             |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		sophisticatedbackpacks-1.19.2-3.18.53.868.jar     |Sophisticated Backpacks       |sophisticatedbackpacks        |1.19.2-3.18.53.868  |COMMON_SET|Manifest: NOSIGNATURE
		kiwiboi-1.19.2-1.1.0.jar                          |Kiwi Boi                      |kiwiboi                       |1.19.2-1.1.0        |COMMON_SET|Manifest: NOSIGNATURE
		PlentyPlates-v4.0.0-1.19.2-Forge.jar              |Plenty Plates                 |plentyplates                  |4.0.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		jeed-1.19.2-2.1.4.jar                             |Just Enough Effect Description|jeed                          |1.19.2-2.1.4        |COMMON_SET|Manifest: NOSIGNATURE
		bygonenether-1.3.0-1.19.2.jar                     |Bygone Nether                 |bygonenether                  |1.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		shulkerbox-1.19.2-1.0.0.jar                       |Advanced Shulkerboxes         |shulkerbox                    |1.19.2-1.0.0        |COMMON_SET|Manifest: NOSIGNATURE
		FpsReducer2-forge-1.19.2-2.1.jar                  |FPS Reducer                   |fpsreducer                    |1.19.2-2.1          |COMMON_SET|Manifest: NOSIGNATURE
		carryon-forge-1.19.2-2.0.5.16.jar                 |Carry On                      |carryon                       |2.0.5.16            |COMMON_SET|Manifest: NOSIGNATURE
		cameraoverhaul-1.0-1.19.2.jar                     |Camera Overhaul               |cameraoverhaul                |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		PathToDirt-1.5.2-mc1.19.2.jar                     |Path To Dirt                  |pathtodirt                    |1.5.2               |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-flowerymooblooms-forge-mc1.19.2-1.0|Friends&Foes - Flowery Moobloo|flowerymooblooms              |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		shulkerboxslot-forge-5.0.0-beta.2+1.19.2.jar      |Shulker Box Slot              |shulkerboxslot                |5.0.0-beta.2+1.19.2 |COMMON_SET|Manifest: NOSIGNATURE
		mcw-bridges-2.1.0-mc1.19.2forge.jar               |Macaw's Bridges               |mcwbridges                    |2.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		FarmersDelight-1.19-1.2.1.jar                     |Farmer's Delight              |farmersdelight                |1.19-1.2.1          |COMMON_SET|Manifest: NOSIGNATURE
		ItShallNotTick-1.0.11-build.35.jar                |It Shall Not Tick             |itshallnottick                |1.0.11-build.35     |COMMON_SET|Manifest: NOSIGNATURE
		AmbientSounds_FORGE_v5.2.13_mc1.19.2.jar          |Ambient Sounds                |ambientsounds                 |5.2.13              |COMMON_SET|Manifest: NOSIGNATURE
		cant_sleep_clowns_will_eat_me-1.19.2-1.1.0.0.jar  |Can't Sleep Clowns Will Eat Me|cant_sleep_clowns_will_eat_me |1.1.0.0             |COMMON_SET|Manifest: NOSIGNATURE
		getittogetherdrops-forge-1.19.2-1.3.jar           |Get It Together, Drops!       |getittogetherdrops            |1.3                 |COMMON_SET|Manifest: NOSIGNATURE
		endrem_forge-5.2.1-R-1.19.X.jar                   |End Remastered                |endrem                        |5.2.1-R-1.19.2      |COMMON_SET|Manifest: NOSIGNATURE
		optifinefixer-1.0.jar                             |OptiFine Crash Fixer          |optifinefixer                 |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		EyesInTheDarkness-1.19-1.3.5.jar                  |Eyes in the Darkness          |eyesinthedarkness             |1.3.5               |COMMON_SET|Manifest: NOSIGNATURE
		dungeons_enhanced-1.19.2-4.1.jar                  |Dungeons Enhanced             |dungeons_enhanced             |4.1                 |COMMON_SET|Manifest: NOSIGNATURE
		wthit-forge-5.16.2.jar                            |wthit                         |wthit                         |5.16.2              |COMMON_SET|Manifest: NOSIGNATURE
		modelfix-1.8.jar                                  |Model Gap Fix                 |modelfix                      |1.8                 |COMMON_SET|Manifest: NOSIGNATURE
		CNB-1.19-1.5.4.jar                                |Creatures and Beasts          |cnb                           |1.5.4               |COMMON_SET|Manifest: NOSIGNATURE
		geckolib-forge-1.19-3.1.40.jar                    |GeckoLib                      |geckolib3                     |3.1.40              |COMMON_SET|Manifest: NOSIGNATURE
		leatheredboots-1.19.2-1.0.0.2-forge.jar           |Leathered Boots               |leatheredboots                |1.0.0.2             |COMMON_SET|Manifest: NOSIGNATURE
		cullleaves-forge-3.0.1.jar                        |CullLeaves                    |cullleaves                    |3.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		midnightlib-1.0.0-forge.jar                       |MidnightLib                   |midnightlib                   |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		collective-1.19.2-6.62.jar                        |Collective                    |collective                    |6.62                |COMMON_SET|Manifest: NOSIGNATURE
		AlmostBedtime_v2.0-1.19.2.jar                     |Almost Bedtime                |almost_bedtime                |2.0-1.19.2          |COMMON_SET|Manifest: NOSIGNATURE
		BetterThirdPerson-Forge-1.19-1.9.0.jar            |Better Third Person           |betterthirdperson             |1.9.0               |COMMON_SET|Manifest: NOSIGNATURE
		NightConfigFixes-v4.0.7-1.19.2-Forge.jar          |Night Config Fixes            |nightconfigfixes              |4.0.7               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		accurate_block_placement-1.19.2_1.0.jar           |Accurate Block Placement      |accurate_block_placement      |1.19.2_1.0          |COMMON_SET|Manifest: NOSIGNATURE
		starterkit-1.19.2-5.2.jar                         |Starter Kit                   |starterkit                    |5.2                 |COMMON_SET|Manifest: NOSIGNATURE
		eatinganimation-1.19-3.2.0.jar                    |Eating Animation              |eatinganimation               |3.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		forge-1.19.2-43.2.14-universal.jar                |Forge                         |forge                         |43.2.14             |COMMON_SET|Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		wthitharvestability-mc1.19.2-2.1.0.jar            |WTHIT Harvestability          |wthitharvestability           |2.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		client-1.19.2-20220805.130853-srg.jar             |Minecraft                     |minecraft                     |1.19.2              |COMMON_SET|Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		Shields+-1.3.2-mc1.19.2.jar                       |ShieldsPlus                   |shieldsplus                   |1.3.2-mc1.19.2      |COMMON_SET|Manifest: NOSIGNATURE
		appleskin-forge-mc1.19-2.4.2.jar                  |AppleSkin                     |appleskin                     |2.4.2+mc1.19        |COMMON_SET|Manifest: NOSIGNATURE
		deeperdarker-forge-1.1.6-forge.jar                |Deeper and Darker             |deeperdarker                  |1.1.6               |COMMON_SET|Manifest: NOSIGNATURE
		architectury-6.5.85-forge.jar                     |Architectury                  |architectury                  |6.5.85              |COMMON_SET|Manifest: NOSIGNATURE
		AI-Improvements-1.19.2-0.5.2.jar                  |AI-Improvements               |aiimprovements                |0.5.2               |COMMON_SET|Manifest: NOSIGNATURE
		inventoryessentials-forge-1.19-5.0.2.jar          |Inventory Essentials          |inventoryessentials           |5.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		Towns-and-Towers-v.1.10-_FORGE-1.19.2_.jar        |Towns and Towers              |t_and_t                       |1.10                |COMMON_SET|Manifest: NOSIGNATURE
		yeetusexperimentus-1.0.1-build.2+mc1.19.1.jar     |Yeetus Experimentus           |yeetusexperimentus            |1.0.1-build.2+mc1.19|COMMON_SET|Manifest: NOSIGNATURE
		shulkerboxtooltip-forge-3.2.2+1.19.2.jar          |ShulkerBoxTooltip             |shulkerboxtooltip             |3.2.2+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		GameMenuModOption-1.19-1.18.jar                   |Game Menu Mod Option          |gamemenumodoption             |1.18                |COMMON_SET|Manifest: NOSIGNATURE
		smartcompletion-1.19.3-forge-1.0.1.jar            |Smart Completion              |smartcompletion               |1.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		effortlessbuilding-1.19.2-3.2.jar                 |Effortless Building           |effortlessbuilding            |3.2                 |ERROR     |Manifest: NOSIGNATURE
		TradingPost-v4.2.0-1.19.2-Forge.jar               |Trading Post                  |tradingpost                   |4.2.0               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		majruszs-accessories-1.19.2-1.2.2.jar             |Majrusz's Accessories         |majruszsaccessories           |1.2.2               |COMMON_SET|Manifest: NOSIGNATURE
		rhino-forge-1902.2.2-build.268.jar                |Rhino                         |rhino                         |1902.2.2-build.268  |COMMON_SET|Manifest: NOSIGNATURE
		kubejs-forge-1902.6.0-build.142.jar               |KubeJS                        |kubejs                        |1902.6.0-build.142  |COMMON_SET|Manifest: NOSIGNATURE
		biomemakeover-FORGE-1.19.2-1.6.4.jar              |Biome Makeover                |biomemakeover                 |1.19.2-1.6.4        |COMMON_SET|Manifest: NOSIGNATURE
		spiderstpo-1.19.2-2.0.4.jar                       |Nyf's Spiders 2.0             |spiderstpo                    |2.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		callablehorses-1.19.2-1.2.2.3.jar                 |Callable Horses               |callablehorses                |1.2.2.3             |COMMON_SET|Manifest: 8c:03:ac:7d:21:62:65:e2:83:91:f3:22:57:99:ed:75:78:1e:db:de:03:99:ef:53:3b:59:95:18:01:bc:84:a9
		InvMove-1.19-0.8.2-Forge.jar                      |InvMove                       |invmove                       |0.8.2               |COMMON_SET|Manifest: NOSIGNATURE
		create-1.19.2-0.5.1.b.jar                         |Create                        |create                        |0.5.1.b             |ERROR     |Manifest: NOSIGNATURE
		kubejs-create-forge-1902.2.4-build.9.jar          |KubeJS Create                 |kubejs_create                 |1902.2.4-build.9    |COMMON_SET|Manifest: NOSIGNATURE
		waystones-forge-1.19.2-11.4.0.jar                 |Waystones                     |waystones                     |11.4.0              |ERROR     |Manifest: NOSIGNATURE
		FastSuite-1.19.2-4.1.0.jar                        |Fast Suite                    |fastsuite                     |4.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		Clumps-forge-1.19.2-9.0.0+14.jar                  |Clumps                        |clumps                        |9.0.0+14            |COMMON_SET|Manifest: NOSIGNATURE
		comforts-forge-6.0.5+1.19.2.jar                   |Comforts                      |comforts                      |6.0.5+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		Tumbleweed-forge-1.19.2-0.5.3.jar                 |Tumbleweed                    |tumbleweed                    |0.5.3               |COMMON_SET|Manifest: NOSIGNATURE
		alternate-current-mc1.19-1.7.0.jar                |Alternate Current             |alternate_current             |1.7.0               |COMMON_SET|Manifest: NOSIGNATURE
		configured-2.1.1-1.19.2.jar                       |Configured                    |configured                    |2.1.1               |COMMON_SET|Manifest: NOSIGNATURE
		Decorative Blocks-forge-1.19.2-3.0.0.jar          |Decorative Blocks             |decorative_blocks             |3.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		VanillaTweaks-forge-1.19.2-1.5.66.jar             |VanillaTweaks                 |vanillatweaks                 |1.5.66              |COMMON_SET|Manifest: NOSIGNATURE
		fastentitytransfer-forge-1.19.x-1.2.1.jar         |Fast Entity Transfer          |fastentitytransfer            |1.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		lazydfu-1.19-1.0.2.jar                            |LazyDFU                       |lazydfu                       |0.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		everycomp-1.19.2-2.4.12.jar                       |Every Compat                  |everycomp                     |1.19.2-2.4.12       |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterDesertTemples-1.19.2-Forge-2.2.2.jar   |YUNG's Better Desert Temples  |betterdeserttemples           |1.19.2-Forge-2.2.2  |COMMON_SET|Manifest: NOSIGNATURE
		Charms1.16-1.19.2-1.2.1.jar                       |Charms                        |charms                        |1.19.2-1.2.1        |COMMON_SET|Manifest: NOSIGNATURE
		netherdepthsupgrade-3.0.0-1.19.2.jar              |Nether Depths Upgrade         |netherdepthsupgrade           |3.0.0-1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		blueprint-1.19.2-6.1.2.jar                        |Blueprint                     |blueprint                     |6.1.2               |ERROR     |Manifest: NOSIGNATURE
		woodworks-1.19.2-2.2.1.jar                        |Woodworks                     |woodworks                     |2.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		3dskinlayers-forge-1.5.2-mc1.19.1.jar             |3dSkinLayers                  |skinlayers3d                  |1.5.2               |COMMON_SET|Manifest: NOSIGNATURE
		TravelersTitles-1.19.2-Forge-3.1.2.jar            |Traveler's Titles             |travelerstitles               |1.19.2-Forge-3.1.2  |COMMON_SET|Manifest: NOSIGNATURE
		toofast-1.19-0.2.2.4.jar                          |Too Fast                      |toofast                       |0.2.2.4             |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-forge-mc1.19.2-1.8.3.jar           |Friends&Foes                  |friendsandfoes                |1.8.3               |COMMON_SET|Manifest: NOSIGNATURE
		horsecombatcontrols-1.19.2-1.0.1.jar              |Horse Combat Controls         |horsecombatcontrols           |1.19.2-1.0.1        |COMMON_SET|Manifest: NOSIGNATURE
		simplyswords-forge-1.47.0-1.19.2.jar              |Simply Swords                 |simplyswords                  |1.47.0-1.19.2       |COMMON_SET|Manifest: NOSIGNATURE
		fxcontrol-1.19-4.0.11.jar                         |FxControl                     |fxcontrol                     |1.19-4.0.11         |COMMON_SET|Manifest: NOSIGNATURE
		EnchantmentDescriptions-Forge-1.19.2-13.0.14.jar  |EnchantmentDescriptions       |enchdesc                      |13.0.14             |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		dynamic_asset_generator-forge-1.19.2-1.2.0.jar    |DynamicAssetGenerator         |dynamic_asset_generator       |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		moonlight-1.19.2-2.2.43-forge.jar                 |Moonlight Library             |moonlight                     |1.19.2-2.2.43       |COMMON_SET|Manifest: NOSIGNATURE
		smarterfarmers-1.19.2-1.7.1.jar                   |Smarter Farmers               |smarterfarmers                |1.19.2-1.7.1        |COMMON_SET|Manifest: NOSIGNATURE
		Blood And Stuff FORGE 1.19.2.jar                  |Blood Particles (Blood And Stu|blood_and_stuff               |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		ToolBelt-1.19.2-1.19.7.jar                        |Tool Belt                     |toolbelt                      |1.19.7              |COMMON_SET|Manifest: NOSIGNATURE
		Salju-Ladders-2.2.1.jar                           |Better Ladders                |salju_ladders                 |2.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		Wooled-Boots-v1.4.1-FORGE-mc1.19.1.jar            |Wooled Boots                  |wooledboots                   |1.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		bettersafebed-forge-1.19-4.jar                    |Better Safe Bed               |bettersafebed                 |4                   |COMMON_SET|Manifest: NOSIGNATURE
		friendsandfoes-beekeeperhut-forge-mc1.19.2-1.2.0.j|Friends&Foes - Beekeeper Hut  |beekeeperhut                  |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		CreativeCore_FORGE_v2.9.4_mc1.19.2.jar            |CreativeCore                  |creativecore                  |2.9.3               |COMMON_SET|Manifest: NOSIGNATURE
		smoothboot(reloaded)-mc1.19.2-0.0.2.jar           |Smooth Boot (Reloaded)        |smoothboot                    |0.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		plushies-1.2-1.19.2.jar                           |Plushie Mod                   |plushies                      |1.2                 |COMMON_SET|Manifest: NOSIGNATURE
		Iceberg-1.19.2-forge-1.1.4.jar                    |Iceberg                       |iceberg                       |1.1.4               |COMMON_SET|Manifest: NOSIGNATURE
		Quark-3.4-405.jar                                 |Quark                         |quark                         |3.4-405             |COMMON_SET|Manifest: NOSIGNATURE
		supplementaries-1.19.2-2.3.20.jar                 |Supplementaries               |supplementaries               |1.19.2-2.3.20       |ERROR     |Manifest: NOSIGNATURE
		suppsquared-1.19.2-1.1.1.jar                      |Supplementaries Squared       |suppsquared                   |1.19.2-1.1.1        |COMMON_SET|Manifest: NOSIGNATURE
		FastWorkbench-1.19.2-7.1.3.jar                    |Fast Workbench                |fastbench                     |7.1.3               |COMMON_SET|Manifest: NOSIGNATURE
		immersive_paintings-0.6.1+1.19.2-forge.jar        |Immersive Paintings           |immersive_paintings           |0.6.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		DiagonalFences-v4.2.5-1.19.2-Forge.jar            |Diagonal Fences               |diagonalfences                |4.2.5               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		UniversalEnchants-v4.2.15-1.19.2-Forge.jar        |Universal Enchants            |universalenchants             |4.2.15              |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		TrampleNoMore-Forge-1.19.2-9.0.1.jar              |TrampleNoMore                 |tramplenomore                 |9.0.1               |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Blocks + 1.19 - 1.5.1.jar                         |Blocks +                      |blocksplus                    |1.5.1               |COMMON_SET|Manifest: NOSIGNATURE
		upgradedcore-1.19.2-4.1.0.1-release.jar           |Upgraded Core                 |upgradedcore                  |1.19.2-4.1.0.1-relea|COMMON_SET|Manifest: NOSIGNATURE
		BetterTridents-v4.0.2-1.19.2-Forge.jar            |Better Tridents               |bettertridents                |4.0.2               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		creeperoverhaul-2.0.9-forge.jar                   |Creeper Overhaul              |creeperoverhaul               |2.0.9               |COMMON_SET|Manifest: NOSIGNATURE
		ferritecore-5.0.3-forge.jar                       |Ferrite Core                  |ferritecore                   |5.0.3               |COMMON_SET|Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		Enhanced_Celestials-forge-1.19.2-2.1.0.6.jar      |Enhanced Celestials           |enhancedcelestials            |2.1.0.6             |COMMON_SET|Manifest: NOSIGNATURE
		CorgiLib-forge-1.19.2-1.0.0.34.jar                |CorgiLib                      |corgilib                      |1.0.0.34            |COMMON_SET|Manifest: NOSIGNATURE
		betterlily-1.2.0.jar                              |Better Lily Pads              |betterlily                    |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		charmofundying-forge-6.2.1+1.19.2.jar             |Charm of Undying              |charmofundying                |6.2.1+1.19.2        |COMMON_SET|Manifest: NOSIGNATURE
		betterf3-1.0.jar                                  |Better F3                     |betterf3                      |1.0                 |COMMON_SET|Manifest: NOSIGNATURE
		majruszs-enchantments-1.19.2-1.9.0.jar            |Majrusz's Enchantments        |majruszsenchantments          |1.9.0               |COMMON_SET|Manifest: NOSIGNATURE
		ArmorSoundTweak-6.0.0-forge.jar                   |Armor Sound Tweak             |armorsoundtweak               |6.0.0               |COMMON_SET|Manifest: 42:2c:5e:4c:e2:f5:d1:07:7f:aa:29:ae:31:88:80:0c:b1:a6:87:6b:6a:2d:0f:67:57:e4:5a:4a:26:73:31:ac
		improvedmobs-1.19-1.11.0-forge.jar                |Improved Mobs Mod             |improvedmobs                  |1.19-1.11.0         |COMMON_SET|Manifest: NOSIGNATURE
		overloadedarmorbar-1.19.3-7.1.jar                 |Overloaded Armor Bar          |overloadedarmorbar            |1.19.3-7.1          |COMMON_SET|Manifest: NOSIGNATURE
		OverflowingBars-v4.0.1-1.19.2-Forge.jar           |Overflowing Bars              |overflowingbars               |4.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		loadmyresources_forge_1.0.4_MC_1.19-1.19.2.jar    |Load My Resources             |loadmyresources               |1.0.4               |COMMON_SET|Manifest: NOSIGNATURE
		UndeadUnleashed-1.1.1-1.19.2.jar                  |Undead Unleashed              |undead_unleashed              |1.1.0               |COMMON_SET|Manifest: NOSIGNATURE
	Flywheel Backend: Uninitialized
	Crash Report UUID: a8c3893a-e74b-40c0-981c-1bc4a8f81f8e
	FML: 43.2
	Forge: net.minecraftforge:43.2.14
	Suspected Mods: None
