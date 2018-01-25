### ACE Stream Media ver. 3.1.24.2 ARMv7 (LibreELEC)

ACE Stream Media this is an innovative media platform of a new generation, 
which will take you to a new high-quality level of multimedia space on the Internet.
This is an assembly for ARMv7 Raspberry Pi,Libre~OpenElec and is a modified assembly 
of @Dorik1972 [forum 4pda](http://4pda.ru/forum/index.php?s=&showtopic=737440&view=findpost&p=59539138)

WebUI: http://ip_box:6878/webui/app/WEBUITOKEN/server

Start engine: autostart.sh
Stop engine: acestream.stop

Settings are the same as in Android in settings.conf:

vod_cache_type = memory|disk 

live_cache_type = memory|disk

disk_cache="default (/storage)" Run a script mount_disk.sh to determine the connected devices. Format "name (device)", example "USBFLASH (/dev/sda1)"

access_token="WEBUITOKEN"

allow_intranet_access="true"

allow_remote_access="false"

playlist_output_format_live = auto|original|hls|http

playlist_output_format_vod = auto|original|hls|http

disk_cache_limit="5"

is_debug="true"

is_experiment="false"

live_buffer_time="20"

login="ACESTREAM_LOGIN"

max_connects="500"

max_peers="50"

memory_cache_limit="150"

password="ACESTREAM_PASSW"

player_buffer_time="5"

total_max_download_rate="0"

total_max_upload_rate="0"

dht_transmissionbt_com="212.129.33.59"

router_bittorrent_com="67.215.246.10"

Addon for Kodi in [repository.search.db](https://github.com/seppius-xbmc-repo/ru/tree/master/repository.search.db) or download [forum 4pda](http://4pda.ru/forum/index.php?s=&showtopic=823683&view=findpost&p=68618451) 
