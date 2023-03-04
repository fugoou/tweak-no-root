# Performance+ Without root

<p align="center">
	<img src="https://s4.bukalapak.com/img/4846047083/large/hp_kentang.jpg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>

how to access ADB ? [`HERE!`](https://developer.android.com/studio/command-line/adb?hl=id)

all in adb command ( according to each Android and each terminal ) just copy & paste

## 1. ( random ) maybe there are some fake strings and values ​​because I also fetched some strings and values ​​on YouTube lol ( it is not recommended to reboot because the string will be lost when rebooting )


```bash
setprop debug.MB.inner.running 24; setprop debug.MB.running 72; setprop debug.app.performance_restricted false; setprop debug.assert 1; setprop debug.atrace.app_number 1; setprop debug.atrace.tags.enableflags 0; setprop debug.audio.deep_buffer.media false; setprop debug.choreographer.callback  120; setprop debug.choreographer.skipwarning 16; setprop debug.choreographer.vsync false; setprop debug.composition.type dyn; setprop debug.cpu.cooling.callback_freq_limit 0; setprop debug.cpuprio 7; setprop debug.cpurend.vsync false; setprop debug.dev.ssrm.turbo true; setprop debug.disable.hwacc 0; setprop debug.disable.sched.pre_cooling true; setprop debug.disable_FragmentIndex true; setprop debug.disable_client_composition_cache 1; setprop debug.disable_sched_boost true; setprop debug.egl.force_fxaa false; setprop debug.egl.force_msaa false; setprop debug.egl.force_smaa false; setprop debug.egl.force_ssaa false; setprop debug.egl.force_taa false; setprop debug.egl.hw 1; setprop debug.egl.profiler 1; setprop debug.egl.swapinterval 1; setprop debug.egl.traceGpuCompletion 100; setprop debug.enable.gamed 0; setprop debug.enable.hwacc 1; setprop debug.enable.sglscale 1; setprop debug.enabletr true; setprop debug.fb.rgb565 1; setprop debug.forceAutoTextureCompression 1; setprop debug.force_rtl false; setprop debug.frame.pacing 120.0; setprop debug.fw.bservice_enable 1; setprop debug.gaming.mode_enable 1; setprop debug.gfx.driver 1; setprop debug.gl.hw 1; setprop debug.gl.swapinterval 0; setprop debug.gles.layers EGL_KHR_gl_texture_cubemap_image,EGL_KHR_gl_texture_3D_image,EGL_KHR_gl_renderbuffer_image; setprop debug.gpu.cooling.callback_freq_limit 0; setprop debug.gpu.mode swiftshader_indirect; setprop debug.gpu3D_MinClock 16632; setprop debug.gpuprio 7; setprop debug.gpurend.vsync false; setprop debug.gr.numframebuffers 3; setprop debug.gr.swapinterval 1; setprop debug.gralloc.enable_fb_ubwc 1; setprop debug.gralloc.gfx_ubwc_disable 0; setprop debug.gralloc.map_fb_memory 0; setprop debug.hal_client_domain hal_perf; setprop debug.hwc.bq_count 3; setprop debug.hwc.compose_level 0; setprop debug.hwc.disabletonemapping true; setprop debug.hwc.mdpThreshold 4.5; setprop debug.hwui.capture_skp_enabled 0; setprop debug.hwui.capture_skp_frames 2; setprop debug.hwui.disable_draw_defer true; setprop debug.hwui.disable_draw_reorder true; setprop debug.hwui.disable_vsync true; setprop debug.hwui.disabledither true; setprop debug.hwui.enable_partial_updates true; setprop debug.hwui.filter_test_overhead true; setprop debug.hwui.fps_divisor -1; setprop debug.hwui.level 2; setprop debug.hwui.overdraw false; setprop debug.hwui.refresh_rate_forced 120.0; setprop debug.hwui.render_dirty_regions false; setprop debug.hwui.renderer vulkan; setprop debug.hwui.show_dirty_regions false; setprop debug.hwui.show_non_rect_clip hide; setprop debug.hwui.skip_empty_damage true; setprop debug.hwui.target_cpu_freq_percent 100; setprop debug.hwui.target_cpu_time_percent 50; setprop debug.hwui.target_gpu_freq_percent 100; setprop debug.hwui.target_gpu_time_percent 100; setprop debug.hwui.target_power_time_percent 900; setprop debug.hwui.use_buffer_age true; setprop debug.hwui.use_gpu_pixel_buffers true; setprop debug.hwui.use_hint_manager true; setprop debug.ioprio 7; setprop debug.javafx.animation.frame 120.0; setprop debug.javafx.animation.framerate 120.0; setprop debug.javafx.animation.fullspeed true; setprop debug.kill_allocating_task 1; setprop debug.lldb-rpc-server 0; setprop debug.max_freq_limit 111300; setprop debug.mdlogger.Running 0; setprop debug.mdpcomp.4k2kSplit 1; setprop debug.mdpcomp.idletime -1; setprop debug.mdpcomp.logs 0; setprop debug.mdpcomp.maxlayer 3; setprop debug.media.codec2 1; setprop debug.min_freq_limit 111300; setprop debug.multicore.processing 1; setprop debug.oculus.refreshRate 120.0; setprop debug.overlayui.enable 1; setprop debug.perfhudes 1; setprop debug.performance.accoustic.force true; setprop debug.performance.cap uncapped; setprop debug.performance.disturb true; setprop debug.performance.tuning 1; setprop debug.performance_schema 1; setprop debug.performance_schema_max_memory_classes 300; setprop debug.performance_schema_max_socket_classes 30; setprop debug.profiler.target_performance_percent 100; setprop debug.qctwa.preservebuf 1; setprop debug.qsg_renderer 1; setprop debug.redroid.fps 120.0; setprop debug.renderengine.backend skiaglthreaded; setprop debug.renderer.process compound; setprop debug.renderer.process_compound true; setprop debug.renderthread.reduceopstasksplitting true; setprop debug.rs.default-CPU-buffer 10102098; setprop debug.rs.default-CPU-driver 1; setprop debug.rs.default-GPU-driver 1; setprop debug.rs.forcecompat 1; setprop debug.rs.max-freq 3800000; setprop debug.rs.max-temp_tolerance 0; setprop debug.rs.max-threads 8; setprop debug.rs.min-freq 3800000; setprop debug.rs.min-perf_percent 100; setprop debug.rs.min-threads 16; setprop debug.rs.precision rs_fp_full; setprop debug.rs.script 1; setprop debug.scenegraph.batching_performance 1; setprop debug.sched.colocate.enable 1; setprop debug.sdm.support_writeback 1; setprop debug.sf.auto_latch_unsignaled true; setprop debug.sf.ddms 1; setprop debug.sf.disable_backpressure 1; setprop debug.sf.disable_client_composition_cache 1; setprop debug.sf.disable_hwc 0; setprop debug.sf.dump 0; setprop debug.sf.early.app.duration 16600000; setprop debug.sf.early.sf.duration 16600000; setprop debug.sf.earlyGl.app.duration 16600000; setprop debug.sf.earlyGl.sf.duration 16600000; setprop debug.sf.early_app_phase_offset_ns 500000; setprop debug.sf.early_gl_app_phase_offset_ns 15000000; setprop debug.sf.early_gl_phase_offset_ns 3000000; setprop debug.sf.early_phase_offset_ns 500000; setprop debug.sf.enable_egl_backpressure 0; setprop debug.sf.enable_gl_backpressure 0; setprop debug.sf.enable_hgl 1; setprop debug.sf.enable_hwc_vds 1; setprop debug.sf.enable_transaction_tracing true; setprop debug.sf.frame_rate_multiple_threshold 120.0; setprop debug.sf.gpu_comp_tiling 1; setprop debug.sf.gpu_freq_index 1; setprop debug.sf.high_fps_early_gl_phase_offset_ns 650000; setprop debug.sf.high_fps_early_phase_offset_ns 6100000; setprop debug.sf.high_fps_late_app_phase_offset_ns 100000; setprop debug.sf.hw 1; setprop debug.sf.hwc.min.duration 0; setprop debug.sf.latch_unsignaled 0; setprop debug.sf.late.app.duration 16600000; setprop debug.sf.late.sf.duration 10500000; setprop debug.sf.max_igbp_list_size 65000; setprop debug.sf.min-frame_rate_multiple_threshold 60; setprop debug.sf.perf_fps_early_gl_phase_offset_ns 12000000; setprop debug.sf.phase_offset_threshold_for_next_vsync_ns 6100000; setprop debug.sf.predict_hwc_composition_strategy 1; setprop debug.sf.recomputecrop 0; setprop debug.sf.send_early_power_session_hint false; setprop debug.sf.send_late_power_session_hint false; setprop debug.sf.showbackground 0; setprop debug.sf.showcpu 0; setprop debug.sf.showfps 0; setprop debug.sf.showupdates 0; setprop debug.sf.swapinterval 0; setprop debug.sf.use_phase_offsets_as_durations 1; setprop debug.singlecore.processing 1; setprop debug.stagefright.c2inputsurface 0; setprop debug.stagefright.ccodec 1; setprop debug.stagefright.omx_default_rank 0; setprop debug.strncmp.property 3; setprop debug.surface_flinger.protected_contents true; setprop debug.surface_flinger.vsync_event_phase_offset_ns 2000000; setprop debug.surface_flinger.vsync_sf_event_phase_offset_ns 6000000; setprop debug.systemui.latency_tracking 0; setprop debug.systemuicompilerfilter speed; setprop debug.threadedOpt 1; setprop debug.tracing.screen_brightness 0.55456835; setprop debug.tracing.screen_state 2; setprop debug.vendor.nhmonitor.delay30dump false; setprop debug.vendor.nhmonitor.status true; setprop debug.vulkan.layers VK_KHR_shared_presentable_image,VK_KHR_android_surface,VK_KHR_buffer_device_address; setprop debug.wave.perfmonitor.mode 1
```


## 2. A little tweak system/secure/global

```bash
dumpsys deviceidle force-idle; settings put global device_idle_constants inactive_to=15000,sensing_to=0,locating_to=0,location_accuracy=20.0,motion_inactive_to=0,idle_after_inactive_to=0,idle_pending_to=60000,max_idle_pending_to=120000,idle_pending_factor=2.0,idle_to=900000,max_idle_to=86400000,idle_factor=2.0,min_time_to_alarm=600000,max_temp_app_whitelist_duration=10000,mms_temp_app_whitelist_duration=10000,sms_temp_app_whitelist_duration=10000; settings put system peak_refresh_rate R.integer.config_defaultPeakRefreshRate; settings put system min_refresh_rate 60.4; settings put secure refresh_rate_mode 2; settings put global zen_mode 0; settings put global sem_enchanced_cpu_responsiveness 1; settings put global enhanced_processing 1; settings put global restricted_device_performance 0,0; settings put global app_standby_enabled 1; settings put secure ui_night_mode 1; settings put system mcf_continuity 0; settings put global cached_apps_freezer 1; settings put system multicore_packet_scheduler 1; settings put system hdr_effect 1; settings put global activity_manager_constants max_cached_processes=190; settings put secure multi_press_timeout 250; settings put global enhanced_processing 1; settings put secure tap_duration_threshold 0.0; settings put global transition_animation_scale 0.6; settings put secure touch_blocking_period 0.0; /system/bin/device_config put activity_manager max_phantom_processes 2147483647; settings put global fstrim_mandatory_interval 86400000; settings put global enable_gpu_debug_layers 1; settings put global gpu_debug_layers VK_LAYER_KHRONOS_validation
```
```bash
settings put global gpu_debug_app <package_name>
```

* Example :
```bash
settings put global gpu_debug_app com.instagram.android
```
```bash 
settings put global gpu_debug_app com.instagram.android,com.whatsapp
```

* more information? Look [`here`](https://developer.arm.com/documentation/101545/0508/Before-you-begin/Android/Preparing-to-capture-non-debuggable-applications) & [`here`](https://forum.xda-developers.com/t/forcedoze-via-adb-optimized-doze-settings-no-root-required-via-adb-usb-debugging.3803732/)


## 2. driver game 11+


* for Android 11

```bash
settings put global game_driver_all_apps 1
```
```bash
settings put global game_driver_opt_out_apps 1
```
```bash
settings put global game_driver_opt_in_apps <package_name>
```


* Example :

```bash
settings put global game_driver_opt_in_apps com.archosaur.sea.dr.gp,com.nexon.bluearchive
```
```bash
settings put global game_driver_opt_in_apps com.archosaur.sea.dr.gp
```


* for Android 12 & 13 ( maybe )


```bash
settings put global updatable_driver_all_apps 1
```
```bash
settings put global updatable_driver_production_opt_out_apps 1
```
```bash
settings put global updatable_driver_production_opt_in_apps <package_name>
```


* Example :


```bash
settings put global updatable_driver_production_opt_in_apps com.archosaur.sea.dr.gp
```
```bash
settings put global updatable_driver_production_opt_in_apps com.archosaur.sea.dr.gp,com.nexon.bluearchive
```


## 2. zRam ( not recommended & not all phones can )


```bash
settings put global ram_expand_size 1
```
```bash
settings put global ram_expand_size_list 0,1,2,4,6,8,12,16
```


## 3. change downscale and mode app


* hard to explain you can see it [`here`](https://developer.android.com/games/gamemode/gamemode-interventions)


## 4. Android Dynamic Performance Framework


* Fixed performance mode :


```bash
cmd power set-fixed-performance-mode-enabled true
```

* more information ? look [`this`](https://developer.android.com/games/optimize/adpf?hl=id)


## 5. change pixel phone ( not recommended )


[`click this to download the app`](https://play.google.com/store/apps/details?id=com.tribalfs.pixels)


* code how to open it ?


```bash
pm grant com.tribalfs.pixels android.permission.WRITE_SECURE_SETTINGS
```
* how to use ?


click custom button > just change "width" to "1080" / "720" / "540" / "480" / "360" / "240" / "144"


* recommended width is "540"


## 6. change size dpi + resolution ( not recommended to combine with tutor number 5 )

"people say that the ideal resolution for games is 1080x2280"

ok here is a list of ideal resolutions for games

<p align="center">
	<img src="https://raw.githubusercontent.com/fugoou/tweak-no-root/main/Screenshot_20230304-191848.jpg">
</p>

for example, my phone has native resolution Width 720 x Height 1600, so to change it to the ideal game resolution we have to find the same Witdh as our phone

* Example :

```bash
wm size 720x1520
```
```bash
wm density 390
```

390 is default dpi but not recommended, this is adjusted to your convenience
 

## 8. Qboost app

* download : [`qboost`](http://m.qt6.com/XiaZai/99175.html)

recommended ?

set all to max power 🥴


## 9. Debloat

uninstall

```bash

pm uninstall -k --user 0 <package_name>

```

reinstall

```bash

cmd package install-existing <package_name>

```

* Example :

uninstall

```bash

pm uninstall -k --user 0 com.android.chrome

```

reinstall

```bash

cmd package install-existing com.android.chrome

```

* note : remove useless system apps
