# RASPIAUDIO Pi Audio Drive

 Storage + Audio + Power in one HAT

Buy the product here :
 https://raspiaudio.com/product/pi5dpa/

 Installation tutorial here : 
 https://forum.raspiaudio.com/t/pi-audio-drive-shield-by-raspiaudio-installation-guide/884

These are ALSA configuration ("state") files for the RASPIAUDIO Pi Audio Drive sound card.


To load a state file, from the command line use:

    sudo alsactl restore -f <filename>

where `<filename>` is one of the following:

    Codec_Zero_AUXIN_record_and_HP_playback.state
    Codec_Zero_OnboardMIC_record_and_SPK_playback.state
    Codec_Zero_Playback_only.state
    Codec_Zero_StereoMIC_record_and_HP_playback.state
