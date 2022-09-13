> algorithm: **.py** = 500€  
> full device registration **.py / .go** = 1.0k€  
> full device registration and activation **.py** = 1.5k €

https://t.me/xtekky demo on request, middleman accepted


TTEncrypt is used from /device_register on tiktok which returns this value:

```json
{
  "install_id": 7137816449338137000,
  "device_id_str": "6990234216324986369",
  "install_id_str": "7137846409338136325",
  "new_user": 1,
  "server_time": 1663094970,
  "device_id": 6990239216424987000
}
```

/device_register post body:

```json
{
    "magic_tag":"ss_app_log",
    "header": {
        "display_name"          : "TikTok Lite",
        "update_version_code"   : APP["version_code"],
        "manifest_version_code" : APP["version_code"],
        "app_version_minor"     : "",
        "aid"                   : 1340,
        "channel"               : "googleplay",
        "package"               : "com.zhiliaoapp.musically.go",
        "app_version"           : "16.9.4",
        "version_code"          : APP["version_code"],
        "sdk_version"           : "2.12.1-rc.6-lite",
        "sdk_target_version"    : 29,
        "git_hash"              : APP["git_hash"],
        "os"                    : "Android",
        "os_version"            : "7.1.2",
        "os_api"                : 25,
        "device_model"          : self.__device["device_model"],
        "device_brand"          : self.__device["device_brand"],
        "device_manufacturer"   : self.__device["device_brand"],
        "cpu_abi"               : "armeabi-v7a",
        "release_build"         : APP["release_build"],
        "density_dpi"           : 320,
        "display_density"       : "xhdpi",
        "resolution"            : self.__device["resolution"],
        "language"              : "en",
        "timezone"              : 2,
        "access"                : "wifi",
        "not_request_sender"    : 0,
        "carrier"               : "Android",
        "mcc_mnc"               : "31002",
        "rom"                   : self.__device["rom"],
        "rom_version"           : f"beyond1qlteue-user 7.1.2 PPR1.190810.011 {self.__device['rom']} release-keys",
        "cdid"                  : self.__device["cdid"],
        "sig_hash"              : APP["sig_hash"],
        "gaid_limited"          : 0,
        "google_aid"            : self.__device["google_aid"],
        "openudid"              : self.__device["openudid"],
        "clientudid"            : self.__device["clientudid"],
        "region"                : "US",
        "tz_name"               : self.__device["tz_name"],
        "tz_offset"             : self.__device["tz_offset"],
        "sim_region"            : "IE",
        "oaid_may_support"      : False,
        "req_id"                : self.__device["req_id"],
        "apk_first_install_time": self.__device["install_time"],
        "is_system_app"         : 0,
        "sdk_flavor"            : "global"
    },
    "_gen_time": int(round(time.time() * 1000))
}
```
