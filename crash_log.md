Crash log
```
Sven-2:test_ar sven$ flutter run -v
[  +38 ms] executing: sysctl hw.optional.arm64
[   +9 ms] Exit code 0 from: sysctl hw.optional.arm64
[        ] hw.optional.arm64: 1
[   +2 ms] executing: [/Users/sven/flutterSdk/flutter/] git -c
log.showSignature=false log -n 1 --pretty=format:%H
[  +13 ms] Exit code 0 from: git -c log.showSignature=false log -n 1
--pretty=format:%H
[        ] f1875d570e39de09040c8f79aa13cc56baab8db1
[        ] executing: [/Users/sven/flutterSdk/flutter/] git tag --points-at
f1875d570e39de09040c8f79aa13cc56baab8db1
[  +19 ms] Exit code 0 from: git tag --points-at
f1875d570e39de09040c8f79aa13cc56baab8db1
[        ] 3.0.5
[   +3 ms] executing: [/Users/sven/flutterSdk/flutter/] git rev-parse
--abbrev-ref --symbolic @{u}
[  +11 ms] Exit code 128 from: git rev-parse --abbrev-ref --symbolic @{u}
[        ] fatal: no upstream configured for branch '3.0.5'
[  +24 ms] executing: [/Users/sven/flutterSdk/flutter/] git rev-parse
--abbrev-ref HEAD
[  +12 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
[        ] heads/3.0.5
[  +20 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping
update.
[   +1 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required,
skipping update.
[  +18 ms] executing: /Users/sven/androidsdk/platform-tools/adb devices -l
[   +7 ms] executing: sysctl hw.optional.arm64
[   +4 ms] Exit code 0 from: sysctl hw.optional.arm64
[        ] hw.optional.arm64: 1
[        ] executing: /usr/bin/arch -arm64e xcrun xcodebuild -version
[ +100 ms] Exit code 0 from: /usr/bin/arch -arm64e xcrun xcodebuild -version
[        ] Xcode 13.4
           Build version 13F17a
[        ] executing: /usr/bin/arch -arm64e xcrun xcdevice list --timeout 2
[   +1 ms] /usr/bin/arch -arm64e xcrun simctl list --json devices
[        ] executing: /usr/bin/arch -arm64e xcrun simctl list --json devices
[   +1 ms] executing: /usr/bin/arch -arm64e xcrun simctl list
[  +64 ms] Exit code 0 from: /usr/bin/arch -arm64e xcrun simctl list
[        ] == Device Types ==
           iPhone 4s (com.apple.CoreSimulator.SimDeviceType.iPhone-4s)
           iPhone 5 (com.apple.CoreSimulator.SimDeviceType.iPhone-5)
           iPhone 5s (com.apple.CoreSimulator.SimDeviceType.iPhone-5s)
           iPhone 6 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6-Plus)
           iPhone 6 (com.apple.CoreSimulator.SimDeviceType.iPhone-6)
           iPhone 6s (com.apple.CoreSimulator.SimDeviceType.iPhone-6s)
           iPhone 6s Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-6s-Plus)
           iPhone SE (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE)
           iPhone 7 (com.apple.CoreSimulator.SimDeviceType.iPhone-7)
           iPhone 7 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-7-Plus)
           iPhone 8 (com.apple.CoreSimulator.SimDeviceType.iPhone-8)
           iPhone 8 Plus (com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus)
           iPhone X (com.apple.CoreSimulator.SimDeviceType.iPhone-X)
           iPhone Xs (com.apple.CoreSimulator.SimDeviceType.iPhone-XS)
           iPhone Xs Max (com.apple.CoreSimulator.SimDeviceType.iPhone-XS-Max)
           iPhone Xʀ (com.apple.CoreSimulator.SimDeviceType.iPhone-XR)
           iPhone 11 (com.apple.CoreSimulator.SimDeviceType.iPhone-11)
           iPhone 11 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro)
           iPhone 11 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max)
           iPhone SE (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generation-)
           iPhone 12 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini)
           iPhone 12 (com.apple.CoreSimulator.SimDeviceType.iPhone-12)
           iPhone 12 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro)
           iPhone 12 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max)
           iPhone 13 Pro (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro)
           iPhone 13 Pro Max
           (com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max)
           iPhone 13 mini (com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini)
           iPhone 13 (com.apple.CoreSimulator.SimDeviceType.iPhone-13)
           iPhone SE (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generation)
           iPod touch (7th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-generation-)
           iPad 2 (com.apple.CoreSimulator.SimDeviceType.iPad-2)
           iPad Retina (com.apple.CoreSimulator.SimDeviceType.iPad-Retina)
           iPad Air (com.apple.CoreSimulator.SimDeviceType.iPad-Air)
           iPad mini 2 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-2)
           iPad mini 3 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-3)
           iPad mini 4 (com.apple.CoreSimulator.SimDeviceType.iPad-mini-4)
           iPad Air 2 (com.apple.CoreSimulator.SimDeviceType.iPad-Air-2)
           iPad Pro (9.7-inch)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-)
           iPad Pro (12.9-inch) (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro)
           iPad (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--5th-generation-)
           iPad Pro (12.9-inch) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---2nd-gene
           ration-)
           iPad Pro (10.5-inch)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--10-5-inch-)
           iPad (6th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--6th-generation-)
           iPad (7th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--7th-generation-)
           iPad Pro (11-inch) (1st generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch-)
           iPad Pro (12.9-inch) (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---3rd-gene
           ration-)
           iPad Pro (11-inch) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch---2nd-genera
           tion-)
           iPad Pro (12.9-inch) (4th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---4th-gene
           ration-)
           iPad mini (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-mini--5th-generation-)
           iPad Air (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air--3rd-generation-)
           iPad (8th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad--8th-generation-)
           iPad (9th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation)
           iPad Air (4th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th-generation-)
           iPad Pro (11-inch) (3rd generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-generatio
           n)
           iPad Pro (12.9-inch) (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th-generat
           ion)
           iPad Air (5th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generation)
           iPad mini (6th generation)
           (com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generation)
           Apple TV (com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p)
           Apple TV 4K (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-4K)
           Apple TV 4K (at 1080p)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-1080p)
           Apple TV 4K (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-4K)
           Apple TV 4K (at 1080p) (2nd generation)
           (com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-generation-108
           0p)
           Apple Watch - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-38mm)
           Apple Watch - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-42mm)
           Apple Watch Series 2 - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-38mm)
           Apple Watch Series 2 - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-2-42mm)
           Apple Watch Series 3 - 38mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-38mm)
           Apple Watch Series 3 - 42mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-3-42mm)
           Apple Watch Series 4 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-40mm)
           Apple Watch Series 4 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-4-44mm)
           Apple Watch Series 5 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-40mm)
           Apple Watch Series 5 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-44mm)
           Apple Watch SE - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-40mm)
           Apple Watch SE - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-SE-44mm)
           Apple Watch Series 6 - 40mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-40mm)
           Apple Watch Series 6 - 44mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-44mm)
           Apple Watch Series 7 - 41mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-41mm)
           Apple Watch Series 7 - 45mm
           (com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-45mm)
           == Runtimes ==
           iOS 15.5 (15.5 - 19F70) - com.apple.CoreSimulator.SimRuntime.iOS-15-5
           tvOS 15.4 (15.4 - 19L439) -
           com.apple.CoreSimulator.SimRuntime.tvOS-15-4
           watchOS 8.5 (8.5 - 19T241) -
           com.apple.CoreSimulator.SimRuntime.watchOS-8-5
           == Devices ==
           -- iOS 15.5 --
               iPhone 8 (57A7585D-BB7D-49BE-9F2F-E270CCDDA27B) (Shutdown) 
               iPhone 8 Plus (E35854BC-8194-4F9E-BD43-19EC37D4E306) (Shutdown) 
               iPhone 11 (D31DDCCB-531C-443A-B773-AB09078CC624) (Shutdown) 
               iPhone 11 Pro (2F5B90C2-9E4C-4EAF-8997-9BC5E37492EF) (Shutdown) 
               iPhone 11 Pro Max (6A0E3A3C-7C23-45E8-9590-22BE14E1C0B9)
               (Shutdown)
               iPhone 12 mini (EF1A6DE4-8831-4E58-AB54-ECEE82C5E729) (Shutdown) 
               iPhone 12 (728DB7C8-ECA5-4019-86E6-F4C55740388B) (Shutdown) 
               iPhone 12 Pro (8C95D63C-0CA2-4182-9E62-B214E406BF73) (Shutdown) 
               iPhone 12 Pro Max (16ACD889-D3A2-456A-8A9C-D1C96C47787D)
               (Shutdown)
               iPhone 13 Pro (2E745365-E7EF-4F72-8C93-6164760860B8) (Shutdown) 
               iPhone 13 Pro Max (9307F5B5-5103-488A-8894-609A3EAEA7DB)
               (Shutdown)
               iPhone 13 mini (0D50093C-029A-44D1-8574-629DE95CAB6E) (Shutdown) 
               iPhone 13 (AB8E0EAC-1A54-4B60-9824-53675B1F2929) (Shutdown) 
               iPhone SE (3rd generation) (404ADD57-3A3F-40BF-8555-DF70E769CCA7)
               (Shutdown)
               iPod touch (7th generation)
               (701CA2C2-32A0-4F15-94E8-B8ABE8A218C9) (Shutdown)
               iPad Pro (9.7-inch) (922D42C6-4961-4A2C-943D-53BE0C90156D)
               (Shutdown)
               iPad (9th generation) (FA68E295-3378-412A-A88F-AD83F92BCB18)
               (Shutdown)
               iPad Pro (11-inch) (3rd generation)
               (D8C25686-3142-4EDB-981D-5A054309576C) (Shutdown)
               iPad Pro (12.9-inch) (5th generation)
               (1524E474-00F1-4BA6-BAF0-FD84F1D13199) (Shutdown)
               iPad Air (5th generation) (3B12671F-4287-4208-98E2-138946EF35C3)
               (Shutdown)
               iPad mini (6th generation) (888EC52F-1343-435A-905A-ABF6395538AE)
               (Shutdown)
           -- tvOS 15.4 --
               Apple TV (E7F51542-D3A4-4A98-AEE4-DB3D25C03B30) (Shutdown) 
               Apple TV 4K (2nd generation)
               (5050286E-97C5-40A6-8245-14DCF7A2C88F) (Shutdown)
               Apple TV 4K (at 1080p) (2nd generation)
               (EFC2896C-B618-48CC-917B-DF84890797FA) (Shutdown)
           -- watchOS 8.5 --
               Apple Watch Series 5 - 40mm
               (5CCC6BA6-9AB5-49A3-868B-ACA7F5090685) (Shutdown)
               Apple Watch Series 5 - 44mm
               (4FA0564A-3172-4988-85CB-B4B73F5C803F) (Shutdown)
               Apple Watch Series 6 - 40mm
               (811ABF26-CAA6-46DB-8BBD-B153C7D5325E) (Shutdown)
               Apple Watch Series 6 - 44mm
               (2CC135FA-DEEE-4D53-8C3C-5689D3EE985D) (Shutdown)
               Apple Watch Series 7 - 41mm
               (DCDC3F26-296E-4212-A182-E040FB8F1993) (Shutdown)
               Apple Watch Series 7 - 45mm
               (390E8F15-EB7A-4015-9855-973C4FB786F5) (Shutdown)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.iOS-14-3 --
               iPhone 8 (E26AA136-9D54-4B90-B453-EB3604C546B5) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 8 Plus (F431CC59-7EA7-4BA4-8274-C385640F4BD4) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 (0C193537-6648-4904-B599-BC92603C0B07) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro (BC63CD65-FB37-4FB6-98B3-8CFE0F4054E1) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro Max (ACC30E9F-0B72-41F0-945F-42D1DB0D79C8)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone SE (2nd generation) (5C4FA74B-F852-42FA-A141-65719084555E)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 mini (793D9CD1-6D5B-4F1D-AE1A-643BF99E25AC) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 (8B54BF75-8C84-45DD-8761-3B052E57570C) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro (95DD4564-21EC-4CC4-924D-D576D0FB6B1A) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro Max (A5CA040A-69C5-4329-9F57-B99C235FCC96)
               (Shutdown) (unavailable, runtime profile not found)
               iPod touch (7th generation)
               (5461FACB-D346-4C09-B25C-98B22F697AC1) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (9.7-inch) (6F93397C-E531-4150-81A3-F6CE74A4119D)
               (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (11-inch) (2nd generation)
               (0D16B05F-9666-4BC8-9E87-77420B8609FB) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (12.9-inch) (4th generation)
               (2CE7EC63-AC15-4659-86B1-5822696234DE) (Shutdown) (unavailable,
               runtime profile not found)
               iPad (8th generation) (298E2EA1-F845-4EE7-B604-6BE7B502F865)
               (Shutdown) (unavailable, runtime profile not found)
               iPad Air (4th generation) (3893174F-4967-4249-9011-005B73536AB2)
               (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.iOS-14-5 --
               iPhone 11 (B1CFCEA9-D7D4-40FC-8F74-60258F967321) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 (7416345D-EDF8-4E51-9158-6DF745576764) (Shutdown)
               (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.iOS-15-4 --
               iPhone 8 (B8AC0B44-C090-46E4-B435-DAB11349B9F5) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 8 Plus (F2909AD4-9556-461D-AA72-BAFF63F130FB) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 (B1C6C4E5-FCB6-48A2-B3E4-7B20291B8B8C) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro (56A6240E-22E8-44BF-B9F8-76A516D31896) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 11 Pro Max (EA7B7EF3-28CC-4547-BCA9-E53A1ED5D681)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 12 mini (DD05B7D3-6343-4D1E-B46D-90DD0F3419CD) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 (2AA253D1-E8F0-4E73-97E0-0E5A76B20D6C) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro (FB582C89-9941-4465-AE0E-180202BA7AE4) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 12 Pro Max (9D93D2C4-A3F2-44F4-9A6F-6EFEC82F0D62)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 Pro (F1355D88-2861-4571-9CE2-AB896A38FC07) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 13 Pro Max (622E7913-82BB-4310-962B-C23BFF56A1DA)
               (Shutdown) (unavailable, runtime profile not found)
               iPhone 13 mini (78EF014A-A69F-46E4-8343-ED246A85C100) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone 13 (78171EB2-438A-48A6-BBDC-B18552E22305) (Shutdown)
               (unavailable, runtime profile not found)
               iPhone SE (3rd generation) (7F34D7B6-8352-4625-A79F-DDE71C9AD4D2)
               (Shutdown) (unavailable, runtime profile not found)
               iPod touch (7th generation)
               (E1A05F94-D652-49DC-9575-AEBC48F27D3D) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (9.7-inch) (E6701601-18AE-4EA7-95D3-AC2F698FE2A8)
               (Shutdown) (unavailable, runtime profile not found)
               iPad (9th generation) (7585DB5A-2BF6-416E-A9A9-AF9138B9B283)
               (Shutdown) (unavailable, runtime profile not found)
               iPad Pro (11-inch) (3rd generation)
               (BC716F0E-3F9F-433B-8482-925FD0C15351) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Pro (12.9-inch) (5th generation)
               (2784D248-12A7-44DB-B943-6420368D73B9) (Shutdown) (unavailable,
               runtime profile not found)
               iPad Air (5th generation) (D5F6D19C-6581-4A3C-8C0B-59AFC1C62805)
               (Shutdown) (unavailable, runtime profile not found)
               iPad mini (6th generation) (619FCD2A-8A61-46A4-911B-A16D918A869A)
               (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.tvOS-14-3 --
               Apple TV (46B9B16C-9453-422C-A709-7E410EA1C5F7) (Shutdown)
               (unavailable, runtime profile not found)
               Apple TV 4K (CE9C2DEE-D79D-415D-92CB-1D61B9DCABA4) (Shutdown)
               (unavailable, runtime profile not found)
               Apple TV 4K (at 1080p) (888ECFD4-E4D5-446D-BC41-630B9A74B0E3)
               (Shutdown) (unavailable, runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.watchOS-7-2 --
               Apple Watch Series 5 - 40mm
               (93D04604-717B-451F-A58A-61F3D2FE3BE2) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 5 - 44mm
               (BACA1129-3F2D-40BD-82B3-4E21B433FABC) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 6 - 40mm
               (34A4CEB1-C8AD-43A6-8DB4-CEA6D088679F) (Shutdown) (unavailable,
               runtime profile not found)
               Apple Watch Series 6 - 44mm
               (5CA0C932-5437-44F8-9639-F3D5F3D1A282) (Shutdown) (unavailable,
               runtime profile not found)
           -- Unavailable: com.apple.CoreSimulator.SimRuntime.watchOS-7-4 --
               Apple Watch Series 5 - 44mm
               (5D7BB08E-F131-4862-8B83-93B6D0777C2E) (Shutdown) (unavailable,
               runtime profile not found)
           == Device Pairs ==
           E64A7A1F-20FB-450F-AAAA-AB5DB9F07BF9 (active, disconnected)
               Watch: Apple Watch Series 5 - 40mm
               (5CCC6BA6-9AB5-49A3-868B-ACA7F5090685) (Shutdown)
               Phone: iPhone 12 Pro (8C95D63C-0CA2-4182-9E62-B214E406BF73)
               (Shutdown)
           710F3E5B-2355-40CF-8010-0C17C2CD9FB6 (active, disconnected)
               Watch: Apple Watch Series 5 - 44mm
               (4FA0564A-3172-4988-85CB-B4B73F5C803F) (Shutdown)
               Phone: iPhone 12 Pro Max (16ACD889-D3A2-456A-8A9C-D1C96C47787D)
               (Shutdown)
           A400576B-9957-43B3-BFD3-3FBD9B817522 (active, disconnected)
               Watch: Apple Watch Series 6 - 40mm
               (811ABF26-CAA6-46DB-8BBD-B153C7D5325E) (Shutdown)
               Phone: iPhone 13 Pro (2E745365-E7EF-4F72-8C93-6164760860B8)
               (Shutdown)
           D5B1AD00-9F18-418D-A323-6ECC718279A8 (active, disconnected)
               Watch: Apple Watch Series 6 - 44mm
               (2CC135FA-DEEE-4D53-8C3C-5689D3EE985D) (Shutdown)
               Phone: iPhone 13 Pro Max (9307F5B5-5103-488A-8894-609A3EAEA7DB)
               (Shutdown)
           30C0E1A2-91A1-4DA3-B32A-919E47813B32 (active, disconnected)
               Watch: Apple Watch Series 7 - 41mm
               (DCDC3F26-296E-4212-A182-E040FB8F1993) (Shutdown)
               Phone: iPhone 13 mini (0D50093C-029A-44D1-8574-629DE95CAB6E)
               (Shutdown)
           40BECAF1-65CF-4931-90B2-BC7281D2AEDA (active, disconnected)
               Watch: Apple Watch Series 7 - 45mm
               (390E8F15-EB7A-4015-9855-973C4FB786F5) (Shutdown)
               Phone: iPhone 13 (AB8E0EAC-1A54-4B60-9824-53675B1F2929)
               (Shutdown)
           4FA9EED6-6675-46F6-80D9-7EBFCBD324D4 (unavailable)
               Watch: Apple Watch Series 5 - 40mm
               (93D04604-717B-451F-A58A-61F3D2FE3BE2) (Shutdown)
               Phone: iPhone 12 mini (793D9CD1-6D5B-4F1D-AE1A-643BF99E25AC)
               (Shutdown)
           03812BB0-55D0-4A3E-A46A-69E3E20E222A (unavailable)
               Watch: Apple Watch Series 5 - 44mm
               (BACA1129-3F2D-40BD-82B3-4E21B433FABC) (Shutdown)
               Phone: iPhone 12 (8B54BF75-8C84-45DD-8761-3B052E57570C)
               (Shutdown)
           996F8F03-8D72-413F-B0D6-49E8872EF5C4 (unavailable)
               Watch: Apple Watch Series 6 - 40mm
               (34A4CEB1-C8AD-43A6-8DB4-CEA6D088679F) (Shutdown)
               Phone: iPhone 12 Pro (95DD4564-21EC-4CC4-924D-D576D0FB6B1A)
               (Shutdown)
           2E819A7C-14C0-4F05-9157-35DA5818C71F (unavailable)
               Watch: Apple Watch Series 6 - 44mm
               (5CA0C932-5437-44F8-9639-F3D5F3D1A282) (Shutdown)
               Phone: iPhone 12 Pro Max (A5CA040A-69C5-4329-9F57-B99C235FCC96)
               (Shutdown)
           EB159942-7118-46EE-933C-C480EAB67F9D (unavailable)
               Watch: Apple Watch Series 5 - 44mm
               (5D7BB08E-F131-4862-8B83-93B6D0777C2E) (Shutdown)
               Phone: iPhone 12 (7416345D-EDF8-4E51-9158-6DF745576764)
               (Shutdown)
[  +92 ms] {
             "devices" : {
               "com.apple.CoreSimulator.SimRuntime.watchOS-8-5" : [
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   CCC6BA6-9AB5-49A3-868B-ACA7F5090685\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5CCC6BA6-9AB5-4
                   9A3-868B-ACA7F5090685",
                   "udid" : "5CCC6BA6-9AB5-49A3-868B-ACA7F5090685",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-4
                   0mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 5 - 40mm"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/4
                   FA0564A-3172-4988-85CB-B4B73F5C803F\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/4FA0564A-3172-4
                   988-85CB-B4B73F5C803F",
                   "udid" : "4FA0564A-3172-4988-85CB-B4B73F5C803F",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-4
                   4mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 5 - 44mm"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/8
                   11ABF26-CAA6-46DB-8BBD-B153C7D5325E\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/811ABF26-CAA6-4
                   6DB-8BBD-B153C7D5325E",
                   "udid" : "811ABF26-CAA6-46DB-8BBD-B153C7D5325E",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-4
                   0mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 6 - 40mm"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   CC135FA-DEEE-4D53-8C3C-5689D3EE985D\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2CC135FA-DEEE-4
                   D53-8C3C-5689D3EE985D",
                   "udid" : "2CC135FA-DEEE-4D53-8C3C-5689D3EE985D",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-4
                   4mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 6 - 44mm"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/D
                   CDC3F26-296E-4212-A182-E040FB8F1993\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/DCDC3F26-296E-4
                   212-A182-E040FB8F1993",
                   "udid" : "DCDC3F26-296E-4212-A182-E040FB8F1993",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-4
                   1mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 7 - 41mm"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/3
                   90E8F15-EB7A-4015-9855-973C4FB786F5\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/390E8F15-EB7A-4
                   015-9855-973C4FB786F5",
                   "udid" : "390E8F15-EB7A-4015-9855-973C4FB786F5",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-7-4
                   5mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 7 - 45mm"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.iOS-14-3" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   26AA136-9D54-4B90-B453-EB3604C546B5\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/E26AA136-9D54-4
                   B90-B453-EB3604C546B5",
                   "udid" : "E26AA136-9D54-4B90-B453-EB3604C546B5",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                   "state" : "Shutdown",
                   "name" : "iPhone 8"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/F
                   431CC59-7EA7-4BA4-8274-C385640F4BD4\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/F431CC59-7EA7-4
                   BA4-8274-C385640F4BD4",
                   "udid" : "F431CC59-7EA7-4BA4-8274-C385640F4BD4",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus",
                   "state" : "Shutdown",
                   "name" : "iPhone 8 Plus"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/0
                   C193537-6648-4904-B599-BC92603C0B07\/data",
                   "dataPathSize" : 580751360,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/0C193537-6648-4
                   904-B599-BC92603C0B07",
                   "udid" : "0C193537-6648-4904-B599-BC92603C0B07",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                   "state" : "Shutdown",
                   "name" : "iPhone 11"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   C63CD65-FB37-4FB6-98B3-8CFE0F4054E1\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/BC63CD65-FB37-4
                   FB6-98B3-8CFE0F4054E1",
                   "udid" : "BC63CD65-FB37-4FB6-98B3-8CFE0F4054E1",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/A
                   CC30E9F-0B72-41F0-945F-42D1DB0D79C8\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/ACC30E9F-0B72-4
                   1F0-945F-42D1DB0D79C8",
                   "udid" : "ACC30E9F-0B72-41F0-945F-42D1DB0D79C8",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro Max"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   C4FA74B-F852-42FA-A141-65719084555E\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5C4FA74B-F852-4
                   2FA-A141-65719084555E",
                   "udid" : "5C4FA74B-F852-42FA-A141-65719084555E",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-SE--2nd-generat
                   ion-",
                   "state" : "Shutdown",
                   "name" : "iPhone SE (2nd generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   93D9CD1-6D5B-4F1D-AE1A-643BF99E25AC\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/793D9CD1-6D5B-4
                   F1D-AE1A-643BF99E25AC",
                   "udid" : "793D9CD1-6D5B-4F1D-AE1A-643BF99E25AC",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 mini"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/8
                   B54BF75-8C84-45DD-8761-3B052E57570C\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/8B54BF75-8C84-4
                   5DD-8761-3B052E57570C",
                   "udid" : "8B54BF75-8C84-45DD-8761-3B052E57570C",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                   "state" : "Shutdown",
                   "name" : "iPhone 12"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/9
                   5DD4564-21EC-4CC4-924D-D576D0FB6B1A\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/95DD4564-21EC-4
                   CC4-924D-D576D0FB6B1A",
                   "udid" : "95DD4564-21EC-4CC4-924D-D576D0FB6B1A",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/A
                   5CA040A-69C5-4329-9F57-B99C235FCC96\/data",
                   "dataPathSize" : 122601472,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/A5CA040A-69C5-4
                   329-9F57-B99C235FCC96",
                   "udid" : "A5CA040A-69C5-4329-9F57-B99C235FCC96",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro Max"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   461FACB-D346-4C09-B25C-98B22F697AC1\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5461FACB-D346-4
                   C09-B25C-98B22F697AC1",
                   "udid" : "5461FACB-D346-4C09-B25C-98B22F697AC1",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-genera
                   tion-",
                   "state" : "Shutdown",
                   "name" : "iPod touch (7th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/6
                   F93397C-E531-4150-81A3-F6CE74A4119D\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/6F93397C-E531-4
                   150-81A3-F6CE74A4119D",
                   "udid" : "6F93397C-E531-4150-81A3-F6CE74A4119D",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (9.7-inch)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/0
                   D16B05F-9666-4BC8-9E87-77420B8609FB\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/0D16B05F-9666-4
                   BC8-9E87-77420B8609FB",
                   "udid" : "0D16B05F-9666-4BC8-9E87-77420B8609FB",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--11-inch---2n
                   d-generation-",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (11-inch) (2nd generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   CE7EC63-AC15-4659-86B1-5822696234DE\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2CE7EC63-AC15-4
                   659-86B1-5822696234DE",
                   "udid" : "2CE7EC63-AC15-4659-86B1-5822696234DE",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--12-9-inch---
                   4th-generation-",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (12.9-inch) (4th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   98E2EA1-F845-4EE7-B604-6BE7B502F865\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/298E2EA1-F845-4
                   EE7-B604-6BE7B502F865",
                   "udid" : "298E2EA1-F845-4EE7-B604-6BE7B502F865",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad--8th-generation-"
                   ,
                   "state" : "Shutdown",
                   "name" : "iPad (8th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/3
                   893174F-4967-4249-9011-005B73536AB2\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/3893174F-4967-4
                   249-9011-005B73536AB2",
                   "udid" : "3893174F-4967-4249-9011-005B73536AB2",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Air--4th-generati
                   on-",
                   "state" : "Shutdown",
                   "name" : "iPad Air (4th generation)"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.iOS-15-4" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   8AC0B44-C090-46E4-B435-DAB11349B9F5\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/B8AC0B44-C090-4
                   6E4-B435-DAB11349B9F5",
                   "udid" : "B8AC0B44-C090-46E4-B435-DAB11349B9F5",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                   "state" : "Shutdown",
                   "name" : "iPhone 8"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/F
                   2909AD4-9556-461D-AA72-BAFF63F130FB\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/F2909AD4-9556-4
                   61D-AA72-BAFF63F130FB",
                   "udid" : "F2909AD4-9556-461D-AA72-BAFF63F130FB",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus",
                   "state" : "Shutdown",
                   "name" : "iPhone 8 Plus"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   1C6C4E5-FCB6-48A2-B3E4-7B20291B8B8C\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/B1C6C4E5-FCB6-4
                   8A2-B3E4-7B20291B8B8C",
                   "udid" : "B1C6C4E5-FCB6-48A2-B3E4-7B20291B8B8C",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                   "state" : "Shutdown",
                   "name" : "iPhone 11"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   6A6240E-22E8-44BF-B9F8-76A516D31896\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/56A6240E-22E8-4
                   4BF-B9F8-76A516D31896",
                   "udid" : "56A6240E-22E8-44BF-B9F8-76A516D31896",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   A7B7EF3-28CC-4547-BCA9-E53A1ED5D681\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/EA7B7EF3-28CC-4
                   547-BCA9-E53A1ED5D681",
                   "udid" : "EA7B7EF3-28CC-4547-BCA9-E53A1ED5D681",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro Max"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/D
                   D05B7D3-6343-4D1E-B46D-90DD0F3419CD\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/DD05B7D3-6343-4
                   D1E-B46D-90DD0F3419CD",
                   "udid" : "DD05B7D3-6343-4D1E-B46D-90DD0F3419CD",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 mini"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   AA253D1-E8F0-4E73-97E0-0E5A76B20D6C\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2AA253D1-E8F0-4
                   E73-97E0-0E5A76B20D6C",
                   "udid" : "2AA253D1-E8F0-4E73-97E0-0E5A76B20D6C",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                   "state" : "Shutdown",
                   "name" : "iPhone 12"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/F
                   B582C89-9941-4465-AE0E-180202BA7AE4\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/FB582C89-9941-4
                   465-AE0E-180202BA7AE4",
                   "udid" : "FB582C89-9941-4465-AE0E-180202BA7AE4",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/9
                   D93D2C4-A3F2-44F4-9A6F-6EFEC82F0D62\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/9D93D2C4-A3F2-4
                   4F4-9A6F-6EFEC82F0D62",
                   "udid" : "9D93D2C4-A3F2-44F4-9A6F-6EFEC82F0D62",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro Max"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/F
                   1355D88-2861-4571-9CE2-AB896A38FC07\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/F1355D88-2861-4
                   571-9CE2-AB896A38FC07",
                   "udid" : "F1355D88-2861-4571-9CE2-AB896A38FC07",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 Pro"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/6
                   22E7913-82BB-4310-962B-C23BFF56A1DA\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/622E7913-82BB-4
                   310-962B-C23BFF56A1DA",
                   "udid" : "622E7913-82BB-4310-962B-C23BFF56A1DA",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 Pro Max"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   8EF014A-A69F-46E4-8343-ED246A85C100\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/78EF014A-A69F-4
                   6E4-8343-ED246A85C100",
                   "udid" : "78EF014A-A69F-46E4-8343-ED246A85C100",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 mini"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   8171EB2-438A-48A6-BBDC-B18552E22305\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/78171EB2-438A-4
                   8A6-BBDC-B18552E22305",
                   "udid" : "78171EB2-438A-48A6-BBDC-B18552E22305",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                   "state" : "Shutdown",
                   "name" : "iPhone 13"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   F34D7B6-8352-4625-A79F-DDE71C9AD4D2\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/7F34D7B6-8352-4
                   625-A79F-DDE71C9AD4D2",
                   "udid" : "7F34D7B6-8352-4625-A79F-DDE71C9AD4D2",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generati
                   on",
                   "state" : "Shutdown",
                   "name" : "iPhone SE (3rd generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   1A05F94-D652-49DC-9575-AEBC48F27D3D\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/E1A05F94-D652-4
                   9DC-9575-AEBC48F27D3D",
                   "udid" : "E1A05F94-D652-49DC-9575-AEBC48F27D3D",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-genera
                   tion-",
                   "state" : "Shutdown",
                   "name" : "iPod touch (7th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   6701601-18AE-4EA7-95D3-AC2F698FE2A8\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/E6701601-18AE-4
                   EA7-95D3-AC2F698FE2A8",
                   "udid" : "E6701601-18AE-4EA7-95D3-AC2F698FE2A8",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (9.7-inch)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   585DB5A-2BF6-416E-A9A9-AF9138B9B283\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/7585DB5A-2BF6-4
                   16E-A9A9-AF9138B9B283",
                   "udid" : "7585DB5A-2BF6-416E-A9A9-AF9138B9B283",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation",
                   "state" : "Shutdown",
                   "name" : "iPad (9th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   C716F0E-3F9F-433B-8482-925FD0C15351\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/BC716F0E-3F9F-4
                   33B-8482-925FD0C15351",
                   "udid" : "BC716F0E-3F9F-433B-8482-925FD0C15351",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-g
                   eneration",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (11-inch) (3rd generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   784D248-12A7-44DB-B943-6420368D73B9\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2784D248-12A7-4
                   4DB-B943-6420368D73B9",
                   "udid" : "2784D248-12A7-44DB-B943-6420368D73B9",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th
                   -generation",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (12.9-inch) (5th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/D
                   5F6D19C-6581-4A3C-8C0B-59AFC1C62805\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/D5F6D19C-6581-4
                   A3C-8C0B-59AFC1C62805",
                   "udid" : "D5F6D19C-6581-4A3C-8C0B-59AFC1C62805",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generatio
                   n",
                   "state" : "Shutdown",
                   "name" : "iPad Air (5th generation)"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/6
                   19FCD2A-8A61-46A4-911B-A16D918A869A\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/619FCD2A-8A61-4
                   6A4-911B-A16D918A869A",
                   "udid" : "619FCD2A-8A61-46A4-911B-A16D918A869A",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generati
                   on",
                   "state" : "Shutdown",
                   "name" : "iPad mini (6th generation)"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.tvOS-14-3" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/4
                   6B9B16C-9453-422C-A709-7E410EA1C5F7\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/46B9B16C-9453-4
                   22C-A709-7E410EA1C5F7",
                   "udid" : "46B9B16C-9453-422C-A709-7E410EA1C5F7",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p",
                   "state" : "Shutdown",
                   "name" : "Apple TV"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/C
                   E9C2DEE-D79D-415D-92CB-1D61B9DCABA4\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/CE9C2DEE-D79D-4
                   15D-92CB-1D61B9DCABA4",
                   "udid" : "CE9C2DEE-D79D-415D-92CB-1D61B9DCABA4",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-4K",
                   "state" : "Shutdown",
                   "name" : "Apple TV 4K"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/8
                   88ECFD4-E4D5-446D-BC41-630B9A74B0E3\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/888ECFD4-E4D5-4
                   46D-BC41-630B9A74B0E3",
                   "udid" : "888ECFD4-E4D5-446D-BC41-630B9A74B0E3",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-1080p",
                   "state" : "Shutdown",
                   "name" : "Apple TV 4K (at 1080p)"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.iOS-14-5" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   1CFCEA9-D7D4-40FC-8F74-60258F967321\/data",
                   "dataPathSize" : 734871552,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/B1CFCEA9-D7D4-4
                   0FC-8F74-60258F967321",
                   "udid" : "B1CFCEA9-D7D4-40FC-8F74-60258F967321",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                   "state" : "Shutdown",
                   "name" : "iPhone 11"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   416345D-EDF8-4E51-9158-6DF745576764\/data",
                   "dataPathSize" : 13312000,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/7416345D-EDF8-4
                   E51-9158-6DF745576764",
                   "udid" : "7416345D-EDF8-4E51-9158-6DF745576764",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                   "state" : "Shutdown",
                   "name" : "iPhone 12"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.watchOS-7-2" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/9
                   3D04604-717B-451F-A58A-61F3D2FE3BE2\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/93D04604-717B-4
                   51F-A58A-61F3D2FE3BE2",
                   "udid" : "93D04604-717B-451F-A58A-61F3D2FE3BE2",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-4
                   0mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 5 - 40mm"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/B
                   ACA1129-3F2D-40BD-82B3-4E21B433FABC\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/BACA1129-3F2D-4
                   0BD-82B3-4E21B433FABC",
                   "udid" : "BACA1129-3F2D-40BD-82B3-4E21B433FABC",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-4
                   4mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 5 - 44mm"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/3
                   4A4CEB1-C8AD-43A6-8DB4-CEA6D088679F\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/34A4CEB1-C8AD-4
                   3A6-8DB4-CEA6D088679F",
                   "udid" : "34A4CEB1-C8AD-43A6-8DB4-CEA6D088679F",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-4
                   0mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 6 - 40mm"
                 },
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   CA0C932-5437-44F8-9639-F3D5F3D1A282\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5CA0C932-5437-4
                   4F8-9639-F3D5F3D1A282",
                   "udid" : "5CA0C932-5437-44F8-9639-F3D5F3D1A282",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-6-4
                   4mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 6 - 44mm"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.watchOS-7-4" : [
                 {
                   "availabilityError" : "runtime profile not found",
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   D7BB08E-F131-4862-8B83-93B6D0777C2E\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5D7BB08E-F131-4
                   862-8B83-93B6D0777C2E",
                   "udid" : "5D7BB08E-F131-4862-8B83-93B6D0777C2E",
                   "isAvailable" : false,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-Watch-Series-5-4
                   4mm",
                   "state" : "Shutdown",
                   "name" : "Apple Watch Series 5 - 44mm"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.tvOS-15-4" : [
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   7F51542-D3A4-4A98-AEE4-DB3D25C03B30\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/E7F51542-D3A4-4
                   A98-AEE4-DB3D25C03B30",
                   "udid" : "E7F51542-D3A4-4A98-AEE4-DB3D25C03B30",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-1080p",
                   "state" : "Shutdown",
                   "name" : "Apple TV"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   050286E-97C5-40A6-8245-14DCF7A2C88F\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/5050286E-97C5-4
                   0A6-8245-14DCF7A2C88F",
                   "udid" : "5050286E-97C5-40A6-8245-14DCF7A2C88F",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-genera
                   tion-4K",
                   "state" : "Shutdown",
                   "name" : "Apple TV 4K (2nd generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   FC2896C-B618-48CC-917B-DF84890797FA\/data",
                   "dataPathSize" : 0,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/EFC2896C-B618-4
                   8CC-917B-DF84890797FA",
                   "udid" : "EFC2896C-B618-48CC-917B-DF84890797FA",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.Apple-TV-4K-2nd-genera
                   tion-1080p",
                   "state" : "Shutdown",
                   "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                 }
               ],
               "com.apple.CoreSimulator.SimRuntime.iOS-15-5" : [
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/5
                   7A7585D-BB7D-49BE-9F2F-E270CCDDA27B\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/57A7585D-BB7D-4
                   9BE-9F2F-E270CCDDA27B",
                   "udid" : "57A7585D-BB7D-49BE-9F2F-E270CCDDA27B",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8",
                   "state" : "Shutdown",
                   "name" : "iPhone 8"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   35854BC-8194-4F9E-BD43-19EC37D4E306\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/E35854BC-8194-4
                   F9E-BD43-19EC37D4E306",
                   "udid" : "E35854BC-8194-4F9E-BD43-19EC37D4E306",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-8-Plus",
                   "state" : "Shutdown",
                   "name" : "iPhone 8 Plus"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/D
                   31DDCCB-531C-443A-B773-AB09078CC624\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/D31DDCCB-531C-4
                   43A-B773-AB09078CC624",
                   "udid" : "D31DDCCB-531C-443A-B773-AB09078CC624",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11",
                   "state" : "Shutdown",
                   "name" : "iPhone 11"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   F5B90C2-9E4C-4EAF-8997-9BC5E37492EF\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2F5B90C2-9E4C-4
                   EAF-8997-9BC5E37492EF",
                   "udid" : "2F5B90C2-9E4C-4EAF-8997-9BC5E37492EF",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/6
                   A0E3A3C-7C23-45E8-9590-22BE14E1C0B9\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/6A0E3A3C-7C23-4
                   5E8-9590-22BE14E1C0B9",
                   "udid" : "6A0E3A3C-7C23-45E8-9590-22BE14E1C0B9",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-11-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 11 Pro Max"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/E
                   F1A6DE4-8831-4E58-AB54-ECEE82C5E729\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/EF1A6DE4-8831-4
                   E58-AB54-ECEE82C5E729",
                   "udid" : "EF1A6DE4-8831-4E58-AB54-ECEE82C5E729",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-mini",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 mini"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   28DB7C8-ECA5-4019-86E6-F4C55740388B\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/728DB7C8-ECA5-4
                   019-86E6-F4C55740388B",
                   "udid" : "728DB7C8-ECA5-4019-86E6-F4C55740388B",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12",
                   "state" : "Shutdown",
                   "name" : "iPhone 12"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/8
                   C95D63C-0CA2-4182-9E62-B214E406BF73\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/8C95D63C-0CA2-4
                   182-9E62-B214E406BF73",
                   "udid" : "8C95D63C-0CA2-4182-9E62-B214E406BF73",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/1
                   6ACD889-D3A2-456A-8A9C-D1C96C47787D\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/16ACD889-D3A2-4
                   56A-8A9C-D1C96C47787D",
                   "udid" : "16ACD889-D3A2-456A-8A9C-D1C96C47787D",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-12-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 12 Pro Max"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/2
                   E745365-E7EF-4F72-8C93-6164760860B8\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/2E745365-E7EF-4
                   F72-8C93-6164760860B8",
                   "udid" : "2E745365-E7EF-4F72-8C93-6164760860B8",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 Pro"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/9
                   307F5B5-5103-488A-8894-609A3EAEA7DB\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/9307F5B5-5103-4
                   88A-8894-609A3EAEA7DB",
                   "udid" : "9307F5B5-5103-488A-8894-609A3EAEA7DB",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-Pro-Max",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 Pro Max"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/0
                   D50093C-029A-44D1-8574-629DE95CAB6E\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/0D50093C-029A-4
                   4D1-8574-629DE95CAB6E",
                   "udid" : "0D50093C-029A-44D1-8574-629DE95CAB6E",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13-mini",
                   "state" : "Shutdown",
                   "name" : "iPhone 13 mini"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/A
                   B8E0EAC-1A54-4B60-9824-53675B1F2929\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/AB8E0EAC-1A54-4
                   B60-9824-53675B1F2929",
                   "udid" : "AB8E0EAC-1A54-4B60-9824-53675B1F2929",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-13",
                   "state" : "Shutdown",
                   "name" : "iPhone 13"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/4
                   04ADD57-3A3F-40BF-8555-DF70E769CCA7\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/404ADD57-3A3F-4
                   0BF-8555-DF70E769CCA7",
                   "udid" : "404ADD57-3A3F-40BF-8555-DF70E769CCA7",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPhone-SE-3rd-generati
                   on",
                   "state" : "Shutdown",
                   "name" : "iPhone SE (3rd generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/7
                   01CA2C2-32A0-4F15-94E8-B8ABE8A218C9\/data",
                   "dataPathSize" : 123482112,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/701CA2C2-32A0-4
                   F15-94E8-B8ABE8A218C9",
                   "udid" : "701CA2C2-32A0-4F15-94E8-B8ABE8A218C9",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPod-touch--7th-genera
                   tion-",
                   "state" : "Shutdown",
                   "name" : "iPod touch (7th generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/9
                   22D42C6-4961-4A2C-943D-53BE0C90156D\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/922D42C6-4961-4
                   A2C-943D-53BE0C90156D",
                   "udid" : "922D42C6-4961-4A2C-943D-53BE0C90156D",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro--9-7-inch-",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (9.7-inch)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/F
                   A68E295-3378-412A-A88F-AD83F92BCB18\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/FA68E295-3378-4
                   12A-A88F-AD83F92BCB18",
                   "udid" : "FA68E295-3378-412A-A88F-AD83F92BCB18",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-9th-generation",
                   "state" : "Shutdown",
                   "name" : "iPad (9th generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/D
                   8C25686-3142-4EDB-981D-5A054309576C\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/D8C25686-3142-4
                   EDB-981D-5A054309576C",
                   "udid" : "D8C25686-3142-4EDB-981D-5A054309576C",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-11-inch-3rd-g
                   eneration",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (11-inch) (3rd generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/1
                   524E474-00F1-4BA6-BAF0-FD84F1D13199\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/1524E474-00F1-4
                   BA6-BAF0-FD84F1D13199",
                   "udid" : "1524E474-00F1-4BA6-BAF0-FD84F1D13199",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Pro-12-9-inch-5th
                   -generation",
                   "state" : "Shutdown",
                   "name" : "iPad Pro (12.9-inch) (5th generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/3
                   B12671F-4287-4208-98E2-138946EF35C3\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/3B12671F-4287-4
                   208-98E2-138946EF35C3",
                   "udid" : "3B12671F-4287-4208-98E2-138946EF35C3",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-Air-5th-generatio
                   n",
                   "state" : "Shutdown",
                   "name" : "iPad Air (5th generation)"
                 },
                 {
                   "dataPath" :
                   "\/Users\/sven\/Library\/Developer\/CoreSimulator\/Devices\/8
                   88EC52F-1343-435A-905A-ABF6395538AE\/data",
                   "dataPathSize" : 13316096,
                   "logPath" :
                   "\/Users\/sven\/Library\/Logs\/CoreSimulator\/888EC52F-1343-4
                   35A-905A-ABF6395538AE",
                   "udid" : "888EC52F-1343-435A-905A-ABF6395538AE",
                   "isAvailable" : true,
                   "deviceTypeIdentifier" :
                   "com.apple.CoreSimulator.SimDeviceType.iPad-mini-6th-generati
                   on",
                   "state" : "Shutdown",
                   "name" : "iPad mini (6th generation)"
                 }
               ]
             }
           }
[  +51 ms] List of devices attached
[+2282 ms] [
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,1",
                        "identifier" : "EF1A6DE4-8831-4E58-AB54-ECEE82C5E729",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-12-mini-1",
                        "modelName" : "iPhone 12 mini",
                        "name" : "iPhone 12 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad12,2",
                        "identifier" : "FA68E295-3378-412A-A88F-AD83F92BCB18",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-9-wwan-1",
                        "modelName" : "iPad (9th generation)",
                        "name" : "iPad (9th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,2",
                          "identifier" : "2E745365-E7EF-4F72-8C93-6164760860B8",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-13-pro-1",
                          "modelName" : "iPhone 13 Pro",
                          "name" : "iPhone 13 Pro"
                        },
                        "modelCode" : "Watch6,1",
                        "identifier" : "811ABF26-CAA6-46DB-8BBD-B153C7D5325E",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 40mm",
                        "name" : "Apple Watch Series 6 - 40mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "EFC2896C-B618-48CC-917B-DF84890797FA",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (at 1080p) (2nd generation)",
                        "name" : "Apple TV 4K (at 1080p) (2nd generation)"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "12.3.1 (21E258)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.macosx",
                        "modelCode" : "MacBookPro17,1",
                        "identifier" : "00008103-000949AC0E8A001E",
                        "architecture" : "arm64e",
                        "modelUTI" :
                        "com.apple.macbookpro-13-retina-touchid-late-2020",
                        "modelName" : "MacBook Pro",
                        "name" : "My Mac"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,5",
                        "identifier" : "AB8E0EAC-1A54-4B60-9824-53675B1F2929",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-13-1",
                        "modelName" : "iPhone 13",
                        "name" : "iPhone 13"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,4",
                          "identifier" : "0D50093C-029A-44D1-8574-629DE95CAB6E",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-13-mini-1",
                          "modelName" : "iPhone 13 mini",
                          "name" : "iPhone 13 mini"
                        },
                        "modelCode" : "Watch6,6",
                        "identifier" : "DCDC3F26-296E-4212-A182-E040FB8F1993",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 41mm",
                        "name" : "Apple Watch Series 7 - 41mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,4",
                          "identifier" : "16ACD889-D3A2-456A-8A9C-D1C96C47787D",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-12-pro-max-1",
                          "modelName" : "iPhone 12 Pro Max",
                          "name" : "iPhone 12 Pro Max"
                        },
                        "modelCode" : "Watch5,4",
                        "identifier" : "4FA0564A-3172-4988-85CB-B4B73F5C803F",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 44mm",
                        "name" : "Apple Watch Series 5 - 44mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,5",
                        "identifier" : "D8C25686-3142-4EDB-981D-5A054309576C",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-pro-11-3rd-1",
                        "modelName" : "iPad Pro (11-inch) (3rd generation)",
                        "name" : "iPad Pro (11-inch) (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,5",
                        "identifier" : "E35854BC-8194-4F9E-BD43-19EC37D4E306",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-8-plus-2",
                        "modelName" : "iPhone 8 Plus",
                        "name" : "iPhone 8 Plus"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,3",
                        "identifier" : "2F5B90C2-9E4C-4EAF-8997-9BC5E37492EF",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-11-pro-1",
                        "modelName" : "iPhone 11 Pro",
                        "name" : "iPhone 11 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,4",
                        "identifier" : "0D50093C-029A-44D1-8574-629DE95CAB6E",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-13-mini-1",
                        "modelName" : "iPhone 13 mini",
                        "name" : "iPhone 13 mini"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,5",
                          "identifier" : "AB8E0EAC-1A54-4B60-9824-53675B1F2929",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-13-1",
                          "modelName" : "iPhone 13",
                          "name" : "iPhone 13"
                        },
                        "modelCode" : "Watch6,9",
                        "identifier" : "390E8F15-EB7A-4015-9855-973C4FB786F5",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series7-1",
                        "modelName" : "Apple Watch Series 7 - 45mm",
                        "name" : "Apple Watch Series 7 - 45mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,1",
                        "identifier" : "D31DDCCB-531C-443A-B773-AB09078CC624",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-11-1",
                        "modelName" : "iPhone 11",
                        "name" : "iPhone 11"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,4",
                        "identifier" : "16ACD889-D3A2-456A-8A9C-D1C96C47787D",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-12-pro-max-1",
                        "modelName" : "iPhone 12 Pro Max",
                        "name" : "iPhone 12 Pro Max"
                      },
                      {
                        "simulator" : false,
                        "operatingSystemVersion" : "15.6.1 (19G82)",
                        "interface" : "usb",
                        "available" : true,
                        "platform" : "com.apple.platform.iphoneos",
                        "modelCode" : "iPhone11,6",
                        "identifier" : "00008020-000B24363C86002E",
                        "architecture" : "arm64e",
                        "modelUTI" : "com.apple.iphone-xs-max-1",
                        "modelName" : "iPhone XS Max",
                        "name" : "AlomateiPhone"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPod9,1",
                        "identifier" : "701CA2C2-32A0-4F15-94E8-B8ABE8A218C9",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipod-touch-7-2",
                        "modelName" : "iPod touch (7th generation)",
                        "name" : "iPod touch (7th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,10",
                        "identifier" : "1524E474-00F1-4BA6-BAF0-FD84F1D13199",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-pro-12point9-5th-1",
                        "modelName" : "iPad Pro (12.9-inch) (5th generation)",
                        "name" : "iPad Pro (12.9-inch) (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad13,17",
                        "identifier" : "3B12671F-4287-4208-98E2-138946EF35C3",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-air5-1",
                        "modelName" : "iPad Air (5th generation)",
                        "name" : "iPad Air (5th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad6,4",
                        "identifier" : "922D42C6-4961-4A2C-943D-53BE0C90156D",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-pro-9point7-a1674-b9b7ba",
                        "modelName" : "iPad Pro (9.7-inch)",
                        "name" : "iPad Pro (9.7-inch)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone13,3",
                          "identifier" : "8C95D63C-0CA2-4182-9E62-B214E406BF73",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-12-pro-1",
                          "modelName" : "iPhone 12 Pro",
                          "name" : "iPhone 12 Pro"
                        },
                        "modelCode" : "Watch5,3",
                        "identifier" : "5CCC6BA6-9AB5-49A3-868B-ACA7F5090685",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series5-1",
                        "modelName" : "Apple Watch Series 5 - 40mm",
                        "name" : "Apple Watch Series 5 - 40mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,2",
                        "identifier" : "728DB7C8-ECA5-4019-86E6-F4C55740388B",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-12-1",
                        "modelName" : "iPhone 12",
                        "name" : "iPhone 12"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone13,3",
                        "identifier" : "8C95D63C-0CA2-4182-9E62-B214E406BF73",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-12-pro-1",
                        "modelName" : "iPhone 12 Pro",
                        "name" : "iPhone 12 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPad14,1",
                        "identifier" : "888EC52F-1343-435A-905A-ABF6395538AE",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.ipad-mini6-1",
                        "modelName" : "iPad mini (6th generation)",
                        "name" : "iPad mini (6th generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone12,5",
                        "identifier" : "6A0E3A3C-7C23-45E8-9590-22BE14E1C0B9",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-11-pro-max-1",
                        "modelName" : "iPhone 11 Pro Max",
                        "name" : "iPhone 11 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,3",
                        "identifier" : "9307F5B5-5103-488A-8894-609A3EAEA7DB",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-13-pro-max-1",
                        "modelName" : "iPhone 13 Pro Max",
                        "name" : "iPhone 13 Pro Max"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV5,3",
                        "identifier" : "E7F51542-D3A4-4A98-AEE4-DB3D25C03B30",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.apple-tv-4",
                        "modelName" : "Apple TV",
                        "name" : "Apple TV"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.4 (19L439)",
                        "available" : true,
                        "platform" : "com.apple.platform.appletvsimulator",
                        "modelCode" : "AppleTV11,1",
                        "identifier" : "5050286E-97C5-40A6-8245-14DCF7A2C88F",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.apple-tv-4k-2nd",
                        "modelName" : "Apple TV 4K (2nd generation)",
                        "name" : "Apple TV 4K (2nd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "8.5 (19T241)",
                        "available" : true,
                        "platform" : "com.apple.platform.watchsimulator",
                        "companionDevice" : {
                          "simulator" : true,
                          "operatingSystemVersion" : "15.5 (19F70)",
                          "available" : true,
                          "platform" : "com.apple.platform.iphonesimulator",
                          "modelCode" : "iPhone14,3",
                          "identifier" : "9307F5B5-5103-488A-8894-609A3EAEA7DB",
                          "architecture" : "arm64",
                          "modelUTI" : "com.apple.iphone-13-pro-max-1",
                          "modelName" : "iPhone 13 Pro Max",
                          "name" : "iPhone 13 Pro Max"
                        },
                        "modelCode" : "Watch6,2",
                        "identifier" : "2CC135FA-DEEE-4D53-8C3C-5689D3EE985D",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.watch-series6-1",
                        "modelName" : "Apple Watch Series 6 - 44mm",
                        "name" : "Apple Watch Series 6 - 44mm"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,6",
                        "identifier" : "404ADD57-3A3F-40BF-8555-DF70E769CCA7",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-se3-1",
                        "modelName" : "iPhone SE (3rd generation)",
                        "name" : "iPhone SE (3rd generation)"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone14,2",
                        "identifier" : "2E745365-E7EF-4F72-8C93-6164760860B8",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-13-pro-1",
                        "modelName" : "iPhone 13 Pro",
                        "name" : "iPhone 13 Pro"
                      },
                      {
                        "simulator" : true,
                        "operatingSystemVersion" : "15.5 (19F70)",
                        "available" : true,
                        "platform" : "com.apple.platform.iphonesimulator",
                        "modelCode" : "iPhone10,4",
                        "identifier" : "57A7585D-BB7D-49BE-9F2F-E270CCDDA27B",
                        "architecture" : "arm64",
                        "modelUTI" : "com.apple.iphone-8-2",
                        "modelName" : "iPhone 8",
                        "name" : "iPhone 8"
                      }
                    ]

                    objc[42613]: Class AMSupportURLConnectionDelegate is
                    implemented in both /usr/lib/libamsupport.dylib
                    (0x20a776098) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x1064182c8). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class AMSupportURLSession is implemented in
                    both /usr/lib/libamsupport.dylib (0x20a7760e8) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x106418318). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class AppleTypeCRetimerRestoreInfoHelper is
                    implemented in both /usr/lib/libauthinstall.dylib
                    (0x20a775eb0) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x1064184f8). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class
                    AppleTypeCRetimerFirmwareAggregateRequestCreator is
                    implemented in both /usr/lib/libauthinstall.dylib
                    (0x20a775f00) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x106418548). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class AppleTypeCRetimerFirmwareRequestCreator
                    is implemented in both /usr/lib/libauthinstall.dylib
                    (0x20a775f50) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x106418598). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class ATCRTRestoreInfoFTABFile is implemented
                    in both /usr/lib/libauthinstall.dylib (0x20a775fa0) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x1064185e8). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class AppleTypeCRetimerFirmwareCopier is
                    implemented in both /usr/lib/libauthinstall.dylib
                    (0x20a775ff0) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x106418638). One of the
                    two will be used. Which one is undefined.
                    objc[42613]: Class ATCRTRestoreInfoFTABSubfile is
                    implemented in both /usr/lib/libauthinstall.dylib
                    (0x20a776040) and
                    /Library/Apple/System/Library/PrivateFrameworks/MobileDevice
                    .framework/Versions/A/MobileDevice (0x106418688). One of the
                    two will be used. Which one is undefined.
                    2022-09-01 13:38:52.726 xcdevice[42613:363178] Requested but
                    did not find extension point with identifier
                    Xcode.IDEKit.ExtensionSentinelHostApplications for extension
                    Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of
                    plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:52.726 xcdevice[42613:363178] Requested but
                    did not find extension point with identifier
                    Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for
                    extension
                    Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.w
                    atchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:52.791 xcdevice[42613:363178] [MT]
                    PluginLoading: Required plug-in compatibility UUID
                    EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application
                    Support/Developer/Shared/Xcode/Plug-ins/CocoaPods.xcplugin'
                    not present in DVTPlugInCompatibilityUUIDs
                    2022-09-01 13:38:52.792 xcdevice[42613:363178] [MT]
                    PluginLoading: Required plug-in compatibility UUID
                    EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application
                    Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin'
                    not present in DVTPlugInCompatibilityUUIDs
[  +15 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required,
skipping update.
[   +3 ms] Artifact Instance of 'WindowsEngineArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required,
skipping update.
[   +2 ms] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping
update.
[        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required,
skipping update.
[        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required,
skipping update.
[  +41 ms] Skipping pub get: version match.
[  +48 ms] Generating
/Users/sven/git_project/flat/test_ar/android/app/src/main/java/io/flutter/plugin
s/GeneratedPluginRegistrant.java
[  +28 ms] Initializing file store
[   +4 ms] Skipping target: gen_localizations
[   +3 ms] gen_dart_plugin_registrant: Starting due to
{InvalidatedReasonKind.inputChanged: The following inputs have updated contents:
/Users/sven/git_project/flat/test_ar/.dart_tool/package_config_subset}
[   +9 ms] gen_dart_plugin_registrant: Complete
[        ] Skipping target: _composite
[        ] complete
[   +2 ms] Launching lib/main.dart on AlomateiPhone in debug mode...
[   +2 ms] /Users/sven/flutterSdk/flutter/bin/cache/dart-sdk/bin/dart
--disable-dart-dev
/Users/sven/flutterSdk/flutter/bin/cache/dart-sdk/bin/snapshots/frontend_server.
dart.snapshot --sdk-root
/Users/sven/flutterSdk/flutter/bin/cache/artifacts/engine/common/flutter_patched
_sdk/ --incremental --target=flutter --debugger-module-names
--experimental-emit-debug-metadata -DFLUTTER_WEB_AUTO_DETECT=true --output-dill
/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_to
ol.65HEHz/app.dill --packages
/Users/sven/git_project/flat/test_ar/.dart_tool/package_config.json
-Ddart.vm.profile=false -Ddart.vm.product=false --enable-asserts
--track-widget-creation --filesystem-scheme org-dartlang-root
--initialize-from-dill
build/c075001b96339384a97db4862b8ab8db.cache.dill.track.dill
--flutter-widget-cache --enable-experiment=alternative-invalidation-strategy
[   +2 ms] executing: [/Users/sven/git_project/flat/test_ar/ios/] /usr/bin/arch
-arm64e xcrun xcodebuild -list
[   +4 ms] <- compile package:test_ar/main.dart
[ +645 ms] Command line invocation:
                        /Applications/Xcode.app/Contents/Developer/usr/bin/xcode
                        build -list

                    User defaults from command line:
                        IDEPackageSupportUseBuiltinSCM = YES

                    Information about project "Runner":
                        Targets:
                            Runner

                        Build Configurations:
                            Debug
                            Release
                            Profile

                        If no build configuration is specified and -scheme is
                        not passed then "Release" is used.

                        Schemes:
                            Runner


                    2022-09-01 13:38:55.279 xcodebuild[42622:363271] Requested
                    but did not find extension point with identifier
                    Xcode.IDEKit.ExtensionSentinelHostApplications for extension
                    Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of
                    plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:55.279 xcodebuild[42622:363271] Requested
                    but did not find extension point with identifier
                    Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for
                    extension
                    Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.w
                    atchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:55.340 xcodebuild[42622:363271] [MT]
                    PluginLoading: Required plug-in compatibility UUID
                    EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application
                    Support/Developer/Shared/Xcode/Plug-ins/CocoaPods.xcplugin'
                    not present in DVTPlugInCompatibilityUUIDs
                    2022-09-01 13:38:55.340 xcodebuild[42622:363271] [MT]
                    PluginLoading: Required plug-in compatibility UUID
                    EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application
                    Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin'
                    not present in DVTPlugInCompatibilityUUIDs
[   +5 ms] executing:
[/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj/] /usr/bin/arch
-arm64e xcrun xcodebuild -project
/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj -scheme Runner
-configuration Debug -destination generic/platform=iOS -showBuildSettings
BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios
[        ] executing:
[/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj/] /usr/bin/arch
-arm64e xcrun xcodebuild -project
/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj -scheme Runner
-configuration Debug -destination generic/platform=iOS -showBuildSettings
BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios
[+1457 ms] Command line invocation:
                        /Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild -project /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj -scheme Runner
                        -configuration Debug -destination generic/platform=iOS -showBuildSettings BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios

                    User defaults from command line:
                        IDEPackageSupportUseBuiltinSCM = YES

                    Build settings from command line:
                        BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios

                    Build settings for action build and target Runner:
                        ACTION = build
                        AD_HOC_CODE_SIGNING_ALLOWED = NO
                        ALLOW_TARGET_PLATFORM_SPECIALIZATION = NO
                        ALTERNATE_GROUP = staff
                        ALTERNATE_MODE = u+w,go-w,a+rX
                        ALTERNATE_OWNER = sven
                        ALWAYS_EMBED_SWIFT_STANDARD_LIBRARIES = NO
                        ALWAYS_SEARCH_USER_PATHS = NO
                        ALWAYS_USE_SEPARATE_HEADERMAPS = NO
                        APPLE_INTERNAL_DEVELOPER_DIR = /AppleInternal/Developer
                        APPLE_INTERNAL_DIR = /AppleInternal
                        APPLE_INTERNAL_DOCUMENTATION_DIR = /AppleInternal/Documentation
                        APPLE_INTERNAL_LIBRARY_DIR = /AppleInternal/Library
                        APPLE_INTERNAL_TOOLS = /AppleInternal/Developer/Tools
                        APPLICATION_EXTENSION_API_ONLY = NO
                        APPLY_RULES_IN_COPY_FILES = NO
                        APPLY_RULES_IN_COPY_HEADERS = NO
                        ARCHS = arm64
                        ARCHS_STANDARD = arm64 armv7
                        ARCHS_STANDARD_32_64_BIT = armv7 arm64
                        ARCHS_STANDARD_32_BIT = armv7
                        ARCHS_STANDARD_64_BIT = arm64
                        ARCHS_STANDARD_INCLUDING_64_BIT = arm64 armv7
                        ARCHS_UNIVERSAL_IPHONE_OS = armv7 arm64
                        ASSETCATALOG_COMPILER_APPICON_NAME = AppIcon
                        AVAILABLE_PLATFORMS = appletvos appletvsimulator driverkit iphoneos iphonesimulator macosx watchos watchsimulator
                        BITCODE_GENERATION_MODE = marker
                        BUILD_ACTIVE_RESOURCES_ONLY = NO
                        BUILD_COMPONENTS = headers build
                        BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios
                        BUILD_LIBRARY_FOR_DISTRIBUTION = NO
                        BUILD_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Products
                        BUILD_STYLE = 
                        BUILD_VARIANTS = normal
                        BUILT_PRODUCTS_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        BUNDLE_CONTENTS_FOLDER_PATH_deep = Contents/
                        BUNDLE_EXECUTABLE_FOLDER_NAME_deep = MacOS
                        BUNDLE_FORMAT = shallow
                        BUNDLE_FRAMEWORKS_FOLDER_PATH = Frameworks
                        BUNDLE_PLUGINS_FOLDER_PATH = PlugIns
                        BUNDLE_PRIVATE_HEADERS_FOLDER_PATH = PrivateHeaders
                        BUNDLE_PUBLIC_HEADERS_FOLDER_PATH = Headers
                        CACHE_ROOT = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        CCHROOT = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        CHMOD = /bin/chmod
                        CHOWN = /usr/sbin/chown
                        CLANG_ANALYZER_NONNULL = YES
                        CLANG_CXX_LANGUAGE_STANDARD = gnu++0x
                        CLANG_CXX_LIBRARY = libc++
                        CLANG_ENABLE_MODULES = YES
                        CLANG_ENABLE_OBJC_ARC = YES
                        CLANG_WARN_BLOCK_CAPTURE_AUTORELEASING = YES
                        CLANG_WARN_BOOL_CONVERSION = YES
                        CLANG_WARN_COMMA = YES
                        CLANG_WARN_CONSTANT_CONVERSION = YES
                        CLANG_WARN_DEPRECATED_OBJC_IMPLEMENTATIONS = YES
                        CLANG_WARN_DIRECT_OBJC_ISA_USAGE = YES_ERROR
                        CLANG_WARN_EMPTY_BODY = YES
                        CLANG_WARN_ENUM_CONVERSION = YES
                        CLANG_WARN_INFINITE_RECURSION = YES
                        CLANG_WARN_INT_CONVERSION = YES
                        CLANG_WARN_NON_LITERAL_NULL_CONVERSION = YES
                        CLANG_WARN_OBJC_IMPLICIT_RETAIN_SELF = YES
                        CLANG_WARN_OBJC_LITERAL_CONVERSION = YES
                        CLANG_WARN_OBJC_ROOT_CLASS = YES_ERROR
                        CLANG_WARN_RANGE_LOOP_ANALYSIS = YES
                        CLANG_WARN_STRICT_PROTOTYPES = YES
                        CLANG_WARN_SUSPICIOUS_MOVE = YES
                        CLANG_WARN_UNREACHABLE_CODE = YES
                        CLANG_WARN__DUPLICATE_METHOD_MATCH = YES
                        CLASS_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ja
                        vaClasses
                        CLEAN_PRECOMPS = YES
                        CLONE_HEADERS = NO
                        COCOAPODS_PARALLEL_CODE_SIGN = true
                        CODESIGNING_FOLDER_PATH = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        CODE_SIGNING_ALLOWED = YES
                        CODE_SIGNING_REQUIRED = YES
                        CODE_SIGN_CONTEXT_CLASS = XCiPhoneOSCodeSignContext
                        CODE_SIGN_IDENTITY = iPhone Developer
                        CODE_SIGN_INJECT_BASE_ENTITLEMENTS = YES
                        COLOR_DIAGNOSTICS = NO
                        COMBINE_HIDPI_IMAGES = NO
                        COMPILER_INDEX_STORE_ENABLE = Default
                        COMPOSITE_SDK_DIRS = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/CompositeSDKs
                        COMPRESS_PNG_FILES = YES
                        CONFIGURATION = Debug
                        CONFIGURATION_BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        CONFIGURATION_TEMP_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos
                        CONTENTS_FOLDER_PATH = Runner.app
                        CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Contents
                        CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        COPYING_PRESERVES_HFS_DATA = NO
                        COPY_HEADERS_RUN_UNIFDEF = NO
                        COPY_PHASE_STRIP = NO
                        COPY_RESOURCES_FROM_STATIC_FRAMEWORKS = YES
                        CORRESPONDING_SIMULATOR_PLATFORM_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform
                        CORRESPONDING_SIMULATOR_PLATFORM_NAME = iphonesimulator
                        CORRESPONDING_SIMULATOR_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator15.5.sdk
                        CORRESPONDING_SIMULATOR_SDK_NAME = iphonesimulator15.5
                        CP = /bin/cp
                        CREATE_INFOPLIST_SECTION_IN_BINARY = NO
                        CURRENT_ARCH = arm64
                        CURRENT_PROJECT_VERSION = 1
                        CURRENT_VARIANT = normal
                        DART_DEFINES = RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ==
                        DART_OBFUSCATION = false
                        DEAD_CODE_STRIPPING = YES
                        DEBUGGING_SYMBOLS = YES
                        DEBUG_INFORMATION_FORMAT = dwarf
                        DEFAULT_COMPILER = com.apple.compilers.llvm.clang.1_0
                        DEFAULT_DEXT_INSTALL_PATH = /System/Library/DriverExtensions
                        DEFAULT_KEXT_INSTALL_PATH = /System/Library/Extensions
                        DEFINES_MODULE = NO
                        DEPLOYMENT_LOCATION = NO
                        DEPLOYMENT_POSTPROCESSING = NO
                        DEPLOYMENT_TARGET_CLANG_ENV_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_CLANG_FLAG_NAME = miphoneos-version-min
                        DEPLOYMENT_TARGET_LD_ENV_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_LD_FLAG_NAME = ios_version_min
                        DEPLOYMENT_TARGET_SETTING_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_SUGGESTED_VALUES = 9.0 9.1 9.2 9.3 10.0 10.1 10.2 10.3 11.0 11.1 11.2 11.3 11.4 12.0 12.1 12.2 12.3 12.4 13.0 13.1 13.2 13.3 13.4 13.5
                        13.6 14.0 14.1 14.2 14.3 14.4 14.5 14.6 14.7 15.0 15.1 15.2 15.3 15.4 15.5
                        DERIVED_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/De
                        rivedSources
                        DERIVED_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/De
                        rivedSources
                        DERIVED_SOURCES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/De
                        rivedSources
                        DEVELOPER_APPLICATIONS_DIR = /Applications/Xcode.app/Contents/Developer/Applications
                        DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/usr/bin
                        DEVELOPER_DIR = /Applications/Xcode.app/Contents/Developer
                        DEVELOPER_FRAMEWORKS_DIR = /Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        DEVELOPER_FRAMEWORKS_DIR_QUOTED = /Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        DEVELOPER_LIBRARY_DIR = /Applications/Xcode.app/Contents/Developer/Library
                        DEVELOPER_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs
                        DEVELOPER_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Tools
                        DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/usr
                        DEVELOPMENT_LANGUAGE = en
                        DEVELOPMENT_TEAM = G7N8SR355W
                        DOCUMENTATION_FOLDER_PATH = Runner.app/en.lproj/Documentation
                        DONT_GENERATE_INFOPLIST_FILE = NO
                        DO_HEADER_SCANNING_IN_JAM = NO
                        DSTROOT = /tmp/Runner.dst
                        DT_TOOLCHAIN_DIR = /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        DWARF_DSYM_FILE_NAME = Runner.app.dSYM
                        DWARF_DSYM_FILE_SHOULD_ACCOMPANY_PRODUCT = NO
                        DWARF_DSYM_FOLDER_PATH = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        EFFECTIVE_PLATFORM_NAME = -iphoneos
                        EMBEDDED_CONTENT_CONTAINS_SWIFT = NO
                        EMBEDDED_PROFILE_NAME = embedded.mobileprovision
                        EMBED_ASSET_PACKS_IN_PRODUCT_BUNDLE = NO
                        ENABLE_APP_SANDBOX = NO
                        ENABLE_BITCODE = NO
                        ENABLE_DEFAULT_HEADER_SEARCH_PATHS = YES
                        ENABLE_DEFAULT_SEARCH_PATHS = YES
                        ENABLE_HARDENED_RUNTIME = NO
                        ENABLE_HEADER_DEPENDENCIES = YES
                        ENABLE_ON_DEMAND_RESOURCES = YES
                        ENABLE_STRICT_OBJC_MSGSEND = YES
                        ENABLE_TESTABILITY = YES
                        ENABLE_TESTING_SEARCH_PATHS = NO
                        ENTITLEMENTS_ALLOWED = YES
                        ENTITLEMENTS_DESTINATION = Signature
                        ENTITLEMENTS_REQUIRED = NO
                        EXCLUDED_INSTALLSRC_SUBDIRECTORY_PATTERNS = .DS_Store .svn .git .hg CVS
                        EXCLUDED_RECURSIVE_SEARCH_PATH_SUBDIRECTORIES = *.nib *.lproj *.framework *.gch *.xcode* *.xcassets (*) .DS_Store CVS .svn .git .hg *.pbproj *.pbxproj
                        EXECUTABLES_FOLDER_PATH = Runner.app/Executables
                        EXECUTABLE_FOLDER_PATH = Runner.app
                        EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/MacOS
                        EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        EXECUTABLE_NAME = Runner
                        EXECUTABLE_PATH = Runner.app/Runner
                        EXPANDED_CODE_SIGN_IDENTITY = 
                        EXPANDED_CODE_SIGN_IDENTITY_NAME = 
                        EXPANDED_PROVISIONING_PROFILE = 
                        FILE_LIST =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects/LinkFileList
                        FIXED_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Fi
                        xedFiles
                        FLUTTER_APPLICATION_PATH = /Users/sven/git_project/flat/test_ar
                        FLUTTER_BUILD_DIR = build
                        FLUTTER_BUILD_NAME = 1.0.0
                        FLUTTER_BUILD_NUMBER = 1
                        FLUTTER_ROOT = /Users/sven/flutterSdk/flutter
                        FLUTTER_TARGET = /Users/sven/git_project/flat/test_ar/lib/main.dart
                        FRAMEWORKS_FOLDER_PATH = Runner.app/Frameworks
                        FRAMEWORK_FLAG_PREFIX = -framework
                        FRAMEWORK_VERSION = A
                        FULL_PRODUCT_NAME = Runner.app
                        GCC3_VERSION = 3.3
                        GCC_C_LANGUAGE_STANDARD = gnu99
                        GCC_DYNAMIC_NO_PIC = NO
                        GCC_INLINES_ARE_PRIVATE_EXTERN = YES
                        GCC_NO_COMMON_BLOCKS = YES
                        GCC_OPTIMIZATION_LEVEL = 0
                        GCC_PFE_FILE_C_DIALECTS = c objective-c c++ objective-c++
                        GCC_PREPROCESSOR_DEFINITIONS = DEBUG=1 
                        GCC_SYMBOLS_PRIVATE_EXTERN = NO
                        GCC_THUMB_SUPPORT = YES
                        GCC_TREAT_WARNINGS_AS_ERRORS = NO
                        GCC_VERSION = com.apple.compilers.llvm.clang.1_0
                        GCC_VERSION_IDENTIFIER = com_apple_compilers_llvm_clang_1_0
                        GCC_WARN_64_TO_32_BIT_CONVERSION = YES
                        GCC_WARN_ABOUT_RETURN_TYPE = YES_ERROR
                        GCC_WARN_UNDECLARED_SELECTOR = YES
                        GCC_WARN_UNINITIALIZED_AUTOS = YES_AGGRESSIVE
                        GCC_WARN_UNUSED_FUNCTION = YES
                        GCC_WARN_UNUSED_VARIABLE = YES
                        GENERATED_MODULEMAP_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/GeneratedModuleMaps-iphoneos
                        GENERATE_INFOPLIST_FILE = NO
                        GENERATE_MASTER_OBJECT_FILE = NO
                        GENERATE_PKGINFO_FILE = YES
                        GENERATE_PROFILING_CODE = NO
                        GENERATE_TEXT_BASED_STUBS = NO
                        GID = 20
                        GROUP = staff
                        HEADERMAP_INCLUDES_FLAT_ENTRIES_FOR_TARGET_BEING_BUILT = YES
                        HEADERMAP_INCLUDES_FRAMEWORK_ENTRIES_FOR_ALL_PRODUCT_TYPES = YES
                        HEADERMAP_INCLUDES_NONPUBLIC_NONPRIVATE_HEADERS = YES
                        HEADERMAP_INCLUDES_PROJECT_HEADERS = YES
                        HEADERMAP_USES_FRAMEWORK_PREFIX_ENTRIES = YES
                        HEADERMAP_USES_VFS = NO
                        HIDE_BITCODE_SYMBOLS = YES
                        HOME = /Users/sven
                        ICONV = /usr/bin/iconv
                        INFOPLIST_EXPAND_BUILD_SETTINGS = YES
                        INFOPLIST_FILE = Runner/Info.plist
                        INFOPLIST_OUTPUT_FORMAT = binary
                        INFOPLIST_PATH = Runner.app/Info.plist
                        INFOPLIST_PREPROCESS = NO
                        INFOSTRINGS_PATH = Runner.app/en.lproj/InfoPlist.strings
                        INLINE_PRIVATE_FRAMEWORKS = NO
                        INSTALLHDRS_COPY_PHASE = NO
                        INSTALLHDRS_SCRIPT_PHASE = NO
                        INSTALL_DIR = /tmp/Runner.dst/Applications
                        INSTALL_GROUP = staff
                        INSTALL_MODE_FLAG = u+w,go-w,a+rX
                        INSTALL_OWNER = sven
                        INSTALL_PATH = /Applications
                        INSTALL_ROOT = /tmp/Runner.dst
                        IPHONEOS_DEPLOYMENT_TARGET = 9.0
                        JAVAC_DEFAULT_FLAGS = -J-Xms64m -J-XX:NewSize=4M -J-Dfile.encoding=UTF8
                        JAVA_APP_STUB = /System/Library/Frameworks/JavaVM.framework/Resources/MacOS/JavaApplicationStub
                        JAVA_ARCHIVE_CLASSES = YES
                        JAVA_ARCHIVE_TYPE = JAR
                        JAVA_COMPILER = /usr/bin/javac
                        JAVA_FOLDER_PATH = Runner.app/Java
                        JAVA_FRAMEWORK_RESOURCES_DIRS = Resources
                        JAVA_JAR_FLAGS = cv
                        JAVA_SOURCE_SUBDIR = .
                        JAVA_USE_DEPENDENCIES = YES
                        JAVA_ZIP_FLAGS = -urg
                        JIKES_DEFAULT_FLAGS = +E +OLDCSO
                        KASAN_DEFAULT_CFLAGS = -DKASAN=1 -fsanitize=address -mllvm -asan-globals-live-support -mllvm -asan-force-dynamic-shadow
                        KEEP_PRIVATE_EXTERNS = NO
                        LD_DEPENDENCY_INFO_FILE =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects-normal/arm64/Runner_dependency_info.dat
                        LD_GENERATE_MAP_FILE = NO
                        LD_MAP_FILE_PATH =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ru
                        nner-LinkMap-normal-arm64.txt
                        LD_NO_PIE = NO
                        LD_QUOTE_LINKER_ARGUMENTS_FOR_COMPILER_DRIVER = YES
                        LD_RUNPATH_SEARCH_PATHS =  @executable_path/Frameworks
                        LEGACY_DEVELOPER_DIR = /Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer
                        LEX = lex
                        LIBRARY_DEXT_INSTALL_PATH = /Library/DriverExtensions
                        LIBRARY_FLAG_NOSPACE = YES
                        LIBRARY_FLAG_PREFIX = -l
                        LIBRARY_KEXT_INSTALL_PATH = /Library/Extensions
                        LINKER_DISPLAYS_MANGLED_NAMES = NO
                        LINK_FILE_LIST_normal_arm64 = 
                        LINK_WITH_STANDARD_LIBRARIES = YES
                        LLVM_TARGET_TRIPLE_OS_VERSION = ios9.0
                        LLVM_TARGET_TRIPLE_VENDOR = apple
                        LOCALIZABLE_CONTENT_DIR = 
                        LOCALIZATION_EXPORT_SUPPORTED = YES
                        LOCALIZED_RESOURCES_FOLDER_PATH = Runner.app/en.lproj
                        LOCALIZED_STRING_MACRO_NAMES = NSLocalizedString CFCopyLocalizedString
                        LOCALIZED_STRING_SWIFTUI_SUPPORT = YES
                        LOCAL_ADMIN_APPS_DIR = /Applications/Utilities
                        LOCAL_APPS_DIR = /Applications
                        LOCAL_DEVELOPER_DIR = /Library/Developer
                        LOCAL_LIBRARY_DIR = /Library
                        LOCROOT = 
                        LOCSYMROOT = 
                        MACH_O_TYPE = mh_execute
                        MAC_OS_X_PRODUCT_BUILD_VERSION = 21E258
                        MAC_OS_X_VERSION_ACTUAL = 120301
                        MAC_OS_X_VERSION_MAJOR = 120000
                        MAC_OS_X_VERSION_MINOR = 120300
                        METAL_LIBRARY_FILE_BASE = default
                        METAL_LIBRARY_OUTPUT_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        MODULES_FOLDER_PATH = Runner.app/Modules
                        MODULE_CACHE_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex
                        MTL_ENABLE_DEBUG_INFO = YES
                        NATIVE_ARCH = arm64e
                        NATIVE_ARCH_32_BIT = i386
                        NATIVE_ARCH_64_BIT = arm64e
                        NATIVE_ARCH_ACTUAL = arm64e
                        NO_COMMON = YES
                        OBJECT_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects
                        OBJECT_FILE_DIR_normal =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects-normal
                        OBJROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        ONLY_ACTIVE_ARCH = YES
                        OS = MACOS
                        OSAC = /usr/bin/osacompile
                        PACKAGE_CONFIG = /Users/sven/git_project/flat/test_ar/.dart_tool/package_config.json
                        PACKAGE_TYPE = com.apple.package-type.wrapper.application
                        PASCAL_STRINGS = YES
                        PATH =
                        /Applications/Xcode.app/Contents/Developer/usr/bin:/usr/local/opt/ruby@2.7/bin:/opt/local/bin:/opt/local/sbin:/Library/Java/JavaVirtualMachines/jdk1.8.0_11
                        1.jdk/Contents/Home/bin:/usr/local/opt/openssl@1.1/bin:/Users/sven/androidsdk/tools:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/opt/X11/bin:/Library/Appl
                        e/usr/bin:/Users/sven/androidsdk/platform-tools:/Users/sven/androidsdk/tools:/Users/sven/flutterSdk/flutter/bin:/Users/sven/flutterSdk/flutter/bin/cache/da
                        rt-sdk/bin:/Users/sven/mygo/bin:/Users/sven/flutterSdk/flutter/.pub-cache/bin::/Users/sven/.pub-cache/bin:/Users/sven/androidsdk/ndk-bundle:/opt/homebrew/b
                        in:/Users/sven/.rvm/bin
                        PATH_PREFIXES_EXCLUDED_FROM_HEADER_DEPENDENCIES = /usr/include /usr/local/include /System/Library/Frameworks /System/Library/PrivateFrameworks
                        /Applications/Xcode.app/Contents/Developer/Headers /Applications/Xcode.app/Contents/Developer/SDKs /Applications/Xcode.app/Contents/Developer/Platforms
                        PBDEVELOPMENTPLIST_PATH = Runner.app/pbdevelopment.plist
                        PFE_FILE_C_DIALECTS = objective-c
                        PKGINFO_FILE_PATH =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Pk
                        gInfo
                        PKGINFO_PATH = Runner.app/PkgInfo
                        PLATFORM_DEVELOPER_APPLICATIONS_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Applications
                        PLATFORM_DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin
                        PLATFORM_DEVELOPER_LIBRARY_DIR = /Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer/Library
                        PLATFORM_DEVELOPER_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs
                        PLATFORM_DEVELOPER_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Tools
                        PLATFORM_DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr
                        PLATFORM_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform
                        PLATFORM_DISPLAY_NAME = iOS
                        PLATFORM_NAME = iphoneos
                        PLATFORM_PREFERRED_ARCH = arm64
                        PLATFORM_PRODUCT_BUILD_VERSION = 19F64
                        PLIST_FILE_OUTPUT_FORMAT = binary
                        PLUGINS_FOLDER_PATH = Runner.app/PlugIns
                        PRECOMPS_INCLUDE_HEADERS_FROM_BUILT_PRODUCTS_DIR = YES
                        PRECOMP_DESTINATION_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Pr
                        efixHeaders
                        PRESERVE_DEAD_CODE_INITS_AND_TERMS = NO
                        PRIVATE_HEADERS_FOLDER_PATH = Runner.app/PrivateHeaders
                        PRODUCT_BUNDLE_IDENTIFIER = com.example.testar.testAr
                        PRODUCT_BUNDLE_PACKAGE_TYPE = APPL
                        PRODUCT_MODULE_NAME = Runner
                        PRODUCT_NAME = Runner
                        PRODUCT_SETTINGS_PATH = /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
                        PRODUCT_TYPE = com.apple.product-type.application
                        PROFILING_CODE = NO
                        PROJECT = Runner
                        PROJECT_DERIVED_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/DerivedSources
                        PROJECT_DIR = /Users/sven/git_project/flat/test_ar/ios
                        PROJECT_FILE_PATH = /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
                        PROJECT_NAME = Runner
                        PROJECT_TEMP_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build
                        PROJECT_TEMP_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        PROVISIONING_PROFILE_REQUIRED = YES
                        PUBLIC_HEADERS_FOLDER_PATH = Runner.app/Headers
                        RECURSIVE_SEARCH_PATHS_FOLLOW_SYMLINKS = YES
                        REMOVE_CVS_FROM_RESOURCES = YES
                        REMOVE_GIT_FROM_RESOURCES = YES
                        REMOVE_HEADERS_FROM_EMBEDDED_BUNDLES = YES
                        REMOVE_HG_FROM_RESOURCES = YES
                        REMOVE_SVN_FROM_RESOURCES = YES
                        RESOURCE_RULES_REQUIRED = YES
                        REZ_COLLECTOR_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Re
                        sourceManagerResources
                        REZ_OBJECTS_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Re
                        sourceManagerResources/Objects
                        SCAN_ALL_SOURCE_FILES_FOR_INCLUDES = NO
                        SCRIPTS_FOLDER_PATH = Runner.app/Scripts
                        SDKROOT = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_DIR_iphoneos15_5 = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_NAME = iphoneos15.5
                        SDK_NAMES = iphoneos15.5
                        SDK_PRODUCT_BUILD_VERSION = 19F64
                        SDK_VERSION = 15.5
                        SDK_VERSION_ACTUAL = 150500
                        SDK_VERSION_MAJOR = 150000
                        SDK_VERSION_MINOR = 150500
                        SED = /usr/bin/sed
                        SEPARATE_STRIP = NO
                        SEPARATE_SYMBOL_EDIT = NO
                        SET_DIR_MODE_OWNER_GROUP = YES
                        SET_FILE_MODE_OWNER_GROUP = NO
                        SHALLOW_BUNDLE = YES
                        SHALLOW_BUNDLE_TRIPLE = ios
                        SHALLOW_BUNDLE_ios_macabi = NO
                        SHALLOW_BUNDLE_macos = NO
                        SHARED_DERIVED_FILE_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/DerivedSources
                        SHARED_FRAMEWORKS_FOLDER_PATH = Runner.app/SharedFrameworks
                        SHARED_PRECOMPS_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/PrecompiledHeaders
                        SHARED_SUPPORT_FOLDER_PATH = Runner.app/SharedSupport
                        SKIP_INSTALL = NO
                        SOURCE_ROOT = /Users/sven/git_project/flat/test_ar/ios
                        SRCROOT = /Users/sven/git_project/flat/test_ar/ios
                        STRINGSDATA_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects-normal/arm64
                        STRINGSDATA_ROOT =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        STRINGS_FILE_INFOPLIST_RENAME = YES
                        STRINGS_FILE_OUTPUT_ENCODING = binary
                        STRIP_BITCODE_FROM_COPIED_FILES = YES
                        STRIP_INSTALLED_PRODUCT = YES
                        STRIP_STYLE = all
                        STRIP_SWIFT_SYMBOLS = YES
                        SUPPORTED_DEVICE_FAMILIES = 1,2
                        SUPPORTED_PLATFORMS = iphonesimulator iphoneos
                        SUPPORTS_MACCATALYST = NO
                        SUPPORTS_TEXT_BASED_API = NO
                        SWIFT_EMIT_LOC_STRINGS = NO
                        SWIFT_OBJC_BRIDGING_HEADER = Runner/Runner-Bridging-Header.h
                        SWIFT_OPTIMIZATION_LEVEL = -Onone
                        SWIFT_PLATFORM_TARGET_PREFIX = ios
                        SWIFT_VERSION = 5.0
                        SYMROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Products
                        SYSTEM_ADMIN_APPS_DIR = /Applications/Utilities
                        SYSTEM_APPS_DIR = /Applications
                        SYSTEM_CORE_SERVICES_DIR = /System/Library/CoreServices
                        SYSTEM_DEMOS_DIR = /Applications/Extras
                        SYSTEM_DEVELOPER_APPS_DIR = /Applications/Xcode.app/Contents/Developer/Applications
                        SYSTEM_DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/usr/bin
                        SYSTEM_DEVELOPER_DEMOS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Utilities/Built Examples
                        SYSTEM_DEVELOPER_DIR = /Applications/Xcode.app/Contents/Developer
                        SYSTEM_DEVELOPER_DOC_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library
                        SYSTEM_DEVELOPER_GRAPHICS_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Graphics Tools
                        SYSTEM_DEVELOPER_JAVA_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Java Tools
                        SYSTEM_DEVELOPER_PERFORMANCE_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Performance Tools
                        SYSTEM_DEVELOPER_RELEASENOTES_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/releasenotes
                        SYSTEM_DEVELOPER_TOOLS = /Applications/Xcode.app/Contents/Developer/Tools
                        SYSTEM_DEVELOPER_TOOLS_DOC_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/documentation/DeveloperTools
                        SYSTEM_DEVELOPER_TOOLS_RELEASENOTES_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/releasenotes/DeveloperTools
                        SYSTEM_DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/usr
                        SYSTEM_DEVELOPER_UTILITIES_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Utilities
                        SYSTEM_DEXT_INSTALL_PATH = /System/Library/DriverExtensions
                        SYSTEM_DOCUMENTATION_DIR = /Library/Documentation
                        SYSTEM_EXTENSIONS_FOLDER_PATH = Runner.app/SystemExtensions
                        SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Library/SystemExtensions
                        SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app/SystemExtensions
                        SYSTEM_KEXT_INSTALL_PATH = /System/Library/Extensions
                        SYSTEM_LIBRARY_DIR = /System/Library
                        TAPI_ENABLE_PROJECT_HEADERS = NO
                        TAPI_VERIFY_MODE = ErrorsOnly
                        TARGETED_DEVICE_FAMILY = 1,2
                        TARGETNAME = Runner
                        TARGET_BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        TARGET_NAME = Runner
                        TARGET_TEMP_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        TEST_FRAMEWORK_SEARCH_PATHS =  /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Frameworks
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk/Developer/Library/Frameworks
                        TEST_LIBRARY_SEARCH_PATHS =  /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/lib
                        TOOLCHAIN_DIR = /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        TRACK_WIDGET_CREATION = true
                        TREAT_MISSING_BASELINES_AS_TEST_FAILURES = NO
                        TREE_SHAKE_ICONS = false
                        UID = 502
                        UNLOCALIZED_RESOURCES_FOLDER_PATH = Runner.app
                        UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Resources
                        UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        UNSTRIPPED_PRODUCT = NO
                        USER = sven
                        USER_APPS_DIR = /Users/sven/Applications
                        USER_LIBRARY_DIR = /Users/sven/Library
                        USE_DYNAMIC_NO_PIC = YES
                        USE_HEADERMAP = YES
                        USE_HEADER_SYMLINKS = NO
                        USE_LLVM_TARGET_TRIPLES = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_CLANG = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_LD = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_TAPI = YES
                        VALIDATE_PRODUCT = NO
                        VALIDATE_WORKSPACE = NO
                        VALID_ARCHS = arm64 arm64e armv7 armv7s
                        VERBOSE_PBXCP = NO
                        VERSIONING_SYSTEM = apple-generic
                        VERSIONPLIST_PATH = Runner.app/version.plist
                        VERSION_INFO_BUILDER = sven
                        VERSION_INFO_FILE = Runner_vers.c
                        VERSION_INFO_STRING = "@(#)PROGRAM:Runner  PROJECT:Runner-1"
                        WRAPPER_EXTENSION = app
                        WRAPPER_NAME = Runner.app
                        WRAPPER_SUFFIX = .app
                        WRAP_ASSET_PACKS_IN_SEPARATE_DIRECTORIES = NO
                        XCODE_APP_SUPPORT_DIR = /Applications/Xcode.app/Contents/Developer/Library/Xcode
                        XCODE_PRODUCT_BUILD_VERSION = 13F17a
                        XCODE_VERSION_ACTUAL = 1340
                        XCODE_VERSION_MAJOR = 1300
                        XCODE_VERSION_MINOR = 1340
                        XPCSERVICES_FOLDER_PATH = Runner.app/XPCServices
                        YACC = yacc
                        _WRAPPER_CONTENTS_DIR_SHALLOW_BUNDLE_NO = /Contents
                        _WRAPPER_PARENT_PATH_SHALLOW_BUNDLE_NO = /..
                        _WRAPPER_RESOURCES_DIR_SHALLOW_BUNDLE_NO = /Resources
                        __CODE_SIGNING_ALLOWED_appletvos = NO
                        __CODE_SIGNING_ALLOWED_iphoneos = NO
                        __CODE_SIGNING_ALLOWED_watchos = NO
                        arch = arm64
                        variant = normal


                    2022-09-01 13:38:55.909 xcodebuild[42627:363340] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionSentinelHostApplications for
                    extension Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:55.909 xcodebuild[42627:363340] Requested but did not find extension point with identifier
                    Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for extension Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in
                    com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:55.962 xcodebuild[42627:363340] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at
                    path '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/CocoaPods.xcplugin' not present in DVTPlugInCompatibilityUUIDs
                    2022-09-01 13:38:55.962 xcodebuild[42627:363340] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at
                    path '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin' not present in DVTPlugInCompatibilityUUIDs
[   +8 ms] executing: /usr/bin/plutil -convert xml1 -o - /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
[  +20 ms] Exit code 0 from: /usr/bin/plutil -convert xml1 -o - /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
[        ] <?xml version="1.0" encoding="UTF-8"?>
           <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
           <plist version="1.0">
           <dict>
           	<key>CADisableMinimumFrameDurationOnPhone</key>
           	<true/>
           	<key>CFBundleDevelopmentRegion</key>
           	<string>$(DEVELOPMENT_LANGUAGE)</string>
           	<key>CFBundleDisplayName</key>
           	<string>Test Ar</string>
           	<key>CFBundleExecutable</key>
           	<string>$(EXECUTABLE_NAME)</string>
           	<key>CFBundleIdentifier</key>
           	<string>$(PRODUCT_BUNDLE_IDENTIFIER)</string>
           	<key>CFBundleInfoDictionaryVersion</key>
           	<string>6.0</string>
           	<key>CFBundleName</key>
           	<string>test_ar</string>
           	<key>CFBundlePackageType</key>
           	<string>APPL</string>
           	<key>CFBundleShortVersionString</key>
           	<string>$(FLUTTER_BUILD_NAME)</string>
           	<key>CFBundleSignature</key>
           	<string>????</string>
           	<key>CFBundleVersion</key>
           	<string>$(FLUTTER_BUILD_NUMBER)</string>
           	<key>LSRequiresIPhoneOS</key>
           	<true/>
           	<key>UILaunchStoryboardName</key>
           	<string>LaunchScreen</string>
           	<key>UIMainStoryboardFile</key>
           	<string>Main</string>
           	<key>UISupportedInterfaceOrientations</key>
           	<array>
           		<string>UIInterfaceOrientationPortrait</string>
           		<string>UIInterfaceOrientationLandscapeLeft</string>
           		<string>UIInterfaceOrientationLandscapeRight</string>
           	</array>
           	<key>UISupportedInterfaceOrientations~ipad</key>
           	<array>
           		<string>UIInterfaceOrientationPortrait</string>
           		<string>UIInterfaceOrientationPortraitUpsideDown</string>
           		<string>UIInterfaceOrientationLandscapeLeft</string>
           		<string>UIInterfaceOrientationLandscapeRight</string>
           	</array>
           	<key>UIViewControllerBasedStatusBarAppearance</key>
           	<false/>
           </dict>
           </plist>
[   +6 ms] Building Runner.app for 00008020-000B24363C86002E
[  +13 ms] executing: xattr -r -d com.apple.FinderInfo /Users/sven/git_project/flat/test_ar
[  +46 ms] executing: [/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj/] /usr/bin/arch -arm64e xcrun xcodebuild -project /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
-scheme Runner -configuration Debug -destination id=00008020-000B24363C86002E -showBuildSettings BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios
[        ] executing: [/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj/] /usr/bin/arch -arm64e xcrun xcodebuild -project /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
-scheme Runner -configuration Debug -destination id=00008020-000B24363C86002E -showBuildSettings BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios
[+3004 ms] Command line invocation:
                        /Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild -project /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj -scheme Runner -configuration Debug
                        -destination id=00008020-000B24363C86002E -showBuildSettings BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios

                    User defaults from command line:
                        IDEPackageSupportUseBuiltinSCM = YES

                    Build settings from command line:
                        BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios

                    Build settings for action build and target Runner:
                        ACTION = build
                        AD_HOC_CODE_SIGNING_ALLOWED = NO
                        ALLOW_TARGET_PLATFORM_SPECIALIZATION = NO
                        ALTERNATE_GROUP = staff
                        ALTERNATE_MODE = u+w,go-w,a+rX
                        ALTERNATE_OWNER = sven
                        ALWAYS_EMBED_SWIFT_STANDARD_LIBRARIES = NO
                        ALWAYS_SEARCH_USER_PATHS = NO
                        ALWAYS_USE_SEPARATE_HEADERMAPS = NO
                        APPLE_INTERNAL_DEVELOPER_DIR = /AppleInternal/Developer
                        APPLE_INTERNAL_DIR = /AppleInternal
                        APPLE_INTERNAL_DOCUMENTATION_DIR = /AppleInternal/Documentation
                        APPLE_INTERNAL_LIBRARY_DIR = /AppleInternal/Library
                        APPLE_INTERNAL_TOOLS = /AppleInternal/Developer/Tools
                        APPLICATION_EXTENSION_API_ONLY = NO
                        APPLY_RULES_IN_COPY_FILES = NO
                        APPLY_RULES_IN_COPY_HEADERS = NO
                        ARCHS = arm64
                        ARCHS_STANDARD = arm64 armv7
                        ARCHS_STANDARD_32_64_BIT = armv7 arm64
                        ARCHS_STANDARD_32_BIT = armv7
                        ARCHS_STANDARD_64_BIT = arm64
                        ARCHS_STANDARD_INCLUDING_64_BIT = arm64 armv7
                        ARCHS_UNIVERSAL_IPHONE_OS = armv7 arm64
                        ASSETCATALOG_COMPILER_APPICON_NAME = AppIcon
                        AVAILABLE_PLATFORMS = appletvos appletvsimulator driverkit iphoneos iphonesimulator macosx watchos watchsimulator
                        BITCODE_GENERATION_MODE = marker
                        BUILD_ACTIVE_RESOURCES_ONLY = NO
                        BUILD_COMPONENTS = headers build
                        BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios
                        BUILD_LIBRARY_FOR_DISTRIBUTION = NO
                        BUILD_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Products
                        BUILD_STYLE = 
                        BUILD_VARIANTS = normal
                        BUILT_PRODUCTS_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        BUNDLE_CONTENTS_FOLDER_PATH_deep = Contents/
                        BUNDLE_EXECUTABLE_FOLDER_NAME_deep = MacOS
                        BUNDLE_FORMAT = shallow
                        BUNDLE_FRAMEWORKS_FOLDER_PATH = Frameworks
                        BUNDLE_PLUGINS_FOLDER_PATH = PlugIns
                        BUNDLE_PRIVATE_HEADERS_FOLDER_PATH = PrivateHeaders
                        BUNDLE_PUBLIC_HEADERS_FOLDER_PATH = Headers
                        CACHE_ROOT = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        CCHROOT = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        CHMOD = /bin/chmod
                        CHOWN = /usr/sbin/chown
                        CLANG_ANALYZER_NONNULL = YES
                        CLANG_CXX_LANGUAGE_STANDARD = gnu++0x
                        CLANG_CXX_LIBRARY = libc++
                        CLANG_ENABLE_MODULES = YES
                        CLANG_ENABLE_OBJC_ARC = YES
                        CLANG_WARN_BLOCK_CAPTURE_AUTORELEASING = YES
                        CLANG_WARN_BOOL_CONVERSION = YES
                        CLANG_WARN_COMMA = YES
                        CLANG_WARN_CONSTANT_CONVERSION = YES
                        CLANG_WARN_DEPRECATED_OBJC_IMPLEMENTATIONS = YES
                        CLANG_WARN_DIRECT_OBJC_ISA_USAGE = YES_ERROR
                        CLANG_WARN_EMPTY_BODY = YES
                        CLANG_WARN_ENUM_CONVERSION = YES
                        CLANG_WARN_INFINITE_RECURSION = YES
                        CLANG_WARN_INT_CONVERSION = YES
                        CLANG_WARN_NON_LITERAL_NULL_CONVERSION = YES
                        CLANG_WARN_OBJC_IMPLICIT_RETAIN_SELF = YES
                        CLANG_WARN_OBJC_LITERAL_CONVERSION = YES
                        CLANG_WARN_OBJC_ROOT_CLASS = YES_ERROR
                        CLANG_WARN_RANGE_LOOP_ANALYSIS = YES
                        CLANG_WARN_STRICT_PROTOTYPES = YES
                        CLANG_WARN_SUSPICIOUS_MOVE = YES
                        CLANG_WARN_UNREACHABLE_CODE = YES
                        CLANG_WARN__DUPLICATE_METHOD_MATCH = YES
                        CLASS_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/JavaClasses
                        CLEAN_PRECOMPS = YES
                        CLONE_HEADERS = NO
                        COCOAPODS_PARALLEL_CODE_SIGN = true
                        CODESIGNING_FOLDER_PATH = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        CODE_SIGNING_ALLOWED = YES
                        CODE_SIGNING_REQUIRED = YES
                        CODE_SIGN_CONTEXT_CLASS = XCiPhoneOSCodeSignContext
                        CODE_SIGN_IDENTITY = iPhone Developer
                        CODE_SIGN_INJECT_BASE_ENTITLEMENTS = YES
                        COLOR_DIAGNOSTICS = NO
                        COMBINE_HIDPI_IMAGES = NO
                        COMPILER_INDEX_STORE_ENABLE = Default
                        COMPOSITE_SDK_DIRS = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/CompositeSDKs
                        COMPRESS_PNG_FILES = YES
                        CONFIGURATION = Debug
                        CONFIGURATION_BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        CONFIGURATION_TEMP_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos
                        CONTENTS_FOLDER_PATH = Runner.app
                        CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Contents
                        CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        COPYING_PRESERVES_HFS_DATA = NO
                        COPY_HEADERS_RUN_UNIFDEF = NO
                        COPY_PHASE_STRIP = NO
                        COPY_RESOURCES_FROM_STATIC_FRAMEWORKS = YES
                        CORRESPONDING_SIMULATOR_PLATFORM_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform
                        CORRESPONDING_SIMULATOR_PLATFORM_NAME = iphonesimulator
                        CORRESPONDING_SIMULATOR_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator15.5.sdk
                        CORRESPONDING_SIMULATOR_SDK_NAME = iphonesimulator15.5
                        CP = /bin/cp
                        CREATE_INFOPLIST_SECTION_IN_BINARY = NO
                        CURRENT_ARCH = arm64
                        CURRENT_PROJECT_VERSION = 1
                        CURRENT_VARIANT = normal
                        DART_DEFINES = RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ==
                        DART_OBFUSCATION = false
                        DEAD_CODE_STRIPPING = YES
                        DEBUGGING_SYMBOLS = YES
                        DEBUG_INFORMATION_FORMAT = dwarf
                        DEFAULT_COMPILER = com.apple.compilers.llvm.clang.1_0
                        DEFAULT_DEXT_INSTALL_PATH = /System/Library/DriverExtensions
                        DEFAULT_KEXT_INSTALL_PATH = /System/Library/Extensions
                        DEFINES_MODULE = NO
                        DEPLOYMENT_LOCATION = NO
                        DEPLOYMENT_POSTPROCESSING = NO
                        DEPLOYMENT_TARGET_CLANG_ENV_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_CLANG_FLAG_NAME = miphoneos-version-min
                        DEPLOYMENT_TARGET_LD_ENV_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_LD_FLAG_NAME = ios_version_min
                        DEPLOYMENT_TARGET_SETTING_NAME = IPHONEOS_DEPLOYMENT_TARGET
                        DEPLOYMENT_TARGET_SUGGESTED_VALUES = 9.0 9.1 9.2 9.3 10.0 10.1 10.2 10.3 11.0 11.1 11.2 11.3 11.4 12.0 12.1 12.2 12.3 12.4 13.0 13.1 13.2 13.3 13.4 13.5 13.6 14.0
                        14.1 14.2 14.3 14.4 14.5 14.6 14.7 15.0 15.1 15.2 15.3 15.4 15.5
                        DERIVED_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSource
                        s
                        DERIVED_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSource
                        s
                        DERIVED_SOURCES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSource
                        s
                        DEVELOPER_APPLICATIONS_DIR = /Applications/Xcode.app/Contents/Developer/Applications
                        DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/usr/bin
                        DEVELOPER_DIR = /Applications/Xcode.app/Contents/Developer
                        DEVELOPER_FRAMEWORKS_DIR = /Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        DEVELOPER_FRAMEWORKS_DIR_QUOTED = /Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        DEVELOPER_LIBRARY_DIR = /Applications/Xcode.app/Contents/Developer/Library
                        DEVELOPER_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs
                        DEVELOPER_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Tools
                        DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/usr
                        DEVELOPMENT_LANGUAGE = en
                        DEVELOPMENT_TEAM = G7N8SR355W
                        DOCUMENTATION_FOLDER_PATH = Runner.app/en.lproj/Documentation
                        DONT_GENERATE_INFOPLIST_FILE = NO
                        DO_HEADER_SCANNING_IN_JAM = NO
                        DSTROOT = /tmp/Runner.dst
                        DT_TOOLCHAIN_DIR = /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        DWARF_DSYM_FILE_NAME = Runner.app.dSYM
                        DWARF_DSYM_FILE_SHOULD_ACCOMPANY_PRODUCT = NO
                        DWARF_DSYM_FOLDER_PATH = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        EFFECTIVE_PLATFORM_NAME = -iphoneos
                        EMBEDDED_CONTENT_CONTAINS_SWIFT = NO
                        EMBEDDED_PROFILE_NAME = embedded.mobileprovision
                        EMBED_ASSET_PACKS_IN_PRODUCT_BUNDLE = NO
                        ENABLE_APP_SANDBOX = NO
                        ENABLE_BITCODE = NO
                        ENABLE_DEFAULT_HEADER_SEARCH_PATHS = YES
                        ENABLE_DEFAULT_SEARCH_PATHS = YES
                        ENABLE_HARDENED_RUNTIME = NO
                        ENABLE_HEADER_DEPENDENCIES = YES
                        ENABLE_ON_DEMAND_RESOURCES = YES
                        ENABLE_STRICT_OBJC_MSGSEND = YES
                        ENABLE_TESTABILITY = YES
                        ENABLE_TESTING_SEARCH_PATHS = NO
                        ENTITLEMENTS_ALLOWED = YES
                        ENTITLEMENTS_DESTINATION = Signature
                        ENTITLEMENTS_REQUIRED = NO
                        EXCLUDED_INSTALLSRC_SUBDIRECTORY_PATTERNS = .DS_Store .svn .git .hg CVS
                        EXCLUDED_RECURSIVE_SEARCH_PATH_SUBDIRECTORIES = *.nib *.lproj *.framework *.gch *.xcode* *.xcassets (*) .DS_Store CVS .svn .git .hg *.pbproj *.pbxproj
                        EXECUTABLES_FOLDER_PATH = Runner.app/Executables
                        EXECUTABLE_FOLDER_PATH = Runner.app
                        EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/MacOS
                        EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        EXECUTABLE_NAME = Runner
                        EXECUTABLE_PATH = Runner.app/Runner
                        EXPANDED_CODE_SIGN_IDENTITY = 
                        EXPANDED_CODE_SIGN_IDENTITY_NAME = 
                        EXPANDED_PROVISIONING_PROFILE = 
                        FILE_LIST =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects/LinkF
                        ileList
                        FIXED_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/FixedFiles
                        FLUTTER_APPLICATION_PATH = /Users/sven/git_project/flat/test_ar
                        FLUTTER_BUILD_DIR = build
                        FLUTTER_BUILD_NAME = 1.0.0
                        FLUTTER_BUILD_NUMBER = 1
                        FLUTTER_ROOT = /Users/sven/flutterSdk/flutter
                        FLUTTER_TARGET = /Users/sven/git_project/flat/test_ar/lib/main.dart
                        FRAMEWORKS_FOLDER_PATH = Runner.app/Frameworks
                        FRAMEWORK_FLAG_PREFIX = -framework
                        FRAMEWORK_VERSION = A
                        FULL_PRODUCT_NAME = Runner.app
                        GCC3_VERSION = 3.3
                        GCC_C_LANGUAGE_STANDARD = gnu99
                        GCC_DYNAMIC_NO_PIC = NO
                        GCC_INLINES_ARE_PRIVATE_EXTERN = YES
                        GCC_NO_COMMON_BLOCKS = YES
                        GCC_OPTIMIZATION_LEVEL = 0
                        GCC_PFE_FILE_C_DIALECTS = c objective-c c++ objective-c++
                        GCC_PREPROCESSOR_DEFINITIONS = DEBUG=1 
                        GCC_SYMBOLS_PRIVATE_EXTERN = NO
                        GCC_THUMB_SUPPORT = YES
                        GCC_TREAT_WARNINGS_AS_ERRORS = NO
                        GCC_VERSION = com.apple.compilers.llvm.clang.1_0
                        GCC_VERSION_IDENTIFIER = com_apple_compilers_llvm_clang_1_0
                        GCC_WARN_64_TO_32_BIT_CONVERSION = YES
                        GCC_WARN_ABOUT_RETURN_TYPE = YES_ERROR
                        GCC_WARN_UNDECLARED_SELECTOR = YES
                        GCC_WARN_UNINITIALIZED_AUTOS = YES_AGGRESSIVE
                        GCC_WARN_UNUSED_FUNCTION = YES
                        GCC_WARN_UNUSED_VARIABLE = YES
                        GENERATED_MODULEMAP_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/GeneratedModuleMaps-iphoneos
                        GENERATE_INFOPLIST_FILE = NO
                        GENERATE_MASTER_OBJECT_FILE = NO
                        GENERATE_PKGINFO_FILE = YES
                        GENERATE_PROFILING_CODE = NO
                        GENERATE_TEXT_BASED_STUBS = NO
                        GID = 20
                        GROUP = staff
                        HEADERMAP_INCLUDES_FLAT_ENTRIES_FOR_TARGET_BEING_BUILT = YES
                        HEADERMAP_INCLUDES_FRAMEWORK_ENTRIES_FOR_ALL_PRODUCT_TYPES = YES
                        HEADERMAP_INCLUDES_NONPUBLIC_NONPRIVATE_HEADERS = YES
                        HEADERMAP_INCLUDES_PROJECT_HEADERS = YES
                        HEADERMAP_USES_FRAMEWORK_PREFIX_ENTRIES = YES
                        HEADERMAP_USES_VFS = NO
                        HIDE_BITCODE_SYMBOLS = YES
                        HOME = /Users/sven
                        ICONV = /usr/bin/iconv
                        INFOPLIST_EXPAND_BUILD_SETTINGS = YES
                        INFOPLIST_FILE = Runner/Info.plist
                        INFOPLIST_OUTPUT_FORMAT = binary
                        INFOPLIST_PATH = Runner.app/Info.plist
                        INFOPLIST_PREPROCESS = NO
                        INFOSTRINGS_PATH = Runner.app/en.lproj/InfoPlist.strings
                        INLINE_PRIVATE_FRAMEWORKS = NO
                        INSTALLHDRS_COPY_PHASE = NO
                        INSTALLHDRS_SCRIPT_PHASE = NO
                        INSTALL_DIR = /tmp/Runner.dst/Applications
                        INSTALL_GROUP = staff
                        INSTALL_MODE_FLAG = u+w,go-w,a+rX
                        INSTALL_OWNER = sven
                        INSTALL_PATH = /Applications
                        INSTALL_ROOT = /tmp/Runner.dst
                        IPHONEOS_DEPLOYMENT_TARGET = 9.0
                        JAVAC_DEFAULT_FLAGS = -J-Xms64m -J-XX:NewSize=4M -J-Dfile.encoding=UTF8
                        JAVA_APP_STUB = /System/Library/Frameworks/JavaVM.framework/Resources/MacOS/JavaApplicationStub
                        JAVA_ARCHIVE_CLASSES = YES
                        JAVA_ARCHIVE_TYPE = JAR
                        JAVA_COMPILER = /usr/bin/javac
                        JAVA_FOLDER_PATH = Runner.app/Java
                        JAVA_FRAMEWORK_RESOURCES_DIRS = Resources
                        JAVA_JAR_FLAGS = cv
                        JAVA_SOURCE_SUBDIR = .
                        JAVA_USE_DEPENDENCIES = YES
                        JAVA_ZIP_FLAGS = -urg
                        JIKES_DEFAULT_FLAGS = +E +OLDCSO
                        KASAN_DEFAULT_CFLAGS = -DKASAN=1 -fsanitize=address -mllvm -asan-globals-live-support -mllvm -asan-force-dynamic-shadow
                        KEEP_PRIVATE_EXTERNS = NO
                        LD_DEPENDENCY_INFO_FILE =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner_dependency_info.dat
                        LD_GENERATE_MAP_FILE = NO
                        LD_MAP_FILE_PATH =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-LinkMa
                        p-normal-arm64.txt
                        LD_NO_PIE = NO
                        LD_QUOTE_LINKER_ARGUMENTS_FOR_COMPILER_DRIVER = YES
                        LD_RUNPATH_SEARCH_PATHS =  @executable_path/Frameworks
                        LEGACY_DEVELOPER_DIR = /Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer
                        LEX = lex
                        LIBRARY_DEXT_INSTALL_PATH = /Library/DriverExtensions
                        LIBRARY_FLAG_NOSPACE = YES
                        LIBRARY_FLAG_PREFIX = -l
                        LIBRARY_KEXT_INSTALL_PATH = /Library/Extensions
                        LINKER_DISPLAYS_MANGLED_NAMES = NO
                        LINK_FILE_LIST_normal_arm64 = 
                        LINK_WITH_STANDARD_LIBRARIES = YES
                        LLVM_TARGET_TRIPLE_OS_VERSION = ios9.0
                        LLVM_TARGET_TRIPLE_VENDOR = apple
                        LOCALIZABLE_CONTENT_DIR = 
                        LOCALIZATION_EXPORT_SUPPORTED = YES
                        LOCALIZED_RESOURCES_FOLDER_PATH = Runner.app/en.lproj
                        LOCALIZED_STRING_MACRO_NAMES = NSLocalizedString CFCopyLocalizedString
                        LOCALIZED_STRING_SWIFTUI_SUPPORT = YES
                        LOCAL_ADMIN_APPS_DIR = /Applications/Utilities
                        LOCAL_APPS_DIR = /Applications
                        LOCAL_DEVELOPER_DIR = /Library/Developer
                        LOCAL_LIBRARY_DIR = /Library
                        LOCROOT = 
                        LOCSYMROOT = 
                        MACH_O_TYPE = mh_execute
                        MAC_OS_X_PRODUCT_BUILD_VERSION = 21E258
                        MAC_OS_X_VERSION_ACTUAL = 120301
                        MAC_OS_X_VERSION_MAJOR = 120000
                        MAC_OS_X_VERSION_MINOR = 120300
                        METAL_LIBRARY_FILE_BASE = default
                        METAL_LIBRARY_OUTPUT_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        MODULES_FOLDER_PATH = Runner.app/Modules
                        MODULE_CACHE_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex
                        MTL_ENABLE_DEBUG_INFO = YES
                        NATIVE_ARCH = arm64e
                        NATIVE_ARCH_32_BIT = i386
                        NATIVE_ARCH_64_BIT = arm64e
                        NATIVE_ARCH_ACTUAL = arm64e
                        NO_COMMON = YES
                        OBJECT_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects
                        OBJECT_FILE_DIR_normal =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l
                        OBJROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        ONLY_ACTIVE_ARCH = YES
                        OS = MACOS
                        OSAC = /usr/bin/osacompile
                        PACKAGE_CONFIG = /Users/sven/git_project/flat/test_ar/.dart_tool/package_config.json
                        PACKAGE_TYPE = com.apple.package-type.wrapper.application
                        PASCAL_STRINGS = YES
                        PATH =
                        /Applications/Xcode.app/Contents/Developer/usr/bin:/usr/local/opt/ruby@2.7/bin:/opt/local/bin:/opt/local/sbin:/Library/Java/JavaVirtualMachines/jdk1.8.0_111.jdk/Conte
                        nts/Home/bin:/usr/local/opt/openssl@1.1/bin:/Users/sven/androidsdk/tools:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/opt/X11/bin:/Library/Apple/usr/bin:/Users/sven/
                        androidsdk/platform-tools:/Users/sven/androidsdk/tools:/Users/sven/flutterSdk/flutter/bin:/Users/sven/flutterSdk/flutter/bin/cache/dart-sdk/bin:/Users/sven/mygo/bin:/
                        Users/sven/flutterSdk/flutter/.pub-cache/bin::/Users/sven/.pub-cache/bin:/Users/sven/androidsdk/ndk-bundle:/opt/homebrew/bin:/Users/sven/.rvm/bin
                        PATH_PREFIXES_EXCLUDED_FROM_HEADER_DEPENDENCIES = /usr/include /usr/local/include /System/Library/Frameworks /System/Library/PrivateFrameworks
                        /Applications/Xcode.app/Contents/Developer/Headers /Applications/Xcode.app/Contents/Developer/SDKs /Applications/Xcode.app/Contents/Developer/Platforms
                        PBDEVELOPMENTPLIST_PATH = Runner.app/pbdevelopment.plist
                        PFE_FILE_C_DIALECTS = objective-c
                        PKGINFO_FILE_PATH =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/PkgInfo
                        PKGINFO_PATH = Runner.app/PkgInfo
                        PLATFORM_DEVELOPER_APPLICATIONS_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Applications
                        PLATFORM_DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin
                        PLATFORM_DEVELOPER_LIBRARY_DIR = /Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer/Library
                        PLATFORM_DEVELOPER_SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs
                        PLATFORM_DEVELOPER_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Tools
                        PLATFORM_DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr
                        PLATFORM_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform
                        PLATFORM_DISPLAY_NAME = iOS
                        PLATFORM_NAME = iphoneos
                        PLATFORM_PREFERRED_ARCH = arm64
                        PLATFORM_PRODUCT_BUILD_VERSION = 19F64
                        PLIST_FILE_OUTPUT_FORMAT = binary
                        PLUGINS_FOLDER_PATH = Runner.app/PlugIns
                        PRECOMPS_INCLUDE_HEADERS_FROM_BUILT_PRODUCTS_DIR = YES
                        PRECOMP_DESTINATION_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/PrefixHeaders
                        PRESERVE_DEAD_CODE_INITS_AND_TERMS = NO
                        PRIVATE_HEADERS_FOLDER_PATH = Runner.app/PrivateHeaders
                        PRODUCT_BUNDLE_IDENTIFIER = com.example.testar.testAr
                        PRODUCT_BUNDLE_PACKAGE_TYPE = APPL
                        PRODUCT_MODULE_NAME = Runner
                        PRODUCT_NAME = Runner
                        PRODUCT_SETTINGS_PATH = /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
                        PRODUCT_TYPE = com.apple.product-type.application
                        PROFILING_CODE = NO
                        PROJECT = Runner
                        PROJECT_DERIVED_FILE_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/DerivedSources
                        PROJECT_DIR = /Users/sven/git_project/flat/test_ar/ios
                        PROJECT_FILE_PATH = /Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
                        PROJECT_NAME = Runner
                        PROJECT_TEMP_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build
                        PROJECT_TEMP_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        PROVISIONING_PROFILE_REQUIRED = YES
                        PUBLIC_HEADERS_FOLDER_PATH = Runner.app/Headers
                        RECURSIVE_SEARCH_PATHS_FOLLOW_SYMLINKS = YES
                        REMOVE_CVS_FROM_RESOURCES = YES
                        REMOVE_GIT_FROM_RESOURCES = YES
                        REMOVE_HEADERS_FROM_EMBEDDED_BUNDLES = YES
                        REMOVE_HG_FROM_RESOURCES = YES
                        REMOVE_SVN_FROM_RESOURCES = YES
                        RESOURCE_RULES_REQUIRED = YES
                        REZ_COLLECTOR_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/ResourceManag
                        erResources
                        REZ_OBJECTS_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/ResourceManag
                        erResources/Objects
                        SCAN_ALL_SOURCE_FILES_FOR_INCLUDES = NO
                        SCRIPTS_FOLDER_PATH = Runner.app/Scripts
                        SDKROOT = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_DIR = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_DIR_iphoneos15_5 = /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        SDK_NAME = iphoneos15.5
                        SDK_NAMES = iphoneos15.5
                        SDK_PRODUCT_BUILD_VERSION = 19F64
                        SDK_VERSION = 15.5
                        SDK_VERSION_ACTUAL = 150500
                        SDK_VERSION_MAJOR = 150000
                        SDK_VERSION_MINOR = 150500
                        SED = /usr/bin/sed
                        SEPARATE_STRIP = NO
                        SEPARATE_SYMBOL_EDIT = NO
                        SET_DIR_MODE_OWNER_GROUP = YES
                        SET_FILE_MODE_OWNER_GROUP = NO
                        SHALLOW_BUNDLE = YES
                        SHALLOW_BUNDLE_TRIPLE = ios
                        SHALLOW_BUNDLE_ios_macabi = NO
                        SHALLOW_BUNDLE_macos = NO
                        SHARED_DERIVED_FILE_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/DerivedSources
                        SHARED_FRAMEWORKS_FOLDER_PATH = Runner.app/SharedFrameworks
                        SHARED_PRECOMPS_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/PrecompiledHeaders
                        SHARED_SUPPORT_FOLDER_PATH = Runner.app/SharedSupport
                        SKIP_INSTALL = NO
                        SOURCE_ROOT = /Users/sven/git_project/flat/test_ar/ios
                        SRCROOT = /Users/sven/git_project/flat/test_ar/ios
                        STRINGSDATA_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64
                        STRINGSDATA_ROOT =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        STRINGS_FILE_INFOPLIST_RENAME = YES
                        STRINGS_FILE_OUTPUT_ENCODING = binary
                        STRIP_BITCODE_FROM_COPIED_FILES = YES
                        STRIP_INSTALLED_PRODUCT = YES
                        STRIP_STYLE = all
                        STRIP_SWIFT_SYMBOLS = YES
                        SUPPORTED_DEVICE_FAMILIES = 1,2
                        SUPPORTED_PLATFORMS = iphonesimulator iphoneos
                        SUPPORTS_MACCATALYST = NO
                        SUPPORTS_TEXT_BASED_API = NO
                        SWIFT_EMIT_LOC_STRINGS = NO
                        SWIFT_OBJC_BRIDGING_HEADER = Runner/Runner-Bridging-Header.h
                        SWIFT_OPTIMIZATION_LEVEL = -Onone
                        SWIFT_PLATFORM_TARGET_PREFIX = ios
                        SWIFT_VERSION = 5.0
                        SYMROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Products
                        SYSTEM_ADMIN_APPS_DIR = /Applications/Utilities
                        SYSTEM_APPS_DIR = /Applications
                        SYSTEM_CORE_SERVICES_DIR = /System/Library/CoreServices
                        SYSTEM_DEMOS_DIR = /Applications/Extras
                        SYSTEM_DEVELOPER_APPS_DIR = /Applications/Xcode.app/Contents/Developer/Applications
                        SYSTEM_DEVELOPER_BIN_DIR = /Applications/Xcode.app/Contents/Developer/usr/bin
                        SYSTEM_DEVELOPER_DEMOS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Utilities/Built Examples
                        SYSTEM_DEVELOPER_DIR = /Applications/Xcode.app/Contents/Developer
                        SYSTEM_DEVELOPER_DOC_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library
                        SYSTEM_DEVELOPER_GRAPHICS_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Graphics Tools
                        SYSTEM_DEVELOPER_JAVA_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Java Tools
                        SYSTEM_DEVELOPER_PERFORMANCE_TOOLS_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Performance Tools
                        SYSTEM_DEVELOPER_RELEASENOTES_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/releasenotes
                        SYSTEM_DEVELOPER_TOOLS = /Applications/Xcode.app/Contents/Developer/Tools
                        SYSTEM_DEVELOPER_TOOLS_DOC_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/documentation/DeveloperTools
                        SYSTEM_DEVELOPER_TOOLS_RELEASENOTES_DIR = /Applications/Xcode.app/Contents/Developer/ADC Reference Library/releasenotes/DeveloperTools
                        SYSTEM_DEVELOPER_USR_DIR = /Applications/Xcode.app/Contents/Developer/usr
                        SYSTEM_DEVELOPER_UTILITIES_DIR = /Applications/Xcode.app/Contents/Developer/Applications/Utilities
                        SYSTEM_DEXT_INSTALL_PATH = /System/Library/DriverExtensions
                        SYSTEM_DOCUMENTATION_DIR = /Library/Documentation
                        SYSTEM_EXTENSIONS_FOLDER_PATH = Runner.app/SystemExtensions
                        SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Library/SystemExtensions
                        SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app/SystemExtensions
                        SYSTEM_KEXT_INSTALL_PATH = /System/Library/Extensions
                        SYSTEM_LIBRARY_DIR = /System/Library
                        TAPI_ENABLE_PROJECT_HEADERS = NO
                        TAPI_VERIFY_MODE = ErrorsOnly
                        TARGETED_DEVICE_FAMILY = 1,2
                        TARGETNAME = Runner
                        TARGET_BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        TARGET_NAME = Runner
                        TARGET_TEMP_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_DIR = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_FILES_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_FILE_DIR =
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        TEMP_ROOT = /Users/sven/Library/Developer/Xcode/DerivedData/Runner-ebrhdyxgvdiwplasylajdreepdlp/Build/Intermediates.noindex
                        TEST_FRAMEWORK_SEARCH_PATHS =  /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Frameworks
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk/Developer/Library/Frameworks
                        TEST_LIBRARY_SEARCH_PATHS =  /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/lib
                        TOOLCHAIN_DIR = /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        TRACK_WIDGET_CREATION = true
                        TREAT_MISSING_BASELINES_AS_TEST_FAILURES = NO
                        TREE_SHAKE_ICONS = false
                        UID = 502
                        UNLOCALIZED_RESOURCES_FOLDER_PATH = Runner.app
                        UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_NO = Runner.app/Resources
                        UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_YES = Runner.app
                        UNSTRIPPED_PRODUCT = NO
                        USER = sven
                        USER_APPS_DIR = /Users/sven/Applications
                        USER_LIBRARY_DIR = /Users/sven/Library
                        USE_DYNAMIC_NO_PIC = YES
                        USE_HEADERMAP = YES
                        USE_HEADER_SYMLINKS = NO
                        USE_LLVM_TARGET_TRIPLES = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_CLANG = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_LD = YES
                        USE_LLVM_TARGET_TRIPLES_FOR_TAPI = YES
                        VALIDATE_PRODUCT = NO
                        VALIDATE_WORKSPACE = NO
                        VALID_ARCHS = arm64 arm64e armv7 armv7s
                        VERBOSE_PBXCP = NO
                        VERSIONING_SYSTEM = apple-generic
                        VERSIONPLIST_PATH = Runner.app/version.plist
                        VERSION_INFO_BUILDER = sven
                        VERSION_INFO_FILE = Runner_vers.c
                        VERSION_INFO_STRING = "@(#)PROGRAM:Runner  PROJECT:Runner-1"
                        WRAPPER_EXTENSION = app
                        WRAPPER_NAME = Runner.app
                        WRAPPER_SUFFIX = .app
                        WRAP_ASSET_PACKS_IN_SEPARATE_DIRECTORIES = NO
                        XCODE_APP_SUPPORT_DIR = /Applications/Xcode.app/Contents/Developer/Library/Xcode
                        XCODE_PRODUCT_BUILD_VERSION = 13F17a
                        XCODE_VERSION_ACTUAL = 1340
                        XCODE_VERSION_MAJOR = 1300
                        XCODE_VERSION_MINOR = 1340
                        XPCSERVICES_FOLDER_PATH = Runner.app/XPCServices
                        YACC = yacc
                        _WRAPPER_CONTENTS_DIR_SHALLOW_BUNDLE_NO = /Contents
                        _WRAPPER_PARENT_PATH_SHALLOW_BUNDLE_NO = /..
                        _WRAPPER_RESOURCES_DIR_SHALLOW_BUNDLE_NO = /Resources
                        __CODE_SIGNING_ALLOWED_appletvos = NO
                        __CODE_SIGNING_ALLOWED_iphoneos = NO
                        __CODE_SIGNING_ALLOWED_watchos = NO
                        arch = arm64
                        variant = normal


                    2022-09-01 13:38:57.460 xcodebuild[42650:363486] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionSentinelHostApplications for extension
                    Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:57.461 xcodebuild[42650:363486] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for
                    extension Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:38:57.514 xcodebuild[42650:363486] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/CocoaPods.xcplugin' not present in DVTPlugInCompatibilityUUIDs
                    2022-09-01 13:38:57.515 xcodebuild[42650:363486] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin' not present in DVTPlugInCompatibilityUUIDs
[   +5 ms] Automatically signing iOS for device deployment using specified development team in Xcode project: G7N8SR355W
[  +27 ms] executing: /usr/bin/plutil -convert xml1 -o - /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
[   +8 ms] Exit code 0 from: /usr/bin/plutil -convert xml1 -o - /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
[        ] <?xml version="1.0" encoding="UTF-8"?>
           <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
           <plist version="1.0">
           <dict>
           	<key>CADisableMinimumFrameDurationOnPhone</key>
           	<true/>
           	<key>CFBundleDevelopmentRegion</key>
           	<string>$(DEVELOPMENT_LANGUAGE)</string>
           	<key>CFBundleDisplayName</key>
           	<string>Test Ar</string>
           	<key>CFBundleExecutable</key>
           	<string>$(EXECUTABLE_NAME)</string>
           	<key>CFBundleIdentifier</key>
           	<string>$(PRODUCT_BUNDLE_IDENTIFIER)</string>
           	<key>CFBundleInfoDictionaryVersion</key>
           	<string>6.0</string>
           	<key>CFBundleName</key>
           	<string>test_ar</string>
           	<key>CFBundlePackageType</key>
           	<string>APPL</string>
           	<key>CFBundleShortVersionString</key>
           	<string>$(FLUTTER_BUILD_NAME)</string>
           	<key>CFBundleSignature</key>
           	<string>????</string>
           	<key>CFBundleVersion</key>
           	<string>$(FLUTTER_BUILD_NUMBER)</string>
           	<key>LSRequiresIPhoneOS</key>
           	<true/>
           	<key>UILaunchStoryboardName</key>
           	<string>LaunchScreen</string>
           	<key>UIMainStoryboardFile</key>
           	<string>Main</string>
           	<key>UISupportedInterfaceOrientations</key>
           	<array>
           		<string>UIInterfaceOrientationPortrait</string>
           		<string>UIInterfaceOrientationLandscapeLeft</string>
           		<string>UIInterfaceOrientationLandscapeRight</string>
           	</array>
           	<key>UISupportedInterfaceOrientations~ipad</key>
           	<array>
           		<string>UIInterfaceOrientationPortrait</string>
           		<string>UIInterfaceOrientationPortraitUpsideDown</string>
           		<string>UIInterfaceOrientationLandscapeLeft</string>
           		<string>UIInterfaceOrientationLandscapeRight</string>
           	</array>
           	<key>UIViewControllerBasedStatusBarAppearance</key>
           	<false/>
           </dict>
           </plist>
[   +2 ms] executing: mkfifo /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout
[  +14 ms] Exit code 0 from: mkfifo /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout
[   +2 ms] Running Xcode build...
[        ] executing: [/Users/sven/git_project/flat/test_ar/ios/] /usr/bin/arch -arm64e xcrun xcodebuild -configuration Debug VERBOSE_SCRIPT_LOGGING=YES -workspace Runner.xcworkspace -scheme
Runner BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios -sdk iphoneos -destination id=00008020-000B24363C86002E ONLY_ACTIVE_ARCH=YES ARCHS=arm64
SCRIPT_OUTPUT_STREAM_FILE=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout -resultBundlePath
/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle -resultBundleVersion 3 FLUTTER_SUPPRESS_ANALYTICS=true
COMPILER_INDEX_STORE_ENABLE=NO
[+5433 ms] Running Xcode build... (completed in 5.4s)
[        ]  └─Compiling, linking and signing...
[+2358 ms] Command line invocation:
                        /Applications/Xcode.app/Contents/Developer/usr/bin/xcodebuild -configuration Debug VERBOSE_SCRIPT_LOGGING=YES -workspace Runner.xcworkspace -scheme Runner
                        BUILD_DIR=/Users/sven/git_project/flat/test_ar/build/ios -sdk iphoneos -destination id=00008020-000B24363C86002E ONLY_ACTIVE_ARCH=YES ARCHS=arm64
                        SCRIPT_OUTPUT_STREAM_FILE=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout -resultBundlePath
                        /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle -resultBundleVersion 3
                        FLUTTER_SUPPRESS_ANALYTICS=true COMPILER_INDEX_STORE_ENABLE=NO

                    User defaults from command line:
                        IDEBuildOperationResultBundlePath = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle
                        IDEPackageSupportUseBuiltinSCM = YES
                        IDERequestedResultBundleFormatVersion = 3

                    Build settings from command line:
                        ARCHS = arm64
                        BUILD_DIR = /Users/sven/git_project/flat/test_ar/build/ios
                        COMPILER_INDEX_STORE_ENABLE = NO
                        FLUTTER_SUPPRESS_ANALYTICS = true
                        ONLY_ACTIVE_ARCH = YES
                        SCRIPT_OUTPUT_STREAM_FILE = /var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout
                        SDKROOT = iphoneos15.5
                        VERBOSE_SCRIPT_LOGGING = YES

                    Writing result bundle at path:
                    	/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle

                    note: Using new build system
                    note: Planning
                    Analyze workspace

                    Create build description
                    Build description signature: 0db60703ae2600ff5e16430de3ce3d4d
                    Build description path:
                    /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/XCBuildData/0db60703ae2600ff5e16430de3ce3d4d-desc.xcbuild

                    note: Build preparation complete
                    note: Building targets in dependency order
                    ProcessProductPackaging ""
                    /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner.app.xcent
                    (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios

                        Entitlements:

                        {
                        "application-identifier" = "G7N8SR355W.com.example.testar.testAr";
                        "com.apple.developer.team-identifier" = G7N8SR355W;
                        "get-task-allow" = 1;
                    }

                        builtin-productPackagingUtility -entitlements -format xml -o
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner.app.xc
                        ent

                    PhaseScriptExecution Run\ Script
                    /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Script-9740EEB61C
                    F901F6004384FC.sh (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export ACTION\=build
                        export AD_HOC_CODE_SIGNING_ALLOWED\=NO
                        export ALLOW_TARGET_PLATFORM_SPECIALIZATION\=NO
                        export ALTERNATE_GROUP\=staff
                        export ALTERNATE_MODE\=u+w,go-w,a+rX
                        export ALTERNATE_OWNER\=sven
                        export ALWAYS_EMBED_SWIFT_STANDARD_LIBRARIES\=NO
                        export ALWAYS_SEARCH_USER_PATHS\=NO
                        export ALWAYS_USE_SEPARATE_HEADERMAPS\=NO
                        export APPLE_INTERNAL_DEVELOPER_DIR\=/AppleInternal/Developer
                        export APPLE_INTERNAL_DIR\=/AppleInternal
                        export APPLE_INTERNAL_DOCUMENTATION_DIR\=/AppleInternal/Documentation
                        export APPLE_INTERNAL_LIBRARY_DIR\=/AppleInternal/Library
                        export APPLE_INTERNAL_TOOLS\=/AppleInternal/Developer/Tools
                        export APPLICATION_EXTENSION_API_ONLY\=NO
                        export APPLY_RULES_IN_COPY_FILES\=NO
                        export APPLY_RULES_IN_COPY_HEADERS\=NO
                        export ARCHS\=arm64
                        export ARCHS_STANDARD\=arm64\ armv7
                        export ARCHS_STANDARD_32_64_BIT\=armv7\ arm64
                        export ARCHS_STANDARD_32_BIT\=armv7
                        export ARCHS_STANDARD_64_BIT\=arm64
                        export ARCHS_STANDARD_INCLUDING_64_BIT\=arm64\ armv7
                        export ARCHS_UNIVERSAL_IPHONE_OS\=armv7\ arm64
                        export ASSETCATALOG_COMPILER_APPICON_NAME\=AppIcon
                        export ASSETCATALOG_FILTER_FOR_DEVICE_MODEL\=iPhone11,6
                        export ASSETCATALOG_FILTER_FOR_DEVICE_OS_VERSION\=15.6.1
                        export AVAILABLE_PLATFORMS\=appletvos\ appletvsimulator\ driverkit\ iphoneos\ iphonesimulator\ macosx\ watchos\ watchsimulator
                        export AppIdentifierPrefix\=G7N8SR355W.
                        export BITCODE_GENERATION_MODE\=marker
                        export BUILD_ACTIVE_RESOURCES_ONLY\=YES
                        export BUILD_COMPONENTS\=headers\ build
                        export BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios
                        export BUILD_LIBRARY_FOR_DISTRIBUTION\=NO
                        export BUILD_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Products
                        export BUILD_STYLE\=
                        export BUILD_VARIANTS\=normal
                        export BUILT_PRODUCTS_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export BUNDLE_CONTENTS_FOLDER_PATH_deep\=Contents/
                        export BUNDLE_EXECUTABLE_FOLDER_NAME_deep\=MacOS
                        export BUNDLE_FORMAT\=shallow
                        export BUNDLE_FRAMEWORKS_FOLDER_PATH\=Frameworks
                        export BUNDLE_PLUGINS_FOLDER_PATH\=PlugIns
                        export BUNDLE_PRIVATE_HEADERS_FOLDER_PATH\=PrivateHeaders
                        export BUNDLE_PUBLIC_HEADERS_FOLDER_PATH\=Headers
                        export CACHE_ROOT\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        export CCHROOT\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        export CHMOD\=/bin/chmod
                        export CHOWN\=/usr/sbin/chown
                        export CLANG_ANALYZER_NONNULL\=YES
                        export CLANG_CXX_LANGUAGE_STANDARD\=gnu++0x
                        export CLANG_CXX_LIBRARY\=libc++
                        export CLANG_ENABLE_MODULES\=YES
                        export CLANG_ENABLE_OBJC_ARC\=YES
                        export CLANG_MODULES_BUILD_SESSION_FILE\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex/Session.modulevalidation
                        export CLANG_WARN_BLOCK_CAPTURE_AUTORELEASING\=YES
                        export CLANG_WARN_BOOL_CONVERSION\=YES
                        export CLANG_WARN_COMMA\=YES
                        export CLANG_WARN_CONSTANT_CONVERSION\=YES
                        export CLANG_WARN_DEPRECATED_OBJC_IMPLEMENTATIONS\=YES
                        export CLANG_WARN_DIRECT_OBJC_ISA_USAGE\=YES_ERROR
                        export CLANG_WARN_EMPTY_BODY\=YES
                        export CLANG_WARN_ENUM_CONVERSION\=YES
                        export CLANG_WARN_INFINITE_RECURSION\=YES
                        export CLANG_WARN_INT_CONVERSION\=YES
                        export CLANG_WARN_NON_LITERAL_NULL_CONVERSION\=YES
                        export CLANG_WARN_OBJC_IMPLICIT_RETAIN_SELF\=YES
                        export CLANG_WARN_OBJC_LITERAL_CONVERSION\=YES
                        export CLANG_WARN_OBJC_ROOT_CLASS\=YES_ERROR
                        export CLANG_WARN_RANGE_LOOP_ANALYSIS\=YES
                        export CLANG_WARN_STRICT_PROTOTYPES\=YES
                        export CLANG_WARN_SUSPICIOUS_MOVE\=YES
                        export CLANG_WARN_UNREACHABLE_CODE\=YES
                        export CLANG_WARN__DUPLICATE_METHOD_MATCH\=YES
                        export
                        CLASS_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bui
                        ld/JavaClasses
                        export CLEAN_PRECOMPS\=YES
                        export CLONE_HEADERS\=NO
                        export COCOAPODS_PARALLEL_CODE_SIGN\=true
                        export CODESIGNING_FOLDER_PATH\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        export CODE_SIGNING_ALLOWED\=YES
                        export CODE_SIGNING_REQUIRED\=YES
                        export CODE_SIGN_CONTEXT_CLASS\=XCiPhoneOSCodeSignContext
                        export CODE_SIGN_IDENTITY\=iPhone\ Developer
                        export CODE_SIGN_INJECT_BASE_ENTITLEMENTS\=YES
                        export COLOR_DIAGNOSTICS\=NO
                        export COMBINE_HIDPI_IMAGES\=NO
                        export COMPILER_INDEX_STORE_ENABLE\=NO
                        export COMPOSITE_SDK_DIRS\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/CompositeSDKs
                        export COMPRESS_PNG_FILES\=YES
                        export CONFIGURATION\=Debug
                        export CONFIGURATION_BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export
                        CONFIGURATION_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos
                        export CONTENTS_FOLDER_PATH\=Runner.app
                        export CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Contents
                        export CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export COPYING_PRESERVES_HFS_DATA\=NO
                        export COPY_HEADERS_RUN_UNIFDEF\=NO
                        export COPY_PHASE_STRIP\=NO
                        export COPY_RESOURCES_FROM_STATIC_FRAMEWORKS\=YES
                        export CORRESPONDING_SIMULATOR_PLATFORM_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform
                        export CORRESPONDING_SIMULATOR_PLATFORM_NAME\=iphonesimulator
                        export CORRESPONDING_SIMULATOR_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator15.5.sdk
                        export CORRESPONDING_SIMULATOR_SDK_NAME\=iphonesimulator15.5
                        export CP\=/bin/cp
                        export CREATE_INFOPLIST_SECTION_IN_BINARY\=NO
                        export CURRENT_ARCH\=undefined_arch
                        export CURRENT_PROJECT_VERSION\=1
                        export CURRENT_VARIANT\=normal
                        export DART_DEFINES\=RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ\=\=
                        export DART_OBFUSCATION\=false
                        export DEAD_CODE_STRIPPING\=YES
                        export DEBUGGING_SYMBOLS\=YES
                        export DEBUG_INFORMATION_FORMAT\=dwarf
                        export DEFAULT_COMPILER\=com.apple.compilers.llvm.clang.1_0
                        export DEFAULT_DEXT_INSTALL_PATH\=/System/Library/DriverExtensions
                        export DEFAULT_KEXT_INSTALL_PATH\=/System/Library/Extensions
                        export DEFINES_MODULE\=NO
                        export DEPLOYMENT_LOCATION\=NO
                        export DEPLOYMENT_POSTPROCESSING\=NO
                        export DEPLOYMENT_TARGET_SETTING_NAME\=IPHONEOS_DEPLOYMENT_TARGET
                        export DEPLOYMENT_TARGET_SUGGESTED_VALUES\=9.0\ 9.1\ 9.2\ 9.3\ 10.0\ 10.1\ 10.2\ 10.3\ 11.0\ 11.1\ 11.2\ 11.3\ 11.4\ 12.0\ 12.1\ 12.2\ 12.3\ 12.4\ 13.0\ 13.1\ 13.2\
                        13.3\ 13.4\ 13.5\ 13.6\ 14.0\ 14.1\ 14.2\ 14.3\ 14.4\ 14.5\ 14.6\ 14.7\ 15.0\ 15.1\ 15.2\ 15.3\ 15.4\ 15.5
                        export
                        DERIVED_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/DerivedSources
                        export
                        DERIVED_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild/DerivedSources
                        export
                        DERIVED_SOURCES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runne
                        r.build/DerivedSources
                        export DERIVE_MACCATALYST_PRODUCT_BUNDLE_IDENTIFIER\=NO
                        export DEVELOPER_APPLICATIONS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications
                        export DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/usr/bin
                        export DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export DEVELOPER_FRAMEWORKS_DIR\=/Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        export DEVELOPER_FRAMEWORKS_DIR_QUOTED\=/Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        export DEVELOPER_LIBRARY_DIR\=/Applications/Xcode.app/Contents/Developer/Library
                        export DEVELOPER_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs
                        export DEVELOPER_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Tools
                        export DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/usr
                        export DEVELOPMENT_LANGUAGE\=en
                        export DEVELOPMENT_TEAM\=G7N8SR355W
                        export DOCUMENTATION_FOLDER_PATH\=Runner.app/en.lproj/Documentation
                        export DONT_GENERATE_INFOPLIST_FILE\=NO
                        export DO_HEADER_SCANNING_IN_JAM\=NO
                        export DSTROOT\=/tmp/Runner.dst
                        export DT_TOOLCHAIN_DIR\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        export DWARF_DSYM_FILE_NAME\=Runner.app.dSYM
                        export DWARF_DSYM_FILE_SHOULD_ACCOMPANY_PRODUCT\=NO
                        export DWARF_DSYM_FOLDER_PATH\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export DYNAMIC_LIBRARY_EXTENSION\=dylib
                        export EFFECTIVE_PLATFORM_NAME\=-iphoneos
                        export EMBEDDED_CONTENT_CONTAINS_SWIFT\=NO
                        export EMBEDDED_PROFILE_NAME\=embedded.mobileprovision
                        export EMBED_ASSET_PACKS_IN_PRODUCT_BUNDLE\=NO
                        export ENABLE_APP_SANDBOX\=NO
                        export ENABLE_BITCODE\=NO
                        export ENABLE_DEFAULT_HEADER_SEARCH_PATHS\=YES
                        export ENABLE_DEFAULT_SEARCH_PATHS\=YES
                        export ENABLE_HARDENED_RUNTIME\=NO
                        export ENABLE_HEADER_DEPENDENCIES\=YES
                        export ENABLE_ON_DEMAND_RESOURCES\=YES
                        export ENABLE_PREVIEWS\=NO
                        export ENABLE_STRICT_OBJC_MSGSEND\=YES
                        export ENABLE_TESTABILITY\=YES
                        export ENABLE_TESTING_SEARCH_PATHS\=NO
                        export ENTITLEMENTS_ALLOWED\=YES
                        export ENTITLEMENTS_DESTINATION\=Signature
                        export ENTITLEMENTS_REQUIRED\=NO
                        export EXCLUDED_INSTALLSRC_SUBDIRECTORY_PATTERNS\=.DS_Store\ .svn\ .git\ .hg\ CVS
                        export EXCLUDED_RECURSIVE_SEARCH_PATH_SUBDIRECTORIES\=\*.nib\ \*.lproj\ \*.framework\ \*.gch\ \*.xcode\*\ \*.xcassets\ \(\*\)\ .DS_Store\ CVS\ .svn\ .git\ .hg\
                        \*.pbproj\ \*.pbxproj
                        export EXECUTABLES_FOLDER_PATH\=Runner.app/Executables
                        export EXECUTABLE_FOLDER_PATH\=Runner.app
                        export EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/MacOS
                        export EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export EXECUTABLE_NAME\=Runner
                        export EXECUTABLE_PATH\=Runner.app/Runner
                        export EXPANDED_CODE_SIGN_IDENTITY\=7954D45E9F6FC02695DCDCE42B9A9414B63635C8
                        export EXPANDED_CODE_SIGN_IDENTITY_NAME\=Apple\ Development:\ Xiangyuan\ Liu\ \(WD2Z3R3ZN4\)
                        export EXPANDED_PROVISIONING_PROFILE\=09db4648-e01d-43ad-aeee-2590c2b85f97
                        export
                        FILE_LIST\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects/LinkFileList
                        export
                        FIXED_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/FixedFiles
                        export FLUTTER_APPLICATION_PATH\=/Users/sven/git_project/flat/test_ar
                        export FLUTTER_BUILD_DIR\=build
                        export FLUTTER_BUILD_NAME\=1.0.0
                        export FLUTTER_BUILD_NUMBER\=1
                        export FLUTTER_ROOT\=/Users/sven/flutterSdk/flutter
                        export FLUTTER_SUPPRESS_ANALYTICS\=true
                        export FLUTTER_TARGET\=/Users/sven/git_project/flat/test_ar/lib/main.dart
                        export FRAMEWORKS_FOLDER_PATH\=Runner.app/Frameworks
                        export FRAMEWORK_FLAG_PREFIX\=-framework
                        export FRAMEWORK_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export FRAMEWORK_VERSION\=A
                        export FULL_PRODUCT_NAME\=Runner.app
                        export GCC3_VERSION\=3.3
                        export GCC_C_LANGUAGE_STANDARD\=gnu99
                        export GCC_DYNAMIC_NO_PIC\=NO
                        export GCC_INLINES_ARE_PRIVATE_EXTERN\=YES
                        export GCC_NO_COMMON_BLOCKS\=YES
                        export GCC_OPTIMIZATION_LEVEL\=0
                        export GCC_PFE_FILE_C_DIALECTS\=c\ objective-c\ c++\ objective-c++
                        export GCC_PREPROCESSOR_DEFINITIONS\=DEBUG\=1\ 
                        export GCC_SYMBOLS_PRIVATE_EXTERN\=NO
                        export GCC_THUMB_SUPPORT\=YES
                        export GCC_TREAT_WARNINGS_AS_ERRORS\=NO
                        export GCC_VERSION\=com.apple.compilers.llvm.clang.1_0
                        export GCC_VERSION_IDENTIFIER\=com_apple_compilers_llvm_clang_1_0
                        export GCC_WARN_64_TO_32_BIT_CONVERSION\=YES
                        export GCC_WARN_ABOUT_RETURN_TYPE\=YES_ERROR
                        export GCC_WARN_UNDECLARED_SELECTOR\=YES
                        export GCC_WARN_UNINITIALIZED_AUTOS\=YES_AGGRESSIVE
                        export GCC_WARN_UNUSED_FUNCTION\=YES
                        export GCC_WARN_UNUSED_VARIABLE\=YES
                        export
                        GENERATED_MODULEMAP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/GeneratedModuleMaps-iphoneos
                        export GENERATE_INFOPLIST_FILE\=NO
                        export GENERATE_MASTER_OBJECT_FILE\=NO
                        export GENERATE_PKGINFO_FILE\=YES
                        export GENERATE_PROFILING_CODE\=NO
                        export GENERATE_TEXT_BASED_STUBS\=NO
                        export GID\=20
                        export GROUP\=staff
                        export HEADERMAP_INCLUDES_FLAT_ENTRIES_FOR_TARGET_BEING_BUILT\=YES
                        export HEADERMAP_INCLUDES_FRAMEWORK_ENTRIES_FOR_ALL_PRODUCT_TYPES\=YES
                        export HEADERMAP_INCLUDES_NONPUBLIC_NONPRIVATE_HEADERS\=YES
                        export HEADERMAP_INCLUDES_PROJECT_HEADERS\=YES
                        export HEADERMAP_USES_FRAMEWORK_PREFIX_ENTRIES\=YES
                        export HEADERMAP_USES_VFS\=NO
                        export HEADER_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include\ 
                        export HIDE_BITCODE_SYMBOLS\=YES
                        export HOME\=/Users/sven
                        export ICONV\=/usr/bin/iconv
                        export INFOPLIST_EXPAND_BUILD_SETTINGS\=YES
                        export INFOPLIST_FILE\=Runner/Info.plist
                        export INFOPLIST_OUTPUT_FORMAT\=binary
                        export INFOPLIST_PATH\=Runner.app/Info.plist
                        export INFOPLIST_PREPROCESS\=NO
                        export INFOSTRINGS_PATH\=Runner.app/en.lproj/InfoPlist.strings
                        export INLINE_PRIVATE_FRAMEWORKS\=NO
                        export INSTALLHDRS_COPY_PHASE\=NO
                        export INSTALLHDRS_SCRIPT_PHASE\=NO
                        export INSTALL_DIR\=/tmp/Runner.dst/Applications
                        export INSTALL_GROUP\=staff
                        export INSTALL_MODE_FLAG\=u+w,go-w,a+rX
                        export INSTALL_OWNER\=sven
                        export INSTALL_PATH\=/Applications
                        export INSTALL_ROOT\=/tmp/Runner.dst
                        export IPHONEOS_DEPLOYMENT_TARGET\=9.0
                        export JAVAC_DEFAULT_FLAGS\=-J-Xms64m\ -J-XX:NewSize\=4M\ -J-Dfile.encoding\=UTF8
                        export JAVA_APP_STUB\=/System/Library/Frameworks/JavaVM.framework/Resources/MacOS/JavaApplicationStub
                        export JAVA_ARCHIVE_CLASSES\=YES
                        export JAVA_ARCHIVE_TYPE\=JAR
                        export JAVA_COMPILER\=/usr/bin/javac
                        export JAVA_FOLDER_PATH\=Runner.app/Java
                        export JAVA_FRAMEWORK_RESOURCES_DIRS\=Resources
                        export JAVA_JAR_FLAGS\=cv
                        export JAVA_SOURCE_SUBDIR\=.
                        export JAVA_USE_DEPENDENCIES\=YES
                        export JAVA_ZIP_FLAGS\=-urg
                        export JIKES_DEFAULT_FLAGS\=+E\ +OLDCSO
                        export KASAN_DEFAULT_CFLAGS\=-DKASAN\=1\ -fsanitize\=address\ -mllvm\ -asan-globals-live-support\ -mllvm\ -asan-force-dynamic-shadow
                        export KEEP_PRIVATE_EXTERNS\=NO
                        export
                        LD_DEPENDENCY_INFO_FILE\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/R
                        unner.build/Objects-normal/undefined_arch/Runner_dependency_info.dat
                        export LD_GENERATE_MAP_FILE\=NO
                        export
                        LD_MAP_FILE_PATH\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild/Runner-LinkMap-normal-undefined_arch.txt
                        export LD_NO_PIE\=NO
                        export LD_QUOTE_LINKER_ARGUMENTS_FOR_COMPILER_DRIVER\=YES
                        export LD_RUNPATH_SEARCH_PATHS\=\ @executable_path/Frameworks
                        export LEGACY_DEVELOPER_DIR\=/Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer
                        export LEX\=lex
                        export LIBRARY_DEXT_INSTALL_PATH\=/Library/DriverExtensions
                        export LIBRARY_FLAG_NOSPACE\=YES
                        export LIBRARY_FLAG_PREFIX\=-l
                        export LIBRARY_KEXT_INSTALL_PATH\=/Library/Extensions
                        export LIBRARY_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export LINKER_DISPLAYS_MANGLED_NAMES\=NO
                        export
                        LINK_FILE_LIST_normal_arm64\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphone
                        os/Runner.build/Objects-normal/arm64/Runner.LinkFileList
                        export LINK_WITH_STANDARD_LIBRARIES\=YES
                        export LLVM_TARGET_TRIPLE_OS_VERSION\=ios9.0
                        export LLVM_TARGET_TRIPLE_VENDOR\=apple
                        export LOCALIZATION_EXPORT_SUPPORTED\=YES
                        export LOCALIZED_RESOURCES_FOLDER_PATH\=Runner.app/en.lproj
                        export LOCALIZED_STRING_MACRO_NAMES\=NSLocalizedString\ CFCopyLocalizedString
                        export LOCALIZED_STRING_SWIFTUI_SUPPORT\=YES
                        export LOCAL_ADMIN_APPS_DIR\=/Applications/Utilities
                        export LOCAL_APPS_DIR\=/Applications
                        export LOCAL_DEVELOPER_DIR\=/Library/Developer
                        export LOCAL_LIBRARY_DIR\=/Library
                        export LOCROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export LOCSYMROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export MACH_O_TYPE\=mh_execute
                        export MAC_OS_X_PRODUCT_BUILD_VERSION\=21E258
                        export MAC_OS_X_VERSION_ACTUAL\=120301
                        export MAC_OS_X_VERSION_MAJOR\=120000
                        export MAC_OS_X_VERSION_MINOR\=120300
                        export METAL_LIBRARY_FILE_BASE\=default
                        export METAL_LIBRARY_OUTPUT_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        export MODULES_FOLDER_PATH\=Runner.app/Modules
                        export MODULE_CACHE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex
                        export MTL_ENABLE_DEBUG_INFO\=YES
                        export NATIVE_ARCH\=arm64
                        export NATIVE_ARCH_32_BIT\=arm
                        export NATIVE_ARCH_64_BIT\=arm64
                        export NATIVE_ARCH_ACTUAL\=arm64
                        export NO_COMMON\=YES
                        export
                        OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/Objects
                        export
                        OBJECT_FILE_DIR_normal\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Ru
                        nner.build/Objects-normal
                        export OBJROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export ONLY_ACTIVE_ARCH\=YES
                        export OS\=MACOS
                        export OSAC\=/usr/bin/osacompile
                        export PACKAGE_CONFIG\=/Users/sven/git_project/flat/test_ar/.dart_tool/package_config.json
                        export PACKAGE_TYPE\=com.apple.package-type.wrapper.application
                        export PASCAL_STRINGS\=YES
                        export
                        PATH\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin:/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctool
                        chain/usr/local/bin:/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/libexec:/Applications/Xcode.app/Contents/Developer/Platforms/iP
                        honeOS.platform/usr/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/usr/local/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPho
                        neOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/local/bin:/Applications/Xcode.app/Contents/Develo
                        per/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/local/bin:/usr/local/opt/ruby@2.7/bin:/opt/local/bin:/opt/local/sbin:/Library/Java/JavaVirtualMachines/jdk1
                        .8.0_111.jdk/Contents/Home/bin:/usr/local/opt/openssl@1.1/bin:/Users/sven/androidsdk/tools:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/opt/X11/bin:/Library/Apple/us
                        r/bin:/Users/sven/androidsdk/platform-tools:/Users/sven/flutterSdk/flutter/bin:/Users/sven/flutterSdk/flutter/bin/cache/dart-sdk/bin:/Users/sven/mygo/bin:/Users/sven/
                        flutterSdk/flutter/.pub-cache/bin:/Users/sven/.pub-cache/bin:/Users/sven/androidsdk/ndk-bundle:/opt/homebrew/bin:/Users/sven/.rvm/bin
                        export PATH_PREFIXES_EXCLUDED_FROM_HEADER_DEPENDENCIES\=/usr/include\ /usr/local/include\ /System/Library/Frameworks\ /System/Library/PrivateFrameworks\
                        /Applications/Xcode.app/Contents/Developer/Headers\ /Applications/Xcode.app/Contents/Developer/SDKs\ /Applications/Xcode.app/Contents/Developer/Platforms
                        export PBDEVELOPMENTPLIST_PATH\=Runner.app/pbdevelopment.plist
                        export
                        PER_ARCH_OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/
                        Runner.build/Objects-normal/undefined_arch
                        export
                        PER_VARIANT_OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphone
                        os/Runner.build/Objects-normal
                        export
                        PKGINFO_FILE_PATH\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/PkgInfo
                        export PKGINFO_PATH\=Runner.app/PkgInfo
                        export PLATFORM_DEVELOPER_APPLICATIONS_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Applications
                        export PLATFORM_DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin
                        export PLATFORM_DEVELOPER_LIBRARY_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library
                        export PLATFORM_DEVELOPER_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs
                        export PLATFORM_DEVELOPER_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Tools
                        export PLATFORM_DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr
                        export PLATFORM_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform
                        export PLATFORM_DISPLAY_NAME\=iOS
                        export PLATFORM_FAMILY_NAME\=iOS
                        export PLATFORM_NAME\=iphoneos
                        export PLATFORM_PREFERRED_ARCH\=arm64
                        export PLATFORM_PRODUCT_BUILD_VERSION\=19F64
                        export PLIST_FILE_OUTPUT_FORMAT\=binary
                        export PLUGINS_FOLDER_PATH\=Runner.app/PlugIns
                        export PRECOMPS_INCLUDE_HEADERS_FROM_BUILT_PRODUCTS_DIR\=YES
                        export
                        PRECOMP_DESTINATION_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/R
                        unner.build/PrefixHeaders
                        export PRESERVE_DEAD_CODE_INITS_AND_TERMS\=NO
                        export PRIVATE_HEADERS_FOLDER_PATH\=Runner.app/PrivateHeaders
                        export PRODUCT_BUNDLE_IDENTIFIER\=com.example.testar.testAr
                        export PRODUCT_BUNDLE_PACKAGE_TYPE\=APPL
                        export PRODUCT_MODULE_NAME\=Runner
                        export PRODUCT_NAME\=Runner
                        export PRODUCT_SETTINGS_PATH\=/Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
                        export PRODUCT_TYPE\=com.apple.product-type.application
                        export PROFILING_CODE\=NO
                        export PROJECT\=Runner
                        export
                        PROJECT_DERIVED_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/DerivedSources
                        export PROJECT_DIR\=/Users/sven/git_project/flat/test_ar/ios
                        export PROJECT_FILE_PATH\=/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
                        export PROJECT_NAME\=Runner
                        export PROJECT_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build
                        export PROJECT_TEMP_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export PROVISIONING_PROFILE_REQUIRED\=YES
                        export PUBLIC_HEADERS_FOLDER_PATH\=Runner.app/Headers
                        export RECURSIVE_SEARCH_PATHS_FOLLOW_SYMLINKS\=YES
                        export REMOVE_CVS_FROM_RESOURCES\=YES
                        export REMOVE_GIT_FROM_RESOURCES\=YES
                        export REMOVE_HEADERS_FROM_EMBEDDED_BUNDLES\=YES
                        export REMOVE_HG_FROM_RESOURCES\=YES
                        export REMOVE_SVN_FROM_RESOURCES\=YES
                        export RESOURCE_RULES_REQUIRED\=YES
                        export
                        REZ_COLLECTOR_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/ResourceManagerResources
                        export
                        REZ_OBJECTS_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/ResourceManagerResources/Objects
                        export REZ_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export SCAN_ALL_SOURCE_FILES_FOR_INCLUDES\=NO
                        export SCRIPTS_FOLDER_PATH\=Runner.app/Scripts
                        export SCRIPT_INPUT_FILE_COUNT\=0
                        export SCRIPT_INPUT_FILE_LIST_COUNT\=0
                        export SCRIPT_OUTPUT_FILE_COUNT\=0
                        export SCRIPT_OUTPUT_FILE_LIST_COUNT\=0
                        export SCRIPT_OUTPUT_STREAM_FILE\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout
                        export SDKROOT\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR_iphoneos\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR_iphoneos15_5\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_NAME\=iphoneos15.5
                        export SDK_NAMES\=iphoneos15.5
                        export SDK_PRODUCT_BUILD_VERSION\=19F64
                        export SDK_VERSION\=15.5
                        export SDK_VERSION_ACTUAL\=150500
                        export SDK_VERSION_MAJOR\=150000
                        export SDK_VERSION_MINOR\=150500
                        export SED\=/usr/bin/sed
                        export SEPARATE_STRIP\=NO
                        export SEPARATE_SYMBOL_EDIT\=NO
                        export SET_DIR_MODE_OWNER_GROUP\=YES
                        export SET_FILE_MODE_OWNER_GROUP\=NO
                        export SHALLOW_BUNDLE\=YES
                        export SHALLOW_BUNDLE_TRIPLE\=ios
                        export SHALLOW_BUNDLE_ios_macabi\=NO
                        export SHALLOW_BUNDLE_macos\=NO
                        export SHARED_DERIVED_FILE_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/DerivedSources
                        export SHARED_FRAMEWORKS_FOLDER_PATH\=Runner.app/SharedFrameworks
                        export SHARED_PRECOMPS_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders
                        export SHARED_SUPPORT_FOLDER_PATH\=Runner.app/SharedSupport
                        export SKIP_INSTALL\=NO
                        export SOURCE_ROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export SRCROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export
                        STRINGSDATA_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/Objects-normal/undefined_arch
                        export
                        STRINGSDATA_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild
                        export STRINGS_FILE_INFOPLIST_RENAME\=YES
                        export STRINGS_FILE_OUTPUT_ENCODING\=binary
                        export STRIP_BITCODE_FROM_COPIED_FILES\=YES
                        export STRIP_INSTALLED_PRODUCT\=NO
                        export STRIP_STYLE\=all
                        export STRIP_SWIFT_SYMBOLS\=YES
                        export SUPPORTED_DEVICE_FAMILIES\=1,2
                        export SUPPORTED_PLATFORMS\=iphoneos\ iphonesimulator
                        export SUPPORTS_MACCATALYST\=NO
                        export SUPPORTS_MAC_DESIGNED_FOR_IPHONE_IPAD\=YES
                        export SUPPORTS_TEXT_BASED_API\=NO
                        export SWIFT_EMIT_LOC_STRINGS\=NO
                        export SWIFT_OBJC_BRIDGING_HEADER\=Runner/Runner-Bridging-Header.h
                        export SWIFT_OPTIMIZATION_LEVEL\=-Onone
                        export SWIFT_PLATFORM_TARGET_PREFIX\=ios
                        export
                        SWIFT_RESPONSE_FILE_PATH_normal_arm64\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/De
                        bug-iphoneos/Runner.build/Objects-normal/arm64/Runner.SwiftFileList
                        export SWIFT_VERSION\=5.0
                        export SYMROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Products
                        export SYSTEM_ADMIN_APPS_DIR\=/Applications/Utilities
                        export SYSTEM_APPS_DIR\=/Applications
                        export SYSTEM_CORE_SERVICES_DIR\=/System/Library/CoreServices
                        export SYSTEM_DEMOS_DIR\=/Applications/Extras
                        export SYSTEM_DEVELOPER_APPS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications
                        export SYSTEM_DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/usr/bin
                        export SYSTEM_DEVELOPER_DEMOS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Utilities/Built\ Examples
                        export SYSTEM_DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export SYSTEM_DEVELOPER_DOC_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library
                        export SYSTEM_DEVELOPER_GRAPHICS_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Graphics\ Tools
                        export SYSTEM_DEVELOPER_JAVA_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Java\ Tools
                        export SYSTEM_DEVELOPER_PERFORMANCE_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Performance\ Tools
                        export SYSTEM_DEVELOPER_RELEASENOTES_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/releasenotes
                        export SYSTEM_DEVELOPER_TOOLS\=/Applications/Xcode.app/Contents/Developer/Tools
                        export SYSTEM_DEVELOPER_TOOLS_DOC_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/documentation/DeveloperTools
                        export SYSTEM_DEVELOPER_TOOLS_RELEASENOTES_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/releasenotes/DeveloperTools
                        export SYSTEM_DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/usr
                        export SYSTEM_DEVELOPER_UTILITIES_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Utilities
                        export SYSTEM_DEXT_INSTALL_PATH\=/System/Library/DriverExtensions
                        export SYSTEM_DOCUMENTATION_DIR\=/Library/Documentation
                        export SYSTEM_EXTENSIONS_FOLDER_PATH\=Runner.app/SystemExtensions
                        export SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Library/SystemExtensions
                        export SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app/SystemExtensions
                        export SYSTEM_KEXT_INSTALL_PATH\=/System/Library/Extensions
                        export SYSTEM_LIBRARY_DIR\=/System/Library
                        export TAPI_ENABLE_PROJECT_HEADERS\=NO
                        export TAPI_VERIFY_MODE\=ErrorsOnly
                        export TARGETED_DEVICE_FAMILY\=1,2
                        export TARGETNAME\=Runner
                        export TARGET_BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export TARGET_DEVICE_IDENTIFIER\=00008020-000B24363C86002E
                        export TARGET_DEVICE_MODEL\=iPhone11,6
                        export TARGET_DEVICE_OS_VERSION\=15.6.1
                        export TARGET_DEVICE_PLATFORM_NAME\=iphoneos
                        export TARGET_NAME\=Runner
                        export
                        TARGET_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild
                        export
                        TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        export
                        TEMP_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bui
                        ld
                        export
                        TEMP_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.buil
                        d
                        export TEMP_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export TEST_FRAMEWORK_SEARCH_PATHS\=\ /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Frameworks\
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk/Developer/Library/Frameworks
                        export TEST_LIBRARY_SEARCH_PATHS\=\ /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/lib
                        export TOOLCHAINS\=com.apple.dt.toolchain.XcodeDefault
                        export TOOLCHAIN_DIR\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        export TRACK_WIDGET_CREATION\=true
                        export TREAT_MISSING_BASELINES_AS_TEST_FAILURES\=NO
                        export TREE_SHAKE_ICONS\=false
                        export TeamIdentifierPrefix\=G7N8SR355W.
                        export UID\=502
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH\=Runner.app
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Resources
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export UNSTRIPPED_PRODUCT\=NO
                        export USER\=sven
                        export USER_APPS_DIR\=/Users/sven/Applications
                        export USER_LIBRARY_DIR\=/Users/sven/Library
                        export USE_DYNAMIC_NO_PIC\=YES
                        export USE_HEADERMAP\=YES
                        export USE_HEADER_SYMLINKS\=NO
                        export USE_LLVM_TARGET_TRIPLES\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_CLANG\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_LD\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_TAPI\=YES
                        export VALIDATE_DEVELOPMENT_ASSET_PATHS\=YES_ERROR
                        export VALIDATE_PRODUCT\=NO
                        export VALIDATE_WORKSPACE\=YES_ERROR
                        export VALID_ARCHS\=arm64\ arm64e\ armv7\ armv7s
                        export VERBOSE_PBXCP\=NO
                        export VERBOSE_SCRIPT_LOGGING\=YES
                        export VERSIONING_SYSTEM\=apple-generic
                        export VERSIONPLIST_PATH\=Runner.app/version.plist
                        export VERSION_INFO_BUILDER\=sven
                        export VERSION_INFO_FILE\=Runner_vers.c
                        export VERSION_INFO_STRING\=\"@\(\#\)PROGRAM:Runner\ \ PROJECT:Runner-1\"
                        export WRAPPER_EXTENSION\=app
                        export WRAPPER_NAME\=Runner.app
                        export WRAPPER_SUFFIX\=.app
                        export WRAP_ASSET_PACKS_IN_SEPARATE_DIRECTORIES\=NO
                        export XCODE_APP_SUPPORT_DIR\=/Applications/Xcode.app/Contents/Developer/Library/Xcode
                        export XCODE_PRODUCT_BUILD_VERSION\=13F17a
                        export XCODE_VERSION_ACTUAL\=1340
                        export XCODE_VERSION_MAJOR\=1300
                        export XCODE_VERSION_MINOR\=1340
                        export XPCSERVICES_FOLDER_PATH\=Runner.app/XPCServices
                        export YACC\=yacc
                        export _WRAPPER_CONTENTS_DIR_SHALLOW_BUNDLE_NO\=/Contents
                        export _WRAPPER_PARENT_PATH_SHALLOW_BUNDLE_NO\=/..
                        export _WRAPPER_RESOURCES_DIR_SHALLOW_BUNDLE_NO\=/Resources
                        export __CODE_SIGNING_ALLOWED_appletvos\=NO
                        export __CODE_SIGNING_ALLOWED_iphoneos\=NO
                        export __CODE_SIGNING_ALLOWED_watchos\=NO
                        export arch\=undefined_arch
                        export variant\=normal
                        /bin/sh -c
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Script-9740EE
                        B61CF901F6004384FC.sh
                    ♦ /Users/sven/flutterSdk/flutter/bin/flutter --verbose assemble --no-version-check --output=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/
                    -dTargetPlatform=ios -dTargetFile=/Users/sven/git_project/flat/test_ar/lib/main.dart -dBuildMode=debug -dIosArchs=arm64
                    -dSdkRoot=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -dSplitDebugInfo= -dTreeShakeIcons=false
                    -dTrackWidgetCreation=true -dDartObfuscation=false -dEnableBitcode= --ExtraGenSnapshotOptions= --DartDefines=RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ==
                    --ExtraFrontEndOptions= -dCodesignIdentity=7954D45E9F6FC02695DCDCE42B9A9414B63635C8 debug_ios_bundle_flutter_assets
                    [  +38 ms] executing: sysctl hw.optional.arm64
                    [   +7 ms] Exit code 0 from: sysctl hw.optional.arm64
                    [        ] hw.optional.arm64: 1
                    [   +2 ms] executing: [/Users/sven/flutterSdk/flutter/] git -c log.showSignature=false log -n 1 --pretty=format:%H
                    [  +12 ms] Exit code 0 from: git -c log.showSignature=false log -n 1 --pretty=format:%H
                    [        ] f1875d570e39de09040c8f79aa13cc56baab8db1
                    [        ] executing: [/Users/sven/flutterSdk/flutter/] git tag --points-at f1875d570e39de09040c8f79aa13cc56baab8db1
                    [  +10 ms] Exit code 0 from: git tag --points-at f1875d570e39de09040c8f79aa13cc56baab8db1
                    [        ] 3.0.5
                    [   +3 ms] executing: [/Users/sven/flutterSdk/flutter/] git rev-parse --abbrev-ref --symbolic @{u}
                    [   +4 ms] Exit code 128 from: git rev-parse --abbrev-ref --symbolic @{u}
                    [        ] fatal: no upstream configured for branch '3.0.5'
                    [  +24 ms] executing: [/Users/sven/flutterSdk/flutter/] git rev-parse --abbrev-ref HEAD
                    [   +4 ms] Exit code 0 from: git rev-parse --abbrev-ref HEAD
                    [        ] heads/3.0.5
                    [  +19 ms] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'IOSEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping update.
                    [        ] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
                    [  +34 ms] Artifact Instance of 'MaterialFonts' is not required, skipping update.
                    [        ] Artifact Instance of 'GradleWrapper' is not required, skipping update.
                    [        ] Artifact Instance of 'AndroidGenSnapshotArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'AndroidInternalBuildArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterWebSdk' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterSdk' is not required, skipping update.
                    [        ] Artifact Instance of 'WindowsEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'WindowsUwpEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'MacOSEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'LinuxEngineArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'LinuxFuchsiaSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'MacOSFuchsiaSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterRunnerSDKArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FlutterRunnerDebugSymbols' is not required, skipping update.
                    [        ] Artifact Instance of 'IosUsbArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'IosUsbArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'IosUsbArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'IosUsbArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'IosUsbArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'FontSubsetArtifacts' is not required, skipping update.
                    [        ] Artifact Instance of 'PubDependencies' is not required, skipping update.
                    [   +9 ms] Initializing file store
                    [   +3 ms] Done initializing file store
                    [ +228 ms] Skipping target: debug_unpack_ios
                    [   +1 ms] Skipping target: gen_localizations
                    [   +1 ms] Skipping target: gen_dart_plugin_registrant
                    [ +448 ms] Skipping target: kernel_snapshot
                    [   +2 ms] Skipping target: debug_universal_framework
                    [ +281 ms] Skipping target: debug_ios_bundle_flutter_assets
                    [        ] Persisting file store
                    [   +3 ms] Done persisting file store
                    [   +2 ms] build succeeded.
                    [   +3 ms] "flutter assemble" took 1,028ms.
                    [   +2 ms] ensureAnalyticsSent: 1ms
                    [        ] Running shutdown hooks
                    [        ] Shutdown hooks complete
                    [        ] exiting with code 0
                    Project /Users/sven/git_project/flat/test_ar built and packaged successfully.
                    CompileSwiftSources normal arm64 com.apple.xcode.tools.swift.compiler (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export SDKROOT\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swiftc -incremental -module-name Runner -Onone -enable-batch-mode
                        -enforce-exclusivity\=checked
                        @/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norm
                        al/arm64/Runner.SwiftFileList -sdk /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -target arm64-apple-ios9.0
                        -g -module-cache-path /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex -Xfrontend -serialize-debugging-options -enable-testing -swift-version 5 -I
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -F /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -parse-as-library -c -j8
                        -output-file-map
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner-OutputFileMap.json -parseable-output -serialize-diagnostics -emit-dependencies -emit-module -emit-module-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.swiftmodule -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/swift-overr
                        ides.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-genera
                        ted-files.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-own-
                        target-headers.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-all-
                        target-headers.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-projec
                        t-headers.hmap -Xcc -I/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces-normal/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces -Xcc -DDEBUG\=1 -emit-objc-header -emit-objc-header-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner-Swift.h -import-objc-header /Users/sven/git_project/flat/test_ar/ios/Runner/Runner-Bridging-Header.h -pch-output-dir
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders -working-directory
                        /Users/sven/git_project/flat/test_ar/ios

                    PrecompileSwiftBridgingHeader normal arm64 (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-frontend -frontend -target arm64-apple-ios9.0 -Xllvm -aarch64-use-tbi
                        -enable-objc-interop -sdk /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -I
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -F /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -enable-testing -g -module-cache-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex -swift-version 5 -enforce-exclusivity\=checked -Onone -new-driver-path
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-driver -serialize-debugging-options -Xcc -working-directory -Xcc
                        /Users/sven/git_project/flat/test_ar/ios -resource-dir /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/swift
                        -enable-anonymous-context-mangled-names -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/swift-overr
                        ides.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-genera
                        ted-files.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-own-
                        target-headers.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-all-
                        target-headers.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-projec
                        t-headers.hmap -Xcc -I/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces-normal/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces -Xcc -DDEBUG\=1 -import-objc-header /Users/sven/git_project/flat/test_ar/ios/Runner/Runner-Bridging-Header.h -module-name Runner -target-sdk-version 15.5
                        -serialize-diagnostics-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders/Runner-Bridging-Header-1pxesgsa3y4c
                        n.dia /Users/sven/git_project/flat/test_ar/ios/Runner/Runner-Bridging-Header.h -emit-pch -pch-output-dir
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders

                    EmitSwiftModule normal arm64 (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-frontend -frontend -emit-module
                        -experimental-skip-non-inlinable-function-bodies-without-types /Users/sven/git_project/flat/test_ar/ios/Runner/AppDelegate.swift -target arm64-apple-ios9.0 -Xllvm
                        -aarch64-use-tbi -enable-objc-interop -sdk /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -I
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -F /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -enable-testing -g -module-cache-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex -swift-version 5 -enforce-exclusivity\=checked -Onone -new-driver-path
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-driver -serialize-debugging-options -Xcc -working-directory -Xcc
                        /Users/sven/git_project/flat/test_ar/ios -resource-dir /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/swift
                        -enable-anonymous-context-mangled-names -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/swift-overr
                        ides.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-genera
                        ted-files.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-own-
                        target-headers.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-all-
                        target-headers.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-projec
                        t-headers.hmap -Xcc -I/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces-normal/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces -Xcc -DDEBUG\=1 -import-objc-header /Users/sven/git_project/flat/test_ar/ios/Runner/Runner-Bridging-Header.h -pch-output-dir
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders -pch-disable-validation
                        -module-name Runner -target-sdk-version 15.5 -emit-module-doc-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.swiftdoc -emit-module-source-info-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.swiftsourceinfo -emit-objc-header-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner-Swift.h -parse-as-library -o
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.swiftmodule -emit-abi-descriptor-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.abi.json

                    CompileSwift normal arm64 /Users/sven/git_project/flat/test_ar/ios/Runner/AppDelegate.swift (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-frontend -frontend -c -primary-file
                        /Users/sven/git_project/flat/test_ar/ios/Runner/AppDelegate.swift -emit-dependencies-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/AppDelegate.d -emit-reference-dependencies-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/AppDelegate.swiftdeps -serialize-diagnostics-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/AppDelegate.dia -target arm64-apple-ios9.0 -Xllvm -aarch64-use-tbi -enable-objc-interop -sdk
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -I
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -F /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -enable-testing -g -module-cache-path
                        /Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex -swift-version 5 -enforce-exclusivity\=checked -Onone -new-driver-path
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/swift-driver -serialize-debugging-options -Xcc -working-directory -Xcc
                        /Users/sven/git_project/flat/test_ar/ios -resource-dir /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/swift
                        -enable-anonymous-context-mangled-names -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/swift-overr
                        ides.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-genera
                        ted-files.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-own-
                        target-headers.hmap -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-all-
                        target-headers.hmap -Xcc -iquote -Xcc
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-projec
                        t-headers.hmap -Xcc -I/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces-normal/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces/arm64 -Xcc
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces -Xcc -DDEBUG\=1 -import-objc-header /Users/sven/git_project/flat/test_ar/ios/Runner/Runner-Bridging-Header.h -pch-output-dir
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders -pch-disable-validation
                        -module-name Runner -target-sdk-version 15.5 -parse-as-library -o
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/AppDelegate.o

                    CompileC
                    /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-normal/ar
                    m64/GeneratedPluginRegistrant.o /Users/sven/git_project/flat/test_ar/ios/Runner/GeneratedPluginRegistrant.m normal arm64 objective-c
                    com.apple.compilers.llvm.clang.1_0.compiler (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export LANG\=en_US.US-ASCII
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -x objective-c -target arm64-apple-ios9.0 -fmessage-length\=0
                        -fdiagnostics-show-note-include-stack -fmacro-backtrace-limit\=0 -std\=gnu99 -fobjc-arc -fmodules -gmodules
                        -fmodules-cache-path\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex -fmodules-prune-interval\=86400 -fmodules-prune-after\=345600
                        -fbuild-session-file\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex/Session.modulevalidation -fmodules-validate-once-per-build-session
                        -Wnon-modular-include-in-framework-module -Werror\=non-modular-include-in-framework-module -Wno-trigraphs -fpascal-strings -O0 -fno-common
                        -Wno-missing-field-initializers -Wno-missing-prototypes -Werror\=return-type -Wunreachable-code -Wno-implicit-atomic-properties -Werror\=deprecated-objc-isa-usage
                        -Wno-objc-interface-ivars -Werror\=objc-root-class -Wno-arc-repeated-use-of-weak -Wimplicit-retain-self -Wduplicate-method-match -Wno-missing-braces -Wparentheses
                        -Wswitch -Wunused-function -Wno-unused-label -Wno-unused-parameter -Wunused-variable -Wunused-value -Wempty-body -Wuninitialized -Wconditional-uninitialized
                        -Wno-unknown-pragmas -Wno-shadow -Wno-four-char-constants -Wno-conversion -Wconstant-conversion -Wint-conversion -Wbool-conversion -Wenum-conversion
                        -Wno-float-conversion -Wnon-literal-null-conversion -Wobjc-literal-conversion -Wshorten-64-to-32 -Wpointer-sign -Wno-newline-eof -Wno-selector
                        -Wno-strict-selector-match -Wundeclared-selector -Wdeprecated-implementations -DDEBUG\=1 -DOBJC_OLD_DISPATCH_PROTOTYPES\=0 -isysroot
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -fstrict-aliasing -Wprotocol -Wdeprecated-declarations -g
                        -Wno-sign-conversion -Winfinite-recursion -Wcomma -Wblock-capture-autoreleasing -Wstrict-prototypes -Wno-semicolon-before-method-body -iquote
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-genera
                        ted-files.hmap
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-own-
                        target-headers.hmap
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-all-
                        target-headers.hmap -iquote
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner-projec
                        t-headers.hmap -I/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces-normal/arm64
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces/arm64
                        -I/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/DerivedSour
                        ces -F/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -MMD -MT dependencies -MF
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/GeneratedPluginRegistrant.d --serialize-diagnostics
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/GeneratedPluginRegistrant.dia -c /Users/sven/git_project/flat/test_ar/ios/Runner/GeneratedPluginRegistrant.m -o
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/GeneratedPluginRegistrant.o

                    Ld /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Runner normal (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/clang -target arm64-apple-ios9.0 -isysroot
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk -L/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        -F/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos -filelist
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.LinkFileList -Xlinker -rpath -Xlinker /usr/lib/swift -Xlinker -rpath -Xlinker @executable_path/Frameworks -dead_strip -Xlinker -object_path_lto
                        -Xlinker
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner_lto.o -Xlinker -export_dynamic -Xlinker -no_deduplicate -fobjc-arc -fobjc-link-runtime
                        -L/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/lib/swift/iphoneos -L/usr/lib/swift -Xlinker -add_ast_path -Xlinker
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner.swiftmodule -Xlinker -no_adhoc_codesign -Xlinker -dependency_info -Xlinker
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Objects-norma
                        l/arm64/Runner_dependency_info.dat -o /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Runner

                    ProcessInfoPlistFile /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Info.plist /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist (in
                    target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        builtin-infoPlistUtility /Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist -producttype com.apple.product-type.application -genpkginfo
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/PkgInfo -expandbuildsettings -format binary -platform iphoneos -additionalcontentfile
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Base.lproj/La
                        unchScreen-SBPartialInfo.plist -additionalcontentfile
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Base.lproj/Ma
                        in-SBPartialInfo.plist -additionalcontentfile
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/assetcatalog_
                        generated_info.plist -requiredArchitecture arm64 -o /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Info.plist

                    PhaseScriptExecution Thin\ Binary
                    /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Script-3B06AD1E1E
                    4923F5004D2608.sh (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export ACTION\=build
                        export AD_HOC_CODE_SIGNING_ALLOWED\=NO
                        export ALLOW_TARGET_PLATFORM_SPECIALIZATION\=NO
                        export ALTERNATE_GROUP\=staff
                        export ALTERNATE_MODE\=u+w,go-w,a+rX
                        export ALTERNATE_OWNER\=sven
                        export ALWAYS_EMBED_SWIFT_STANDARD_LIBRARIES\=NO
                        export ALWAYS_SEARCH_USER_PATHS\=NO
                        export ALWAYS_USE_SEPARATE_HEADERMAPS\=NO
                        export APPLE_INTERNAL_DEVELOPER_DIR\=/AppleInternal/Developer
                        export APPLE_INTERNAL_DIR\=/AppleInternal
                        export APPLE_INTERNAL_DOCUMENTATION_DIR\=/AppleInternal/Documentation
                        export APPLE_INTERNAL_LIBRARY_DIR\=/AppleInternal/Library
                        export APPLE_INTERNAL_TOOLS\=/AppleInternal/Developer/Tools
                        export APPLICATION_EXTENSION_API_ONLY\=NO
                        export APPLY_RULES_IN_COPY_FILES\=NO
                        export APPLY_RULES_IN_COPY_HEADERS\=NO
                        export ARCHS\=arm64
                        export ARCHS_STANDARD\=arm64\ armv7
                        export ARCHS_STANDARD_32_64_BIT\=armv7\ arm64
                        export ARCHS_STANDARD_32_BIT\=armv7
                        export ARCHS_STANDARD_64_BIT\=arm64
                        export ARCHS_STANDARD_INCLUDING_64_BIT\=arm64\ armv7
                        export ARCHS_UNIVERSAL_IPHONE_OS\=armv7\ arm64
                        export ASSETCATALOG_COMPILER_APPICON_NAME\=AppIcon
                        export ASSETCATALOG_FILTER_FOR_DEVICE_MODEL\=iPhone11,6
                        export ASSETCATALOG_FILTER_FOR_DEVICE_OS_VERSION\=15.6.1
                        export AVAILABLE_PLATFORMS\=appletvos\ appletvsimulator\ driverkit\ iphoneos\ iphonesimulator\ macosx\ watchos\ watchsimulator
                        export AppIdentifierPrefix\=G7N8SR355W.
                        export BITCODE_GENERATION_MODE\=marker
                        export BUILD_ACTIVE_RESOURCES_ONLY\=YES
                        export BUILD_COMPONENTS\=headers\ build
                        export BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios
                        export BUILD_LIBRARY_FOR_DISTRIBUTION\=NO
                        export BUILD_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Products
                        export BUILD_STYLE\=
                        export BUILD_VARIANTS\=normal
                        export BUILT_PRODUCTS_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export BUNDLE_CONTENTS_FOLDER_PATH_deep\=Contents/
                        export BUNDLE_EXECUTABLE_FOLDER_NAME_deep\=MacOS
                        export BUNDLE_FORMAT\=shallow
                        export BUNDLE_FRAMEWORKS_FOLDER_PATH\=Frameworks
                        export BUNDLE_PLUGINS_FOLDER_PATH\=PlugIns
                        export BUNDLE_PRIVATE_HEADERS_FOLDER_PATH\=PrivateHeaders
                        export BUNDLE_PUBLIC_HEADERS_FOLDER_PATH\=Headers
                        export CACHE_ROOT\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        export CCHROOT\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/C/com.apple.DeveloperTools/13.4-13F17a/Xcode
                        export CHMOD\=/bin/chmod
                        export CHOWN\=/usr/sbin/chown
                        export CLANG_ANALYZER_NONNULL\=YES
                        export CLANG_CXX_LANGUAGE_STANDARD\=gnu++0x
                        export CLANG_CXX_LIBRARY\=libc++
                        export CLANG_ENABLE_MODULES\=YES
                        export CLANG_ENABLE_OBJC_ARC\=YES
                        export CLANG_MODULES_BUILD_SESSION_FILE\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex/Session.modulevalidation
                        export CLANG_WARN_BLOCK_CAPTURE_AUTORELEASING\=YES
                        export CLANG_WARN_BOOL_CONVERSION\=YES
                        export CLANG_WARN_COMMA\=YES
                        export CLANG_WARN_CONSTANT_CONVERSION\=YES
                        export CLANG_WARN_DEPRECATED_OBJC_IMPLEMENTATIONS\=YES
                        export CLANG_WARN_DIRECT_OBJC_ISA_USAGE\=YES_ERROR
                        export CLANG_WARN_EMPTY_BODY\=YES
                        export CLANG_WARN_ENUM_CONVERSION\=YES
                        export CLANG_WARN_INFINITE_RECURSION\=YES
                        export CLANG_WARN_INT_CONVERSION\=YES
                        export CLANG_WARN_NON_LITERAL_NULL_CONVERSION\=YES
                        export CLANG_WARN_OBJC_IMPLICIT_RETAIN_SELF\=YES
                        export CLANG_WARN_OBJC_LITERAL_CONVERSION\=YES
                        export CLANG_WARN_OBJC_ROOT_CLASS\=YES_ERROR
                        export CLANG_WARN_RANGE_LOOP_ANALYSIS\=YES
                        export CLANG_WARN_STRICT_PROTOTYPES\=YES
                        export CLANG_WARN_SUSPICIOUS_MOVE\=YES
                        export CLANG_WARN_UNREACHABLE_CODE\=YES
                        export CLANG_WARN__DUPLICATE_METHOD_MATCH\=YES
                        export
                        CLASS_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bui
                        ld/JavaClasses
                        export CLEAN_PRECOMPS\=YES
                        export CLONE_HEADERS\=NO
                        export COCOAPODS_PARALLEL_CODE_SIGN\=true
                        export CODESIGNING_FOLDER_PATH\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        export CODE_SIGNING_ALLOWED\=YES
                        export CODE_SIGNING_REQUIRED\=YES
                        export CODE_SIGN_CONTEXT_CLASS\=XCiPhoneOSCodeSignContext
                        export CODE_SIGN_IDENTITY\=iPhone\ Developer
                        export CODE_SIGN_INJECT_BASE_ENTITLEMENTS\=YES
                        export COLOR_DIAGNOSTICS\=NO
                        export COMBINE_HIDPI_IMAGES\=NO
                        export COMPILER_INDEX_STORE_ENABLE\=NO
                        export COMPOSITE_SDK_DIRS\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/CompositeSDKs
                        export COMPRESS_PNG_FILES\=YES
                        export CONFIGURATION\=Debug
                        export CONFIGURATION_BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export
                        CONFIGURATION_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos
                        export CONTENTS_FOLDER_PATH\=Runner.app
                        export CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Contents
                        export CONTENTS_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export COPYING_PRESERVES_HFS_DATA\=NO
                        export COPY_HEADERS_RUN_UNIFDEF\=NO
                        export COPY_PHASE_STRIP\=NO
                        export COPY_RESOURCES_FROM_STATIC_FRAMEWORKS\=YES
                        export CORRESPONDING_SIMULATOR_PLATFORM_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform
                        export CORRESPONDING_SIMULATOR_PLATFORM_NAME\=iphonesimulator
                        export CORRESPONDING_SIMULATOR_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator15.5.sdk
                        export CORRESPONDING_SIMULATOR_SDK_NAME\=iphonesimulator15.5
                        export CP\=/bin/cp
                        export CREATE_INFOPLIST_SECTION_IN_BINARY\=NO
                        export CURRENT_ARCH\=undefined_arch
                        export CURRENT_PROJECT_VERSION\=1
                        export CURRENT_VARIANT\=normal
                        export DART_DEFINES\=RkxVVFRFUl9XRUJfQVVUT19ERVRFQ1Q9dHJ1ZQ\=\=
                        export DART_OBFUSCATION\=false
                        export DEAD_CODE_STRIPPING\=YES
                        export DEBUGGING_SYMBOLS\=YES
                        export DEBUG_INFORMATION_FORMAT\=dwarf
                        export DEFAULT_COMPILER\=com.apple.compilers.llvm.clang.1_0
                        export DEFAULT_DEXT_INSTALL_PATH\=/System/Library/DriverExtensions
                        export DEFAULT_KEXT_INSTALL_PATH\=/System/Library/Extensions
                        export DEFINES_MODULE\=NO
                        export DEPLOYMENT_LOCATION\=NO
                        export DEPLOYMENT_POSTPROCESSING\=NO
                        export DEPLOYMENT_TARGET_SETTING_NAME\=IPHONEOS_DEPLOYMENT_TARGET
                        export DEPLOYMENT_TARGET_SUGGESTED_VALUES\=9.0\ 9.1\ 9.2\ 9.3\ 10.0\ 10.1\ 10.2\ 10.3\ 11.0\ 11.1\ 11.2\ 11.3\ 11.4\ 12.0\ 12.1\ 12.2\ 12.3\ 12.4\ 13.0\ 13.1\ 13.2\
                        13.3\ 13.4\ 13.5\ 13.6\ 14.0\ 14.1\ 14.2\ 14.3\ 14.4\ 14.5\ 14.6\ 14.7\ 15.0\ 15.1\ 15.2\ 15.3\ 15.4\ 15.5
                        export
                        DERIVED_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/DerivedSources
                        export
                        DERIVED_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild/DerivedSources
                        export
                        DERIVED_SOURCES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runne
                        r.build/DerivedSources
                        export DERIVE_MACCATALYST_PRODUCT_BUNDLE_IDENTIFIER\=NO
                        export DEVELOPER_APPLICATIONS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications
                        export DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/usr/bin
                        export DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export DEVELOPER_FRAMEWORKS_DIR\=/Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        export DEVELOPER_FRAMEWORKS_DIR_QUOTED\=/Applications/Xcode.app/Contents/Developer/Library/Frameworks
                        export DEVELOPER_LIBRARY_DIR\=/Applications/Xcode.app/Contents/Developer/Library
                        export DEVELOPER_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs
                        export DEVELOPER_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Tools
                        export DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/usr
                        export DEVELOPMENT_LANGUAGE\=en
                        export DEVELOPMENT_TEAM\=G7N8SR355W
                        export DOCUMENTATION_FOLDER_PATH\=Runner.app/en.lproj/Documentation
                        export DONT_GENERATE_INFOPLIST_FILE\=NO
                        export DO_HEADER_SCANNING_IN_JAM\=NO
                        export DSTROOT\=/tmp/Runner.dst
                        export DT_TOOLCHAIN_DIR\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        export DWARF_DSYM_FILE_NAME\=Runner.app.dSYM
                        export DWARF_DSYM_FILE_SHOULD_ACCOMPANY_PRODUCT\=NO
                        export DWARF_DSYM_FOLDER_PATH\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export DYNAMIC_LIBRARY_EXTENSION\=dylib
                        export EFFECTIVE_PLATFORM_NAME\=-iphoneos
                        export EMBEDDED_CONTENT_CONTAINS_SWIFT\=NO
                        export EMBEDDED_PROFILE_NAME\=embedded.mobileprovision
                        export EMBED_ASSET_PACKS_IN_PRODUCT_BUNDLE\=NO
                        export ENABLE_APP_SANDBOX\=NO
                        export ENABLE_BITCODE\=NO
                        export ENABLE_DEFAULT_HEADER_SEARCH_PATHS\=YES
                        export ENABLE_DEFAULT_SEARCH_PATHS\=YES
                        export ENABLE_HARDENED_RUNTIME\=NO
                        export ENABLE_HEADER_DEPENDENCIES\=YES
                        export ENABLE_ON_DEMAND_RESOURCES\=YES
                        export ENABLE_PREVIEWS\=NO
                        export ENABLE_STRICT_OBJC_MSGSEND\=YES
                        export ENABLE_TESTABILITY\=YES
                        export ENABLE_TESTING_SEARCH_PATHS\=NO
                        export ENTITLEMENTS_ALLOWED\=YES
                        export ENTITLEMENTS_DESTINATION\=Signature
                        export ENTITLEMENTS_REQUIRED\=NO
                        export EXCLUDED_INSTALLSRC_SUBDIRECTORY_PATTERNS\=.DS_Store\ .svn\ .git\ .hg\ CVS
                        export EXCLUDED_RECURSIVE_SEARCH_PATH_SUBDIRECTORIES\=\*.nib\ \*.lproj\ \*.framework\ \*.gch\ \*.xcode\*\ \*.xcassets\ \(\*\)\ .DS_Store\ CVS\ .svn\ .git\ .hg\
                        \*.pbproj\ \*.pbxproj
                        export EXECUTABLES_FOLDER_PATH\=Runner.app/Executables
                        export EXECUTABLE_FOLDER_PATH\=Runner.app
                        export EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/MacOS
                        export EXECUTABLE_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export EXECUTABLE_NAME\=Runner
                        export EXECUTABLE_PATH\=Runner.app/Runner
                        export EXPANDED_CODE_SIGN_IDENTITY\=7954D45E9F6FC02695DCDCE42B9A9414B63635C8
                        export EXPANDED_CODE_SIGN_IDENTITY_NAME\=Apple\ Development:\ Xiangyuan\ Liu\ \(WD2Z3R3ZN4\)
                        export EXPANDED_PROVISIONING_PROFILE\=09db4648-e01d-43ad-aeee-2590c2b85f97
                        export
                        FILE_LIST\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Ob
                        jects/LinkFileList
                        export
                        FIXED_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/FixedFiles
                        export FLUTTER_APPLICATION_PATH\=/Users/sven/git_project/flat/test_ar
                        export FLUTTER_BUILD_DIR\=build
                        export FLUTTER_BUILD_NAME\=1.0.0
                        export FLUTTER_BUILD_NUMBER\=1
                        export FLUTTER_ROOT\=/Users/sven/flutterSdk/flutter
                        export FLUTTER_SUPPRESS_ANALYTICS\=true
                        export FLUTTER_TARGET\=/Users/sven/git_project/flat/test_ar/lib/main.dart
                        export FRAMEWORKS_FOLDER_PATH\=Runner.app/Frameworks
                        export FRAMEWORK_FLAG_PREFIX\=-framework
                        export FRAMEWORK_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export FRAMEWORK_VERSION\=A
                        export FULL_PRODUCT_NAME\=Runner.app
                        export GCC3_VERSION\=3.3
                        export GCC_C_LANGUAGE_STANDARD\=gnu99
                        export GCC_DYNAMIC_NO_PIC\=NO
                        export GCC_INLINES_ARE_PRIVATE_EXTERN\=YES
                        export GCC_NO_COMMON_BLOCKS\=YES
                        export GCC_OPTIMIZATION_LEVEL\=0
                        export GCC_PFE_FILE_C_DIALECTS\=c\ objective-c\ c++\ objective-c++
                        export GCC_PREPROCESSOR_DEFINITIONS\=DEBUG\=1\ 
                        export GCC_SYMBOLS_PRIVATE_EXTERN\=NO
                        export GCC_THUMB_SUPPORT\=YES
                        export GCC_TREAT_WARNINGS_AS_ERRORS\=NO
                        export GCC_VERSION\=com.apple.compilers.llvm.clang.1_0
                        export GCC_VERSION_IDENTIFIER\=com_apple_compilers_llvm_clang_1_0
                        export GCC_WARN_64_TO_32_BIT_CONVERSION\=YES
                        export GCC_WARN_ABOUT_RETURN_TYPE\=YES_ERROR
                        export GCC_WARN_UNDECLARED_SELECTOR\=YES
                        export GCC_WARN_UNINITIALIZED_AUTOS\=YES_AGGRESSIVE
                        export GCC_WARN_UNUSED_FUNCTION\=YES
                        export GCC_WARN_UNUSED_VARIABLE\=YES
                        export
                        GENERATED_MODULEMAP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/GeneratedModuleMaps-iphoneos
                        export GENERATE_INFOPLIST_FILE\=NO
                        export GENERATE_MASTER_OBJECT_FILE\=NO
                        export GENERATE_PKGINFO_FILE\=YES
                        export GENERATE_PROFILING_CODE\=NO
                        export GENERATE_TEXT_BASED_STUBS\=NO
                        export GID\=20
                        export GROUP\=staff
                        export HEADERMAP_INCLUDES_FLAT_ENTRIES_FOR_TARGET_BEING_BUILT\=YES
                        export HEADERMAP_INCLUDES_FRAMEWORK_ENTRIES_FOR_ALL_PRODUCT_TYPES\=YES
                        export HEADERMAP_INCLUDES_NONPUBLIC_NONPRIVATE_HEADERS\=YES
                        export HEADERMAP_INCLUDES_PROJECT_HEADERS\=YES
                        export HEADERMAP_USES_FRAMEWORK_PREFIX_ENTRIES\=YES
                        export HEADERMAP_USES_VFS\=NO
                        export HEADER_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/include\ 
                        export HIDE_BITCODE_SYMBOLS\=YES
                        export HOME\=/Users/sven
                        export ICONV\=/usr/bin/iconv
                        export INFOPLIST_EXPAND_BUILD_SETTINGS\=YES
                        export INFOPLIST_FILE\=Runner/Info.plist
                        export INFOPLIST_OUTPUT_FORMAT\=binary
                        export INFOPLIST_PATH\=Runner.app/Info.plist
                        export INFOPLIST_PREPROCESS\=NO
                        export INFOSTRINGS_PATH\=Runner.app/en.lproj/InfoPlist.strings
                        export INLINE_PRIVATE_FRAMEWORKS\=NO
                        export INSTALLHDRS_COPY_PHASE\=NO
                        export INSTALLHDRS_SCRIPT_PHASE\=NO
                        export INSTALL_DIR\=/tmp/Runner.dst/Applications
                        export INSTALL_GROUP\=staff
                        export INSTALL_MODE_FLAG\=u+w,go-w,a+rX
                        export INSTALL_OWNER\=sven
                        export INSTALL_PATH\=/Applications
                        export INSTALL_ROOT\=/tmp/Runner.dst
                        export IPHONEOS_DEPLOYMENT_TARGET\=9.0
                        export JAVAC_DEFAULT_FLAGS\=-J-Xms64m\ -J-XX:NewSize\=4M\ -J-Dfile.encoding\=UTF8
                        export JAVA_APP_STUB\=/System/Library/Frameworks/JavaVM.framework/Resources/MacOS/JavaApplicationStub
                        export JAVA_ARCHIVE_CLASSES\=YES
                        export JAVA_ARCHIVE_TYPE\=JAR
                        export JAVA_COMPILER\=/usr/bin/javac
                        export JAVA_FOLDER_PATH\=Runner.app/Java
                        export JAVA_FRAMEWORK_RESOURCES_DIRS\=Resources
                        export JAVA_JAR_FLAGS\=cv
                        export JAVA_SOURCE_SUBDIR\=.
                        export JAVA_USE_DEPENDENCIES\=YES
                        export JAVA_ZIP_FLAGS\=-urg
                        export JIKES_DEFAULT_FLAGS\=+E\ +OLDCSO
                        export KASAN_DEFAULT_CFLAGS\=-DKASAN\=1\ -fsanitize\=address\ -mllvm\ -asan-globals-live-support\ -mllvm\ -asan-force-dynamic-shadow
                        export KEEP_PRIVATE_EXTERNS\=NO
                        export
                        LD_DEPENDENCY_INFO_FILE\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/R
                        unner.build/Objects-normal/undefined_arch/Runner_dependency_info.dat
                        export LD_GENERATE_MAP_FILE\=NO
                        export
                        LD_MAP_FILE_PATH\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild/Runner-LinkMap-normal-undefined_arch.txt
                        export LD_NO_PIE\=NO
                        export LD_QUOTE_LINKER_ARGUMENTS_FOR_COMPILER_DRIVER\=YES
                        export LD_RUNPATH_SEARCH_PATHS\=\ @executable_path/Frameworks
                        export LEGACY_DEVELOPER_DIR\=/Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer
                        export LEX\=lex
                        export LIBRARY_DEXT_INSTALL_PATH\=/Library/DriverExtensions
                        export LIBRARY_FLAG_NOSPACE\=YES
                        export LIBRARY_FLAG_PREFIX\=-l
                        export LIBRARY_KEXT_INSTALL_PATH\=/Library/Extensions
                        export LIBRARY_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export LINKER_DISPLAYS_MANGLED_NAMES\=NO
                        export
                        LINK_FILE_LIST_normal_arm64\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphone
                        os/Runner.build/Objects-normal/arm64/Runner.LinkFileList
                        export LINK_WITH_STANDARD_LIBRARIES\=YES
                        export LLVM_TARGET_TRIPLE_OS_VERSION\=ios9.0
                        export LLVM_TARGET_TRIPLE_VENDOR\=apple
                        export LOCALIZATION_EXPORT_SUPPORTED\=YES
                        export LOCALIZED_RESOURCES_FOLDER_PATH\=Runner.app/en.lproj
                        export LOCALIZED_STRING_MACRO_NAMES\=NSLocalizedString\ CFCopyLocalizedString
                        export LOCALIZED_STRING_SWIFTUI_SUPPORT\=YES
                        export LOCAL_ADMIN_APPS_DIR\=/Applications/Utilities
                        export LOCAL_APPS_DIR\=/Applications
                        export LOCAL_DEVELOPER_DIR\=/Library/Developer
                        export LOCAL_LIBRARY_DIR\=/Library
                        export LOCROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export LOCSYMROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export MACH_O_TYPE\=mh_execute
                        export MAC_OS_X_PRODUCT_BUILD_VERSION\=21E258
                        export MAC_OS_X_VERSION_ACTUAL\=120301
                        export MAC_OS_X_VERSION_MAJOR\=120000
                        export MAC_OS_X_VERSION_MINOR\=120300
                        export METAL_LIBRARY_FILE_BASE\=default
                        export METAL_LIBRARY_OUTPUT_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app
                        export MODULES_FOLDER_PATH\=Runner.app/Modules
                        export MODULE_CACHE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/ModuleCache.noindex
                        export MTL_ENABLE_DEBUG_INFO\=YES
                        export NATIVE_ARCH\=arm64
                        export NATIVE_ARCH_32_BIT\=arm
                        export NATIVE_ARCH_64_BIT\=arm64
                        export NATIVE_ARCH_ACTUAL\=arm64
                        export NO_COMMON\=YES
                        export
                        OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/Objects
                        export
                        OBJECT_FILE_DIR_normal\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Ru
                        nner.build/Objects-normal
                        export OBJROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export ONLY_ACTIVE_ARCH\=YES
                        export OS\=MACOS
                        export OSAC\=/usr/bin/osacompile
                        export PACKAGE_CONFIG\=/Users/sven/git_project/flat/test_ar/.dart_tool/package_config.json
                        export PACKAGE_TYPE\=com.apple.package-type.wrapper.application
                        export PASCAL_STRINGS\=YES
                        export
                        PATH\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin:/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctool
                        chain/usr/local/bin:/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/libexec:/Applications/Xcode.app/Contents/Developer/Platforms/iP
                        honeOS.platform/usr/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/usr/local/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPho
                        neOS.platform/Developer/usr/bin:/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/local/bin:/Applications/Xcode.app/Contents/Develo
                        per/usr/bin:/Applications/Xcode.app/Contents/Developer/usr/local/bin:/usr/local/opt/ruby@2.7/bin:/opt/local/bin:/opt/local/sbin:/Library/Java/JavaVirtualMachines/jdk1
                        .8.0_111.jdk/Contents/Home/bin:/usr/local/opt/openssl@1.1/bin:/Users/sven/androidsdk/tools:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/opt/X11/bin:/Library/Apple/us
                        r/bin:/Users/sven/androidsdk/platform-tools:/Users/sven/flutterSdk/flutter/bin:/Users/sven/flutterSdk/flutter/bin/cache/dart-sdk/bin:/Users/sven/mygo/bin:/Users/sven/
                        flutterSdk/flutter/.pub-cache/bin:/Users/sven/.pub-cache/bin:/Users/sven/androidsdk/ndk-bundle:/opt/homebrew/bin:/Users/sven/.rvm/bin
                        export PATH_PREFIXES_EXCLUDED_FROM_HEADER_DEPENDENCIES\=/usr/include\ /usr/local/include\ /System/Library/Frameworks\ /System/Library/PrivateFrameworks\
                        /Applications/Xcode.app/Contents/Developer/Headers\ /Applications/Xcode.app/Contents/Developer/SDKs\ /Applications/Xcode.app/Contents/Developer/Platforms
                        export PBDEVELOPMENTPLIST_PATH\=Runner.app/pbdevelopment.plist
                        export
                        PER_ARCH_OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/
                        Runner.build/Objects-normal/undefined_arch
                        export
                        PER_VARIANT_OBJECT_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphone
                        os/Runner.build/Objects-normal
                        export
                        PKGINFO_FILE_PATH\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/PkgInfo
                        export PKGINFO_PATH\=Runner.app/PkgInfo
                        export PLATFORM_DEVELOPER_APPLICATIONS_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Applications
                        export PLATFORM_DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/bin
                        export PLATFORM_DEVELOPER_LIBRARY_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library
                        export PLATFORM_DEVELOPER_SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs
                        export PLATFORM_DEVELOPER_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Tools
                        export PLATFORM_DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr
                        export PLATFORM_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform
                        export PLATFORM_DISPLAY_NAME\=iOS
                        export PLATFORM_FAMILY_NAME\=iOS
                        export PLATFORM_NAME\=iphoneos
                        export PLATFORM_PREFERRED_ARCH\=arm64
                        export PLATFORM_PRODUCT_BUILD_VERSION\=19F64
                        export PLIST_FILE_OUTPUT_FORMAT\=binary
                        export PLUGINS_FOLDER_PATH\=Runner.app/PlugIns
                        export PRECOMPS_INCLUDE_HEADERS_FROM_BUILT_PRODUCTS_DIR\=YES
                        export
                        PRECOMP_DESTINATION_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/R
                        unner.build/PrefixHeaders
                        export PRESERVE_DEAD_CODE_INITS_AND_TERMS\=NO
                        export PRIVATE_HEADERS_FOLDER_PATH\=Runner.app/PrivateHeaders
                        export PRODUCT_BUNDLE_IDENTIFIER\=com.example.testar.testAr
                        export PRODUCT_BUNDLE_PACKAGE_TYPE\=APPL
                        export PRODUCT_MODULE_NAME\=Runner
                        export PRODUCT_NAME\=Runner
                        export PRODUCT_SETTINGS_PATH\=/Users/sven/git_project/flat/test_ar/ios/Runner/Info.plist
                        export PRODUCT_TYPE\=com.apple.product-type.application
                        export PROFILING_CODE\=NO
                        export PROJECT\=Runner
                        export
                        PROJECT_DERIVED_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/DerivedSources
                        export PROJECT_DIR\=/Users/sven/git_project/flat/test_ar/ios
                        export PROJECT_FILE_PATH\=/Users/sven/git_project/flat/test_ar/ios/Runner.xcodeproj
                        export PROJECT_NAME\=Runner
                        export PROJECT_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build
                        export PROJECT_TEMP_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export PROVISIONING_PROFILE_REQUIRED\=YES
                        export PUBLIC_HEADERS_FOLDER_PATH\=Runner.app/Headers
                        export RECURSIVE_SEARCH_PATHS_FOLLOW_SYMLINKS\=YES
                        export REMOVE_CVS_FROM_RESOURCES\=YES
                        export REMOVE_GIT_FROM_RESOURCES\=YES
                        export REMOVE_HEADERS_FROM_EMBEDDED_BUNDLES\=YES
                        export REMOVE_HG_FROM_RESOURCES\=YES
                        export REMOVE_SVN_FROM_RESOURCES\=YES
                        export RESOURCE_RULES_REQUIRED\=YES
                        export
                        REZ_COLLECTOR_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.
                        build/ResourceManagerResources
                        export
                        REZ_OBJECTS_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/ResourceManagerResources/Objects
                        export REZ_SEARCH_PATHS\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos\ 
                        export SCAN_ALL_SOURCE_FILES_FOR_INCLUDES\=NO
                        export SCRIPTS_FOLDER_PATH\=Runner.app/Scripts
                        export SCRIPT_INPUT_FILE_COUNT\=0
                        export SCRIPT_INPUT_FILE_LIST_COUNT\=0
                        export SCRIPT_OUTPUT_FILE_COUNT\=0
                        export SCRIPT_OUTPUT_FILE_LIST_COUNT\=0
                        export SCRIPT_OUTPUT_STREAM_FILE\=/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/pipe_to_stdout
                        export SDKROOT\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR_iphoneos\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_DIR_iphoneos15_5\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        export SDK_NAME\=iphoneos15.5
                        export SDK_NAMES\=iphoneos15.5
                        export SDK_PRODUCT_BUILD_VERSION\=19F64
                        export SDK_VERSION\=15.5
                        export SDK_VERSION_ACTUAL\=150500
                        export SDK_VERSION_MAJOR\=150000
                        export SDK_VERSION_MINOR\=150500
                        export SED\=/usr/bin/sed
                        export SEPARATE_STRIP\=NO
                        export SEPARATE_SYMBOL_EDIT\=NO
                        export SET_DIR_MODE_OWNER_GROUP\=YES
                        export SET_FILE_MODE_OWNER_GROUP\=NO
                        export SHALLOW_BUNDLE\=YES
                        export SHALLOW_BUNDLE_TRIPLE\=ios
                        export SHALLOW_BUNDLE_ios_macabi\=NO
                        export SHALLOW_BUNDLE_macos\=NO
                        export SHARED_DERIVED_FILE_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/DerivedSources
                        export SHARED_FRAMEWORKS_FOLDER_PATH\=Runner.app/SharedFrameworks
                        export SHARED_PRECOMPS_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/PrecompiledHeaders
                        export SHARED_SUPPORT_FOLDER_PATH\=Runner.app/SharedSupport
                        export SKIP_INSTALL\=NO
                        export SOURCE_ROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export SRCROOT\=/Users/sven/git_project/flat/test_ar/ios
                        export
                        STRINGSDATA_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild/Objects-normal/undefined_arch
                        export
                        STRINGSDATA_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.b
                        uild
                        export STRINGS_FILE_INFOPLIST_RENAME\=YES
                        export STRINGS_FILE_OUTPUT_ENCODING\=binary
                        export STRIP_BITCODE_FROM_COPIED_FILES\=YES
                        export STRIP_INSTALLED_PRODUCT\=NO
                        export STRIP_STYLE\=all
                        export STRIP_SWIFT_SYMBOLS\=YES
                        export SUPPORTED_DEVICE_FAMILIES\=1,2
                        export SUPPORTED_PLATFORMS\=iphoneos\ iphonesimulator
                        export SUPPORTS_MACCATALYST\=NO
                        export SUPPORTS_MAC_DESIGNED_FOR_IPHONE_IPAD\=YES
                        export SUPPORTS_TEXT_BASED_API\=NO
                        export SWIFT_EMIT_LOC_STRINGS\=NO
                        export SWIFT_OBJC_BRIDGING_HEADER\=Runner/Runner-Bridging-Header.h
                        export SWIFT_OPTIMIZATION_LEVEL\=-Onone
                        export SWIFT_PLATFORM_TARGET_PREFIX\=ios
                        export
                        SWIFT_RESPONSE_FILE_PATH_normal_arm64\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/De
                        bug-iphoneos/Runner.build/Objects-normal/arm64/Runner.SwiftFileList
                        export SWIFT_VERSION\=5.0
                        export SYMROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Products
                        export SYSTEM_ADMIN_APPS_DIR\=/Applications/Utilities
                        export SYSTEM_APPS_DIR\=/Applications
                        export SYSTEM_CORE_SERVICES_DIR\=/System/Library/CoreServices
                        export SYSTEM_DEMOS_DIR\=/Applications/Extras
                        export SYSTEM_DEVELOPER_APPS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications
                        export SYSTEM_DEVELOPER_BIN_DIR\=/Applications/Xcode.app/Contents/Developer/usr/bin
                        export SYSTEM_DEVELOPER_DEMOS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Utilities/Built\ Examples
                        export SYSTEM_DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export SYSTEM_DEVELOPER_DOC_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library
                        export SYSTEM_DEVELOPER_GRAPHICS_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Graphics\ Tools
                        export SYSTEM_DEVELOPER_JAVA_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Java\ Tools
                        export SYSTEM_DEVELOPER_PERFORMANCE_TOOLS_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Performance\ Tools
                        export SYSTEM_DEVELOPER_RELEASENOTES_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/releasenotes
                        export SYSTEM_DEVELOPER_TOOLS\=/Applications/Xcode.app/Contents/Developer/Tools
                        export SYSTEM_DEVELOPER_TOOLS_DOC_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/documentation/DeveloperTools
                        export SYSTEM_DEVELOPER_TOOLS_RELEASENOTES_DIR\=/Applications/Xcode.app/Contents/Developer/ADC\ Reference\ Library/releasenotes/DeveloperTools
                        export SYSTEM_DEVELOPER_USR_DIR\=/Applications/Xcode.app/Contents/Developer/usr
                        export SYSTEM_DEVELOPER_UTILITIES_DIR\=/Applications/Xcode.app/Contents/Developer/Applications/Utilities
                        export SYSTEM_DEXT_INSTALL_PATH\=/System/Library/DriverExtensions
                        export SYSTEM_DOCUMENTATION_DIR\=/Library/Documentation
                        export SYSTEM_EXTENSIONS_FOLDER_PATH\=Runner.app/SystemExtensions
                        export SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Library/SystemExtensions
                        export SYSTEM_EXTENSIONS_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app/SystemExtensions
                        export SYSTEM_KEXT_INSTALL_PATH\=/System/Library/Extensions
                        export SYSTEM_LIBRARY_DIR\=/System/Library
                        export TAPI_ENABLE_PROJECT_HEADERS\=NO
                        export TAPI_VERIFY_MODE\=ErrorsOnly
                        export TARGETED_DEVICE_FAMILY\=1,2
                        export TARGETNAME\=Runner
                        export TARGET_BUILD_DIR\=/Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos
                        export TARGET_DEVICE_IDENTIFIER\=00008020-000B24363C86002E
                        export TARGET_DEVICE_MODEL\=iPhone11,6
                        export TARGET_DEVICE_OS_VERSION\=15.6.1
                        export TARGET_DEVICE_PLATFORM_NAME\=iphoneos
                        export TARGET_NAME\=Runner
                        export
                        TARGET_TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bu
                        ild
                        export
                        TEMP_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build
                        export
                        TEMP_FILES_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.bui
                        ld
                        export
                        TEMP_FILE_DIR\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.buil
                        d
                        export TEMP_ROOT\=/Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex
                        export TEST_FRAMEWORK_SEARCH_PATHS\=\ /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/Frameworks\
                        /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk/Developer/Library/Frameworks
                        export TEST_LIBRARY_SEARCH_PATHS\=\ /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/usr/lib
                        export TOOLCHAINS\=com.apple.dt.toolchain.XcodeDefault
                        export TOOLCHAIN_DIR\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain
                        export TRACK_WIDGET_CREATION\=true
                        export TREAT_MISSING_BASELINES_AS_TEST_FAILURES\=NO
                        export TREE_SHAKE_ICONS\=false
                        export TeamIdentifierPrefix\=G7N8SR355W.
                        export UID\=502
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH\=Runner.app
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_NO\=Runner.app/Resources
                        export UNLOCALIZED_RESOURCES_FOLDER_PATH_SHALLOW_BUNDLE_YES\=Runner.app
                        export UNSTRIPPED_PRODUCT\=NO
                        export USER\=sven
                        export USER_APPS_DIR\=/Users/sven/Applications
                        export USER_LIBRARY_DIR\=/Users/sven/Library
                        export USE_DYNAMIC_NO_PIC\=YES
                        export USE_HEADERMAP\=YES
                        export USE_HEADER_SYMLINKS\=NO
                        export USE_LLVM_TARGET_TRIPLES\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_CLANG\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_LD\=YES
                        export USE_LLVM_TARGET_TRIPLES_FOR_TAPI\=YES
                        export VALIDATE_DEVELOPMENT_ASSET_PATHS\=YES_ERROR
                        export VALIDATE_PRODUCT\=NO
                        export VALIDATE_WORKSPACE\=YES_ERROR
                        export VALID_ARCHS\=arm64\ arm64e\ armv7\ armv7s
                        export VERBOSE_PBXCP\=NO
                        export VERBOSE_SCRIPT_LOGGING\=YES
                        export VERSIONING_SYSTEM\=apple-generic
                        export VERSIONPLIST_PATH\=Runner.app/version.plist
                        export VERSION_INFO_BUILDER\=sven
                        export VERSION_INFO_FILE\=Runner_vers.c
                        export VERSION_INFO_STRING\=\"@\(\#\)PROGRAM:Runner\ \ PROJECT:Runner-1\"
                        export WRAPPER_EXTENSION\=app
                        export WRAPPER_NAME\=Runner.app
                        export WRAPPER_SUFFIX\=.app
                        export WRAP_ASSET_PACKS_IN_SEPARATE_DIRECTORIES\=NO
                        export XCODE_APP_SUPPORT_DIR\=/Applications/Xcode.app/Contents/Developer/Library/Xcode
                        export XCODE_PRODUCT_BUILD_VERSION\=13F17a
                        export XCODE_VERSION_ACTUAL\=1340
                        export XCODE_VERSION_MAJOR\=1300
                        export XCODE_VERSION_MINOR\=1340
                        export XPCSERVICES_FOLDER_PATH\=Runner.app/XPCServices
                        export YACC\=yacc
                        export _WRAPPER_CONTENTS_DIR_SHALLOW_BUNDLE_NO\=/Contents
                        export _WRAPPER_PARENT_PATH_SHALLOW_BUNDLE_NO\=/..
                        export _WRAPPER_RESOURCES_DIR_SHALLOW_BUNDLE_NO\=/Resources
                        export __CODE_SIGNING_ALLOWED_appletvos\=NO
                        export __CODE_SIGNING_ALLOWED_iphoneos\=NO
                        export __CODE_SIGNING_ALLOWED_watchos\=NO
                        export arch\=undefined_arch
                        export variant\=normal
                        /bin/sh -c
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Script-3B06AD
                        1E1E4923F5004D2608.sh

                    CopySwiftLibs /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export CODESIGN_ALLOCATE\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/codesign_allocate
                        export DEVELOPER_DIR\=/Applications/Xcode.app/Contents/Developer
                        export SDKROOT\=/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS15.5.sdk
                        builtin-swiftStdLibTool --copy --verbose --sign 7954D45E9F6FC02695DCDCE42B9A9414B63635C8 --scan-executable
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Runner --scan-folder
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Frameworks --scan-folder
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/PlugIns --scan-folder
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/SystemExtensions --platform iphoneos --toolchain
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain --destination
                        /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app/Frameworks --strip-bitcode --strip-bitcode-tool
                        /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/bitcode_strip --emit-dependency-info
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/SwiftStdLibTo
                        olInputDependencies.dep --filter-for-swift-os

                    CodeSign /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        export CODESIGN_ALLOCATE\=/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/codesign_allocate

                        Signing Identity:     "Apple Development: Xiangyuan Liu (WD2Z3R3ZN4)"
                        Provisioning Profile: "iOS Team Provisioning Profile: *"
                                              (09db4648-e01d-43ad-aeee-2590c2b85f97)

                        /usr/bin/codesign --force --sign 7954D45E9F6FC02695DCDCE42B9A9414B63635C8 --entitlements
                        /Users/sven/Library/Developer/Xcode/DerivedData/Runner-gulxhpndzmrxsrgcboycqqtyupxz/Build/Intermediates.noindex/Runner.build/Debug-iphoneos/Runner.build/Runner.app.xc
                        ent --timestamp\=none --generate-entitlement-der /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app

                    Validate /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app (in target 'Runner' from project 'Runner')
                        cd /Users/sven/git_project/flat/test_ar/ios
                        builtin-validationUtility /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app


                    Result bundle written to path:
                    	/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle

                    ** BUILD SUCCEEDED **


                    2022-09-01 13:39:00.531 xcodebuild[42679:363651] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionSentinelHostApplications for extension
                    Xcode.DebuggerFoundation.AppExtensionHosts.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:39:00.531 xcodebuild[42679:363651] Requested but did not find extension point with identifier Xcode.IDEKit.ExtensionPointIdentifierToBundleIdentifier for
                    extension Xcode.DebuggerFoundation.AppExtensionToBundleIdentifierMap.watchOS of plug-in com.apple.dt.IDEWatchSupportCore
                    2022-09-01 13:39:00.586 xcodebuild[42679:363651] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/CocoaPods.xcplugin' not present in DVTPlugInCompatibilityUUIDs
                    2022-09-01 13:39:00.586 xcodebuild[42679:363651] [MT] PluginLoading: Required plug-in compatibility UUID EFD92DF8-D0A2-4C92-B6E3-9B3CD7E8DC19 for plug-in at path
                    '~/Library/Application Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin' not present in DVTPlugInCompatibilityUUIDs
[  +29 ms]  └─Compiling, linking and signing... (completed in 2,387ms)
[        ] Xcode build done.                                            7.8s
[        ] executing: /usr/bin/arch -arm64e xcrun xcresulttool get --path
/var/folders/7j/qhzt2g1s3gj3145mgm4hdrlr0000gp/T/flutter_tools.uSj3AJ/flutter_ios_build_temp_dirglw5Bq/temporary_xcresult_bundle --format json
[  +21 ms] {
             "_type" : {
               "_name" : "ActionsInvocationRecord"
             },
             "actions" : {
               "_type" : {
                 "_name" : "Array"
               },
               "_values" : [
                 {
                   "_type" : {
                     "_name" : "ActionRecord"
                   },
                   "actionResult" : {
                     "_type" : {
                       "_name" : "ActionResult"
                     },
                     "coverage" : {
                       "_type" : {
                         "_name" : "CodeCoverageInfo"
                       }
                     },
                     "issues" : {
                       "_type" : {
                         "_name" : "ResultIssueSummaries"
                       }
                     },
                     "metrics" : {
                       "_type" : {
                         "_name" : "ResultMetrics"
                       }
                     },
                     "resultName" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "action"
                     },
                     "status" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "notRequested"
                     }
                   },
                   "buildResult" : {
                     "_type" : {
                       "_name" : "ActionResult"
                     },
                     "coverage" : {
                       "_type" : {
                         "_name" : "CodeCoverageInfo"
                       }
                     },
                     "issues" : {
                       "_type" : {
                         "_name" : "ResultIssueSummaries"
                       }
                     },
                     "logRef" : {
                       "_type" : {
                         "_name" : "Reference"
                       },
                       "id" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "0~IDYOl1GKnDIQPnYoMGgnWFbq3xXpUV2ihaUBJUdvX56RaYVMzWOnynx5QNDGxBpykuBzYl5qsERbJmr734b1GA=="
                       },
                       "targetType" : {
                         "_type" : {
                           "_name" : "TypeDefinition"
                         },
                         "name" : {
                           "_type" : {
                             "_name" : "String"
                           },
                           "_value" : "ActivityLogSection"
                         }
                       }
                     },
                     "metrics" : {
                       "_type" : {
                         "_name" : "ResultMetrics"
                       }
                     },
                     "resultName" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "build"
                     },
                     "status" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "succeeded"
                     }
                   },
                   "endedTime" : {
                     "_type" : {
                       "_name" : "Date"
                     },
                     "_value" : "2022-09-01T13:39:08.090+0800"
                   },
                   "runDestination" : {
                     "_type" : {
                       "_name" : "ActionRunDestinationRecord"
                     },
                     "displayName" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "AlomateiPhone"
                     },
                     "localComputerRecord" : {
                       "_type" : {
                         "_name" : "ActionDeviceRecord"
                       },
                       "busSpeedInMHz" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "cpuCount" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "1"
                       },
                       "cpuKind" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "Apple M1"
                       },
                       "cpuSpeedInMHz" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "identifier" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "00008103-000949AC0E8A001E"
                       },
                       "isConcreteDevice" : {
                         "_type" : {
                           "_name" : "Bool"
                         },
                         "_value" : "true"
                       },
                       "logicalCPUCoresPerPackage" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "8"
                       },
                       "modelCode" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "MacBookPro17,1"
                       },
                       "modelName" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "MacBook Pro"
                       },
                       "modelUTI" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "com.apple.macbookpro-13-retina-touchid-late-2020"
                       },
                       "name" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "My Mac"
                       },
                       "nativeArchitecture" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "arm64e"
                       },
                       "operatingSystemVersion" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "12.3.1"
                       },
                       "operatingSystemVersionWithBuildNumber" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "12.3.1 (21E258)"
                       },
                       "physicalCPUCoresPerPackage" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "8"
                       },
                       "platformRecord" : {
                         "_type" : {
                           "_name" : "ActionPlatformRecord"
                         },
                         "identifier" : {
                           "_type" : {
                             "_name" : "String"
                           },
                           "_value" : "com.apple.platform.macosx"
                         },
                         "userDescription" : {
                           "_type" : {
                             "_name" : "String"
                           },
                           "_value" : "macOS"
                         }
                       },
                       "ramSizeInMegabytes" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "16384"
                       }
                     },
                     "targetArchitecture" : {
                       "_type" : {
                         "_name" : "String"
                       },
                       "_value" : "arm64"
                     },
                     "targetDeviceRecord" : {
                       "_type" : {
                         "_name" : "ActionDeviceRecord"
                       },
                       "busSpeedInMHz" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "cpuCount" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "cpuSpeedInMHz" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "identifier" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "00008020-000B24363C86002E"
                       },
                       "isConcreteDevice" : {
                         "_type" : {
                           "_name" : "Bool"
                         },
                         "_value" : "true"
                       },
                       "logicalCPUCoresPerPackage" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "modelCode" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "iPhone11,6"
                       },
                       "modelName" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "iPhone XS Max"
                       },
                       "modelUTI" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "com.apple.iphone-xs-max-1"
                       },
                       "name" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "AlomateiPhone"
                       },
                       "nativeArchitecture" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "arm64e"
                       },
                       "operatingSystemVersion" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "15.6.1"
                       },
                       "operatingSystemVersionWithBuildNumber" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "15.6.1 (19G82)"
                       },
                       "physicalCPUCoresPerPackage" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       },
                       "platformRecord" : {
                         "_type" : {
                           "_name" : "ActionPlatformRecord"
                         },
                         "identifier" : {
                           "_type" : {
                             "_name" : "String"
                           },
                           "_value" : "com.apple.platform.iphoneos"
                         },
                         "userDescription" : {
                           "_type" : {
                             "_name" : "String"
                           },
                           "_value" : "iOS"
                         }
                       },
                       "ramSizeInMegabytes" : {
                         "_type" : {
                           "_name" : "Int"
                         },
                         "_value" : "0"
                       }
                     },
                     "targetSDKRecord" : {
                       "_type" : {
                         "_name" : "ActionSDKRecord"
                       },
                       "identifier" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "iphoneos15.5"
                       },
                       "name" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "iOS 15.5"
                       },
                       "operatingSystemVersion" : {
                         "_type" : {
                           "_name" : "String"
                         },
                         "_value" : "15.5"
                       }
                     }
                   },
                   "schemeCommandName" : {
                     "_type" : {
                       "_name" : "String"
                     },
                     "_value" : "Run"
                   },
                   "schemeTaskName" : {
                     "_type" : {
                       "_name" : "String"
                     },
                     "_value" : "Build"
                   },
                   "startedTime" : {
                     "_type" : {
                       "_name" : "Date"
                     },
                     "_value" : "2022-09-01T13:39:02.327+0800"
                   },
                   "title" : {
                     "_type" : {
                       "_name" : "String"
                     },
                     "_value" : "Build \"Runner\""
                   }
                 }
               ]
             },
             "issues" : {
               "_type" : {
                 "_name" : "ResultIssueSummaries"
               }
             },
             "metadataRef" : {
               "_type" : {
                 "_name" : "Reference"
               },
               "id" : {
                 "_type" : {
                   "_name" : "String"
                 },
                 "_value" : "0~1Mu4LXpe-VU4hhWK7e80d4BlojHisyrCJ7EgXxlu-zHOF5wi5dEddsJJSzcpaY8Yr6EO511xmxDA0Zz8tEarwA=="
               },
               "targetType" : {
                 "_type" : {
                   "_name" : "TypeDefinition"
                 },
                 "name" : {
                   "_type" : {
                     "_name" : "String"
                   },
                   "_value" : "ActionsInvocationMetadata"
                 }
               }
             },
             "metrics" : {
               "_type" : {
                 "_name" : "ResultMetrics"
               }
             }
           }
[   +3 ms] executing: rsync -8 -av --delete /Users/sven/git_project/flat/test_ar/build/ios/Debug-iphoneos/Runner.app /Users/sven/git_project/flat/test_ar/build/ios/iphoneos
[  +41 ms] building file list ... done
           Runner.app/
           Runner.app/Info.plist
           Runner.app/PkgInfo
           Runner.app/Runner
           Runner.app/_CodeSignature/CodeResources

           sent 126840 bytes  received 114 bytes  253908.00 bytes/sec
           total size is 86139610  speedup is 678.51
[   +1 ms] Installing and launching...
[        ] Debugging is enabled, connecting to observatory
[   +2 ms] executing: script -t 0 /dev/null /Users/sven/flutterSdk/flutter/bin/cache/artifacts/ios-deploy/ios-deploy --id 00008020-000B24363C86002E --bundle build/ios/iphoneos/Runner.app
--app_deltas build/ios/app-delta --debug --no-wifi --args --enable-dart-profiling --disable-service-auth-codes --enable-checked-mode --verify-entry-points
[  +27 ms] [....] Waiting for iOS device to be connected
[ +181 ms] [....] Using 00008020-000B24363C86002E (D331pAP, iPhone XS Max, iphoneos, arm64e, 15.6.1, 19G82) a.k.a. 'AlomateiPhone'.
[        ] ------ Install phase ------
[        ] [  0%] Found 00008020-000B24363C86002E (D331pAP, iPhone XS Max, iphoneos, arm64e, 15.6.1, 19G82) a.k.a. 'AlomateiPhone' connected through USB, beginning install
[ +177 ms] [  5%] TransferringPackage
[        ] [  5%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/META-INF/ to device
[        ] [  7%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/META-INF/ to device
[        ] [  7%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/META-INF/com.apple.ZipMetadata.plist to device
[        ] [  9%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/META-INF/com.apple.ZipMetadata.plist to device
[        ] [  9%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/com.apple.deltainstallcommands.com.example.testar.testAr to device
[        ] [ 11%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/com.apple.deltainstallcommands.com.example.testar.testAr to device
[        ] [ 11%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/ to device
[        ] [ 13%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/ to device
[        ] [ 13%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/ to device
[        ] [ 15%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/ to device
[        ] [ 15%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/_CodeSignature/ to device
[        ] [ 17%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/_CodeSignature/ to device
[        ] [ 17%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/_CodeSignature/CodeResources to device
[        ] [ 21%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/_CodeSignature/CodeResources to device
[        ] [ 23%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/_CodeSignature/CodeResources to device
[        ] [ 23%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/Info.plist to device
[        ] [ 25%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/Info.plist to device
[        ] [ 25%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/Runner to device
[        ] [ 42%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/Runner to device
[        ] [ 44%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/Runner to device
[        ] [ 44%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/PkgInfo to device
[        ] [ 46%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/Payload/Runner.app/PkgInfo to device
[        ] [ 46%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/ManifestCache.plist to device
[        ] [ 48%] Copying /Users/sven/git_project/flat/test_ar/build/ios/app-delta/Runner.app.1aikVk/Runner.app_sparse.ipa/ManifestCache.plist to device
[ +136 ms] [ 52%] CreatingStagingDirectory
[   +1 ms] [ 57%] ExtractingPackage
[        ] [ 60%] InspectingPackage
[ +144 ms] [ 60%] TakingInstallLock
[ +378 ms] [ 65%] PreflightingApplication
[        ] [ 67%] PatchingApplication
[ +906 ms] [ 67%] InstallingEmbeddedProfile
[  +65 ms] [ 70%] VerifyingApplication
[+1861 ms] [ 75%] CreatingContainer
[  +15 ms] [ 80%] InstallingApplication
[  +38 ms] [ 85%] PostflightingApplication
[   +3 ms] [ 90%] SandboxingApplication
[  +43 ms] [ 95%] GeneratingApplicationMap
[ +777 ms] [100%] Installed package build/ios/iphoneos/Runner.app
[  +89 ms] ------ Debug phase ------
[        ] Starting debug of 00008020-000B24363C86002E (D331pAP, iPhone XS Max, iphoneos, arm64e, 15.6.1, 19G82) a.k.a. 'AlomateiPhone' connected through USB...
[ +769 ms] [  0%] Looking up developer disk image
[  +24 ms] [ 95%] Developer disk image mounted successfully
[  +60 ms] Symbol Path: /Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols
[ +398 ms] [100%] Connecting to remote debug server
[        ] -------------------------
[ +148 ms] (lldb) command source -s 0 '/tmp/AB783B4C-5E2E-4100-8FD6-9B31ED67DF19/fruitstrap-lldb-prep-cmds-00008020_000B24363C86002E'
[   +2 ms] Executing commands in '/tmp/AB783B4C-5E2E-4100-8FD6-9B31ED67DF19/fruitstrap-lldb-prep-cmds-00008020_000B24363C86002E'.
[        ] (lldb)     platform select remote-'ios' --sysroot '/Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols'
[        ]   Platform: remote-ios
[        ]  Connected: no
[        ]   SDK Path: "/Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols"
[        ] (lldb)     target create "/Users/sven/git_project/flat/test_ar/build/ios/iphoneos/Runner.app"
[+3355 ms] Current executable set to '/Users/sven/git_project/flat/test_ar/build/ios/iphoneos/Runner.app' (arm64).
[        ] (lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/82F1181D-418E-491E-B4E8-EA0BA500690C/Runner.app"
[ +206 ms] (lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62406"
[        ] (lldb)     script fruitstrap_output_path=""
[        ] (lldb)     script fruitstrap_error_path=""
[        ] (lldb)     target modules search-paths add /usr "/Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols/usr" /System
"/Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols/System" "/private/var/containers/Bundle/Application/82F1181D-418E-491E-B4E8-EA0BA500690C"
"/Users/sven/git_project/flat/test_ar/build/ios/iphoneos" "/var/containers/Bundle/Application/82F1181D-418E-491E-B4E8-EA0BA500690C" "/Users/sven/git_project/flat/test_ar/build/ios/iphoneos"
/Developer "/Users/sven/Library/Developer/Xcode/iOS DeviceSupport/15.6.1 (19G82) arm64e/Symbols/Developer"
[   +7 ms] (lldb)     command script import "/tmp/AB783B4C-5E2E-4100-8FD6-9B31ED67DF19/fruitstrap_00008020_000B24363C86002E.py"
[   +3 ms] (lldb)     command script add -f fruitstrap_00008020_000B24363C86002E.connect_command connect
[        ] (lldb)     command script add -s asynchronous -f fruitstrap_00008020_000B24363C86002E.run_command run
[        ] (lldb)     command script add -s asynchronous -f fruitstrap_00008020_000B24363C86002E.autoexit_command autoexit
[        ] (lldb)     command script add -s asynchronous -f fruitstrap_00008020_000B24363C86002E.safequit_command safequit
[        ] (lldb)     connect
[  +48 ms] (lldb)     run
[ +218 ms] success
[        ] Application launched on the device. Waiting for observatory url.
[+2655 ms] Observatory URL on device: http://127.0.0.1:50389/
[   +8 ms] Attempting to forward device port 50389 to host port 62419
[        ] executing: /Users/sven/flutterSdk/flutter/bin/cache/artifacts/usbmuxd/iproxy 62419:50389 --udid 00008020-000B24363C86002E --debug
[+1009 ms] Forwarded port ForwardedPort HOST:62419 to DEVICE:50389
[        ] Forwarded host port 62419 to device port 50389 for Observatory
[   +2 ms] Installing and launching... (completed in 13.8s)
[   +2 ms] Caching compiled dill
[ +141 ms] Connecting to service protocol: http://127.0.0.1:62419/
[   +7 ms] Process 418 stopped
[        ] * thread #8, name = 'io.flutter.1.ui', stop reason = EXC_BAD_ACCESS (code=1, address=0x1270b4dc8)
[        ]     frame #0: 0x00000001035250e0 Flutter`skia::textlayout::TextLine::measureTextInsideOneRun(skia::textlayout::SkRange<unsigned long>, skia::textlayout::Run const*, float, float,
bool, bool) const + 980
[        ] Flutter`skia::textlayout::TextLine::measureTextInsideOneRun:
[        ] ->  0x1035250e0 <+980>: ldr    s11, [x8, x9]
[        ]     0x1035250e4 <+984>: ldp    s0, s1, [x21, #0xa0]
[        ]     0x1035250e8 <+988>: ldrb   w8, [x21, #0xdb]
[        ]     0x1035250ec <+992>: cmp    w8, #0x0
[        ] Target 0: (Runner) stopped.
[   +1 ms] thread backtrace all
[        ] process detach
[ +775 ms]   thread #1, queue = 'com.apple.main-thread'
[        ]     frame #0: 0x00000001cc4664a0 libsystem_kernel.dylib`mach_msg_trap + 8
[        ]     frame #1: 0x00000001cc466ae4 libsystem_kernel.dylib`mach_msg + 76
[        ]     frame #2: 0x0000000194936d30 CoreFoundation`__CFRunLoopServiceMachPort + 372
[        ]     frame #3: 0x000000019493b1bc CoreFoundation`__CFRunLoopRun + 1180
[        ]     frame #4: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #5: 0x00000001b0aba374 GraphicsServices`GSEventRunModal + 164
[        ]     frame #6: 0x00000001972c2b58 UIKitCore`-[UIApplication _run] + 1100
[        ]     frame #7: 0x0000000197044090 UIKitCore`UIApplicationMain + 364
[        ]     frame #8: 0x000000010082dcf4 Runner`main at AppDelegate.swift:5:13
[        ]     frame #9: 0x0000000100a41da4 dyld`start + 520
[        ]   thread #2
[        ]     frame #0: 0x00000001cc466a74 libsystem_kernel.dylib`__workq_kernreturn + 8
[        ]   thread #3
[        ]     frame #0: 0x00000001cc466a74 libsystem_kernel.dylib`__workq_kernreturn + 8
[        ]   thread #4
[        ]     frame #0: 0x00000001cc466a74 libsystem_kernel.dylib`__workq_kernreturn + 8
[        ]   thread #5, name = 'com.apple.uikit.eventfetch-thread'
[        ]     frame #0: 0x00000001cc4664a0 libsystem_kernel.dylib`mach_msg_trap + 8
[        ]     frame #1: 0x00000001cc466ae4 libsystem_kernel.dylib`mach_msg + 76
[        ]     frame #2: 0x0000000194936d30 CoreFoundation`__CFRunLoopServiceMachPort + 372
[        ]     frame #3: 0x000000019493b1bc CoreFoundation`__CFRunLoopRun + 1180
[        ]     frame #4: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #5: 0x0000000196141444 Foundation`-[NSRunLoop(NSRunLoop) runMode:beforeDate:] + 236
[        ]     frame #6: 0x0000000196182e0c Foundation`-[NSRunLoop(NSRunLoop) runUntilDate:] + 92
[        ]     frame #7: 0x000000019723ccc4 UIKitCore`-[UIEventFetcher threadMain] + 524
[        ]     frame #8: 0x000000019619141c Foundation`__NSThread__start__ + 808
[        ]     frame #9: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #6
[        ]     frame #0: 0x00000001cc466a74 libsystem_kernel.dylib`__workq_kernreturn + 8
[        ]   thread #7
[        ]     frame #0: 0x00000001cc466a74 libsystem_kernel.dylib`__workq_kernreturn + 8
[        ] * thread #8, name = 'io.flutter.1.ui', stop reason = EXC_BAD_ACCESS (code=1, address=0x1270b4dc8)
[        ]   * frame #0: 0x00000001035250e0 Flutter`skia::textlayout::TextLine::measureTextInsideOneRun(skia::textlayout::SkRange<unsigned long>, skia::textlayout::Run const*, float, float,
bool, bool) const + 980
[        ]     frame #1: 0x0000000103524ab8 Flutter`skia::textlayout::TextLine::iterateThroughSingleRunByStyles(skia::textlayout::Run const*, float, skia::textlayout::SkRange<unsigned long>,
skia::textlayout::StyleType, std::__1::function<void (skia::textlayout::SkRange<unsigned long>, skia::textlayout::TextStyle const&, skia::textlayout::TextLine::ClipContext const&)> const&)
const + 380
[        ]     frame #2: 0x0000000103525cf4 Flutter`std::__1::__function::__func<skia::textlayout::TextLine::ensureTextBlobCachePopulated()::$_3,
std::__1::allocator<skia::textlayout::TextLine::ensureTextBlobCachePopulated()::$_3>, bool (skia::textlayout::Run const*, float, skia::textlayout::SkRange<unsigned long>,
float*)>::operator()(skia::textlayout::Run const*&&, float&&, skia::textlayout::SkRange<unsigned long>&&, float*&&) + 116
[        ]     frame #3: 0x0000000103526808 Flutter`std::__1::function<bool (skia::textlayout::Run const*, float, skia::textlayout::SkRange<unsigned long>,
float*)>::operator()(skia::textlayout::Run const*, float, skia::textlayout::SkRange<unsigned long>, float*) const + 60
[        ]     frame #4: 0x0000000103524664 Flutter`skia::textlayout::TextLine::iterateThroughVisualRuns(bool, std::__1::function<bool (skia::textlayout::Run const*, float,
skia::textlayout::SkRange<unsigned long>, float*)> const&) const + 500
[        ]     frame #5: 0x000000010352478c Flutter`skia::textlayout::TextLine::ensureTextBlobCachePopulated() + 76
[        ]     frame #6: 0x000000010352105c Flutter`skia::textlayout::ParagraphImpl::paint(SkCanvas*, float, float) + 372
[        ]     frame #7: 0x0000000103576a7c Flutter`flutter::Paragraph_paint(_Dart_NativeArguments*) + 192
[        ]     frame #8: 0x00000001036c6844 Flutter`dart::NativeEntry::AutoScopeNativeCallWrapperNoStackCheck(_Dart_NativeArguments*, void (*)(_Dart_NativeArguments*)) + 308
[        ]     frame #9: 0x000000010a682cd0
[        ]     frame #10: 0x0000000113cfa724
[        ]     frame #11: 0x0000000113cfa210
[        ]     frame #12: 0x0000000113cf9f54
[        ]     frame #13: 0x0000000113cf8b80
[        ]     frame #14: 0x0000000113cd8cc4
[        ]     frame #15: 0x0000000113cda7bc
[        ]     frame #16: 0x0000000113cf8568
[        ]     frame #17: 0x0000000113cf7af0
[        ]     frame #18: 0x0000000113cd8cc4
[        ]     frame #19: 0x0000000113cda7bc
[        ]     frame #20: 0x0000000113cf781c
[        ]     frame #21: 0x0000000113cd8cc4
[        ]     frame #22: 0x0000000113cda7bc
[        ]     frame #23: 0x0000000113cf7538
[        ]     frame #24: 0x0000000113cf72d8
[        ]     frame #25: 0x0000000113cd8cc4
[        ]     frame #26: 0x0000000113cda7bc
[        ]     frame #27: 0x0000000113cdaba8
[        ]     frame #28: 0x0000000113cf709c
[        ]     frame #29: 0x0000000113cd8cc4
[        ]     frame #30: 0x0000000113cda7bc
[        ]     frame #31: 0x0000000113cdaba8
[        ]     frame #32: 0x0000000113cf6c30
[        ]     frame #33: 0x0000000113cf6428
[        ]     frame #34: 0x0000000113cebf5c
[        ]     frame #35: 0x0000000113cd8cc4
[        ]     frame #36: 0x0000000113cda7bc
[        ]     frame #37: 0x0000000113cdaba8
[        ]     frame #38: 0x0000000113cd8cc4
[        ]     frame #39: 0x0000000113cda7bc
[        ]     frame #40: 0x0000000113cdaba8
[        ]     frame #41: 0x0000000113cd8cc4
[        ]     frame #42: 0x0000000113cd654c
[        ]     frame #43: 0x0000000113cd56a4
[        ]     frame #44: 0x0000000113cdda58
[        ]     frame #45: 0x0000000113cda778
[        ]     frame #46: 0x0000000113cdaba8
[        ]     frame #47: 0x0000000113cd8cc4
[        ]     frame #48: 0x0000000113cda7bc
[        ]     frame #49: 0x0000000113cea7b8
[        ]     frame #50: 0x0000000113cea558
[        ]     frame #51: 0x0000000113cea174
[        ]     frame #52: 0x0000000113cd8cc4
[        ]     frame #53: 0x0000000113cda7bc
[        ]     frame #54: 0x0000000113cdaba8
[        ]     frame #55: 0x0000000113cdfa1c
[        ]     frame #56: 0x0000000113cd8cc4
[        ]     frame #57: 0x0000000113cda7bc
[        ]     frame #58: 0x0000000113cdaba8
[        ]     frame #59: 0x0000000113cdedf4
[        ]     frame #60: 0x0000000113cd8cc4
[        ]     frame #61: 0x0000000113cda7bc
[        ]     frame #62: 0x0000000113cdaba8
[        ]     frame #63: 0x0000000113cdedf4
[        ]     frame #64: 0x0000000113cd8cc4
[        ]     frame #65: 0x0000000113cda7bc
[        ]     frame #66: 0x0000000113cdaba8
[        ]     frame #67: 0x0000000113cd8cc4
[        ]     frame #68: 0x0000000113cd654c
[        ]     frame #69: 0x0000000113cd56a4
[        ]     frame #70: 0x0000000113cdda58
[        ]     frame #71: 0x0000000113cda778
[        ]     frame #72: 0x0000000113cdaba8
[        ]     frame #73: 0x0000000113cd8cc4
[        ]     frame #74: 0x0000000113cda7bc
[        ]     frame #75: 0x0000000113cdaba8
[        ]     frame #76: 0x0000000113cd8cc4
[        ]     frame #77: 0x0000000113cda7bc
[        ]     frame #78: 0x0000000113cdaba8
[        ]     frame #79: 0x0000000113cdc32c
[        ]     frame #80: 0x0000000113cd8cc4
[        ]     frame #81: 0x0000000113cda7bc
[        ]     frame #82: 0x0000000113cdaba8
[        ]     frame #83: 0x0000000113cd8cc4
[        ]     frame #84: 0x0000000113cda7bc
[        ]     frame #85: 0x0000000113cdb6f8
[        ]     frame #86: 0x0000000113cdb2e4
[        ]     frame #87: 0x0000000113cd8cc4
[        ]     frame #88: 0x0000000113cda7bc
[        ]     frame #89: 0x0000000113cdaba8
[        ]     frame #90: 0x0000000113cd8cc4
[        ]     frame #91: 0x0000000113cda7bc
[        ]     frame #92: 0x0000000113cdaba8
[        ]     frame #93: 0x0000000113cd8cc4
[        ]     frame #94: 0x0000000113cda7bc
[        ]     frame #95: 0x0000000113cdaba8
[        ]     frame #96: 0x0000000113cd8cc4
[        ]     frame #97: 0x0000000113cda7bc
[        ]     frame #98: 0x0000000113cdaba8
[        ]     frame #99: 0x0000000113cdae0c
[        ]     frame #100: 0x0000000113cd8cc4
[        ]     frame #101: 0x0000000113cda7bc
[        ]     frame #102: 0x0000000113cdaba8
[        ]     frame #103: 0x0000000113cd8cc4
[        ]     frame #104: 0x0000000113cda7bc
[        ]     frame #105: 0x0000000113cdaba8
[        ]     frame #106: 0x0000000113cd8cc4
[        ]     frame #107: 0x0000000113cda7bc
[        ]     frame #108: 0x0000000113cdaba8
[        ]     frame #109: 0x0000000113cd8cc4
[        ]     frame #110: 0x0000000113cda7bc
[        ]     frame #111: 0x0000000113cdaba8
[        ]     frame #112: 0x0000000113cd8cc4
[        ]     frame #113: 0x0000000113cda7bc
[        ]     frame #114: 0x0000000113cda418
[        ]     frame #115: 0x0000000113cd8cc4
[        ]     frame #116: 0x0000000113cd654c
[        ]     frame #117: 0x0000000113cd56a4
[        ]     frame #118: 0x0000000113cd4538
[        ]     frame #119: 0x0000000113c8550c
[        ]     frame #120: 0x00000001139f201c
[        ]     frame #121: 0x00000001139f1908
[        ]     frame #122: 0x00000001139f1808
[        ]     frame #123: 0x00000001139f11f4
[        ]     frame #124: 0x00000001139efca4
[        ]     frame #125: 0x00000001139ef720
[        ]     frame #126: 0x000000010ddbf0d4
[        ]     frame #127: 0x000000010ddbeee4
[        ]     frame #128: 0x000000010ddbe5fc
[        ]     frame #129: 0x0000000112893bb4
[        ]     frame #130: 0x0000000112893a64
[        ]     frame #131: 0x000000010ddbf26c
[        ]     frame #132: 0x000000010ddbeee4
[        ]     frame #133: 0x000000010ddbe5fc
[        ]     frame #134: 0x00000001128a38dc
[        ]     frame #135: 0x00000001128a379c
[        ]     frame #136: 0x00000001128a2b50
[        ]     frame #137: 0x00000001128a0b48
[        ]     frame #138: 0x00000001128a0814
[        ]     frame #139: 0x000000010ddb38fc
[        ]     frame #140: 0x000000010ddb2dc8
[        ]     frame #141: 0x000000010a682fc8
[        ]     frame #142: 0x00000001036537c0 Flutter`dart::DartEntry::InvokeFunction(dart::Function const&, dart::Array const&, dart::Array const&, unsigned long) + 676
[        ]     frame #143: 0x0000000103672050 Flutter`dart::IsolateMessageHandler::HandleMessage(std::__1::unique_ptr<dart::Message, std::__1::default_delete<dart::Message> >) + 3072
[        ]     frame #144: 0x00000001036aec98 Flutter`dart::MessageHandler::HandleMessages(dart::MonitorLocker*, bool, bool) + 580
[        ]     frame #145: 0x00000001039feca4 Flutter`Dart_HandleMessage + 300
[        ]     frame #146: 0x0000000103498df4 Flutter`std::__1::__function::__func<tonic::DartMessageHandler::OnMessage(tonic::DartState*)::$_0,
std::__1::allocator<tonic::DartMessageHandler::OnMessage(tonic::DartState*)::$_0>, void ()>::operator()() + 344
[        ]     frame #147: 0x00000001035e3490
Flutter`std::__1::__function::__func<flutter::DartIsolate::SetMessageHandlingTaskRunner(fml::RefPtr<fml::TaskRunner>)::$_3::operator()(std::__1::function<void ()>) const::'lambda'(),
std::__1::allocator<flutter::DartIsolate::SetMessageHandlingTaskRunner(fml::RefPtr<fml::TaskRunner>)::$_3::operator()(std::__1::function<void ()>) const::'lambda'()>, void ()>::operator()()
+ 48
[        ]     frame #148: 0x000000010339a174 Flutter`fml::MessageLoopImpl::FlushTasks(fml::FlushType) + 1592
[        ]     frame #149: 0x000000010339dc8c Flutter`fml::MessageLoopDarwin::OnTimerFire(__CFRunLoopTimer*, fml::MessageLoopDarwin*) + 32
[        ]     frame #150: 0x00000001949de678 CoreFoundation`__CFRUNLOOP_IS_CALLING_OUT_TO_A_TIMER_CALLBACK_FUNCTION__ + 32
[        ]     frame #151: 0x0000000194962654 CoreFoundation`__CFRunLoopDoTimer + 1064
[        ]     frame #152: 0x000000019495ce00 CoreFoundation`__CFRunLoopDoTimers + 320
[        ]     frame #153: 0x000000019493b4b0 CoreFoundation`__CFRunLoopRun + 1936
[        ]     frame #154: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #155: 0x000000010339db5c Flutter`fml::MessageLoopDarwin::Run() + 88
[        ]     frame #156: 0x000000010339cc18 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::Thread::Thread(std::__1::function<void (fml::Thread::ThreadConfig const&)> const&, fml::Thread::ThreadConfig const&)::$_0>
>(void*) + 208
[        ]     frame #157: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #9, name = 'io.flutter.1.raster'
[        ]     frame #0: 0x00000001cc4664a0 libsystem_kernel.dylib`mach_msg_trap + 8
[        ]     frame #1: 0x00000001cc466ae4 libsystem_kernel.dylib`mach_msg + 76
[        ]     frame #2: 0x0000000194936d30 CoreFoundation`__CFRunLoopServiceMachPort + 372
[        ]     frame #3: 0x000000019493b1bc CoreFoundation`__CFRunLoopRun + 1180
[        ]     frame #4: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #5: 0x000000010339db5c Flutter`fml::MessageLoopDarwin::Run() + 88
[        ]     frame #6: 0x000000010339cc18 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::Thread::Thread(std::__1::function<void (fml::Thread::ThreadConfig const&)> const&, fml::Thread::ThreadConfig const&)::$_0>
>(void*) + 208
[        ]     frame #7: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #10, name = 'io.flutter.1.io'
[        ]     frame #0: 0x00000001cc4664a0 libsystem_kernel.dylib`mach_msg_trap + 8
[        ]     frame #1: 0x00000001cc466ae4 libsystem_kernel.dylib`mach_msg + 76
[        ]     frame #2: 0x0000000194936d30 CoreFoundation`__CFRunLoopServiceMachPort + 372
[        ]     frame #3: 0x000000019493b1bc CoreFoundation`__CFRunLoopRun + 1180
[        ]     frame #4: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #5: 0x000000010339db5c Flutter`fml::MessageLoopDarwin::Run() + 88
[        ]     frame #6: 0x000000010339cc18 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::Thread::Thread(std::__1::function<void (fml::Thread::ThreadConfig const&)> const&, fml::Thread::ThreadConfig const&)::$_0>
>(void*) + 208
[        ]     frame #7: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #11, name = 'io.flutter.1.profiler'
[        ]     frame #0: 0x00000001cc4664a0 libsystem_kernel.dylib`mach_msg_trap + 8
[        ]     frame #1: 0x00000001cc466ae4 libsystem_kernel.dylib`mach_msg + 76
[        ]     frame #2: 0x0000000194936d30 CoreFoundation`__CFRunLoopServiceMachPort + 372
[        ]     frame #3: 0x000000019493b1bc CoreFoundation`__CFRunLoopRun + 1180
[        ]     frame #4: 0x000000019494ebc8 CoreFoundation`CFRunLoopRunSpecific + 600
[        ]     frame #5: 0x000000010339db5c Flutter`fml::MessageLoopDarwin::Run() + 88
[        ]     frame #6: 0x000000010339cc18 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::Thread::Thread(std::__1::function<void (fml::Thread::ThreadConfig const&)> const&, fml::Thread::ThreadConfig const&)::$_0>
>(void*) + 208
[        ]     frame #7: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #12, name = 'io.worker.1'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #13, name = 'io.worker.2'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #14, name = 'io.worker.3'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #15, name = 'io.worker.4'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #16, name = 'io.worker.5'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #17, name = 'io.worker.6'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c298 libsystem_pthread.dylib`_pthread_cond_wait + 1236
[        ]     frame #2: 0x00000001ad79928c libc++.1.dylib`std::__1::condition_variable::wait(std::__1::unique_lock<std::__1::mutex>&) + 28
[        ]     frame #3: 0x0000000103397810 Flutter`void* std::__1::__thread_proxy<std::__1::tuple<std::__1::unique_ptr<std::__1::__thread_struct,
std::__1::default_delete<std::__1::__thread_struct> >, fml::ConcurrentMessageLoop::ConcurrentMessageLoop(unsigned long)::$_0> >(void*) + 316
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #18, name = 'dart:io EventHandler'
[        ]     frame #0: 0x00000001cc467e18 libsystem_kernel.dylib`kevent + 8
[        ]     frame #1: 0x000000010357f238 Flutter`dart::bin::EventHandlerImplementation::EventHandlerEntry(unsigned long) + 436
[        ]     frame #2: 0x00000001035b0c0c Flutter`dart::bin::ThreadStart(void*) + 44
[        ]     frame #3: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #19, name = 'Dart Profiler ThreadInterrupter'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fcf88 Flutter`dart::ThreadInterrupter::ThreadMain(unsigned long) + 424
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #20, name = 'Dart Profiler SampleBlockProcessor'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x000000010375a154 Flutter`dart::SampleBlockProcessor::ThreadMain(unsigned long) + 260
[        ]     frame #3: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #4: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #21, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fe098 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 680
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #22, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fe098 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 680
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #23, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fe098 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 680
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #24, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fe098 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 680
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #25, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001037fe098 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 680
[        ]     frame #4: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #5: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[        ]   thread #26, name = 'DartWorker'
[        ]     frame #0: 0x00000001cc466f24 libsystem_kernel.dylib`__psynch_cvwait + 8
[        ]     frame #1: 0x0000000205b8c2c4 libsystem_pthread.dylib`_pthread_cond_wait + 1280
[        ]     frame #2: 0x00000001037552a4 Flutter`dart::Monitor::WaitMicros(long long) + 128
[        ]     frame #3: 0x00000001036746c8 Flutter`dart::MutatorThreadPool::OnEnterIdleLocked(dart::MonitorLocker*) + 384
[        ]     frame #4: 0x00000001037fe0d8 Flutter`dart::ThreadPool::Worker::Main(unsigned long) + 744
[        ]     frame #5: 0x0000000103754c2c Flutter`dart::ThreadStart(void*) + 288
[        ]     frame #6: 0x0000000205b859ac libsystem_pthread.dylib`_pthread_start + 148
[   +7 ms] Fail to connect to service protocol: http://127.0.0.1:62419/: HttpException: Connection closed before full header was received, uri = http://127.0.0.1:62419/ws
[        ] Error connecting to the service protocol: failed to connect to http://127.0.0.1:62419/
[   +1 ms] "flutter run" took 30,712ms.
[   +2 ms] 
           #0      throwToolExit (package:flutter_tools/src/base/common.dart:10:3)
           #1      RunCommand.runCommand (package:flutter_tools/src/commands/run.dart:699:9)
           <asynchronous suspension>
           #2      FlutterCommand.run.<anonymous closure> (package:flutter_tools/src/runner/flutter_command.dart:1183:27)
           <asynchronous suspension>
           #3      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #4      CommandRunner.runCommand (package:args/command_runner.dart:209:13)
           <asynchronous suspension>
           #5      FlutterCommandRunner.runCommand.<anonymous closure> (package:flutter_tools/src/runner/flutter_command_runner.dart:281:9)
           <asynchronous suspension>
           #6      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #7      FlutterCommandRunner.runCommand (package:flutter_tools/src/runner/flutter_command_runner.dart:229:5)
           <asynchronous suspension>
           #8      run.<anonymous closure>.<anonymous closure> (package:flutter_tools/runner.dart:62:9)
           <asynchronous suspension>
           #9      AppContext.run.<anonymous closure> (package:flutter_tools/src/base/context.dart:150:19)
           <asynchronous suspension>
           #10     main (package:flutter_tools/executable.dart:94:3)
           <asynchronous suspension>
           
           
[   +1 ms] ensureAnalyticsSent: 0ms
[        ] Running shutdown hooks
[        ] Shutdown hooks complete
[        ] (lldb) 
[        ] ios-deploy exited with code 0
[   +1 ms] exiting with code 2
```
