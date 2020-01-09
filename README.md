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

ALC_ENUMERATE_ALL_EXT                  Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
ALC_ENUMERATION_EXT                    Source: http://openal.org/documentation/openal-1.1-specification.pdf
ALC_EXT_ASA                            Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_ASA_DISTORTION                 Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_ASA_ROGER_BEEP                 Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_CAPTURE                        Source: http://openal.org/documentation/openal-1.1-specification.pdf 
ALC_EXT_DEDICATED                      Source: http://icculus.org/alextreg/wiki/ALC_EXT_DEDICATED 
ALC_EXT_EFX                            Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
ALC_EXT_MAC_OSX                        Source: https://opensource.apple.com/source/OpenAL/OpenAL-48.7/Source/OpenAL/READ_ME?txt
ALC_EXT_OUTPUT_CAPTURER                Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_EXT_disconnect                     Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
ALC_EXT_thread_local_context           Source: http://kcat.strangesoft.net/openal-extensions/ 
ALC_LOKI_audio_channel                 Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
ALC_MAC_OSX_CONVERT_DATA_UPON_LOADING  Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
ALC_SOFT_device_clock                  Source: https://www.openal-soft.org/openal-extensions/ 
ALC_SOFT_HRTF                          Source: http://kcat.strangesoft.net/openal-extensions/ 
ALC_SOFT_loopback                      Source: http://kcat.strangesoft.net/openal-extensions/ 
ALC_SOFT_output_limiter                Source: https://www.openal-soft.org/openal-extensions/ 
ALC_SOFT_pause_device                  Source: http://kcat.strangesoft.net/openal-extensions/ 

AL Extensions
--------------

AL_EXT_ALAW                            Source: https://github.com/ioquake/ioq3/blob/master/code/AL/alext.h 
AL_EXT_BFORMAT                         Source: https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_EXPONENT_DISTANCE               Source: http://openal.org/documentation/openal-1.1-specification.pdf 
AL_EXT_IMA4                            Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_LINEAR_DISTANCE                 Source: http://openal.org/documentation/openal-1.1-specification.pdf 
AL_EXT_MCFORMATS                       Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_MULAW                           Source: https://github.com/ioquake/ioq3/blob/master/code/AL/alext.h 
AL_EXT_MULAW_BFORMAT                   Source: https://github.com/kcat/openal-soft/blob/master/include/AL/alext.h
AL_EXT_MULAW_MCFORMATS                 Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_OFFSET                          Source: http://openal.org/documentation/openal-1.1-specification.pdf 
AL_EXT_SOURCE_NOTIFICATIONS            Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
AL_EXT_SOURCE_RADIUS                   Source: http://icculus.org/alextreg/index.php?operation=op_showext&extname=AL_EXT_SOURCE_RADIUS
AL_EXT_SOURCE_SPATIALIZATION           Source: https://opensource.apple.com/source/OpenAL/OpenAL-56/Source/OpenAL/MacOSX_OALExtensions.h
AL_EXT_STATIC_BUFFER                   Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_STEREO_ANGLES                   Source: http://icculus.org/alextreg/wiki/AL_EXT_STEREO_ANGLES 
AL_EXT_buffer_sub_data                 Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_double                          Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_float32                         Source: http://icculus.org/alextreg/wiki/AL_EXT_float32 
AL_EXT_sample_buffer_object            Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_EXT_source_distance_model           Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_EXT_vorbis                          Source: http://icculus.org/alextreg/wiki/AL_EXT_vorbis 
AL_LOKI_IMA_ADPCM_format               Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_LOKI_WAVE_format                    Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_LOKI_quadriphonic                   Source: https://github.com/FrictionalGames/OALWrapper/blob/master/include/AL/alext.h
AL_SOFT_MSADPCM                        Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_block_alignment                Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_buffer_samples                 Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_buffer_sub_data                Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_deferred_updates               Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_direct_channels                Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_gain_clamp_ex                  Source: https://www.openal-soft.org/openal-extensions/ 
AL_SOFT_loop_points                    Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_source_latency                 Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_source_length                  Source: http://kcat.strangesoft.net/openal-extensions/ 
AL_SOFT_source_resampler               Source: https://www.openal-soft.org/openal-extensions/ 
AL_SOFT_source_spatialize              Source: https://www.openal-soft.org/openal-extensions/ 
