## Syscalls (dumped from searching 38 00 ?? ?? 44 00 00 02)
| Dec      | Hex      | Address      | Name                                 | Notes                                                        |
|----------|----------|--------------|--------------------------------------|--------------------------------------------------------------|
| 65535    | 0xFFFF   | 0x80076E74   |  ZwRaiseException                    |                                                              |
| 65535    | 0xFFFF   | 0x80076E80   |  ZwRestoreContext                    |                                                              |
| 65535    | 0xFFFF   | 0x80076E94   |  RtlCaptureContext                   |                                                              |
| 000      | 0x0000   | 0x801083F0   |  HvxGetVersions                      |                                                              |
| 001      | 0x0001   | 0x80077050   |  HvxStartupProcessors                |                                                              |
| 002      | 0x0002   | 0x80070F78   |  HvxQuiesceProcessor                 |                                                              |
| 003      | 0x0003   | 0x80073900   |  KeFlushCurrentEntireTb              |                                                              |
| 004      | 0x0004   | 0x8007390C   |  KeFlushCurrentSingleTb              |                                                              |
| 005      | 0x0005   | 0x800786F0   |  KiRelocatePage                      | This is a reference within the function 'KiRelocatePage'     |
| 006      | 0x0006   | 0x800734C0   |  KeGetSpecialPurposeRegister         |                                                              |
| 007      | 0x0007   | 0x800734CC   |  KeSetSpecialPurposeRegister         |                                                              |
| 008      | 0x0008   | 0x800734D8   |  KeGetSocRegister                    |                                                              |
| 008      | 0x0008   | 0x80071B78   |  HvxGetSocRegister                   |                                                              |
| 009      | 0x0009   | 0x800734E4   |  KeSetSocRegister                    |                                                              |
| 009      | 0x0009   | 0x80071B88   |  HvxSetSocRegister                   |                                                              |
| 010      | 0x000A   | 0x80077060   |  HvxSetTimeBaseToZero                |                                                              |
| 011      | 0x000B   | 0x800734A8   |  KeZeroPage                          |                                                              |
| 012      | 0x000C   | 0x8007F968   |  HvxFlushDcacheRange                 |                                                              |
| 013      | 0x000D   | 0x80061000   |  HvxPostOutput                       |                                                              |
| 014      | 0x000E   | 0x800734F0   |  KeEnablePPUPerformanceMonitor       |                                                              |
| 015      | 0x000F   | 0x800734FC   |  KeGetImagePageTableEntry            |                                                              |
| 015      | 0x000F   | 0x8007F978   |  HvxGetImagePageTableEntry           |                                                              |
| 016      | 0x0010   | 0x800820B0   |  HvxSetImagePageTableEntry           |                                                              |
| 017      | 0x0011   | 0x800799B0   |  HvxCreateImageMapping               |                                                              |
| 018      | 0x0012   | 0x80084390   |  HvxMapImagePage                     |                                                              |
| 019      | 0x0013   | 0x800843A0   |  HvxCompleteImageMapping             |                                                              |
| 020      | 0x0014   | 0x800799C0   |  HvxLoadImageData                    |                                                              |
| 021      | 0x0015   | 0x800799D0   |  HvxFinishImageDataLoad              |                                                              |
| 022      | 0x0016   | 0x800799E0   |  HvxStartResolveImports              |                                                              |
| 023      | 0x0017   | 0x80079AC0   |  HvxResolveImports                   |                                                              |
| 024      | 0x0018   | 0x80079AD0   |  sub_80079AD0                        | This is something to do with loading an xex                  |
| 025      | 0x0019   | 0x80079AE0   |  sub_80079AE0                        | This is something to do with loading an xex                  |
| 026      | 0x001A   | 0x80079AF0   |  HvxFinishImageLoad                  |                                                              |
| 027      | 0x001B   | 0x80079BE0   |  HvxAbandonImageLoad                 |                                                              |
| 028      | 0x001C   | 0x80079BF0   |  HvxUnmapImagePages                  |                                                              |
| 029      | 0x001D   | 0x80079C00   |  HvxUnmapImage                       |                                                              |
| 030      | 0x001E   | 0x80079C10   |  HvxUnmapImageRange                  |                                                              |
| 031      | 0x001F   | 0x800728F0   |  HvxCreateUserMode                   |                                                              |
| 032      | 0x0020   | 0x80072900   |  HvxDeleteUserMode                   |                                                              |
| 033      | 0x0021   | 0x80072910   |  HvxFlushUserModeTb                  |                                                              |
| 034      | 0x0022   | 0x80070F88   |  HvxSetPowerMode                     |                                                              |
| 036      | 0x0024   | 0x80070F98   |  HvxBlowFuses                        |                                                              |
| 037      | 0x0025   | 0x800692D0   |  HvxFsbInterrupt                     |                                                              |
| 038      | 0x0026   | 0x80071B98   |  HvxLockL2                           |                                                              |
| 039      | 0x0027   | 0x8009EB38   |  HvxDvdAuthBuildNVPage               |                                                              |
| 040      | 0x0028   | 0x8009EB48   |  HvxDvdAuthVerifyNVPage              |                                                              |
| 041      | 0x0029   | 0x8009EB58   |  HvxDvdAuthRecordAuthenticationPage  |                                                              |
| 042      | 0x002A   | 0x8009EB68   |  HvxDvdAuthRecordXControl            |                                                              |
| 043      | 0x002B   | 0x8009EB78   |  HvxDvdAuthGetAuthPage               |                                                              |
| 044      | 0x002C   | 0x8009EB88   |  HvxDvdAuthVerifyAuthPage            |                                                              |
| 045      | 0x002D   | 0x8009EB98   |  HvxDvdAuthGetNextLBAIndex           |                                                              |
| 046      | 0x002E   | 0x8009EBA8   |  HvxDvdAuthVerifyLBA                 |                                                              |
| 047      | 0x002F   | 0x8009EBB8   |  HvxDvdAuthClearDiscAuthInfo         |                                                              |
| 048      | 0x0030   | 0x80108400   |  HvxKeysInitialize                   |                                                              |
| 049      | 0x0031   | 0x80108410   |  HvxKeysGetKeyProperties             |                                                              |
| 050      | 0x0032   | 0x80108420   |  HvxKeysGetStatus                    |                                                              |
| 051      | 0x0033   | 0x80108430   |  HvxKeysGenerateRandomKey            |                                                              |
| 052      | 0x0034   | 0x80108440   |  sub_80108440                        |                                                              |
| 053      | 0x0035   | 0x80108450   |  sub_80108450                        |                                                              |
| 054      | 0x0036   | 0x80108460   |  sub_80108460                        |                                                              |
| 055      | 0x0037   | 0x80108470   |  sub_80108470                        |                                                              |
| 056      | 0x0038   | 0x80108480   |  sub_80108480                        |                                                              |
| 057      | 0x0039   | 0x80108490   |  sub_80108490                        |                                                              |
| 058      | 0x003A   | 0x801084A0   |  sub_801084A0                        |                                                              |
| 059      | 0x003B   | 0x801084B0   |  sub_801084B0                        |                                                              |
| 060      | 0x003C   | 0x801084C0   |  sub_801084C0                        |                                                              |
| 061      | 0x003D   | 0x801084D0   |  HvxKeysAesCbc                       |                                                              |
| 062      | 0x003E   | 0x801084E0   |  sub_801084E0                        |                                                              |
| 063      | 0x003F   | 0x801084F0   |  sub_801084F0                        |                                                              |
| 064      | 0x0040   | 0x80108500   |  sub_80108500                        |                                                              |
| 065      | 0x0041   | 0x80108510   |  sub_80108510                        |                                                              |
| 066      | 0x0042   | 0x80108520   |  sub_80108520                        |                                                              |
| 067      | 0x0043   | 0x8009EBC8   |  sub_8009EBC8                        |                                                              |
| 068      | 0x0044   | 0x80077070   |  HvxEnableTimebase                   |                                                              |
| 069      | 0x0045   | 0x800BB7D8   |  sub_800BB7D8                        |                                                              |
| 070      | 0x0046   | 0x800BB7E8   |  sub_800BB7E8                        |                                                              |
| 071      | 0x0047   | 0x800BB7F8   |  sub_800BB7F8                        |                                                              |
| 072      | 0x0048   | 0x80108530   |  sub_80108530                        |                                                              |
| 073      | 0x0049   | 0x80082CD0   |  HvxEncryptedAllocationReserve       |                                                              |
| 074      | 0x004A   | 0x80082CE0   |  HvxEncryptedAllocationMap           |                                                              |
| 075      | 0x004B   | 0x80082CF0   |  sub_80082CF0                        |                                                              |
| 076      | 0x004C   | 0x80082D00   |  sub_80082D00                        |                                                              |
| 077      | 0x004D   | 0x80084258   |  sub_80084258                        |                                                              |
| 078      | 0x004E   | 0x80108540   |  sub_80108540                        |                                                              |
| 079      | 0x004F   | 0x80108550   |  sub_80108550                        |                                                              |
| 080      | 0x0050   | 0x80108560   |  sub_80108560                        |                                                              |
| 081      | 0x0051   | 0x80108570   |  sub_80108570                        |                                                              |
| 082      | 0x0052   | 0x80108580   |  sub_80108580                        |                                                              |
| 083      | 0x0053   | 0x80108590   |  HvxGetUpdateSequence                |                                                              |
| 084      | 0x0054   | 0x801085A0   |  HvxSecurityInitialize               |                                                              |
| 085      | 0x0055   | 0x801085B0   |  sub_801085B0                        |                                                              |
| 086      | 0x0056   | 0x801085C0   |  HvxSecuritySaveSettings             |                                                              |
| 087      | 0x0057   | 0x801085D0   |  sub_801085D0                        |                                                              |
| 088      | 0x0058   | 0x801085E0   |  HvxSecurityGetDetected              |                                                              |
| 089      | 0x0059   | 0x801085F0   |  sub_801085F0                        |                                                              |
| 090      | 0x005A   | 0x80108600   |  sub_80108600                        |                                                              |
| 091      | 0x005B   | 0x80108610   |  sub_80108610                        |                                                              |
| 092      | 0x005C   | 0x80108620   |  sub_80108620                        |                                                              |
| 093      | 0x005D   | 0x80108630   |  sub_80108630                        |                                                              |
| 094      | 0x005E   | 0x8009EBD8   |  sub_8009EBD8                        |                                                              |
| 095      | 0x005F   | 0x8009EBE8   |  sub_8009EBE8                        |                                                              |
| 096      | 0x0060   | 0x8009EBF8   |  HvxDvdAuthSetDiscAuthResult         |                                                              |
| 097      | 0x0061   | 0x80079CA8   |  sub_80079CA8                        |                                                              |
| 098      | 0x0062   | 0x80079CB8   |  HvxImageXexHeader                   |                                                              |
| 099      | 0x0063   | 0x80108640   |  sub_80108640                        |                                                              |
| 100      | 0x0064   | 0x80108650   |  sub_80108650                        |                                                              |
| 101      | 0x0065   | 0x80108660   |  sub_80108660                        |                                                              |
| 102      | 0x0066   | 0x80108670   |  sub_80108670                        |                                                              |
| 103      | 0x0067   | 0x80070070   |  sub_80070070                        |                                                              |
| 104      | 0x0068   | 0x80070080   |  sub_80070080                        |                                                              |
| 105      | 0x0069   | 0x80070090   |  HvxXexActivationVerifyOwnership     |                                                              |
| 106      | 0x006A   | 0x8006FC78   |  sub_8006FC78                        |                                                              |
| 107      | 0x006B   | 0x8006FC88   |  sub_8006FC88                        |                                                              |
| 108      | 0x006C   | 0x8006FC98   |  sub_8006FC98                        |                                                              |
| 109      | 0x006D   | 0x8006FCA8   |  sub_8006FCA8                        |                                                              |
| 110      | 0x006E   | 0x8006FCB8   |  sub_8006FCB8                        |                                                              |
| 113      | 0x0071   | 0x80066760   |  HvxImageShim                        |                                                              |
| 114      | 0x0072   | 0x80066450   |  HvxExpansionInstall                 |unsigned int __cdecl HvxExpansionInstall(unsigned int PhysicalAddress, unsigned int CodeSize);|
| 116      | 0x0074   | 0x8009EC08   |  sub_8009EC08                        |                                                              |
| 117      | 0x0075   | 0x80108680   |  sub_80108680                        |                                                              |
| 118      | 0x0076   | 0x8009EC18   |  sub_8009EC18                        |                                                              |



## Exports
| Ordinal      | Hex      | Address      | Name                                 | Notes                                                        |
|--------------|----------|--------------|--------------------------------------|--------------------------------------------------------------|
001 | 0x0001 | 0x80085EA0 | DbgBreakPoint | |
002 | 0x0002 | 0x80085EA8 | DbgBreakPointWithStatus | |
003 | 0x0003 | 0x80085EE8 | DbgPrint | |
004 | 0x0004 | 0x80085F88 | DbgPrompt | |
005 | 0x0005 | 0x800B90C8 | DumpGetRawDumpInfo | |
006 | 0x0006 | 0x800B9580 | DumpWriteDump | |
007 | 0x0007 | 0x800641D8 | ExAcquireReadWriteLockExclusive | |
008 | 0x0008 | 0x800642B8 | ExAcquireReadWriteLockShared | |
009 | 0x0009 | 0x80064A68 | ExAllocatePool | |
010 | 0x000A | 0x80064A60 | ExAllocatePoolWithTag | |
011 | 0x000B | 0x800644E8 | ExAllocatePoolTypeWithTag | |
012 | 0x000C | 0x801A3798 | ExConsoleGameRegion | |
013 | 0x000D | 0x80065F40 | ExCreateThread | |
014 | 0x000E | 0x800407CC | ExEventObjectType | |
015 | 0x000F | 0x80064768 | ExFreePool | |
016 | 0x0010 | 0x80065700 | ExGetXConfigSetting | |
017 | 0x0011 | 0x80064498 | ExInitializeReadWriteLock | |
018 | 0x0012 | 0x800407E8 | ExMutantObjectType | |
019 | 0x0013 | 0x80064968 | ExQueryPoolBlockSize | |
020 | 0x0014 | 0x80065DF8 | ExRegisterThreadNotification | |
021 | 0x0015 | 0x80066770 | ExRegisterTitleTerminateNotification | |
022 | 0x0016 | 0x800643D8 | ExReleaseReadWriteLock | |
023 | 0x0017 | 0x80040804 | ExSemaphoreObjectType | |
024 | 0x0018 | 0x80065688 | ExSetXConfigSetting | |
025 | 0x0019 | 0x80065C60 | ExTerminateThread | |
026 | 0x001A | 0x80066918 | ExTerminateTitleProcess | |
027 | 0x001B | 0x800407B0 | ExThreadObjectType | |
028 | 0x001C | 0x80040820 | ExTimerObjectType | |
029 | 0x001D | 0x80081578 | MmDoubleMapMemory | |
030 | 0x001E | 0x800815F0 | MmUnmapMemory | |
031 | 0x001F | 0x80108FA8 | XeKeysGetConsoleCertificate | |
032 | 0x0020 | 0x8006E9D0 | FscGetCacheElementCount | |
033 | 0x0021 | 0x8006E920 | FscSetCacheElementCount | |
034 | 0x0022 | 0x80068080 | HalGetCurrentAVPack | |
035 | 0x0023 | 0x8006A300 | HalGpioControl | |
036 | 0x0024 | 0x8006A488 | HalOpenCloseODDTray | |
037 | 0x0025 | 0x8006A558 | HalReadWritePCISpace | |
038 | 0x0026 | 0x80067A58 | HalRegisterPowerDownNotification | |
039 | 0x0027 | 0x80067898 | HalRegisterSMCNotification | |
040 | 0x0028 | 0x800682A0 | HalReturnToFirmware | |
041 | 0x0029 | 0x80067F48 | HalSendSMCMessage | |
042 | 0x002A | 0x8006A7C0 | HalSetAudioEnable | |
043 | 0x002B | 0x800671A4 | InterlockedFlushSList | |
044 | 0x002C | 0x8006715C | InterlockedPopEntrySList | |
045 | 0x002D | 0x80067120 | InterlockedPushEntrySList | |
046 | 0x002E | 0x8006AB28 | IoAcquireDeviceObjectLock | |
047 | 0x002F | 0x8006B650 | IoAllocateIrp | |
048 | 0x0030 | 0x8006B6D8 | IoBuildAsynchronousFsdRequest | |
049 | 0x0031 | 0x8006B770 | IoBuildDeviceIoControlRequest | |
050 | 0x0032 | 0x8006B820 | IoBuildSynchronousFsdRequest | |
051 | 0x0033 | 0x8006AB48 | IoCallDriver | |
052 | 0x0034 | 0x8006B9D0 | IoCheckShareAccess | |
053 | 0x0035 | 0x8006AC20 | IoCompleteRequest | |
054 | 0x0036 | 0x80040AEC | IoCompletionObjectType | |
055 | 0x0037 | 0x8006AEA0 | IoCreateDevice | |
056 | 0x0038 | 0x8006B0B0 | IoCreateFile | |
057 | 0x0039 | 0x8006B150 | IoDeleteDevice | |
058 | 0x003A | 0x80040B08 | IoDeviceObjectType | |
059 | 0x003B | 0x8006B1D0 | IoDismountVolume | |
060 | 0x003C | 0x8006B278 | IoDismountVolumeByFileHandle | |
061 | 0x003D | 0x8006B2F0 | IoDismountVolumeByName | |
062 | 0x003E | 0x80040B24 | IoFileObjectType | |
063 | 0x003F | 0x8006B368 | IoFreeIrp | |
064 | 0x0040 | 0x8006B398 | IoInitializeIrp | |
065 | 0x0041 | 0x8006B400 | IoInvalidDeviceRequest | |
066 | 0x0042 | 0x800664C8 | ExSetBetaFeaturesEnabled | |
067 | 0x0043 | 0x8006B4A0 | IoQueueThreadIrp | |
068 | 0x0044 | 0x8006AB38 | IoReleaseDeviceObjectLock | |
069 | 0x0045 | 0x8006BB38 | IoRemoveShareAccess | |
070 | 0x0046 | 0x8006BE10 | IoSetIoCompletion | |
071 | 0x0047 | 0x8006BBD0 | IoSetShareAccess | |
072 | 0x0048 | 0x8006B5C0 | IoStartNextPacket | |
073 | 0x0049 | 0x8006B5D0 | IoStartNextPacketByKey | |
074 | 0x004A | 0x8006B5D8 | IoStartPacket | |
075 | 0x004B | 0x8006B878 | IoSynchronousDeviceIoControlRequest | |
076 | 0x004C | 0x8006B928 | IoSynchronousFsdRequest | |
077 | 0x004D | 0x800701C0 | KeAcquireSpinLockAtRaisedIrql | |
078 | 0x004E | 0x800707C8 | KeAlertResumeThread | |
079 | 0x004F | 0x80070730 | KeAlertThread | |
080 | 0x0050 | 0x80071598 | KeBlowFuses | |
081 | 0x0051 | 0x80070880 | KeBoostPriorityThread | |
082 | 0x0052 | 0x800718C8 | KeBugCheck | |
083 | 0x0053 | 0x800716E8 | KeBugCheckEx | |
084 | 0x0054 | 0x80072078 | KeCancelTimer | |
085 | 0x0055 | 0x80072260 | KeConnectInterrupt | |
086 | 0x0056 | 0x80072470 | KeContextFromKframes | |
087 | 0x0057 | 0x800725A0 | KeContextToKframes | |
088 | 0x0058 | 0x800729D0 | KeCreateUserMode | |
089 | 0x0059 | 0x801A5758 | KeDebugMonitorData | |
090 | 0x005A | 0x80072B58 | KeDelayExecutionThread | |
091 | 0x005B | 0x80072A40 | KeDeleteUserMode | |
092 | 0x005C | 0x80072360 | KeDisconnectInterrupt | |
093 | 0x005D | 0x80072408 | KeEnableFpuExceptions | |
094 | 0x005E | 0x800734F0 | KeEnablePPUPerformanceMonitor | |
095 | 0x005F | 0x800718E0 | KeEnterCriticalRegion | |
096 | 0x0060 | 0x80073510 | KeEnterUserMode | |
097 | 0x0061 | 0x80073850 | KeFlushCacheRange | |
098 | 0x0062 | 0x80073900 | KeFlushCurrentEntireTb | |
099 | 0x0063 | 0x80073940 | KeFlushEntireTb | |
100 | 0x0064 | 0x800729C8 | KeFlushUserModeCurrentTb | |
101 | 0x0065 | 0x80072958 | KeFlushUserModeTb | |
102 | 0x0066 | 0x80071A68 | KeGetCurrentProcessType | |
103 | 0x0067 | 0x80072018 | KeGetPMWRegister | |
104 | 0x0068 | 0x80072028 | KeGetPRVRegister | |
105 | 0x0069 | 0x800734D8 | KeGetSocRegister | |
106 | 0x006A | 0x800734C0 | KeGetSpecialPurposeRegister | |
107 | 0x006B | 0x80071E00 | KeLockL2 | |
108 | 0x006C | 0x80071EE8 | KeUnlockL2 | |
109 | 0x006D | 0x80073AC8 | KeInitializeApc | |
110 | 0x006E | 0x80073DA8 | KeInitializeDeviceQueue | |
111 | 0x006F | 0x80073F30 | KeInitializeDpc | |
112 | 0x0070 | 0x80074300 | KeInitializeEvent | |
113 | 0x0071 | 0x800721D0 | KeInitializeInterrupt | |
114 | 0x0072 | 0x80074320 | KeInitializeMutant | |
115 | 0x0073 | 0x80074608 | KeInitializeQueue | |
116 | 0x0074 | 0x80074A78 | KeInitializeSemaphore | |
117 | 0x0075 | 0x80072048 | KeInitializeTimerEx | |
118 | 0x0076 | 0x80073D08 | KeInsertByKeyDeviceQueue | |
119 | 0x0077 | 0x80073C98 | KeInsertDeviceQueue | |
120 | 0x0078 | 0x800746A8 | KeInsertHeadQueue | |
121 | 0x0079 | 0x80074660 | KeInsertQueue | |
122 | 0x007A | 0x80073B88 | KeInsertQueueApc | |
123 | 0x007B | 0x80073F50 | KeInsertQueueDpc | |
124 | 0x007C | 0x80074B28 | KeIpiGenericCall | |
125 | 0x007D | 0x800718F8 | KeLeaveCriticalRegion | |
126 | 0x007E | 0x80073690 | KeLeaveUserMode | |
127 | 0x007F | 0x80074108 | KePulseEvent | |
128 | 0x0080 | 0x80074EB8 | KeQueryBackgroundProcessors | |
129 | 0x0081 | 0x80070258 | KeQueryBasePriorityThread | |
130 | 0x0082 | 0x80071938 | KeQueryInterruptTime | |
131 | 0x0083 | 0x800734B4 | KeQueryPerformanceFrequency | |
132 | 0x0084 | 0x80071948 | KeQuerySystemTime | |
133 | 0x0085 | 0x800750C0 | KeRaiseIrqlToDpcLevel | |
134 | 0x0086 | 0x80070FA8 | KeRegisterDriverNotification | |
135 | 0x0087 | 0x800743A0 | KeReleaseMutant | |
136 | 0x0088 | 0x800749D0 | KeReleaseSemaphore | |
137 | 0x0089 | 0x8007020C | KeReleaseSpinLockFromRaisedIrql | |
138 | 0x008A | 0x80073E38 | KeRemoveByKeyDeviceQueue | |
139 | 0x008B | 0x80073DD0 | KeRemoveDeviceQueue | |
140 | 0x008C | 0x80073ED8 | KeRemoveEntryDeviceQueue | |
141 | 0x008D | 0x800746F0 | KeRemoveQueue | |
142 | 0x008E | 0x80074078 | KeRemoveQueueDpc | |
143 | 0x008F | 0x80074190 | KeResetEvent | |
144 | 0x0090 | 0x80075970 | KeRestoreFloatingPointState | |
145 | 0x0091 | 0x80075AC4 | KeRestoreVectorUnitState | |
146 | 0x0092 | 0x80070980 | KeResumeThread | |
147 | 0x0093 | 0x80075800 | KeRetireDpcList | |
148 | 0x0094 | 0x80074940 | KeRundownQueue | |
149 | 0x0095 | 0x8007599C | KeSaveFloatingPointState | |
150 | 0x0096 | 0x80075AEC | KeSaveVectorUnitState | |
151 | 0x0097 | 0x80070378 | KeSetAffinityThread | |
152 | 0x0098 | 0x80074EC8 | KeSetBackgroundProcessors | |
153 | 0x0099 | 0x80070A38 | KeSetBasePriorityThread | |
154 | 0x009A | 0x80071AA8 | KeSetCurrentProcessType | |
155 | 0x009B | 0x80075E70 | KeSetCurrentStackPointers | |
156 | 0x009C | 0x80070B58 | KeSetDisableBoostThread | |
157 | 0x009D | 0x800741D8 | KeSetEvent | |
158 | 0x009E | 0x80074290 | KeSetEventBoostPriority | |
159 | 0x009F | 0x80072020 | KeSetPMWRegister | |
160 | 0x00A0 | 0x80071508 | KeSetPowerMode | |
161 | 0x00A1 | 0x80072038 | KeSetPRVRegister | |
162 | 0x00A2 | 0x80070BB0 | KeSetPriorityClassThread | |
163 | 0x00A3 | 0x80070C70 | KeSetPriorityThread | |
164 | 0x00A4 | 0x800734E4 | KeSetSocRegister | |
165 | 0x00A5 | 0x800734CC | KeSetSpecialPurposeRegister | |
166 | 0x00A6 | 0x800721C0 | KeSetTimer | |
167 | 0x00A7 | 0x800720D8 | KeSetTimerEx | |
168 | 0x00A8 | 0x80073484 | KeStallExecutionProcessor | |
169 | 0x00A9 | 0x80070CE0 | KeSuspendThread | |
170 | 0x00AA | 0x800738C8 | KeSweepDcacheRange | |
171 | 0x00AB | 0x8007388C | KeSweepIcacheRange | |
172 | 0x00AC | 0x80070DA8 | KeTestAlertThread | |
173 | 0x00AD | 0x801B0EE0 | KeTimeStampBundle | |
174 | 0x00AE | 0x8007021C | KeTryToAcquireSpinLockAtRaisedIrql | |
175 | 0x00AF | 0x80072D48 | KeWaitForMultipleObjects | |
176 | 0x00B0 | 0x80073120 | KeWaitForSingleObject | |
177 | 0x00B1 | 0x80070138 | KfAcquireSpinLock | |
178 | 0x00B2 | 0x800750D0 | KfRaiseIrql | |
179 | 0x00B3 | 0x800750F4 | KfLowerIrql | |
180 | 0x00B4 | 0x8007018C | KfReleaseSpinLock | |
181 | 0x00B5 | 0x801A5920 | KiBugCheckData | |
182 | 0x00B6 | 0x80129528 | LDICreateDecompression | |
183 | 0x00B7 | 0x80129600 | LDIDecompress | |
184 | 0x00B8 | 0x801296E0 | LDIDestroyDecompression | |
185 | 0x00B9 | 0x80080AB0 | MmAllocatePhysicalMemory | |
186 | 0x00BA | 0x800801D8 | MmAllocatePhysicalMemoryEx | |
187 | 0x00BB | 0x800812C0 | MmCreateKernelStack | |
188 | 0x00BC | 0x80081FC8 | MmDeleteKernelStack | |
189 | 0x00BD | 0x800807B8 | MmFreePhysicalMemory | |
190 | 0x00BE | 0x80080048 | MmGetPhysicalAddress | |
191 | 0x00BF | 0x80081638 | MmIsAddressValid | |
192 | 0x00C0 | 0x8007FF28 | MmLockAndMapSegmentArray | |
193 | 0x00C1 | 0x8007FC90 | MmLockUnlockBufferPages | |
194 | 0x00C2 | 0x8007FB00 | MmMapIoSpace | |
195 | 0x00C3 | 0x8007F898 | MmPersistPhysicalMemoryAllocation | |
196 | 0x00C4 | 0x800819D0 | MmQueryAddressProtect | |
197 | 0x00C5 | 0x8007F780 | MmQueryAllocationSize | |
198 | 0x00C6 | 0x80081128 | MmQueryStatistics | |
199 | 0x00C7 | 0x80081BD0 | MmSetAddressProtect | |
200 | 0x00C8 | 0x8007F988 | MmSplitPhysicalMemoryAllocation | |
201 | 0x00C9 | 0x80080A48 | MmUnlockAndUnmapSegmentArray | |
202 | 0x00CA | 0x8007FC10 | MmUnmapIoSpace | |
203 | 0x00CB | 0x80040E78 | Nls844UnicodeCaseTable | |
204 | 0x00CC | 0x80083AA8 | NtAllocateVirtualMemory | |
205 | 0x00CD | 0x80066E60 | NtCancelTimer | |
206 | 0x00CE | 0x800661A8 | NtClearEvent | |
207 | 0x00CF | 0x80089EB0 | NtClose | |
208 | 0x00D0 | 0x8008A120 | NtCreateDirectoryObject | |
209 | 0x00D1 | 0x80066368 | NtCreateEvent | |
210 | 0x00D2 | 0x8006CAA8 | NtCreateFile | |
211 | 0x00D3 | 0x8006BC88 | NtCreateIoCompletion | |
212 | 0x00D4 | 0x80066548 | NtCreateMutant | |
213 | 0x00D5 | 0x80066980 | NtCreateSemaphore | |
214 | 0x00D6 | 0x8008AD88 | NtCreateSymbolicLinkObject | |
215 | 0x00D7 | 0x80066BA8 | NtCreateTimer | |
216 | 0x00D8 | 0x8006DF08 | NtDeleteFile | |
217 | 0x00D9 | 0x8006D168 | NtDeviceIoControlFile | |
218 | 0x00DA | 0x80089FE0 | NtDuplicateObject | |
219 | 0x00DB | 0x8006D348 | NtFlushBuffersFile | |
220 | 0x00DC | 0x80083190 | NtFreeVirtualMemory | |
221 | 0x00DD | 0x8008A0D0 | NtMakeTemporaryObject | |
222 | 0x00DE | 0x8008A198 | NtOpenDirectoryObject | |
223 | 0x00DF | 0x8006CAE0 | NtOpenFile | |
224 | 0x00E0 | 0x8008AE48 | NtOpenSymbolicLinkObject | |
225 | 0x00E1 | 0x80083560 | NtProtectVirtualMemory | |
226 | 0x00E2 | 0x80066200 | NtPulseEvent | |
227 | 0x00E3 | 0x800659D0 | NtQueueApcThread | |
228 | 0x00E4 | 0x8006CFA8 | NtQueryDirectoryFile | |
229 | 0x00E5 | 0x8008A1B0 | NtQueryDirectoryObject | |
230 | 0x00E6 | 0x80066260 | NtQueryEvent | |
231 | 0x00E7 | 0x8006DF98 | NtQueryFullAttributesFile | |
232 | 0x00E8 | 0x8006D630 | NtQueryInformationFile | |
233 | 0x00E9 | 0x8006BCF8 | NtQueryIoCompletion | |
234 | 0x00EA | 0x800665A8 | NtQueryMutant | |
235 | 0x00EB | 0x80066A10 | NtQuerySemaphore | |
236 | 0x00EC | 0x8008AE60 | NtQuerySymbolicLinkObject | |
237 | 0x00ED | 0x80066C58 | NtQueryTimer | |
238 | 0x00EE | 0x80082D10 | NtQueryVirtualMemory | |
239 | 0x00EF | 0x8006D490 | NtQueryVolumeInformationFile | |
240 | 0x00F0 | 0x8006CEC8 | NtReadFile | |
241 | 0x00F1 | 0x8006CF38 | NtReadFileScatter | |
242 | 0x00F2 | 0x80066618 | NtReleaseMutant | |
243 | 0x00F3 | 0x80066A68 | NtReleaseSemaphore | |
244 | 0x00F4 | 0x8006BD40 | NtRemoveIoCompletion | |
245 | 0x00F5 | 0x80065B90 | NtResumeThread | |
246 | 0x00F6 | 0x80066308 | NtSetEvent | |
247 | 0x00F7 | 0x8006D928 | NtSetInformationFile | |
248 | 0x00F8 | 0x8006BEE8 | NtSetIoCompletion | |
249 | 0x00F9 | 0x800671D8 | NtSetSystemTime | |
250 | 0x00FA | 0x80066F48 | NtSetTimerEx | |
251 | 0x00FB | 0x8008AFD0 | NtSignalAndWaitForSingleObjectEx | |
252 | 0x00FC | 0x80065A98 | NtSuspendThread | |
253 | 0x00FD | 0x8008B188 | NtWaitForSingleObjectEx | |
254 | 0x00FE | 0x8008B238 | NtWaitForMultipleObjectsEx | |
255 | 0x00FF | 0x8006CF00 | NtWriteFile | |
256 | 0x0100 | 0x8006CF70 | NtWriteFileGather | |
257 | 0x0101 | 0x80075EA8 | NtYieldExecution | |
258 | 0x0102 | 0x8008B468 | ObCreateObject | |
259 | 0x0103 | 0x8008AEF0 | ObCreateSymbolicLink | |
260 | 0x0104 | 0x8008AF50 | ObDeleteSymbolicLink | |
261 | 0x0105 | 0x8008B928 | ObDereferenceObject | |
262 | 0x0106 | 0x80042660 | ObDirectoryObjectType | |
263 | 0x0107 | 0x8008B448 | ObGetWaitableObject | |
264 | 0x0108 | 0x8008B618 | ObInsertObject | |
265 | 0x0109 | 0x8008B9B0 | ObIsTitleObject | |
266 | 0x010A | 0x8008BD08 | ObLookupAnyThreadByThreadId | |
267 | 0x010B | 0x8008BD30 | ObLookupThreadByThreadId | |
268 | 0x010C | 0x8008A050 | ObMakeTemporaryObject | |
269 | 0x010D | 0x8008BB10 | ObOpenObjectByName | |
270 | 0x010E | 0x8008B9C0 | ObOpenObjectByPointer | |
271 | 0x010F | 0x8008B8E0 | ObReferenceObject | |
272 | 0x0110 | 0x8008BA50 | ObReferenceObjectByHandle | |
273 | 0x0111 | 0x8008B908 | ObReferenceObjectByName | |
274 | 0x0112 | 0x8004267C | ObSymbolicLinkObjectType | |
275 | 0x0113 | 0x8008ACB8 | ObTranslateSymbolicLink | |
276 | 0x0114 | 0x80086BB0 | RtlAnsiStringToUnicodeString | |
277 | 0x0115 | 0x800865B0 | RtlAppendStringToString | |
278 | 0x0116 | 0x800867A0 | RtlAppendUnicodeStringToString | |
279 | 0x0117 | 0x800866F0 | RtlAppendUnicodeToString | |
280 | 0x0118 | 0x800BAB90 | RtlAssert | |
281 | 0x0119 | 0x80076E8C | RtlCaptureContext | |
282 | 0x011A | 0x80087DB0 | RtlCompareMemory | |
283 | 0x011B | 0x8008859C | RtlCompareMemoryUlong | |
284 | 0x011C | 0x80086498 | RtlCompareString | |
285 | 0x011D | 0x80086390 | RtlCompareStringN | |
286 | 0x011E | 0x80086590 | RtlCompareUnicodeString | |
287 | 0x011F | 0x800864B0 | RtlCompareUnicodeStringN | |
288 | 0x0120 | 0x80086970 | RtlCompareUtf8ToUnicode | |
289 | 0x0121 | 0x80086190 | RtlCopyString | |
290 | 0x0122 | 0x80086678 | RtlCopyUnicodeString | |
291 | 0x0123 | 0x80086838 | RtlCreateUnicodeString | |
292 | 0x0124 | 0x80086330 | RtlDowncaseUnicodeChar | |
293 | 0x0125 | 0x80088FA0 | RtlEnterCriticalSection | |
294 | 0x0126 | 0x80088EE8 | RtlFillMemoryUlong | |
295 | 0x0127 | 0x80086630 | RtlFreeAnsiString | |
296 | 0x0128 | 0x80086630 | RtlFreeAnsiString | |
297 | 0x0129 | 0x80089218 | RtlGetCallersAddress | |
298 | 0x012A | 0x800893B0 | RtlGetStackLimits | |
299 | 0x012B | 0x80089590 | RtlImageXexHeaderField | |
300 | 0x012C | 0x80086110 | RtlInitAnsiString | |
301 | 0x012D | 0x80086150 | RtlInitUnicodeString | |
302 | 0x012E | 0x80089760 | RtlInitializeCriticalSection | |
303 | 0x012F | 0x80089710 | RtlInitializeCriticalSectionAndSpinCount | |
304 | 0x0130 | 0x800890F8 | RtlLeaveCriticalSection | |
305 | 0x0131 | 0x80086F00 | RtlLookupFunctionEntry | |
306 | 0x0132 | 0x80086260 | RtlLowerChar | |
307 | 0x0133 | 0x800868A8 | RtlMultiByteToUnicodeN | |
308 | 0x0134 | 0x800868F0 | RtlMultiByteToUnicodeSize | |
309 | 0x0135 | 0x80089768 | RtlNtStatusToDosError | |
310 | 0x0136 | 0x800878A0 | RtlRaiseException | |
311 | 0x0137 | 0x800877F8 | RtlRaiseStatus | |
312 | 0x0138 | 0x800BAB90 | RtlRip | |
313 | 0x0139 | 0x8010C680 | _scprintf | |
314 | 0x013A | 0x8010C7F8 | _snprintf | |
315 | 0x013B | 0x8010C5F0 | sprintf | |
316 | 0x013C | 0x8010C788 | _scwprintf | |
317 | 0x013D | 0x8010C880 | _snwprintf | |
318 | 0x013E | 0x8010C6F0 | _swprintf | |
319 | 0x013F | 0x80089A58 | RtlTimeFieldsToTime | |
320 | 0x0140 | 0x800898E8 | RtlTimeToTimeFields | |
321 | 0x0141 | 0x80089184 | RtlTryEnterCriticalSection | |
322 | 0x0142 | 0x80086CC0 | RtlUnicodeStringToAnsiString | |
323 | 0x0143 | 0x80086920 | RtlUnicodeToMultiByteN | |
324 | 0x0144 | 0x80086908 | RtlUnicodeToMultiByteSize | |
325 | 0x0145 | 0x80086AF0 | RtlUnicodeToUtf8 | |
326 | 0x0146 | 0x80086A98 | RtlUnicodeToUtf8Size | |
327 | 0x0147 | 0x80087D80 | RtlUnwind | |
328 | 0x0148 | 0x800878C8 | RtlUnwind2 | |
329 | 0x0149 | 0x800862D0 | RtlUpcaseUnicodeChar | |
330 | 0x014A | 0x800861F0 | RtlUpperChar | |
331 | 0x014B | 0x800873E0 | RtlVirtualUnwind | |
332 | 0x014C | 0x8010C988 | _vscprintf | |
333 | 0x014D | 0x8010CAA0 | _vsnprintf | |
334 | 0x014E | 0x8010C918 | vsprintf | |
335 | 0x014F | 0x8010CA50 | _vscwprintf | |
336 | 0x0150 | 0x8010CB10 | _vsnwprintf | |
337 | 0x0151 | 0x8010C9D8 | _vswprintf | |
338 | 0x0152 | 0x80076EB0 | KeTlsAlloc | |
339 | 0x0153 | 0x80076F60 | KeTlsFree | |
340 | 0x0154 | 0x80077018 | KeTlsGetValue | |
341 | 0x0155 | 0x80077030 | KeTlsSetValue | |
342 | 0x0156 | 0x80170000 | XboxHardwareInfo | |
343 | 0x0157 | 0x80040454 | XboxKrnlBaseVersion | |
344 | 0x0158 | 0x8004044C | XboxKrnlVersion | |
345 | 0x0159 | 0x8010FFC0 | XeCryptAesKey | |
346 | 0x015A | 0x8010FFD0 | XeCryptAesEcb | |
347 | 0x015B | 0x8010FFF0 | XeCryptAesCbc | |
348 | 0x015C | 0x80111528 | XeCryptBnDwLeDhEqualBase | |
349 | 0x015D | 0x80111440 | XeCryptBnDwLeDhInvalBase | |
350 | 0x015E | 0x80111368 | XeCryptBnDwLeDhModExp | |
351 | 0x015F | 0x80111720 | XeCryptBnDw_Copy | |
352 | 0x0160 | 0x80111750 | XeCryptBnDw_SwapLeBe | |
353 | 0x0161 | 0x80111780 | XeCryptBnDw_Zero | |
354 | 0x0162 | 0x801115C8 | XeCryptBnDwLePkcs1Format | |
355 | 0x0163 | 0x80111680 | XeCryptBnDwLePkcs1Verify | |
356 | 0x0164 | 0x801117A0 | XeCryptBnQwBeSigCreate | |
357 | 0x0165 | 0x80111898 | XeCryptBnQwBeSigFormat | |
358 | 0x0166 | 0x80111990 | XeCryptBnQwBeSigVerify | |
359 | 0x0167 | 0x80111C60 | XeCryptBnQwNeModExp | |
360 | 0x0168 | 0x80112010 | XeCryptBnQwNeModExpRoot | |
361 | 0x0169 | 0x801121A8 | XeCryptBnQwNeModInv | |
362 | 0x016A | 0x801121E0 | XeCryptBnQwNeModMul | |
363 | 0x016B | 0x80112408 | XeCryptBnQwNeRsaKeyGen | |
364 | 0x016C | 0x80112760 | XeCryptBnQwNeRsaPrvCrypt | |
365 | 0x016D | 0x801126E0 | XeCryptBnQwNeRsaPubCrypt | |
366 | 0x016E | 0x801127A0 | XeCryptBnQw_Copy | |
367 | 0x016F | 0x801127D0 | XeCryptBnQw_SwapDwQw | |
368 | 0x0170 | 0x80112800 | XeCryptBnQw_SwapDwQwLeBe | |
369 | 0x0171 | 0x80112830 | XeCryptBnQw_SwapLeBe | |
370 | 0x0172 | 0x80112860 | XeCryptBnQw_Zero | |
371 | 0x0173 | 0x801129C0 | XeCryptChainAndSumMac | |
372 | 0x0174 | 0x80113320 | XeCryptDesParity | |
373 | 0x0175 | 0x801130C8 | XeCryptDesKey | |
374 | 0x0176 | 0x80112AD0 | XeCryptDesEcb | |
375 | 0x0177 | 0x80112E68 | XeCryptDesCbc | |
376 | 0x0178 | 0x801132E0 | XeCryptDes3Key | |
377 | 0x0179 | 0x80112F28 | XeCryptDes3Ecb | |
378 | 0x017A | 0x80112FA8 | XeCryptDes3Cbc | |
379 | 0x017B | 0x80114998 | XeCryptHmacMd5Init | |
380 | 0x017C | 0x80114AD8 | XeCryptHmacMd5Update | |
381 | 0x017D | 0x80114AE0 | XeCryptHmacMd5Final | |
382 | 0x017E | 0x80114B30 | XeCryptHmacMd5 | |
383 | 0x017F | 0x80114E40 | XeCryptHmacShaInit | |
384 | 0x0180 | 0x80114F90 | XeCryptHmacShaUpdate | |
385 | 0x0181 | 0x80114F98 | XeCryptHmacShaFinal | |
386 | 0x0182 | 0x80114FE8 | XeCryptHmacSha | |
387 | 0x0183 | 0x80115080 | XeCryptHmacShaVerify | |
388 | 0x0184 | 0x801146C0 | XeCryptMd5Init | |
389 | 0x0185 | 0x80114700 | XeCryptMd5Update | |
390 | 0x0186 | 0x801147F8 | XeCryptMd5Final | |
391 | 0x0187 | 0x801148D8 | XeCryptMd5 | |
392 | 0x0188 | 0x80112880 | XeCryptParveEcb | |
393 | 0x0189 | 0x80112938 | XeCryptParveCbcMac | |
394 | 0x018A | 0x80061440 | XeCryptRandom | |
395 | 0x018B | 0x80115140 | XeCryptRc4Key | |
396 | 0x018C | 0x801151E8 | XeCryptRc4Ecb | |
397 | 0x018D | 0x801150E0 | XeCryptRc4 | |
398 | 0x018E | 0x801152C0 | XeCryptRotSumSha | |
399 | 0x018F | 0x80114BC8 | XeCryptShaInit | |
400 | 0x0190 | 0x80114C10 | XeCryptShaUpdate | |
401 | 0x0191 | 0x80114CB0 | XeCryptShaFinal | |
402 | 0x0192 | 0x80114D78 | XeCryptSha | |
403 | 0x0193 | 0x801A5DD4 | XexExecutableModuleHandle | |
404 | 0x0194 | 0x80079688 | XexCheckExecutablePrivilege | |
405 | 0x0195 | 0x8007D320 | XexGetModuleHandle | |
406 | 0x0196 | 0x8007D208 | XexGetModuleSection | |
407 | 0x0197 | 0x8007D1B0 | XexGetProcedureAddress | |
408 | 0x0198 | 0x8007D7E0 | XexLoadExecutable | |
409 | 0x0199 | 0x8007D7C0 | XexLoadImage | |
410 | 0x019A | 0x8007D858 | XexLoadImageFromMemory | |
411 | 0x019B | 0x8007C130 | XexLoadImageHeaders | |
412 | 0x019C | 0x8007B498 | XexPcToFileHeader | |
413 | 0x019D | 0x800BAB90 | KeSetProfilerISR | |
414 | 0x019E | 0x8007DB18 | XexRegisterPatchDescriptor | |
415 | 0x019F | 0x8007B308 | XexSendDeferredNotifications | |
416 | 0x01A0 | 0x8007B0C8 | XexStartExecutable | |
417 | 0x01A1 | 0x8007D0E8 | XexUnloadImage | |
418 | 0x01A2 | 0x8007D190 | XexUnloadImageAndExitThread | |
419 | 0x01A3 | 0x8007B1F0 | XexUnloadTitleModules | |
420 | 0x01A4 | 0x8007C100 | XexVerifyImageHeaders | |
421 | 0x01A5 | 0x80089BE0 | __C_specific_handler | |
422 | 0x01A6 | 0x80085FE8 | DbgLoadImageSymbols | |
423 | 0x01A7 | 0x80086058 | DbgUnLoadImageSymbols | |
424 | 0x01A8 | 0x800894A8 | RtlImageDirectoryEntryToData | |
425 | 0x01A9 | 0x800893E8 | RtlImageNtHeader | |
426 | 0x01AA | 0x8007BB68 | ExDebugMonitorService | |
427 | 0x01AB | 0x80082070 | MmDbgReadCheck | |
428 | 0x01AC | 0x80082268 | MmDbgReleaseAddress | |
429 | 0x01AD | 0x800820C0 | MmDbgWriteCheck | |
430 | 0x01AE | 0x801A5960 | ExLoadedCommandLine | |
431 | 0x01AF | 0x801A5B60 | ExLoadedImageName | |
432 | 0x01B0 | 0x800BD5F0 | VdBlockUntilGUIIdle | |
433 | 0x01B1 | 0x800BD7A8 | VdCallGraphicsNotificationRoutines | |
434 | 0x01B2 | 0x800BDD40 | VdDisplayFatalError | |
435 | 0x01B3 | 0x800BEE20 | VdEnableClosedCaption | |
436 | 0x01B4 | 0x800BF1C8 | VdEnableDisableClockGating | |
437 | 0x01B5 | 0x800BF118 | VdEnableDisablePowerSavingMode | |
438 | 0x01B6 | 0x800BF928 | VdEnableRingBufferRPtrWriteBack | |
439 | 0x01B7 | 0x800BCF58 | VdGenerateGPUCSCCoefficients | |
440 | 0x01B8 | 0x800BEEF0 | VdGetClosedCaptionReadyStatus | |
441 | 0x01B9 | 0x800C6658 | VdGetCurrentDisplayGamma | |
442 | 0x01BA | 0x800C64F8 | VdGetCurrentDisplayInformation | |
443 | 0x01BB | 0x800C6558 | VdGetDisplayModeOverride | |
444 | 0x01BC | 0x800BD6C0 | VdGetGraphicsAsicID | |
445 | 0x01BD | 0x800C8B48 | VdGetSystemCommandBuffer | |
446 | 0x01BE | 0x80186254 | VdGlobalDevice | |
447 | 0x01BF | 0x80186258 | VdGlobalXamDevice | |
448 | 0x01C0 | 0x80170DA4 | VdGpuClockInMHz | |
449 | 0x01C1 | 0x80171120 | VdHSIOCalibrationLock | |
450 | 0x01C2 | 0x800C7E18 | VdInitializeEngines | |
451 | 0x01C3 | 0x800BF8D8 | VdInitializeRingBuffer | |
452 | 0x01C4 | 0x800CF670 | VdInitializeScaler | |
453 | 0x01C5 | 0x800CFAE0 | VdInitializeScalerCommandBuffer | |
454 | 0x01C6 | 0x800C8E38 | VdIsHSIOTrainingSucceeded | |
455 | 0x01C7 | 0x800CFFB0 | VdPersistDisplay | |
456 | 0x01C8 | 0x800C8A08 | VdQuerySystemCommandBuffer | |
457 | 0x01C9 | 0x800C6E10 | VdQueryVideoFlags | |
458 | 0x01CA | 0x800C6E00 | VdQueryVideoMode | |
459 | 0x01CB | 0x800C1690 | VdReadDVERegisterUlong | |
460 | 0x01CC | 0x800C8E48 | VdReadWriteHSIOCalibrationFlag | |
461 | 0x01CD | 0x800BD840 | VdRegisterGraphicsNotification | |
462 | 0x01CE | 0x800BD798 | VdRegisterXamGraphicsNotification | |
463 | 0x01CF | 0x800BEE88 | VdSendClosedCaptionData | |
464 | 0x01D0 | 0x800BE6E8 | VdSetCGMSOption | |
465 | 0x01D1 | 0x800C6600 | VdSetColorProfileAdjustment | |
466 | 0x01D2 | 0x800BCD30 | VdSetCscMatricesOverride | |
467 | 0x01D3 | 0x800C7650 | VdSetDisplayMode | |
468 | 0x01D4 | 0x800C6B58 | VdSetDisplayModeOverride | |
469 | 0x01D5 | 0x800D0340 | VdSetGraphicsInterruptCallback | |
470 | 0x01D6 | 0x800BB808 | VdSetHDCPOption | |
471 | 0x01D7 | 0x800BF0D0 | VdSetMacrovisionOption | |
472 | 0x01D8 | 0x800C8AB8 | VdSetSystemCommandBuffer | |
473 | 0x01D9 | 0x800C8940 | VdSetSystemCommandBufferGpuIdentifierAddress | |
474 | 0x01DA | 0x800BE738 | VdSetWSSData | |
475 | 0x01DB | 0x800BEDE8 | VdSetWSSOption | |
476 | 0x01DC | 0x800C7F60 | VdShutdownEngines | |
477 | 0x01DD | 0x800C5ED8 | VdTurnDisplayOff | |
478 | 0x01DE | 0x800C6010 | VdTurnDisplayOn | |
479 | 0x01DF | 0x800BAB90 | KeSetProfilerISR | |
480 | 0x01E0 | 0x800C1700 | VdWriteDVERegisterUlong | |
481 | 0x01E1 | 0x80101C40 | XVoicedHeadsetPresent | |
482 | 0x01E2 | 0x80102048 | XVoicedSubmitPacket | |
483 | 0x01E3 | 0x80102230 | XVoicedClose | |
484 | 0x01E4 | 0x80101DC8 | XVoicedActivate | |
485 | 0x01E5 | 0x800F6BB8 | XInputdGetCapabilities | |
486 | 0x01E6 | 0x800F6C20 | XInputdReadState | |
487 | 0x01E7 | 0x800F6C88 | XInputdWriteState | |
488 | 0x01E8 | 0x800F6CD0 | XInputdNotify | |
489 | 0x01E9 | 0x800F6E40 | XInputdRawState | |
490 | 0x01EA | 0x800E5028 | HidGetCapabilities | |
491 | 0x01EB | 0x800E5080 | HidReadKeys | |
492 | 0x01EC | 0x800F6D50 | XInputdGetDeviceStats | |
493 | 0x01ED | 0x800F6F50 | XInputdResetDevice | |
494 | 0x01EE | 0x800F6F78 | XInputdSetRingOfLight | |
495 | 0x01EF | 0x800F6FB8 | XInputdSetRFPowerMode | |
496 | 0x01F0 | 0x800F6FF8 | XInputdSetRadioFrequency | |
497 | 0x01F1 | 0x800E51C8 | HidGetLastInputTime | |
498 | 0x01F2 | 0x8012CA80 | XAudioRenderDriverInitialize | |
499 | 0x01F3 | 0x8012E250 | XAudioRegisterRenderDriverClient | |
500 | 0x01F4 | 0x8012E270 | XAudioUnregisterRenderDriverClient | |
501 | 0x01F5 | 0x8012D598 | XAudioSubmitRenderDriverFrame | |
502 | 0x01F6 | 0x8012CC70 | XAudioRenderDriverLock | |
503 | 0x01F7 | 0x8012E2E0 | XAudioGetVoiceCategoryVolumeChangeMask | |
504 | 0x01F8 | 0x8012CC30 | XAudioGetVoiceCategoryVolume | |
505 | 0x01F9 | 0x8012E300 | XAudioSetVoiceCategoryVolume | |
506 | 0x01FA | 0x8012C780 | XAudioBeginDigitalBypassMode | |
507 | 0x01FB | 0x8012C848 | XAudioEndDigitalBypassMode | |
508 | 0x01FC | 0x8012C8C0 | XAudioSubmitDigitalPacket | |
509 | 0x01FD | 0x8012FCF8 | XAudioQueryDriverPerformance | |
510 | 0x01FE | 0x8012CE30 | XAudioGetRenderDriverThread | |
511 | 0x01FF | 0x8012CE48 | XAudioGetSpeakerConfig | |
512 | 0x0200 | 0x8012D5D8 | XAudioSetSpeakerConfig | |
513 | 0x0201 | 0x800D20D8 | NicSetUnicastAddress | |
514 | 0x0202 | 0x800D2160 | NicAttach | |
515 | 0x0203 | 0x800D21E8 | NicDetach | |
516 | 0x0204 | 0x800D2708 | NicXmit | |
517 | 0x0205 | 0x800D2258 | NicUpdateMcastMembership | |
518 | 0x0206 | 0x800D22C8 | NicFlushXmitQueue | |
519 | 0x0207 | 0x800D1F00 | NicShutdown | |
520 | 0x0208 | 0x800D27C0 | NicGetLinkState | |
521 | 0x0209 | 0x800D2330 | NicGetStats | |
522 | 0x020A | 0x800D23B0 | NicGetOpt | |
523 | 0x020B | 0x800D24A8 | NicSetOpt | |
524 | 0x020C | 0x8012BA58 | DrvSetSysReqCallback | |
525 | 0x020D | 0x8012BA80 | DrvSetUserBindingCallback | |
526 | 0x020E | 0x8012BAF8 | DrvSetContentStorageCallback | |
527 | 0x020F | 0x8012BB48 | DrvSetAutobind | |
528 | 0x0210 | 0x8012BD48 | DrvGetContentStorageNotification | |
529 | 0x0211 | 0x800E7860 | MtpdBeginTransaction | |
530 | 0x0212 | 0x800E7CA0 | MtpdCancelTransaction | |
531 | 0x0213 | 0x800E78F8 | MtpdEndTransaction | |
532 | 0x0214 | 0x800E6480 | MtpdGetCurrentDevices | |
533 | 0x0215 | 0x800E7A28 | MtpdReadData | |
534 | 0x0216 | 0x800E7990 | MtpdReadEvent | |
535 | 0x0217 | 0x800E7BB0 | MtpdResetDevice | |
536 | 0x0218 | 0x800E7AF0 | MtpdSendData | |
537 | 0x0219 | 0x800E7D90 | MtpdVerifyProximity | |
538 | 0x021A | 0x800E84A0 | XUsbcamSetCaptureMode | |
539 | 0x021B | 0x800E8B98 | XUsbcamGetConfig | |
540 | 0x021C | 0x800E8D00 | XUsbcamSetConfig | |
541 | 0x021D | 0x800E83F8 | XUsbcamGetState | |
542 | 0x021E | 0x800E8690 | XUsbcamReadFrame | |
543 | 0x021F | 0x800E8780 | XUsbcamSnapshot | |
544 | 0x0220 | 0x800E89C8 | XUsbcamSetView | |
545 | 0x0221 | 0x800E8B28 | XUsbcamGetView | |
546 | 0x0222 | 0x800E8240 | XUsbcamCreate | |
547 | 0x0223 | 0x800E8358 | XUsbcamDestroy | |
548 | 0x0224 | 0x801324F0 | XMACreateContext | |
549 | 0x0225 | 0x80131CB8 | XMAInitializeContext | |
550 | 0x0226 | 0x801324F8 | XMAReleaseContext | |
551 | 0x0227 | 0x80132500 | XMAEnableContext | |
552 | 0x0228 | 0x80132508 | XMADisableContext | |
553 | 0x0229 | 0x80131DB8 | XMAGetOutputBufferWriteOffset | |
554 | 0x022A | 0x80131DC8 | XMASetOutputBufferReadOffset | |
555 | 0x022B | 0x80131DD8 | XMAGetOutputBufferReadOffset | |
556 | 0x022C | 0x80131DE8 | XMASetOutputBufferValid | |
557 | 0x022D | 0x80131DF8 | XMAIsOutputBufferValid | |
558 | 0x022E | 0x80131E08 | XMASetInputBuffer0Valid | |
559 | 0x022F | 0x80131E18 | XMAIsInputBuffer0Valid | |
560 | 0x0230 | 0x80131E28 | XMASetInputBuffer1Valid | |
561 | 0x0231 | 0x80131E38 | XMAIsInputBuffer1Valid | |
562 | 0x0232 | 0x80131E48 | XMASetInputBuffer0 | |
563 | 0x0233 | 0x80131E98 | XMASetInputBuffer1 | |
564 | 0x0234 | 0x80131EE8 | XMAGetPacketMetadata | |
565 | 0x0235 | 0x80132810 | XMABlockWhileInUse | |
566 | 0x0236 | 0x80131EF8 | XMASetLoopData | |
567 | 0x0237 | 0x80131F58 | XMASetInputBufferReadOffset | |
568 | 0x0238 | 0x80131F68 | XMAGetInputBufferReadOffset | |
569 | 0x0239 | 0x80066518 | ExIsBetaFeatureEnabled | |
570 | 0x023A | 0x80108C00 | XeKeysGetFactoryChallenge | |
571 | 0x023B | 0x80108C68 | XeKeysSetFactoryResponse | |
572 | 0x023C | 0x8010B920 | XeKeysInitializeFuses | |
573 | 0x023D | 0x8010B9B0 | XeKeysSaveBootLoader | |
574 | 0x023E | 0x80108D80 | XeKeysSaveKeyVault | |
575 | 0x023F | 0x80108E40 | XeKeysGetStatus | |
576 | 0x0240 | 0x8010BA28 | XeKeysGeneratePrivateKey | |
577 | 0x0241 | 0x80108E70 | XeKeysGetKeyProperties | |
578 | 0x0242 | 0x80108E78 | XeKeysSetKey | |
579 | 0x0243 | 0x80108ED8 | XeKeysGenerateRandomKey | |
580 | 0x0244 | 0x80108EE0 | XeKeysGetKey | |
581 | 0x0245 | 0x80108F48 | XeKeysGetDigest | |
582 | 0x0246 | 0x80109010 | XeKeysGetConsoleID | |
583 | 0x0247 | 0x80109170 | XeKeysGetConsoleType | |
584 | 0x0248 | 0x801091B0 | XeKeysQwNeRsaPrvCrypt | |
585 | 0x0249 | 0x80109240 | XeKeysHmacSha | |
586 | 0x024A | 0x800F0768 | XInputdPassThroughRFCommand | |
587 | 0x024B | 0x801092B0 | XeKeysAesCbc | |
588 | 0x024C | 0x80109320 | XeKeysDes2Cbc | |
589 | 0x024D | 0x80109390 | XeKeysDesCbc | |
590 | 0x024E | 0x80109400 | XeKeysObscureKey | |
591 | 0x024F | 0x80109468 | XeKeysHmacShaUsingKey | |
592 | 0x0250 | 0x80108CD8 | XeKeysSaveBootLoaderEx | |
593 | 0x0251 | 0x801094D8 | XeKeysAesCbcUsingKey | |
594 | 0x0252 | 0x80109548 | XeKeysDes2CbcUsingKey | |
595 | 0x0253 | 0x801095B8 | XeKeysDesCbcUsingKey | |
596 | 0x0254 | 0x80109628 | XeKeysObfuscate | |
597 | 0x0255 | 0x801096F8 | XeKeysUnObfuscate | |
598 | 0x0256 | 0x80109B98 | XeKeysConsolePrivateKeySign | |
599 | 0x0257 | 0x8010BF20 | XeKeysConsoleSignatureVerification | |
600 | 0x0258 | 0x80109C90 | XeKeysVerifyRSASignature | |
601 | 0x0259 | 0x800B04C8 | StfsCreateDevice | |
602 | 0x025A | 0x800B02B8 | StfsControlDevice | |
603 | 0x025B | 0x800C8B90 | VdSwap | |
604 | 0x025C | 0x8017CDD8 | HalFsbInterruptCount | |
605 | 0x025D | 0x80109DF0 | XeKeysSaveSystemUpdate | |
606 | 0x025E | 0x8010C120 | XeKeysLockSystemUpdate | |
607 | 0x025F | 0x80109FF8 | XeKeysExecute | |
608 | 0x0260 | 0x8010A068 | XeKeysGetVersions | |
609 | 0x0261 | 0x800F6F00 | XInputdPowerDownDevice | |
610 | 0x0262 | 0x80061810 | AniBlockOnAnimation | |
611 | 0x0263 | 0x80061818 | AniTerminateAnimation | |
612 | 0x0264 | 0x800E83E8 | XUsbcamReset | |
613 | 0x0265 | 0x80061838 | AniSetLogo | |
614 | 0x0266 | 0x801A5754 | KeCertMonitorData | |
615 | 0x0267 | 0x80067BB0 | HalIsExecutingPowerDownDpc | |
616 | 0x0268 | 0x800CBA60 | VdInitializeEDRAM | |
617 | 0x0269 | 0x800CBC70 | VdRetrainEDRAM | |
618 | 0x026A | 0x800C9088 | VdRetrainEDRAMWorker | |
619 | 0x026B | 0x80186290 | VdHSIOTrainCount | |
620 | 0x026C | 0x800680B8 | HalGetPowerUpCause | |
621 | 0x026D | 0x80186264 | VdHSIOTrainingStatus | |
622 | 0x026E | 0x801ED430 | RgcBindInfo | |
623 | 0x026F | 0x800C4E78 | VdReadEEDIDBlock | |
624 | 0x0270 | 0x800C3948 | VdEnumerateVideoModes | |
625 | 0x0271 | 0x800BC7D8 | VdEnableHDCP | |
626 | 0x0272 | 0x800BB848 | VdRegisterHDCPNotification | |
627 | 0x0273 | 0x800E5160 | HidReadMouseChanges | |
628 | 0x0274 | 0x800B9518 | DumpSetCollectionFacility | |
629 | 0x0275 | 0x8007B848 | XexTransformImageKey | |
630 | 0x0276 | 0x8012D5F0 | XAudioOverrideSpeakerConfig | |
631 | 0x0277 | 0x800F5498 | XInputdReadTextKeystroke | |
632 | 0x0278 | 0x8012BB88 | DrvXenonButtonPressed | |
633 | 0x0279 | 0x8012BBD0 | DrvBindToUser | |
634 | 0x027A | 0x8007D3F0 | XexGetModuleImportVersions | |
635 | 0x027B | 0x80088F58 | RtlComputeCrc32 | |
636 | 0x027C | 0x8010A070 | XeKeysSetRevocationList | |
637 | 0x027D | 0x800679E0 | HalRegisterPowerDownCallback | |
638 | 0x027E | 0x800C3FE0 | VdGetDisplayDiscoveryData | |
639 | 0x027F | 0x800F6F28 | XInputdSendStayAliveRequest | |
640 | 0x0280 | 0x80101E30 | XVoicedSendVPort | |
641 | 0x0281 | 0x80101E80 | XVoicedGetBatteryStatus | |
642 | 0x0282 | 0x800F6A78 | XInputdFFGetDeviceInfo | |
643 | 0x0283 | 0x800F6AA0 | XInputdFFSetEffect | |
644 | 0x0284 | 0x800F6AC8 | XInputdFFUpdateEffect | |
645 | 0x0285 | 0x800F6AF0 | XInputdFFEffectOperation | |
646 | 0x0286 | 0x800F6B18 | XInputdFFDeviceControl | |
647 | 0x0287 | 0x800F6B40 | XInputdFFSetDeviceGain | |
648 | 0x0288 | 0x800F6B68 | XInputdFFCancelIo | |
649 | 0x0289 | 0x800F6B90 | XInputdFFSetRumble | |
650 | 0x028A | 0x80083830 | NtAllocateEncryptedMemory | |
651 | 0x028B | 0x80082FD8 | NtFreeEncryptedMemory | |
652 | 0x028C | 0x8010A630 | XeKeysExSaveKeyVault | |
653 | 0x028D | 0x8010A6B8 | XeKeysExSetKey | |
654 | 0x028E | 0x8010A718 | XeKeysExGetKey | |
655 | 0x028F | 0x8012BAA8 | DrvSetDeviceConfigChangeCallback | |
656 | 0x0290 | 0x8012BC18 | DrvDeviceConfigChange | |
657 | 0x0291 | 0x8006A630 | HalRegisterHdDvdRomNotification | |
658 | 0x0292 | 0x8010A900 | XeKeysSecurityInitialize | |
659 | 0x0293 | 0x8010A908 | XeKeysSecurityLoadSettings | |
660 | 0x0294 | 0x8010A970 | XeKeysSecuritySaveSettings | |
661 | 0x0295 | 0x8010BAB8 | XeKeysSecuritySetDetected | |
662 | 0x0296 | 0x8010A9E8 | XeKeysSecurityGetDetected | |
663 | 0x0297 | 0x8010BB60 | XeKeysSecuritySetActivated | |
664 | 0x0298 | 0x8010A9F0 | XeKeysSecurityGetActivated | |
665 | 0x0299 | 0x80108E30 | XeKeysReserved665 | |
666 | 0x029A | 0x80123078 | XexRegisterUsermodeModule | |
667 | 0x029B | 0x8010AE48 | XeKeysGetProtectedFlag | |
668 | 0x029C | 0x8010AEA0 | XeKeysSetProtectedFlag | |
669 | 0x029D | 0x80071B60 | KeEnablePFMInterrupt | |
670 | 0x029E | 0x800BAB90 | KeSetProfilerISR | |
671 | 0x029F | 0x800BAB90 | KeSetProfilerISR | |
672 | 0x02A0 | 0x800C3FC0 | VdStartDisplayDiscovery | |
673 | 0x02A1 | 0x800BBB60 | VdSetHDCPRevocationList | |
674 | 0x02A2 | 0x8010A780 | XeKeysGetUpdateSequence | |
675 | 0x02A3 | 0x8010ADE8 | XeKeysDvdAuthExActivate | |
676 | 0x02A4 | 0x800734FC | KeGetImagePageTableEntry | |
677 | 0x02A5 | 0x80067758 | HalRegisterBackgroundModeTransitionCallback | |
678 | 0x02A6 | 0x80061730 | AniStartBootAnimation | |
679 | 0x02A7 | 0x80068460 | HalClampUnclampOutputDACs | |
680 | 0x02A8 | 0x80068328 | HalPowerDownToBackgroundMode | |
681 | 0x02A9 | 0x80068378 | HalNotifyAddRemoveBackgroundTask | |
682 | 0x02AA | 0x80067840 | HalCallBackgroundModeNotificationRoutines | |
683 | 0x02AB | 0x8017CDDC | HalFsbResetCount | |
684 | 0x02AC | 0x80069DF0 | HalGetMemoryInformation | |
685 | 0x02AD | 0x800F5550 | XInputdGetLastTextInputTime | |
686 | 0x02AE | 0x800BFE08 | VdEnableWMAProOverHDMI | |
687 | 0x02AF | 0x8010B620 | XeKeysRevokeSaveSettings | |
688 | 0x02B0 | 0x800F5580 | XInputdSetTextMessengerIndicator | |
689 | 0x02B1 | 0x8014ADD0 | MicDeviceRequest | |
690 | 0x02B2 | 0x8010B6C0 | XeKeysGetMediaID | |
691 | 0x02B3 | 0x80108E30 | XeKeysReserved665 | |
692 | 0x02B4 | 0x80070F38 | KeGetVidInfo | |
693 | 0x02B5 | 0x80068480 | HalNotifyBackgroundModeTransitionComplete | |
694 | 0x02B6 | 0x8006AB08 | IoAcquireCancelSpinLock | |
695 | 0x02B7 | 0x8006AB18 | IoReleaseCancelSpinLock | |
696 | 0x02B8 | 0x8006DDA8 | NtCancelIoFile | |
697 | 0x02B9 | 0x8006DE90 | NtCancelIoFileEx | |
698 | 0x02BA | 0x80069C50 | HalFinalizePowerLossRecovery | |
699 | 0x02BB | 0x80069870 | HalSetPowerLossRecovery | |
700 | 0x02BC | 0x80065768 | ExReadModifyWriteXConfigSettingUlong | |
701 | 0x02BD | 0x80067A18 | HalRegisterXamPowerDownCallback | |
702 | 0x02BE | 0x80064C18 | ExCancelAlarm | |
703 | 0x02BF | 0x80064B10 | ExInitializeAlarm | |
704 | 0x02C0 | 0x80064B28 | ExSetAlarm | |
705 | 0x02C1 | 0x800700A0 | XexActivationGetNonce | |
706 | 0x02C2 | 0x800700A8 | XexActivationSetLicense | |
707 | 0x02C3 | 0x8006FD58 | IptvSetBoundaryKey | |
708 | 0x02C4 | 0x8006FDF8 | IptvSetSessionKey | |
709 | 0x02C5 | 0x8006FE80 | IptvVerifyOmac1Signature | |
710 | 0x02C6 | 0x8006FF40 | IptvGetAesCtrTransform | |
711 | 0x02C7 | 0x80096EA8 | SataCdRomRecordReset | |
712 | 0x02C8 | 0x800F6588 | XInputdSetTextDeviceKeyLocks | |
713 | 0x02C9 | 0x800F5660 | XInputdGetTextDeviceKeyLocks | |
714 | 0x02CA | 0x80070128 | XexActivationVerifyOwnership | |
715 | 0x02CB | 0x800BAB90 | XexDisableVerboseDbgPrint | |
716 | 0x02CC | 0x80148B58 | SvodCreateDevice | |
717 | 0x02CD | 0x80123078 | RtlCaptureStackBackTrace | |
718 | 0x02CE | 0x8010BE50 | XeKeysRevokeUpdateDynamic | |
719 | 0x02CF | 0x80123078 | XexRegisterUsermodeModule | |
720 | 0x02D0 | 0x80065810 | ExRegisterXConfigNotification | |
721 | 0x02D1 | 0x8010A9F8 | XeKeysSecuritySetStat | |
722 | 0x02D2 | 0x800C6E08 | VdQueryRealVideoMode | |
723 | 0x02D3 | 0x8007BB68 | XexReserveCodeBuffer | |
724 | 0x02D4 | 0x8012E2C0 | XAudioSuspendRenderDriverClients | |
725 | 0x02D5 | 0x8006FFE8 | IptvGetSessionKeyHash | |
726 | 0x02D6 | 0x800BE4F0 | VdSetCGMSState | |
727 | 0x02D7 | 0x800BE470 | VdSetSCMSState | |
728 | 0x02D8 | 0x80073A50 | KeFlushMultipleTb | |
729 | 0x02D9 | 0x800C8768 | VdGetOption | |
730 | 0x02DA | 0x800C8660 | VdSetOption | |
731 | 0x02DB | 0x8017217C | UsbdBootEnumerationDoneEvent | |
732 | 0x02DC | 0x80170C10 | StfsDeviceErrorEvent | |
733 | 0x02DD | 0x80064260 | ExTryToAcquireReadWriteLockExclusive | |
734 | 0x02DE | 0x80064360 | ExTryToAcquireReadWriteLockShared | |
735 | 0x02DF | 0x8007B8D0 | XexSetLastKdcTime | |
736 | 0x02E0 | 0x800F6EC0 | XInputdControl | |
737 | 0x02E1 | 0x80101328 | RmcDeviceRequest | |
738 | 0x02E2 | 0x80129698 | LDIResetDecompression | |
739 | 0x02E3 | 0x800D1F38 | NicRegisterDevice | |
740 | 0x02E4 | 0x800D69D8 | UsbdAddDeviceComplete | |
741 | 0x02E5 | 0x800D82E8 | UsbdCancelAsyncTransfer | |
742 | 0x02E6 | 0x800D8528 | UsbdGetDeviceSpeed | |
743 | 0x02E7 | 0x800D8600 | UsbdGetDeviceTopology | |
744 | 0x02E8 | 0x800D83E0 | UsbdGetEndpointDescriptor | |
745 | 0x02E9 | 0x800D8748 | UsbdIsDeviceAuthenticated | |
746 | 0x02EA | 0x800D8180 | UsbdOpenDefaultEndpoint | |
747 | 0x02EB | 0x800D81A0 | UsbdOpenEndpoint | |
748 | 0x02EC | 0x800D8278 | UsbdQueueAsyncTransfer | |
749 | 0x02ED | 0x800D81F8 | UsbdQueueCloseDefaultEndpoint | |
750 | 0x02EE | 0x800D8238 | UsbdQueueCloseEndpoint | |
751 | 0x02EF | 0x800D80E8 | UsbdRemoveDeviceComplete | |
752 | 0x02F0 | 0x80073C10 | KeRemoveQueueApc | |
753 | 0x02F1 | 0x8017218C | UsbdDriverLoadRequiredEvent | |
754 | 0x02F2 | 0x800D9020 | UsbdGetRequiredDrivers | |
755 | 0x02F3 | 0x800D90B0 | UsbdRegisterDriverObject | |
756 | 0x02F4 | 0x800D90F8 | UsbdUnregisterDriverObject | |