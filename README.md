OpenAL extension repository
===========================

An update repository of OpenAL extensions (forked of the unmaintenanced repository openalext), with compile information available from different sources. As for now, a lot of these descriptions
are only stubs or extracts from headers.

If you have more detailed description of a specific OpenAL extension (or would like to provide
list of extensions available on a specific platform), please issue a pull request.

Extensions available on specific platforms
==========================================

OpenAL Soft 1.20.0
------------------

* AL_EXT_ALAW
* AL_EXT_BFORMAT
* AL_EXT_DOUBLE
* AL_EXT_EXPONENT_DISTANCE
* AL_EXT_FLOAT32
* AL_EXT_IMA4
* AL_EXT_LINEAR_DISTANCE
* AL_EXT_MCFORMATS
* AL_EXT_MULAW
* AL_EXT_MULAW_BFORMAT
* AL_EXT_MULAW_MCFORMATS
* AL_EXT_OFFSET
* AL_EXT_source_distance_model
* AL_EXT_SOURCE_RADIUS
* AL_EXT_STEREO_ANGLES
* AL_LOKI_quadriphonic
* AL_SOFT_block_alignment
* AL_SOFT_deferred_updates
* AL_SOFT_direct_channels
* AL_SOFTX_events
* AL_SOFTX_filter_gain_ex
* AL_SOFT_gain_clamp_ex
* AL_SOFT_loop_points
* AL_SOFT_MSADPCM
* AL_SOFTX_map_buffer
* AL_SOFT_source_latency
* AL_SOFT_source_length
* AL_SOFT_source_resampler
* AL_SOFT_source_spatialize
* ALC_ENUMERATE_ALL_EXT
* ALC_ENUMERATION_EXT
* ALC_EXT_CAPTURE
* ALC_EXT_DEDICATED
* ALC_EXT_disconnect
* ALC_EXT_EFX
* ALC_EXT_thread_local_context
* ALC_SOFT_device_clock
* ALC_SOFT_HRTF
* ALC_SOFT_loopback
* ALC_SOFT_output_limiter
* ALC_SOFT_pause_device

OpenAL (native), Mac OS X 10.9.5
--------------------------------

* AL_EXT_EXPONENT_DISTANCE
* AL_EXT_float32
* AL_EXT_LINEAR_DISTANCE
* AL_EXT_OFFSET
* AL_EXT_SOURCE_NOTIFICATIONS
* AL_EXT_STATIC_BUFFER
* ALC_ENUMERATION_EXT
* ALC_EXT_ASA
* ALC_EXT_ASA_DISTORTION
* ALC_EXT_ASA_ROGER_BEEP
* ALC_EXT_CAPTURE
* ALC_EXT_MAC_OSX

OpenAL (native), Mac OS X 10.10.5, 10.11.1
------------------------------------------

* AL_EXT_EXPONENT_DISTANCE
* AL_EXT_float32
* AL_EXT_LINEAR_DISTANCE
* AL_EXT_OFFSET
* AL_EXT_SOURCE_NOTIFICATIONS
* AL_EXT_SOURCE_SPATIALIZATION
* AL_EXT_STATIC_BUFFER
* ALC_ENUMERATION_EXT
* ALC_EXT_ASA
* ALC_EXT_ASA_DISTORTION
* ALC_EXT_ASA_ROGER_BEEP
* ALC_EXT_CAPTURE
* ALC_EXT_MAC_OSX

OpenAL (native), iOS 9.0
------------------------

* AL_EXT_EXPONENT_DISTANCE
* AL_EXT_LINEAR_DISTANCE
* AL_EXT_OFFSET
* AL_EXT_SOURCE_NOTIFICATIONS
* AL_EXT_SOURCE_SPATIALIZATION
* AL_EXT_STATIC_BUFFER
* ALC_ENUMERATION_EXT
* ALC_EXT_ASA
* ALC_EXT_CAPTURE
* ALC_EXT_MAC_OSX
* ALC_EXT_OUTPUT_CAPTURER

Sources
=======

ALC Extensions
--------------

Extension | Source
--------- | ------
ALC_ENUMERATE_ALL_EXT                  | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
ALC_ENUMERATION_EXT                    | http://openal.org/documentation/openal-1.1-specification.pdf
ALC_EXT_ASA                            | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_ASA_DISTORTION                 | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_ASA_ROGER_BEEP                 | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_CAPTURE                        | http://openal.org/documentation/openal-1.1-specification.pdf
ALC_EXT_DEDICATED                      | http://icculus.org/alextreg/wiki/action=printer&id=ALC_EXT_DEDICATED
ALC_EXT_DEFAULT_FILTER_ORDER           | https://javadoc.lwjgl.org/org/lwjgl/openal/EXTDefaultFilterOrder.html
ALC_EXT_EFX                            | https://www.openal-soft.org/misc-downloads/Effects%20Extension%20Guide.pdf
ALC_EXT_MAC_OSX                        | https://opensource.apple.com/source/OpenAL/OpenAL-48.7/Source/OpenAL/READ_ME?txt
ALC_EXT_OUTPUT_CAPTURER                | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_disconnect                     | http://icculus.org/alextreg/wiki/action=printer&id=ALC_EXT_Disconnect
ALC_EXT_thread_local_context           | http://kcat.strangesoft.net/openal-extensions/
ALC_LOKI_audio_channel                 | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_audio_channel
ALC_MAC_OSX_CONVERT_DATA_UPON_LOADING  | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_SOFT_device_clock                  | https://www.openal-soft.org/openal-extensions/
ALC_SOFT_HRTF                          | http://kcat.strangesoft.net/openal-extensions/
ALC_SOFT_loopback                      | http://kcat.strangesoft.net/openal-extensions/
ALC_SOFT_output_limiter                | https://www.openal-soft.org/openal-extensions/
ALC_SOFT_pause_device                  | http://kcat.strangesoft.net/openal-extensions/

AL Extensions
--------------

Extension | Source
--------- | ------
AL_EXT_ALAW                            | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_BFORMAT                         | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_BFORMAT
AL_EXT_EXPONENT_DISTANCE               | http://openal.org/documentation/openal-1.1-specification.pdf
AL_EXT_FOLDBACK                        | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_FOLDBACK
AL_EXT_IMA4                            | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_LINEAR_DISTANCE                 | http://openal.org/documentation/openal-1.1-specification.pdf
AL_EXT_MCFORMATS                       | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_MULAW                           | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_MULAW_BFORMAT                   | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_MULAW_MCFORMATS                 | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_OFFSET                          | http://openal.org/documentation/openal-1.1-specification.pdf
AL_EXT_SOURCE_NOTIFICATIONS            | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
AL_EXT_SOURCE_RADIUS                   | http://icculus.org/alextreg/index.php?operation=op_showext&extname=AL_EXT_SOURCE_RADIUS
AL_EXT_SOURCE_SPATIALIZATION           | https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
AL_EXT_STATIC_BUFFER                   | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_STEREO_ANGLES                   | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_STEREO_ANGLES
AL_EXT_buffer_sub_data                 | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_double                          | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_float32                         | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_Float32
AL_EXT_mp3                             | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_mp3
AL_EXT_sample_buffer_object            | https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_source_distance_model           | http://kcat.strangesoft.net/openal-extensions/
AL_EXT_vorbis                          | http://icculus.org/alextreg/wiki/action=printer&id=AL_EXT_vorbis
AL_LOKI_IMA_ADPCM_format               | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_IMA_ADPCM_format
AL_LOKI_WAVE_format                    | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_WAVE_format
AL_LOKI_attenuation_scale              | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_attenuation_scale
AL_LOKI_buffer_data_callback           | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_buffer_data_callback
AL_LOKI_play_position                  | http://scp.indiegames.us/fsodoc/ds_8cpp_source.html
AL_LOKI_quadriphonic                   | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_quadriphonic
AL_SOFT_MSADPCM                        | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_block_alignment                | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_buffer_samples                 | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_buffer_sub_data                | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_deferred_updates               | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_direct_channels                | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_gain_clamp_ex                  | https://www.openal-soft.org/openal-extensions/
AL_SOFT_loop_points                    | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_source_latency                 | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_source_length                  | http://kcat.strangesoft.net/openal-extensions/
AL_SOFT_source_resampler               | https://www.openal-soft.org/openal-extensions/
AL_SOFT_source_spatialize              | https://www.openal-soft.org/openal-extensions/
EAX-RAM                                | https://www.openal.org/documentation/OpenAL_Programmers_Guide.pdf
EAX                                    | http://icculus.org/alextreg/wiki/action=printer&id=EAX
EAX2.0                                 | http://icculus.org/alextreg/wiki/action=printer&id=EAX2.0
EAX3.0                                 | http://icculus.org/alextreg/wiki/action=printer&id=EAX3.0
EAX4.0                                 | http://icculus.org/alextreg/wiki/action=printer&id=EAX4.0
EAX5.0                                 | http://icculus.org/alextreg/wiki/action=printer&id=EAX5.0
EAX-AC3                                | http://icculus.org/alextreg/wiki/action=printer&id=EAX-AC3
EAX Unified                            |
EAX3.0EMULATED                         |
EAX4.0EMULATED                         |

ALUT Extensions
--------------

Extension | Source
--------- | ------
ALUT_LOKI_buffer_convert_data          | https://github.com/Raulshc/openal-svn-mirror/blob/master/OpenAL-Sample/doc/LOKI_buffer_convert_data
