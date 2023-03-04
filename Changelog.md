# Changelog

<!--
# To create a release, dispatch the https://github.com/yt-dlp/yt-dlp/actions/workflows/release.yml workflow on master
-->

### 2023.03.04.100510

- [Merge up to youtube-dl 195f22f6](https://github.com/yt-dlp/yt-dlp/commit/32a84bcf4e5c398fc31c2424d60ebff34e93c0b9) by [Grub4k](https://github.com/Grub4k), [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl 2dd6c6e](https://github.com/yt-dlp/yt-dlp/commit/45b2ee6f4fae139892a1a4335c269dcbb6671497) by [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl 8a158a9](https://github.com/yt-dlp/yt-dlp/commit/6d1b34896e69c4e53d8f960bf4b3867bca1c129c) by [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl adb5294](https://github.com/yt-dlp/yt-dlp/commit/16d4535abc99d81c3a59314e644b4af6c604e805) by [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl de39d128](https://github.com/yt-dlp/yt-dlp/commit/db4678e448d6e7da9743f4028c94b540fcafc528) by [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl e6a836d](https://github.com/yt-dlp/yt-dlp/commit/d711839760e220e561098cf257de43769049d238) by [pukkandan](https://github.com/pukkandan)
- [Merge up to youtube-dl ed5c44e7](https://github.com/yt-dlp/yt-dlp/commit/1ac7f461845b3f9c0c3a2e6a1308bf82d3e8e55a) by [pukkandan](https://github.com/pukkandan)

#### Core changes
- [Add `--compat-options 2021,2022`](https://github.com/yt-dlp/yt-dlp/commit/2a06bb4eb671eb306a2687ef0a4f853b936f05e0) by [pukkandan](https://github.com/pukkandan)
- [Add `--enable-file-urls`](https://github.com/yt-dlp/yt-dlp/commit/8300774c4a32cc21b56088869a720fbbc0eb288a) ([#5917](https://github.com/yt-dlp/yt-dlp/issues/5917)) by [coletdjnz](https://github.com/coletdjnz)
- [Add `--no-update`](https://github.com/yt-dlp/yt-dlp/commit/d32f30ac485e477fd6ba043c2342d12f2498c943) by [pukkandan](https://github.com/pukkandan)
- [Add `ac4` to known codecs](https://github.com/yt-dlp/yt-dlp/commit/710822166279059c2880bfa4ca7a5626cc1e7d98) by [pukkandan](https://github.com/pukkandan)
- [Add `weba` to known extensions](https://github.com/yt-dlp/yt-dlp/commit/fbb73833067ba742459729809679a62f34b3e41e) by [pukkandan](https://github.com/pukkandan)
- [Add deprecation warning for Py3.6](https://github.com/yt-dlp/yt-dlp/commit/eff4275925dadbee58b162650e00efbdd1c27ab9) by [pukkandan](https://github.com/pukkandan)
- [Add message when there are no subtitles/thumbnails](https://github.com/yt-dlp/yt-dlp/commit/88fb9425775da7f92d24e8b5f3009cafb56e94d6) by [pukkandan](https://github.com/pukkandan)
- [Add new field `aspect_ratio`](https://github.com/yt-dlp/yt-dlp/commit/105bfd90f572cdc4f4a06bfcbadde0f1b231a098) by [pukkandan](https://github.com/pukkandan)
- [Add option --retry-sleep](https://github.com/yt-dlp/yt-dlp/commit/23326151c45b632c3d5948bd018e80abb370e676) ([#3059](https://github.com/yt-dlp/yt-dlp/issues/3059)) by [pukkandan](https://github.com/pukkandan) (With fixes in [c4a62b9](https://github.com/yt-dlp/yt-dlp/commit/c4a62b99f682bac966ede4a58d1b20f0f3f49f1e), [666c36d](https://github.com/yt-dlp/yt-dlp/commit/666c36d58dfacc8998952569cc2d9c414957c53d))
- [Add option `--alias`](https://github.com/yt-dlp/yt-dlp/commit/9e491463521c65ca4d1d44a757e0a115f62834f5) by [pukkandan](https://github.com/pukkandan)
- [Add option `--break-match-filters`](https://github.com/yt-dlp/yt-dlp/commit/fe2ce85aff0aa03735fc0152bb8cb9c3d4ef0753) by [pukkandan](https://github.com/pukkandan)
- [Add option `--download-sections` to download video partially](https://github.com/yt-dlp/yt-dlp/commit/5ec1b6b71689d2f0cbdcd2b6c4dd861fb2fcf911) by [pukkandan](https://github.com/pukkandan)
- [Add option `--lazy-playlist` to process entries as they are received](https://github.com/yt-dlp/yt-dlp/commit/7e9a61258543f64113e779f2f82fe7a29827489d) by [pukkandan](https://github.com/pukkandan)
- [Add option `--use-extractors`](https://github.com/yt-dlp/yt-dlp/commit/fe7866d0ed6bfa3904ce12b049a3424fdc0ea1fa) by [pukkandan](https://github.com/pukkandan) (With fixes in [2516caf](https://github.com/yt-dlp/yt-dlp/commit/2516cafb28293612cfb6e158dac34a3117b42461))
- [Add pre-processor stage `video`](https://github.com/yt-dlp/yt-dlp/commit/119e40ef64b25f66a39246e87ce6c143cd34276d) by [pukkandan](https://github.com/pukkandan) (With fixes in [193fb15](https://github.com/yt-dlp/yt-dlp/commit/193fb150b76c4aaf41fb2c98b073e7e1f8a108f0))
- [Add slicing notation to `--playlist-items`](https://github.com/yt-dlp/yt-dlp/commit/7e88d7d78f452ea69f06bbdf23f82e9ad7c3de5e) by [pukkandan](https://github.com/pukkandan)
- [Add version to infojson](https://github.com/yt-dlp/yt-dlp/commit/b5e7a2e69d94d68d47586452e6014e03cf2a2805) by [pukkandan](https://github.com/pukkandan)
- [Allow a `set` to be passed as `download_archive`](https://github.com/yt-dlp/yt-dlp/commit/ae1035646a6be09c2aed3e22eb8910f341ddacfe) by [pukkandan](https://github.com/pukkandan) (With fixes in [9c935fb](https://github.com/yt-dlp/yt-dlp/commit/9c935fbc72de8f53c2d65f2ac9ef80b8358e2baf), [941e881](https://github.com/yt-dlp/yt-dlp/commit/941e881e1fe20ee8955f3b751ce26953d9e86656))
- [Allow extractors to specify section_start/end for clips](https://github.com/yt-dlp/yt-dlp/commit/3975b4d2e83a2d425a7b88752cd2d6ec83110f20) by [pukkandan](https://github.com/pukkandan)
- [Allow open ranges for time ranges](https://github.com/yt-dlp/yt-dlp/commit/fc2ba496fd09ca68c7e6eeb2c11e7000d08ff099) ([#4940](https://github.com/yt-dlp/yt-dlp/issues/4940)) by [Lesmiscore](https://github.com/Lesmiscore)
- [Allow plugin extractors to replace the built-in ones](https://github.com/yt-dlp/yt-dlp/commit/2314b4d89fc111ddfcb25937210f1f1c2390cc4a) by [pukkandan](https://github.com/pukkandan)
- [Allow users to specify encoding in each config files](https://github.com/yt-dlp/yt-dlp/commit/a904a7f8c6edc42046f0a78fb279739d500d4887) ([#4357](https://github.com/yt-dlp/yt-dlp/issues/4357)) by [Lesmiscore](https://github.com/Lesmiscore) (With fixes in [88f60fe](https://github.com/yt-dlp/yt-dlp/commit/88f60feb32614c723f997b2cba20c8c10fbe9bd3) by [pukkandan](https://github.com/pukkandan))
- [Backport SSL configuration from Python 3.10](https://github.com/yt-dlp/yt-dlp/commit/5b9f253fa0aee996cf1ed30185d4b502e00609c4) ([#5437](https://github.com/yt-dlp/yt-dlp/issues/5437)) by [coletdjnz](https://github.com/coletdjnz)
- [Bugfix for 3a408f9d199127ca2626359e21a866a09ab236b3](https://github.com/yt-dlp/yt-dlp/commit/1a8cc83735ed748afa78764af1e724afa646d8f9) by [pukkandan](https://github.com/pukkandan)
- [Deprioritize HEVC-over-FLV formats](https://github.com/yt-dlp/yt-dlp/commit/5424dbaf91728aaf77458e68d993ba6c34e8e222) ([#5823](https://github.com/yt-dlp/yt-dlp/issues/5823)) by [Lesmiscore](https://github.com/Lesmiscore)
- [Determine merge container better (See desc)](https://github.com/yt-dlp/yt-dlp/commit/fc61aff41beae0063b306dd9d74cc4ff27f0eff7) ([#1482](https://github.com/yt-dlp/yt-dlp/issues/1482)) by [pukkandan](https://github.com/pukkandan), [selfisekai](https://github.com/selfisekai)
- [Discard info_dict from memory if no longer needed](https://github.com/yt-dlp/yt-dlp/commit/134c913cca8e526a0128c62741689c0d0d05df03) by [pukkandan](https://github.com/pukkandan)
- [Do more processing in `--flat-playlist`](https://github.com/yt-dlp/yt-dlp/commit/94dc8604dde2c6cf92dff9678fdd633126d385dc) by [pukkandan](https://github.com/pukkandan)
- [Do not allow extractors to return `None`](https://github.com/yt-dlp/yt-dlp/commit/cb794ee010c88c6dddb3a38608114f6bc0e4a3a0) by [pukkandan](https://github.com/pukkandan)
- [Do not backport Python 3.10 SSL configuration for LibreSSL](https://github.com/yt-dlp/yt-dlp/commit/ac8e69dd3238c03eb40c267a090173abaac99a3a) ([#5464](https://github.com/yt-dlp/yt-dlp/issues/5464)) by [coletdjnz](https://github.com/coletdjnz)
- [Do not load system certificates when `certifi` is used](https://github.com/yt-dlp/yt-dlp/commit/168bbc4f3895f007af2341ed6b419908bf206e0a) by [pukkandan](https://github.com/pukkandan)
- [Do not print progress to `stderr` with `-q`](https://github.com/yt-dlp/yt-dlp/commit/8a7f6d7a155bc0966c40736336faea81db92315b) by [pukkandan](https://github.com/pukkandan)
- [Don't download entire video when no matching `--download-sections`](https://github.com/yt-dlp/yt-dlp/commit/0500ee3d81c5d31500d7093512deee2b0ff8aacd) by [pukkandan](https://github.com/pukkandan)
- [Ensure pre-processor errors do not block video download](https://github.com/yt-dlp/yt-dlp/commit/415f8d51a8f3565d7a1d4a8188511e7ad68514c7) by [pukkandan](https://github.com/pukkandan)
- [Fix `--break-on-existing` with `--lazy-playlist`](https://github.com/yt-dlp/yt-dlp/commit/d21056f4cf0a1623daa107f9181074f5725ac436) by [pukkandan](https://github.com/pukkandan)
- [Fix `--break-per-url --max-downloads`](https://github.com/yt-dlp/yt-dlp/commit/fd404bec7e6314c4584fedb1b595ee5e2d1225a6) by [pukkandan](https://github.com/pukkandan)
- [Fix `--concat-playlist`](https://github.com/yt-dlp/yt-dlp/commit/59d7de0da545944c48a82fc2937b996d7cd8cc9c) by [pukkandan](https://github.com/pukkandan)
- [Fix `--config-location -`](https://github.com/yt-dlp/yt-dlp/commit/1060f82f899b61a0a1c63df37ecdf6dc2bae50e8) by [pukkandan](https://github.com/pukkandan)
- [Fix `--cookies-from-browser` CLI parsing](https://github.com/yt-dlp/yt-dlp/commit/935bac1e4de35107a15ea2ad45402f507527dcfb) by [pukkandan](https://github.com/pukkandan)
- [Fix `--downloader native`](https://github.com/yt-dlp/yt-dlp/commit/28163422a667d63cceb0e8bf27d150951e78d313) by [pukkandan](https://github.com/pukkandan)
- [Fix `--list` options not implying `-s` in some cases](https://github.com/yt-dlp/yt-dlp/commit/e4221b700f01acd96fe6a03c20d57c59be6f1f7f) ([#5296](https://github.com/yt-dlp/yt-dlp/issues/5296)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
- [Fix `--simulate --max-downloads`](https://github.com/yt-dlp/yt-dlp/commit/ca6d59d2c1a38433708d4a739e812c0bc52655bc) by [pukkandan](https://github.com/pukkandan)
- [Fix `original_url` in playlists](https://github.com/yt-dlp/yt-dlp/commit/8791e78cccd68db8161f06dc8567280e0d99a5e1) by [pukkandan](https://github.com/pukkandan)
- [Fix `section_end` of clips](https://github.com/yt-dlp/yt-dlp/commit/bc401608830ba34831c31b74eb5661114bf284e7) by [pukkandan](https://github.com/pukkandan)
- [Fix bug in --download-archive](https://github.com/yt-dlp/yt-dlp/commit/c200096c031ac6f86f2ceb3792601ab0b33439ea) by [pukkandan](https://github.com/pukkandan)
- [Fix bug in `--alias`](https://github.com/yt-dlp/yt-dlp/commit/822d66e591341f8bf082be371b4beb66d72ba080) by [pukkandan](https://github.com/pukkandan) (With fixes in [ca7f8b8](https://github.com/yt-dlp/yt-dlp/commit/ca7f8b8f3150ad80e8a0de97e0b6f53df944e3d9))
- [Fix bug in writing playlist info-json](https://github.com/yt-dlp/yt-dlp/commit/ec54bd43f374cee429d67078ac61b75e66afb3fa) by [pukkandan](https://github.com/pukkandan)
- [Fix bugs in `PlaylistEntries`](https://github.com/yt-dlp/yt-dlp/commit/bc5c2f8a2c84633940956a27bf2125804f73882e) by [pukkandan](https://github.com/pukkandan)
- [Fix color in `-q -F`](https://github.com/yt-dlp/yt-dlp/commit/591bb9d3553a4d7b453777c1e28e0948741e3b50) by [pukkandan](https://github.com/pukkandan) (With fixes in [7896214](https://github.com/yt-dlp/yt-dlp/commit/7896214c42db91bbf62853b5c7359c9e83064cf1))
- [Fix config locations](https://github.com/yt-dlp/yt-dlp/commit/773c272d66d0874eae76795a3742f3eec1a950a8) ([#5933](https://github.com/yt-dlp/yt-dlp/issues/5933)) by [coletdjnz](https://github.com/coletdjnz), [Grub4k](https://github.com/Grub4k), [pukkandan](https://github.com/pukkandan)
- [Fix end time of clips](https://github.com/yt-dlp/yt-dlp/commit/2576d53a312efee864af023ea819c6608558bd1b) ([#5255](https://github.com/yt-dlp/yt-dlp/issues/5255)) by [cruel-efficiency](https://github.com/cruel-efficiency)
- [Fix for formats=None](https://github.com/yt-dlp/yt-dlp/commit/aebb4f4ba78ec7542416832e9dd5e47788cb12aa) by [pukkandan](https://github.com/pukkandan)
- [Fix lazy extractor bug in fe7866d0ed6bfa3904ce12b049a3424fdc0ea1fa](https://github.com/yt-dlp/yt-dlp/commit/e5458d1d88fcc81011ab19ba610c4b37946c9fa9) by [pukkandan](https://github.com/pukkandan)
- [Fix misleading DRM message](https://github.com/yt-dlp/yt-dlp/commit/7356a44443995d83c59b915186b6a719769eab60) by [pukkandan](https://github.com/pukkandan)
- [Fix playlist error handling](https://github.com/yt-dlp/yt-dlp/commit/1ac4fd80c87d4e566ae680076e788a63d187199b) by [pukkandan](https://github.com/pukkandan)
- [Fix rounding of integers in format table](https://github.com/yt-dlp/yt-dlp/commit/563e0bf82a84d2829ef4745dbaf23344e772fadb) by [pukkandan](https://github.com/pukkandan)
- [Fix tests for 989a01c2610832193c268d072ada8814bfd4c00d](https://github.com/yt-dlp/yt-dlp/commit/97d9c79e926197dcf277635d2582f882df4290ac) by [pukkandan](https://github.com/pukkandan)
- [Implement universal format sorting](https://github.com/yt-dlp/yt-dlp/commit/784320c98c2a7e84d72636bc25f6f54c86f5e481) by [pukkandan](https://github.com/pukkandan)
- [Imply `--no-progress` when `--print`](https://github.com/yt-dlp/yt-dlp/commit/5712943b764ba819ef479524c32700228603817a) by [pukkandan](https://github.com/pukkandan)
- [Import ctypes only when necessary](https://github.com/yt-dlp/yt-dlp/commit/fe0918bb65c828ec81ce904cece58d450c117eba) by [pukkandan](https://github.com/pukkandan)
- [Improve 5736d79172c47ff84740d5720467370a560febad](https://github.com/yt-dlp/yt-dlp/commit/2b24afa6d7f0ed09a663b4483d29f7c05258edfe) by [pukkandan](https://github.com/pukkandan)
- [Improve chapter sanitization](https://github.com/yt-dlp/yt-dlp/commit/a3976e07600247786b23df1ec9f93695b6d899ae) by [pukkandan](https://github.com/pukkandan)
- [Improve default subtitle language selection](https://github.com/yt-dlp/yt-dlp/commit/376aa24b1541e2bfb23337c0ae9bafa5bb3787f1) ([#6240](https://github.com/yt-dlp/yt-dlp/issues/6240)) by [sdht0](https://github.com/sdht0)
- [Improve error handling of bad config files](https://github.com/yt-dlp/yt-dlp/commit/44a6fcff397e98b4aa7e3bb1da7425b3cca05a71) by [pukkandan](https://github.com/pukkandan)
- [Improve handling for overriding extractors with plugins](https://github.com/yt-dlp/yt-dlp/commit/e756f45ba0648f972be71ce328419a623e381028) ([#5916](https://github.com/yt-dlp/yt-dlp/issues/5916)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
- [Improve plugin architecture](https://github.com/yt-dlp/yt-dlp/commit/8e40b9d1ec132ae1bcac50b3ee520ece46ac9c55) ([#5553](https://github.com/yt-dlp/yt-dlp/issues/5553)) by [coletdjnz](https://github.com/coletdjnz), [flashdagger](https://github.com/flashdagger), [Grub4K](https://github.com/Grub4K), [pukkandan](https://github.com/pukkandan)
- [Let `--parse/replace-in-metadata` run at any post-processing stage](https://github.com/yt-dlp/yt-dlp/commit/fe74d5b592438c669f5717b34504f27c34ca9904) by [pukkandan](https://github.com/pukkandan)
- [Make `title` completely non-fatal](https://github.com/yt-dlp/yt-dlp/commit/7aefd19afed357c80743405ec2ace2148cba42e3) by [pukkandan](https://github.com/pukkandan)
- [Make early reject of `--match-filter` stricter](https://github.com/yt-dlp/yt-dlp/commit/d7b460d0e5fc710950582baed2e3fc616ed98a80) by [pukkandan](https://github.com/pukkandan)
- [Minor bugfixes](https://github.com/yt-dlp/yt-dlp/commit/0647d9251f7285759109cc82693efee533346911) by [pukkandan](https://github.com/pukkandan) (With fixes in [a6ca61d](https://github.com/yt-dlp/yt-dlp/commit/a6ca61d427f37b472f30afd90d5e8cf539c541b6))
- [Playlists maynot always have webpage_url](https://github.com/yt-dlp/yt-dlp/commit/0bd5a039ea234374821510ac0371e03e87a6a57f) by [pukkandan](https://github.com/pukkandan)
- [Reject entire playlists faster with `--match-filter`](https://github.com/yt-dlp/yt-dlp/commit/3bec830a597e8c7ab0d9f4e1258dc4a1be0b1de4) by [pukkandan](https://github.com/pukkandan) (With fixes in [3955b20](https://github.com/yt-dlp/yt-dlp/commit/3955b20703ccda1568835bc9822479ea68e7ee67))
- [Remove Python 3.6 support](https://github.com/yt-dlp/yt-dlp/commit/6929b41a216e20f0498cbd99880b17eab16777c9) by [pukkandan](https://github.com/pukkandan)
- [Remove filtered entries from `-J`](https://github.com/yt-dlp/yt-dlp/commit/f0ad6f8c510449bf79c818bafd27779f24e2fbbc) by [pukkandan](https://github.com/pukkandan)
- [Restore LD_LIBRARY_PATH when using PyInstaller](https://github.com/yt-dlp/yt-dlp/commit/82ea226c61880c9118cce32681e54be24839519a) ([#4666](https://github.com/yt-dlp/yt-dlp/issues/4666)) by [Lesmiscore](https://github.com/Lesmiscore)
- [Return an error code if update fails](https://github.com/yt-dlp/yt-dlp/commit/e79969b2425e0c52813780f2b2afbccd4b4b0647) by [pukkandan](https://github.com/pukkandan)
- [Sanitize `chapters`](https://github.com/yt-dlp/yt-dlp/commit/9eef7c4e558f86fb248554868931936097d46592) by [pukkandan](https://github.com/pukkandan)
- [Sanitize formats before sorting](https://github.com/yt-dlp/yt-dlp/commit/39f32f1715c0dffb7626dda7307db6388bb7abaa) by [pukkandan](https://github.com/pukkandan) (With fixes in [9ebac35](https://github.com/yt-dlp/yt-dlp/commit/9ebac35577e61c3d25fafc959655fa3ab04ca7ef), [c154302](https://github.com/yt-dlp/yt-dlp/commit/c154302c588c3d4362cec4fc5545e7e5d2bcf7a3))
- [Skip some fixup if remux/recode is needed](https://github.com/yt-dlp/yt-dlp/commit/ca9def714a71151bec9e16ae0042a2c49f9ec99c) ([#4266](https://github.com/yt-dlp/yt-dlp/issues/4266)) by [Lesmiscore](https://github.com/Lesmiscore)
- [Standardize retry mechanism](https://github.com/yt-dlp/yt-dlp/commit/be5c1ae86202be54225d376756f5d9f0bf8f392a) ([#1649](https://github.com/yt-dlp/yt-dlp/issues/1649)) by [pukkandan](https://github.com/pukkandan) (With fixes in [05e2243](https://github.com/yt-dlp/yt-dlp/commit/05e2243e8032061f300c00ca62999b6b29e1ed8f))
- [Support `--no-progress` for `--wait-for-video`](https://github.com/yt-dlp/yt-dlp/commit/a7dc6a89f66c9bf3c8cff5ef7c8e775d57a5b917) by [pukkandan](https://github.com/pukkandan)
- [Support environment variables in `--ffmpeg-location`](https://github.com/yt-dlp/yt-dlp/commit/5736d79172c47ff84740d5720467370a560febad) by [pukkandan](https://github.com/pukkandan)
- [Support module level `__bool__` and `property`](https://github.com/yt-dlp/yt-dlp/commit/754c84e2e416cf6609dd0e4632b4985a08d34043) by [pukkandan](https://github.com/pukkandan)
- [Update publish.yml](https://github.com/yt-dlp/yt-dlp/commit/cb59f73cbc634f3b81652ad712442dfee04a761e) by [pukkandan](https://github.com/pukkandan)
- [Validate `--merge-output-format`](https://github.com/yt-dlp/yt-dlp/commit/4f04be6add6133d103b4c671cec02128a8a0f16e) by [pukkandan](https://github.com/pukkandan)
- [Workaround `libc_ver` not be available on Windows Store version of Python](https://github.com/yt-dlp/yt-dlp/commit/dab284f80fb08675008eec39a4561fed1cf1617b) by [pukkandan](https://github.com/pukkandan)
- [Write API params in debug head](https://github.com/yt-dlp/yt-dlp/commit/497074f044b4641289527f6c960b88705d256568) by [pukkandan](https://github.com/pukkandan)
- [[cleanup Misc](https://github.com/yt-dlp/yt-dlp/commit/d5d1df8afdd532cc889f9d95be0740668a0776fe) by [pukkandan](https://github.com/pukkandan)
- [`--compat-option no-live-chat` should disable danmaku](https://github.com/yt-dlp/yt-dlp/commit/b79f9e302d1f75edda18035e4efffc395b5710e5) by [pukkandan](https://github.com/pukkandan)
- [`--config-location -` to provide options interactively](https://github.com/yt-dlp/yt-dlp/commit/6b9e832db7dedcd6f2e7be1bf44f56a91ff18737) by [pukkandan](https://github.com/pukkandan)
- [`--max-downloads` should obey `--break-per-input`](https://github.com/yt-dlp/yt-dlp/commit/490110c543828b1cc9f83b3c3bbfb1bb2118b055) by [pukkandan](https://github.com/pukkandan)
- [extractor/DouyuTV]: [Use new API](https://github.com/yt-dlp/yt-dlp/commit/f14c2333481c63c24017a41ded7d8f36726504b7) ([#6074](https://github.com/yt-dlp/yt-dlp/issues/6074)) by [hatienl0i261299](https://github.com/hatienl0i261299)
- [extractor/cda]: [Support login through API](https://github.com/yt-dlp/yt-dlp/commit/34f00179db37b963d6c8ce8703877a06aa7f1195) ([#5100](https://github.com/yt-dlp/yt-dlp/issues/5100)) by [selfisekai](https://github.com/selfisekai)
- aes
    - [Add multiple padding modes in CBC](https://github.com/yt-dlp/yt-dlp/commit/7a7eeb10053f2765803bb088ab968072dd09254c) by [elyse0](https://github.com/elyse0)
- cache
    - extractor/youtube: [Invalidate old cache](https://github.com/yt-dlp/yt-dlp/commit/5e01315aa1ad0c56be33cb5b6a4d079068ee7145) by [pukkandan](https://github.com/pukkandan)
- compat
    - [Add `functools.cached_property`](https://github.com/yt-dlp/yt-dlp/commit/2762dbb17e8556140f9fff0c0aa3373c521f5e09) by [pukkandan](https://github.com/pukkandan)
    - [Fix `compat.WINDOWS_VT_MODE`](https://github.com/yt-dlp/yt-dlp/commit/3c5386cd711a5a0480a0b8d72e9df5007b10ac92) by [pukkandan](https://github.com/pukkandan)
    - [Fix `shutils.move` in restricted ACL mode on BSD](https://github.com/yt-dlp/yt-dlp/commit/fbb0ee7747b8e3657c9c50d26b728eb4c75d1899) ([#5309](https://github.com/yt-dlp/yt-dlp/issues/5309)) by [ClosedPort22](https://github.com/ClosedPort22), [pukkandan](https://github.com/pukkandan)
    - [Implement `compat.imghdr`](https://github.com/yt-dlp/yt-dlp/commit/5792c950bfd9f8b6730659b3046b41c1aea64c98) by [pukkandan](https://github.com/pukkandan)
    - [Let PyInstaller detect _legacy module](https://github.com/yt-dlp/yt-dlp/commit/f5e438a976dcf8d7d263631ea0b0bf114b6182af) by [pukkandan](https://github.com/pukkandan)
    - [Remove deprecated functions from core code](https://github.com/yt-dlp/yt-dlp/commit/14f25df2b6233553e968df023430ca96c0b1df9f) by [pukkandan](https://github.com/pukkandan)
    - [Remove more functions](https://github.com/yt-dlp/yt-dlp/commit/ac668111128b5f124b4271b3aa4c35f6e71a4749) by [pukkandan](https://github.com/pukkandan)
- compat_utils
    - [Improve `passthrough_module`](https://github.com/yt-dlp/yt-dlp/commit/88426d9446758c707fb511408f2d6f56de952db4) by [pukkandan](https://github.com/pukkandan)
    - [Simplify `EnhancedModule`](https://github.com/yt-dlp/yt-dlp/commit/768a00178109508893488e53a0e720b117fbccf6) by [pukkandan](https://github.com/pukkandan)
- cookies
    - [Detect profiles for cygwin/BSD](https://github.com/yt-dlp/yt-dlp/commit/dec30912a708d01b4164f35dda85319361a97a58) ([#3975](https://github.com/yt-dlp/yt-dlp/issues/3975)) by [moench-tegeder](https://github.com/moench-tegeder)
    - [Improve `LenientSimpleCookie`](https://github.com/yt-dlp/yt-dlp/commit/36069409ec7ed88f7571f29ff35a5a4c62b70cfc) ([#5195](https://github.com/yt-dlp/yt-dlp/issues/5195)) by [Grub4K](https://github.com/Grub4K)
    - [Improve container support](https://github.com/yt-dlp/yt-dlp/commit/825d3ce386e66ac0c73e41e352d84053f9f0e624) ([#4806](https://github.com/yt-dlp/yt-dlp/issues/4806)) by [bashonly](https://github.com/bashonly), [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Let `_get_mac_keyring_password` fail gracefully](https://github.com/yt-dlp/yt-dlp/commit/46a5b335e708c81bb6e9eb8cef0c13c72c497f0a) by [pukkandan](https://github.com/pukkandan)
    - [Parse cookies leniently](https://github.com/yt-dlp/yt-dlp/commit/8817a80d3ac69f2dfd12bdc41657c4a04139807c) ([#4780](https://github.com/yt-dlp/yt-dlp/issues/4780)) by [Grub4K](https://github.com/Grub4K)
    - [Support firefox container in `--cookies-from-browser`](https://github.com/yt-dlp/yt-dlp/commit/9bd13fe5bbe1df6bb01d4edb68f2c63a4812bf94) ([#4753](https://github.com/yt-dlp/yt-dlp/issues/4753)) by [bashonly](https://github.com/bashonly)
- dependencies
    - [Simplify `Cryptodome`](https://github.com/yt-dlp/yt-dlp/commit/65f6e807804d2af5e00f2aecd72bfc43af19324a) by [pukkandan](https://github.com/pukkandan)
    - [Standardize `Cryptodome` imports](https://github.com/yt-dlp/yt-dlp/commit/f6a765ceb59c55aea06921880c1c87d1ff36e5de) by [pukkandan](https://github.com/pukkandan)
- jsinterp
    - [Add `charcodeAt` and bitwise overflow](https://github.com/yt-dlp/yt-dlp/commit/f26af78a8ac11d9d617ed31ea5282cfaa5bcbcfa) ([#4706](https://github.com/yt-dlp/yt-dlp/issues/4706)) by [elyse0](https://github.com/elyse0)
    - [Bring on-par with youtube-dl](https://github.com/yt-dlp/yt-dlp/commit/be13a6e525a05f97dffd6ee0798145132f14be3a) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
    - [Bring or-par with youtube-dl](https://github.com/yt-dlp/yt-dlp/commit/49b4ceaedf92db85177cfa10542bddbed16529c7) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
    - [Escape regex that looks like nested set](https://github.com/yt-dlp/yt-dlp/commit/b44cd29851fdc2fadb283adb59a074f89a27ba7e) by [pukkandan](https://github.com/pukkandan)
    - [Fix `_separate`](https://github.com/yt-dlp/yt-dlp/commit/c4b2df872d0ab49da939bf8bda001fa4e2d2ea06) by [pukkandan](https://github.com/pukkandan)
    - [Fix bug in operator precedence](https://github.com/yt-dlp/yt-dlp/commit/164b03c4864b0d44cfee5e7702f7c2317164a6cf) by [pukkandan](https://github.com/pukkandan)
    - [Fix escape in regex](https://github.com/yt-dlp/yt-dlp/commit/05deb747bb18febb803b47119ca7bc432ffb80c8) by [pukkandan](https://github.com/pukkandan)
    - [Fix for youtube player 1f7d5369](https://github.com/yt-dlp/yt-dlp/commit/f6ca640b122239d5ab215f8c2564efb7ac3e8c65) by [pukkandan](https://github.com/pukkandan)
    - [Fix for youtube player c81bbb4a](https://github.com/yt-dlp/yt-dlp/commit/6d3e7424bfe8cfdbd5931a37519ca7faafff642d) by [pukkandan](https://github.com/pukkandan)
    - [Handle `Date` at epoch 0](https://github.com/yt-dlp/yt-dlp/commit/9acf1ee25f7ad3920ede574a9de95b8c18626af4) by [pukkandan](https://github.com/pukkandan)
    - [Handle new youtube signature functions](https://github.com/yt-dlp/yt-dlp/commit/8f53dc44a0cc1c2d98c35740b9293462c080f5d0) by [pukkandan](https://github.com/pukkandan)
    - [Implement timeout](https://github.com/yt-dlp/yt-dlp/commit/992dc6b4863d0e60f2a1ce3933f67814d8a17f8d) by [pukkandan](https://github.com/pukkandan)
    - [Improve separating regex](https://github.com/yt-dlp/yt-dlp/commit/0468a3b3253957bfbeb98b4a7c71542ff80e9e06) by [pukkandan](https://github.com/pukkandan)
    - [Some optimizations and refactoring](https://github.com/yt-dlp/yt-dlp/commit/230d5c8239d6b6e211f413de26979398c1cabb04) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
    - [Support `if` statements](https://github.com/yt-dlp/yt-dlp/commit/8b008d62544b82e24a0ba36c30e8e51855d93419) by [pukkandan](https://github.com/pukkandan)
    - [Truncate error messages](https://github.com/yt-dlp/yt-dlp/commit/a1c5bd82eccf36ed239d368b86ac46db236ff9b1) by [pukkandan](https://github.com/pukkandan)
    - [Workaround operator associativity issue](https://github.com/yt-dlp/yt-dlp/commit/1a7c9fad9f89b8994911c7d83f012da5f1aef445) by [pukkandan](https://github.com/pukkandan)
    - extractor/youtube: [Minor fixes](https://github.com/yt-dlp/yt-dlp/commit/d81ba7d491bf2c89246d8817438db48a5a4e4ae9) by [pukkandan](https://github.com/pukkandan)
- outtmpl
    - [Add alternate form `h` for HTML escaping](https://github.com/yt-dlp/yt-dlp/commit/47cdc68e034cd7f61414e6634df334f56b795a07) by [pukkandan](https://github.com/pukkandan)
    - [Curly braces to filter keys](https://github.com/yt-dlp/yt-dlp/commit/07a1250e0e90515ff8142161536f9dafa6eaba1b) by [pukkandan](https://github.com/pukkandan) (With fixes in [48c8424](https://github.com/yt-dlp/yt-dlp/commit/48c8424bd9e03fdfd5c4c4495de233e896eb1f16))
    - [Ensure ASCII in json and add option for Unicode](https://github.com/yt-dlp/yt-dlp/commit/9b9dad119a5307fb847aa5626d9391b59f1865d5) by [pukkandan](https://github.com/pukkandan)
    - [Make `%s` work in strfformat for all systems](https://github.com/yt-dlp/yt-dlp/commit/9665f15a960c4e274b0be5fbf22e6f4a6680d162) by [pukkandan](https://github.com/pukkandan)
    - [Smarter replacing of unsupported characters](https://github.com/yt-dlp/yt-dlp/commit/989a01c2610832193c268d072ada8814bfd4c00d) by [pukkandan](https://github.com/pukkandan)
    - [Treat empty values as None in filenames](https://github.com/yt-dlp/yt-dlp/commit/a6bcaf71fc94b2f301d4253ecea87ea2ff76fedb) by [pukkandan](https://github.com/pukkandan)
- plugins
    - [Don't look in `.egg` directories](https://github.com/yt-dlp/yt-dlp/commit/b059188383eee4fa336ef728dda3ff4bb7335625) by [pukkandan](https://github.com/pukkandan)
    - [Fix zip search paths](https://github.com/yt-dlp/yt-dlp/commit/88d8928bf7630801865cf8728ae5c77234324b7b) by [pukkandan](https://github.com/pukkandan)
- update
    - [Ability to set a maximum version for specific variants](https://github.com/yt-dlp/yt-dlp/commit/b1f94422cc22886e18e3c3fb8243506eee573e98) by [pukkandan](https://github.com/pukkandan)
    - [Add option `--update-to`, including to nightly](https://github.com/yt-dlp/yt-dlp/commit/77df20f14cc9ed41dfe3a1fe2d77fd27f5365a94) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K), [pukkandan](https://github.com/pukkandan)
    - [Copy bitmask from old binary](https://github.com/yt-dlp/yt-dlp/commit/6440c45ff3c3209593c0f39af075e71e4ca0299a) by [Lesmiscore](https://github.com/Lesmiscore)
    - [Do not check `_update_spec` when up to date](https://github.com/yt-dlp/yt-dlp/commit/a63b35a60c6a6a04e8c863dc9e4e2554a74c0140) by [pukkandan](https://github.com/pukkandan)
    - [Expose more functionality to API](https://github.com/yt-dlp/yt-dlp/commit/57e0f077a635ee30f37ebea71ddb70723831ecd8) by [pukkandan](https://github.com/pukkandan)
    - [Fix updater file removal on windows](https://github.com/yt-dlp/yt-dlp/commit/5be214abed6d35a5337a806c74a5883a58d6934e) ([#5970](https://github.com/yt-dlp/yt-dlp/issues/5970)) by [Grub4K](https://github.com/Grub4K)
    - [Prepare to remove Python 3.6 support](https://github.com/yt-dlp/yt-dlp/commit/24093d52a768e624a3ecd9d834f3239f64e1bf2c) by [pukkandan](https://github.com/pukkandan)
    - [Self-restart after update](https://github.com/yt-dlp/yt-dlp/commit/8372be74699de4591ea2d439fc01f1950870ab7f) by [pukkandan](https://github.com/pukkandan)
    - [Set executable bit-mask](https://github.com/yt-dlp/yt-dlp/commit/a6125983ab4434fc4079f575a4bf22042411ea5e) by [pukkandan](https://github.com/pukkandan)
    - [Use `.git` folder to distinguish `source`/`unknown`](https://github.com/yt-dlp/yt-dlp/commit/233ad894d3fa4596b793541649f6183188508e44) by [pukkandan](https://github.com/pukkandan)
    - [Use error code 100 for update errors](https://github.com/yt-dlp/yt-dlp/commit/ff48fc04d0001b98a7dcbd30cce67aa1135ef355) by [pukkandan](https://github.com/pukkandan)
    - [Workaround #5632](https://github.com/yt-dlp/yt-dlp/commit/2fb0f858686c46abc50a0e253245afe750746775) by [pukkandan](https://github.com/pukkandan)
- utils
    - [Add `deprecation_warning`](https://github.com/yt-dlp/yt-dlp/commit/da4db748fa813a8de684d5ab699b8f561b982e35) by [pukkandan](https://github.com/pukkandan)
    - [Add orderedSet_from_options](https://github.com/yt-dlp/yt-dlp/commit/5314b521925498356e78652fe59866116d56e1d1) by [pukkandan](https://github.com/pukkandan)
    - [Don't use Content-length with encoding](https://github.com/yt-dlp/yt-dlp/commit/65e5c021e7c5f23ecbc6a982b72a02ac6cd6900d) ([#6176](https://github.com/yt-dlp/yt-dlp/issues/6176)) by [felixonmars](https://github.com/felixonmars)
    - [Fix `get_compatible_ext`](https://github.com/yt-dlp/yt-dlp/commit/8f84770acd7b70e7f6876f9ea8c5b1f4f0497b66) by [pukkandan](https://github.com/pukkandan)
    - [Fix `get_domain`](https://github.com/yt-dlp/yt-dlp/commit/ebf99aaf7002b3178ae3e5e68930d277115e54d3) by [pukkandan](https://github.com/pukkandan)
    - [Fix `time_seconds` to use the provided TZ](https://github.com/yt-dlp/yt-dlp/commit/83c4970e52839ce8761ec61bd19d549aed7d7920) ([#6118](https://github.com/yt-dlp/yt-dlp/issues/6118)) by [Grub4K](https://github.com/Grub4K), [Lesmiscore](https://github.com/Lesmiscore)
    - [Fix inconsistent default handling between HTTP and HTTPS requests](https://github.com/yt-dlp/yt-dlp/commit/379a4f161d4ad3e40932dcf5aca6e6fb9715ab28) ([#4158](https://github.com/yt-dlp/yt-dlp/issues/4158)) by [pukkandan](https://github.com/pukkandan)
    - [Fix race condition in `make_dir`](https://github.com/yt-dlp/yt-dlp/commit/b25d6cb96337d479bdcb41768356da414c3aa835) ([#6089](https://github.com/yt-dlp/yt-dlp/issues/6089)) by [aionescu](https://github.com/aionescu)
    - [Improve performance using `functools.cache`](https://github.com/yt-dlp/yt-dlp/commit/0b9c08b47bb5e95c21b067044ace4e824d19a9c2) by [pukkandan](https://github.com/pukkandan) (With fixes in [53973b4](https://github.com/yt-dlp/yt-dlp/commit/53973b4d2cb349d39d6f240911142b330d1dd80d))
    - [Make `ExtractorError` mutable](https://github.com/yt-dlp/yt-dlp/commit/9bcfe33be7f1aa7164e690ced133cae4b063efa4) by [pukkandan](https://github.com/pukkandan)
    - [Move `FileDownloader.parse_bytes` into utils](https://github.com/yt-dlp/yt-dlp/commit/64c464a144e2a96ec21a717d191217edda9107a4) by [pukkandan](https://github.com/pukkandan)
    - [Move format sorting code into `utils`](https://github.com/yt-dlp/yt-dlp/commit/d0d74b719755548dab8fc7c402ad3e303391e826) by [pukkandan](https://github.com/pukkandan)
    - [Send HTTP/1.1 ALPN extension](https://github.com/yt-dlp/yt-dlp/commit/2c6dcb65fb612fc5bc5c61937bf438d3c473d8d0) ([#3889](https://github.com/yt-dlp/yt-dlp/issues/3889)) by [coletdjnz](https://github.com/coletdjnz)
    - [Use local kernel32 for file locking on Windows](https://github.com/yt-dlp/yt-dlp/commit/37e325b92ff9d784715ac0e5d1f7d96bf5f45ad9) by [Grub4K](https://github.com/Grub4K)
    - `ExtractorError`: [Fix `exc_info`](https://github.com/yt-dlp/yt-dlp/commit/5df14442552038d7344162b21f97dd510fe2ffd6) by [pukkandan](https://github.com/pukkandan)
    - `ISO3166Utils`: [Add `EU` and `AP`](https://github.com/yt-dlp/yt-dlp/commit/2f97cc615bdb788bf5c86c1132144ca491b820c3) by [pukkandan](https://github.com/pukkandan)
    - `LenientJSONDecoder`: [Parse unclosed objects](https://github.com/yt-dlp/yt-dlp/commit/cc09083636ce21e58ff74f45eac2dbda507462b0) by [pukkandan](https://github.com/pukkandan)
    - `Popen.run`: [Fix default return in binary mode](https://github.com/yt-dlp/yt-dlp/commit/914491b8e087d21b8a1714eb185008c29b6fe1e8) by [pukkandan](https://github.com/pukkandan)
    - `Popen`
        - [Refactor to use contextmanager](https://github.com/yt-dlp/yt-dlp/commit/f0c9fb96827ff798a48626e7e5d32a9c5de7b97e) by [pukkandan](https://github.com/pukkandan)
        - [Shim undocumented `text_mode` property](https://github.com/yt-dlp/yt-dlp/commit/da8e2912b165005f76779a115a071cd6132ceedf) by [Grub4K](https://github.com/Grub4K)
    - `base_url`: [URL paths can contain `&`](https://github.com/yt-dlp/yt-dlp/commit/7657ec7ed6318dd66dd72cc100ba7bc5b911366e) ([#4841](https://github.com/yt-dlp/yt-dlp/issues/4841)) by [elyse0](https://github.com/elyse0)
    - `classproperty`: [Add cache support](https://github.com/yt-dlp/yt-dlp/commit/83cc7b8aae1328b0d148b631357f753c61c38a29) by [pukkandan](https://github.com/pukkandan)
    - `get_exe_version`: [Detect broken executables](https://github.com/yt-dlp/yt-dlp/commit/1cdda3299810b86206853a22e680758eadcc4e05) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
    - `is_html`: [Handle double BOM](https://github.com/yt-dlp/yt-dlp/commit/80e8493ee7c3083f4e215794e4a67ba5265f24f7) by [pukkandan](https://github.com/pukkandan)
    - `js_to_json`
        - [Improve](https://github.com/yt-dlp/yt-dlp/commit/f55523cfdd18dcd578f5d96cbb06266663169d35) by [pukkandan](https://github.com/pukkandan)
        - [Improve escape handling](https://github.com/yt-dlp/yt-dlp/commit/a71b812f53a5f678e4c9467858e721dcd4953a16) ([#5217](https://github.com/yt-dlp/yt-dlp/issues/5217)) by [Grub4K](https://github.com/Grub4K)
    - `locked_file`: [Fix for PyPy on Windows](https://github.com/yt-dlp/yt-dlp/commit/2cb19820430aa8f7fe8cef11203d9f98388ef8ab) by [pukkandan](https://github.com/pukkandan)
    - `mimetype2ext`: [weba is not standard](https://github.com/yt-dlp/yt-dlp/commit/d80ca5deaa46db6e498399bb04a72a4c10ee8e22) by [pukkandan](https://github.com/pukkandan)
    - `strftime_or_none`: [Workaround Python bug on Windows](https://github.com/yt-dlp/yt-dlp/commit/d509c1f5a347d0247593f116fa5cad2ff4f9a3de) by [pukkandan](https://github.com/pukkandan)
    - `traverse_obj`
        - [Allow `re.Match` objects](https://github.com/yt-dlp/yt-dlp/commit/7b0127e1e11186bcbb80a18b1b530d864a5dbada) ([#5174](https://github.com/yt-dlp/yt-dlp/issues/5174)) by [Grub4K](https://github.com/Grub4K)
        - [Always return list when branching](https://github.com/yt-dlp/yt-dlp/commit/f99bbfc9838d98d81027dddb18ace0af66acdf6d) ([#5170](https://github.com/yt-dlp/yt-dlp/issues/5170)) by [Grub4K](https://github.com/Grub4K)
        - [Fix more bugs](https://github.com/yt-dlp/yt-dlp/commit/6839ae1f6dde4c0442619e351b3f0442312ab4f9) by [pukkandan](https://github.com/pukkandan)
        - [Fix several behavioral problems](https://github.com/yt-dlp/yt-dlp/commit/b1bde57bef878478e3503ab07190fd207914ade9) by [Grub4K](https://github.com/Grub4K)
        - [Rewrite, document and add tests](https://github.com/yt-dlp/yt-dlp/commit/ab029d7e9200a273d7204be68c0735b16971ff44) ([#5024](https://github.com/yt-dlp/yt-dlp/issues/5024)) by [Grub4K](https://github.com/Grub4K)
        - [Various improvements](https://github.com/yt-dlp/yt-dlp/commit/776995bc109c5cd1aa56b684fada2ce718a386ec) by [Grub4K](https://github.com/Grub4K)
    - `windows_enable_vt_mode`: [Better error handling](https://github.com/yt-dlp/yt-dlp/commit/f079514957401f49db30ec4cd25f8c8246b0c1de) by [pukkandan](https://github.com/pukkandan)
    - cleanup
        - [Consolidate known media extensions](https://github.com/yt-dlp/yt-dlp/commit/8dc593051132fd626e06270e1f540717208025e3) by [pukkandan](https://github.com/pukkandan)
        - [Refactor parse_codecs](https://github.com/yt-dlp/yt-dlp/commit/d816f61fbf45498233b72526963c938ebdd1d52a) by [pukkandan](https://github.com/pukkandan)
    - js_to_json: [Fix bug in f55523c](https://github.com/yt-dlp/yt-dlp/commit/d5f043d127cac1e8ec8a6eacde04ad1133600a16) ([#5771](https://github.com/yt-dlp/yt-dlp/issues/5771)) by [ChillingPepper](https://github.com/ChillingPepper), [pukkandan](https://github.com/pukkandan)
    - sanitize_open: [Allow any IO stream as stdout](https://github.com/yt-dlp/yt-dlp/commit/daef7911000bea69407667de8193eafcdcdad36b) by [pukkandan](https://github.com/pukkandan)
    - windows_enable_vt_mode: [Proper implementation](https://github.com/yt-dlp/yt-dlp/commit/c53a18f016fe6ff774411d938c9959097f00b44c) by [Grub4K](https://github.com/Grub4K)

#### Extractor changes
- [Add `_search_json`](https://github.com/yt-dlp/yt-dlp/commit/b7c47b743871cdf3e0de75b17e4454d987384bf9) by [pukkandan](https://github.com/pukkandan) (With fixes in [6514166](https://github.com/yt-dlp/yt-dlp/commit/65141660aba62fefb1901804aeb0484992243af7) by [coletdjnz](https://github.com/coletdjnz))
- [Add `default` parameter to `_search_json`](https://github.com/yt-dlp/yt-dlp/commit/f0bc6e2019a2f81d358ebddc4ae4cf8e9e4ed905) ([#4057](https://github.com/yt-dlp/yt-dlp/issues/4057)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
- [Add a way to distinguish IEs that returns only videos](https://github.com/yt-dlp/yt-dlp/commit/171a31dbe8b59b3bab6a9b0712594228ee1b5234) by [pukkandan](https://github.com/pukkandan)
- [Add dev option `--load-pages`](https://github.com/yt-dlp/yt-dlp/commit/f95b9dee4501eed75e7dba984cd914f7f16e3bf1) by [pukkandan](https://github.com/pukkandan) (With fixes in [09d02ea](https://github.com/yt-dlp/yt-dlp/commit/09d02ea4294fd5b284a18a904b8b08f3c9ec1fd9))
- [Add field `audio_channels`](https://github.com/yt-dlp/yt-dlp/commit/b8ed0f15d4a86e815da72bae9c7ef7ae106dd86b) by [pukkandan](https://github.com/pukkandan)
- [Deprecate `_sort_formats`](https://github.com/yt-dlp/yt-dlp/commit/9f14daf22b4080ae1531a772ee7574959af4e2fa) by [pukkandan](https://github.com/pukkandan)
- [Escape `%` in `representation_id` of m3u8](https://github.com/yt-dlp/yt-dlp/commit/0cb0fdbbfe32a0e8bc03c3248b95ec473a98b5cc) by [pukkandan](https://github.com/pukkandan)
- [Fix DRM detection in m3u8](https://github.com/yt-dlp/yt-dlp/commit/43a3eaf96393b712d60cbcf5c6cb1e90ed7f42f5) by [pukkandan](https://github.com/pukkandan)
- [Fix `_create_request` when headers is None](https://github.com/yt-dlp/yt-dlp/commit/c043c246251da815c99f8c779194fcdef9ef7a58) by [pukkandan](https://github.com/pukkandan)
- [Fix `_search_nuxt_data`](https://github.com/yt-dlp/yt-dlp/commit/b23167e7542c177f32b22b29857b637dc4aede69) ([#6062](https://github.com/yt-dlp/yt-dlp/issues/6062)) by [LowSuggestion912](https://github.com/LowSuggestion912)
- [Fix `fatal=False` for `_search_nuxt_data`](https://github.com/yt-dlp/yt-dlp/commit/f7fc8d39e99d5b0683ac48a876618a5495a9ef5e) by [pukkandan](https://github.com/pukkandan)
- [Fix `fatal=False` in `RetryManager`](https://github.com/yt-dlp/yt-dlp/commit/8ca48a1a5427040fd708f33a264c10d5d0e85fc1) by [pukkandan](https://github.com/pukkandan)
- [Fix `json_ld` type checks](https://github.com/yt-dlp/yt-dlp/commit/1d55ebabc93b8e422a0126fc307f2a8e50fa5a97) ([#5145](https://github.com/yt-dlp/yt-dlp/issues/5145)) by [Grub4K](https://github.com/Grub4K)
- [Fix empty `BaseURL` in MPD](https://github.com/yt-dlp/yt-dlp/commit/47046464faaa3c72465f52c3c6a6191fbfd6b32c) by [pukkandan](https://github.com/pukkandan)
- [Fix format sorting of `channels`](https://github.com/yt-dlp/yt-dlp/commit/7e798d725ed8337c10bd91c0176265a678c61cf1) by [pukkandan](https://github.com/pukkandan)
- [Framework for embed detection](https://github.com/yt-dlp/yt-dlp/commit/8f97a15d1c7ebc10d0b51ce24632ac17b34a5f69) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [pukkandan](https://github.com/pukkandan)
- [Handle `json_ld` with multiple `@type`s](https://github.com/yt-dlp/yt-dlp/commit/f3c0c77304bc0e5614a65c45629de22f067685ac) by [pukkandan](https://github.com/pukkandan)
- [Import `_ALL_CLASSES` lazily](https://github.com/yt-dlp/yt-dlp/commit/560738f34de4df6eaf82290fd503def3f366f878) by [pukkandan](https://github.com/pukkandan)
- [Improve `_generic_title`](https://github.com/yt-dlp/yt-dlp/commit/62b8dac4908bdb340e173bb70048f0f22e825007) by [pukkandan](https://github.com/pukkandan)
- [Improve json+ld extraction](https://github.com/yt-dlp/yt-dlp/commit/0f60ba6e656516ec24d619d20d61249be6296105) by [pukkandan](https://github.com/pukkandan)
- [Let `_extract_format` functions obey `--ignore-no-formats`](https://github.com/yt-dlp/yt-dlp/commit/0b5546c723b9fb212e7e0199dbdaae8b8e0bf206) by [pukkandan](https://github.com/pukkandan)
- [Make search_json able to parse lists](https://github.com/yt-dlp/yt-dlp/commit/8b7fb8b60da78b54a518246b251be3d1829fef38) by [pukkandan](https://github.com/pukkandan)
- [Passthrough `errnote=False` to parsing](https://github.com/yt-dlp/yt-dlp/commit/6edf28081f297c1db98ce982e911c985b679e1a1) by [pukkandan](https://github.com/pukkandan)
- [Recognize `src` attribute from HTML5 media elements](https://github.com/yt-dlp/yt-dlp/commit/222a230871fe4fe63f35c49590379c9a77116819) ([#3899](https://github.com/yt-dlp/yt-dlp/issues/3899)) by [Lesmiscore](https://github.com/Lesmiscore)
- [Support multiple archive ids for one video](https://github.com/yt-dlp/yt-dlp/commit/1e8fe57e5cd0f33f940df87430d75e1230ec5b7a) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [pukkandan](https://github.com/pukkandan)
- cleanup
    - [Reduce direct use of `_downloader`](https://github.com/yt-dlp/yt-dlp/commit/9809740ba5cc5daf53e690d104a37aa6545e53f9) by [pukkandan](https://github.com/pukkandan)
    - [Refactor `_download_...` methods](https://github.com/yt-dlp/yt-dlp/commit/617f658b7ec1193749848c1b7343acab125dbc46) by [pukkandan](https://github.com/pukkandan) (With fixes in [c491002](https://github.com/yt-dlp/yt-dlp/commit/c4910024f3dbb9798554f02d935d0b0604f51182))
- test: [Basic framework for embed tests](https://github.com/yt-dlp/yt-dlp/commit/f2e8dbcc0067fb16b632de1984e622a8e99d9d8f) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [coletdjnz](https://github.com/coletdjnz)
- 0000studio
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/0bea4fd8072c1421ab3a94f0601ddef9df14f133) ([#3959](https://github.com/yt-dlp/yt-dlp/issues/3959)) by [Lesmiscore](https://github.com/Lesmiscore)
- 24tv.ua
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/1e0daeb314f0644eed5cdd638b6cc5452a6bbab5) ([#5121](https://github.com/yt-dlp/yt-dlp/issues/5121)) by [coletdjnz](https://github.com/coletdjnz)
- 91porn
    - [Fix title and comment extraction](https://github.com/yt-dlp/yt-dlp/commit/c085cc2def9862ac8a7619ce8ea5dcc177325719) ([#5932](https://github.com/yt-dlp/yt-dlp/issues/5932)) by [pmitchell86](https://github.com/pmitchell86)
- AbemaTV
    - [Cache user token whenever appropriate](https://github.com/yt-dlp/yt-dlp/commit/a4f16832213d9e29beecf685d6cd09a2f0b48c87) ([#6216](https://github.com/yt-dlp/yt-dlp/issues/6216)) by [Lesmiscore](https://github.com/Lesmiscore)
- AbemaTVTitle
    - [Implement paging](https://github.com/yt-dlp/yt-dlp/commit/bc83b4b06cd2648276c7f075754ace8be22f889a) ([#4376](https://github.com/yt-dlp/yt-dlp/issues/4376)) by [Lesmiscore](https://github.com/Lesmiscore)
- acfun
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/fe588ce8ef2d4719fd931c5a6793d9ff747428f3) ([#4228](https://github.com/yt-dlp/yt-dlp/issues/4228)) by [lockmatrix](https://github.com/lockmatrix)
- adobepass
    - [Add MSO AlticeOne (Optimum TV)](https://github.com/yt-dlp/yt-dlp/commit/0c0b78b273a15f360508f80a2920e39a63b520bc) ([#4875](https://github.com/yt-dlp/yt-dlp/issues/4875)) by [CplPwnies](https://github.com/CplPwnies)
- aenetworks
    - [Add formats parameter](https://github.com/yt-dlp/yt-dlp/commit/1cddfdc52b39f6760a70869632d12577b080b69c) ([#4645](https://github.com/yt-dlp/yt-dlp/issues/4645)) by [jacobtruman](https://github.com/jacobtruman)
- aeon
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c6989aa3ae5d79137cf6e4228220ad620519bcbd) ([#5205](https://github.com/yt-dlp/yt-dlp/issues/5205)) by [DoubleCouponDay](https://github.com/DoubleCouponDay)
- agora
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/78545664bf80086a011494b2010f949b2f182b04) ([#5101](https://github.com/yt-dlp/yt-dlp/issues/5101)) by [selfisekai](https://github.com/selfisekai)
- airtv
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/e318b5b87ab2e04f554c97f2d7b9989f8c24156c) ([#5533](https://github.com/yt-dlp/yt-dlp/issues/5533)) by [HobbyistDev](https://github.com/HobbyistDev)
- aitube
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/a1d9aca3382a83e61d5069a140664a112e6c54e4) ([#5946](https://github.com/yt-dlp/yt-dlp/issues/5946)) by [HobbyistDev](https://github.com/HobbyistDev)
- amazon
    - [Add `AmazonReviews` extractor](https://github.com/yt-dlp/yt-dlp/commit/53006b35ea8b26ff31a96a423ddaa3304d0a124e) ([#5857](https://github.com/yt-dlp/yt-dlp/issues/5857)) by [bashonly](https://github.com/bashonly)
- amazonminitv
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/48652590ec401f4e747a5e51552cdcac20744aa1) ([#3628](https://github.com/yt-dlp/yt-dlp/issues/3628)) by [GautamMKGarg](https://github.com/GautamMKGarg), [nyuszika7h](https://github.com/nyuszika7h)
    - [Cleanup 48652590ec401f4e747a5e51552cdcac20744aa1](https://github.com/yt-dlp/yt-dlp/commit/a9d069f5b8540f15caaf696bc39ce6a969f8b11c) by [pukkandan](https://github.com/pukkandan)
- AmazonStore
    - [Fix JSON extraction](https://github.com/yt-dlp/yt-dlp/commit/7474e4531e5911b04030ee52ff93ca4f2527490d) ([#5111](https://github.com/yt-dlp/yt-dlp/issues/5111)) by [coletdjnz](https://github.com/coletdjnz)
    - [Retry to avoid captcha page](https://github.com/yt-dlp/yt-dlp/commit/3c7a2762343280d0e749acffd0edcf72fa4d0661) ([#4811](https://github.com/yt-dlp/yt-dlp/issues/4811)) by [Lesmiscore](https://github.com/Lesmiscore)
- americastestkitchen
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/c66ed4e2e5b1a904687120afda0003b77d326c22) ([#5343](https://github.com/yt-dlp/yt-dlp/issues/5343)) by [bashonly](https://github.com/bashonly)
- anchorfm
    - [Add episode extractor](https://github.com/yt-dlp/yt-dlp/commit/a4ad59ff2ded208bf33f6fe07299a3449eadccdc) ([#6092](https://github.com/yt-dlp/yt-dlp/issues/6092)) by [bashonly](https://github.com/bashonly), [HobbyistDev](https://github.com/HobbyistDev)
- angel
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/e1bd953f4574a8cc4603fc0d56ea6acc9c64323b) ([#4410](https://github.com/yt-dlp/yt-dlp/issues/4410)) by [AxiosDeminence](https://github.com/AxiosDeminence)
- animelab
    - [Remove extractor](https://github.com/yt-dlp/yt-dlp/commit/84131d035130f40f98b71e43d6e680202c9da4c1) ([#3922](https://github.com/yt-dlp/yt-dlp/issues/3922)) by [gamer191](https://github.com/gamer191)
- animeondemand
    - [Remove extractor](https://github.com/yt-dlp/yt-dlp/commit/a12d03e15dc0d7ea1192dda77c389132a6a4e5d8) ([#4830](https://github.com/yt-dlp/yt-dlp/issues/4830)) by [TokyoBlackHole](https://github.com/TokyoBlackHole)
- anvato
    - [Fix extractor and refactor](https://github.com/yt-dlp/yt-dlp/commit/4a61501db9369c813f913dc491c36951f8b087ad) ([#5074](https://github.com/yt-dlp/yt-dlp/issues/5074)) by [bashonly](https://github.com/bashonly)
- archiveorg
    - [Improve handling of formats](https://github.com/yt-dlp/yt-dlp/commit/871a8929bcc3e8432d5341752dd888e057e5cfae) ([#4461](https://github.com/yt-dlp/yt-dlp/issues/4461)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
- ARD
    - [Add vtt subtitles](https://github.com/yt-dlp/yt-dlp/commit/d61ef7f34395eae33810ec16397f86c54bf06af6) ([#5835](https://github.com/yt-dlp/yt-dlp/issues/5835)) by [CapacitorSet](https://github.com/CapacitorSet)
- arte
    - [Bug fix](https://github.com/yt-dlp/yt-dlp/commit/89e4d86171c7b7c997c77d4714542e0383bf0db0) ([#4769](https://github.com/yt-dlp/yt-dlp/issues/4769)) by [cgrigis](https://github.com/cgrigis)
    - [Fix title extraction](https://github.com/yt-dlp/yt-dlp/commit/f640e42ffa4049aa702f707be8a6c4472af9cbeb) by [pukkandan](https://github.com/pukkandan)
    - [Move to v2 API](https://github.com/yt-dlp/yt-dlp/commit/051d6b450cc014e167ba169bee190fcff3c1a6d4) ([#3302](https://github.com/yt-dlp/yt-dlp/issues/3302)) by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
- ArteTV
    - [Extract chapters](https://github.com/yt-dlp/yt-dlp/commit/15e9e578c04f1fa3f408dc3ec99491cc3f0ba839) ([#5879](https://github.com/yt-dlp/yt-dlp/issues/5879)) by [bashonly](https://github.com/bashonly), [iw0nderhow](https://github.com/iw0nderhow)
    - [Remove duplicate stream urls](https://github.com/yt-dlp/yt-dlp/commit/1534aba8658294913d58accbc6688574c9911585) ([#5047](https://github.com/yt-dlp/yt-dlp/issues/5047)) by [Grub4K](https://github.com/Grub4K)
- atscaleconfevent
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c82a4a8fcef33bdeb68da8149c1f687de148778c) ([#3971](https://github.com/yt-dlp/yt-dlp/issues/3971)) by [Ashish0804](https://github.com/Ashish0804)
- audioboom
    - [Support direct URLs and refactor](https://github.com/yt-dlp/yt-dlp/commit/8dbad2a4394ed68a2d6d48f6b4b2f7176a30906c) ([#4803](https://github.com/yt-dlp/yt-dlp/issues/4803)) by [pukkandan](https://github.com/pukkandan), [tpikonen](https://github.com/tpikonen)
- Audiodraft
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/65493f64e1d8682f7e548f17b064111c075b3b2b) ([#4288](https://github.com/yt-dlp/yt-dlp/issues/4288)) by [Ashish0804](https://github.com/Ashish0804), [fstirlitz](https://github.com/fstirlitz)
- bandcamp
    - [Add `album_artist`](https://github.com/yt-dlp/yt-dlp/commit/a0e526ed4d042c88771cd5669ceb4413d2b8c47f) ([#5537](https://github.com/yt-dlp/yt-dlp/issues/5537)) by [stelcodes](https://github.com/stelcodes)
    - [Extract `uploader_url`](https://github.com/yt-dlp/yt-dlp/commit/2c475e48b54b071a3e59441829b6dec7d5b3c0ac) by [pukkandan](https://github.com/pukkandan)
- bbc
    - [Fix news articles](https://github.com/yt-dlp/yt-dlp/commit/edebb6517088a678e65112be28339b18bbe01b4d) ([#4472](https://github.com/yt-dlp/yt-dlp/issues/4472)) by [ajj8](https://github.com/ajj8)
    - [Support onion domains](https://github.com/yt-dlp/yt-dlp/commit/ed13a772d717c0df4f41fad6010369ad5d545005) ([#5211](https://github.com/yt-dlp/yt-dlp/issues/5211)) by [DoubleCouponDay](https://github.com/DoubleCouponDay)
- beatbump
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/0ef3d470272694533301294e733e96343dab57af) ([#5304](https://github.com/yt-dlp/yt-dlp/issues/5304)) by [Bobscorn](https://github.com/Bobscorn), [pukkandan](https://github.com/pukkandan)
- BerufeTV
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/9d69c4e4b44077cf9138b0d2c4af7ce199492737) ([#4921](https://github.com/yt-dlp/yt-dlp/issues/4921)) by [Fabi019](https://github.com/Fabi019)
- bfmtv
    - [Support `rmc` prefix](https://github.com/yt-dlp/yt-dlp/commit/20266508dd6247dd3cf0e97b9b9f14c3afc046db) ([#6025](https://github.com/yt-dlp/yt-dlp/issues/6025)) by [carusocr](https://github.com/carusocr)
- bigo
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/1275aeb95559e22dc8b404e91d316b1fa6072804) ([#4312](https://github.com/yt-dlp/yt-dlp/issues/4312)) by [Lesmiscore](https://github.com/Lesmiscore)
- bilibili
    - [Add chapters and misc cleanup](https://github.com/yt-dlp/yt-dlp/commit/c90c5b9bddfaa36afd07db676e351571fce102e8) ([#4221](https://github.com/yt-dlp/yt-dlp/issues/4221)) by [lockmatrix](https://github.com/lockmatrix), [pukkandan](https://github.com/pukkandan)
    - [Add space.bilibili extractors](https://github.com/yt-dlp/yt-dlp/commit/2b9d02167fdf2fbe5bd8306144ab45027da263c1) ([#4468](https://github.com/yt-dlp/yt-dlp/issues/4468)) by [lockmatrix](https://github.com/lockmatrix)
    - [Extract `flac` with premium account](https://github.com/yt-dlp/yt-dlp/commit/de49cdbe9d37a66b05bb73292cfba031847386dc) ([#4759](https://github.com/yt-dlp/yt-dlp/issues/4759)) by [jackyyf](https://github.com/jackyyf)
    - [Fix BilibiliIE and Bangumi extractors](https://github.com/yt-dlp/yt-dlp/commit/ad97487606c87878aa06b736a72ffde15056bdd4) ([#4945](https://github.com/yt-dlp/yt-dlp/issues/4945)) by [lockmatrix](https://github.com/lockmatrix), [pukkandan](https://github.com/pukkandan)
    - [Fix `--no-playlist` for anthology](https://github.com/yt-dlp/yt-dlp/commit/f74371a97d67237e055612006602934b910b1275) by [pukkandan](https://github.com/pukkandan)
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/1c226ccdd464c09218a33824aedbcf3aa305a678) ([#5820](https://github.com/yt-dlp/yt-dlp/issues/5820)) by [skbeh](https://github.com/skbeh)
- BiliBiliSearch
    - [Don't sort by date](https://github.com/yt-dlp/yt-dlp/commit/8d1ad6378fb52ce48a957d90bc28127ee986b6f4) by [pukkandan](https://github.com/pukkandan)
    - [Fix infinite loop](https://github.com/yt-dlp/yt-dlp/commit/2d1019542af1f13a9c287969d0f2569570320872) by [pukkandan](https://github.com/pukkandan)
- BilibiliSpace
    - [Fix extractor, better error message](https://github.com/yt-dlp/yt-dlp/commit/12f153a8275bd4c05aee1532b3eb00f1361c4636) ([#5043](https://github.com/yt-dlp/yt-dlp/issues/5043)) by [lockmatrix](https://github.com/lockmatrix)
- biliintl
    - [Add `/media` to `VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/76c3ceccfb3fdec9e5289816bc2447262596fb28) ([#5939](https://github.com/yt-dlp/yt-dlp/issues/5939)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Add fallback to `video_data`](https://github.com/yt-dlp/yt-dlp/commit/d37422f1db3cbdf85638eea42e73883ab1c9df10) ([#5971](https://github.com/yt-dlp/yt-dlp/issues/5971)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Add intro and ending chapters](https://github.com/yt-dlp/yt-dlp/commit/0ba87dd279d3565ed93c559cf7880ad61eb83af8) ([#6018](https://github.com/yt-dlp/yt-dlp/issues/6018)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Fix metadata extraction](https://github.com/yt-dlp/yt-dlp/commit/8072ef2bbd1721e4c79156b422e4fccc1e062853) by [pukkandan](https://github.com/pukkandan)
    - [Fix subtitle extraction](https://github.com/yt-dlp/yt-dlp/commit/dfb855b42da32807ffac243f1e763f480c4d44ba) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Fix subtitle extraction](https://github.com/yt-dlp/yt-dlp/commit/fbb888a3d51d93d502f34dcfff362a4cf55e015a) by [MinePlayersPE](https://github.com/MinePlayersPE)
    - [Support uppercase lang in `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/0831d95c46e0a198957d44262bb251113346a6b4) by [coletdjnz](https://github.com/coletdjnz)
    - series: [Make partial download of series faster](https://github.com/yt-dlp/yt-dlp/commit/26fdfc3704a278acada27cc420d67c6d3f71423b) by [pukkandan](https://github.com/pukkandan)
- BiliIntlSeries
    - [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/be9c0884d7af01f9b658975a98a91d71c420d34f) by [pukkandan](https://github.com/pukkandan)
- BiliLive
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/ca2f6e14e65f0faf92cabff8b7e5b4760363c52e) by [pukkandan](https://github.com/pukkandan)
- bitchute
    - [Better error for geo-restricted videos](https://github.com/yt-dlp/yt-dlp/commit/efdc45a6ea1dad1000d0478928cd4576975b9b3f) ([#5474](https://github.com/yt-dlp/yt-dlp/issues/5474)) by [flashdagger](https://github.com/flashdagger)
    - [Improve `BitChuteChannelIE`](https://github.com/yt-dlp/yt-dlp/commit/c61473c1d617a4d5432248815f22dcb46906acaf) ([#5066](https://github.com/yt-dlp/yt-dlp/issues/5066)) by [flashdagger](https://github.com/flashdagger), [pukkandan](https://github.com/pukkandan)
    - [Mark errors as expected](https://github.com/yt-dlp/yt-dlp/commit/1704c47ba81dfa6de1b57c1c639863aad37390eb) by [pukkandan](https://github.com/pukkandan)
    - [Simplify extractor](https://github.com/yt-dlp/yt-dlp/commit/f72218c1992d1eed446b3236a91e7613cec6039a) ([#5066](https://github.com/yt-dlp/yt-dlp/issues/5066)) by [flashdagger](https://github.com/flashdagger), [pukkandan](https://github.com/pukkandan)
- bongacams
    - [Update `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/573a98d6f0867f9acb909cb3ff3dc9c10f9b2e8b) ([#5104](https://github.com/yt-dlp/yt-dlp/issues/5104)) by [0xGodspeed](https://github.com/0xGodspeed)
- booyah
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/7f5b3cb8b39c8e73f6c45d521059622b1e140b33) ([#4834](https://github.com/yt-dlp/yt-dlp/issues/4834)) by [elyse0](https://github.com/elyse0), [HobbyistDev](https://github.com/HobbyistDev)
- boxcast
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/9acca71237f42a4775008e51fe26e42f0a39c552) ([#5983](https://github.com/yt-dlp/yt-dlp/issues/5983)) by [HobbyistDev](https://github.com/HobbyistDev)
- brightcove
    - [Add `BrightcoveNewBaseIE` and fix embed extraction](https://github.com/yt-dlp/yt-dlp/commit/f5a9e9df0da38a0c3c13f1dd106d5eb585253f0c) ([#5558](https://github.com/yt-dlp/yt-dlp/issues/5558)) by [pukkandan](https://github.com/pukkandan)
- bundesliga
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/f48ab881f6a75fbc61f7d9c132180f7696db95f8) ([#5094](https://github.com/yt-dlp/yt-dlp/issues/5094)) by [Fabi019](https://github.com/Fabi019)
- camsoda
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/8fddc232bfe99eee847a4c4fa57ed7a334ebd62c) ([#5465](https://github.com/yt-dlp/yt-dlp/issues/5465)) by [zulaport](https://github.com/zulaport)
- camtasia
    - [Separate into own extractor](https://github.com/yt-dlp/yt-dlp/commit/5fff2e576f5a36ba253e53880566db932b9b7621) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [coletdjnz](https://github.com/coletdjnz)
- ccc
    - [Extract view_count](https://github.com/yt-dlp/yt-dlp/commit/6e7c9201cdc510ba2fedf976438a748fd7da32b9) ([#3939](https://github.com/yt-dlp/yt-dlp/issues/3939)) by [vkorablin](https://github.com/vkorablin)
- cda
    - [Support premium and misc improvements](https://github.com/yt-dlp/yt-dlp/commit/da8d2de2082ab55f11d76d0aef7e6c3614672b45) ([#5529](https://github.com/yt-dlp/yt-dlp/issues/5529)) by [selfisekai](https://github.com/selfisekai)
- cellebrite
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/cbd4f237b41af8ed6e8d70ed315033a501cfab3f) ([#4333](https://github.com/yt-dlp/yt-dlp/issues/4333)) by [HobbyistDev](https://github.com/HobbyistDev)
- cinetecamilano
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/7c8c63529ec32371a9b8b8cf48ea481ec239761b) ([#5279](https://github.com/yt-dlp/yt-dlp/issues/5279)) by [timendum](https://github.com/timendum)
- ciscowebex
    - [Support password-protected videos](https://github.com/yt-dlp/yt-dlp/commit/a4d6ead30fde0e85eb34859e86c707621e38f8a1) ([#5601](https://github.com/yt-dlp/yt-dlp/issues/5601)) by [damianoamatruda](https://github.com/damianoamatruda)
- cloudflarestream
    - [Fix video_id padding](https://github.com/yt-dlp/yt-dlp/commit/7f71cee020c429983d75a3937cd2efbb797e4d72) ([#4384](https://github.com/yt-dlp/yt-dlp/issues/4384)) by [haobinliang](https://github.com/haobinliang)
- clyp
    - [Support `wav`](https://github.com/yt-dlp/yt-dlp/commit/cc13293c2819b5461be211a9729fd02bb1e2f476) ([#6102](https://github.com/yt-dlp/yt-dlp/issues/6102)) by [qulaz](https://github.com/qulaz)
- crunchyroll
    - [Add intro chapter](https://github.com/yt-dlp/yt-dlp/commit/93abb7406b95793f6872d12979b91d5f336b4f43) ([#6023](https://github.com/yt-dlp/yt-dlp/issues/6023)) by [ByteDream](https://github.com/ByteDream)
    - [Beta is now the only layout](https://github.com/yt-dlp/yt-dlp/commit/cb1553e96601e92765dd8d70d549b8d551191e70) ([#5294](https://github.com/yt-dlp/yt-dlp/issues/5294)) by [tejing1](https://github.com/tejing1)
    - [Better message for premium videos](https://github.com/yt-dlp/yt-dlp/commit/44699d10dc8de9c6a338f4a8e5c63506ec4d2118) by [pukkandan](https://github.com/pukkandan)
    - [Fix incorrect premium-only error](https://github.com/yt-dlp/yt-dlp/commit/c9d14bd22ab31e2a41f9f8061843668a06db583b) by [Grub4K](https://github.com/Grub4K)
    - [Handle missing metadata correctly](https://github.com/yt-dlp/yt-dlp/commit/7d0f6f0c4527aa1c1f99984c5b34d21ebc87228d) ([#4405](https://github.com/yt-dlp/yt-dlp/issues/4405)) by [Burve](https://github.com/Burve), [pukkandan](https://github.com/pukkandan)
    - [Improve _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/56b5b832bfaaab9e3f1a39eeb3e950630383a37a) by [pukkandan](https://github.com/pukkandan)
    - [Improve `_VALID_URL`s](https://github.com/yt-dlp/yt-dlp/commit/5da42f2b9b29e69cff8a2ea22d3cf9c586e470d6) by [pukkandan](https://github.com/pukkandan)
    - beta
        - [Extract timestamp and fix tests](https://github.com/yt-dlp/yt-dlp/commit/b99ba3df096cd9c2973f7cf978c58ccfb3fa2200) ([#4535](https://github.com/yt-dlp/yt-dlp/issues/4535)) by [tejing1](https://github.com/tejing1)
        - [Fix extractor after API change](https://github.com/yt-dlp/yt-dlp/commit/88d62206b41723ba85174bd4d33469089d23334b) ([#3801](https://github.com/yt-dlp/yt-dlp/issues/3801)) by [Burve](https://github.com/Burve), [tejing1](https://github.com/tejing1)
        - [Improve handling of hardsubs](https://github.com/yt-dlp/yt-dlp/commit/dfea94f8f69a8cd06b4781e95a0cd23fb06e6d67) ([#5041](https://github.com/yt-dlp/yt-dlp/issues/5041)) by [Grub4K](https://github.com/Grub4K)
        - [Use anonymous access](https://github.com/yt-dlp/yt-dlp/commit/459262ac97c039a426f51f3fb3a5d780de5b9dca) ([#4704](https://github.com/yt-dlp/yt-dlp/issues/4704)) by [tejing1](https://github.com/tejing1)
        - [Use streams API](https://github.com/yt-dlp/yt-dlp/commit/f62f553d46856aff2e36a0d561ec78a1d28d5b68) ([#4555](https://github.com/yt-dlp/yt-dlp/issues/4555)) by [tejing1](https://github.com/tejing1)
    - show: [Add `language` to entries](https://github.com/yt-dlp/yt-dlp/commit/8a6b1677234c2b4e0d9279cb2eb7475c36523c72) ([#5687](https://github.com/yt-dlp/yt-dlp/issues/5687)) by [Chrissi2812](https://github.com/Chrissi2812)
- curiositystream
    - [Fix auth](https://github.com/yt-dlp/yt-dlp/commit/6b71d186dda5c71b8ff2ec665cbda6f9d4ffb06e) ([#5730](https://github.com/yt-dlp/yt-dlp/issues/5730)) by [mnn](https://github.com/mnn)
- CWTV
    - [Extract thumbnail](https://github.com/yt-dlp/yt-dlp/commit/8d214c484c57ac3eb19043c7dc72e4f24e3018e2) ([#4185](https://github.com/yt-dlp/yt-dlp/issues/4185)) by [ischmidt20](https://github.com/ischmidt20)
- DailyWire
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/695b28afaa73ee542040b912ecf91f98eef8db1e) ([#4084](https://github.com/yt-dlp/yt-dlp/issues/4084)) by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
- detik
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/8f47b39b2700a0a6b9d863b6fda7e4334264d963) ([#4284](https://github.com/yt-dlp/yt-dlp/issues/4284)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Avoid unnecessary extraction](https://github.com/yt-dlp/yt-dlp/commit/1305b659ef2bf3c76851b9400c7ac4a8f100fce2) by [pukkandan](https://github.com/pukkandan)
    - [Generalize extractors](https://github.com/yt-dlp/yt-dlp/commit/c7f540ea1eab69c47ba2a758f9c79297b721cb70) ([#4899](https://github.com/yt-dlp/yt-dlp/issues/4899)) by [coletdjnz](https://github.com/coletdjnz), [HobbyistDev](https://github.com/HobbyistDev)
- deuxm
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/cc1d3bf96b23855e76267a08479a065a0a95bdf3) ([#5388](https://github.com/yt-dlp/yt-dlp/issues/5388)) by [CrankDatSouljaBoy](https://github.com/CrankDatSouljaBoy)
- digitalconcerthall
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/a79cba0c95b8b74d2ca4f7fbf6ffe76e34ed7221) ([#4105](https://github.com/yt-dlp/yt-dlp/issues/4105)) by [ZhymabekRoman](https://github.com/ZhymabekRoman)
- doodstream
    - [Add `wf` domain](https://github.com/yt-dlp/yt-dlp/commit/66c4afd82892a12cfd9174750b6e12dfaa1d0fcb) ([#4648](https://github.com/yt-dlp/yt-dlp/issues/4648)) by [aldoridhoni](https://github.com/aldoridhoni)
    - [Remove extractor](https://github.com/yt-dlp/yt-dlp/commit/ed6bec168dd6af955f4ec0165356ac76b944c537) by [pukkandan](https://github.com/pukkandan)
    - [Support more domains](https://github.com/yt-dlp/yt-dlp/commit/b6cd135ac2640d8817d48f8b289072f056a7010b) ([#4493](https://github.com/yt-dlp/yt-dlp/issues/4493)) by [Galiley](https://github.com/Galiley)
- dplay
    - [Add MotorTrend extractor](https://github.com/yt-dlp/yt-dlp/commit/26bafe70286d19df6bc49733e17ba8b05847a998) ([#4446](https://github.com/yt-dlp/yt-dlp/issues/4446)) by [Sipherdrakon](https://github.com/Sipherdrakon)
    - [Add MotorTrendOnDemand extractor](https://github.com/yt-dlp/yt-dlp/commit/f03940963ed02f0e4a99afaa2673a4329741c420) ([#5151](https://github.com/yt-dlp/yt-dlp/issues/5151)) by [bashonly](https://github.com/bashonly)
    - italy: [Add default authentication](https://github.com/yt-dlp/yt-dlp/commit/292fdad2970362743e8f0cf88cbd2d78edbc1fcd) ([#5056](https://github.com/yt-dlp/yt-dlp/issues/5056)) by [Timendum](https://github.com/Timendum)
- dropbox
    - [Extract the correct `mountComponent`](https://github.com/yt-dlp/yt-dlp/commit/f254d6ccd9afd4f3f84bf6cb897bed55517f8229) by [pukkandan](https://github.com/pukkandan)
- dropout
    - [Login is not mandatory](https://github.com/yt-dlp/yt-dlp/commit/28786529dce173c08c01c85e425e03b9164f75fc) by [pukkandan](https://github.com/pukkandan)
    - [Support cookies and login only as needed](https://github.com/yt-dlp/yt-dlp/commit/34baaced11fc34ab38e39c45d1f6fccc09292404) ([#4075](https://github.com/yt-dlp/yt-dlp/issues/4075)) by [pingiun](https://github.com/pingiun), [pukkandan](https://github.com/pukkandan)
- drtv
    - [Add series extractors](https://github.com/yt-dlp/yt-dlp/commit/ab4cbeff00ac08f142f78a6281aa0c1124a59daa) ([#5644](https://github.com/yt-dlp/yt-dlp/issues/5644)) by [FrederikNS](https://github.com/FrederikNS)
    - [Fix bug in ab4cbef](https://github.com/yt-dlp/yt-dlp/commit/7481998b169b2a52049fc33bff82034d6563ead4) ([#6034](https://github.com/yt-dlp/yt-dlp/issues/6034)) by [bashonly](https://github.com/bashonly)
- duboku
    - [Fix for hostname change](https://github.com/yt-dlp/yt-dlp/commit/5bbe631e048d1a5a3199a6b72337a952894461e3) ([#3891](https://github.com/yt-dlp/yt-dlp/issues/3891)) by [mozbugbox](https://github.com/mozbugbox)
- ebay
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/da880559a6ecbbf374cc9f3378e696b55b9599af) ([#6170](https://github.com/yt-dlp/yt-dlp/issues/6170)) by [JChris246](https://github.com/JChris246)
- embedly
    - [Embedded links may be for other extractors](https://github.com/yt-dlp/yt-dlp/commit/87ebab0615b1bf9b14b478b055e7059d630b4833) by [pukkandan](https://github.com/pukkandan)
    - [Handle vimeo embeds](https://github.com/yt-dlp/yt-dlp/commit/78d25e0b7c2b45597e193c0decb33f4f248502a9) by [pukkandan](https://github.com/pukkandan)
- epoch
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/f8c7ba99845c6d426d32e7f1218a6ecfc8132f45) ([#4772](https://github.com/yt-dlp/yt-dlp/issues/4772)) by [tejasa97](https://github.com/tejasa97)
    - [Support videos without data-trailer](https://github.com/yt-dlp/yt-dlp/commit/7053aa3a48dbdfe8f11b12fa0f442a9bf8b136b1) ([#5387](https://github.com/yt-dlp/yt-dlp/issues/5387)) by [gibson042](https://github.com/gibson042), [pukkandan](https://github.com/pukkandan)
- ertflix
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/1685d46007e01c5437a89e979a39b799373a782d) by [pukkandan](https://github.com/pukkandan)
- espn
    - [Add `WatchESPN` extractor](https://github.com/yt-dlp/yt-dlp/commit/b5770743fe9700ed5c00864a6abd98ea3e4c73ab) ([#2283](https://github.com/yt-dlp/yt-dlp/issues/2283)) by [ischmidt20](https://github.com/ischmidt20), [pukkandan](https://github.com/pukkandan)
    - [Extract duration](https://github.com/yt-dlp/yt-dlp/commit/2eae7d507c1b0749bb198df406720baaa7f70837) ([#4499](https://github.com/yt-dlp/yt-dlp/issues/4499)) by [ischmidt20](https://github.com/ischmidt20)
- ESPNcricinfo
    - [Handle new URL pattern](https://github.com/yt-dlp/yt-dlp/commit/640c934823fc2d1ec77ec932566078014058635f) ([#6321](https://github.com/yt-dlp/yt-dlp/issues/6321)) by [venkata-krishnas](https://github.com/venkata-krishnas)
- europarl
    - [Add EuroParlWebstream Extractor](https://github.com/yt-dlp/yt-dlp/commit/22697a84f6aa5de0b1731c10068aad97704f21fa) ([#5547](https://github.com/yt-dlp/yt-dlp/issues/5547)) by [HobbyistDev](https://github.com/HobbyistDev)
- eurosport
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/11734714c2166a26f0de0c02ff1a0e736d15210f) ([#4613](https://github.com/yt-dlp/yt-dlp/issues/4613)) by [HobbyistDev](https://github.com/HobbyistDev)
- expressen
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/0d6bafbfa725f40444720eeca2291680bb8ab3c3) ([#4006](https://github.com/yt-dlp/yt-dlp/issues/4006)) by [aejdl](https://github.com/aejdl)
- extractors
    - [Use new framework for existing embeds](https://github.com/yt-dlp/yt-dlp/commit/bfd973ece3369c593b5e82a88cc16de80088a73e) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [pukkandan](https://github.com/pukkandan) (With fixes in [43aebb7](https://github.com/yt-dlp/yt-dlp/commit/43aebb7db45c346f0285d4b3bd50227dd3397416), [4080efe](https://github.com/yt-dlp/yt-dlp/commit/4080efeb0127150c7a84cdcc0940e0a552fbdf4f))
- facebook
    - [Add reel support](https://github.com/yt-dlp/yt-dlp/commit/63be30e3e06a11d1243032ef7f444e4e276470d4) ([#4660](https://github.com/yt-dlp/yt-dlp/issues/4660)) by [bashonly](https://github.com/bashonly)
- FIFA
    - [Change API endpoint](https://github.com/yt-dlp/yt-dlp/commit/061a17abd3589555feeafd8f53dd9ad969ff36f1) ([#4577](https://github.com/yt-dlp/yt-dlp/issues/4577)) by [Bricio](https://github.com/Bricio), [yashkc2025](https://github.com/yashkc2025)
    - [Fix Preplay extraction](https://github.com/yt-dlp/yt-dlp/commit/13f930abc0c91d8e50336488e4c55defe97aa588) ([#5921](https://github.com/yt-dlp/yt-dlp/issues/5921)) by [dirkf](https://github.com/dirkf)
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/170a0313863d1148f1fb84612aec0780093aeb77) ([#4272](https://github.com/yt-dlp/yt-dlp/issues/4272)) by [ischmidt20](https://github.com/ischmidt20)
- Fox
    - [Extract thumbnail](https://github.com/yt-dlp/yt-dlp/commit/42a44f01c3f3be9c2af7d91807f0eb85168815e4) ([#5243](https://github.com/yt-dlp/yt-dlp/issues/5243)) by [vitkhab](https://github.com/vitkhab)
- foxnews
    - [Add `FoxNewsVideo` extractor](https://github.com/yt-dlp/yt-dlp/commit/e9ce4e92501fbe8cc0761ec94f16346d8ba65434) by [pukkandan](https://github.com/pukkandan)
    - [Update embed extraction](https://github.com/yt-dlp/yt-dlp/commit/40268a79745695a51846700c6af5d11e9a4e6e2a) ([#4043](https://github.com/yt-dlp/yt-dlp/issues/4043)) by [elyse0](https://github.com/elyse0)
- foxsports
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/7c5e1701f6e948c83a928b6657542036c1d7516e) ([#5719](https://github.com/yt-dlp/yt-dlp/issues/5719)) by [bashonly](https://github.com/bashonly)
- FranceCulture
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/d05460e5fee0dca9ab7463c78c630653fb37dcde) ([#3874](https://github.com/yt-dlp/yt-dlp/issues/3874)) by [aurelg](https://github.com/aurelg), [pukkandan](https://github.com/pukkandan)
- freesound
    - [Workaround invalid URL in webpage](https://github.com/yt-dlp/yt-dlp/commit/9cfdbcbf3f17be51f5b6bb9bb6d880b2f3d67362) ([#6147](https://github.com/yt-dlp/yt-dlp/issues/6147)) by [rebane2001](https://github.com/rebane2001)
- freetv
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/e0a4a3d5bfc631d283fc804a357191ad21beee09) ([#3587](https://github.com/yt-dlp/yt-dlp/issues/3587)) by [elyse0](https://github.com/elyse0)
- fuyin
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/d1bf2e199c180bc4116a8620f32528461d1c5e19) ([#4151](https://github.com/yt-dlp/yt-dlp/issues/4151)) by [HobbyistDev](https://github.com/HobbyistDev)
- generic
    - [Add `fragment_query` extractor arg for DASH and HLS](https://github.com/yt-dlp/yt-dlp/commit/3b021eacefab4a9e43660d72d6d5a49f7ddb025e) ([#5528](https://github.com/yt-dlp/yt-dlp/issues/5528)) by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
    - [Avoid catastrophic backtracking in KVS regex](https://github.com/yt-dlp/yt-dlp/commit/8aa0bd5d10627ece3c1815c01d02fb8bf22847a7) by [bashonly](https://github.com/bashonly)
    - [Decode unicode-escaped embed URLs](https://github.com/yt-dlp/yt-dlp/commit/05997b6e98e638d97d409c65bb5eb86da68f3b64) ([#5919](https://github.com/yt-dlp/yt-dlp/issues/5919)) by [bashonly](https://github.com/bashonly)
    - [Detect manifest links via extension](https://github.com/yt-dlp/yt-dlp/commit/b38cae49e6f4849c8ee2a774bdc3c1c647ae5f0e) by [bashonly](https://github.com/bashonly)
    - [Don't report redirect to https](https://github.com/yt-dlp/yt-dlp/commit/4de88a6a362a6f976ebac5d384a79ca59606ec0a) by [pukkandan](https://github.com/pukkandan)
    - [Don't return JW player without formats](https://github.com/yt-dlp/yt-dlp/commit/4e4982ab5b259027b39a6f9013ec96aefce78aa1) by [pukkandan](https://github.com/pukkandan)
    - [Fix JSON LD manifest extraction](https://github.com/yt-dlp/yt-dlp/commit/ed027fd9d8c0832d6186b3591ca51622e34a072d) ([#5577](https://github.com/yt-dlp/yt-dlp/issues/5577)) by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
    - [Handle basic-auth when checking redirects](https://github.com/yt-dlp/yt-dlp/commit/8e9fe43cd393e69fa49b3d842aa3180c1d105b8f) by [pukkandan](https://github.com/pukkandan)
    - [Pass through referer from json-ld](https://github.com/yt-dlp/yt-dlp/commit/3166e6840c7f7b1ea3984f0e40a892d87e690480) by [pukkandan](https://github.com/pukkandan)
    - [Remove HEAD request](https://github.com/yt-dlp/yt-dlp/commit/61544381781d35276e1e7831456c653107ac8909) by [pukkandan](https://github.com/pukkandan)
    - [Revert e6ae51c123897927eb3c9899923d8ffd31c7f85d](https://github.com/yt-dlp/yt-dlp/commit/21a73e9f39386d4ddfe07a9049cc33c13afed493) by [pukkandan](https://github.com/pukkandan)
    - [Separate embed extraction into own function](https://github.com/yt-dlp/yt-dlp/commit/ade1fa70cbaaaadaa4772e5f0564870cea3167ef) ([#5176](https://github.com/yt-dlp/yt-dlp/issues/5176)) by [pukkandan](https://github.com/pukkandan)
    - [Use `Accept-Encoding: identity` for initial request](https://github.com/yt-dlp/yt-dlp/commit/3e01ce744a981d8f19ae77ec695005e7000f4703) by [pukkandan](https://github.com/pukkandan)
    - quoted-html: [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/6dca2aa66de8a142543d5c8b6ccadd251339648e) ([#5213](https://github.com/yt-dlp/yt-dlp/issues/5213)) by [coletdjnz](https://github.com/coletdjnz)
- genius
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/68a9a450d432f67dc8c2531f053a5fd41b5f341a) ([#5221](https://github.com/yt-dlp/yt-dlp/issues/5221)) by [bashonly](https://github.com/bashonly)
- globo
    - article: [Remove false positives](https://github.com/yt-dlp/yt-dlp/commit/c40f327a1667a1dd04bd5c360e8b85dae93c8b4c) ([#4396](https://github.com/yt-dlp/yt-dlp/issues/4396)) by [Bricio](https://github.com/Bricio)
- Go
    - [Extract timestamp](https://github.com/yt-dlp/yt-dlp/commit/e2884db36a8a66be1aa1bc640d5ae2b830dea310) ([#4186](https://github.com/yt-dlp/yt-dlp/issues/4186)) by [ischmidt20](https://github.com/ischmidt20)
- goodgame
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/3ac7b66047f6bae8bfc9d1a9bfd0b9304b97c296) ([#3686](https://github.com/yt-dlp/yt-dlp/issues/3686)) by [nevack](https://github.com/nevack)
- GoogleDrive
    - [Add folder extractor](https://github.com/yt-dlp/yt-dlp/commit/145c5a83a80536b781fd043016bd27c91c760667) ([#4009](https://github.com/yt-dlp/yt-dlp/issues/4009)) by [evansp](https://github.com/evansp), [pukkandan](https://github.com/pukkandan)
    - [Fix some audio](https://github.com/yt-dlp/yt-dlp/commit/4d248e29d20d983ededab0b03d4fe69dff9eb4ed) by [pukkandan](https://github.com/pukkandan)
- GoPlay
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/fada8272b6c86ec43f0ccdeaa7bd29baecb4ba2d) ([#3412](https://github.com/yt-dlp/yt-dlp/issues/3412)) by [basrieter](https://github.com/basrieter), [CNugteren](https://github.com/CNugteren), [jeroenj](https://github.com/jeroenj)
    - [Use new API](https://github.com/yt-dlp/yt-dlp/commit/d27bde98832e3b7ffb39f3cf6346011b97bb3bc3) ([#6151](https://github.com/yt-dlp/yt-dlp/issues/6151)) by [jeroenj](https://github.com/jeroenj)
- gronkh
    - [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/0d95d8b00ad1bf879ed61f4e588753ef87ccd061) ([#5628](https://github.com/yt-dlp/yt-dlp/issues/5628)) by [muddi900](https://github.com/muddi900)
- harpodeon
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/e251986cbe7c62a7bef02a1a32bae21dff25565e) ([#4540](https://github.com/yt-dlp/yt-dlp/issues/4540)) by [eren-kemer](https://github.com/eren-kemer)
- heise
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/0ca0f88121db5a1e9c223077af1b78c62d5ead6d) ([#5029](https://github.com/yt-dlp/yt-dlp/issues/5029)) by [coletdjnz](https://github.com/coletdjnz)
- hidive
    - [Fix cookie login when netrc is also given](https://github.com/yt-dlp/yt-dlp/commit/2c646fe42cc3a9eba21ec5b96bb2949b9bd0a7ee) ([#4447](https://github.com/yt-dlp/yt-dlp/issues/4447)) by [winterbird-code](https://github.com/winterbird-code)
    - [Fix subtitles and age-restriction](https://github.com/yt-dlp/yt-dlp/commit/7708df8da05c94270b43e0630e4e20f6d2d62c55) ([#5828](https://github.com/yt-dlp/yt-dlp/issues/5828)) by [chexxor](https://github.com/chexxor)
- holodex
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/98a60600b22959ff9e644084c0b67672aaf6fbf6) ([#4434](https://github.com/yt-dlp/yt-dlp/issues/4434)) by [pukkandan](https://github.com/pukkandan), [sqrtNOT](https://github.com/sqrtNOT)
    - [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/1d77d8ce07d21850cac2be6fcffea3311234bc16) ([#4948](https://github.com/yt-dlp/yt-dlp/issues/4948)) by [LiviaMedeiros](https://github.com/LiviaMedeiros)
- hotstar
    - [Add season support](https://github.com/yt-dlp/yt-dlp/commit/db6fa6960caa1ac3c85f5e77ef9eb95f8eda8cb3) ([#5479](https://github.com/yt-dlp/yt-dlp/issues/5479)) by [m4tu4g](https://github.com/m4tu4g)
    - [Improve format metadata](https://github.com/yt-dlp/yt-dlp/commit/e74a3c6dcc30ba16455749c3c5dbb9477961c175) by [pukkandan](https://github.com/pukkandan)
    - [Refactor v1 API calls](https://github.com/yt-dlp/yt-dlp/commit/fad689c7b61b8afd1a18de167ab0a74105b98c47) by [pukkandan](https://github.com/pukkandan)
- hrfensehen
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/8a04054647d40037499e446cd6c1099cdd46f4c8) ([#5096](https://github.com/yt-dlp/yt-dlp/issues/5096)) by [snapdgn](https://github.com/snapdgn)
- html5
    - [Separate into own extractor](https://github.com/yt-dlp/yt-dlp/commit/f14a2d838240e9e75fe52d4e381156064e90674c) ([#4307](https://github.com/yt-dlp/yt-dlp/issues/4307)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
- hungama
    - [Add subtitle](https://github.com/yt-dlp/yt-dlp/commit/1c09783f7ad6653001cb1788cbc6de635d44a4c4) ([#4856](https://github.com/yt-dlp/yt-dlp/issues/4856)) by [GautamMKGarg](https://github.com/GautamMKGarg), [pukkandan](https://github.com/pukkandan)
- huya
    - [Fix stream extraction](https://github.com/yt-dlp/yt-dlp/commit/5135ed3d4a87b3c03902aec68b60b40855b12863) ([#4798](https://github.com/yt-dlp/yt-dlp/issues/4798)) by [ohaiibuzzle](https://github.com/ohaiibuzzle)
    - [Support HD streams](https://github.com/yt-dlp/yt-dlp/commit/fbbb5508ea98ed8709847f5ecced7d70ff05e0ee) ([#6172](https://github.com/yt-dlp/yt-dlp/issues/6172)) by [felixonmars](https://github.com/felixonmars)
- hypergryph
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/31c279a2a2c2ef402a9e6dad9992b310d16439a6) ([#6094](https://github.com/yt-dlp/yt-dlp/issues/6094)) by [bashonly](https://github.com/bashonly), [HobbyistDev](https://github.com/HobbyistDev)
- hytale
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/2f1b7afe328267a95cd11bbab3cf80fecc2678a0) ([#4326](https://github.com/yt-dlp/yt-dlp/issues/4326)) by [llamasblade](https://github.com/llamasblade), [pukkandan](https://github.com/pukkandan)
- iltalehti
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/a83333c4328591c279a27dd0ec4c7c5addcc411f) ([#5117](https://github.com/yt-dlp/yt-dlp/issues/5117)) by [tpikonen](https://github.com/tpikonen)
- ina
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/79c318937bd3d2bdd348b94465101925b146d14d) ([#3807](https://github.com/yt-dlp/yt-dlp/issues/3807)) by [elyse0](https://github.com/elyse0)
    - [Improve extractor](https://github.com/yt-dlp/yt-dlp/commit/db5f24820426323f797da206fa8fa1e5b5d7ffe1) ([#4487](https://github.com/yt-dlp/yt-dlp/issues/4487)) by [elyse0](https://github.com/elyse0)
- instagram
    - [Extract more metadata](https://github.com/yt-dlp/yt-dlp/commit/2e7675489f4323c17c8de1e1fd264365c2c36e26) ([#4708](https://github.com/yt-dlp/yt-dlp/issues/4708)) by [pritam20ps05](https://github.com/pritam20ps05)
    - [Fix extraction](https://github.com/yt-dlp/yt-dlp/commit/7d3b98be4c4567b985ba7d7b17057e930457edc9) ([#4696](https://github.com/yt-dlp/yt-dlp/issues/4696)) by [bashonly](https://github.com/bashonly), [pritam20ps05](https://github.com/pritam20ps05) (With fixes in [8a3da4c](https://github.com/yt-dlp/yt-dlp/commit/8a3da4c68c1bf50ba69af10ea7855e2f7a2b38b4) by [bashonly](https://github.com/bashonly))
    - [Fix post/story extractors](https://github.com/yt-dlp/yt-dlp/commit/e3e606de12ea138825754290542559b888f72bb5) ([#4074](https://github.com/yt-dlp/yt-dlp/issues/4074)) by [pritam20ps05](https://github.com/pritam20ps05), [pukkandan](https://github.com/pukkandan)
- iprima
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/9fddc12ab022a31754e0eaa358fc4e1dfa974587) ([#6291](https://github.com/yt-dlp/yt-dlp/issues/6291)) by [std-move](https://github.com/std-move)
    - [Make json+ld non-fatal](https://github.com/yt-dlp/yt-dlp/commit/2530b68d4476fe6cb4b25897b906cbb1774ca7c9) by [bashonly](https://github.com/bashonly)
- iq
    - [Increase phantomjs timeout](https://github.com/yt-dlp/yt-dlp/commit/d51b2816e33860f3e2a86bda431e31e48cb2e020) by [pukkandan](https://github.com/pukkandan)
    - [Set language correctly for Korean subtitles](https://github.com/yt-dlp/yt-dlp/commit/385f7f38957e21701593ff1229295bf4ca00eba0) by [pukkandan](https://github.com/pukkandan)
- iqiyi
    - [Fix `Iq` JS regex](https://github.com/yt-dlp/yt-dlp/commit/d7f98714696a4c9691ed28fb9b63395b9227646a) ([#5922](https://github.com/yt-dlp/yt-dlp/issues/5922)) by [bashonly](https://github.com/bashonly)
- IslamChannel
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/e0992d555879b07ac7622dfac1f88f9e76e32923) ([#4779](https://github.com/yt-dlp/yt-dlp/issues/4779)) by [Lesmiscore](https://github.com/Lesmiscore)
- IsraelNationalNews
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/0d887f273a0aa28e7aea3780663b7faca44440b6) ([#5089](https://github.com/yt-dlp/yt-dlp/issues/5089)) by [Bobscorn](https://github.com/Bobscorn)
- iwara
    - user: [Make paging better](https://github.com/yt-dlp/yt-dlp/commit/661e7253a2e0482b5f79755915dca6990eb8e8cf) ([#3901](https://github.com/yt-dlp/yt-dlp/issues/3901)) by [Lesmiscore](https://github.com/Lesmiscore)
- ixigua
    - [Add Extractor](https://github.com/yt-dlp/yt-dlp/commit/697ebe4d31e7b82aae823bfcab89c0c042bc2272) ([#3953](https://github.com/yt-dlp/yt-dlp/issues/3953)) by [HobbyistDev](https://github.com/HobbyistDev)
- japandiet
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/682b4524bfb2ce18eada6fbddd2d5541d3cb5e88) ([#5368](https://github.com/yt-dlp/yt-dlp/issues/5368)) by [Lesmiscore](https://github.com/Lesmiscore)
- joj
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/1a3cd8ec35f05bf016123f9ea456d28d0e86302a) ([#5934](https://github.com/yt-dlp/yt-dlp/issues/5934)) by [OndrejBakan](https://github.com/OndrejBakan), [pukkandan](https://github.com/pukkandan)
- JWPlatform
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/d3a3d7f0cc27ca78aeb807b27c7ebee88ff3161e) ([#5112](https://github.com/yt-dlp/yt-dlp/issues/5112)) by [coletdjnz](https://github.com/coletdjnz)
    - [Look for `data-video-jw-id`](https://github.com/yt-dlp/yt-dlp/commit/55baa67c7c7e10c4ef84f68460fa5561ab67c642) by [pukkandan](https://github.com/pukkandan)
- kanal2
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/9d52bf65ff38386a70493ce152f0883476b0709b) ([#5575](https://github.com/yt-dlp/yt-dlp/issues/5575)) by [bashonly](https://github.com/bashonly), [glensc](https://github.com/glensc), [pukkandan](https://github.com/pukkandan)
- kankanews
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/074b2fae9076221faaa8697381428131ad968dc9) ([#5729](https://github.com/yt-dlp/yt-dlp/issues/5729)) by [synthpop123](https://github.com/synthpop123)
- kick
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c1edb853b0a0cc69ea08337c0c5aee669b26d3d2) ([#5736](https://github.com/yt-dlp/yt-dlp/issues/5736)) by [bashonly](https://github.com/bashonly)
- kicker.de
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c27eaf8920c8e2ca063cbda1dc605078a41dec9d) ([#4073](https://github.com/yt-dlp/yt-dlp/issues/4073)) by [HobbyistDev](https://github.com/HobbyistDev)
- kompas
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/d380fc161487ef2e14b204f22e13e16e1a6ceb64) ([#4562](https://github.com/yt-dlp/yt-dlp/issues/4562)) by [HobbyistDev](https://github.com/HobbyistDev)
- la7
    - [Improve extractor](https://github.com/yt-dlp/yt-dlp/commit/72f96c55662c688a15ed00ffa661546156f7e461) ([#5538](https://github.com/yt-dlp/yt-dlp/issues/5538)) by [nixxo](https://github.com/nixxo)
- lbry
    - [Authenticate with cookies](https://github.com/yt-dlp/yt-dlp/commit/59a0c35865124fa2e85d6ed0e01b61a53a6b1446) ([#5435](https://github.com/yt-dlp/yt-dlp/issues/5435)) by [flashdagger](https://github.com/flashdagger)
    - [Update livestream API](https://github.com/yt-dlp/yt-dlp/commit/9fde8a6b125466419745bfc2afed1f34f9821b3f) ([#4042](https://github.com/yt-dlp/yt-dlp/issues/4042)) by [flashdagger](https://github.com/flashdagger)
- liputan6
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/63e66cd0ad2d96b53fdd77a40e19b46755c7219a) ([#4304](https://github.com/yt-dlp/yt-dlp/issues/4304)) by [HobbyistDev](https://github.com/HobbyistDev)
- listennotes
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/0d2a0ecac3d721b4b01ebc2f00f922740961e515) ([#5310](https://github.com/yt-dlp/yt-dlp/issues/5310)) by [lksj](https://github.com/lksj), [pukkandan](https://github.com/pukkandan)
- livestreamfails
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/844086505f7d27bd17eae20cd21a8656a2137ebd) ([#4204](https://github.com/yt-dlp/yt-dlp/issues/4204)) by [nomevi](https://github.com/nomevi)
    - [Support posts](https://github.com/yt-dlp/yt-dlp/commit/bf2e1ec67a5cdaa9039e91cd39c1f670649068a8) ([#5139](https://github.com/yt-dlp/yt-dlp/issues/5139)) by [invertico](https://github.com/invertico)
- malltv
    - [Fix video_id extraction](https://github.com/yt-dlp/yt-dlp/commit/7e378287c4502d82aedb5272b8e9d5f6c1681fad) ([#4883](https://github.com/yt-dlp/yt-dlp/issues/4883)) by [HobbyistDev](https://github.com/HobbyistDev)
- MangoTV
    - [Fix subtitle languages](https://github.com/yt-dlp/yt-dlp/commit/1765c6039e131744a84180ba10a7a9c87565421b) by [pukkandan](https://github.com/pukkandan)
- medaltv
    - [Fix extraction](https://github.com/yt-dlp/yt-dlp/commit/07275b708b4f46c3b3fc9ea941a842fb287cad02) ([#4739](https://github.com/yt-dlp/yt-dlp/issues/4739)) by [xenova](https://github.com/xenova)
- mediaset
    - [Better embed detection and error messages](https://github.com/yt-dlp/yt-dlp/commit/10dc85924a74ae69bcf3170c37b351036eacca58) ([#5664](https://github.com/yt-dlp/yt-dlp/issues/5664)) by [nixxo](https://github.com/nixxo)
    - [Fix embed extraction](https://github.com/yt-dlp/yt-dlp/commit/b86ca447ce0dc7b41e5314a7bb566cfa4d5a3660) by [pukkandan](https://github.com/pukkandan)
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/8102a5991babd17707b6b6d39be942382c719d8c) by [pukkandan](https://github.com/pukkandan)
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/e08f72e6759fb6b1102521f0bdb9457038ef7c06) by [pukkandan](https://github.com/pukkandan)
- mediastream
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/3d79ebc8b7e2b1fe3be8cbd0957b00ef29f8647a) ([#5640](https://github.com/yt-dlp/yt-dlp/issues/5640)) by [elyse0](https://github.com/elyse0), [HobbyistDev](https://github.com/HobbyistDev)
    - [Improve WinSports support](https://github.com/yt-dlp/yt-dlp/commit/2d5a8c5db2bd4ff1c2e45e00cd890a10f8ffca9e) ([#6401](https://github.com/yt-dlp/yt-dlp/issues/6401)) by [bashonly](https://github.com/bashonly)
- mediaworksnzvod
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/aa824dd10bb645784e2fbf1470e27d3723322fcb) ([#4817](https://github.com/yt-dlp/yt-dlp/issues/4817)) by [coletdjnz](https://github.com/coletdjnz)
- MicrosoftEmbed
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/177662e0f24bfd54e57b87698739d7a518321bac) ([#5082](https://github.com/yt-dlp/yt-dlp/issues/5082)) by [DoubleCouponDay](https://github.com/DoubleCouponDay)
- MirrorCoUK
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/7a2e40dd48a351998ed89241829e80b22e3ff30d) ([#3999](https://github.com/yt-dlp/yt-dlp/issues/3999)) by [LunarFang416](https://github.com/LunarFang416), [pukkandan](https://github.com/pukkandan)
- mixch
    - [Support `--wait-for-video`](https://github.com/yt-dlp/yt-dlp/commit/9012d20b23b01827c8d75b460da22485c5cc80ef) by [pukkandan](https://github.com/pukkandan) (With fixes in [4af47a0](https://github.com/yt-dlp/yt-dlp/commit/4af47a00038dfbe6a243119e499f2e876e0f2766))
- mixcloud
    - [All formats are audio-only](https://github.com/yt-dlp/yt-dlp/commit/13db4e7b9e3932595c6b78df47ab4a0382f031f8) by [pukkandan](https://github.com/pukkandan)
- mlb
    - [Add `MLBArticle` extractor](https://github.com/yt-dlp/yt-dlp/commit/e091fb92dab691be2ba54644e2dc6125a3a6a7cd) ([#4832](https://github.com/yt-dlp/yt-dlp/issues/4832)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [New extractor](https://github.com/yt-dlp/yt-dlp/commit/e183bb8c9b12a3d600b570dc1a0ec064df3a24f2) ([#4586](https://github.com/yt-dlp/yt-dlp/issues/4586)) by [ischmidt20](https://github.com/ischmidt20)
- MLBTV
    - [Detect live streams](https://github.com/yt-dlp/yt-dlp/commit/1015ceeeaf847bce88b60fe20d08a09ab8ce7d47) by [pukkandan](https://github.com/pukkandan)
- mocha
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/65ea4cba293d283f1d03b48208fb07e7e2ae35e2) ([#4213](https://github.com/yt-dlp/yt-dlp/issues/4213)) by [HobbyistDev](https://github.com/HobbyistDev)
- motorsport
    - [Support native embeds](https://github.com/yt-dlp/yt-dlp/commit/5469a4ab117448c77ebd660cedd012ec2975d289) by [pukkandan](https://github.com/pukkandan)
- moviepilot
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/c62e64cf0122e52fa2175dd1b004ca6b8e1d82af) ([#5954](https://github.com/yt-dlp/yt-dlp/issues/5954)) by [panatexxa](https://github.com/panatexxa)
- moview
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/7695f5a0a758477608c68492fc00144cdad1c3bc) ([#4607](https://github.com/yt-dlp/yt-dlp/issues/4607)) by [HobbyistDev](https://github.com/HobbyistDev)
- Mxplayer
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/576faf00b24963d4ab9a1a23c1ab243c13d9ce16) ([#4966](https://github.com/yt-dlp/yt-dlp/issues/4966)) by [itachi-19](https://github.com/itachi-19)
    - [Improve extractor](https://github.com/yt-dlp/yt-dlp/commit/9b383177c99185d66efb5dd1c1bee2eb025a6386) ([#5303](https://github.com/yt-dlp/yt-dlp/issues/5303)) by [m4tu4g](https://github.com/m4tu4g)
- naver
    - [Add `navernow` extractor](https://github.com/yt-dlp/yt-dlp/commit/14c3a980492103d080908c1285dd59b978f11f71) ([#3866](https://github.com/yt-dlp/yt-dlp/issues/3866)) by [ping](https://github.com/ping)
    - [Improve `_VALID_URL` for `NaverNowIE`](https://github.com/yt-dlp/yt-dlp/commit/d761dfd059ded109b4feef7315bd84f7d47c6bd7) ([#5620](https://github.com/yt-dlp/yt-dlp/issues/5620)) by [bashonly](https://github.com/bashonly)
    - [Treat fan subtitles as separate language](https://github.com/yt-dlp/yt-dlp/commit/c0caa805157fb315d4b24ea4e1f3eef0210c2096) by [pukkandan](https://github.com/pukkandan)
- NaverNow
    - [Change endpoint](https://github.com/yt-dlp/yt-dlp/commit/bfbb5a1bb124cfce2805224ee1467ba799c8a11e) ([#4457](https://github.com/yt-dlp/yt-dlp/issues/4457)) by [ping](https://github.com/ping)
- nbc
    - [Add NBCStations extractor](https://github.com/yt-dlp/yt-dlp/commit/11398b922c0469e4143f72951d3c9c55587ef39d) ([#5077](https://github.com/yt-dlp/yt-dlp/issues/5077)) by [bashonly](https://github.com/bashonly)
    - [Fix XML parsing](https://github.com/yt-dlp/yt-dlp/commit/176a068cde4f2d9dfa0336168caead0b1edcb8ac) by [bashonly](https://github.com/bashonly)
    - [Fix `NBC` and `NBCStations` extractors](https://github.com/yt-dlp/yt-dlp/commit/cb73b8460c3ce6d37ab651a4e44bb23b10056154) ([#6033](https://github.com/yt-dlp/yt-dlp/issues/6033)) by [bashonly](https://github.com/bashonly)
    - [Update graphql query](https://github.com/yt-dlp/yt-dlp/commit/c3366fdfd000a25fd405737b75b47324a6e3eca5) ([#5952](https://github.com/yt-dlp/yt-dlp/issues/5952)) by [jacobtruman](https://github.com/jacobtruman)
- nebula
    - [Add nebula.tv](https://github.com/yt-dlp/yt-dlp/commit/4cca2eb1bf8bb830df15cbcda21a93fe2392573a) ([#4918](https://github.com/yt-dlp/yt-dlp/issues/4918)) by [tannertechnology](https://github.com/tannertechnology)
    - [Remove broken cookie support](https://github.com/yt-dlp/yt-dlp/commit/d50ea3ce5abc3b0defc0e5d1e22b22ce9b01b07b) ([#5979](https://github.com/yt-dlp/yt-dlp/issues/5979)) by [hheimbuerger](https://github.com/hheimbuerger)
- netverse
    - [Add `NetverseSearch` extractor](https://github.com/yt-dlp/yt-dlp/commit/153e88a75151a51cc2a2fbf02d62f66fc09b29d9) ([#5838](https://github.com/yt-dlp/yt-dlp/issues/5838)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/60ba603ab5c720c1fa09cdeabb5087ae607027ae) ([#3854](https://github.com/yt-dlp/yt-dlp/issues/3854)) by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
    - [Extract comments](https://github.com/yt-dlp/yt-dlp/commit/f0f3fa028bc54921c793de2e48a05fef5227fee5) ([#5568](https://github.com/yt-dlp/yt-dlp/issues/5568)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Improve playlist extractor](https://github.com/yt-dlp/yt-dlp/commit/306770819e0788bf1670b66b3c6059419b850346) ([#3854](https://github.com/yt-dlp/yt-dlp/issues/3854)) by [HobbyistDev](https://github.com/HobbyistDev)
- newspicks
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/bfbecd1174a9e2ee08117352c26e664d36f1cc17) ([#4725](https://github.com/yt-dlp/yt-dlp/issues/4725)) by [Lesmiscore](https://github.com/Lesmiscore)
- nfl
    - [Add `NFLPlus` extractors](https://github.com/yt-dlp/yt-dlp/commit/8b37c58f8b5494504acdb5ebe3f8bbd26230f725) ([#6222](https://github.com/yt-dlp/yt-dlp/issues/6222)) by [bashonly](https://github.com/bashonly)
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/dd4411aac2ef72edb170efb38d19b13b82271cc4) ([#5130](https://github.com/yt-dlp/yt-dlp/issues/5130)) by [bashonly](https://github.com/bashonly)
- niconico
    - [Add support for like history](https://github.com/yt-dlp/yt-dlp/commit/3b161265add30613bde2e46fca214fe94d09e651) ([#5705](https://github.com/yt-dlp/yt-dlp/issues/5705)) by [Matumo](https://github.com/Matumo), [pukkandan](https://github.com/pukkandan)
    - [Always use HTTPS for requests](https://github.com/yt-dlp/yt-dlp/commit/c7e4ab278a19e0d4e0eb9626660a4634df964364) by [pukkandan](https://github.com/pukkandan)
    - series: [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/ac05fb933812647a598c660ec2a5bb9ff91af3b1) ([#3935](https://github.com/yt-dlp/yt-dlp/issues/3935)) by [sqrtNOT](https://github.com/sqrtNOT)
- ninegag
    - [Extract uploader](https://github.com/yt-dlp/yt-dlp/commit/298d9c0e891b1a0fbc3ec6d3674ff6fbc550d6ec) ([#4597](https://github.com/yt-dlp/yt-dlp/issues/4597)) by [DjesonPV](https://github.com/DjesonPV)
- nitter
    - [Update instance list](https://github.com/yt-dlp/yt-dlp/commit/a9189510baadf0dccd2d4d363bc6f3a441128bb0) ([#6236](https://github.com/yt-dlp/yt-dlp/issues/6236)) by [OIRNOIR](https://github.com/OIRNOIR)
- noice
    - [Add NoicePodcast extractor](https://github.com/yt-dlp/yt-dlp/commit/28b8f57b4b2a2e1bd1fbe68ae1ab2c44fdd51992) ([#5621](https://github.com/yt-dlp/yt-dlp/issues/5621)) by [HobbyistDev](https://github.com/HobbyistDev)
- nos.nl
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/866f0373445472ce7ff70da3572b2f178dcece85) ([#4822](https://github.com/yt-dlp/yt-dlp/issues/4822)) by [HobbyistDev](https://github.com/HobbyistDev)
- nosnl
    - [Add support for /video](https://github.com/yt-dlp/yt-dlp/commit/3ac54764301a0e97bf0d2eeb0c32d45a7e03d1f7) ([#5590](https://github.com/yt-dlp/yt-dlp/issues/5590)) by [HobbyistDev](https://github.com/HobbyistDev)
- NovaPlay
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/aeaf905e22614812e29c652a8140feaae08ce279) ([#4415](https://github.com/yt-dlp/yt-dlp/issues/4415)) by [Bojidarist](https://github.com/Bojidarist)
- npo
    - [Fix extractor and add HD support](https://github.com/yt-dlp/yt-dlp/commit/cc2389c8ac72a514d4e002a0f6ca5a7d65c7eff0) ([#6155](https://github.com/yt-dlp/yt-dlp/issues/6155)) by [seproDev](https://github.com/seproDev)
- npr
    - [Implement e50c3500b43d80e4492569c4b4523c4379c6fbb2 differently](https://github.com/yt-dlp/yt-dlp/commit/0c36dc00d7b9f43238bacb0e03730f31117d0b38) by [pukkandan](https://github.com/pukkandan)
    - [Use stream url from json-ld](https://github.com/yt-dlp/yt-dlp/commit/e50c3500b43d80e4492569c4b4523c4379c6fbb2) ([#3455](https://github.com/yt-dlp/yt-dlp/issues/3455)) by [r5d](https://github.com/r5d)
- ntvru
    - [Extract HLS and DASH formats](https://github.com/yt-dlp/yt-dlp/commit/77d6d136468d0c23c8e79bc937898747804f585a) ([#6403](https://github.com/yt-dlp/yt-dlp/issues/6403)) by [bashonly](https://github.com/bashonly)
- nzherald
    - [Support new video embed](https://github.com/yt-dlp/yt-dlp/commit/3f5c216969165c4a0583a4795e4d15325dc009d4) ([#5493](https://github.com/yt-dlp/yt-dlp/issues/5493)) by [coletdjnz](https://github.com/coletdjnz)
- NZOnScreen
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/d3bb187f01e1e30db05e639fc23a2e1935d777fe) ([#6208](https://github.com/yt-dlp/yt-dlp/issues/6208)) by [gregsadetsky](https://github.com/gregsadetsky), [pukkandan](https://github.com/pukkandan)
- odkmedia
    - [Add `OnDemandChinaEpisodeIE`](https://github.com/yt-dlp/yt-dlp/commit/10fd9e6ee833c88edf6c633f864f42843a708d32) ([#6116](https://github.com/yt-dlp/yt-dlp/issues/6116)) by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
- odnoklassniki
    - [Extract subtitles](https://github.com/yt-dlp/yt-dlp/commit/b23b503e22ff577d23920e877ee73da478bb4c6f) ([#5920](https://github.com/yt-dlp/yt-dlp/issues/5920)) by [bashonly](https://github.com/bashonly)
    - [Support boosty.to embeds](https://github.com/yt-dlp/yt-dlp/commit/8196182a12ca2358c09903a9c4abd9c06e3f8e95) ([#5105](https://github.com/yt-dlp/yt-dlp/issues/5105)) by [Lesmiscore](https://github.com/Lesmiscore), [megapro17](https://github.com/megapro17), [pukkandan](https://github.com/pukkandan)
- oftv
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/0d113603ac2ccc869eb1d1b7419caed77f5f5d8a) ([#5134](https://github.com/yt-dlp/yt-dlp/issues/5134)) by [DoubleCouponDay](https://github.com/DoubleCouponDay)
- ondemandkorea
    - [Update `jw_config` regex](https://github.com/yt-dlp/yt-dlp/commit/10e2eb4f81d3c9ef14d59a775428bbef96f22709) ([#5040](https://github.com/yt-dlp/yt-dlp/issues/5040)) by [julien-hadleyjack](https://github.com/julien-hadleyjack)
- onenewsnz
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/34859e4b32a7c2c74a54c6734678e8513885da43) ([#5088](https://github.com/yt-dlp/yt-dlp/issues/5088)) by [coletdjnz](https://github.com/coletdjnz)
- oneplace
    - [Add OnePlacePodcast extractor](https://github.com/yt-dlp/yt-dlp/commit/81388c0954a07fbfeab09831ce350d9f91de1cdd) ([#5549](https://github.com/yt-dlp/yt-dlp/issues/5549)) by [HobbyistDev](https://github.com/HobbyistDev)
- orf
    - radio: [Rewrite extractors](https://github.com/yt-dlp/yt-dlp/commit/5770293d25708f57c12b496c5a2a1f1b3abb37ee) by [pukkandan](https://github.com/pukkandan)
- paramountplus
    - [Better DRM detection](https://github.com/yt-dlp/yt-dlp/commit/8671f995cc5296f1bc9f68afc886353b5a9e40aa) ([#5126](https://github.com/yt-dlp/yt-dlp/issues/5126)) by [bashonly](https://github.com/bashonly)
    - [Update API token](https://github.com/yt-dlp/yt-dlp/commit/3639df54c3298e35b5ae2a96a25bc4d3c38950d0) ([#5285](https://github.com/yt-dlp/yt-dlp/issues/5285)) by [bashonly](https://github.com/bashonly)
- parler
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/43cf982ac353c6e257c4d8fadb02c20491a007fb) ([#4616](https://github.com/yt-dlp/yt-dlp/issues/4616)) by [palewire](https://github.com/palewire)
- patreon
    - [Fix and improve extractors](https://github.com/yt-dlp/yt-dlp/commit/4f08e586553755ab61f64a5ef9b14780d91559a7) ([#4398](https://github.com/yt-dlp/yt-dlp/issues/4398)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Sort formats](https://github.com/yt-dlp/yt-dlp/commit/b27bc13af6a2a96f66f5209151dd2965a7c514fe) by [pukkandan](https://github.com/pukkandan)
- philharmoniedeparis
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/956f1cf80540b5e7047b4064a8f7bd459082a8cf) ([#4367](https://github.com/yt-dlp/yt-dlp/issues/4367)) by [sqrtNOT](https://github.com/sqrtNOT)
- pinterest
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/f549b18512570d0c000179df9147415e4eba1649) ([#5739](https://github.com/yt-dlp/yt-dlp/issues/5739)) by [bashonly](https://github.com/bashonly)
- playsuisse
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/ee164987c731aa2dccdc035b196795666e860ee0) ([#845](https://github.com/yt-dlp/yt-dlp/issues/845)) by [pukkandan](https://github.com/pukkandan), [sbor23](https://github.com/sbor23)
- plutotv
    - [Fix videos with non-zero start](https://github.com/yt-dlp/yt-dlp/commit/42ec478fc4abe4131a0908881673a19aa750bc97) ([#5745](https://github.com/yt-dlp/yt-dlp/issues/5745)) by [digitall](https://github.com/digitall)
- podbayfm
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/2c98d998181c81ee49908be03c031204fd66d03d) ([#4971](https://github.com/yt-dlp/yt-dlp/issues/4971)) by [schnusch](https://github.com/schnusch)
- Podchaser
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/4bf72cc1c96374cda5035eedda2e70d81c38b5d8) ([#3665](https://github.com/yt-dlp/yt-dlp/issues/3665)) by [pukkandan](https://github.com/pukkandan)
- PokemonSoundLibrary
    - [Remove extractor](https://github.com/yt-dlp/yt-dlp/commit/1cd6cba306574725eb6615789109fbeb933a016c) ([#3918](https://github.com/yt-dlp/yt-dlp/issues/3918)) by [Lesmiscore](https://github.com/Lesmiscore)
- polskieradio
    - [Adapt to next.js redesigns](https://github.com/yt-dlp/yt-dlp/commit/d1b5f3d79cb33f393f17aa12df24fca33c7ef3aa) ([#5416](https://github.com/yt-dlp/yt-dlp/issues/5416)) by [selfisekai](https://github.com/selfisekai)
- pornez
    - [Handle relative URLs in iframe](https://github.com/yt-dlp/yt-dlp/commit/f7efe6dc958eb0689cb9534ff0b4e592040be8df) ([#6171](https://github.com/yt-dlp/yt-dlp/issues/6171)) by [JChris246](https://github.com/JChris246)
- pornhub
    - [Extract `uploader_id` field](https://github.com/yt-dlp/yt-dlp/commit/4f2a58c9c57093d4a305e505ddf30f945b240416) ([#4104](https://github.com/yt-dlp/yt-dlp/issues/4104)) by [Lesmiscore](https://github.com/Lesmiscore)
- prankcast
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/143a2ccab39a4e6477521f0d563f940a97fa9dc6) ([#4774](https://github.com/yt-dlp/yt-dlp/issues/4774)) by [columndeeply](https://github.com/columndeeply), [HobbyistDev](https://github.com/HobbyistDev)
- premiershiprugby
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/30d22d775bc9abdbd301132b6cb7a57badb796dc) ([#4129](https://github.com/yt-dlp/yt-dlp/issues/4129)) by [HobbyistDev](https://github.com/HobbyistDev)
- qingting
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c94df4d19d3af4120c9b674556acb1f1905c366f) ([#5329](https://github.com/yt-dlp/yt-dlp/issues/5329)) by [bashonly](https://github.com/bashonly), [changren-wcr](https://github.com/changren-wcr)
- radiko
    - [Fix format sorting for Time Free](https://github.com/yt-dlp/yt-dlp/commit/203a06f8554df6db07d8f20f465ecbfe8a14e591) ([#6159](https://github.com/yt-dlp/yt-dlp/issues/6159)) by [road-master](https://github.com/road-master)
- radiofrance
    - [Add more radios](https://github.com/yt-dlp/yt-dlp/commit/38d86f4d45cf2b764f79141c602356fbb426a4b6) ([#4065](https://github.com/yt-dlp/yt-dlp/issues/4065)) by [bubbleguuum](https://github.com/bubbleguuum)
- rai
    - [Add raisudtirol extractor](https://github.com/yt-dlp/yt-dlp/commit/47304e07dc4a044242f7d5a14c3f6c3e5f3ad8ba) ([#4524](https://github.com/yt-dlp/yt-dlp/issues/4524)) by [nixxo](https://github.com/nixxo)
    - [Fix RaiNews extraction](https://github.com/yt-dlp/yt-dlp/commit/0cd2810379bbd444707028f38f44c686521f44df) ([#4380](https://github.com/yt-dlp/yt-dlp/issues/4380)) by [nixxo](https://github.com/nixxo)
    - [Minor fix](https://github.com/yt-dlp/yt-dlp/commit/4d37d4a77c50c326b273efbaed5afa1c45771474) ([#4700](https://github.com/yt-dlp/yt-dlp/issues/4700)) by [pukkandan](https://github.com/pukkandan)
    - [Misc fixes](https://github.com/yt-dlp/yt-dlp/commit/7e823974414dba7a8ae4d703c511f92a374a0a50) ([#4600](https://github.com/yt-dlp/yt-dlp/issues/4600)) by [nixxo](https://github.com/nixxo)
- rcs
    - [Fix embed extraction](https://github.com/yt-dlp/yt-dlp/commit/f1aae715684b8a2cd4ce5590373b49ba5030dba6) by [coletdjnz](https://github.com/coletdjnz)
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/c6b657867ad68af6b930ed0aa11ec5d93ee187b7) ([#5700](https://github.com/yt-dlp/yt-dlp/issues/5700)) by [nixxo](https://github.com/nixxo), [pukkandan](https://github.com/pukkandan)
- redbee
    - [Unify and update extractors](https://github.com/yt-dlp/yt-dlp/commit/2a5e5477bcb70d62de20556924a405857d071e09) ([#4479](https://github.com/yt-dlp/yt-dlp/issues/4479)) by [elyse0](https://github.com/elyse0)
- reddit
    - [Add fallback format](https://github.com/yt-dlp/yt-dlp/commit/2e565f5bcacd2ab25bb57160313048b398afab4c) ([#5165](https://github.com/yt-dlp/yt-dlp/issues/5165)) by [bashonly](https://github.com/bashonly)
    - [Add subreddit as `channel_id`](https://github.com/yt-dlp/yt-dlp/commit/84e0e33a19ce3206b0e17bf9bd0c25811a0b20c2) ([#5685](https://github.com/yt-dlp/yt-dlp/issues/5685)) by [gschizas](https://github.com/gschizas)
    - [Add vcodec to fallback format](https://github.com/yt-dlp/yt-dlp/commit/02b2f9fa7de583f2bfdebe568f608c9b9398d316) ([#5591](https://github.com/yt-dlp/yt-dlp/issues/5591)) by [chengzhicn](https://github.com/chengzhicn)
    - [Extract crossposted media](https://github.com/yt-dlp/yt-dlp/commit/1fc089143c79b02b8373ae1d785d5e3a68635d4d) ([#5801](https://github.com/yt-dlp/yt-dlp/issues/5801)) by [bashonly](https://github.com/bashonly)
    - [Extract video embeds in text posts](https://github.com/yt-dlp/yt-dlp/commit/0e96b408b994678764a89cabbb3879b2c383624a) ([#5677](https://github.com/yt-dlp/yt-dlp/issues/5677)) by [bashonly](https://github.com/bashonly)
    - [Support user posts](https://github.com/yt-dlp/yt-dlp/commit/c77df98b1a477a020a57141464d10c0f4d0fdbc9) ([#6173](https://github.com/yt-dlp/yt-dlp/issues/6173)) by [OMEGARAZER](https://github.com/OMEGARAZER)
- redgifs
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/c53e5cf59fb73769faa97516d70cff7fca39185b) ([#4892](https://github.com/yt-dlp/yt-dlp/issues/4892)) by [jhwgh1968](https://github.com/jhwgh1968)
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/f47cf86eff47accf47082f88583ef25cdae18467) by [pukkandan](https://github.com/pukkandan)
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/0c908911f9e9f348a5036c35f2906615347c4aa2) by [bashonly](https://github.com/bashonly)
    - [Refresh auth token for 401](https://github.com/yt-dlp/yt-dlp/commit/8c188d5d09177ed213a05c900d3523867c5897fd) ([#5352](https://github.com/yt-dlp/yt-dlp/issues/5352)) by [endotronic](https://github.com/endotronic), [pukkandan](https://github.com/pukkandan) (With fixes in [f96a3fb](https://github.com/yt-dlp/yt-dlp/commit/f96a3fb7d3cbeb2b63c2eafcc14b359f37ff3078) by [pukkandan](https://github.com/pukkandan))
- rokfin
    - search: [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c9b2b368b3a513d8743bf4d17fa9427f46ccdc18) ([#2992](https://github.com/yt-dlp/yt-dlp/issues/2992)) by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
- rozhlas
    - [Add extractor RozhlasVltavaIE](https://github.com/yt-dlp/yt-dlp/commit/355d781bed497cbcb254bf2a2737b83fa51c84ea) ([#5951](https://github.com/yt-dlp/yt-dlp/issues/5951)) by [amra](https://github.com/amra)
- rtbf
    - [Fix jwt extraction](https://github.com/yt-dlp/yt-dlp/commit/b85703d11a150967b9430f38ac938c7f41a4ad76) ([#4738](https://github.com/yt-dlp/yt-dlp/issues/4738)) by [elyse0](https://github.com/elyse0)
    - [Fix stream extractor](https://github.com/yt-dlp/yt-dlp/commit/2b3e43e2479511974815fba247393560183691ad) ([#4671](https://github.com/yt-dlp/yt-dlp/issues/4671)) by [elyse0](https://github.com/elyse0)
- rtl.lu
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/5f2da312fa66d6f001ca4d8d79ee281b9b62e9ed) ([#4222](https://github.com/yt-dlp/yt-dlp/issues/4222)) by [HobbyistDev](https://github.com/HobbyistDev)
- rtvsl
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/dfa6661e0f2ea8113083956d5419f15bbc89856c) ([#2586](https://github.com/yt-dlp/yt-dlp/issues/2586)) by [iw0nderhow](https://github.com/iw0nderhow), [pukkandan](https://github.com/pukkandan)
- rumble
    - [Add HLS formats and extract more metadata](https://github.com/yt-dlp/yt-dlp/commit/0d8affc17faa540f41cb6fba7675dbf98364250b) ([#5280](https://github.com/yt-dlp/yt-dlp/issues/5280)) by [flashdagger](https://github.com/flashdagger)
    - [Add RumbleIE extractor](https://github.com/yt-dlp/yt-dlp/commit/839e2a62ae977ae51b1fcec50a8af3d28e1d230c) ([#5515](https://github.com/yt-dlp/yt-dlp/issues/5515)) by [flashdagger](https://github.com/flashdagger)
    - [Detect JS embed](https://github.com/yt-dlp/yt-dlp/commit/79e591b59b8c706824bd937048c719573de77923) by [pukkandan](https://github.com/pukkandan)
    - [Fix format sorting](https://github.com/yt-dlp/yt-dlp/commit/acacb57c7e173b93c6e0f0c43e61b9b2912719d8) by [pukkandan](https://github.com/pukkandan)
- rutube
    - [Fix `_EMBED_REGEX`](https://github.com/yt-dlp/yt-dlp/commit/d42763a443107fa6a9d69c110f92c98857ca2406) by [coletdjnz](https://github.com/coletdjnz)
    - [Support private videos](https://github.com/yt-dlp/yt-dlp/commit/df10bad2670d63349dc3c99a34baafe992e2fffb) ([#5761](https://github.com/yt-dlp/yt-dlp/issues/5761)) by [mexus](https://github.com/mexus)
- RUTV
    - [Fix warnings for livestreams](https://github.com/yt-dlp/yt-dlp/commit/5c8b2ee9ecf8773eb463b4ae218f8313a6626b2f) ([#5016](https://github.com/yt-dlp/yt-dlp/issues/5016)) by [Lesmiscore](https://github.com/Lesmiscore)
- sbs
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/226c0f3a54faef19e2d2729d0072e7df43a7250b) ([#5193](https://github.com/yt-dlp/yt-dlp/issues/5193)) by [bashonly](https://github.com/bashonly)
- screen9
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/540236ce11a133675a3a9ea9b373155274fab550) ([#5137](https://github.com/yt-dlp/yt-dlp/issues/5137)) by [tpikonen](https://github.com/tpikonen)
- screencastify
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/27c0f899c8f4a71e2ec8ac7ee4ab0217da7934bd) ([#5604](https://github.com/yt-dlp/yt-dlp/issues/5604)) by [bashonly](https://github.com/bashonly)
- screencastomatic
    - [Support `--video-password`](https://github.com/yt-dlp/yt-dlp/commit/a1af516259127d4d82bae01088b654ff980bc863) ([#4761](https://github.com/yt-dlp/yt-dlp/issues/4761)) by [shreyasminocha](https://github.com/shreyasminocha)
- Scrolller
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/2c60eae899932b1ffab0296174a0a10820192e5b) ([#4010](https://github.com/yt-dlp/yt-dlp/issues/4010)) by [LunarFang416](https://github.com/LunarFang416)
- servus
    - [Rewrite extractor](https://github.com/yt-dlp/yt-dlp/commit/f40e32fb1ac67be5bdbc8e32a3c235abfc4be260) ([#6036](https://github.com/yt-dlp/yt-dlp/issues/6036)) by [Ashish0804](https://github.com/Ashish0804), [FrankZ85](https://github.com/FrankZ85), [StefanLobbenmeier](https://github.com/StefanLobbenmeier)
- sibnet
    - [Separate from VKIE](https://github.com/yt-dlp/yt-dlp/commit/7991ae57a800316930e20a15df8314616c5cba8f) by [pukkandan](https://github.com/pukkandan)
- skyit
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/d715b0e4135fca75b417ee876a4360c58fa3ef6d) ([#5442](https://github.com/yt-dlp/yt-dlp/issues/5442)) by [nixxo](https://github.com/nixxo)
- slideslive
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/f69b0554eb4500f1bdd0e07484d6b0a91e2b050c) ([#5737](https://github.com/yt-dlp/yt-dlp/issues/5737)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
    - [Fix slides and chapters/duration](https://github.com/yt-dlp/yt-dlp/commit/5ab3534d44231f7711398bc3cfc520e2efd09f50) ([#6024](https://github.com/yt-dlp/yt-dlp/issues/6024)) by [bashonly](https://github.com/bashonly)
    - [Support embeds and slides](https://github.com/yt-dlp/yt-dlp/commit/3d667e0047915c32f5df9fdd86a4223dc0e9ce8f) ([#5784](https://github.com/yt-dlp/yt-dlp/issues/5784)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K), [pukkandan](https://github.com/pukkandan)
- Smotrim
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/faf7863bb0898c4a7972cd77b12a619bbc79c914) ([#5015](https://github.com/yt-dlp/yt-dlp/issues/5015)) by [Lesmiscore](https://github.com/Lesmiscore), [nikita-moor](https://github.com/nikita-moor)
- soundcloud
    - [Support user permalink](https://github.com/yt-dlp/yt-dlp/commit/e107c2b8cf8d6f3506d07bc64fc243682ee49b1e) ([#5842](https://github.com/yt-dlp/yt-dlp/issues/5842)) by [nosoop](https://github.com/nosoop)
    - search: [More metadata in `--flat-playlist`](https://github.com/yt-dlp/yt-dlp/commit/c04cc2e28e2a6c2e3384fb203796714d739ae42a) ([#4965](https://github.com/yt-dlp/yt-dlp/issues/4965)) by [SuperSonicHub1](https://github.com/SuperSonicHub1)
- southpark
    - [Add `southpark.lat` extractor](https://github.com/yt-dlp/yt-dlp/commit/bde0132e15cbac5801a5e9acb4a5445ffea423e0) ([#4008](https://github.com/yt-dlp/yt-dlp/issues/4008)) by [darkxex](https://github.com/darkxex)
- SovietsCloset
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/2f1a299c50559ac2ac8c159c8df83fcc4940cfa7) ([#4688](https://github.com/yt-dlp/yt-dlp/issues/4688)) by [ChillingPepper](https://github.com/ChillingPepper)
- spankbang
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/9fcd8ad1f21377f8cf784c35ebc758743227666e) ([#5791](https://github.com/yt-dlp/yt-dlp/issues/5791)) by [JChris246](https://github.com/JChris246)
- SportDeutschland
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/5e1a54f63e393c218a40949012ff0de0ce63cb15) ([#6041](https://github.com/yt-dlp/yt-dlp/issues/6041)) by [FriedrichRehren](https://github.com/FriedrichRehren)
- spotify
    - show: [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/8246f8402b77dfb5c905e97b04b09f89632575d9) by [pukkandan](https://github.com/pukkandan)
- StarTrek
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/eb2333bce129618e21fcf4d250cc6dc6cc811d16) ([#4191](https://github.com/yt-dlp/yt-dlp/issues/4191)) by [scy](https://github.com/scy)
- steam
    - [Add broadcast extractor](https://github.com/yt-dlp/yt-dlp/commit/5fb450a64c300056476cfef481b7b5377ff82d54) ([#4137](https://github.com/yt-dlp/yt-dlp/issues/4137)) by [HobbyistDev](https://github.com/HobbyistDev)
- StreamCZ
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/854b0d325e36acddef7a798be21a98756d86ca89) ([#3789](https://github.com/yt-dlp/yt-dlp/issues/3789)) by [adamanldo](https://github.com/adamanldo), [dirkf](https://github.com/dirkf)
- stripchat
    - [Don't modify input URL](https://github.com/yt-dlp/yt-dlp/commit/76f2bb175d56a8d85001da2b4ee18d790e0948ad) ([#4781](https://github.com/yt-dlp/yt-dlp/issues/4781)) by [dfaker](https://github.com/dfaker)
    - [Fix _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/befcac11a0353b4df9ee4015bbabdd6239a6dde1) ([#4491](https://github.com/yt-dlp/yt-dlp/issues/4491)) by [freezboltz](https://github.com/freezboltz)
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/7d5f919bad07017f4b39b55725491b1e9717d47a) ([#5985](https://github.com/yt-dlp/yt-dlp/issues/5985)) by [bashonly](https://github.com/bashonly), [JChris246](https://github.com/JChris246)
    - [Fix hostname for HLS stream](https://github.com/yt-dlp/yt-dlp/commit/a349d4d6415e9aa0fb11c674e405d57fa13cc7fd) ([#5445](https://github.com/yt-dlp/yt-dlp/issues/5445)) by [zulaport](https://github.com/zulaport)
    - [Improve error message](https://github.com/yt-dlp/yt-dlp/commit/3b87f4d9439e28cf568113409eafb304a519b2e1) ([#5475](https://github.com/yt-dlp/yt-dlp/issues/5475)) by [freezboltz](https://github.com/freezboltz)
- stv
    - [Detect DRM](https://github.com/yt-dlp/yt-dlp/commit/4455918e7f090ace0b0c2537bbfd364956eb66cb) by [pukkandan](https://github.com/pukkandan)
- substack
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/612e31f5ea66ccc69a6ddf0dd3a4086db7127434) ([#4011](https://github.com/yt-dlp/yt-dlp/issues/4011)) by [elyse0](https://github.com/elyse0)
- swearnet
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/049565df2e24d9611a9ffdd033c80a6dafdabbe0) ([#5371](https://github.com/yt-dlp/yt-dlp/issues/5371)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Fix description bug](https://github.com/yt-dlp/yt-dlp/commit/ddf1e22d48530819d60220d0bdc36e20f5b8483b) ([#5681](https://github.com/yt-dlp/yt-dlp/issues/5681)) by [pukkandan](https://github.com/pukkandan)
- syvdk
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/17a23f0930e8012bec4e7c3619e0bfc484481971) ([#4250](https://github.com/yt-dlp/yt-dlp/issues/4250)) by [misaelaguayo](https://github.com/misaelaguayo)
- telegraaf
    - [Use mobile GraphQL API endpoint](https://github.com/yt-dlp/yt-dlp/commit/32972518da55934f7ccf7960f788363d5700da5e) by [coletdjnz](https://github.com/coletdjnz)
- telegram
    - [Add playlist support and more metadata](https://github.com/yt-dlp/yt-dlp/commit/96b9e9cf62c81b005242da418f092e45709a5123) ([#5358](https://github.com/yt-dlp/yt-dlp/issues/5358)) by [bashonly](https://github.com/bashonly), [bsun0000](https://github.com/bsun0000)
- tempo
    - [Add IVXPlayer extractor](https://github.com/yt-dlp/yt-dlp/commit/30031be974d210f451100339699ef03b0ddb5f10) ([#5837](https://github.com/yt-dlp/yt-dlp/issues/5837)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/67685a541d647947d410d37ec312494ec6874de6) ([#4463](https://github.com/yt-dlp/yt-dlp/issues/4463)) by [HobbyistDev](https://github.com/HobbyistDev)
- tencent
    - [Add Iflix extractor](https://github.com/yt-dlp/yt-dlp/commit/48f535f5f8de109cdfb20eef8beed73e65cdfdd4) ([#4829](https://github.com/yt-dlp/yt-dlp/issues/4829)) by [elyse0](https://github.com/elyse0)
    - [Add more formats and info](https://github.com/yt-dlp/yt-dlp/commit/18d295c9e0f95adc179eef345b7af64d6372db78) ([#5950](https://github.com/yt-dlp/yt-dlp/issues/5950)) by [Hill-98](https://github.com/Hill-98)
    - [Fix geo-restricted video](https://github.com/yt-dlp/yt-dlp/commit/0a4b2f4180b57f8e82b5d9c078c070ddfac7c727) ([#5505](https://github.com/yt-dlp/yt-dlp/issues/5505)) by [elyse0](https://github.com/elyse0)
- tennistv
    - [Fix timestamp](https://github.com/yt-dlp/yt-dlp/commit/eb2d9504b91c4ca3b10a90302df53b867924e86b) ([#5085](https://github.com/yt-dlp/yt-dlp/issues/5085)) by [zenerdi0de](https://github.com/zenerdi0de)
    - [Rewrite extractor](https://github.com/yt-dlp/yt-dlp/commit/37e40d693b508c6be4a8013cfb7fe7e5b4934042) ([#2324](https://github.com/yt-dlp/yt-dlp/issues/2324)) by [pukkandan](https://github.com/pukkandan), [zenerdi0de](https://github.com/zenerdi0de)
- theholetv
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/4e7f375c949cb152ae953aa834098351f8e5a872) ([#4325](https://github.com/yt-dlp/yt-dlp/issues/4325)) by [dosy4ev](https://github.com/dosy4ev)
- tiktok
    - [Add `TikTokLive` extractor](https://github.com/yt-dlp/yt-dlp/commit/933ed882e94ebfacc5e407dbd74fa25e672092c4) ([#5637](https://github.com/yt-dlp/yt-dlp/issues/5637)) by [JC-Chung](https://github.com/JC-Chung)
    - [Extract `SIGI_STATE`](https://github.com/yt-dlp/yt-dlp/commit/a39a7ba8d6efccf8d2fc8029ecebcb10e6c11d59) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan), [sulyi](https://github.com/sulyi)
    - [Fix TikTokIE](https://github.com/yt-dlp/yt-dlp/commit/f7c5a5e96756636379a0b1afbeadb08b9c643bef) ([#4984](https://github.com/yt-dlp/yt-dlp/issues/4984)) by [bashonly](https://github.com/bashonly)
    - [Fix subs, `DouyinIE`, improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/ba723997235fc50673dac8eae1503b509b7800d5) ([#5676](https://github.com/yt-dlp/yt-dlp/issues/5676)) by [bashonly](https://github.com/bashonly)
    - [Update API hostname](https://github.com/yt-dlp/yt-dlp/commit/c9f5ce511877ae4f22d2eb2f70c3c6edf6c1971d) ([#5690](https://github.com/yt-dlp/yt-dlp/issues/5690)) by [redraskal](https://github.com/redraskal)
    - [Update `_VALID_URL`, add `api_hostname` arg](https://github.com/yt-dlp/yt-dlp/commit/c4cbd3bebd33d2d77fa340a4035447ab1b9eb3eb) ([#5708](https://github.com/yt-dlp/yt-dlp/issues/5708)) by [bashonly](https://github.com/bashonly)
- tnaflix
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/989f47b6315541989bb507f26b431d9586430995) ([#6086](https://github.com/yt-dlp/yt-dlp/issues/6086)) by [bashonly](https://github.com/bashonly), [oxamun](https://github.com/oxamun)
    - [Fix for HTTP 500](https://github.com/yt-dlp/yt-dlp/commit/09c127ff838505de1bddde56ad4d22f46ebf6ed7) ([#5150](https://github.com/yt-dlp/yt-dlp/issues/5150)) by [SG5](https://github.com/SG5) (With fixes in [a79bf78](https://github.com/yt-dlp/yt-dlp/commit/a79bf78397088fd6c3dde1f8370a030ab43b8b99) by [pukkandan](https://github.com/pukkandan))
- toggo
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/ef6342bd07c7bd1e41b0cc8889bcfadfab3477f2) ([#4663](https://github.com/yt-dlp/yt-dlp/issues/4663)) by [masta79](https://github.com/masta79)
- triller
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/92aa6d688358ab4f328d37e66f0db3c54d7ab89b) ([#4712](https://github.com/yt-dlp/yt-dlp/issues/4712)) by [bashonly](https://github.com/bashonly)
    - [Fix auth token](https://github.com/yt-dlp/yt-dlp/commit/d6f8871964253373ddaae60c89f1f4838769e7df) ([#4813](https://github.com/yt-dlp/yt-dlp/issues/4813)) by [bashonly](https://github.com/bashonly)
- Trovo
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/660c0c4efd60c8fe33e5cd34ae00f54708ec85c1) ([#4208](https://github.com/yt-dlp/yt-dlp/issues/4208)) by [u-spec-png](https://github.com/u-spec-png)
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/9cc5aed990e6f3baa1eff3d7e040eef197a166de) ([#4880](https://github.com/yt-dlp/yt-dlp/issues/4880)) by [Mehavoid](https://github.com/Mehavoid)
- trtcocuk
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/032f22020c3aaf0c1be1bb500498d13782d01c73) ([#5009](https://github.com/yt-dlp/yt-dlp/issues/5009)) by [HobbyistDev](https://github.com/HobbyistDev)
- truth
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/cb7cc448c0b7508215a45af0b81506403f61ef05) ([#4609](https://github.com/yt-dlp/yt-dlp/issues/4609)) by [palewire](https://github.com/palewire)
- TubeTuGraz
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/49afc1d84a767ab2576d2c7d51d28c8920fc96f9) ([#2397](https://github.com/yt-dlp/yt-dlp/issues/2397)) by [Ferdi265](https://github.com/Ferdi265), [pukkandan](https://github.com/pukkandan)
- tubi
    - [Exclude playlists from playlist entries](https://github.com/yt-dlp/yt-dlp/commit/2dc4970e08c1f40332b9ccd90ccbc5340b86f7bc) ([#4416](https://github.com/yt-dlp/yt-dlp/issues/4416)) by [sqrtNOT](https://github.com/sqrtNOT)
- tubitv
    - [Better DRM detection](https://github.com/yt-dlp/yt-dlp/commit/3b55aaac596e7a08730439eb8cac4e240f4b250b) ([#5171](https://github.com/yt-dlp/yt-dlp/issues/5171)) by [bashonly](https://github.com/bashonly)
    - [Extract additional formats](https://github.com/yt-dlp/yt-dlp/commit/ffcd62c2899a7d0cd4aeceaed922d3d0a6c1c582) ([#4646](https://github.com/yt-dlp/yt-dlp/issues/4646)) by [shirt-dev](https://github.com/shirt-dev)
- tv2
    - [Support new url format](https://github.com/yt-dlp/yt-dlp/commit/acf306d1f97486c8c88455cfa294d11c818d41fe) ([#5063](https://github.com/yt-dlp/yt-dlp/issues/5063)) by [tobi1805](https://github.com/tobi1805)
- tver
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/6837633a4a614920b6e43ffc6b4b8590dca8c9d7) ([#4033](https://github.com/yt-dlp/yt-dlp/issues/4033)) by [Lesmiscore](https://github.com/Lesmiscore) (With fixes in [2523702](https://github.com/yt-dlp/yt-dlp/commit/2523702718f07bbc5c2b71552a2537050440bdf3))
- tviplayer
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/26b92a919df60f30da199736a513b77415bc6cf2) ([#4281](https://github.com/yt-dlp/yt-dlp/issues/4281)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/1f6b90ed8db7006e2f2d539c41c8f3e59058dd00) ([#4585](https://github.com/yt-dlp/yt-dlp/issues/4585)) by [HobbyistDev](https://github.com/HobbyistDev)
- tvp
    - [Support `stream.tvp.pl`](https://github.com/yt-dlp/yt-dlp/commit/a31d0fa6c315b1145d682361149003d98f1e3782) ([#6139](https://github.com/yt-dlp/yt-dlp/issues/6139)) by [selfisekai](https://github.com/selfisekai)
    - [Update extractors](https://github.com/yt-dlp/yt-dlp/commit/728f4b5c2ef914f3b45d160883469502366d8eac) ([#5346](https://github.com/yt-dlp/yt-dlp/issues/5346)) by [selfisekai](https://github.com/selfisekai)
- twitcasting
    - [Fix `data-movie-playlist` extraction](https://github.com/yt-dlp/yt-dlp/commit/da9a60ca0d9ed085ba3d60bf46e48bd2b53f1ecb) ([#5453](https://github.com/yt-dlp/yt-dlp/issues/5453)) by [Lesmiscore](https://github.com/Lesmiscore)
    - [Fix videos with password](https://github.com/yt-dlp/yt-dlp/commit/9a9006ba20f1f9f34183e1bde098c75502a018f8) ([#5894](https://github.com/yt-dlp/yt-dlp/issues/5894)) by [bashonly](https://github.com/bashonly), [Spicadox](https://github.com/Spicadox)
- twitch
    - [Extract chapters for single chapter VODs](https://github.com/yt-dlp/yt-dlp/commit/1cdf69c57e8950b07f24a6ebc6dfb0c6b1e83274) ([#4453](https://github.com/yt-dlp/yt-dlp/issues/4453)) by [mpeter50](https://github.com/mpeter50)
    - [Support storyboards for VODs](https://github.com/yt-dlp/yt-dlp/commit/418bbfd722ba01bb106daf80ab204984a1fc26e5) ([#4342](https://github.com/yt-dlp/yt-dlp/issues/4342)) by [ftk](https://github.com/ftk)
    - [Update for GraphQL API changes](https://github.com/yt-dlp/yt-dlp/commit/4a6272c6d1bff89969b67cd22b26ebe6d7e72279) ([#6318](https://github.com/yt-dlp/yt-dlp/issues/6318)) by [elyse0](https://github.com/elyse0)
- twitter
    - [Add Spaces extractor and GraphQL API](https://github.com/yt-dlp/yt-dlp/commit/7a26ce2641c45b561dde190e2eb92b7d923ca5de) ([#5247](https://github.com/yt-dlp/yt-dlp/issues/5247), [#4864](https://github.com/yt-dlp/yt-dlp/issues/4864)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K), [nixxo](https://github.com/nixxo), [pukkandan](https://github.com/pukkandan)
    - [Add onion site to `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/82fb2357d90ace7a321f5c5fa55cd1a5bdb01578) ([#5208](https://github.com/yt-dlp/yt-dlp/issues/5208)) by [DoubleCouponDay](https://github.com/DoubleCouponDay)
    - [Fix `--no-playlist` and add media `view_count` when using GraphQL](https://github.com/yt-dlp/yt-dlp/commit/b6795fd310f1dd61dddc9fd08e52fe485bdc8a3e) ([#6211](https://github.com/yt-dlp/yt-dlp/issues/6211)) by [Grub4K](https://github.com/Grub4K)
    - [Fix graphql extraction on some tweets](https://github.com/yt-dlp/yt-dlp/commit/7543c9c99bcb116b085fdb1f41b84a0ead04c05d) ([#6075](https://github.com/yt-dlp/yt-dlp/issues/6075)) by [selfisekai](https://github.com/selfisekai)
    - [Heed `--no-playlist` for multi-video tweets](https://github.com/yt-dlp/yt-dlp/commit/16bed382fd5e7f258b8d058ca2863deb38875994) ([#5757](https://github.com/yt-dlp/yt-dlp/issues/5757)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
    - [Refresh guest token when expired](https://github.com/yt-dlp/yt-dlp/commit/352e7d987323e9df9205ee117a604ee4123231c2) ([#5560](https://github.com/yt-dlp/yt-dlp/issues/5560)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
    - [Support multi-video posts](https://github.com/yt-dlp/yt-dlp/commit/13b2ae29c2056c5306c3b735e801e9b091a33739) ([#5183](https://github.com/yt-dlp/yt-dlp/issues/5183)) by [Grub4K](https://github.com/Grub4K)
    - spaces: [Add 'Referer' to m3u8](https://github.com/yt-dlp/yt-dlp/commit/9a0416c6a5e87c577cb5079e75e3ae63ee948d80) ([#5580](https://github.com/yt-dlp/yt-dlp/issues/5580)) by [nixxo](https://github.com/nixxo)
- txxx
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/389896df85ed14eaf74f72531da6c4491d6b73b0) ([#5240](https://github.com/yt-dlp/yt-dlp/issues/5240)) by [chio0hai](https://github.com/chio0hai)
- udemy
    - [Fix lectures that have no URL and detect DRM](https://github.com/yt-dlp/yt-dlp/commit/8d1ddb0805c7c56bd03a5c0837c55602473d213f) by [pukkandan](https://github.com/pukkandan)
- uktv
    - [Improve _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/0a6b4b82e926ffd583a5cbe81d25bbfc7f1f43ed) by [dirkf](https://github.com/dirkf)
- uktvplay
    - [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/581e86b512bbe39c1252bd696d0db8a906bce355) by [pukkandan](https://github.com/pukkandan)
- unscripted
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/20a7304e4c7a839ab73be03a248d092173206c17) ([#5008](https://github.com/yt-dlp/yt-dlp/issues/5008)) by [HobbyistDev](https://github.com/HobbyistDev)
- unsupported
    - [Add more URLs](https://github.com/yt-dlp/yt-dlp/commit/8486540257c8f1532654cafb4e22b099ba62a287) by [pukkandan](https://github.com/pukkandan)
    - [Raise error on known DRM-only sites](https://github.com/yt-dlp/yt-dlp/commit/d9df9b4919e84a3ba7be04acb73e56d67431550c) ([#5483](https://github.com/yt-dlp/yt-dlp/issues/5483)) by [coletdjnz](https://github.com/coletdjnz)
- urplay
    - [Support for audio-only formats](https://github.com/yt-dlp/yt-dlp/commit/247c8dd4f548436e2cf0f2e55a80aa37ec62555a) ([#4606](https://github.com/yt-dlp/yt-dlp/issues/4606)) by [barsnick](https://github.com/barsnick)
- Veoh
    - [Add user extractor](https://github.com/yt-dlp/yt-dlp/commit/d9658562350f6aaf9f6deb037734d1cd691a64ce) ([#5242](https://github.com/yt-dlp/yt-dlp/issues/5242)) by [tntmod54321](https://github.com/tntmod54321)
- vevo
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/9c0412cf6b2257b314a6e1cc5ac07edc03f6d6ea) ([#3921](https://github.com/yt-dlp/yt-dlp/issues/3921)) by [Lesmiscore](https://github.com/Lesmiscore)
- videoken
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/4b183d49620e564219c01714ca8639199f6b1cc0) ([#5824](https://github.com/yt-dlp/yt-dlp/issues/5824)) by [bashonly](https://github.com/bashonly)
- vidio
    - [Support embed link](https://github.com/yt-dlp/yt-dlp/commit/ad26f15a069a8e080c2b2bdab887ac193db5e2ce) ([#4564](https://github.com/yt-dlp/yt-dlp/issues/4564)) by [HobbyistDev](https://github.com/HobbyistDev)
- vimeo
    - [Add `VimeoProIE`](https://github.com/yt-dlp/yt-dlp/commit/7ff2fafe47aa9978f89ff358a8b9f9261430f33a) ([#5596](https://github.com/yt-dlp/yt-dlp/issues/5596)) by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
    - [Fix `playerConfig` extraction](https://github.com/yt-dlp/yt-dlp/commit/c0cd13fb1c71b842c3d272d0273c03542b467766) ([#6203](https://github.com/yt-dlp/yt-dlp/issues/6203)) by [bashonly](https://github.com/bashonly), [LeoniePhiline](https://github.com/LeoniePhiline)
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/aedaa455d9874f14662023f21b254168ecd55579) by [pukkandan](https://github.com/pukkandan)
    - user: [Fix _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/1d64a59547d1c674de5750d4581131ec8e2d280e) by [pukkandan](https://github.com/pukkandan)
- ViMP
    - [Add playlist extractor](https://github.com/yt-dlp/yt-dlp/commit/1db146127292e31fa8e8cb47e9ce2b696bbe173b) ([#4147](https://github.com/yt-dlp/yt-dlp/issues/4147)) by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
    - [Add thumbnail and support more sites](https://github.com/yt-dlp/yt-dlp/commit/74900105be772df0d38a5fac48ab339ace63381d) ([#4147](https://github.com/yt-dlp/yt-dlp/issues/4147)) by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
- viu
    - [Add `ViuOTTIndonesiaIE` extractor](https://github.com/yt-dlp/yt-dlp/commit/72671a212d7c939329cb5d34335fa089dd3acbd3) ([#6099](https://github.com/yt-dlp/yt-dlp/issues/6099)) by [HobbyistDev](https://github.com/HobbyistDev)
    - [Support subtitles of on-screen text](https://github.com/yt-dlp/yt-dlp/commit/f324fe8c590d3f4737cfd8b5a41eaa60edc546dc) ([#5173](https://github.com/yt-dlp/yt-dlp/issues/5173)) by [tkgmomosheep](https://github.com/tkgmomosheep)
- vk
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/59f63c8f0facb71208c8c131935fc4317e96f8b4) ([#4128](https://github.com/yt-dlp/yt-dlp/issues/4128)) by [Mehavoid](https://github.com/Mehavoid)
    - [Fix playlists for new API](https://github.com/yt-dlp/yt-dlp/commit/a9c685453f7019bee94170f936619c6db76c964e) ([#6122](https://github.com/yt-dlp/yt-dlp/issues/6122)) by [the-marenga](https://github.com/the-marenga)
- vlive
    - [Extract `release_timestamp`](https://github.com/yt-dlp/yt-dlp/commit/5da08bde9e073987d1aae2683235721e4813f9c6) by [pukkandan](https://github.com/pukkandan)
    - [Replace with `VLiveWebArchiveIE`](https://github.com/yt-dlp/yt-dlp/commit/b3eaab7ca2e118d4db73dcb44afd9c8717db8b67) ([#6196](https://github.com/yt-dlp/yt-dlp/issues/6196)) by [seproDev](https://github.com/seproDev)
- vocaroo
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/e4a8b1769e19755acba6d8f212208359905a3159) ([#6117](https://github.com/yt-dlp/yt-dlp/issues/6117)) by [qbnu](https://github.com/qbnu), [SuperSonicHub1](https://github.com/SuperSonicHub1)
- volejtv
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/91d54e9b99dacae74b3e55bb429365e9fbbac50f) ([#5943](https://github.com/yt-dlp/yt-dlp/issues/5943)) by [HobbyistDev](https://github.com/HobbyistDev)
- voot
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/a4713ba96d8b4905e9e8c37fb3b0c1826ae28e25) ([#5283](https://github.com/yt-dlp/yt-dlp/issues/5283)) by [freezboltz](https://github.com/freezboltz)
- VQQ
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/b2a4db425b02644353fdfbb9fe9df8c6ce7064ab) ([#4706](https://github.com/yt-dlp/yt-dlp/issues/4706)) by [elyse0](https://github.com/elyse0)
- WASDTV
    - record: [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/22b22b7d5c9dafa1d3f2dac25522bdd8b4091de4) by [pukkandan](https://github.com/pukkandan)
- WatchESPN
    - [Improve _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/3df6a603e4753f08bc44cdbbb45832970466f436) by [dirkf](https://github.com/dirkf), [IONECarter](https://github.com/IONECarter)
- web.archive
    - youtube: [Fix _YT_INITIAL_PLAYER_RESPONSE_RE](https://github.com/yt-dlp/yt-dlp/commit/19b4e59a1e1bf368078f90e7f735fa4576f97b64) by [pukkandan](https://github.com/pukkandan)
- webcamerapl
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/85a802969ebb62ff57347110f7ad0d87099e65e7) ([#5715](https://github.com/yt-dlp/yt-dlp/issues/5715)) by [milkknife](https://github.com/milkknife)
- wetv
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/2aab569f1c4c0c5b991a4ad50913d82fd04b3d26) ([#4330](https://github.com/yt-dlp/yt-dlp/issues/4330)) by [elyse0](https://github.com/elyse0) (With fixes in [ce7f6aa](https://github.com/yt-dlp/yt-dlp/commit/ce7f6aa660250039a1ab83cb5370b5bcf88c451c) by [pukkandan](https://github.com/pukkandan))
- wikimedia
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/2e2c60c4ba6d17b6f677a65c5279ca5cc82d70ab) ([#4314](https://github.com/yt-dlp/yt-dlp/issues/4314)) by [EhtishamSabir](https://github.com/EhtishamSabir), [pukkandan](https://github.com/pukkandan)
- wistia
    - [Add support for channels](https://github.com/yt-dlp/yt-dlp/commit/3c757d5ed2527b17881eb65c67ddbe0d1335771f) ([#4819](https://github.com/yt-dlp/yt-dlp/issues/4819)) by [coletdjnz](https://github.com/coletdjnz)
    - [Improve extension detection](https://github.com/yt-dlp/yt-dlp/commit/2647c933b8ed22f95dd8e9866c4db031867a1bc8) ([#5415](https://github.com/yt-dlp/yt-dlp/issues/5415)) by [bashonly](https://github.com/bashonly), [Grub4k](https://github.com/Grub4k), [pukkandan](https://github.com/pukkandan)
    - [Match IDs in embed URLs](https://github.com/yt-dlp/yt-dlp/commit/163281178a61565cd592426d452978ff47e63439) ([#4990](https://github.com/yt-dlp/yt-dlp/issues/4990)) by [bashonly](https://github.com/bashonly)
- wordpress
    - mb.miniAudioPlayer: [Add embed extractor](https://github.com/yt-dlp/yt-dlp/commit/4c9a1a3ba56c2906f9ef8d768de7f8e5a2361144) ([#5087](https://github.com/yt-dlp/yt-dlp/issues/5087)) by [coletdjnz](https://github.com/coletdjnz)
    - playlist: [Add generic embed extractor](https://github.com/yt-dlp/yt-dlp/commit/c9eba8075f000fdfab81b3ca11a8816d5835abf7) ([#5012](https://github.com/yt-dlp/yt-dlp/issues/5012)) by [coletdjnz](https://github.com/coletdjnz)
- wrestleuniverse
    - [Add extractors](https://github.com/yt-dlp/yt-dlp/commit/e61acb40b2cb6ef45508d72235026d458c9d5dff) ([#6158](https://github.com/yt-dlp/yt-dlp/issues/6158)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
- WSJArticle
    - [Fix video id extraction](https://github.com/yt-dlp/yt-dlp/commit/129dfa5f459f065d8be6205acda3a024127a894f) ([#4268](https://github.com/yt-dlp/yt-dlp/issues/4268)) by [sqrtNOT](https://github.com/sqrtNOT)
- xanimu
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/b382c1fc6a6bfff1b6373296961beabe60ffb72c) ([#5969](https://github.com/yt-dlp/yt-dlp/issues/5969)) by [JChris246](https://github.com/JChris246)
- xfileshare
    - [Add Referer](https://github.com/yt-dlp/yt-dlp/commit/d8657ff76f0701c7e35bfd7f2a2e247921c73afb) ([#4494](https://github.com/yt-dlp/yt-dlp/issues/4494)) by [Galiley](https://github.com/Galiley)
- xiami
    - [Remove extractors](https://github.com/yt-dlp/yt-dlp/commit/dfc186d4220081fdf7184347187639b15ab68a2f) ([#5711](https://github.com/yt-dlp/yt-dlp/issues/5711)) by [synthpop123](https://github.com/synthpop123)
- Ximalaya
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/dd634acd71620877e4543cfae66c30302505605d) ([#4339](https://github.com/yt-dlp/yt-dlp/issues/4339)) by [lockmatrix](https://github.com/lockmatrix)
    - [Update album `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/417cdaae08fc447c9d15c53a88e2e9a027cdbf0a) ([#6110](https://github.com/yt-dlp/yt-dlp/issues/6110)) by [carusocr](https://github.com/carusocr)
- yahoo
    - gyao: [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/8a3e7b1c95f08696ca2a026c1b462aeb8faf6904) by [pukkandan](https://github.com/pukkandan)
- YahooJapanNews
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/565a4c594499eb4f2c218e12f8ad1cea3362aedd) ([#4480](https://github.com/yt-dlp/yt-dlp/issues/4480)) by [Lesmiscore](https://github.com/Lesmiscore)
- yandexmusic
    - [Extract higher quality format](https://github.com/yt-dlp/yt-dlp/commit/2ebe6fefbeae02b826f9c84826c34fc0967023f3) by [pukkandan](https://github.com/pukkandan)
- yandexvideopreview
    - [Update _VALID_URL](https://github.com/yt-dlp/yt-dlp/commit/2e0f8d4f6e4dd546044c9432ec6aa223f67178bb) ([#5084](https://github.com/yt-dlp/yt-dlp/issues/5084)) by [Grub4K](https://github.com/Grub4K)
- yappy
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/361630015535026712bdb67f804a15b65ff9ee7e) ([#6111](https://github.com/yt-dlp/yt-dlp/issues/6111)) by [HobbyistDev](https://github.com/HobbyistDev)
- yle_areena
    - [Extract non-Kaltura videos](https://github.com/yt-dlp/yt-dlp/commit/40d77d89027cd0e0ce31d22aec81db3e1d433900) ([#6402](https://github.com/yt-dlp/yt-dlp/issues/6402)) by [bashonly](https://github.com/bashonly)
    - [Support restricted videos](https://github.com/yt-dlp/yt-dlp/commit/b05f0a50e05a85da0cdb322d6472b3cb67ee8427) ([#5735](https://github.com/yt-dlp/yt-dlp/issues/5735)) by [docbender](https://github.com/docbender)
- YleAreena
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/f4b2c59cfe8368e629f2f4c8c2e66dec9a7f8873) ([#5270](https://github.com/yt-dlp/yt-dlp/issues/5270)) by [pukkandan](https://github.com/pukkandan), [vitkhab](https://github.com/vitkhab)
- youku
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/06a9d68eb8413120f7e03d6c288cf855cd782f77) ([#5622](https://github.com/yt-dlp/yt-dlp/issues/5622)) by [KurtBestor](https://github.com/KurtBestor)
- youporn
    - [Fix metadata](https://github.com/yt-dlp/yt-dlp/commit/86f557b636cf2dc66cd882a88ae4338086c48fbb) ([#2768](https://github.com/yt-dlp/yt-dlp/issues/2768)) by [marieell](https://github.com/marieell)
- youtube
    - [Add `androidSdkVersion` parameter to Android Innertube clients](https://github.com/yt-dlp/yt-dlp/commit/c7dcf0b31e57bb98472da7cf293f523caa81c4a7) by [coletdjnz](https://github.com/coletdjnz)
    - [Add `innertube_host` and `innertube_key` extractor args](https://github.com/yt-dlp/yt-dlp/commit/2ae778b8fc56087462e48d1e31208c2a398409c1) ([#3916](https://github.com/yt-dlp/yt-dlp/issues/3916)) by [coletdjnz](https://github.com/coletdjnz)
    - [Add `live_status=post_live`](https://github.com/yt-dlp/yt-dlp/commit/e325a21a1f9a007fa7fd0c9a702ce12404157e24) ([#4495](https://github.com/yt-dlp/yt-dlp/issues/4495)) by [lazypete365](https://github.com/lazypete365)
    - [Add `no-youtube-prefer-utc-upload-date` compat option](https://github.com/yt-dlp/yt-dlp/commit/1ff88b7aec76bc8396c58f4757e2c08b20e5533e) ([#4771](https://github.com/yt-dlp/yt-dlp/issues/4771)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Add `piped.video`](https://github.com/yt-dlp/yt-dlp/commit/bc87dac75f289581bb2cd98500015c4d6a9027de) ([#5571](https://github.com/yt-dlp/yt-dlp/issues/5571)) by [Bnyro](https://github.com/Bnyro)
    - [Add fallback to phantomjs](https://github.com/yt-dlp/yt-dlp/commit/25836db6bea78501c514bfbe5840f305b33afdcd) by [pukkandan](https://github.com/pukkandan)
    - [Add hyperpipe instances](https://github.com/yt-dlp/yt-dlp/commit/78a78fa74dbc888d20f1b65e1382bf99131597d5) ([#6020](https://github.com/yt-dlp/yt-dlp/issues/6020)) by [Generator](https://github.com/Generator)
    - [Add support for Shorts audio pivot feed](https://github.com/yt-dlp/yt-dlp/commit/80eb0bd9b94106df9e1e5ac288def6e239937329) ([#4932](https://github.com/yt-dlp/yt-dlp/issues/4932)) by [coletdjnz](https://github.com/coletdjnz)
    - [Bring back `_extract_chapters_from_description`](https://github.com/yt-dlp/yt-dlp/commit/0fe51254cb878cf5f65801e2b62424a185665639) by [pukkandan](https://github.com/pukkandan)
    - [Bump Innertube client versions](https://github.com/yt-dlp/yt-dlp/commit/a0c830f488170db9007979da0ba13ebf9ebad5b1) by [coletdjnz](https://github.com/coletdjnz)
    - [Consider language in format de-duplication](https://github.com/yt-dlp/yt-dlp/commit/a4894d3e25943c4ecf4f38c0d50ce592d2175f29) by [pukkandan](https://github.com/pukkandan)
    - [Construct dash formats with `range` query](https://github.com/yt-dlp/yt-dlp/commit/5038f6d713303e0967d002216e7a88652401c22a) by [pukkandan](https://github.com/pukkandan) (With fixes in [f34804b](https://github.com/yt-dlp/yt-dlp/commit/f34804b2f920f62a6e893a14a9e2a2144b14dd23) by [bashonly](https://github.com/bashonly), [coletdjnz](https://github.com/coletdjnz))
    - [Detect `lazy-load-for-videos` embeds](https://github.com/yt-dlp/yt-dlp/commit/7c6eb424d35e51c81f8fe9e1eb7cc18067c3a8a7) by [pukkandan](https://github.com/pukkandan)
    - [Detect and break on looping comments](https://github.com/yt-dlp/yt-dlp/commit/7f51861b1820c37b157a239b1fe30628d907c034) ([#6301](https://github.com/yt-dlp/yt-dlp/issues/6301)) by [coletdjnz](https://github.com/coletdjnz)
    - [Differentiate between no and disabled comments](https://github.com/yt-dlp/yt-dlp/commit/0cf643b234ff2f4d017a980dbaefdb14ed6e4db6) ([#5491](https://github.com/yt-dlp/yt-dlp/issues/5491)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Do not warn on duplicate chapters](https://github.com/yt-dlp/yt-dlp/commit/709ee214170cdb3e91f68062a07f52d1a24a8c89) by [pukkandan](https://github.com/pukkandan)
    - [Download `post_live` videos from start](https://github.com/yt-dlp/yt-dlp/commit/4d37720a0c5f1c9c4768ea20b0f943277f55bc12) ([#5091](https://github.com/yt-dlp/yt-dlp/issues/5091)) by [Lesmiscore](https://github.com/Lesmiscore), [pukkandan](https://github.com/pukkandan)
    - [Extract DRC formats](https://github.com/yt-dlp/yt-dlp/commit/9bb856998b0d5a0ad58268f0ba8d784fb9d934e3) by [pukkandan](https://github.com/pukkandan)
    - [Extract channel `view_count` when `/about` tab is passed](https://github.com/yt-dlp/yt-dlp/commit/31e183557fcd1b937582f9429f29207c1261f501) by [pukkandan](https://github.com/pukkandan)
    - [Extract concurrent view count for livestreams](https://github.com/yt-dlp/yt-dlp/commit/867c66ff97b0639485a2b6ebc28f2e0df0bf8187) ([#5152](https://github.com/yt-dlp/yt-dlp/issues/5152)) by [coletdjnz](https://github.com/coletdjnz)
    - [Extract more format info](https://github.com/yt-dlp/yt-dlp/commit/a41662343603bc2d32648ebf0779e5fe1e18d263) by [pukkandan](https://github.com/pukkandan)
    - [Fallback regex for nsig code extraction](https://github.com/yt-dlp/yt-dlp/commit/b505e8517ad2ca8e07d5f9577dfd9a96165beaa0) by [pukkandan](https://github.com/pukkandan)
    - [Fix `duration` for premieres](https://github.com/yt-dlp/yt-dlp/commit/9da6612b0fc3a86b3aa207dd9f9d9379c6a62b92) ([#5382](https://github.com/yt-dlp/yt-dlp/issues/5382)) by [nosoop](https://github.com/nosoop)
    - [Fix `live_status` extraction for playlist videos](https://github.com/yt-dlp/yt-dlp/commit/e63faa101cf7b9bf9f899cabb74ce03c7f893572) by [coletdjnz](https://github.com/coletdjnz)
    - [Fix `uploader_id` extraction](https://github.com/yt-dlp/yt-dlp/commit/149eb0bbf34fa8fdf8d1e2aa28e17479d099e26b) by [bashonly](https://github.com/bashonly)
    - [Fix `ytuser:`](https://github.com/yt-dlp/yt-dlp/commit/08270da5c3454cec1d26c4e34add58158af19a1d) by [pukkandan](https://github.com/pukkandan)
    - [Fix bug in format sorting](https://github.com/yt-dlp/yt-dlp/commit/b25cac650f3cbba16f46c64b0f9b0a96a9171fbc) by [pukkandan](https://github.com/pukkandan)
    - [Fix bug in handling of music URLs](https://github.com/yt-dlp/yt-dlp/commit/a8c754cc00a076f8cba84b477312c35a05cddbc4) by [pukkandan](https://github.com/pukkandan)
    - [Fix duration check for post-live manifestless mode](https://github.com/yt-dlp/yt-dlp/commit/a3fb1ca5abe721b6fcef5f99bfde9f11360488b8) by [pukkandan](https://github.com/pukkandan)
    - [Fix initial player response extraction](https://github.com/yt-dlp/yt-dlp/commit/ee27297f82ccbd702ccd4721d1d3c9d67bbe187e) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Fix live chat for videos with content warning](https://github.com/yt-dlp/yt-dlp/commit/4ce05f57599961c853253398b993c94efb504048) by [coletdjnz](https://github.com/coletdjnz)
    - [Fix live_status](https://github.com/yt-dlp/yt-dlp/commit/6678a4f0b3074f41f02e968d1d48d7c64e48ef07) by [pukkandan](https://github.com/pukkandan)
    - [Fix video like count extraction](https://github.com/yt-dlp/yt-dlp/commit/3ffb2f5bea02ad353411981d342e8db79d57fb88) by [coletdjnz](https://github.com/coletdjnz)
    - [Handle `consent.youtube`](https://github.com/yt-dlp/yt-dlp/commit/b032ff0f032512bd6fc70c9c1994d906eacc06cb) by [pukkandan](https://github.com/pukkandan)
    - [Ignore incomplete data error for comment replies](https://github.com/yt-dlp/yt-dlp/commit/e72e48c53f16771ea7d786deb6b65a40d82a14c4) ([#5490](https://github.com/yt-dlp/yt-dlp/issues/5490)) by [coletdjnz](https://github.com/coletdjnz)
    - [Improve chapter parsing from description](https://github.com/yt-dlp/yt-dlp/commit/2e30b46fe4a04e82d1ec1a21f8d387e5f96405be) by [pukkandan](https://github.com/pukkandan)
    - [Make signature extraction non-fatal](https://github.com/yt-dlp/yt-dlp/commit/52023f129199152fa6da1caad76c1dac0421715d) by [pukkandan](https://github.com/pukkandan)
    - [Mark videos as fully watched](https://github.com/yt-dlp/yt-dlp/commit/06cc8f103b571380b30f03beff94d522930f64e4) ([#4146](https://github.com/yt-dlp/yt-dlp/issues/4146)) by [Brett824](https://github.com/Brett824)
    - [Mark videos as fully watched](https://github.com/yt-dlp/yt-dlp/commit/5318156f1c6e9567b7d44910d3301ca4cc876784) by [bsun0000](https://github.com/bsun0000)
    - [More metadata for storyboards](https://github.com/yt-dlp/yt-dlp/commit/45e8a04e48fc83fb25c2b13f1c0e668b99838ad4) ([#4334](https://github.com/yt-dlp/yt-dlp/issues/4334)) by [ftk](https://github.com/ftk)
    - [Parse translated subtitles only when requested](https://github.com/yt-dlp/yt-dlp/commit/07b47084ba1f041ce5eee005c7a6eea676e3728c) by [pukkandan](https://github.com/pukkandan)
    - [Prevent redirect to unwanted videos](https://github.com/yt-dlp/yt-dlp/commit/a3e964211611ec60a3f84688ab9ff30e4c1504f6) ([#4593](https://github.com/yt-dlp/yt-dlp/issues/4593)) by [coletdjnz](https://github.com/coletdjnz)
    - [Retry manifest refresh for live-from-start](https://github.com/yt-dlp/yt-dlp/commit/253ac4ba6af5d2617275d258d259bcc2c8fa391a) ([#5670](https://github.com/yt-dlp/yt-dlp/issues/5670)) by [mzhou](https://github.com/mzhou)
    - [Subtitles cannot be translated to `und`](https://github.com/yt-dlp/yt-dlp/commit/71eb82d1b2864927b62e0600c41b8b9db4071218) by [pukkandan](https://github.com/pukkandan)
    - [Support `/live/` URL](https://github.com/yt-dlp/yt-dlp/commit/dad2210c0cb9cf03702a9511817ee5ec646d7bc8) by [pukkandan](https://github.com/pukkandan)
    - [Support changing extraction language](https://github.com/yt-dlp/yt-dlp/commit/c26f9b991a0681fd3ea548d535919cec1fbbd430) ([#4470](https://github.com/yt-dlp/yt-dlp/issues/4470)) by [coletdjnz](https://github.com/coletdjnz)
    - [Update iOS Innertube clients](https://github.com/yt-dlp/yt-dlp/commit/224b5a35f7f17fec5639608d31074b8048369385) ([#4792](https://github.com/yt-dlp/yt-dlp/issues/4792)) by [SamantazFox](https://github.com/SamantazFox)
    - [Update invidious and piped instances](https://github.com/yt-dlp/yt-dlp/commit/05799a48c7dec12b34c8bf951c8d2eceedda59f8) ([#6030](https://github.com/yt-dlp/yt-dlp/issues/6030)) by [rohieb](https://github.com/rohieb)
    - [Update piped instances](https://github.com/yt-dlp/yt-dlp/commit/e14ea7fbd92cc15ad0dccedc163f8c26f843c389) ([#5441](https://github.com/yt-dlp/yt-dlp/issues/5441)) by [Generator](https://github.com/Generator)
    - [Update playlist metadata extraction for new layout](https://github.com/yt-dlp/yt-dlp/commit/6141346d18f45412f751a7c8ae21836eb61b5eb2) ([#5376](https://github.com/yt-dlp/yt-dlp/issues/5376)) by [coletdjnz](https://github.com/coletdjnz)
    - [Use device-specific user agent](https://github.com/yt-dlp/yt-dlp/commit/50ac0e5416e0bdff21241852010cad4927e898d6) ([#4770](https://github.com/yt-dlp/yt-dlp/issues/4770)) by [coletdjnz](https://github.com/coletdjnz)
    - [`uploader_id` includes `@` with handle](https://github.com/yt-dlp/yt-dlp/commit/c61cf091a54d3aa3c611722035ccde5ecfe981bb) by [bashonly](https://github.com/bashonly)
    - Fix `: [ytnotifications` extractor](https://github.com/yt-dlp/yt-dlp/commit/c7a7baaa130099aa283dae1f8e583d14ec540ad3) ([#3775](https://github.com/yt-dlp/yt-dlp/issues/3775)) by [coletdjnz](https://github.com/coletdjnz)
    - cleanup: [Fix tests](https://github.com/yt-dlp/yt-dlp/commit/12a1b2254db81caa3c68d4dccb848ca73410e66e) ([#4293](https://github.com/yt-dlp/yt-dlp/issues/4293)) by [sheerluck](https://github.com/sheerluck)
    - tab
        - [Detect `videoRenderer` in `_post_thread_continuation_entries`](https://github.com/yt-dlp/yt-dlp/commit/6b0b0a289a58eca0613e166ff54df6f0c4b32445) by [pukkandan](https://github.com/pukkandan)
        - [Extract metadata from channel items](https://github.com/yt-dlp/yt-dlp/commit/c73355510629e3eda5a79d4e2876a35316ca6ed2) ([#5569](https://github.com/yt-dlp/yt-dlp/issues/5569)) by [coletdjnz](https://github.com/coletdjnz)
        - [Fix video metadata from tabs](https://github.com/yt-dlp/yt-dlp/commit/4dc23a80510d75546f49f8742cf8b704a2efc808) ([#5489](https://github.com/yt-dlp/yt-dlp/issues/5489)) by [coletdjnz](https://github.com/coletdjnz)
        - [Improve continuation items extraction](https://github.com/yt-dlp/yt-dlp/commit/1fb53b946c5aca3755bf72cc1c204925043b04f7) by [pukkandan](https://github.com/pukkandan)
        - [Improvements to tab handling](https://github.com/yt-dlp/yt-dlp/commit/bd7e919a75cd264daabbe50137b2a7c89390c68c) ([#5487](https://github.com/yt-dlp/yt-dlp/issues/5487)) by [pukkandan](https://github.com/pukkandan)
        - [Let `approximate_date` return timestamp](https://github.com/yt-dlp/yt-dlp/commit/5225df50cf96d2f462dc3df3c22f8d1e2028872d) by [pukkandan](https://github.com/pukkandan)
        - [Support `reporthistory` page](https://github.com/yt-dlp/yt-dlp/commit/0a5095fe8d9e944e3832be8125fbb3133500f9cc) by [pukkandan](https://github.com/pukkandan)
        - [Update tab handling for redesign](https://github.com/yt-dlp/yt-dlp/commit/86973308cdf670956a61b3ba6d2c124576843954) ([#5439](https://github.com/yt-dlp/yt-dlp/issues/5439)) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
- YoutubeShortsAudioPivot
    - [Support `source` URLs](https://github.com/yt-dlp/yt-dlp/commit/1dd18a88087d92357c9a2d942ecc4d678ab04641) by [pukkandan](https://github.com/pukkandan)
- YoutubeWebArchive
    - [Improve metadata extraction](https://github.com/yt-dlp/yt-dlp/commit/217753f4aa184a5dac0d7c91c1f95de8b1880474) ([#4968](https://github.com/yt-dlp/yt-dlp/issues/4968)) by [coletdjnz](https://github.com/coletdjnz)
- zattoo
    - [Fix Zattoo resellers](https://github.com/yt-dlp/yt-dlp/commit/f60ef66371825c9f0718817d60ff79e4b2abc52a) ([#4675](https://github.com/yt-dlp/yt-dlp/issues/4675)) by [goggle](https://github.com/goggle)
    - [Fix live streams](https://github.com/yt-dlp/yt-dlp/commit/520876fa09daa62301d602537407b0cfce6c55a1) ([#3812](https://github.com/yt-dlp/yt-dlp/issues/3812)) by [miseran](https://github.com/miseran)
    - [Fix resellers](https://github.com/yt-dlp/yt-dlp/commit/1155ecef29187bff975ceb51c755722c660e0387) by [pukkandan](https://github.com/pukkandan) (With fixes in [48732be](https://github.com/yt-dlp/yt-dlp/commit/48732becfe013849a4191ff467f27b08e04e84fb))
- zdf
    - [Improve format sorting](https://github.com/yt-dlp/yt-dlp/commit/62b2b736e741095d9136c423f37c588fca267d61) ([#4040](https://github.com/yt-dlp/yt-dlp/issues/4040)) by [elyse0](https://github.com/elyse0) (With fixes in [e3aae45](https://github.com/yt-dlp/yt-dlp/commit/e3aae45a6f1ef8c361fe78e8778a5361cade4df7) by [pukkandan](https://github.com/pukkandan))
    - [Use android API endpoint for UHD downloads](https://github.com/yt-dlp/yt-dlp/commit/0fe87a8730638490415d630f48e61d264d89c358) ([#6150](https://github.com/yt-dlp/yt-dlp/issues/6150)) by [seproDev](https://github.com/seproDev)
- zee5
    - [Fix `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/7244895bde622c6aa0f2d858af1989c4b4f7b4aa) ([#5124](https://github.com/yt-dlp/yt-dlp/issues/5124)) by [m4tu4g](https://github.com/m4tu4g)
    - [Generate device ids](https://github.com/yt-dlp/yt-dlp/commit/a5642f2c4a212488ef4d103ae54ed01f6040adf2) ([#5062](https://github.com/yt-dlp/yt-dlp/issues/5062)) by [freezboltz](https://github.com/freezboltz)
    - [Improve `_VALID_URL`](https://github.com/yt-dlp/yt-dlp/commit/385adffcf52cda84195adee0e5216072204a764d) ([#5316](https://github.com/yt-dlp/yt-dlp/issues/5316)) by [m4tu4g](https://github.com/m4tu4g)
    - [Update Device ID](https://github.com/yt-dlp/yt-dlp/commit/0f7247f88e15c424faa0f556e9d2e21ba320f501) ([#4423](https://github.com/yt-dlp/yt-dlp/issues/4423)) by [m4tu4g](https://github.com/m4tu4g)
- zeenews
    - [Add extractor](https://github.com/yt-dlp/yt-dlp/commit/c13a301a94e84d581817a534875e4e2a5c0fdf19) ([#5289](https://github.com/yt-dlp/yt-dlp/issues/5289)) by [m4tu4g](https://github.com/m4tu4g), [pukkandan](https://github.com/pukkandan)
- zenyandex
    - [Fix extractors](https://github.com/yt-dlp/yt-dlp/commit/c9bd65185c0b3b490d0353e139d5484c93bd9774) ([#3750](https://github.com/yt-dlp/yt-dlp/issues/3750), [#5268](https://github.com/yt-dlp/yt-dlp/issues/5268)) by [lksj](https://github.com/lksj), [puc9](https://github.com/puc9), [pukkandan](https://github.com/pukkandan)

#### Downloader changes
- [Add average speed to final progress line](https://github.com/yt-dlp/yt-dlp/commit/3df4f81dfe57e973a4ae79552e13828f616d74ea) by [pukkandan](https://github.com/pukkandan)
- cleanup: [Refactor `report_progress`](https://github.com/yt-dlp/yt-dlp/commit/11233f2afdfc55d3672a7c17ad919a3f70005c19) by [pukkandan](https://github.com/pukkandan)
- aria2c
    - [Disable native progress](https://github.com/yt-dlp/yt-dlp/commit/ad68b16a1e82d0b22b619cea128d52f7d5d2b330) by [pukkandan](https://github.com/pukkandan)
    - [Fix filename containing leading whitespace](https://github.com/yt-dlp/yt-dlp/commit/af7a5eef2f0fce13dbeb375cb97f316292a694c7) ([#5099](https://github.com/yt-dlp/yt-dlp/issues/5099)) by [std-move](https://github.com/std-move)
    - [Native progress for aria2c via RPC](https://github.com/yt-dlp/yt-dlp/commit/8c53322cda75394a8d551dde20b2529ee5ad6e89) ([#3724](https://github.com/yt-dlp/yt-dlp/issues/3724)) by [Lesmiscore](https://github.com/Lesmiscore), [pukkandan](https://github.com/pukkandan)
- external
    - [Smarter detection of executable](https://github.com/yt-dlp/yt-dlp/commit/e1eabd7beb4cc83338a7422546ae1c9ae8b2097f) by [pukkandan](https://github.com/pukkandan)
- ffmpeg
    - [Fix headers for video+audio formats](https://github.com/yt-dlp/yt-dlp/commit/3cf50fa8e9e460fef35531df46b6e893924f1c96) ([#5659](https://github.com/yt-dlp/yt-dlp/issues/5659)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
- fragment
    - [HLS download can continue without first fragment](https://github.com/yt-dlp/yt-dlp/commit/814bba3933ca36a79c68ac737b805cf25c407521) by [pukkandan](https://github.com/pukkandan)
- hls
    - [Allow extractors to provide AES key](https://github.com/yt-dlp/yt-dlp/commit/7e68567e508168b345266c0c19812ad50a829eaa) ([#6158](https://github.com/yt-dlp/yt-dlp/issues/6158)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K)
- ism
    - [Support ec-3 codec](https://github.com/yt-dlp/yt-dlp/commit/81b6102d2099eec78a2db9ae3d101a8503dd4f25) ([#5004](https://github.com/yt-dlp/yt-dlp/issues/5004)) by [nixxo](https://github.com/nixxo)

#### Postprocessor changes
- adobepass
    - [Allow cookies for authenticating MSO](https://github.com/yt-dlp/yt-dlp/commit/b2a2d913100f3f83992dc256b990e6d03f6845e4) by [pukkandan](https://github.com/pukkandan)
- bloomberg
    - [Change playback endpoint](https://github.com/yt-dlp/yt-dlp/commit/7879e79d11a2e5855167820518df49caf623fe48) ([#3857](https://github.com/yt-dlp/yt-dlp/issues/3857)) by [m4tu4g](https://github.com/m4tu4g)
- crunchyroll
    - [Fix language code in _VALID_URLs](https://github.com/yt-dlp/yt-dlp/commit/f1042989c16795b9f75edd7856b1257570ab40e3) by [pukkandan](https://github.com/pukkandan) (With fixes in [964b549](https://github.com/yt-dlp/yt-dlp/commit/964b5493a45445ec13817e3dabca097164044bf7))
- curiositystream
    - [Get `auth_token` from cookie](https://github.com/yt-dlp/yt-dlp/commit/d2ff2c91bbac42e4d84131d7cf23d79c910d5309) ([#3836](https://github.com/yt-dlp/yt-dlp/issues/3836)) by [mnn](https://github.com/mnn)
- dash
    - [Show fragment count with `--live-from-start`](https://github.com/yt-dlp/yt-dlp/commit/36195c4461701ffe4245b126a222b784c7abd1ea) ([#3493](https://github.com/yt-dlp/yt-dlp/issues/3493)) by [flashdagger](https://github.com/flashdagger)
- doc
    - cleanup: [Re-indent "Usage and Options" section](https://github.com/yt-dlp/yt-dlp/commit/2dd5a2e3a1c0fad8441f8e9c7eb77315afcb075b) by [pukkandan](https://github.com/pukkandan)
- embedthumbnail
    - [Detect libatomicparsley.so](https://github.com/yt-dlp/yt-dlp/commit/b5e9a641f537470c8f6fe9d87a33f808c7a9cabb) by [pukkandan](https://github.com/pukkandan)
    - [Fix thumbnail name in mp3](https://github.com/yt-dlp/yt-dlp/commit/e02e6d86dbca8852a8f1df934b8f4a30552060d2) ([#5163](https://github.com/yt-dlp/yt-dlp/issues/5163)) by [How-Bout-No](https://github.com/How-Bout-No)
- ExtractAudio
    - [Allow conditional conversion](https://github.com/yt-dlp/yt-dlp/commit/e0ab98541cec9515d94ada8885a0bb999277f0c0) by [pukkandan](https://github.com/pukkandan)
    - [Handle outtmpl without ext](https://github.com/yt-dlp/yt-dlp/commit/f737fb16d8234408c85bc189ccc926fea000515b) ([#6005](https://github.com/yt-dlp/yt-dlp/issues/6005)) by [carusocr](https://github.com/carusocr)
    - cleanup: [Refactor](https://github.com/yt-dlp/yt-dlp/commit/35faefee5ddb67c447c3206199cc06124600e84d) by [pukkandan](https://github.com/pukkandan)
- f4m
    - [Bugfix](https://github.com/yt-dlp/yt-dlp/commit/95032f302ccaf294e2b16814f3b838c050182475) by [pukkandan](https://github.com/pukkandan)
- ffmpeg
    - [Check version lazily](https://github.com/yt-dlp/yt-dlp/commit/3a85e9cee9a15527987a48f6bf8f77987a3f4a6c) by [pukkandan](https://github.com/pukkandan)
    - [Disable avconv unless `--prefer-avconv`](https://github.com/yt-dlp/yt-dlp/commit/c220d9efc892a5d94feaeb803e5f5f0a85fd2146) by [pukkandan](https://github.com/pukkandan)
    - [Set `ffmpeg_location` in a contextvar](https://github.com/yt-dlp/yt-dlp/commit/6a7d3a0a0981d05903e70bcb31fc3f9438eedf22) by [pukkandan](https://github.com/pukkandan)
    - [Smarter detection of ffprobe filename](https://github.com/yt-dlp/yt-dlp/commit/8420a4d06370d4a3db0f068f5fc9520406d33c40) by [pukkandan](https://github.com/pukkandan)
    - [Write full output to debug on error](https://github.com/yt-dlp/yt-dlp/commit/f67baae17e76997c13d35f65f50be633106837e0) by [pukkandan](https://github.com/pukkandan)
- FFmpegThumbnailsConvertor
    - [Fix conversion from GIF](https://github.com/yt-dlp/yt-dlp/commit/5f2a7f7c4a44aa96054b903534295632044b6ad8) by [pukkandan](https://github.com/pukkandan)
- FFmpegVideoConvertor
    - [Add `gif` to `--recode-video`](https://github.com/yt-dlp/yt-dlp/commit/69f5fe45b98ef3ecb8e5ac69ebebdce7733a3ae4) by [pukkandan](https://github.com/pukkandan)
- FormatSort
    - [Add `mov` to `vext`](https://github.com/yt-dlp/yt-dlp/commit/29ca408219947914b5ce1d2fa1c268a4397719f8) by [pukkandan](https://github.com/pukkandan)
    - [Fix `aext` for `--prefer-free-formats`](https://github.com/yt-dlp/yt-dlp/commit/f2e9fa3ef7a7ce8e18cec53ea7956a3bb36c59ea) by [pukkandan](https://github.com/pukkandan)
- generic
    - [Refactor `_extract_rss`](https://github.com/yt-dlp/yt-dlp/commit/d6bf1161db0aa316229c0bc79352917d27fafa09) by [pukkandan](https://github.com/pukkandan)
- hls
    - [Warn user when trying to download live HLS](https://github.com/yt-dlp/yt-dlp/commit/bbae4377237f7535a738ae94b40dc6f76872f47b) by [pukkandan](https://github.com/pukkandan)
- Hotstar
    - [Bugfix for a1ddaa899ca8693f31f34770f7263ace7e8c8841](https://github.com/yt-dlp/yt-dlp/commit/5d5c0f7e99d121aa0db476b1166828af552aeb14) by [pukkandan](https://github.com/pukkandan)
- http
    - [Ensure the file handle is always closed](https://github.com/yt-dlp/yt-dlp/commit/6d645b5577031d0611acab94a5ca3c88db9042f8) by [pukkandan](https://github.com/pukkandan)
    - [Fix bug in retrying on read timeout in py < 3.10](https://github.com/yt-dlp/yt-dlp/commit/5faf6528fb701724ac32e0a487f92281c7800bda) by [pukkandan](https://github.com/pukkandan)
- kaltura
    - [Support playlists](https://github.com/yt-dlp/yt-dlp/commit/58fb927ebd162daae2787ab8664a0991a70b0e85) ([#4986](https://github.com/yt-dlp/yt-dlp/issues/4986)) by [jwoglom](https://github.com/jwoglom), [pukkandan](https://github.com/pukkandan)
- lbry
    - [Use HEAD request for redirect URL](https://github.com/yt-dlp/yt-dlp/commit/8a40bffaf9e02f73329b8bc66742fb817eda1a64) ([#4181](https://github.com/yt-dlp/yt-dlp/issues/4181)) by [flashdagger](https://github.com/flashdagger)
- metadataparser
    - [Don't set `None` when the field didn't match](https://github.com/yt-dlp/yt-dlp/commit/4f547d6d2cdedc80e65a0a16532f98145c7244df) by [pukkandan](https://github.com/pukkandan)
- mhtml
    - cleanup: [Use imghdr](https://github.com/yt-dlp/yt-dlp/commit/b4daacb4ecd1f686d1a4e204ade6a9b1bb75a5d3) by [pukkandan](https://github.com/pukkandan)
- ModifyChapters
    - [Fix repeated removal of small segments](https://github.com/yt-dlp/yt-dlp/commit/d9473db78ad4c002de53f4cc7c9b045399f8ab72) by [pukkandan](https://github.com/pukkandan)
    - [Handle the entire video being marked for removal](https://github.com/yt-dlp/yt-dlp/commit/a7ddbc0475db14d5249a312e4e03aaf0adc82647) by [pukkandan](https://github.com/pukkandan)
    - [Modify duration in infodict](https://github.com/yt-dlp/yt-dlp/commit/4019bf0525995fe9426ad8e78f366538cc804e62) by [pukkandan](https://github.com/pukkandan)
- options
    - [Fix `parse_known_args` for `--`](https://github.com/yt-dlp/yt-dlp/commit/c800598cd1a3467e53b479c5efc8c6d603d94e5c) by [pukkandan](https://github.com/pukkandan)
    - [Fix aliases to `--config-location`](https://github.com/yt-dlp/yt-dlp/commit/284a60c51600cdee55f025270f8b223d2c45a154) by [pukkandan](https://github.com/pukkandan)
- patreon
    - [Ignore erroneous media attachments](https://github.com/yt-dlp/yt-dlp/commit/cea4b857f0019205b6a473b3a053aa36403892ed) ([#4638](https://github.com/yt-dlp/yt-dlp/issues/4638)) by [coletdjnz](https://github.com/coletdjnz)
- phantomjs
    - [Add function to execute JS without a DOM](https://github.com/yt-dlp/yt-dlp/commit/587021cd9f717181b44e881941aca3f8d753758b) by [MinePlayersPE](https://github.com/MinePlayersPE), [pukkandan](https://github.com/pukkandan) (With fixes in [69082b3](https://github.com/yt-dlp/yt-dlp/commit/69082b38dcb8ba5c6050d86f592c899a0a71760f) by [elyse0](https://github.com/elyse0))
- pyinst
    - [Fix for pyinstaller 5.8](https://github.com/yt-dlp/yt-dlp/commit/2e269bd998c61efaf7500907d114a56e5e83e65e) by [pukkandan](https://github.com/pukkandan)
- rokfin
    - [Implement login](https://github.com/yt-dlp/yt-dlp/commit/e037c405ad57fb3276da133a05226451b9be6478) ([#2992](https://github.com/yt-dlp/yt-dlp/issues/2992)) by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
- rumble
    - [Extract subtitles](https://github.com/yt-dlp/yt-dlp/commit/92922fe7f96ac75bb5f9d87f0a9bef5f51383198) ([#3823](https://github.com/yt-dlp/yt-dlp/issues/3823)) by [fstirlitz](https://github.com/fstirlitz)
- SponsorBlock
    - [Add `type` field](https://github.com/yt-dlp/yt-dlp/commit/1338ae3ba338d116ab75d787cc6d637d382d0f77) by [pukkandan](https://github.com/pukkandan)
    - [Obey `--retry-sleep extractor`](https://github.com/yt-dlp/yt-dlp/commit/8fab23301c79a927592dda710a60903423beffbb) by [pukkandan](https://github.com/pukkandan)
    - [Relax duration check for large segments](https://github.com/yt-dlp/yt-dlp/commit/cd5df121f3577178cb73bafe886677da9452dc42) by [pukkandan](https://github.com/pukkandan)
    - [Support `chapter` category](https://github.com/yt-dlp/yt-dlp/commit/63c547d71ceae6be181948b4b6ce4180b16f4209) ([#5260](https://github.com/yt-dlp/yt-dlp/issues/5260)) by [ajayyy](https://github.com/ajayyy), [pukkandan](https://github.com/pukkandan)
- ThumbnailsConvertor
    - [Allow conditional conversion](https://github.com/yt-dlp/yt-dlp/commit/00bbc5f17710367adc7508062e155547b35edd20) by [pukkandan](https://github.com/pukkandan)
    - [Fix conversion after fixup_webp](https://github.com/yt-dlp/yt-dlp/commit/0e0ce898f6226f712064a8e809cf3c5690789cce) by [pukkandan](https://github.com/pukkandan)
    - [Fix filename escaping](https://github.com/yt-dlp/yt-dlp/commit/8522226d2fea04d48802a9ef402438ff79227fe4) by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
- tiktok
    - [Detect embeds](https://github.com/yt-dlp/yt-dlp/commit/b801cd7179c9546f4054dc534ec4b713e09976a7) by [pukkandan](https://github.com/pukkandan)
- vgtv
    - [Support tv.vg.no](https://github.com/yt-dlp/yt-dlp/commit/dcbf7394ab805babe508e59c0a65e0f88186ce8e) ([#4404](https://github.com/yt-dlp/yt-dlp/issues/4404)) by [sqrtNOT](https://github.com/sqrtNOT)
- VK
    - [Fix playlist URLs](https://github.com/yt-dlp/yt-dlp/commit/5d14b734918c2c1230cd103d013d54ff194617f7) ([#4930](https://github.com/yt-dlp/yt-dlp/issues/4930)) by [the-marenga](https://github.com/the-marenga)
- WatchESPN
    - [Support free videos and BAM_DTC](https://github.com/yt-dlp/yt-dlp/commit/0a4fb0d3fe8ff5f55e9bfd9aec47ed251fd41615) ([#4118](https://github.com/yt-dlp/yt-dlp/issues/4118)) by [ischmidt20](https://github.com/ischmidt20)
- webvtt
    - [Handle premature EOF](https://github.com/yt-dlp/yt-dlp/commit/f352a0977879a6210b1519036fc75e9d423f277c) by [flashdagger](https://github.com/flashdagger)
    - extractor/youtube: [Extract auto-subs from livestream VODs](https://github.com/yt-dlp/yt-dlp/commit/c646d76f6717a646dd35f6efad6b396435f9fa55) by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
- youtube
    - [Add warning for PostLiveDvr](https://github.com/yt-dlp/yt-dlp/commit/829bbd1d05ae7e4519327f1cb6e75b3da38e0a0b) by [pukkandan](https://github.com/pukkandan)
    - [Extract `comment_count` from webpage](https://github.com/yt-dlp/yt-dlp/commit/0df111a371f191a2513e681ec30fc8563545c983) by [pukkandan](https://github.com/pukkandan)
    - [Fix error reporting of "Incomplete data"](https://github.com/yt-dlp/yt-dlp/commit/3ce2933693b66e5e8948352609c8258d8d2cec15) by [pukkandan](https://github.com/pukkandan)
    - [Improve format sorting for IOS formats](https://github.com/yt-dlp/yt-dlp/commit/5c6d2ef9d1001508407d7825d731013f3cb99f5f) by [pukkandan](https://github.com/pukkandan)
    - [Improve signature caching](https://github.com/yt-dlp/yt-dlp/commit/580ce007827e208edd1a72278c0b799cbb3bc251) by [pukkandan](https://github.com/pukkandan)
    - clips: [Support downloading clips](https://github.com/yt-dlp/yt-dlp/commit/471d0367c76e1413bb35e0be45765a277e469ee2) by [pukkandan](https://github.com/pukkandan)
    - twitch: [Allow waiting for channels to become live](https://github.com/yt-dlp/yt-dlp/commit/693f060040967e0ce5d9769d64b0cdd059c054d2) by [pukkandan](https://github.com/pukkandan)

#### Misc. changes
- build
    - [Add Linux standalone builds](https://github.com/yt-dlp/yt-dlp/commit/e4afcfde08cbd40147e75c924768f1598ece1885) by [pukkandan](https://github.com/pukkandan)
    - [Add `cffi` as a dependency for `yt_dlp_linux`](https://github.com/yt-dlp/yt-dlp/commit/776d1c3f0c9b00399896dd2e40e78e9a43218109) by [bashonly](https://github.com/bashonly)
    - [Add `make uninstall`](https://github.com/yt-dlp/yt-dlp/commit/b4d373833856ef464e0c7c197d0f0581f34e0efe) ([#3747](https://github.com/yt-dlp/yt-dlp/issues/3747)) by [MrRawes](https://github.com/MrRawes)
    - [Add minimal `pyproject.toml`](https://github.com/yt-dlp/yt-dlp/commit/e9df3d42c48428a41b98fcfd065f89a6c12c7149) by [pukkandan](https://github.com/pukkandan)
    - [Automated builds and nightly releases](https://github.com/yt-dlp/yt-dlp/commit/29cb20bd563c02671b31dd840139e93dd37150a1) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K) (With fixes in [bfc861a](https://github.com/yt-dlp/yt-dlp/commit/bfc861a91ee65c9b0ac169754f512e052c6827cf) by [pukkandan](https://github.com/pukkandan))
    - [Consistent order for lazy extractors](https://github.com/yt-dlp/yt-dlp/commit/5b836d47392d2ffb7205a30ac2b5786b208c3238) ([#4220](https://github.com/yt-dlp/yt-dlp/issues/4220)) by [lamby](https://github.com/lamby)
    - [Create armv7l and aarch64 releases](https://github.com/yt-dlp/yt-dlp/commit/17fc3dc48af968e28c23197ed06542fdb47aba2b) ([#5449](https://github.com/yt-dlp/yt-dlp/issues/5449)) by [MrOctopus](https://github.com/MrOctopus), [pukkandan](https://github.com/pukkandan)
    - [Draft release until complete](https://github.com/yt-dlp/yt-dlp/commit/c2c8921b419a4a9b41b99eab9a155245bdd5f7a4) by [pukkandan](https://github.com/pukkandan)
    - [Exclude devscripts from installs](https://github.com/yt-dlp/yt-dlp/commit/460eb9c50e0970fdceb51485c5fe3268574c48e8) by [pukkandan](https://github.com/pukkandan)
    - [Fix architecture suffix of executables](https://github.com/yt-dlp/yt-dlp/commit/5200976949b93bc937a95d4453985e5e1a1160e2) ([#4355](https://github.com/yt-dlp/yt-dlp/issues/4355)) by [odo2063](https://github.com/odo2063) (With fixes in [d08e1e6](https://github.com/yt-dlp/yt-dlp/commit/d08e1e68758d5041afa79abd6a2d7dd1c45879d8) by [pukkandan](https://github.com/pukkandan))
    - [Fix changelog](https://github.com/yt-dlp/yt-dlp/commit/81e019599835fdb76e661c4b54043eea4ebffff4) by [pukkandan](https://github.com/pukkandan)
    - [Fix publishing to PyPI and homebrew](https://github.com/yt-dlp/yt-dlp/commit/55676fe498345a389a2539d8baaba958d6d61c3e) by [bashonly](https://github.com/bashonly)
    - [Fix release tag commit](https://github.com/yt-dlp/yt-dlp/commit/885fe351fbee9f7b5fe52576c8917c0baefebe37) by [pukkandan](https://github.com/pukkandan)
    - [Fix updating homebrew formula](https://github.com/yt-dlp/yt-dlp/commit/1ed70fd0b7b8434d4542f8472ac08af6d9d9e986) by [pukkandan](https://github.com/pukkandan)
    - [Improve `setup.py`](https://github.com/yt-dlp/yt-dlp/commit/7b84d6f9b32aa432189db5b481c33bcca2b47da0) by [pukkandan](https://github.com/pukkandan)
    - [Improve build process](https://github.com/yt-dlp/yt-dlp/commit/c4b6c5c7c9eb0aa448d03c1540580cdd92737aa8) ([#4513](https://github.com/yt-dlp/yt-dlp/issues/4513)) by [shirt-dev](https://github.com/shirt-dev)
    - [Make linux binary truly standalone using `conda`](https://github.com/yt-dlp/yt-dlp/commit/a6858cda296b532db3fd7bcfc4f960f9b2fdf30a) ([#5423](https://github.com/yt-dlp/yt-dlp/issues/5423)) by [mlampe](https://github.com/mlampe)
    - [More test-runners](https://github.com/yt-dlp/yt-dlp/commit/7a96d0b39c34c6c8c42cc6aaac90dd8d0f5a51d7) by [pukkandan](https://github.com/pukkandan)
    - [Pin `py2exe` version](https://github.com/yt-dlp/yt-dlp/commit/98d4ec1ef287cc5655ce6afd7b17755c57a245cb) by [pukkandan](https://github.com/pukkandan)
    - [Replace `set-output` with `GITHUB_OUTPUT`](https://github.com/yt-dlp/yt-dlp/commit/7d61d2306e36d31ad992df4e332be4ff8c708ef8) ([#5315](https://github.com/yt-dlp/yt-dlp/issues/5315)) by [Lesmiscore](https://github.com/Lesmiscore)
    - [Sign SHA files and release public key](https://github.com/yt-dlp/yt-dlp/commit/12647e03d417feaa9ea6a458bea5ebd747494a53) by [Grub4K](https://github.com/Grub4K)
    - [Standalone x64 builds for MacOS 10.9](https://github.com/yt-dlp/yt-dlp/commit/6d916fe709a38e8c4c69b73843acf170b5165931) ([#4106](https://github.com/yt-dlp/yt-dlp/issues/4106)) by [StefanLobbenmeier](https://github.com/StefanLobbenmeier) (With fixes in [28cdb60](https://github.com/yt-dlp/yt-dlp/commit/28cdb605aab484b17f808a68c17973daad967c4f), [63da2d0](https://github.com/yt-dlp/yt-dlp/commit/63da2d0911373e309aab797b062c4e372292e096) by [pukkandan](https://github.com/pukkandan), [StefanLobbenmeier](https://github.com/StefanLobbenmeier))
    - [Update pyinstaller](https://github.com/yt-dlp/yt-dlp/commit/8ef5af19421c3bc2f6f8f3c515dda80d4a6ce2d4) by [pukkandan](https://github.com/pukkandan)
    - [Update pyinstaller](https://github.com/yt-dlp/yt-dlp/commit/9f9c85dda4953923d710ca9d24b2e433ec26e882) by [pukkandan](https://github.com/pukkandan)
    - [Update pyinstaller](https://github.com/yt-dlp/yt-dlp/commit/365b9006051ac7d735c20bb63c4907b758233048) by [pukkandan](https://github.com/pukkandan)
    - [`make tar' should not follow `DESTDIR`](https://github.com/yt-dlp/yt-dlp/commit/50a399326fa82e2e5fe3f2829da5a31407adafaa) ([#4790](https://github.com/yt-dlp/yt-dlp/issues/4790)) by [satan1st](https://github.com/satan1st)
    - `py2exe`: [Migrate to freeze API](https://github.com/yt-dlp/yt-dlp/commit/dc3028d233b2f7091215dc0d9acc522914b9b59d) ([#5149](https://github.com/yt-dlp/yt-dlp/issues/5149)) by [pukkandan](https://github.com/pukkandan), [SG5](https://github.com/SG5)
    - cleanup: [Refactor](https://github.com/yt-dlp/yt-dlp/commit/b5899f4f19116bb4d98907413fa3fb84a952ef13) by [pukkandan](https://github.com/pukkandan)
    - devscripts: [Add devscript to set a build variant](https://github.com/yt-dlp/yt-dlp/commit/70b2340909d8d917f71d20181614fd7392d3f7f0) by [pukkandan](https://github.com/pukkandan)
    - test: [Harden workflows' security](https://github.com/yt-dlp/yt-dlp/commit/c789fb778798d682a1b2d3c74180ba8d20c23552) ([#5410](https://github.com/yt-dlp/yt-dlp/issues/5410)) by [sashashura](https://github.com/sashashura)
- cleanup
    - [Consistent style for file heads](https://github.com/yt-dlp/yt-dlp/commit/54007a45f11ed730352324289b714baefd2901eb) by [pukkandan](https://github.com/pukkandan)
    - [Deprecate `YoutubeDL.parse_outtmpl`](https://github.com/yt-dlp/yt-dlp/commit/bf1824b391e2f18b7e927f54340c0aabfa9399cd) by [pukkandan](https://github.com/pukkandan)
    - [Fix `Changelog`](https://github.com/yt-dlp/yt-dlp/commit/17ca19ab60a6a13eb8a629c51442b5248b0d8394) by [pukkandan](https://github.com/pukkandan)
    - [Fix flake8 and minor refactor](https://github.com/yt-dlp/yt-dlp/commit/7a32c70d13558977ec4e26900d6d4b0aa8614713) by [pukkandan](https://github.com/pukkandan)
    - [Fix some typos](https://github.com/yt-dlp/yt-dlp/commit/962ffcf89c8d935410391fbea3580688aafe76d7) ([#4194](https://github.com/yt-dlp/yt-dlp/issues/4194)) by [crazymoose77756](https://github.com/crazymoose77756)
    - [Use `random.choices`](https://github.com/yt-dlp/yt-dlp/commit/efa944f4bc892321a0d01dcddb210405761ecada) ([#5800](https://github.com/yt-dlp/yt-dlp/issues/5800)) by [freezboltz](https://github.com/freezboltz)
    - extractor: [Rename `extractors.py` to `_extractors.py`](https://github.com/yt-dlp/yt-dlp/commit/99d10bf60796a90d2ca421ec63f1208b15ae5f48) by [pukkandan](https://github.com/pukkandan)
    - jsinterp: [Give functions names to help debugging](https://github.com/yt-dlp/yt-dlp/commit/b2e0343ba0fc5d8702e90f6ba2b71358e2677e0b) by [pukkandan](https://github.com/pukkandan)
    - utils: [Don't use kwargs for `format_field`](https://github.com/yt-dlp/yt-dlp/commit/a70635b8a1bcf42bf587fe3cd7503f1d092009ce) by [pukkandan](https://github.com/pukkandan)
    - Miscellaneous
        - [08e29b9](https://github.com/yt-dlp/yt-dlp/commit/08e29b9f1f0b6e5fe1c1e87bf8169bfd7ac91d57), [1e4fca9](https://github.com/yt-dlp/yt-dlp/commit/1e4fca9a87b0ff6b7316261a2f081493af3885b2), [2163367](https://github.com/yt-dlp/yt-dlp/commit/21633673c33f082c6673bc245e4a90d880729a58), [2414649](https://github.com/yt-dlp/yt-dlp/commit/241464919271278831f23b3a086dcf57aeb80d3b), [31b532a](https://github.com/yt-dlp/yt-dlp/commit/31b532a1f261347bd1499968a1de9ed09943e87f), [46d09f8](https://github.com/yt-dlp/yt-dlp/commit/46d09f87072e112c363f4a573966d8e48a788562), [4815bbf](https://github.com/yt-dlp/yt-dlp/commit/4815bbfc41cf641e4a0650289dbff968cb3bde76), [56ba69e](https://github.com/yt-dlp/yt-dlp/commit/56ba69e4c991e81a449882258be08d0b6b98c648), [5b28cef](https://github.com/yt-dlp/yt-dlp/commit/5b28cef72db3b531680d89c121631c73ae05354f), [6368e2e](https://github.com/yt-dlp/yt-dlp/commit/6368e2e639bca7e66609911d2672b6a9dc65b052), [71df9b7](https://github.com/yt-dlp/yt-dlp/commit/71df9b7fd504767583cf1e088ae307c942799f2b), [7b2c3f4](https://github.com/yt-dlp/yt-dlp/commit/7b2c3f47c6b586a208655fcfc716bba3f8619d1e), [8a82af3](https://github.com/yt-dlp/yt-dlp/commit/8a82af3511b4379af0d239dbd01c672c17a2c46a), [998a3ca](https://github.com/yt-dlp/yt-dlp/commit/998a3cae0ca2e2276ea02a3470c7e083feec96f5), [a057779](https://github.com/yt-dlp/yt-dlp/commit/a057779d5e706f7bb8721a6c46cca47f0925f682), [a538772](https://github.com/yt-dlp/yt-dlp/commit/a5387729696a5b33f53f60ef06f48e45663b12dd), [a831c2e](https://github.com/yt-dlp/yt-dlp/commit/a831c2ea9041557fdcd4abed0a449ef7bbca13e2), [ae61d10](https://github.com/yt-dlp/yt-dlp/commit/ae61d108dd83a951b6e8a27e1fb969682416150d), [c487cf0](https://github.com/yt-dlp/yt-dlp/commit/c487cf00101525ff836d59a2a42ef63e85ea9556), [c6e07cf](https://github.com/yt-dlp/yt-dlp/commit/c6e07cf1e16ff3d1a0691067249ba3777f8c0bcb), [deae7c1](https://github.com/yt-dlp/yt-dlp/commit/deae7c171180ddd4735c414306f084f86ef27e07), [edfc772](https://github.com/yt-dlp/yt-dlp/commit/edfc7725b1f2b4f7838836ca0df613ec0e058cac), [f2df407](https://github.com/yt-dlp/yt-dlp/commit/f2df4071651d124bf7bad47648a6eb7a9ce57369), [f5ea474](https://github.com/yt-dlp/yt-dlp/commit/f5ea47488a2c59b2520b4988b7eab4d8830e3077) by [pukkandan](https://github.com/pukkandan)
        - [e121e3c](https://github.com/yt-dlp/yt-dlp/commit/e121e3cee731426f620e17939141018d09661fa2) by [christoph-heinrich](https://github.com/christoph-heinrich)
        - [d2c8aad](https://github.com/yt-dlp/yt-dlp/commit/d2c8aadf799a63aaa7da81ae03052b1ec2addd20) by [DavidH-2022](https://github.com/DavidH-2022), [MrRawes](https://github.com/MrRawes), [pukkandan](https://github.com/pukkandan)
        - [304ad45](https://github.com/yt-dlp/yt-dlp/commit/304ad45a9b18cba7b62e7cb435fb0ddc49003ed7) by [gamer191](https://github.com/gamer191), [pukkandan](https://github.com/pukkandan)
        - [7aaf4cd](https://github.com/yt-dlp/yt-dlp/commit/7aaf4cd2a8fd8ecf2123b981782c3d12dce80d78) by [Alienmaster](https://github.com/Alienmaster), [pukkandan](https://github.com/pukkandan)
        - [1890fc6](https://github.com/yt-dlp/yt-dlp/commit/1890fc6389393ffaa05fa27bd47717f4d862404f) by [flashdagger](https://github.com/flashdagger), [gamer191](https://github.com/gamer191), [pukkandan](https://github.com/pukkandan)
        - [64fa820](https://github.com/yt-dlp/yt-dlp/commit/64fa820ccf61a7aea6c2a48b1362b3a4ec270cad) by [kwconder](https://github.com/kwconder), [Lesmiscore](https://github.com/Lesmiscore), [MrRawes](https://github.com/MrRawes), [pukkandan](https://github.com/pukkandan)
- devscripts
    - [Create `utils` and refactor](https://github.com/yt-dlp/yt-dlp/commit/115add43876964956917bf596c1d0b148c5b3c26) by [pukkandan](https://github.com/pukkandan)
    - [Fix import](https://github.com/yt-dlp/yt-dlp/commit/96623ab5c6cea59c22395a47f00a13d334de6106) by [pukkandan](https://github.com/pukkandan)
    - [Provide pyinstaller hooks](https://github.com/yt-dlp/yt-dlp/commit/acb1042a9ffa8769fe691beac1011d6da1fcf321) by [pukkandan](https://github.com/pukkandan)
    - [Script to generate changelog](https://github.com/yt-dlp/yt-dlp/commit/d400e261cf029a3f20d364113b14de973be75404) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [Grub4K](https://github.com/Grub4K) (With fixes in [9344964](https://github.com/yt-dlp/yt-dlp/commit/93449642815a6973a4b09b289982ca7e1f961b5f))
    - make_lazy_extractors: [Fix for Docker](https://github.com/yt-dlp/yt-dlp/commit/46d72cd2c7fced093189babb484d53766f52ef57) ([#4958](https://github.com/yt-dlp/yt-dlp/issues/4958)) by [josanabr](https://github.com/josanabr)
- docs
    - [Clarify `best*`](https://github.com/yt-dlp/yt-dlp/commit/30389593c26d3b014b76746ebf751b731d1db6d0) by [pukkandan](https://github.com/pukkandan)
    - [Consistent use of `e.g.`](https://github.com/yt-dlp/yt-dlp/commit/62b58c0936cccc6f3e5115086406c7bfaf6fc551) ([#4643](https://github.com/yt-dlp/yt-dlp/issues/4643)) by [Lesmiscore](https://github.com/Lesmiscore)
    - [Fix bug report issue template](https://github.com/yt-dlp/yt-dlp/commit/81bf0943eaa04069125dc683c418b65c2dbb7e25) by [pukkandan](https://github.com/pukkandan)
    - [Fix capitalization in references](https://github.com/yt-dlp/yt-dlp/commit/d4ada3574ee1e68c8cf2a695378470fddb569c39) ([#4515](https://github.com/yt-dlp/yt-dlp/issues/4515)) by [christoph-heinrich](https://github.com/christoph-heinrich)
    - [Improve docstring of `download_ranges`](https://github.com/yt-dlp/yt-dlp/commit/0f44636597636cfa9065ee2fa4b7308b203c6a8e) ([#4340](https://github.com/yt-dlp/yt-dlp/issues/4340)) by [FirefoxMetzger](https://github.com/FirefoxMetzger)
    - [Improve issue templates](https://github.com/yt-dlp/yt-dlp/commit/ca9f1df25346816baacb13e875f3873c47be86e2) by [pukkandan](https://github.com/pukkandan)
    - [Improvements](https://github.com/yt-dlp/yt-dlp/commit/8aa0e7cd96a1e2f315d49744793ae07f6543ce4c) by [pukkandan](https://github.com/pukkandan)
    - [Improvements](https://github.com/yt-dlp/yt-dlp/commit/17ffed184237b3686212cc73290e5cdd0f6f20ca) by [pukkandan](https://github.com/pukkandan)
    - [Improvements](https://github.com/yt-dlp/yt-dlp/commit/8e174ba7dee040d3fb4e14b21b39c3993dd79dd1) by [pukkandan](https://github.com/pukkandan)
    - [Misc improvements](https://github.com/yt-dlp/yt-dlp/commit/2fa669f759eae6d5c7e608e3ee628f9d60d03e83) by [pukkandan](https://github.com/pukkandan)
    - [Separate notes about environment variables](https://github.com/yt-dlp/yt-dlp/commit/878eac3e2e3dfc0b811e9575056d89e19e060e79) by [pukkandan](https://github.com/pukkandan)
    - devscripts: [Document `pyinst`'s argument passthrough](https://github.com/yt-dlp/yt-dlp/commit/73ac0e6b857ca138481594cb24d9532ba2714a02) ([#5235](https://github.com/yt-dlp/yt-dlp/issues/5235)) by [jahway603](https://github.com/jahway603)
- pyinstaller
    - [Analyze sub-modules of `Cryptodome`](https://github.com/yt-dlp/yt-dlp/commit/b85faf6ffb700058e774e99c04304a7a9257cdd0) by [pukkandan](https://github.com/pukkandan)
- test
    - [Allow `extract_flat` in download tests](https://github.com/yt-dlp/yt-dlp/commit/495322b95bbf8befa0f0b354f110a1d4eddac784) by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    - [Fix `FakeYDL` signatures](https://github.com/yt-dlp/yt-dlp/commit/f0500bd1e4e3910abd58a1be812ba35fc20049e7) by [coletdjnz](https://github.com/coletdjnz)
    - [Fix test_youtube_signature](https://github.com/yt-dlp/yt-dlp/commit/90a1df305b628c78a497cf4010fb68cad856a314) by [pukkandan](https://github.com/pukkandan)
    - [Split download tests so they can be more easily run in CI](https://github.com/yt-dlp/yt-dlp/commit/258d88f3011a2226361c0642ff680840d49e8092) by [pukkandan](https://github.com/pukkandan)
- update-formulae
    - [Do not change dependency section](https://github.com/yt-dlp/yt-dlp/commit/5c0dc6e6035c4b92aa1a254ebb0284be75dd0d2b) by [pukkandan](https://github.com/pukkandan)

### 2023.03.03

#### Important changes
- **A new release type has been added!**
    * [`nightly`](https://github.com/yt-dlp/yt-dlp/releases/tag/nightly) builds will be made after each push, containing the latest fixes (but also possibly bugs).
    * When using `--update`/`-U`, a release binary will only update to its current channel (either `stable` or `nightly`).
    * The `--update-to` option has been added allowing the user more control over program upgrades (or downgrades).
    * `--update-to` can change the release channel (`stable`, `nightly`) and also upgrade or downgrade to specific tags.
    * **Usage**: `--update-to CHANNEL`, `--update-to TAG`, `--update-to CHANNEL@TAG`
- **YouTube throttling fixes!**

#### Core changes
- [Add option `--break-match-filters`](https://github.com/yt-dlp/yt-dlp/commit/fe2ce85aff0aa03735fc0152bb8cb9c3d4ef0753) by [pukkandan](https://github.com/pukkandan)
- [Fix `--break-on-existing` with `--lazy-playlist`](https://github.com/yt-dlp/yt-dlp/commit/d21056f4cf0a1623daa107f9181074f5725ac436) by [pukkandan](https://github.com/pukkandan)
- dependencies
    - [Simplify `Cryptodome`](https://github.com/yt-dlp/yt-dlp/commit/65f6e807804d2af5e00f2aecd72bfc43af19324a) by [pukkandan](https://github.com/pukkandan)
- jsinterp
    - [Handle `Date` at epoch 0](https://github.com/yt-dlp/yt-dlp/commit/9acf1ee25f7ad3920ede574a9de95b8c18626af4) by [pukkandan](https://github.com/pukkandan)
- plugins
    - [Don't look in `.egg` directories](https://github.com/yt-dlp/yt-dlp/commit/b059188383eee4fa336ef728dda3ff4bb7335625) by [pukkandan](https://github.com/pukkandan)
- update
    - [Add option `--update-to`, including to nightly](https://github.com/yt-dlp/yt-dlp/commit/77df20f14cc9ed41dfe3a1fe2d77fd27f5365a94) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K), [pukkandan](https://github.com/pukkandan)
- utils
    - `LenientJSONDecoder`: [Parse unclosed objects](https://github.com/yt-dlp/yt-dlp/commit/cc09083636ce21e58ff74f45eac2dbda507462b0) by [pukkandan](https://github.com/pukkandan)
    - `Popen`: [Shim undocumented `text_mode` property](https://github.com/yt-dlp/yt-dlp/commit/da8e2912b165005f76779a115a071cd6132ceedf) by [Grub4K](https://github.com/Grub4K)

#### Extractor changes
- [Fix DRM detection in m3u8](https://github.com/yt-dlp/yt-dlp/commit/43a3eaf96393b712d60cbcf5c6cb1e90ed7f42f5) by [pukkandan](https://github.com/pukkandan)
- generic
    - [Detect manifest links via extension](https://github.com/yt-dlp/yt-dlp/commit/b38cae49e6f4849c8ee2a774bdc3c1c647ae5f0e) by [bashonly](https://github.com/bashonly)
    - [Handle basic-auth when checking redirects](https://github.com/yt-dlp/yt-dlp/commit/8e9fe43cd393e69fa49b3d842aa3180c1d105b8f) by [pukkandan](https://github.com/pukkandan)
- GoogleDrive
    - [Fix some audio](https://github.com/yt-dlp/yt-dlp/commit/4d248e29d20d983ededab0b03d4fe69dff9eb4ed) by [pukkandan](https://github.com/pukkandan)
- iprima
    - [Fix extractor](https://github.com/yt-dlp/yt-dlp/commit/9fddc12ab022a31754e0eaa358fc4e1dfa974587) ([#6291](https://github.com/yt-dlp/yt-dlp/issues/6291)) by [std-move](https://github.com/std-move)
- mediastream
    - [Improve WinSports support](https://github.com/yt-dlp/yt-dlp/commit/2d5a8c5db2bd4ff1c2e45e00cd890a10f8ffca9e) ([#6401](https://github.com/yt-dlp/yt-dlp/issues/6401)) by [bashonly](https://github.com/bashonly)
- ntvru
    - [Extract HLS and DASH formats](https://github.com/yt-dlp/yt-dlp/commit/77d6d136468d0c23c8e79bc937898747804f585a) ([#6403](https://github.com/yt-dlp/yt-dlp/issues/6403)) by [bashonly](https://github.com/bashonly)
- tencent
    - [Add more formats and info](https://github.com/yt-dlp/yt-dlp/commit/18d295c9e0f95adc179eef345b7af64d6372db78) ([#5950](https://github.com/yt-dlp/yt-dlp/issues/5950)) by [Hill-98](https://github.com/Hill-98)
- yle_areena
    - [Extract non-Kaltura videos](https://github.com/yt-dlp/yt-dlp/commit/40d77d89027cd0e0ce31d22aec81db3e1d433900) ([#6402](https://github.com/yt-dlp/yt-dlp/issues/6402)) by [bashonly](https://github.com/bashonly)
- youtube
    - [Construct dash formats with `range` query](https://github.com/yt-dlp/yt-dlp/commit/5038f6d713303e0967d002216e7a88652401c22a) by [pukkandan](https://github.com/pukkandan) (With fixes in [f34804b](https://github.com/yt-dlp/yt-dlp/commit/f34804b2f920f62a6e893a14a9e2a2144b14dd23) by [bashonly](https://github.com/bashonly), [coletdjnz](https://github.com/coletdjnz))
    - [Detect and break on looping comments](https://github.com/yt-dlp/yt-dlp/commit/7f51861b1820c37b157a239b1fe30628d907c034) ([#6301](https://github.com/yt-dlp/yt-dlp/issues/6301)) by [coletdjnz](https://github.com/coletdjnz)
    - [Extract channel `view_count` when `/about` tab is passed](https://github.com/yt-dlp/yt-dlp/commit/31e183557fcd1b937582f9429f29207c1261f501) by [pukkandan](https://github.com/pukkandan)

#### Misc. changes
- build
    - [Add `cffi` as a dependency for `yt_dlp_linux`](https://github.com/yt-dlp/yt-dlp/commit/776d1c3f0c9b00399896dd2e40e78e9a43218109) by [bashonly](https://github.com/bashonly)
    - [Automated builds and nightly releases](https://github.com/yt-dlp/yt-dlp/commit/29cb20bd563c02671b31dd840139e93dd37150a1) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [bashonly](https://github.com/bashonly), [Grub4K](https://github.com/Grub4K) (With fixes in [bfc861a](https://github.com/yt-dlp/yt-dlp/commit/bfc861a91ee65c9b0ac169754f512e052c6827cf) by [pukkandan](https://github.com/pukkandan))
    - [Sign SHA files and release public key](https://github.com/yt-dlp/yt-dlp/commit/12647e03d417feaa9ea6a458bea5ebd747494a53) by [Grub4K](https://github.com/Grub4K)
- cleanup
    - [Fix `Changelog`](https://github.com/yt-dlp/yt-dlp/commit/17ca19ab60a6a13eb8a629c51442b5248b0d8394) by [pukkandan](https://github.com/pukkandan)
    - jsinterp: [Give functions names to help debugging](https://github.com/yt-dlp/yt-dlp/commit/b2e0343ba0fc5d8702e90f6ba2b71358e2677e0b) by [pukkandan](https://github.com/pukkandan)
    - Miscellaneous: [4815bbf](https://github.com/yt-dlp/yt-dlp/commit/4815bbfc41cf641e4a0650289dbff968cb3bde76), [5b28cef](https://github.com/yt-dlp/yt-dlp/commit/5b28cef72db3b531680d89c121631c73ae05354f) by [pukkandan](https://github.com/pukkandan)
- devscripts
    - [Script to generate changelog](https://github.com/yt-dlp/yt-dlp/commit/d400e261cf029a3f20d364113b14de973be75404) ([#6220](https://github.com/yt-dlp/yt-dlp/issues/6220)) by [Grub4K](https://github.com/Grub4K) (With fixes in [9344964](https://github.com/yt-dlp/yt-dlp/commit/93449642815a6973a4b09b289982ca7e1f961b5f))

### 2023.02.17

* Merge youtube-dl: Upto [commit/2dd6c6e](https://github.com/ytdl-org/youtube-dl/commit/2dd6c6e)
* Fix `--concat-playlist`
* Imply `--no-progress` when `--print`
* Improve default subtitle language selection by [sdht0](https://github.com/sdht0)
* Make `title` completely non-fatal
* Sanitize formats before sorting by [pukkandan](https://github.com/pukkandan)
* Support module level `__bool__` and `property`
* [dependencies] Standardize `Cryptodome` imports
* [hls] Allow extractors to provide AES key by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [ExtractAudio] Handle outtmpl without ext by [carusocr](https://github.com/carusocr)
* [extractor/common] Fix `_search_nuxt_data` by [LowSuggestion912](https://github.com/LowSuggestion912)
* [extractor/generic] Avoid catastrophic backtracking in KVS regex by [bashonly](https://github.com/bashonly)
* [jsinterp] Support `if` statements
* [plugins] Fix zip search paths
* [utils] `traverse_obj`:  Various improvements by [Grub4K](https://github.com/Grub4K)
* [utils] `traverse_obj`: Fix more bugs
* [utils] `traverse_obj`: Fix several behavioral problems by [Grub4K](https://github.com/Grub4K)
* [utils] Don't use Content-length with encoding by [felixonmars](https://github.com/felixonmars)
* [utils] Fix `time_seconds` to use the provided TZ by [Grub4K](https://github.com/Grub4K), [Lesmiscore](https://github.com/Lesmiscore)
* [utils] Fix race condition in `make_dir` by [aionescu](https://github.com/aionescu)
* [utils] Use local kernel32 for file locking on Windows by [Grub4K](https://github.com/Grub4K)
* [compat_utils] Improve `passthrough_module`
* [compat_utils] Simplify `EnhancedModule`
* [build] Update pyinstaller
* [pyinst] Fix for pyinstaller 5.8
* [devscripts] Provide `pyinstaller` hooks
* [devscripts/pyinstaller] Analyze sub-modules of `Cryptodome`
* [cleanup] Misc fixes and cleanup
* [extractor/anchorfm] Add episode extractor by [HobbyistDev](https://github.com/HobbyistDev), [bashonly](https://github.com/bashonly)
* [extractor/boxcast] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/ebay] Add extractor by [JChris246](https://github.com/JChris246)
* [extractor/hypergryph] Add extractor by [HobbyistDev](https://github.com/HobbyistDev), [bashonly](https://github.com/bashonly)
* [extractor/NZOnScreen] Add extractor by [gregsadetsky](https://github.com/gregsadetsky), [pukkandan](https://github.com/pukkandan)
* [extractor/rozhlas] Add extractor RozhlasVltavaIE by [amra](https://github.com/amra)
* [extractor/tempo] Add IVXPlayer extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/txxx] Add extractors by [chio0hai](https://github.com/chio0hai)
* [extractor/vocaroo] Add extractor by [SuperSonicHub1](https://github.com/SuperSonicHub1), [qbnu](https://github.com/qbnu)
* [extractor/wrestleuniverse] Add extractors by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [extractor/yappy] Add extractor by [HobbyistDev](https://github.com/HobbyistDev), [dirkf](https://github.com/dirkf)
* [extractor/youtube] **Fix `uploader_id` extraction** by [bashonly](https://github.com/bashonly)
* [extractor/youtube] Add hyperpipe instances by [Generator](https://github.com/Generator)
* [extractor/youtube] Handle `consent.youtube`
* [extractor/youtube] Support `/live/` URL
* [extractor/youtube] Update invidious and piped instances by [rohieb](https://github.com/rohieb)
* [extractor/91porn] Fix title and comment extraction by [pmitchell86](https://github.com/pmitchell86)
* [extractor/AbemaTV] Cache user token whenever appropriate by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/bfmtv] Support `rmc` prefix by [carusocr](https://github.com/carusocr)
* [extractor/biliintl] Add intro and ending chapters by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/clyp] Support `wav` by [qulaz](https://github.com/qulaz)
* [extractor/crunchyroll] Add intro chapter by [ByteDream](https://github.com/ByteDream)
* [extractor/crunchyroll] Better message for premium videos
* [extractor/crunchyroll] Fix incorrect premium-only error by [Grub4K](https://github.com/Grub4K)
* [extractor/DouyuTV] Use new API by [hatienl0i261299](https://github.com/hatienl0i261299)
* [extractor/embedly] Embedded links may be for other extractors
* [extractor/freesound] Workaround invalid URL in webpage by [rebane2001](https://github.com/rebane2001)
* [extractor/GoPlay] Use new API by [jeroenj](https://github.com/jeroenj)
* [extractor/Hidive] Fix subtitles and age-restriction by [chexxor](https://github.com/chexxor)
* [extractor/huya] Support HD streams by [felixonmars](https://github.com/felixonmars)
* [extractor/moviepilot] Fix extractor by [panatexxa](https://github.com/panatexxa)
* [extractor/nbc] Fix `NBC` and `NBCStations` extractors by [bashonly](https://github.com/bashonly)
* [extractor/nbc] Fix XML parsing by [bashonly](https://github.com/bashonly)
* [extractor/nebula] Remove broken cookie support by [hheimbuerger](https://github.com/hheimbuerger)
* [extractor/nfl] Add `NFLPlus` extractors by [bashonly](https://github.com/bashonly)
* [extractor/niconico] Add support for like history by [Matumo](https://github.com/Matumo), [pukkandan](https://github.com/pukkandan)
* [extractor/nitter] Update instance list by [OIRNOIR](https://github.com/OIRNOIR)
* [extractor/npo] Fix extractor and add HD support by [seproDev](https://github.com/seproDev)
* [extractor/odkmedia] Add `OnDemandChinaEpisodeIE` by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
* [extractor/pornez] Handle relative URLs in iframe by [JChris246](https://github.com/JChris246)
* [extractor/radiko] Fix format sorting for Time Free by [road-master](https://github.com/road-master)
* [extractor/rcs] Fix extractors by [nixxo](https://github.com/nixxo), [pukkandan](https://github.com/pukkandan)
* [extractor/reddit] Support user posts by [OMEGARAZER](https://github.com/OMEGARAZER)
* [extractor/rumble] Fix format sorting by [pukkandan](https://github.com/pukkandan)
* [extractor/servus] Rewrite extractor by [Ashish0804](https://github.com/Ashish0804), [FrankZ85](https://github.com/FrankZ85), [StefanLobbenmeier](https://github.com/StefanLobbenmeier)
* [extractor/slideslive] Fix slides and chapters/duration by [bashonly](https://github.com/bashonly)
* [extractor/SportDeutschland] Fix extractor by [FriedrichRehren](https://github.com/FriedrichRehren)
* [extractor/Stripchat] Fix extractor by [JChris246](https://github.com/JChris246), [bashonly](https://github.com/bashonly)
* [extractor/tnaflix] Fix extractor by [bashonly](https://github.com/bashonly), [oxamun](https://github.com/oxamun)
* [extractor/tvp] Support `stream.tvp.pl` by [selfisekai](https://github.com/selfisekai)
* [extractor/twitter] Fix `--no-playlist` and add media `view_count` when using GraphQL by [Grub4K](https://github.com/Grub4K)
* [extractor/twitter] Fix graphql extraction on some tweets by [selfisekai](https://github.com/selfisekai)
* [extractor/vimeo] Fix `playerConfig` extraction by [LeoniePhiline](https://github.com/LeoniePhiline), [bashonly](https://github.com/bashonly)
* [extractor/viu] Add `ViuOTTIndonesiaIE` extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/vk] Fix playlists for new API by [the-marenga](https://github.com/the-marenga)
* [extractor/vlive] Replace with `VLiveWebArchiveIE` by [seproDev](https://github.com/seproDev)
* [extractor/ximalaya] Update album `_VALID_URL` by [carusocr](https://github.com/carusocr)
* [extractor/zdf] Use android API endpoint for UHD downloads by [seproDev](https://github.com/seproDev)
* [extractor/drtv] Fix bug in [ab4cbef](https://github.com/yt-dlp/yt-dlp/commit/ab4cbef) by [bashonly](https://github.com/bashonly)


### 2023.01.06

* Fix config locations by [Grub4K](https://github.com/Grub4K), [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [downloader/aria2c] Disable native progress
* [utils] `mimetype2ext`: `weba` is not standard
* [utils] `windows_enable_vt_mode`: Better error handling
* [build] Add minimal `pyproject.toml`
* [update] Fix updater file removal on windows by [Grub4K](https://github.com/Grub4K)
* [cleanup] Misc fixes and cleanup
* [extractor/aitube] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/drtv] Add series extractors by [FrederikNS](https://github.com/FrederikNS)
* [extractor/volejtv] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/xanimu] Add extractor by [JChris246](https://github.com/JChris246)
* [extractor/youtube] Retry manifest refresh for live-from-start by [mzhou](https://github.com/mzhou)
* [extractor/biliintl] Add `/media` to `VALID_URL` by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/biliIntl] Add fallback to `video_data` by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/crunchyroll:show] Add `language` to entries by [Chrissi2812](https://github.com/Chrissi2812)
* [extractor/joj] Fix extractor by [OndrejBakan](https://github.com/OndrejBakan), [pukkandan](https://github.com/pukkandan)
* [extractor/nbc] Update graphql query by [jacobtruman](https://github.com/jacobtruman)
* [extractor/reddit] Add subreddit as `channel_id` by [gschizas](https://github.com/gschizas)
* [extractor/tiktok] Add `TikTokLive` extractor by [JC-Chung](https://github.com/JC-Chung)

### 2023.01.02

* **Improve plugin architecture** by [Grub4K](https://github.com/Grub4K), [coletdjnz](https://github.com/coletdjnz), [flashdagger](https://github.com/flashdagger), [pukkandan](https://github.com/pukkandan)
    * Plugins can be loaded in any distribution of yt-dlp (binary, pip, source, etc.) and can be distributed and installed as packages. See [the readme](https://github.com/yt-dlp/yt-dlp/tree/05997b6e98e638d97d409c65bb5eb86da68f3b64#plugins) for more information
* Add `--compat-options 2021,2022`
    * This allows devs to change defaults and make other potentially breaking changes more easily. If you need everything to work exactly as-is, put Use `--compat 2022` in your config to guard against future compat changes.
* [downloader/aria2c] Native progress for aria2c via RPC by [Lesmiscore](https://github.com/Lesmiscore), [pukkandan](https://github.com/pukkandan)
* Merge youtube-dl: Upto [commit/195f22f](https://github.com/ytdl-org/youtube-dl/commit/195f22f6) by [Grub4K](https://github.com/Grub4K), [pukkandan](https://github.com/pukkandan)
* Add pre-processor stage `video`
* Let `--parse/replace-in-metadata` run at any post-processing stage
* Add `--enable-file-urls` by [coletdjnz](https://github.com/coletdjnz)
* Add new field `aspect_ratio`
* Add `ac4` to known codecs
* Add `weba` to known extensions
* [FFmpegVideoConvertor] Add `gif` to `--recode-video`
* Add message when there are no subtitles/thumbnails
* Deprioritize HEVC-over-FLV formats by [Lesmiscore](https://github.com/Lesmiscore)
* Make early reject of `--match-filter` stricter
* Fix `--cookies-from-browser` CLI parsing
* Fix `original_url` in playlists
* Fix bug in writing playlist info-json
* Fix bugs in `PlaylistEntries`
* [downloader/ffmpeg] Fix headers for video+audio formats by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [extractor] Add a way to distinguish IEs that returns only videos
* [extractor] Implement universal format sorting and deprecate `_sort_formats`
* [extractor] Let `_extract_format` functions obey `--ignore-no-formats`
* [extractor/generic] Add `fragment_query` extractor arg for DASH and HLS by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/generic] Decode unicode-escaped embed URLs by [bashonly](https://github.com/bashonly)
* [extractor/generic] Don't report redirect to https
* [extractor/generic] Fix JSON LD manifest extraction by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/generic] Use `Accept-Encoding: identity` for initial request by [coletdjnz](https://github.com/coletdjnz)
* [FormatSort] Add `mov` to `vext`
* [jsinterp] Escape regex that looks like nested set
* [webvtt] Handle premature EOF by [flashdagger](https://github.com/flashdagger)
* [utils] `classproperty`: Add cache support
* [utils] `get_exe_version`: Detect broken executables by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
* [utils] `js_to_json`: Fix bug in [f55523c](https://github.com/yt-dlp/yt-dlp/commit/f55523c) by [ChillingPepper](https://github.com/ChillingPepper), [pukkandan](https://github.com/pukkandan)
* [utils] Make `ExtractorError` mutable
* [utils] Move `FileDownloader.parse_bytes` into utils
* [utils] Move format sorting code into `utils`
* [utils] `windows_enable_vt_mode`: Proper implementation by [Grub4K](https://github.com/Grub4K)
* [update] Workaround [#5632](https://github.com/yt-dlp/yt-dlp/issues/5632)
* [docs] Improvements
* [cleanup] Misc fixes and cleanup
* [cleanup] Use `random.choices` by [freezboltz](https://github.com/freezboltz)
* [extractor/airtv] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/amazonminitv] Add extractors by [GautamMKGarg](https://github.com/GautamMKGarg), [nyuszika7h](https://github.com/nyuszika7h)
* [extractor/beatbump] Add extractors by [Bobscorn](https://github.com/Bobscorn), [pukkandan](https://github.com/pukkandan)
* [extractor/europarl] Add EuroParlWebstream extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/kanal2] Add extractor by [bashonly](https://github.com/bashonly), [glensc](https://github.com/glensc), [pukkandan](https://github.com/pukkandan)
* [extractor/kankanews] Add extractor by [synthpop123](https://github.com/synthpop123)
* [extractor/kick] Add extractor by [bashonly](https://github.com/bashonly)
* [extractor/mediastream] Add extractor by [HobbyistDev](https://github.com/HobbyistDev), [elyse0](https://github.com/elyse0)
* [extractor/noice] Add NoicePodcast extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/oneplace] Add OnePlacePodcast extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/rumble] Add RumbleIE extractor by [flashdagger](https://github.com/flashdagger)
* [extractor/screencastify] Add extractor by [bashonly](https://github.com/bashonly)
* [extractor/trtcocuk] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/Veoh] Add user extractor by [tntmod54321](https://github.com/tntmod54321)
* [extractor/videoken] Add extractors by [bashonly](https://github.com/bashonly)
* [extractor/webcamerapl] Add extractor by [milkknife](https://github.com/milkknife)
* [extractor/amazon] Add `AmazonReviews` extractor by [bashonly](https://github.com/bashonly)
* [extractor/netverse] Add `NetverseSearch` extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/vimeo] Add `VimeoProIE` by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/xiami] Remove extractors by [synthpop123](https://github.com/synthpop123)
* [extractor/youtube] Add `piped.video` by [Bnyro](https://github.com/Bnyro)
* [extractor/youtube] Consider language in format de-duplication
* [extractor/youtube] Extract DRC formats
* [extractor/youtube] Fix `ytuser:`
* [extractor/youtube] Fix bug in handling of music URLs
* [extractor/youtube] Subtitles cannot be translated to `und`
* [extractor/youtube:tab] Extract metadata from channel items by [coletdjnz](https://github.com/coletdjnz)
* [extractor/ARD] Add vtt subtitles by [CapacitorSet](https://github.com/CapacitorSet)
* [extractor/ArteTV] Extract chapters by [bashonly](https://github.com/bashonly), [iw0nderhow](https://github.com/iw0nderhow)
* [extractor/bandcamp] Add `album_artist` by [stelcodes](https://github.com/stelcodes)
* [extractor/bilibili] Fix `--no-playlist` for anthology
* [extractor/bilibili] Improve `_VALID_URL` by [skbeh](https://github.com/skbeh)
* [extractor/biliintl:series] Make partial download of series faster
* [extractor/BiliLive] Fix extractor
* [extractor/brightcove] Add `BrightcoveNewBaseIE` and fix embed extraction
* [extractor/cda] Support premium and misc improvements by [selfisekai](https://github.com/selfisekai)
* [extractor/ciscowebex] Support password-protected videos by [damianoamatruda](https://github.com/damianoamatruda)
* [extractor/curiositystream] Fix auth by [mnn](https://github.com/mnn)
* [extractor/embedly] Handle vimeo embeds
* [extractor/fifa] Fix Preplay extraction by [dirkf](https://github.com/dirkf)
* [extractor/foxsports] Fix extractor by [bashonly](https://github.com/bashonly)
* [extractor/gronkh] Fix `_VALID_URL` by [muddi900](https://github.com/muddi900)
* [extractor/hotstar] Improve format metadata
* [extractor/iqiyi] Fix `Iq` JS regex by [bashonly](https://github.com/bashonly)
* [extractor/la7] Improve extractor by [nixxo](https://github.com/nixxo)
* [extractor/mediaset] Better embed detection and error messages by [nixxo](https://github.com/nixxo)
* [extractor/mixch] Support `--wait-for-video`
* [extractor/naver] Improve `_VALID_URL` for `NaverNowIE` by [bashonly](https://github.com/bashonly)
* [extractor/naver] Treat fan subtitles as separate language
* [extractor/netverse] Extract comments by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/nosnl] Add support for /video by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/odnoklassniki] Extract subtitles by [bashonly](https://github.com/bashonly)
* [extractor/pinterest] Fix extractor by [bashonly](https://github.com/bashonly)
* [extractor/plutotv] Fix videos with non-zero start by [digitall](https://github.com/digitall)
* [extractor/polskieradio] Adapt to next.js redesigns by [selfisekai](https://github.com/selfisekai)
* [extractor/reddit] Add vcodec to fallback format by [chengzhicn](https://github.com/chengzhicn)
* [extractor/reddit] Extract crossposted media by [bashonly](https://github.com/bashonly)
* [extractor/reddit] Extract video embeds in text posts by [bashonly](https://github.com/bashonly)
* [extractor/rutube] Support private videos by [mexus](https://github.com/mexus)
* [extractor/sibnet] Separate from VKIE
* [extractor/slideslive] Fix extractor by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [extractor/slideslive] Support embeds and slides by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/soundcloud] Support user permalink by [nosoop](https://github.com/nosoop)
* [extractor/spankbang] Fix extractor by [JChris246](https://github.com/JChris246)
* [extractor/stv] Detect DRM
* [extractor/swearnet] Fix description bug
* [extractor/tencent] Fix geo-restricted video by [elyse0](https://github.com/elyse0)
* [extractor/tiktok] Fix subs, `DouyinIE`, improve `_VALID_URL` by [bashonly](https://github.com/bashonly)
* [extractor/tiktok] Update `_VALID_URL`, add `api_hostname` arg by [bashonly](https://github.com/bashonly)
* [extractor/tiktok] Update API hostname by [redraskal](https://github.com/redraskal)
* [extractor/twitcasting] Fix videos with password by [Spicadox](https://github.com/Spicadox), [bashonly](https://github.com/bashonly)
* [extractor/twitter] Heed `--no-playlist` for multi-video tweets by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [extractor/twitter] Refresh guest token when expired by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* [extractor/twitter:spaces] Add `Referer` to m3u8 by [nixxo](https://github.com/nixxo)
* [extractor/udemy] Fix lectures that have no URL and detect DRM
* [extractor/unsupported] Add more URLs
* [extractor/urplay] Support for audio-only formats by [barsnick](https://github.com/barsnick)
* [extractor/wistia] Improve extension detection by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/yle_areena] Support restricted videos by [docbender](https://github.com/docbender)
* [extractor/youku] Fix extractor by [KurtBestor](https://github.com/KurtBestor)
* [extractor/youporn] Fix metadata by [marieell](https://github.com/marieell)
* [extractor/redgifs] Fix bug in [8c188d5](https://github.com/yt-dlp/yt-dlp/commit/8c188d5d09177ed213a05c900d3523867c5897fd)


### 2022.11.11

* Merge youtube-dl: Upto [commit/de39d12](https://github.com/ytdl-org/youtube-dl/commit/de39d128)
* Backport SSL configuration from Python 3.10 by [coletdjnz](https://github.com/coletdjnz)
* Do more processing in `--flat-playlist`
* Fix `--list` options not implying `-s` in some cases by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly)
* Fix end time of clips by [cruel-efficiency](https://github.com/cruel-efficiency)
* Fix for `formats=None`
* Write API params in debug head
* [outtmpl] Ensure ASCII in json and add option for Unicode
* [SponsorBlock] Add `type` field, obey `--retry-sleep extractor`, relax duration check for large segments
* [SponsorBlock] **Support `chapter` category** by [ajayyy](https://github.com/ajayyy), [pukkandan](https://github.com/pukkandan)
* [ThumbnailsConvertor] Fix filename escaping by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
* [ModifyChapters] Handle the entire video being marked for removal
* [embedthumbnail] Fix thumbnail name in mp3 by [How-Bout-No](https://github.com/How-Bout-No)
* [downloader/fragment] HLS download can continue without first fragment
* [cookies] Improve `LenientSimpleCookie` by [Grub4K](https://github.com/Grub4K)
* [jsinterp] Improve separating regex
* [extractor/common] Fix `fatal=False` for `_search_nuxt_data`
* [extractor/common] Improve `_generic_title`
* [extractor/common] Fix `json_ld` type checks by [Grub4K](https://github.com/Grub4K)
* [extractor/generic] Separate embed extraction into own function
* [extractor/generic:quoted-html] Add extractor by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/unsupported] Raise error on known DRM-only sites by [coletdjnz](https://github.com/coletdjnz)
* [utils] `js_to_json`: Improve escape handling by [Grub4K](https://github.com/Grub4K)
* [utils] `strftime_or_none`: Workaround Python bug on Windows
* [utils] `traverse_obj`: Always return list when branching, allow `re.Match` objects by [Grub4K](https://github.com/Grub4K)
* [build, test] Harden workflows' security by [sashashura](https://github.com/sashashura)
* [build] `py2exe`: Migrate to freeze API by [SG5](https://github.com/SG5), [pukkandan](https://github.com/pukkandan)
* [build] Create `armv7l` and `aarch64` releases by [MrOctopus](https://github.com/MrOctopus), [pukkandan](https://github.com/pukkandan)
* [build] Make linux binary truly standalone using `conda` by [mlampe](https://github.com/mlampe)
* [build] Replace `set-output` with `GITHUB_OUTPUT` by [Lesmiscore](https://github.com/Lesmiscore)
* [update] Use error code `100` for update errors
* [compat] Fix `shutils.move` in restricted ACL mode on BSD by [ClosedPort22](https://github.com/ClosedPort22), [pukkandan](https://github.com/pukkandan)
* [docs, devscripts] Document `pyinst`'s argument passthrough by [jahway603](https://github.com/jahway603)
* [test] Allow `extract_flat` in download tests by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [cleanup] Misc fixes and cleanup by [pukkandan](https://github.com/pukkandan), [Alienmaster](https://github.com/Alienmaster)
* [extractor/aeon] Add extractor by [DoubleCouponDay](https://github.com/DoubleCouponDay)
* [extractor/agora] Add extractors by [selfisekai](https://github.com/selfisekai)
* [extractor/camsoda] Add extractor by [zulaport](https://github.com/zulaport)
* [extractor/cinetecamilano] Add extractor by [timendum](https://github.com/timendum)
* [extractor/deuxm] Add extractors by [CrankDatSouljaBoy](https://github.com/CrankDatSouljaBoy)
* [extractor/genius] Add extractors by [bashonly](https://github.com/bashonly)
* [extractor/japandiet] Add extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/listennotes] Add extractor by [lksj](https://github.com/lksj), [pukkandan](https://github.com/pukkandan)
* [extractor/nos.nl] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/oftv] Add extractors by [DoubleCouponDay](https://github.com/DoubleCouponDay)
* [extractor/podbayfm] Add extractor by [schnusch](https://github.com/schnusch)
* [extractor/qingting] Add extractor by [bashonly](https://github.com/bashonly), [changren-wcr](https://github.com/changren-wcr)
* [extractor/screen9] Add extractor by [tpikonen](https://github.com/tpikonen)
* [extractor/swearnet] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/YleAreena] Add extractor by [pukkandan](https://github.com/pukkandan), [vitkhab](https://github.com/vitkhab)
* [extractor/zeenews] Add extractor by [m4tu4g](https://github.com/m4tu4g), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube:tab] **Update tab handling for redesign** by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
    * Channel URLs download all uploads of the channel as multiple playlists, separated by tab
* [extractor/youtube] Differentiate between no comments and disabled comments by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Extract `concurrent_view_count` for livestreams by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Fix `duration` for premieres by [nosoop](https://github.com/nosoop)
* [extractor/youtube] Fix `live_status` by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube] Ignore incomplete data error for comment replies by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Improve chapter parsing from description
* [extractor/youtube] Mark videos as fully watched by [bsun0000](https://github.com/bsun0000)
* [extractor/youtube] Update piped instances by [Generator](https://github.com/Generator)
* [extractor/youtube] Update playlist metadata extraction for new layout by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube:tab] Fix video metadata from tabs by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube:tab] Let `approximate_date` return timestamp
* [extractor/americastestkitchen] Fix extractor by [bashonly](https://github.com/bashonly)
* [extractor/bbc] Support onion domains by [DoubleCouponDay](https://github.com/DoubleCouponDay)
* [extractor/bilibili] Add chapters and misc cleanup by [lockmatrix](https://github.com/lockmatrix), [pukkandan](https://github.com/pukkandan)
* [extractor/bilibili] Fix BilibiliIE and Bangumi extractors by [lockmatrix](https://github.com/lockmatrix), [pukkandan](https://github.com/pukkandan)
* [extractor/bitchute] Better error for geo-restricted videos by [flashdagger](https://github.com/flashdagger)
* [extractor/bitchute] Improve `BitChuteChannelIE` by [flashdagger](https://github.com/flashdagger), [pukkandan](https://github.com/pukkandan)
* [extractor/bitchute] Simplify extractor by [flashdagger](https://github.com/flashdagger), [pukkandan](https://github.com/pukkandan)
* [extractor/cda] Support login through API by [selfisekai](https://github.com/selfisekai)
* [extractor/crunchyroll] Beta is now the only layout by [tejing1](https://github.com/tejing1)
* [extractor/detik] Avoid unnecessary extraction
* [extractor/doodstream] Remove extractor
* [extractor/dplay] Add MotorTrendOnDemand extractor by [bashonly](https://github.com/bashonly)
* [extractor/epoch] Support videos without data-trailer by [gibson042](https://github.com/gibson042), [pukkandan](https://github.com/pukkandan)
* [extractor/fox] Extract thumbnail by [vitkhab](https://github.com/vitkhab)
* [extractor/foxnews] Add `FoxNewsVideo` extractor
* [extractor/hotstar] Add season support by [m4tu4g](https://github.com/m4tu4g)
* [extractor/hotstar] Refactor v1 API calls
* [extractor/iprima] Make json+ld non-fatal by [bashonly](https://github.com/bashonly)
* [extractor/iq] Increase phantomjs timeout
* [extractor/kaltura] Support playlists by [jwoglom](https://github.com/jwoglom), [pukkandan](https://github.com/pukkandan)
* [extractor/lbry] Authenticate with cookies by [flashdagger](https://github.com/flashdagger)
* [extractor/livestreamfails] Support posts by [invertico](https://github.com/invertico)
* [extractor/mlb] Add `MLBArticle` extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/mxplayer] Improve extractor by [m4tu4g](https://github.com/m4tu4g)
* [extractor/niconico] Always use HTTPS for requests
* [extractor/nzherald] Support new video embed by [coletdjnz](https://github.com/coletdjnz)
* [extractor/odnoklassniki] Support boosty.to embeds by [Lesmiscore](https://github.com/Lesmiscore), [megapro17](https://github.com/megapro17), [pukkandan](https://github.com/pukkandan)
* [extractor/paramountplus] Update API token by [bashonly](https://github.com/bashonly)
* [extractor/reddit] Add fallback format by [bashonly](https://github.com/bashonly)
* [extractor/redgifs] Fix extractors by [bashonly](https://github.com/bashonly), [pukkandan](https://github.com/pukkandan)
* [extractor/redgifs] Refresh auth token for 401 by [endotronic](https://github.com/endotronic), [pukkandan](https://github.com/pukkandan)
* [extractor/rumble] Add HLS formats and extract more metadata by [flashdagger](https://github.com/flashdagger)
* [extractor/sbs] Improve `_VALID_URL` by [bashonly](https://github.com/bashonly)
* [extractor/skyit] Fix extractors by [nixxo](https://github.com/nixxo)
* [extractor/stripchat] Fix hostname for HLS stream by [zulaport](https://github.com/zulaport)
* [extractor/stripchat] Improve error message by [freezboltz](https://github.com/freezboltz)
* [extractor/telegram] Add playlist support and more metadata by [bashonly](https://github.com/bashonly), [bsun0000](https://github.com/bsun0000)
* [extractor/Tnaflix] Fix for HTTP 500 by [SG5](https://github.com/SG5), [pukkandan](https://github.com/pukkandan)
* [extractor/tubitv] Better DRM detection by [bashonly](https://github.com/bashonly)
* [extractor/tvp] Update extractors by [selfisekai](https://github.com/selfisekai)
* [extractor/twitcasting] Fix `data-movie-playlist` extraction by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/twitter] Add onion site to `_VALID_URL` by [DoubleCouponDay](https://github.com/DoubleCouponDay)
* [extractor/twitter] Add Spaces extractor and GraphQL API by [Grub4K](https://github.com/Grub4K), [bashonly](https://github.com/bashonly), [nixxo](https://github.com/nixxo), [pukkandan](https://github.com/pukkandan)
* [extractor/twitter] Support multi-video posts by [Grub4K](https://github.com/Grub4K)
* [extractor/uktvplay] Fix `_VALID_URL`
* [extractor/viu] Support subtitles of on-screen text by [tkgmomosheep](https://github.com/tkgmomosheep)
* [extractor/VK] Fix playlist URLs by [the-marenga](https://github.com/the-marenga)
* [extractor/vlive] Extract `release_timestamp`
* [extractor/voot] Improve `_VALID_URL` by [freezboltz](https://github.com/freezboltz)
* [extractor/wordpress:mb.miniAudioPlayer] Add embed extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/YoutubeWebArchive] Improve metadata extraction by [coletdjnz](https://github.com/coletdjnz)
* [extractor/zee5] Improve `_VALID_URL` by [m4tu4g](https://github.com/m4tu4g)
* [extractor/zenyandex] Fix extractors by [lksj](https://github.com/lksj), [puc9](https://github.com/puc9), [pukkandan](https://github.com/pukkandan)


### 2022.10.04

* Allow a `set` to be passed as `download_archive` by [pukkandan](https://github.com/pukkandan), [bashonly](https://github.com/bashonly)
* Allow open ranges for time ranges by [Lesmiscore](https://github.com/Lesmiscore)
* Allow plugin extractors to replace the built-in ones
* Don't download entire video when no matching `--download-sections`
* Fix `--config-location -`
* Improve [5736d79](https://github.com/yt-dlp/yt-dlp/pull/5044/commits/5736d79172c47ff84740d5720467370a560febad)
* Fix for when playlists don't have `webpage_url`
* Support environment variables in `--ffmpeg-location`
* Workaround `libc_ver` not be available on Windows Store version of Python
* [outtmpl] Curly braces to filter keys by [pukkandan](https://github.com/pukkandan)
* [outtmpl] Make `%s` work in strfformat for all systems
* [jsinterp] Workaround operator associativity issue
* [cookies] Let `_get_mac_keyring_password` fail gracefully
* [cookies] Parse cookies leniently by [Grub4K](https://github.com/Grub4K)
* [phantomjs] Fix bug in [587021c](https://github.com/yt-dlp/yt-dlp/commit/587021cd9f717181b44e881941aca3f8d753758b) by [elyse0](https://github.com/elyse0)
* [downloader/aria2c] Fix filename containing leading whitespace by [std-move](https://github.com/std-move)
* [downloader/ism] Support ec-3 codec by [nixxo](https://github.com/nixxo)
* [extractor] Fix `fatal=False` in `RetryManager`
* [extractor] Improve json-ld extraction
* [extractor] Make `_search_json` able to parse lists
* [extractor] Escape `%` in `representation_id` of m3u8
* [extractor/generic] Pass through referer from json-ld
* [utils] `base_url`: URL paths can contain `&` by [elyse0](https://github.com/elyse0)
* [utils] `js_to_json`: Improve
* [utils] `Popen.run`: Fix default return in binary mode
* [utils] `traverse_obj`: Rewrite, document and add tests by [Grub4K](https://github.com/Grub4K)
* [devscripts] `make_lazy_extractors`: Fix for Docker by [josanabr](https://github.com/josanabr)
* [docs] Misc Improvements
* [cleanup] Misc fixes and cleanup by [pukkandan](https://github.com/pukkandan), [gamer191](https://github.com/gamer191)
* [extractor/24tv.ua] Add extractors by [coletdjnz](https://github.com/coletdjnz)
* [extractor/BerufeTV] Add extractor by [Fabi019](https://github.com/Fabi019)
* [extractor/booyah] Add extractor by [HobbyistDev](https://github.com/HobbyistDev), [elyse0](https://github.com/elyse0)
* [extractor/bundesliga] Add extractor by [Fabi019](https://github.com/Fabi019)
* [extractor/GoPlay] Add extractor by [CNugteren](https://github.com/CNugteren), [basrieter](https://github.com/basrieter), [jeroenj](https://github.com/jeroenj)
* [extractor/iltalehti] Add extractor by [tpikonen](https://github.com/tpikonen)
* [extractor/IsraelNationalNews] Add extractor by [Bobscorn](https://github.com/Bobscorn)
* [extractor/mediaworksnzvod] Add extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/MicrosoftEmbed] Add extractor by [DoubleCouponDay](https://github.com/DoubleCouponDay)
* [extractor/nbc] Add NBCStations extractor by [bashonly](https://github.com/bashonly)
* [extractor/onenewsnz] Add extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/prankcast] Add extractor by [HobbyistDev](https://github.com/HobbyistDev), [columndeeply](https://github.com/columndeeply)
* [extractor/Smotrim] Add extractor by [Lesmiscore](https://github.com/Lesmiscore), [nikita-moor](https://github.com/nikita-moor)
* [extractor/tencent] Add Iflix extractor by [elyse0](https://github.com/elyse0)
* [extractor/unscripted] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/adobepass] Add MSO AlticeOne (Optimum TV) by [CplPwnies](https://github.com/CplPwnies)
* [extractor/youtube] **Download `post_live` videos from start** by [Lesmiscore](https://github.com/Lesmiscore), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube] Add support for Shorts audio pivot feed by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube] Detect `lazy-load-for-videos` embeds
* [extractor/youtube] Do not warn on duplicate chapters
* [extractor/youtube] Fix video like count extraction by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Support changing extraction language by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube:tab] Improve continuation items extraction
* [extractor/youtube:tab] Support `reporthistory` page
* [extractor/amazonstore] Fix JSON extraction by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/amazonstore] Retry to avoid captcha page by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/animeondemand] Remove extractor by [TokyoBlackHole](https://github.com/TokyoBlackHole)
* [extractor/anvato] Fix extractor and refactor by [bashonly](https://github.com/bashonly)
* [extractor/artetv] Remove duplicate stream urls by [Grub4K](https://github.com/Grub4K)
* [extractor/audioboom] Support direct URLs and refactor by [pukkandan](https://github.com/pukkandan), [tpikonen](https://github.com/tpikonen)
* [extractor/bandcamp] Extract `uploader_url`
* [extractor/bilibili] Add space.bilibili extractors by [lockmatrix](https://github.com/lockmatrix)
* [extractor/BilibiliSpace] Fix extractor and better error message by [lockmatrix](https://github.com/lockmatrix)
* [extractor/BiliIntl] Support uppercase lang in `_VALID_URL` by [coletdjnz](https://github.com/coletdjnz)
* [extractor/BiliIntlSeries] Fix `_VALID_URL`
* [extractor/bongacams] Update `_VALID_URL` by [0xGodspeed](https://github.com/0xGodspeed)
* [extractor/crunchyroll:beta] Improve handling of hardsubs by [Grub4K](https://github.com/Grub4K)
* [extractor/detik] Generalize extractors by [HobbyistDev](https://github.com/HobbyistDev), [coletdjnz](https://github.com/coletdjnz)
* [extractor/dplay:italy] Add default authentication by [Timendum](https://github.com/Timendum)
* [extractor/heise] Fix extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/holodex] Fix `_VALID_URL` by [LiviaMedeiros](https://github.com/LiviaMedeiros)
* [extractor/hrfensehen] Fix extractor by [snapdgn](https://github.com/snapdgn)
* [extractor/hungama] Add subtitle by [GautamMKGarg](https://github.com/GautamMKGarg), [pukkandan](https://github.com/pukkandan)
* [extractor/instagram] Extract more metadata by [pritam20ps05](https://github.com/pritam20ps05)
* [extractor/JWPlatform] Fix extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/malltv] Fix video_id extraction by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/MLBTV] Detect live streams
* [extractor/motorsport] Support native embeds
* [extractor/Mxplayer] Fix extractor by [itachi-19](https://github.com/itachi-19)
* [extractor/nebula] Add nebula.tv by [tannertechnology](https://github.com/tannertechnology)
* [extractor/nfl] Fix extractor by [bashonly](https://github.com/bashonly)
* [extractor/ondemandkorea] Update `jw_config` regex by [julien-hadleyjack](https://github.com/julien-hadleyjack)
* [extractor/paramountplus] Better DRM detection by [bashonly](https://github.com/bashonly)
* [extractor/patreon] Sort formats
* [extractor/rcs] Fix embed extraction by [coletdjnz](https://github.com/coletdjnz)
* [extractor/redgifs] Fix extractor by [jhwgh1968](https://github.com/jhwgh1968)
* [extractor/rutube] Fix `_EMBED_REGEX` by [coletdjnz](https://github.com/coletdjnz)
* [extractor/RUTV] Fix warnings for livestreams by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/soundcloud:search] More metadata in `--flat-playlist` by [SuperSonicHub1](https://github.com/SuperSonicHub1)
* [extractor/telegraaf] Use mobile GraphQL API endpoint by [coletdjnz](https://github.com/coletdjnz)
* [extractor/tennistv] Fix timestamp by [zenerdi0de](https://github.com/zenerdi0de)
* [extractor/tiktok] Fix TikTokIE by [bashonly](https://github.com/bashonly)
* [extractor/triller] Fix auth token by [bashonly](https://github.com/bashonly)
* [extractor/trovo] Fix extractors by [Mehavoid](https://github.com/Mehavoid)
* [extractor/tv2] Support new url format by [tobi1805](https://github.com/tobi1805)
* [extractor/web.archive:youtube] Fix `_YT_INITIAL_PLAYER_RESPONSE_RE`
* [extractor/wistia] Add support for channels by [coletdjnz](https://github.com/coletdjnz)
* [extractor/wistia] Match IDs in embed URLs by [bashonly](https://github.com/bashonly)
* [extractor/wordpress:playlist] Add generic embed extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/yandexvideopreview] Update `_VALID_URL` by [Grub4K](https://github.com/Grub4K)
* [extractor/zee5] Fix `_VALID_URL` by [m4tu4g](https://github.com/m4tu4g)
* [extractor/zee5] Generate device ids by [freezboltz](https://github.com/freezboltz)


### 2022.09.01

* Add option `--use-extractors`
* Merge youtube-dl: Upto [commit/ed5c44e](https://github.com/ytdl-org/youtube-dl/commit/ed5c44e7)
* Add yt-dlp version to infojson
* Fix `--break-per-url --max-downloads`
* Fix bug in `--alias`
* [cookies] Support firefox container in `--cookies-from-browser` by [bashonly](https://github.com/bashonly), [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [downloader/external] Smarter detection of executable
* [extractor/generic] Don't return JW player without formats
* [FormatSort] Fix `aext` for `--prefer-free-formats`
* [jsinterp] Various improvements by [pukkandan](https://github.com/pukkandan), [dirkf](https://github.com/dirkf), [elyse0](https://github.com/elyse0)
* [cache] Mechanism to invalidate old cache
* [utils] Add `deprecation_warning`
* [utils] Add `orderedSet_from_options`
* [utils] `Popen`: Restore `LD_LIBRARY_PATH` when using PyInstaller by [Lesmiscore](https://github.com/Lesmiscore)
* [build] `make tar` should not follow `DESTDIR` by [satan1st](https://github.com/satan1st)
* [build] Update pyinstaller by [shirt-dev](https://github.com/shirt-dev)
* [test] Fix `test_youtube_signature`
* [cleanup] Misc fixes and cleanup by [DavidH-2022](https://github.com/DavidH-2022), [MrRawes](https://github.com/MrRawes), [pukkandan](https://github.com/pukkandan)
* [extractor/epoch] Add extractor by [tejasa97](https://github.com/tejasa97)
* [extractor/eurosport] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/IslamChannel] Add extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/newspicks] Add extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/triller] Add extractor by [bashonly](https://github.com/bashonly)
* [extractor/VQQ] Add extractors by [elyse0](https://github.com/elyse0)
* [extractor/youtube] Improvements to nsig extraction
* [extractor/youtube] Fix bug in format sorting
* [extractor/youtube] Update iOS Innertube clients by [SamantazFox](https://github.com/SamantazFox)
* [extractor/youtube] Use device-specific user agent by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Add `--compat-option no-youtube-prefer-utc-upload-date` by [coletdjnz](https://github.com/coletdjnz)
* [extractor/arte] Bug fix by [cgrigis](https://github.com/cgrigis)
* [extractor/bilibili] Extract `flac` with premium account by [jackyyf](https://github.com/jackyyf)
* [extractor/BiliBiliSearch] Don't sort by date
* [extractor/BiliBiliSearch] Fix infinite loop
* [extractor/bitchute] Mark errors as expected
* [extractor/crunchyroll:beta] Use anonymous access by [tejing1](https://github.com/tejing1)
* [extractor/huya] Fix stream extraction by [ohaiibuzzle](https://github.com/ohaiibuzzle)
* [extractor/medaltv] Fix extraction by [xenova](https://github.com/xenova)
* [extractor/mediaset] Fix embed extraction
* [extractor/mixcloud] All formats are audio-only
* [extractor/rtbf] Fix jwt extraction by [elyse0](https://github.com/elyse0)
* [extractor/screencastomatic] Support `--video-password` by [shreyasminocha](https://github.com/shreyasminocha)
* [extractor/stripchat] Don't modify input URL by [dfaker](https://github.com/dfaker)
* [extractor/uktv] Improve `_VALID_URL` by [dirkf](https://github.com/dirkf)
* [extractor/vimeo:user] Fix `_VALID_URL`


### 2022.08.19

* Fix bug in `--download-archive`
* [jsinterp] **Fix for new youtube players** and related improvements by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
* [phantomjs] Add function to execute JS without a DOM by [MinePlayersPE](https://github.com/MinePlayersPE), [pukkandan](https://github.com/pukkandan)
* [build] Exclude devscripts from installs by [Lesmiscore](https://github.com/Lesmiscore)
* [cleanup] Misc fixes and cleanup
* [extractor/youtube] **Add fallback to phantomjs** for nsig
* [extractor/youtube] Fix error reporting of "Incomplete data"
* [extractor/youtube] Improve format sorting for IOS formats
* [extractor/youtube] Improve signature caching
* [extractor/instagram] Fix extraction by [bashonly](https://github.com/bashonly), [pritam20ps05](https://github.com/pritam20ps05)
* [extractor/rai] Minor fix by [nixxo](https://github.com/nixxo)
* [extractor/rtbf] Fix stream extractor by [elyse0](https://github.com/elyse0)
* [extractor/SovietsCloset] Fix extractor by [ChillingPepper](https://github.com/ChillingPepper)
* [extractor/zattoo] Fix Zattoo resellers by [goggle](https://github.com/goggle)

### 2022.08.14

* Merge youtube-dl: Upto [commit/d231b56](https://github.com/ytdl-org/youtube-dl/commit/d231b56)
* [jsinterp] Handle **new youtube signature functions**
* [jsinterp] Truncate error messages
* [extractor] Fix format sorting of `channels`
* [ffmpeg] Disable avconv unless `--prefer-avconv`
* [ffmpeg] Smarter detection of ffprobe filename
* [embedthumbnail] Detect `libatomicparsley.so`
* [ThumbnailsConvertor] Fix conversion after `fixup_webp`
* [utils] Fix `get_compatible_ext`
* [build] Fix changelog
* [update] Set executable bit-mask by [pukkandan](https://github.com/pukkandan), [Lesmiscore](https://github.com/Lesmiscore)
* [devscripts] Fix import
* [docs] Consistent use of `e.g.` by [Lesmiscore](https://github.com/Lesmiscore)
* [cleanup] Misc fixes and cleanup
* [extractor/moview] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/parler] Add extractor by [palewire](https://github.com/palewire)
* [extractor/patreon] Ignore erroneous media attachments by [coletdjnz](https://github.com/coletdjnz)
* [extractor/truth] Add extractor by [palewire](https://github.com/palewire)
* [extractor/aenetworks] Add formats parameter by [jacobtruman](https://github.com/jacobtruman)
* [extractor/crunchyroll] Improve `_VALID_URL`s
* [extractor/doodstream] Add `wf` domain by [aldoridhoni](https://github.com/aldoridhoni)
* [extractor/facebook] Add reel support by [bashonly](https://github.com/bashonly)
* [extractor/MLB] New extractor by [ischmidt20](https://github.com/ischmidt20)
* [extractor/rai] Misc fixes by [nixxo](https://github.com/nixxo)
* [extractor/toggo] Improve `_VALID_URL` by [masta79](https://github.com/masta79)
* [extractor/tubitv] Extract additional formats by [shirt-dev](https://github.com/shirt-dev)
* [extractor/zattoo] Potential fix for resellers


### 2022.08.08

* **Remove Python 3.6 support**
* Determine merge container better by [pukkandan](https://github.com/pukkandan), [selfisekai](https://github.com/selfisekai)
* Framework for embed detection by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* Merge youtube-dl: Upto [commit/adb5294](https://github.com/ytdl-org/youtube-dl/commit/adb5294)
* `--compat-option no-live-chat` should disable danmaku
* Fix misleading DRM message
* Import ctypes only when necessary
* Minor bugfixes
* Reject entire playlists faster with `--match-filter`
* Remove filtered entries from `-J`
* Standardize retry mechanism
* Validate `--merge-output-format`
* [downloader] Add average speed to final progress line
* [extractor] Add field `audio_channels`
* [extractor] Support multiple archive ids for one video
* [ffmpeg] Set `ffmpeg_location` in a contextvar
* [FFmpegThumbnailsConvertor] Fix conversion from GIF
* [MetadataParser] Don't set `None` when the field didn't match
* [outtmpl] Smarter replacing of unsupported characters
* [outtmpl] Treat empty values as None in filenames
* [utils] sanitize_open: Allow any IO stream as stdout
* [build, devscripts] Add devscript to set a build variant
* [build] Improve build process by [shirt-dev](https://github.com/shirt-dev)
* [build] Update pyinstaller
* [devscripts] Create `utils` and refactor
* [docs] Clarify `best*`
* [docs] Fix bug report issue template
* [docs] Fix capitalization in references by [christoph-heinrich](https://github.com/christoph-heinrich)
* [cleanup, mhtml] Use imghdr
* [cleanup, utils] Consolidate known media extensions
* [cleanup] Misc fixes and cleanup
* [extractor/angel] Add extractor by [AxiosDeminence](https://github.com/AxiosDeminence)
* [extractor/dplay] Add MotorTrend extractor by [Sipherdrakon](https://github.com/Sipherdrakon)
* [extractor/harpodeon] Add extractor by [eren-kemer](https://github.com/eren-kemer)
* [extractor/holodex] Add extractor by [pukkandan](https://github.com/pukkandan), [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/kompas] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/rai] Add raisudtirol extractor by [nixxo](https://github.com/nixxo)
* [extractor/tempo] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/youtube] **Fixes for third party client detection** by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Add `live_status=post_live` by [lazypete365](https://github.com/lazypete365)
* [extractor/youtube] Extract more format info
* [extractor/youtube] Parse translated subtitles only when requested
* [extractor/youtube, extractor/twitch] Allow waiting for channels to become live
* [extractor/youtube, webvtt] Extract auto-subs from livestream VODs by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
* [extractor/AbemaTVTitle] Implement paging by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/archiveorg] Improve handling of formats by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/arte] Fix title extraction
* [extractor/arte] **Move to v2 API** by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
* [extractor/bbc] Fix news articles by [ajj8](https://github.com/ajj8)
* [extractor/camtasia] Separate into own extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/cloudflarestream] Fix video_id padding by [haobinliang](https://github.com/haobinliang)
* [extractor/crunchyroll] Fix conversion of thumbnail from GIF
* [extractor/crunchyroll] Handle missing metadata correctly by [Burve](https://github.com/Burve), [pukkandan](https://github.com/pukkandan)
* [extractor/crunchyroll:beta] Extract timestamp and fix tests by [tejing1](https://github.com/tejing1)
* [extractor/crunchyroll:beta] Use streams API by [tejing1](https://github.com/tejing1)
* [extractor/doodstream] Support more domains by [Galiley](https://github.com/Galiley)
* [extractor/ESPN] Extract duration by [ischmidt20](https://github.com/ischmidt20)
* [extractor/FIFA] Change API endpoint by [Bricio](https://github.com/Bricio), [yashkc2025](https://github.com/yashkc2025)
* [extractor/globo:article] Remove false positives by [Bricio](https://github.com/Bricio)
* [extractor/Go] Extract timestamp by [ischmidt20](https://github.com/ischmidt20)
* [extractor/hidive] Fix cookie login when netrc is also given by [winterbird-code](https://github.com/winterbird-code)
* [extractor/html5] Separate into own extractor by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/ina] Improve extractor by [elyse0](https://github.com/elyse0)
* [extractor/NaverNow] Change endpoint by [ping](https://github.com/ping)
* [extractor/ninegag] Extract uploader by [DjesonPV](https://github.com/DjesonPV)
* [extractor/NovaPlay] Fix extractor by [Bojidarist](https://github.com/Bojidarist)
* [extractor/orf:radio] Rewrite extractors
* [extractor/patreon] Fix and improve extractors by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/rai] Fix RaiNews extraction by [nixxo](https://github.com/nixxo)
* [extractor/redbee] Unify and update extractors by [elyse0](https://github.com/elyse0)
* [extractor/stripchat] Fix _VALID_URL by [freezboltz](https://github.com/freezboltz)
* [extractor/tubi] Exclude playlists from playlist entries by [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/tviplayer] Improve `_VALID_URL` by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/twitch] Extract chapters for single chapter VODs by [mpeter50](https://github.com/mpeter50)
* [extractor/vgtv] Support tv.vg.no by [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/vidio] Support embed link by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/vk] Fix extractor by [Mehavoid](https://github.com/Mehavoid)
* [extractor/WASDTV:record] Fix `_VALID_URL`
* [extractor/xfileshare] Add Referer by [Galiley](https://github.com/Galiley)
* [extractor/YahooJapanNews] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/yandexmusic] Extract higher quality format
* [extractor/zee5] Update Device ID by [m4tu4g](https://github.com/m4tu4g)


### 2022.07.18

* Allow users to specify encoding in each config files by [Lesmiscore](https://github.com/Lesmiscore)
* Discard infodict from memory if no longer needed
* Do not allow extractors to return `None`
* Do not load system certificates when `certifi` is used
* Fix rounding of integers in format table
* Improve chapter sanitization
* Skip some fixup if remux/recode is needed by [Lesmiscore](https://github.com/Lesmiscore)
* Support `--no-progress` for `--wait-for-video`
* Fix bug in [612f2be](https://github.com/yt-dlp/yt-dlp/commit/612f2be5d3924540158dfbe5f25d841f04cff8c6)
* [outtmpl] Add alternate form `h` for HTML escaping
* [aes] Add multiple padding modes in CBC by [elyse0](https://github.com/elyse0)
* [extractor/common] Passthrough `errnote=False` to parsers
* [extractor/generic] Remove HEAD request
* [http] Ensure the file handle is always closed
* [ModifyChapters] Modify duration in infodict
* [options] Fix aliases to `--config-location`
* [utils] Fix `get_domain`
* [build] Consistent order for lazy extractors by [lamby](https://github.com/lamby)
* [build] Fix architecture suffix of executables by [odo2063](https://github.com/odo2063)
* [build] Improve `setup.py`
* [update] Do not check `_update_spec` when up to date
* [update] Prepare to remove Python 3.6 support
* [compat] Let PyInstaller detect _legacy module
* [devscripts/update-formulae] Do not change dependency section
* [test] Split download tests so they can be more easily run in CI
* [docs] Improve docstring of `download_ranges` by [FirefoxMetzger](https://github.com/FirefoxMetzger)
* [docs] Improve issue templates
* [build] Fix bug in [6d916fe](https://github.com/yt-dlp/yt-dlp/commit/6d916fe709a38e8c4c69b73843acf170b5165931)
* [cleanup, utils] Refactor parse_codecs
* [cleanup] Misc fixes and cleanup
* [extractor/acfun] Add extractors by [lockmatrix](https://github.com/lockmatrix)
* [extractor/Audiodraft] Add extractors by [Ashish0804](https://github.com/Ashish0804), [fstirlitz](https://github.com/fstirlitz)
* [extractor/cellebrite] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/detik] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/hytale] Add extractor by [llamasblade](https://github.com/llamasblade), [pukkandan](https://github.com/pukkandan)
* [extractor/liputan6] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/mocha] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/rtl.lu] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/rtvsl] Add extractor by [iw0nderhow](https://github.com/iw0nderhow), [pukkandan](https://github.com/pukkandan)
* [extractor/StarTrek] Add extractor by [scy](https://github.com/scy)
* [extractor/syvdk] Add extractor by [misaelaguayo](https://github.com/misaelaguayo)
* [extractor/theholetv] Add extractor by [dosy4ev](https://github.com/dosy4ev)
* [extractor/TubeTuGraz] Add extractor by [Ferdi265](https://github.com/Ferdi265), [pukkandan](https://github.com/pukkandan)
* [extractor/tviplayer] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/wetv] Add extractors by [elyse0](https://github.com/elyse0)
* [extractor/wikimedia] Add extractor by [EhtishamSabir](https://github.com/EhtishamSabir), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube] Fix duration check for post-live manifestless mode
* [extractor/youtube] More metadata for storyboards by [ftk](https://github.com/ftk)
* [extractor/bigo] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/BiliIntl] Fix subtitle extraction by [MinePlayersPE](https://github.com/MinePlayersPE)
* [extractor/crunchyroll] Improve `_VALID_URL`
* [extractor/fifa] Fix extractor by [ischmidt20](https://github.com/ischmidt20)
* [extractor/instagram] Fix post/story extractors by [pritam20ps05](https://github.com/pritam20ps05), [pukkandan](https://github.com/pukkandan)
* [extractor/iq] Set language correctly for Korean subtitles
* [extractor/MangoTV] Fix subtitle languages
* [extractor/Netverse] Improve playlist extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/philharmoniedeparis] Fix extractor by [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/Trovo] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [extractor/twitch] Support storyboards for VODs by [ftk](https://github.com/ftk)
* [extractor/WatchESPN] Improve `_VALID_URL` by [IONECarter](https://github.com/IONECarter), [dirkf](https://github.com/dirkf)
* [extractor/WSJArticle] Fix video id extraction by [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/Ximalaya] Fix extractors by [lockmatrix](https://github.com/lockmatrix)
* [cleanup, extractor/youtube] Fix tests by [sheerluck](https://github.com/sheerluck)


### 2022.06.29

* Fix `--downloader native`
* Fix `section_end` of clips
* Fix playlist error handling
* Sanitize `chapters`
* [extractor] Fix `_create_request` when headers is None
* [extractor] Fix empty `BaseURL` in MPD
* [ffmpeg] Write full output to debug on error
* [hls] Warn user when trying to download live HLS
* [options] Fix `parse_known_args` for `--`
* [utils] Fix inconsistent default handling between HTTP and HTTPS requests by [coletdjnz](https://github.com/coletdjnz)
* [build] Draft release until complete
* [build] Fix release tag commit
* [build] Standalone x64 builds for MacOS 10.9 by [StefanLobbenmeier](https://github.com/StefanLobbenmeier)
* [update] Ability to set a maximum version for specific variants
* [compat] Fix `compat.WINDOWS_VT_MODE`
* [compat] Remove deprecated functions from core code
* [compat] Remove more functions
* [cleanup, extractor] Reduce direct use of `_downloader`
* [cleanup] Consistent style for file heads
* [cleanup] Fix some typos by [crazymoose77756](https://github.com/crazymoose77756)
* [cleanup] Misc fixes and cleanup
* [extractor/Scrolller] Add extractor by [LunarFang416](https://github.com/LunarFang416)
* [extractor/ViMP] Add playlist extractor by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
* [extractor/fuyin] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/livestreamfails] Add extractor by [nomevi](https://github.com/nomevi)
* [extractor/premiershiprugby] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/steam] Add broadcast extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/youtube] Mark videos as fully watched by [Brett824](https://github.com/Brett824)
* [extractor/CWTV] Extract thumbnail by [ischmidt20](https://github.com/ischmidt20)
* [extractor/ViMP] Add thumbnail and support more sites by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
* [extractor/dropout] Support cookies and login only as needed by [pingiun](https://github.com/pingiun), [pukkandan](https://github.com/pukkandan)
* [extractor/ertflix] Improve `_VALID_URL`
* [extractor/lbry] Use HEAD request for redirect URL by [flashdagger](https://github.com/flashdagger)
* [extractor/mediaset] Improve `_VALID_URL`
* [extractor/npr] Implement [e50c350](https://github.com/yt-dlp/yt-dlp/commit/e50c3500b43d80e4492569c4b4523c4379c6fbb2) differently
* [extractor/tennistv] Rewrite extractor by [pukkandan](https://github.com/pukkandan), [zenerdi0de](https://github.com/zenerdi0de)

### 2022.06.22.1

* [build] Fix updating homebrew formula

### 2022.06.22

* [**Deprecate support for Python 3.6**](https://github.com/yt-dlp/yt-dlp/issues/3764#issuecomment-1154051119)
* **Add option `--download-sections` to download video partially**
    * Chapter regex and time ranges are accepted, e.g. `--download-sections *1:10-2:20`
* Add option `--alias`
* Add option `--lazy-playlist` to process entries as they are received
* Add option `--retry-sleep`
* Add slicing notation to `--playlist-items`
    * Adds support for negative indices and step
    * Add `-I` as alias for `--playlist-index`
    * Makes `--playlist-start`, `--playlist-end`, `--playlist-reverse`, `--no-playlist-reverse` redundant
* `--config-location -` to provide options interactively
* [build] Add Linux standalone builds
* [update] Self-restart after update
* Merge youtube-dl: Upto [commit/8a158a9](https://github.com/ytdl-org/youtube-dl/commit/8a158a9)
* Add `--no-update`
* Allow extractors to specify section_start/end for clips
* Do not print progress to `stderr` with `-q`
* Ensure pre-processor errors do not block video download
* Fix `--simulate --max-downloads`
* Improve error handling of bad config files
* Return an error code if update fails
* Fix bug in [3a408f9](https://github.com/yt-dlp/yt-dlp/commit/3a408f9d199127ca2626359e21a866a09ab236b3)
* [ExtractAudio] Allow conditional conversion
* [ModifyChapters] Fix repeated removal of small segments
* [ThumbnailsConvertor] Allow conditional conversion
* [cookies] Detect profiles for cygwin/BSD by [moench-tegeder](https://github.com/moench-tegeder)
* [dash] Show fragment count with `--live-from-start` by [flashdagger](https://github.com/flashdagger)
* [extractor] Add `_search_json` by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor] Add `default` parameter to `_search_json` by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor] Add dev option `--load-pages`
* [extractor] Handle `json_ld` with multiple `@type`s
* [extractor] Import `_ALL_CLASSES` lazily
* [extractor] Recognize `src` attribute from HTML5 media elements by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/generic] Revert e6ae51c123897927eb3c9899923d8ffd31c7f85d
* [f4m] Bugfix
* [ffmpeg] Check version lazily
* [jsinterp] Some optimizations and refactoring by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
* [utils] Improve performance using `functools.cache`
* [utils] Send HTTP/1.1 ALPN extension by [coletdjnz](https://github.com/coletdjnz)
* [utils] `ExtractorError`: Fix `exc_info`
* [utils] `ISO3166Utils`: Add `EU` and `AP`
* [utils] `Popen`: Refactor to use contextmanager
* [utils] `locked_file`: Fix for PyPy on Windows
* [update] Expose more functionality to API
* [update] Use `.git` folder to distinguish `source`/`unknown`
* [compat] Add `functools.cached_property`
* [test] Fix `FakeYDL` signatures by [coletdjnz](https://github.com/coletdjnz)
* [docs] Improvements
* [cleanup, ExtractAudio] Refactor
* [cleanup, downloader] Refactor `report_progress`
* [cleanup, extractor] Refactor `_download_...` methods
* [cleanup, extractor] Rename `extractors.py` to `_extractors.py`
* [cleanup, utils] Don't use kwargs for `format_field`
* [cleanup, build] Refactor
* [cleanup, docs] Re-indent "Usage and Options" section
* [cleanup] Deprecate `YoutubeDL.parse_outtmpl`
* [cleanup] Misc fixes and cleanup by [Lesmiscore](https://github.com/Lesmiscore), [MrRawes](https://github.com/MrRawes), [christoph-heinrich](https://github.com/christoph-heinrich), [flashdagger](https://github.com/flashdagger), [gamer191](https://github.com/gamer191), [kwconder](https://github.com/kwconder), [pukkandan](https://github.com/pukkandan)
* [extractor/DailyWire] Add extractors by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
* [extractor/fourzerostudio] Add extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/GoogleDrive] Add folder extractor by [evansp](https://github.com/evansp), [pukkandan](https://github.com/pukkandan)
* [extractor/MirrorCoUK] Add extractor by [LunarFang416](https://github.com/LunarFang416), [pukkandan](https://github.com/pukkandan)
* [extractor/atscaleconfevent] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [extractor/freetv] Add extractor by [elyse0](https://github.com/elyse0)
* [extractor/ixigua] Add Extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/kicker.de] Add extractor by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/netverse] Add extractors by [HobbyistDev](https://github.com/HobbyistDev), [pukkandan](https://github.com/pukkandan)
* [extractor/playsuisse] Add extractor by [pukkandan](https://github.com/pukkandan), [sbor23](https://github.com/sbor23)
* [extractor/substack] Add extractor by [elyse0](https://github.com/elyse0)
* [extractor/youtube] **Support downloading clips**
* [extractor/youtube] Add `innertube_host` and `innertube_key` extractor args by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Add warning for PostLiveDvr
* [extractor/youtube] Bring back `_extract_chapters_from_description`
* [extractor/youtube] Extract `comment_count` from webpage
* [extractor/youtube] Fix `:ytnotifications` extractor by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Fix initial player response extraction by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [extractor/youtube] Fix live chat for videos with content warning by [coletdjnz](https://github.com/coletdjnz)
* [extractor/youtube] Make signature extraction non-fatal
* [extractor/youtube:tab] Detect `videoRenderer` in `_post_thread_continuation_entries`
* [extractor/BiliIntl] Fix metadata extraction
* [extractor/BiliIntl] Fix subtitle extraction by [HobbyistDev](https://github.com/HobbyistDev)
* [extractor/FranceCulture] Fix extractor by [aurelg](https://github.com/aurelg), [pukkandan](https://github.com/pukkandan)
* [extractor/PokemonSoundLibrary] Remove extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/StreamCZ] Fix extractor by [adamanldo](https://github.com/adamanldo), [dirkf](https://github.com/dirkf)
* [extractor/WatchESPN] Support free videos and BAM_DTC by [ischmidt20](https://github.com/ischmidt20)
* [extractor/animelab] Remove extractor by [gamer191](https://github.com/gamer191)
* [extractor/bloomberg] Change playback endpoint by [m4tu4g](https://github.com/m4tu4g)
* [extractor/ccc] Extract view_count by [vkorablin](https://github.com/vkorablin)
* [extractor/crunchyroll:beta] Fix extractor after API change by [Burve](https://github.com/Burve), [tejing1](https://github.com/tejing1)
* [extractor/curiositystream] Get `auth_token` from cookie by [mnn](https://github.com/mnn)
* [extractor/digitalconcerthall] Fix extractor by [ZhymabekRoman](https://github.com/ZhymabekRoman)
* [extractor/dropbox] Extract the correct `mountComponent`
* [extractor/dropout] Login is not mandatory
* [extractor/duboku] Fix for hostname change by [mozbugbox](https://github.com/mozbugbox)
* [extractor/espn] Add `WatchESPN` extractor by [ischmidt20](https://github.com/ischmidt20), [pukkandan](https://github.com/pukkandan)
* [extractor/expressen] Fix extractor by [aejdl](https://github.com/aejdl)
* [extractor/foxnews] Update embed extraction by [elyse0](https://github.com/elyse0)
* [extractor/ina] Fix extractor by [elyse0](https://github.com/elyse0)
* [extractor/iwara:user] Make paging better by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/jwplatform] Look for `data-video-jw-id`
* [extractor/lbry] Update livestream API by [flashdagger](https://github.com/flashdagger)
* [extractor/mediaset] Improve `_VALID_URL`
* [extractor/naver] Add `navernow` extractor by [ping](https://github.com/ping)
* [extractor/niconico:series] Fix extractor by [sqrtNOT](https://github.com/sqrtNOT)
* [extractor/npr] Use stream url from json-ld by [r5d](https://github.com/r5d)
* [extractor/pornhub] Extract `uploader_id` field by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/radiofrance] Add more radios by [bubbleguuum](https://github.com/bubbleguuum)
* [extractor/rumble] Detect JS embed
* [extractor/rumble] Extract subtitles by [fstirlitz](https://github.com/fstirlitz)
* [extractor/southpark] Add `southpark.lat` extractor by [darkxex](https://github.com/darkxex)
* [extractor/spotify:show] Fix extractor
* [extractor/tiktok] Detect embeds
* [extractor/tiktok] Extract `SIGI_STATE` by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan), [sulyi](https://github.com/sulyi)
* [extractor/tver] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/vevo] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [extractor/yahoo:gyao] Fix extractor
* [extractor/zattoo] Fix live streams by [miseran](https://github.com/miseran)
* [extractor/zdf] Improve format sorting by [elyse0](https://github.com/elyse0)


### 2022.05.18

* Add support for SSL client certificate authentication by [coletdjnz](https://github.com/coletdjnz), [dirkf](https://github.com/dirkf)
    * Adds `--client-certificate`, `--client-certificate-key`, `--client-certificate-password`
* Add `--match-filter -` to interactively ask for each video
* `--max-downloads` should obey `--break-per-input`
* Allow use of weaker ciphers with `--legacy-server-connect`
* Don't imply `-s` for later stages of `-O`
* Fix `--date today`
* Fix `--skip-unavailable-fragments`
* Fix color in `-q -F`
* Fix redirect HTTP method handling by [coletdjnz](https://github.com/coletdjnz)
* Improve `--clean-infojson`
* Remove warning for videos with an empty title
* Run `FFmpegFixupM3u8PP` for live-streams if needed
* Show name of downloader in verbose log
* [cookies] Allow `cookiefile` to be a text stream
* [cookies] Report progress when importing cookies
* [downloader/ffmpeg] Specify headers for each URL by [elyse0](https://github.com/elyse0)
* [fragment] Do not change chunk-size when `--test`
* [fragment] Make single thread download work for `--live-from-start` by [Lesmiscore](https://github.com/Lesmiscore)
* [hls] Fix `byte_range` for `EXT-X-MAP` fragment by [fstirlitz](https://github.com/fstirlitz)
* [http] Fix retrying on read timeout by [coletdjnz](https://github.com/coletdjnz)
* [ffmpeg] Fix features detection
* [EmbedSubtitle] Enable for more video extensions
* [EmbedThumbnail] Disable thumbnail conversion for mkv by [evansp](https://github.com/evansp)
* [EmbedThumbnail] Do not obey `-k`
* [EmbedThumbnail] Do not remove id3v1 tags
* [FFmpegMetadata] Remove `\0` from metadata
* [FFmpegMetadata] Remove filename from attached info-json
* [FixupM3u8] Obey `--hls-prefer-mpegts`
* [Sponsorblock] Don't crash when duration is unknown
* [XAttrMetadata] Refactor and document dependencies
* [extractor] Document netrc machines
* [extractor] Update `manifest_url`s after redirect by [elyse0](https://github.com/elyse0)
* [extractor] Update dash `manifest_url` after redirects by [elyse0](https://github.com/elyse0)
* [extractor] Use `classmethod`/`property` where possible
* [generic] Refactor `_extract_rss`
* [utils] `is_html`: Handle double BOM
* [utils] `locked_file`: Ignore illegal seek on `truncate` by [jakeogh](https://github.com/jakeogh)
* [utils] `sanitize_path`: Fix when path is empty string
* [utils] `write_string`: Workaround newline issue in `conhost`
* [utils] `certifi`: Make sure the pem file exists
* [utils] Fix `WebSocketsWrapper`
* [utils] `locked_file`: Do not give executable bits for newly created files by [Lesmiscore](https://github.com/Lesmiscore)
* [utils] `YoutubeDLCookieJar`: Detect and reject JSON file by [Lesmiscore](https://github.com/Lesmiscore)
* [test] Convert warnings into errors and fix some existing warnings by [fstirlitz](https://github.com/fstirlitz)
* [dependencies] Create module with all dependency imports
* [compat] Split into sub-modules by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
* [compat] Implement `compat.imghdr`
* [build] Add `make uninstall` by [MrRawes](https://github.com/MrRawes)
* [build] Avoid use of `install -D`
* [build] Fix `Makefile` by [putnam](https://github.com/putnam)
* [build] Fix `--onedir` on macOS
* [build] Add more test-runners
* [cleanup] Deprecate some compat vars by [fstirlitz](https://github.com/fstirlitz), [pukkandan](https://github.com/pukkandan)
* [cleanup] Remove unused code paths, extractors, scripts and tests by [fstirlitz](https://github.com/fstirlitz)
* [cleanup] Upgrade syntax (`pyupgrade`) and sort imports (`isort`)
* [cleanup, docs, build] Misc fixes
* [BilibiliLive] Add extractor by [HE7086](https://github.com/HE7086), [pukkandan](https://github.com/pukkandan)
* [Fifa] Add Extractor by [Bricio](https://github.com/Bricio)
* [goodgame] Add extractor by [nevack](https://github.com/nevack)
* [gronkh] Add playlist extractors by [hatienl0i261299](https://github.com/hatienl0i261299)
* [icareus] Add extractor by [tpikonen](https://github.com/tpikonen), [pukkandan](https://github.com/pukkandan)
* [iwara] Add playlist extractors by [i6t](https://github.com/i6t)
* [Likee] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [masters] Add extractor by [m4tu4g](https://github.com/m4tu4g)
* [nebula] Add support for subscriptions by [hheimbuerger](https://github.com/hheimbuerger)
* [Podchaser] Add extractors by [connercsbn](https://github.com/connercsbn)
* [rokfin:search] Add extractor by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
* [youtube] Add `:ytnotifications` extractor by [krichbanana](https://github.com/krichbanana)
* [youtube] Add YoutubeStoriesIE (`ytstories:<channel UCID>`) by [coletdjnz](https://github.com/coletdjnz)
* [ZingMp3] Add chart and user extractors by [hatienl0i261299](https://github.com/hatienl0i261299)
* [adn] Update AES key by [elyse0](https://github.com/elyse0)
* [adobepass] Allow cookies for authenticating MSO
* [bandcamp] Exclude merch links by [Yipten](https://github.com/Yipten)
* [chingari] Fix archiving and tests
* [DRTV] Improve `_VALID_URL` by [vertan](https://github.com/vertan)
* [facebook] Improve thumbnail extraction by [Wikidepia](https://github.com/Wikidepia)
* [fc2] Stop heatbeating once FFmpeg finishes by [Lesmiscore](https://github.com/Lesmiscore)
* [Gofile] Fix extraction and support password-protected links by [mehq](https://github.com/mehq)
* [hotstar, cleanup] Refactor extractors
* [InfoQ] Don't fail on missing audio format by [evansp](https://github.com/evansp)
* [Jamendo] Extract more metadata by [evansp](https://github.com/evansp)
* [kaltura] Update API calls by [flashdagger](https://github.com/flashdagger)
* [KhanAcademy] Fix extractor by [rand-net](https://github.com/rand-net)
* [LCI] Fix extractor by [MarwenDallel](https://github.com/MarwenDallel)
* [lrt] Support livestreams by [GiedriusS](https://github.com/GiedriusS)
* [niconico] Set `expected_protocol` to a public field
* [Niconico] Support 2FA by [ekangmonyet](https://github.com/ekangmonyet)
* [Olympics] Fix format extension
* [openrec:movie] Enable fallback for /movie/ URLs
* [PearVideo] Add fallback for formats by [hatienl0i261299](https://github.com/hatienl0i261299)
* [radiko] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [rai] Add `release_year`
* [reddit] Prevent infinite loop
* [rokfin] Implement login by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
* [ruutu] Support hs.fi embeds by [tpikonen](https://github.com/tpikonen), [pukkandan](https://github.com/pukkandan)
* [spotify] Detect iframe embeds by [fstirlitz](https://github.com/fstirlitz)
* [telegram] Fix metadata extraction
* [tmz, cleanup] Update tests by [diegorodriguezv](https://github.com/diegorodriguezv)
* [toggo] Fix `_VALID_URL` by [ca-za](https://github.com/ca-za)
* [trovo] Update to new API by [nyuszika7h](https://github.com/nyuszika7h)
* [TVer] Improve extraction by [Lesmiscore](https://github.com/Lesmiscore)
* [twitcasting] Pass headers for each formats by [Lesmiscore](https://github.com/Lesmiscore)
* [VideocampusSachsen] Improve extractor by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
* [vimeo] Fix extractors
* [wat] Fix extraction of multi-language videos and subtitles by [elyse0](https://github.com/elyse0)
* [wistia] Fix `_VALID_URL` by [dirkf](https://github.com/dirkf)
* [youtube, cleanup] Minor refactoring by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [youtube] Added piped instance urls by [JordanWeatherby](https://github.com/JordanWeatherby)
* [youtube] Deprioritize auto-generated thumbnails
* [youtube] Deprioritize format 22 (often damaged)
* [youtube] Fix episode metadata extraction
* [zee5] Fix extractor by [Ashish0804](https://github.com/Ashish0804)
* [zingmp3, cleanup] Refactor extractors


### 2022.04.08

* Use certificates from `certifi` if installed by [coletdjnz](https://github.com/coletdjnz)
* Treat multiple `--match-filters` as OR
* File locking improvements:
    * Do not lock downloading file on Windows
    * Do not prevent download if locking is unsupported
    * Do not truncate files before locking by [jakeogh](https://github.com/jakeogh), [pukkandan](https://github.com/pukkandan)
    * Fix non-blocking non-exclusive lock
* De-prioritize automatic-subtitles when no `--sub-lang` is given
* Exit after `--dump-user-agent`
* Fallback to video-only format when selecting by extension
* Fix `--abort-on-error` for subtitles
* Fix `--no-overwrite` for playlist infojson
* Fix `--print` with `--ignore-no-formats` when url is `None` by [flashdagger](https://github.com/flashdagger)
* Fix `--sleep-interval`
* Fix `--throttled-rate`
* Fix `autonumber`
* Fix case of `http_headers`
* Fix filepath sanitization in `--print-to-file`
* Handle float in `--wait-for-video`
* Ignore `mhtml` formats from `-f mergeall`
* Ignore format-specific fields in initial pass of `--match-filter`
* Protect stdout from unexpected progress and console-title
* Remove `Accept-Encoding` header from `std_headers` by [coletdjnz](https://github.com/coletdjnz)
* Remove incorrect warning for `--dateafter`
* Show warning when all media formats have DRM
* [downloader] Fix invocation of `HttpieFD`
* [http] Fix #3215
* [http] Reject broken range before request by [Lesmiscore](https://github.com/Lesmiscore), [Jules-A](https://github.com/Jules-A), [pukkandan](https://github.com/pukkandan)
* [fragment] Read downloaded fragments only when needed by [Lesmiscore](https://github.com/Lesmiscore)
* [http] Retry on more errors by [coletdjnz](https://github.com/coletdjnz)
* [mhtml] Fix fragments with absolute urls by [coletdjnz](https://github.com/coletdjnz)
* [extractor] Add `_perform_login` function
* [extractor] Allow control characters inside json
* [extractor] Support merging subtitles with data by [coletdjnz](https://github.com/coletdjnz)
* [generic] Extract subtitles from video.js by [Lesmiscore](https://github.com/Lesmiscore)
* [ffmpeg] Cache version data
* [FFmpegConcat] Ensure final directory exists
* [FfmpegMetadata] Write id3v1 tags
* [FFmpegVideoConvertor] Add more formats to `--remux-video`
* [FFmpegVideoConvertor] Ensure all streams are copied
* [MetadataParser] Validate outtmpl early
* [outtmpl] Fix replacement/default when used with alternate
* [outtmpl] Limit changes during sanitization
* [phantomjs] Fix bug
* [test] Add `test_locked_file`
* [utils] `format_decimal_suffix`: Fix for very large numbers by [s0u1h](https://github.com/s0u1h)
* [utils] `traverse_obj`: Allow filtering by value
* [utils] Add `filter_dict`, `get_first`, `try_call`
* [utils] ExtractorError: Fix for older python versions
* [utils] WebSocketsWrapper: Allow omitting `__enter__` invocation by [Lesmiscore](https://github.com/Lesmiscore)
* [docs] Add an `.editorconfig` file by [fstirlitz](https://github.com/fstirlitz)
* [docs] Clarify the exact `BSD` license of dependencies by [MrRawes](https://github.com/MrRawes)
* [docs] Minor improvements by [pukkandan](https://github.com/pukkandan), [cffswb](https://github.com/cffswb), [danielyli](https://github.com/danielyli)
* [docs] Remove readthedocs
* [build] Add `requirements.txt` to pip distributions
* [cleanup, postprocessor] Create `_download_json`
* [cleanup, vimeo] Fix tests
* [cleanup] Misc fixes and minor cleanup
* [cleanup] Use `_html_extract_title`
* [AfreecaTV] Add `AfreecaTVUserIE` by [hatienl0i261299](https://github.com/hatienl0i261299)
* [arte] Add `format_note` to m3u8 formats
* [azmedien] Add TVO Online to supported hosts by [1-Byte](https://github.com/1-Byte)
* [BanBye] Add extractor by [mehq](https://github.com/mehq)
* [bilibili] Fix extraction of title with quotes by [dzek69](https://github.com/dzek69)
* [Craftsy] Add extractor by [Bricio](https://github.com/Bricio)
* [Cybrary] Add extractor by [aaearon](https://github.com/aaearon)
* [Huya] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [ITProTV] Add extractor by [aaearon](https://github.com/aaearon)
* [Jable] Add extractors by [mehq](https://github.com/mehq)
* [LastFM] Add extractors by [mehq](https://github.com/mehq)
* [Moviepilot] Add extractor by [panatexxa](https://github.com/panatexxa)
* [panopto] Add extractors by [coletdjnz](https://github.com/coletdjnz), [kmark](https://github.com/kmark)
* [PokemonSoundLibrary] Add extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [WasdTV] Add extractor by [un-def](https://github.com/un-def), [hatienl0i261299](https://github.com/hatienl0i261299)
* [adobepass] Fix Suddenlink MSO by [CplPwnies](https://github.com/CplPwnies)
* [afreecatv] Match new vod url by [wlritchi](https://github.com/wlritchi)
* [AZMedien] Support `tv.telezueri.ch` by [goggle](https://github.com/goggle)
* [BiliIntl] Support user-generated videos by [wlritchi](https://github.com/wlritchi)
* [BRMediathek] Fix VALID_URL
* [crunchyroll:playlist] Implement beta API by [tejing1](https://github.com/tejing1)
* [crunchyroll] Fix inheritance
* [daftsex] Fix extractor by [Soebb](https://github.com/Soebb)
* [dailymotion] Support `geo.dailymotion.com` by [hatienl0i261299](https://github.com/hatienl0i261299)
* [ellentube] Extract subtitles from manifest
* [elonet] Rewrite extractor by [Fam0r](https://github.com/Fam0r), [pukkandan](https://github.com/pukkandan)
* [fptplay] Fix metadata extraction by [hatienl0i261299](https://github.com/hatienl0i261299)
* [FranceCulture] Support playlists by [bohwaz](https://github.com/bohwaz)
* [go, viu] Extract subtitles from the m3u8 manifest by [fstirlitz](https://github.com/fstirlitz)
* [Imdb] Improve extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [MangoTV] Improve extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [Nebula] Fix bug in 52efa4b31200119adaa8acf33e50b84fcb6948f0
* [niconico] Fix extraction of thumbnails and uploader (#3266)
* [niconico] Rewrite NiconicoIE by [Lesmiscore](https://github.com/Lesmiscore)
* [nitter] Minor fixes and update instance list by [foghawk](https://github.com/foghawk)
* [NRK] Extract timestamp by [hatienl0i261299](https://github.com/hatienl0i261299)
* [openrec] Download archived livestreams by [Lesmiscore](https://github.com/Lesmiscore)
* [openrec] Refactor extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [panopto] Improve subtitle extraction and support slides by [coletdjnz](https://github.com/coletdjnz)
* [ParamountPlus, CBS] Change VALID_URL by [Sipherdrakon](https://github.com/Sipherdrakon)
* [ParamountPlusSeries] Support multiple pages by [dodrian](https://github.com/dodrian)
* [Piapro] Extract description with break lines by [Lesmiscore](https://github.com/Lesmiscore)
* [rai] Fix extraction of http formas by [nixxo](https://github.com/nixxo)
* [rumble] unescape title
* [RUTV] Fix format sorting by [Lesmiscore](https://github.com/Lesmiscore)
* [ruutu] Detect embeds by [tpikonen](https://github.com/tpikonen)
* [tenplay] Improve extractor by [aarubui](https://github.com/aarubui)
* [TikTok] Fix URLs with user id by [hatienl0i261299](https://github.com/hatienl0i261299)
* [TikTokVM] Fix redirect to user URL
* [TVer] Fix extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [TVer] Support landing page by [vvto33](https://github.com/vvto33)
* [twitcasting] Don't return multi_video for archive with single hls manifest by [Lesmiscore](https://github.com/Lesmiscore)
* [veo] Fix `_VALID_URL`
* [Veo] Fix extractor by [i6t](https://github.com/i6t)
* [viki] Don't attempt to modify URLs with signature by [nyuszika7h](https://github.com/nyuszika7h)
* [viu] Fix bypass for preview by [zackmark29](https://github.com/zackmark29)
* [viu] Fixed extractor by [zackmark29](https://github.com/zackmark29), [pukkandan](https://github.com/pukkandan)
* [web.archive:youtube] Make CDX API requests non-fatal by [coletdjnz](https://github.com/coletdjnz)
* [wget] Fix proxy by [kikuyan](https://github.com/kikuyan), [coletdjnz](https://github.com/coletdjnz)
* [xnxx] Add `xnxx3.com` by [rozari0](https://github.com/rozari0)
* [youtube] **Add new age-gate bypass** by [zerodytrash](https://github.com/zerodytrash), [pukkandan](https://github.com/pukkandan)
* [youtube] Add extractor-arg to skip auto-translated subs
* [youtube] Avoid false positives when detecting damaged formats
* [youtube] Detect DRM better by [shirt](https://github.com/shirt-dev)
* [youtube] Fix auto-translated automatic captions
* [youtube] Fix pagination of `membership` tab
* [youtube] Fix uploader for collaborative playlists by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Improve video upload date handling by [coletdjnz](https://github.com/coletdjnz)
* [youtube:api] Prefer minified JSON response by [coletdjnz](https://github.com/coletdjnz)
* [youtube:search] Support hashtag entries by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Fix duration extraction for shorts by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Minor improvements
* [youtube:tab] Return shorts url if video is a short by [coletdjnz](https://github.com/coletdjnz)
* [Zattoo] Fix extractors by [goggle](https://github.com/goggle)
* [Zingmp3] Fix signature by [hatienl0i261299](https://github.com/hatienl0i261299)


### 2022.03.08.1

* [cleanup] Refactor `__init__.py`
* [build] Fix bug

### 2022.03.08

* Merge youtube-dl: Upto [commit/6508688](https://github.com/ytdl-org/youtube-dl/commit/6508688e88c83bb811653083db9351702cd39a6a) (except NDR)
* Add regex operator and quoting to format filters by [lukasfink1](https://github.com/lukasfink1)
* Add brotli content-encoding support by [coletdjnz](https://github.com/coletdjnz)
* Add pre-processor stage `after_filter`
* Better error message when no `--live-from-start` format
* Create necessary directories for `--print-to-file`
* Fill more fields for playlists by [Lesmiscore](https://github.com/Lesmiscore)
* Fix `-all` for `--sub-langs`
* Fix doubling of `video_id` in `ExtractorError`
* Fix for when stdout/stderr encoding is `None`
* Handle negative duration from extractor
* Implement `--add-header` without modifying `std_headers`
* Obey `--abort-on-error` for "ffmpeg not installed"
* Set `webpage_url_...` from `webpage_url` and not input URL
* Tolerate failure to `--write-link` due to unknown URL
* [aria2c] Add `--http-accept-gzip=true`
* [build] Update pyinstaller to 4.10 by [shirt](https://github.com/shirt-dev)
* [cookies] Update MacOS12 `Cookies.binarycookies` location by [mdpauley](https://github.com/mdpauley)
* [devscripts] Improve `prepare_manpage`
* [downloader] Do not use aria2c for non-native `m3u8`
* [downloader] Obey `--file-access-retries` when deleting/renaming by [ehoogeveen-medweb](https://github.com/ehoogeveen-medweb)
* [extractor] Allow `http_headers` to be specified for `thumbnails`
* [extractor] Extract subtitles from manifests for vimeo, globo, kaltura, svt by [fstirlitz](https://github.com/fstirlitz)
* [extractor] Fix for manifests without period duration by [dirkf](https://github.com/dirkf), [pukkandan](https://github.com/pukkandan)
* [extractor] Support `--mark-watched` without `_NETRC_MACHINE` by [coletdjnz](https://github.com/coletdjnz)
* [FFmpegConcat] Abort on `--simulate`
* [FormatSort] Consider `acodec`=`ogg` as `vorbis`
* [fragment] Fix bugs around resuming with Range by [Lesmiscore](https://github.com/Lesmiscore)
* [fragment] Improve `--live-from-start` for YouTube livestreams by [Lesmiscore](https://github.com/Lesmiscore)
* [generic] Pass referer to extracted formats
* [generic] Set rss `guid` as video id by [Bricio](https://github.com/Bricio)
* [options] Better ambiguous option resolution
* [options] Rename `--clean-infojson` to `--clean-info-json`
* [SponsorBlock] Fixes for highlight and "full video labels" by [nihil-admirari](https://github.com/nihil-admirari)
* [Sponsorblock] minor fixes by [nihil-admirari](https://github.com/nihil-admirari)
* [utils] Better traceback for `ExtractorError`
* [utils] Fix file locking for AOSP by [jakeogh](https://github.com/jakeogh)
* [utils] Improve file locking
* [utils] OnDemandPagedList: Do not download pages after error
* [utils] render_table: Fix character calculation for removing extra gap by [Lesmiscore](https://github.com/Lesmiscore)
* [utils] Use `locked_file` for `sanitize_open` by [jakeogh](https://github.com/jakeogh)
* [utils] Validate `DateRange` input
* [utils] WebSockets wrapper for non-async functions by [Lesmiscore](https://github.com/Lesmiscore)
* [cleanup] Don't pass protocol to `_extract_m3u8_formats` for live videos
* [cleanup] Remove extractors for some dead websites by [marieell](https://github.com/marieell)
* [cleanup, docs] Misc cleanup
* [AbemaTV] Add extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [adobepass] Add Suddenlink MSO by [CplPwnies](https://github.com/CplPwnies)
* [ant1newsgr] Add extractor by [zmousm](https://github.com/zmousm)
* [bigo] Add extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [Caltrans] Add extractor by [Bricio](https://github.com/Bricio)
* [daystar] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [fc2:live] Add extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [fptplay] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [murrtube] Add extractor by [cyberfox1691](https://github.com/cyberfox1691)
* [nfb] Add extractor by [ofkz](https://github.com/ofkz)
* [niconico] Add playlist extractors and refactor by [Lesmiscore](https://github.com/Lesmiscore)
* [peekvids] Add extractor by [schn0sch](https://github.com/schn0sch)
* [piapro] Add extractor by [pycabbage](https://github.com/pycabbage), [Lesmiscore](https://github.com/Lesmiscore)
* [rokfin] Add extractor by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
* [rokfin] Add stack and channel extractors by [P-reducible](https://github.com/P-reducible), [pukkandan](https://github.com/pukkandan)
* [ruv.is] Add extractor by [iw0nderhow](https://github.com/iw0nderhow)
* [telegram] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [VideocampusSachsen] Add extractors by [FestplattenSchnitzel](https://github.com/FestplattenSchnitzel)
* [xinpianchang] Add extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [abc] Support 1080p by [Ronnnny](https://github.com/Ronnnny)
* [afreecatv] Support password-protected livestreams by [wlritchi](https://github.com/wlritchi)
* [ard] Fix valid URL
* [ATVAt] Detect geo-restriction by [marieell](https://github.com/marieell)
* [bandcamp] Detect acodec
* [bandcamp] Fix user URLs by [lyz-code](https://github.com/lyz-code)
* [bbc] Fix extraction of news articles by [ajj8](https://github.com/ajj8)
* [beeg] Fix extractor by [Bricio](https://github.com/Bricio)
* [bigo] Fix extractor to not to use `form_params`
* [Bilibili] Pass referer for all formats by [blackgear](https://github.com/blackgear)
* [Biqle] Fix extractor by [Bricio](https://github.com/Bricio)
* [ccma] Fix timestamp parsing by [nyuszika7h](https://github.com/nyuszika7h)
* [crunchyroll] Better error reporting on login failure by [tejing1](https://github.com/tejing1)
* [cspan] Support of C-Span congress videos by [Grabien](https://github.com/Grabien)
* [dropbox] fix regex by [zenerdi0de](https://github.com/zenerdi0de)
* [fc2] Fix extraction by [Lesmiscore](https://github.com/Lesmiscore)
* [fujitv] Extract resolution for free sources by [YuenSzeHong](https://github.com/YuenSzeHong)
* [Gettr] Add `GettrStreamingIE` by [i6t](https://github.com/i6t)
* [Gettr] Fix formats order by [i6t](https://github.com/i6t)
* [Gettr] Improve extractor by [i6t](https://github.com/i6t)
* [globo] Expand valid URL by [Bricio](https://github.com/Bricio)
* [lbry] Fix `--ignore-no-formats-error`
* [manyvids] Extract `uploader` by [regarten](https://github.com/regarten)
* [mildom] Fix linter
* [mildom] Rework extractors by [Lesmiscore](https://github.com/Lesmiscore)
* [mirrativ] Cleanup extractor code by [Lesmiscore](https://github.com/Lesmiscore)
* [nhk] Add support for NHK for School by [Lesmiscore](https://github.com/Lesmiscore)
* [niconico:tag] Add support for searching tags
* [nrk] Add fallback API
* [peekvids] Use JSON-LD by [schn0sch](https://github.com/schn0sch)
* [peertube] Add media.fsfe.org by [mxmehl](https://github.com/mxmehl)
* [rtvs] Fix extractor by [Bricio](https://github.com/Bricio)
* [spiegel] Fix `_VALID_URL`
* [ThumbnailsConvertor] Support `webp`
* [tiktok] Fix `vm.tiktok`/`vt.tiktok` URLs
* [tubitv] Fix/improve TV series extraction by [bbepis](https://github.com/bbepis)
* [tumblr] Fix extractor by [foghawk](https://github.com/foghawk)
* [twitcasting] Add fallback for finding running live by [Lesmiscore](https://github.com/Lesmiscore)
* [TwitCasting] Check for password protection by [Lesmiscore](https://github.com/Lesmiscore)
* [twitcasting] Fix extraction by [Lesmiscore](https://github.com/Lesmiscore)
* [twitch] Fix field name of `view_count`
* [twitter] Fix for private videos by [iphoting](https://github.com/iphoting)
* [washingtonpost] Fix extractor by [Bricio](https://github.com/Bricio)
* [youtube:tab] Add `approximate_date` extractor-arg
* [youtube:tab] Follow redirect to regional channel  by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Reject webpage data if redirected to home page
* [youtube] De-prioritize potentially damaged formats
* [youtube] Differentiate descriptive audio by language code
* [youtube] Ensure subtitle urls are absolute by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Escape possible `$` in `_extract_n_function_name` regex by [Lesmiscore](https://github.com/Lesmiscore)
* [youtube] Fix automatic captions
* [youtube] Fix n-sig extraction for phone player JS by [MinePlayersPE](https://github.com/MinePlayersPE)
* [youtube] Further de-prioritize 3gp format
* [youtube] Label original auto-subs
* [youtube] Prefer UTC upload date for videos by [coletdjnz](https://github.com/coletdjnz)
* [zaq1] Remove dead extractor by [marieell](https://github.com/marieell)
* [zee5] Support web-series by [Aniruddh-J](https://github.com/Aniruddh-J)
* [zingmp3] Fix extractor by [hatienl0i261299](https://github.com/hatienl0i261299)
* [zoom] Add support for screen cast by [Mipsters](https://github.com/Mipsters)


### 2022.02.04

* [youtube:search] Fix extractor by [coletdjnz](https://github.com/coletdjnz)
* [youtube:search] Add tests
* [twitcasting] Enforce UTF-8 for POST payload by [Lesmiscore](https://github.com/Lesmiscore)
* [mediaset] Fix extractor by [nixxo](https://github.com/nixxo)
* [websocket] Make syntax error in `websockets` module non-fatal

### 2022.02.03

* Merge youtube-dl: Upto [commit/78ce962](https://github.com/ytdl-org/youtube-dl/commit/78ce962f4fe020994c216dd2671546fbe58a5c67)
* Add option `--print-to-file`
* Make nested --config-locations relative to parent file
* Ensure `_type` is present in `info.json`
* Fix `--compat-options list-formats`
* Fix/improve `InAdvancePagedList`
* [downloader/ffmpeg] Handle unknown formats better
* [outtmpl] Handle `-o ""` better
* [outtmpl] Handle hard-coded file extension better
* [extractor] Add convenience function `_yes_playlist`
* [extractor] Allow non-fatal `title` extraction
* [extractor] Extract video inside `Article` json_ld
* [generic] Allow further processing of json_ld URL
* [cookies] Fix keyring selection for unsupported desktops
* [utils] Strip double spaces in `clean_html` by [dirkf](https://github.com/dirkf)
* [aes] Add `unpad_pkcs7`
* [test] Fix `test_youtube_playlist_noplaylist`
* [docs,cleanup] Misc cleanup
* [dplay] Add extractors for site changes by [Sipherdrakon](https://github.com/Sipherdrakon)
* [ertgr] Add  extractors by [zmousm](https://github.com/zmousm), [dirkf](https://github.com/dirkf)
* [Musicdex] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [YandexVideoPreview] Add extractor by [KiberInfinity](https://github.com/KiberInfinity)
* [youtube] Add extractor `YoutubeMusicSearchURLIE`
* [archive.org] Ignore unnecessary files
* [Bilibili] Add 8k support by [u-spec-png](https://github.com/u-spec-png)
* [bilibili] Fix extractor, make anthology title non-fatal
* [CAM4] Add thumbnail extraction by [alerikaisattera](https://github.com/alerikaisattera)
* [cctv] De-prioritize sample format
* [crunchyroll:beta] Add cookies support by [tejing1](https://github.com/tejing1)
* [crunchyroll] Fix login by [tejing1](https://github.com/tejing1)
* [doodstream] Fix extractor
* [fc2] Fix extraction by [Lesmiscore](https://github.com/Lesmiscore)
* [FFmpegConcat] Abort on --skip-download and download errors
* [Fujitv] Extract metadata and support premium by [YuenSzeHong](https://github.com/YuenSzeHong)
* [globo] Fix extractor by [Bricio](https://github.com/Bricio)
* [glomex] Simplify embed detection
* [GoogleSearch] Fix extractor
* [Instagram] Fix extraction when logged in by [MinePlayersPE](https://github.com/MinePlayersPE)
* [iq.com] Add VIP support by [MinePlayersPE](https://github.com/MinePlayersPE)
* [mildom] Fix extractor by [lazypete365](https://github.com/lazypete365)
* [MySpass] Fix video url processing by [trassshhub](https://github.com/trassshhub)
* [Odnoklassniki] Improve embedded players extraction by [KiberInfinity](https://github.com/KiberInfinity)
* [orf:tvthek] Lazy playlist extraction and obey --no-playlist
* [Pladform] Fix redirection to external player by [KiberInfinity](https://github.com/KiberInfinity)
* [ThisOldHouse] Improve Premium URL check by [Ashish0804](https://github.com/Ashish0804)
* [TikTok] Iterate through app versions by [MinePlayersPE](https://github.com/MinePlayersPE)
* [tumblr] Fix 403 errors and handle vimeo embeds by [foghawk](https://github.com/foghawk)
* [viki] Fix "Bad request" for manifest by [nyuszika7h](https://github.com/nyuszika7h)
* [Vimm] add recording extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [web.archive:youtube] Add `ytarchive:` prefix and misc cleanup
* [youtube:api] Do not use seek when reading HTTPError response by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix n-sig for player e06dea74
* [youtube, cleanup] Misc fixes and cleanup


### 2022.01.21

* Add option `--concat-playlist` to **concat videos in a playlist**
* Allow **multiple and nested configuration files**
* Add more post-processing stages (`after_video`, `playlist`)
* Allow `--exec` to be run at any post-processing stage (Deprecates `--exec-before-download`)
* Allow `--print` to be run at any post-processing stage
* Allow listing formats, thumbnails, subtitles using `--print` by [pukkandan](https://github.com/pukkandan), [Zirro](https://github.com/Zirro)
* Add fields `video_autonumber`, `modified_date`, `modified_timestamp`, `playlist_count`, `channel_follower_count`
* Add key `requested_downloads` in the root `info_dict`
* Write `download_archive` only after all formats are downloaded
* [FfmpegMetadata] Allow setting metadata of individual streams using `meta<n>_` prefix
* Add option `--legacy-server-connect` by [xtkoba](https://github.com/xtkoba)
* Allow escaped `,` in `--extractor-args`
* Allow unicode characters in `info.json`
* Check for existing thumbnail/subtitle in final directory
* Don't treat empty containers as `None` in `sanitize_info`
* Fix `-s --ignore-no-formats --force-write-archive`
* Fix live title for multiple formats
* List playlist thumbnails in `--list-thumbnails`
* Raise error if subtitle download fails
* [cookies] Fix bug when keyring is unspecified
* [ffmpeg] Ignore unknown streams, standardize use of `-map 0`
* [outtmpl] Alternate form for `D` and fix suffix's case
* [utils] Add `Sec-Fetch-Mode` to `std_headers`
* [utils] Fix `format_bytes` output for Bytes by [pukkandan](https://github.com/pukkandan), [mdawar](https://github.com/mdawar)
* [utils] Handle `ss:xxx` in `parse_duration`
* [utils] Improve parsing for nested HTML elements by [zmousm](https://github.com/zmousm), [pukkandan](https://github.com/pukkandan)
* [utils] Use key `None` in `traverse_obj` to return as-is
* [extractor] Detect more subtitle codecs in MPD manifests by [fstirlitz](https://github.com/fstirlitz)
* [extractor] Extract chapters from JSON-LD by [iw0nderhow](https://github.com/iw0nderhow), [pukkandan](https://github.com/pukkandan)
* [extractor] Extract thumbnails from JSON-LD by [nixxo](https://github.com/nixxo)
* [extractor] Improve `url_result` and related
* [generic] Improve KVS player extraction by [trassshhub](https://github.com/trassshhub)
* [build] Reduce dependency on third party workflows
* [extractor,cleanup] Use `_search_nextjs_data`, `format_field`
* [cleanup] Minor fixes and cleanup
* [docs] Improvements
* [test] Fix TestVerboseOutput
* [afreecatv] Add livestreams extractor by [wlritchi](https://github.com/wlritchi)
* [callin] Add extractor by [foghawk](https://github.com/foghawk)
* [CrowdBunker] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [daftsex] Add extractors by [k3ns1n](https://github.com/k3ns1n)
* [digitalconcerthall] Add extractor by [teridon](https://github.com/teridon)
* [Drooble] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [EuropeanTour] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [iq.com] Add extractors by [MinePlayersPE](https://github.com/MinePlayersPE)
* [KelbyOne] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [LnkIE] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [MainStreaming] Add extractor by [coletdjnz](https://github.com/coletdjnz)
* [megatvcom] Add extractors by [zmousm](https://github.com/zmousm)
* [Newsy] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [noodlemagazine] Add extractor by [trassshhub](https://github.com/trassshhub)
* [PokerGo] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [Pornez] Add extractor by [mozlima](https://github.com/mozlima)
* [PRX] Add Extractors by [coletdjnz](https://github.com/coletdjnz)
* [RTNews] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [Rule34video] Add extractor by [trassshhub](https://github.com/trassshhub)
* [tvopengr] Add extractors by [zmousm](https://github.com/zmousm)
* [Vimm] Add extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [glomex] Add extractors by [zmousm](https://github.com/zmousm)
* [instagram] Add story/highlight extractor by [u-spec-png](https://github.com/u-spec-png)
* [openrec] Add movie extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [rai] Add Raiplaysound extractors by [nixxo](https://github.com/nixxo), [pukkandan](https://github.com/pukkandan)
* [aparat] Fix extractor
* [ard] Extract subtitles by [fstirlitz](https://github.com/fstirlitz)
* [BiliIntl] Add login by [MinePlayersPE](https://github.com/MinePlayersPE)
* [CeskaTelevize] Use `http` for manifests
* [CTVNewsIE] Add fallback for video search by [Ashish0804](https://github.com/Ashish0804)
* [dplay] Migrate DiscoveryPlusItaly to DiscoveryPlus by [timendum](https://github.com/timendum)
* [dplay] Re-structure DiscoveryPlus extractors
* [Dropbox] Support password protected files and more formats by [zenerdi0de](https://github.com/zenerdi0de)
* [facebook] Fix extraction from groups
* [facebook] Improve title and uploader extraction
* [facebook] Parse dash manifests
* [fox] Extract m3u8 from preview by [ischmidt20](https://github.com/ischmidt20)
* [funk] Support origin URLs
* [gfycat] Fix `uploader`
* [gfycat] Support embeds by [coletdjnz](https://github.com/coletdjnz)
* [hotstar] Add extractor args to ignore tags by [Ashish0804](https://github.com/Ashish0804)
* [hrfernsehen] Fix ardloader extraction by [CreaValix](https://github.com/CreaValix)
* [instagram] Fix username extraction for stories and highlights by [nyuszika7h](https://github.com/nyuszika7h)
* [kakao] Detect geo-restriction
* [line] Remove `tv.line.me` by [sian1468](https://github.com/sian1468)
* [mixch] Add `MixchArchiveIE` by [Lesmiscore](https://github.com/Lesmiscore)
* [mixcloud] Detect restrictions by [llacb47](https://github.com/llacb47)
* [NBCSports] Fix extraction of platform URLs by [ischmidt20](https://github.com/ischmidt20)
* [Nexx] Extract more metadata by [MinePlayersPE](https://github.com/MinePlayersPE)
* [Nexx] Support 3q CDN by [MinePlayersPE](https://github.com/MinePlayersPE)
* [pbs] de-prioritize AD formats
* [PornHub,YouTube] Refresh onion addresses by [unit193](https://github.com/unit193)
* [RedBullTV] Parse subtitles from manifest by [Ashish0804](https://github.com/Ashish0804)
* [streamcz] Fix extractor by [arkamar](https://github.com/arkamar), [pukkandan](https://github.com/pukkandan)
* [Ted] Rewrite extractor by [pukkandan](https://github.com/pukkandan), [trassshhub](https://github.com/trassshhub)
* [Theta] Fix valid URL by [alerikaisattera](https://github.com/alerikaisattera)
* [ThisOldHouseIE] Add support for premium videos by [Ashish0804](https://github.com/Ashish0804)
* [TikTok] Fix extraction for sigi-based webpages, add API fallback by [MinePlayersPE](https://github.com/MinePlayersPE)
* [TikTok] Pass cookies to formats, and misc fixes by [MinePlayersPE](https://github.com/MinePlayersPE)
* [TikTok] Extract captions, user thumbnail by [MinePlayersPE](https://github.com/MinePlayersPE)
* [TikTok] Change app version by [MinePlayersPE](https://github.com/MinePlayersPE), [llacb47](https://github.com/llacb47)
* [TVer] Extract message for unaired live by [Lesmiscore](https://github.com/Lesmiscore)
* [twitcasting] Refactor extractor by [Lesmiscore](https://github.com/Lesmiscore)
* [twitter] Fix video in quoted tweets
* [veoh] Improve extractor by [foghawk](https://github.com/foghawk)
* [vk] Capture `clip` URLs
* [vk] Fix VKUserVideosIE by [Ashish0804](https://github.com/Ashish0804)
* [vk] Improve `_VALID_URL` by [k3ns1n](https://github.com/k3ns1n)
* [VrtNU] Handle empty title by [pgaig](https://github.com/pgaig)
* [XVideos] Check HLS formats by [MinePlayersPE](https://github.com/MinePlayersPE)
* [yahoo:gyao] Improved playlist handling by [hyano](https://github.com/hyano)
* [youtube:tab] Extract more playlist metadata by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [youtube:tab] Raise error on tab redirect by [krichbanana](https://github.com/krichbanana), [coletdjnz](https://github.com/coletdjnz)
* [youtube] Update Innertube clients by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Detect live-stream embeds
* [youtube] Do not return `upload_date` for playlists
* [youtube] Extract channel subscriber count by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Make invalid storyboard URL non-fatal
* [youtube] Enforce UTC, update innertube clients and tests by [coletdjnz](https://github.com/coletdjnz)
* [zdf] Add chapter extraction by [iw0nderhow](https://github.com/iw0nderhow)
* [zee5] Add geo-bypass


### 2021.12.27

* Avoid recursion error when re-extracting info
* [ffmpeg] Fix position of `--ppa`
* [aria2c] Don't show progress when `--no-progress`
* [cookies] Support other keyrings by [mbway](https://github.com/mbway)
* [EmbedThumbnail] Prefer AtomicParsley over ffmpeg if available
* [generic] Fix HTTP KVS Player by [git-anony-mouse](https://github.com/git-anony-mouse)
* [ThumbnailsConvertor] Fix for when there are no thumbnails
* [docs] Add examples for using `TYPES:` in `-P`/`-o`
* [PixivSketch] Add extractors by [nao20010128nao](https://github.com/nao20010128nao)
* [tiktok] Add music, sticker and tag IEs by [MinePlayersPE](https://github.com/MinePlayersPE)
* [BiliIntl] Fix extractor by [MinePlayersPE](https://github.com/MinePlayersPE)
* [CBC] Fix URL regex
* [tiktok] Fix `extractor_key` used in archive
* [youtube] **End `live-from-start` properly when stream ends with 403**
* [Zee5] Fix VALID_URL for tv-shows by [Ashish0804](https://github.com/Ashish0804)

### 2021.12.25

* [dash,youtube] **Download live from start to end** by [nao20010128nao](https://github.com/nao20010128nao), [pukkandan](https://github.com/pukkandan)
    * Add option `--live-from-start` to enable downloading live videos from start
    * Add key `is_from_start` in formats to identify formats (of live videos) that downloads from start
    * [dash] Create protocol `http_dash_segments_generator` that allows a function to be passed instead of fragments
    * [fragment] Allow multiple live dash formats to download simultaneously
    * [youtube] Implement fragment re-fetching for the live dash formats
    * [youtube] Re-extract dash manifest every 5 hours (manifest expires in 6hrs)
    * [postprocessor/ffmpeg] Add `FFmpegFixupDuplicateMoovPP` to fixup duplicated moov atoms
    * Known issues:
        * Ctrl+C doesn't work on Windows when downloading multiple formats
        * If video becomes private, download hangs
* [SponsorBlock] Add `Filler` and `Highlight` categories by [nihil-admirari](https://github.com/nihil-admirari), [pukkandan](https://github.com/pukkandan)
    * Change `--sponsorblock-cut all` to `--sponsorblock-cut default` if you do not want filler sections to be removed
* Add field `webpage_url_domain`
* Add interactive format selection with `-f -`
* Add option `--file-access-retries` by [ehoogeveen-medweb](https://github.com/ehoogeveen-medweb)
* [outtmpl] Add alternate forms `S`, `D` and improve `id` detection
* [outtmpl] Add operator `&` for replacement text by [PilzAdam](https://github.com/PilzAdam)
* [EmbedSubtitle] Disable duration check temporarily
* [extractor] Add `_search_nuxt_data` by [nao20010128nao](https://github.com/nao20010128nao)
* [extractor] Ignore errors in comment extraction when `-i` is given
* [extractor] Standardize `_live_title`
* [FormatSort] Prevent incorrect deprecation warning
* [generic] Extract m3u8 formats from JSON-LD
* [postprocessor/ffmpeg] Always add `faststart`
* [utils] Fix parsing `YYYYMMDD` dates in Nov/Dec by [wlritchi](https://github.com/wlritchi)
* [utils] Improve `parse_count`
* [utils] Update `std_headers` by [kikuyan](https://github.com/kikuyan), [fstirlitz](https://github.com/fstirlitz)
* [lazy_extractors] Fix for search IEs
* [extractor] Support default implicit graph in JSON-LD by [zmousm](https://github.com/zmousm)
* Allow `--no-write-thumbnail` to override `--write-all-thumbnail`
* Fix `--throttled-rate`
* Fix control characters being printed to `--console-title`
* Fix PostProcessor hooks not registered for some PPs
* Pre-process when using `--flat-playlist`
* Remove known invalid thumbnails from `info_dict`
* Add warning when using `-f best`
* Use `parse_duration` for `--wait-for-video` and some minor fix
* [test/download] Add more fields
* [test/download] Ignore field `webpage_url_domain` by [std-move](https://github.com/std-move)
* [compat] Suppress errors in enabling VT mode
* [docs] Improve manpage format by [iw0nderhow](https://github.com/iw0nderhow), [pukkandan](https://github.com/pukkandan)
* [docs,cleanup] Minor fixes and cleanup
* [cleanup] Fix some typos by [unit193](https://github.com/unit193)
* [ABC:iview] Add show extractor by [pabs3](https://github.com/pabs3)
* [dropout] Add extractor by [TwoThousandHedgehogs](https://github.com/TwoThousandHedgehogs), [pukkandan](https://github.com/pukkandan)
* [GameJolt] Add extractors by [MinePlayersPE](https://github.com/MinePlayersPE)
* [gofile] Add extractor by [Jertzukka](https://github.com/Jertzukka), [Ashish0804](https://github.com/Ashish0804)
* [hse] Add extractors by [cypheron](https://github.com/cypheron), [pukkandan](https://github.com/pukkandan)
* [NateTV] Add NateIE and NateProgramIE by [Ashish0804](https://github.com/Ashish0804), [Hyeeji](https://github.com/Hyeeji)
* [OpenCast] Add extractors by [bwildenhain](https://github.com/bwildenhain), [C0D3D3V](https://github.com/C0D3D3V)
* [rtve] Add `RTVEAudioIE` by [kebianizao](https://github.com/kebianizao)
* [Rutube] Add RutubeChannelIE by [Ashish0804](https://github.com/Ashish0804)
* [skeb] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [soundcloud] Add related tracks extractor by [Lapin0t](https://github.com/Lapin0t)
* [toggo] Add extractor by [nyuszika7h](https://github.com/nyuszika7h)
* [TrueID] Add extractor by [MinePlayersPE](https://github.com/MinePlayersPE)
* [audiomack] Update album and song VALID_URL by [abdullah-if](https://github.com/abdullah-if), [dirkf](https://github.com/dirkf)
* [CBC Gem] Extract 1080p formats by [DavidSkrundz](https://github.com/DavidSkrundz)
* [ceskatelevize] Fetch iframe from nextJS data by [mkubecek](https://github.com/mkubecek)
* [crackle] Look for non-DRM formats by [raleeper](https://github.com/raleeper)
* [dplay] Temporary fix for `discoveryplus.com/it`
* [DiscoveryPlusShowBaseIE] yield actual video id by [Ashish0804](https://github.com/Ashish0804)
* [Facebook] Handle redirect URLs
* [fujitv] Extract 1080p from `tv_android` m3u8 by [YuenSzeHong](https://github.com/YuenSzeHong)
* [gronkh] Support new URL pattern by [Sematre](https://github.com/Sematre)
* [instagram] Expand valid URL by [u-spec-png](https://github.com/u-spec-png)
* [Instagram] Try bypassing login wall with embed page by [MinePlayersPE](https://github.com/MinePlayersPE)
* [Jamendo] Fix use of `_VALID_URL_RE` by [jaller94](https://github.com/jaller94)
* [LBRY] Support livestreams by [Ashish0804](https://github.com/Ashish0804), [pukkandan](https://github.com/pukkandan)
* [NJPWWorld] Extract formats from m3u8 by [aarubui](https://github.com/aarubui)
* [NovaEmbed] update player regex by [std-move](https://github.com/std-move)
* [npr] Make SMIL extraction non-fatal by [r5d](https://github.com/r5d)
* [ntvcojp] Extract NUXT data by [nao20010128nao](https://github.com/nao20010128nao)
* [ok.ru] add mobile fallback by [nao20010128nao](https://github.com/nao20010128nao)
* [olympics] Add uploader and cleanup by [u-spec-png](https://github.com/u-spec-png)
* [ondemandkorea] Update `jw_config` regex by [julien-hadleyjack](https://github.com/julien-hadleyjack)
* [PlutoTV] Expand `_VALID_URL`
* [RaiNews] Fix extractor by [nixxo](https://github.com/nixxo)
* [RCTIPlusSeries] Lazy extraction and video type selection by [MinePlayersPE](https://github.com/MinePlayersPE)
* [redtube] Handle formats delivered inside a JSON by [dirkf](https://github.com/dirkf), [nixxo](https://github.com/nixxo)
* [SonyLiv] Add OTP login support by [Ashish0804](https://github.com/Ashish0804)
* [Steam] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [TikTok] Pass cookies to mobile API by [MinePlayersPE](https://github.com/MinePlayersPE)
* [trovo] Fix inheritance of `TrovoChannelBaseIE`
* [TVer] Extract better thumbnails by [YuenSzeHong](https://github.com/YuenSzeHong)
* [vimeo] Extract chapters
* [web.archive:youtube] Improve metadata extraction by [coletdjnz](https://github.com/coletdjnz)
* [youtube:comments] Add more options for limiting number of comments extracted by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Extract more metadata from feeds/channels/playlists by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Extract video thumbnails from playlist by [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [youtube:tab] Ignore query when redirecting channel to playlist and cleanup of related code
* [youtube] Fix `ytsearchdate`
* [zdf] Support videos with different ptmd location by [iw0nderhow](https://github.com/iw0nderhow)
* [zee5] Support /episodes in URL


### 2021.12.01

* **Add option `--wait-for-video` to wait for scheduled streams**
* Add option `--break-per-input` to apply --break-on... to each input URL
* Add option `--embed-info-json` to embed info.json in mkv
* Add compat-option `embed-metadata`
* Allow using a custom format selector through API
* [AES] Add ECB mode by [nao20010128nao](https://github.com/nao20010128nao)
* [build] Fix MacOS Build
* [build] Save Git HEAD at release alongside version info
* [build] Use `workflow_dispatch` for release
* [downloader/ffmpeg] Fix for direct videos inside mpd manifests
* [downloader] Add colors to download progress
* [EmbedSubtitles] Slightly relax duration check and related cleanup
* [ExtractAudio] Fix conversion to `wav` and `vorbis`
* [ExtractAudio] Support `alac`
* [extractor] Extract `average_rating` from JSON-LD
* [FixupM3u8] Fixup MPEG-TS in MP4 container
* [generic] Support mpd manifests without extension by [shirt](https://github.com/shirt-dev)
* [hls] Better FairPlay DRM detection by [nyuszika7h](https://github.com/nyuszika7h)
* [jsinterp] Fix splice to handle float (for youtube js player f1ca6900)
* [utils] Allow alignment in `render_table` and add tests
* [utils] Fix `PagedList`
* [utils] Fix error when copying `LazyList`
* Clarify video/audio-only formats in -F
* Ensure directory exists when checking formats
* Ensure path for link files exists by [Zirro](https://github.com/Zirro)
* Ensure same config file is not loaded multiple times
* Fix `postprocessor_hooks`
* Fix `--break-on-archive` when pre-checking
* Fix `--check-formats` for `mhtml`
* Fix `--load-info-json` of playlists with failed entries
* Fix `--trim-filename` when filename has `.`
* Fix bug in parsing `--add-header`
* Fix error in `report_unplayable_conflict` by [shirt](https://github.com/shirt-dev)
* Fix writing playlist infojson with `--no-clean-infojson`
* Validate --get-bypass-country
* [blogger] Add extractor by [pabs3](https://github.com/pabs3)
* [breitbart] Add extractor by [Grabien](https://github.com/Grabien)
* [CableAV] Add extractor by [j54vc1bk](https://github.com/j54vc1bk)
* [CanalAlpha] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [CozyTV] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [CPTwentyFour] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [DiscoveryPlus] Add `DiscoveryPlusItalyShowIE` by [Ashish0804](https://github.com/Ashish0804)
* [ESPNCricInfo] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [LinkedIn] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [mixch] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [nebula] Add `NebulaCollectionIE` and rewrite extractor by [hheimbuerger](https://github.com/hheimbuerger)
* [OneFootball] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [peer.tv] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [radiozet] Add extractor by [0xA7404A](https://github.com/0xA7404A) (Aurora)
* [redgifs] Add extractor by [chio0hai](https://github.com/chio0hai)
* [RedGifs] Add Search and User extractors by [Deer-Spangle](https://github.com/Deer-Spangle)
* [rtrfm] Add extractor by [pabs3](https://github.com/pabs3)
* [Streamff] Add extractor by [cntrl-s](https://github.com/cntrl-s)
* [Stripchat] Add extractor by [zulaport](https://github.com/zulaport)
* [Aljazeera] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [AmazonStoreIE] Fix regex to not match vdp urls by [Ashish0804](https://github.com/Ashish0804)
* [ARDBetaMediathek] Handle new URLs
* [bbc] Get all available formats by [nyuszika7h](https://github.com/nyuszika7h)
* [Bilibili] Fix title extraction by [u-spec-png](https://github.com/u-spec-png)
* [CBC Gem] Fix for shows that don't have all seasons by [makeworld-the-better-one](https://github.com/makeworld-the-better-one)
* [curiositystream] Add more metadata
* [CuriosityStream] Fix series
* [DiscoveryPlus] Rewrite extractors by [Ashish0804](https://github.com/Ashish0804), [pukkandan](https://github.com/pukkandan)
* [HotStar] Set language field from tags by [Ashish0804](https://github.com/Ashish0804)
* [instagram, cleanup] Refactor extractors
* [Instagram] Display more login errors by [MinePlayersPE](https://github.com/MinePlayersPE)
* [itv] Fix extractor by [staubichsauger](https://github.com/staubichsauger), [pukkandan](https://github.com/pukkandan)
* [mediaklikk] Expand valid URL
* [MTV] Improve mgid extraction by [Sipherdrakon](https://github.com/Sipherdrakon), [kikuyan](https://github.com/kikuyan)
* [nexx] Better error message for unsupported format
* [NovaEmbed] Fix extractor by [pukkandan](https://github.com/pukkandan), [std-move](https://github.com/std-move)
* [PatreonUser] Do not capture RSS URLs
* [Reddit] Add support for 1080p videos by [xenova](https://github.com/xenova)
* [RoosterTeethSeries] Fix for multiple pages by [MinePlayersPE](https://github.com/MinePlayersPE)
* [sbs] Fix for movies and livestreams
* [Senate.gov] Add SenateGovIE and fix SenateISVPIE by [Grabien](https://github.com/Grabien), [pukkandan](https://github.com/pukkandan)
* [soundcloud:search] Fix pagination
* [tiktok:user] Set `webpage_url` correctly
* [Tokentube] Fix description by [u-spec-png](https://github.com/u-spec-png)
* [trovo] Fix extractor by [nyuszika7h](https://github.com/nyuszika7h)
* [tv2] Expand valid URL
* [Tvplayhome] Fix extractor by [pukkandan](https://github.com/pukkandan), [18928172992817182](https://github.com/18928172992817182)
* [Twitch:vod] Add chapters by [mpeter50](https://github.com/mpeter50)
* [twitch:vod] Extract live status by [DEvmIb](https://github.com/DEvmIb)
* [VidLii] Add 720p support by [mrpapersonic](https://github.com/mrpapersonic)
* [vimeo] Add fallback for config URL
* [vimeo] Sort http formats higher
* [WDR] Expand valid URL
* [willow] Add extractor by [aarubui](https://github.com/aarubui)
* [xvideos] Detect embed URLs by [4a1e2y5](https://github.com/4a1e2y5)
* [xvideos] Fix extractor by [Yakabuff](https://github.com/Yakabuff)
* [youtube, cleanup] Reorganize Tab and Search extractor inheritances
* [youtube:search_url] Add playlist/channel support
* [youtube] Add `default` player client by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Add storyboard formats
* [youtube] Decrypt n-sig for URLs with `ratebypass`
* [youtube] Minor improvement to format sorting
* [cleanup] Add deprecation warnings
* [cleanup] Refactor `JSInterpreter._seperate`
* [Cleanup] Remove some unnecessary groups in regexes by [Ashish0804](https://github.com/Ashish0804)
* [cleanup] Misc cleanup


### 2021.11.10.1

* Temporarily disable MacOS Build

### 2021.11.10

* [youtube] **Fix throttling by decrypting n-sig**
* Merging extractors from [haruhi-dl](https://git.sakamoto.pl/laudom/haruhi-dl) by [selfisekai](https://github.com/selfisekai)
    * [extractor] Add `_search_nextjs_data`
    * [tvp] Fix extractors
    * [tvp] Add TVPStreamIE
    * [wppilot] Add extractors
    * [polskieradio] Add extractors
    * [radiokapital] Add extractors
    * [polsatgo] Add extractor by [selfisekai](https://github.com/selfisekai), [sdomi](https://github.com/sdomi)
* Separate `--check-all-formats` from `--check-formats`
* Approximate filesize from bitrate
* Don't create console in `windows_enable_vt_mode`
* Fix bug in `--load-infojson` of playlists
* [minicurses] Add colors to `-F` and standardize color-printing code
* [outtmpl] Add type `link` for internet shortcut files
* [outtmpl] Add alternate forms for `q` and `j`
* [outtmpl] Do not traverse `None`
* [fragment] Fix progress display in fragmented downloads
* [downloader/ffmpeg] Fix vtt download with ffmpeg
* [ffmpeg] Detect presence of setts and libavformat version
* [ExtractAudio] Rescale `--audio-quality` correctly by [CrypticSignal](https://github.com/CrypticSignal), [pukkandan](https://github.com/pukkandan)
* [ExtractAudio] Use `libfdk_aac` if available by [CrypticSignal](https://github.com/CrypticSignal)
* [FormatSort] `eac3` is better than `ac3`
* [FormatSort] Fix some fields' defaults
* [generic] Detect more json_ld
* [generic] parse jwplayer with only the json URL
* [extractor] Add keyword automatically to SearchIE descriptions
* [extractor] Fix some errors being converted to `ExtractorError`
* [utils] Add `join_nonempty`
* [utils] Add `jwt_decode_hs256` by [Ashish0804](https://github.com/Ashish0804)
* [utils] Create `DownloadCancelled` exception
* [utils] Parse `vp09` as vp9
* [utils] Sanitize URL when determining protocol
* [test/download] Fallback test to `bv`
* [docs] Minor documentation improvements
* [cleanup] Improvements to error and debug messages
* [cleanup] Minor fixes and cleanup
* [3speak] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [AmazonStore] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [Gab] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [mediaset] Add playlist support by [nixxo](https://github.com/nixxo)
* [MLSScoccer] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [N1] Add support for nova.rs by [u-spec-png](https://github.com/u-spec-png)
* [PlanetMarathi] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [RaiplayRadio] Add extractors by [frafra](https://github.com/frafra)
* [roosterteeth] Add series extractor
* [sky] Add `SkyNewsStoryIE` by [ajj8](https://github.com/ajj8)
* [youtube] Fix sorting for some videos
* [youtube] Populate `thumbnail` with the best "known" thumbnail
* [youtube] Refactor itag processing
* [youtube] Remove unnecessary no-playlist warning
* [youtube:tab] Add Invidious list for playlists/channels by [rhendric](https://github.com/rhendric)
* [Bilibili:comments] Fix infinite loop by [u-spec-png](https://github.com/u-spec-png)
* [ceskatelevize] Fix extractor by [flashdagger](https://github.com/flashdagger)
* [Coub] Fix media format identification by [wlritchi](https://github.com/wlritchi)
* [crunchyroll] Add extractor-args `language` and `hardsub`
* [DiscoveryPlus] Allow language codes in URL
* [imdb] Fix thumbnail by [ozburo](https://github.com/ozburo)
* [instagram] Add IOS URL support by [u-spec-png](https://github.com/u-spec-png)
* [instagram] Improve login code by [u-spec-png](https://github.com/u-spec-png)
* [Instagram] Improve metadata extraction by [u-spec-png](https://github.com/u-spec-png)
* [iPrima] Fix extractor by [stanoarn](https://github.com/stanoarn)
* [itv] Add support for ITV News by [ajj8](https://github.com/ajj8)
* [la7] Fix extractor by [nixxo](https://github.com/nixxo)
* [linkedin] Don't login multiple times
* [mtv] Fix some videos by [Sipherdrakon](https://github.com/Sipherdrakon)
* [Newgrounds] Fix description by [u-spec-png](https://github.com/u-spec-png)
* [Nrk] Minor fixes by [fractalf](https://github.com/fractalf)
* [Olympics] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [piksel] Fix sorting
* [twitter] Do not sort by codec
* [viewlift] Add cookie-based login and series support by [Ashish0804](https://github.com/Ashish0804), [pukkandan](https://github.com/pukkandan)
* [vimeo] Detect source extension and misc cleanup by [flashdagger](https://github.com/flashdagger)
* [vimeo] Fix ondemand videos and direct URLs with hash
* [vk] Fix login and add subtitles by [kaz-us](https://github.com/kaz-us)
* [VLive] Add upload_date and thumbnail by [Ashish0804](https://github.com/Ashish0804)
* [VRT] Fix login by [pgaig](https://github.com/pgaig)
* [Vupload] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [wakanim] Add support for MPD manifests by [nyuszika7h](https://github.com/nyuszika7h)
* [wakanim] Detect geo-restriction by [nyuszika7h](https://github.com/nyuszika7h)
* [ZenYandex] Fix extractor by [u-spec-png](https://github.com/u-spec-png)


### 2021.10.22

* [build] Improvements
    * Build standalone MacOS packages by [smplayer-dev](https://github.com/smplayer-dev)
    * Release windows exe built with `py2exe`
    * Enable lazy-extractors in releases
        * Set env var `YTDLP_NO_LAZY_EXTRACTORS` to forcefully disable this (experimental)
    * Clean up error reporting in update
    * Refactor `pyinst.py`, misc cleanup and improve docs
* [docs] Migrate issues to use forms by [Ashish0804](https://github.com/Ashish0804)
* [downloader] **Fix slow progress hooks**
    * This was causing HLS/DASH downloads to be extremely slow in some situations
* [downloader/ffmpeg] Improve simultaneous download and merge
* [EmbedMetadata] Allow overwriting all default metadata with `meta_default` key
* [ModifyChapters] Add ability for `--remove-chapters` to remove sections by timestamp
* [utils] Allow duration strings in `--match-filter`
* Add HDR information to formats
* Add negative option `--no-batch-file` by [Zirro](https://github.com/Zirro)
* Calculate more fields for merged formats
* Do not verify thumbnail URLs unless `--check-formats` is specified
* Don't create console for subprocesses on Windows
* Fix `--restrict-filename` when used with default template
* Fix `check_formats` output being written to stdout when `-qv`
* Fix bug in storyboards
* Fix conflict b/w id and ext in format selection
* Fix verbose head not showing custom configs
* Load archive only after printing verbose head
* Make `duration_string` and `resolution` available in --match-filter
* Re-implement deprecated option `--id`
* Reduce default `--socket-timeout`
* Write verbose header to logger
* [outtmpl] Fix bug in expanding environment variables
* [cookies] Local State should be opened as utf-8
* [extractor,utils] Detect more codecs/mimetypes
* [extractor] Detect `EXT-X-KEY` Apple FairPlay
* [utils] Use `importlib` to load plugins by [sulyi](https://github.com/sulyi)
* [http] Retry on socket timeout and show the last encountered error
* [fragment] Print error message when skipping fragment
* [aria2c] Fix `--skip-unavailable-fragment`
* [SponsorBlock] Obey `extractor-retries` and `sleep-requests`
* [Merger] Do not add `aac_adtstoasc` to non-hls audio
* [ModifyChapters] Do not mutate original chapters by [nihil-admirari](https://github.com/nihil-admirari)
* [devscripts/run_tests] Use markers to filter tests by [sulyi](https://github.com/sulyi)
* [7plus] Add cookie based authentication by [nyuszika7h](https://github.com/nyuszika7h)
* [AdobePass] Fix RCN MSO by [jfogelman](https://github.com/jfogelman)
* [CBC] Fix Gem livestream by [makeworld-the-better-one](https://github.com/makeworld-the-better-one)
* [CBC] Support CBC Gem member content by [makeworld-the-better-one](https://github.com/makeworld-the-better-one)
* [crunchyroll] Add season to flat-playlist
* [crunchyroll] Add support for `beta.crunchyroll` URLs and fix series URLs with language code
* [EUScreen] Add Extractor by [Ashish0804](https://github.com/Ashish0804)
* [Gronkh] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [hidive] Fix typo
* [Hotstar] Mention Dynamic Range in `format_id` by [Ashish0804](https://github.com/Ashish0804)
* [Hotstar] Raise appropriate error for DRM
* [instagram] Add login by [u-spec-png](https://github.com/u-spec-png)
* [instagram] Show appropriate error when login is needed
* [microsoftstream] Add extractor by [damianoamatruda](https://github.com/damianoamatruda), [nixklai](https://github.com/nixklai)
* [on24] Add extractor by [damianoamatruda](https://github.com/damianoamatruda)
* [patreon] Fix vimeo player regex by [zenerdi0de](https://github.com/zenerdi0de)
* [SkyNewsAU] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [tagesschau] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [tbs] Add tbs live streams by [llacb47](https://github.com/llacb47)
* [tiktok] Fix typo and update tests
* [trovo] Support channel clips and VODs by [Ashish0804](https://github.com/Ashish0804)
* [Viafree] Add support for Finland by [18928172992817182](https://github.com/18928172992817182)
* [vimeo] Fix embedded `player.vimeo`
* [vlive:channel] Fix extraction by [kikuyan](https://github.com/kikuyan), [pukkandan](https://github.com/pukkandan)
* [youtube] Add auto-translated subtitles
* [youtube] Expose different formats with same itag
* [youtube:comments] Fix for new layout by [coletdjnz](https://github.com/coletdjnz)
* [cleanup] Cleanup bilibili code by [pukkandan](https://github.com/pukkandan), [u-spec-png](https://github.com/u-spec-png)
* [cleanup] Remove broken youtube login code
* [cleanup] Standardize timestamp formatting code
* [cleanup] Generalize `getcomments` implementation for extractors
* [cleanup] Simplify search extractors code
* [cleanup] misc


### 2021.10.10

* [downloader/ffmpeg] Fix bug in initializing `FFmpegPostProcessor`
* [minicurses] Fix when printing to file
* [downloader] Fix throttledratelimit
* [francetv] Fix extractor by [fstirlitz](https://github.com/fstirlitz), [sarnoud](https://github.com/sarnoud)
* [NovaPlay] Add extractor by [Bojidarist](https://github.com/Bojidarist)
* [ffmpeg] Revert "Set max probesize" - No longer needed
* [docs] Remove incorrect dependency on VC++10
* [build] Allow to release without changelog

### 2021.10.09

* Improved progress reporting
    * Separate `--console-title` and `--no-progress`
    * Add option `--progress` to show progress-bar even in quiet mode
    * Fix and refactor `minicurses` and use it for all progress reporting
    * Standardize use of terminal sequences and enable color support for windows 10
    * Add option `--progress-template` to customize progress-bar and console-title
    * Add postprocessor hooks and progress reporting
* [postprocessor] Add plugin support with option `--use-postprocessor`
* [extractor] Extract storyboards from SMIL manifests by [fstirlitz](https://github.com/fstirlitz)
* [outtmpl] Alternate form of format type `l` for `\n` delimited list
* [outtmpl] Format type `U` for unicode normalization
* [outtmpl] Allow empty output template to skip a type of file
* Merge webm formats into mkv if thumbnails are to be embedded
* [adobepass] Add RCN as MSO by [jfogelman](https://github.com/jfogelman)
* [ciscowebex] Add extractor by [damianoamatruda](https://github.com/damianoamatruda)
* [Gettr] Add extractor by [i6t](https://github.com/i6t)
* [GoPro] Add extractor by [i6t](https://github.com/i6t)
* [N1] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [Theta] Add video extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [Veo] Add extractor by [i6t](https://github.com/i6t)
* [Vupload] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [bbc] Extract better quality videos by [ajj8](https://github.com/ajj8)
* [Bilibili] Add subtitle converter by [u-spec-png](https://github.com/u-spec-png)
* [CBC] Cleanup tests by [makeworld-the-better-one](https://github.com/makeworld-the-better-one)
* [Douyin] Rewrite extractor by [MinePlayersPE](https://github.com/MinePlayersPE)
* [Funimation] Fix for /v/ urls by [pukkandan](https://github.com/pukkandan), [Jules-A](https://github.com/Jules-A)
* [Funimation] Sort formats according to the relevant extractor-args
* [Hidive] Fix duplicate and incorrect formats
* [HotStarSeries] Fix cookies by [Ashish0804](https://github.com/Ashish0804)
* [LinkedInLearning] Add subtitles by [Ashish0804](https://github.com/Ashish0804)
* [Mediaite] Relax valid url by [coletdjnz](https://github.com/coletdjnz)
* [Newgrounds] Add age_limit and fix duration by [u-spec-png](https://github.com/u-spec-png)
* [Newgrounds] Fix view count on songs by [u-spec-png](https://github.com/u-spec-png)
* [parliamentlive.tv] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [PolskieRadio] Fix extractors by [jakubadamw](https://github.com/jakubadamw), [u-spec-png](https://github.com/u-spec-png)
* [reddit] Add embedded url by [u-spec-png](https://github.com/u-spec-png)
* [reddit] Fix 429 by generating a random `reddit_session` by [AjaxGb](https://github.com/AjaxGb)
* [Rumble] Add RumbleChannelIE by [Ashish0804](https://github.com/Ashish0804)
* [soundcloud:playlist] Detect last page correctly
* [SovietsCloset] Add duration from m3u8 by [ChillingPepper](https://github.com/ChillingPepper)
* [Streamable] Add codecs by [u-spec-png](https://github.com/u-spec-png)
* [vidme] Remove extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [youtube:tab] Fallback to API when webpage fails to download by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix non-fatal errors in fetching player
* Fix `--flat-playlist` when neither IE nor id is known
* Fix `-f mp4` behaving differently from youtube-dl
* Workaround for bug in `ssl.SSLContext.load_default_certs`
* [aes] Improve performance slightly by [sulyi](https://github.com/sulyi)
* [cookies] Fix keyring fallback by [mbway](https://github.com/mbway)
* [embedsubtitle] Fix error when duration is unknown
* [ffmpeg] Fix error when subtitle file is missing
* [ffmpeg] Set max probesize to workaround AAC HLS stream issues by [shirt](https://github.com/shirt-dev)
* [FixupM3u8] Remove redundant run if merged is needed
* [hls] Fix decryption issues by [shirt](https://github.com/shirt-dev), [pukkandan](https://github.com/pukkandan)
* [http] Respect user-provided chunk size over extractor's
* [utils] Let traverse_obj accept functions as keys
* [docs] Add note about our custom ffmpeg builds
* [docs] Write embedding and contributing documentation by [pukkandan](https://github.com/pukkandan), [timethrow](https://github.com/timethrow)
* [update] Check for new version even if not updateable
* [build] Add more files to the tarball
* [build] Allow building with py2exe (and misc fixes)
* [build] Use pycryptodomex by [shirt](https://github.com/shirt-dev), [pukkandan](https://github.com/pukkandan)
* [cleanup] Some minor refactoring, improve docs and misc cleanup


### 2021.09.25

* Add new option `--netrc-location`
* [outtmpl] Allow alternate fields using `,`
* [outtmpl] Add format type `B` to treat the value as bytes, e.g. to limit the filename to a certain number of bytes
* Separate the options `--ignore-errors` and `--no-abort-on-error`
* Basic framework for simultaneous download of multiple formats by [nao20010128nao](https://github.com/nao20010128nao)
* [17live] Add 17.live extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [bilibili] Add BiliIntlIE and BiliIntlSeriesIE by [Ashish0804](https://github.com/Ashish0804)
* [CAM4] Add extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [Chingari] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [CGTN] Add extractor by [chao813](https://github.com/chao813)
* [damtomo] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [gotostage] Add extractor by [poschi3](https://github.com/poschi3)
* [Koo] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [Mediaite] Add Extractor by [Ashish0804](https://github.com/Ashish0804)
* [Mediaklikk] Add Extractor by [tmarki](https://github.com/tmarki), [mrx23dot](https://github.com/mrx23dot), [coletdjnz](https://github.com/coletdjnz)
* [MuseScore] Add Extractor by [Ashish0804](https://github.com/Ashish0804)
* [Newgrounds] Add NewgroundsUserIE and improve extractor by [u-spec-png](https://github.com/u-spec-png)
* [nzherald] Add NZHeraldIE by [coletdjnz](https://github.com/coletdjnz)
* [Olympics] Add replay extractor by [Ashish0804](https://github.com/Ashish0804)
* [Peertube] Add channel and playlist extractors by [u-spec-png](https://github.com/u-spec-png)
* [radlive] Add extractor by [nyuszika7h](https://github.com/nyuszika7h)
* [SovietsCloset] Add extractor by [ChillingPepper](https://github.com/ChillingPepper)
* [Streamanity] Add Extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [Theta] Add extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [Yandex] Add ZenYandexIE and ZenYandexChannelIE by [Ashish0804](https://github.com/Ashish0804)
* [9Now] handle episodes of series by [dalanmiller](https://github.com/dalanmiller)
* [AnimalPlanet] Fix extractor by [Sipherdrakon](https://github.com/Sipherdrakon)
* [Arte] Improve description extraction by [renalid](https://github.com/renalid)
* [atv.at] Use jwt for API by [NeroBurner](https://github.com/NeroBurner)
* [brightcove] Extract subtitles from manifests
* [CBC] Fix CBC Gem extractors by [makeworld-the-better-one](https://github.com/makeworld-the-better-one)
* [cbs] Report appropriate error for DRM
* [comedycentral] Support `collection-playlist` by [nixxo](https://github.com/nixxo)
* [DIYNetwork] Support new format by [Sipherdrakon](https://github.com/Sipherdrakon)
* [downloader/niconico] Pass custom headers by [nao20010128nao](https://github.com/nao20010128nao)
* [dw] Fix extractor
* [Fancode] Fix live streams by [zenerdi0de](https://github.com/zenerdi0de)
* [funimation] Fix for locations outside US by [Jules-A](https://github.com/Jules-A), [pukkandan](https://github.com/pukkandan)
* [globo] Fix GloboIE by [Ashish0804](https://github.com/Ashish0804)
* [HiDive] Fix extractor by [Ashish0804](https://github.com/Ashish0804)
* [Hotstar] Add referer for subs by [Ashish0804](https://github.com/Ashish0804)
* [itv] Fix extractor, add subtitles and thumbnails by [coletdjnz](https://github.com/coletdjnz), [sleaux-meaux](https://github.com/sleaux-meaux), [Vangelis66](https://github.com/Vangelis66)
* [lbry] Show error message from API response
* [Mxplayer] Use mobile API by [Ashish0804](https://github.com/Ashish0804)
* [NDR] Rewrite NDRIE by [Ashish0804](https://github.com/Ashish0804)
* [Nuvid] Fix extractor by [u-spec-png](https://github.com/u-spec-png)
* [Oreilly] Handle new web url by [MKSherbini](https://github.com/MKSherbini)
* [pbs] Fix subtitle extraction by [coletdjnz](https://github.com/coletdjnz), [gesa](https://github.com/gesa), [raphaeldore](https://github.com/raphaeldore)
* [peertube] Update instances by [u-spec-png](https://github.com/u-spec-png)
* [plutotv] Fix extractor for URLs with `/en`
* [reddit] Workaround for 429 by redirecting to old.reddit.com
* [redtube] Fix exts
* [soundcloud] Make playlist extraction lazy
* [soundcloud] Retry playlist pages on `502` error and update `_CLIENT_ID`
* [southpark] Fix SouthParkDE by [coletdjnz](https://github.com/coletdjnz)
* [SovietsCloset] Fix playlists for games with only named categories by [ConquerorDopy](https://github.com/ConquerorDopy)
* [SpankBang] Fix uploader by [f4pp3rk1ng](https://github.com/f4pp3rk1ng), [coletdjnz](https://github.com/coletdjnz)
* [tiktok] Use API to fetch higher quality video by [MinePlayersPE](https://github.com/MinePlayersPE), [llacb47](https://github.com/llacb47)
* [TikTokUser] Fix extractor using mobile API by [MinePlayersPE](https://github.com/MinePlayersPE), [llacb47](https://github.com/llacb47)
* [videa] Fix some extraction errors by [nyuszika7h](https://github.com/nyuszika7h)
* [VrtNU] Handle login errors by [llacb47](https://github.com/llacb47)
* [vrv] Don't raise error when thumbnails are missing
* [youtube] Cleanup authentication code by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix `--mark-watched` with `--cookies-from-browser`
* [youtube] Improvements to JS player extraction and add extractor-args to skip it by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Retry on 'Unknown Error' by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Return full URL instead of just ID
* [youtube] Warn when trying to download clips
* [zdf] Improve format sorting
* [zype] Extract subtitles from the m3u8 manifest by [fstirlitz](https://github.com/fstirlitz)
* Allow `--force-write-archive` to work with `--flat-playlist`
* Download subtitles in order of `--sub-langs`
* Allow `0` in `--playlist-items`
* Handle more playlist errors with `-i`
* Fix `--no-get-comments`
* Fix `extra_info` being reused across runs
* Fix compat options `no-direct-merge` and `playlist-index`
* Dump files should obey `--trim-filename` by [sulyi](https://github.com/sulyi)
* [aes] Add `aes_gcm_decrypt_and_verify` by [sulyi](https://github.com/sulyi), [pukkandan](https://github.com/pukkandan)
* [aria2c] Fix IV for some AES-128 streams by [shirt](https://github.com/shirt-dev)
* [compat] Don't ignore `HOME` (if set) on windows
* [cookies] Make browser names case insensitive
* [cookies] Print warning for cookie decoding error only once
* [extractor] Fix root-relative URLs in MPD by [DigitalDJ](https://github.com/DigitalDJ)
* [ffmpeg] Add `aac_adtstoasc` when merging if needed
* [fragment,aria2c] Generalize and refactor some code
* [fragment] Avoid repeated request for AES key
* [fragment] Fix range header when using `-N` and media sequence by [shirt](https://github.com/shirt-dev)
* [hls,aes] Fallback to native implementation for AES-CBC and detect `Cryptodome` in addition to `Crypto`
* [hls] Byterange + AES128 is supported by native downloader
* [ModifyChapters] Improve sponsor chapter merge algorithm by [nihil-admirari](https://github.com/nihil-admirari)
* [ModifyChapters] Minor fixes
* [WebVTT] Adjust parser to accommodate PBS subtitles
* [utils] Improve `extract_timezone` by [dirkf](https://github.com/dirkf)
* [options] Fix `--no-config` and refactor reading of config files
* [options] Strip spaces and ignore empty entries in list-like switches
* [test/cookies] Improve logging
* [build] Automate more of the release process by [animelover1984](https://github.com/animelover1984), [pukkandan](https://github.com/pukkandan)
* [build] Fix sha256 by [nihil-admirari](https://github.com/nihil-admirari)
* [build] Bring back brew taps by [nao20010128nao](https://github.com/nao20010128nao)
* [build] Provide `--onedir` zip for windows
* [cleanup,docs] Add deprecation warning in docs for some counter intuitive behaviour
* [cleanup] Fix line endings for `nebula.py` by [glenn-slayden](https://github.com/glenn-slayden)
* [cleanup] Improve `make clean-test` by [sulyi](https://github.com/sulyi)
* [cleanup] Misc


### 2021.09.02

* **Native SponsorBlock** implementation by [nihil-admirari](https://github.com/nihil-admirari), [pukkandan](https://github.com/pukkandan)
    * `--sponsorblock-remove CATS` removes specified chapters from file
    * `--sponsorblock-mark CATS` marks the specified sponsor sections as chapters
    * `--sponsorblock-chapter-title TMPL` to specify sponsor chapter template
    * `--sponsorblock-api URL` to use a different API
    * No re-encoding is done unless `--force-keyframes-at-cuts` is used
    * The fetched sponsor sections are written to the infojson
    * Deprecates: `--sponskrub`, `--no-sponskrub`, `--sponskrub-cut`, `--no-sponskrub-cut`, `--sponskrub-force`, `--no-sponskrub-force`, `--sponskrub-location`, `--sponskrub-args`
* Split `--embed-chapters` from `--embed-metadata` (it still implies the former by default)
* Add option `--remove-chapters` to remove arbitrary chapters by [nihil-admirari](https://github.com/nihil-admirari), [pukkandan](https://github.com/pukkandan)
* Add option `--force-keyframes-at-cuts` for more accurate cuts when removing and splitting chapters by [nihil-admirari](https://github.com/nihil-admirari)
* Let `--match-filter` reject entries early
    * Makes redundant: `--match-title`, `--reject-title`, `--min-views`, `--max-views`
* [lazy_extractor] Improvements (It now passes all tests)
    * Bugfix for when plugin directory doesn't exist by [kidonng](https://github.com/kidonng)
    * Create instance only after pre-checking archive
    * Import actual class if an attribute is accessed
    * Fix `suitable` and add flake8 test
* [downloader/ffmpeg] Experimental support for DASH manifests (including live)
    * Your ffmpeg must have [this patch](https://github.com/FFmpeg/FFmpeg/commit/3249c757aed678780e22e99a1a49f4672851bca9) applied for YouTube DASH to work
* [downloader/ffmpeg] Allow passing custom arguments before `-i`
* [BannedVideo] Add extractor by [smege1001](https://github.com/smege1001), [blackjack4494](https://github.com/blackjack4494), [pukkandan](https://github.com/pukkandan)
* [bilibili] Add category extractor by [animelover1984](https://github.com/animelover1984)
* [Epicon] Add extractors by [Ashish0804](https://github.com/Ashish0804)
* [filmmodu] Add extractor by [mzbaulhaque](https://github.com/mzbaulhaque)
* [GabTV] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [Hungama] Fix `HungamaSongIE` and add `HungamaAlbumPlaylistIE` by [Ashish0804](https://github.com/Ashish0804)
* [ManotoTV] Add new extractors by [tandy1000](https://github.com/tandy1000)
* [Niconico] Add Search extractors by [animelover1984](https://github.com/animelover1984), [pukkandan](https://github.com/pukkandan)
* [Patreon] Add `PatreonUserIE` by [zenerdi0de](https://github.com/zenerdi0de)
* [peloton] Add extractor by [IONECarter](https://github.com/IONECarter), [capntrips](https://github.com/capntrips), [pukkandan](https://github.com/pukkandan)
* [ProjectVeritas] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [radiko] Add extractors by [nao20010128nao](https://github.com/nao20010128nao)
* [StarTV] Add extractor for `startv.com.tr` by [mrfade](https://github.com/mrfade), [coletdjnz](https://github.com/coletdjnz)
* [tiktok] Add `TikTokUserIE` by [Ashish0804](https://github.com/Ashish0804), [pukkandan](https://github.com/pukkandan)
* [Tokentube] Add extractor by [u-spec-png](https://github.com/u-spec-png)
* [TV2Hu] Fix `TV2HuIE` and add `TV2HuSeriesIE` by [Ashish0804](https://github.com/Ashish0804)
* [voicy] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [adobepass] Fix Verizon SAML login by [nyuszika7h](https://github.com/nyuszika7h), [ParadoxGBB](https://github.com/ParadoxGBB)
* [afreecatv] Fix adult VODs by [wlritchi](https://github.com/wlritchi)
* [afreecatv] Tolerate failure to parse date string by [wlritchi](https://github.com/wlritchi)
* [aljazeera] Fix extractor by [MinePlayersPE](https://github.com/MinePlayersPE)
* [ATV.at] Fix extractor for ATV.at by [NeroBurner](https://github.com/NeroBurner), [coletdjnz](https://github.com/coletdjnz)
* [bitchute] Fix test by [mahanstreamer](https://github.com/mahanstreamer)
* [camtube] Remove obsolete extractor by [alerikaisattera](https://github.com/alerikaisattera)
* [CDA] Add more formats by [u-spec-png](https://github.com/u-spec-png)
* [eroprofile] Fix page skipping in albums by [jhwgh1968](https://github.com/jhwgh1968)
* [facebook] Fix format sorting
* [facebook] Fix metadata extraction by [kikuyan](https://github.com/kikuyan)
* [facebook] Update onion URL by [Derkades](https://github.com/Derkades)
* [HearThisAtIE] Fix extractor by [Ashish0804](https://github.com/Ashish0804)
* [instagram] Add referrer to prevent throttling by [u-spec-png](https://github.com/u-spec-png), [kikuyan](https://github.com/kikuyan)
* [iwara.tv] Extract more metadata by [BunnyHelp](https://github.com/BunnyHelp)
* [iwara] Add thumbnail by [i6t](https://github.com/i6t)
* [kakao] Fix extractor
* [mediaset] Fix extraction for some videos by [nyuszika7h](https://github.com/nyuszika7h)
* [Motherless] Fix extractor by [coletdjnz](https://github.com/coletdjnz)
* [Nova] fix extractor by [std-move](https://github.com/std-move)
* [ParamountPlus] Fix geo verification by [shirt](https://github.com/shirt-dev)
* [peertube] handle new video URL format by [Chocobozzz](https://github.com/Chocobozzz)
* [pornhub] Separate and fix playlist extractor by [mzbaulhaque](https://github.com/mzbaulhaque)
* [reddit] Fix for quarantined subreddits by [ouwou](https://github.com/ouwou)
* [ShemarooMe] Fix extractor by [Ashish0804](https://github.com/Ashish0804)
* [soundcloud] Refetch `client_id` on 403
* [tiktok] Fix metadata extraction
* [TV2] Fix extractor by [Ashish0804](https://github.com/Ashish0804)
* [tv5mondeplus] Fix extractor by [korli](https://github.com/korli)
* [VH1,TVLand] Fix extractors by [Sipherdrakon](https://github.com/Sipherdrakon)
* [Viafree] Fix extractor and extract subtitles by [coletdjnz](https://github.com/coletdjnz)
* [XHamster] Extract `uploader_id` by [octotherp](https://github.com/octotherp)
* [youtube] Add `shorts` to `_VALID_URL`
* [youtube] Add av01 itags to known formats list by [blackjack4494](https://github.com/blackjack4494)
* [youtube] Extract error messages from HTTPError response by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix subtitle names
* [youtube] Prefer audio stream that YouTube considers default
* [youtube] Remove annotations and deprecate `--write-annotations` by [coletdjnz](https://github.com/coletdjnz)
* [Zee5] Fix extractor and add subtitles by [Ashish0804](https://github.com/Ashish0804)
* [aria2c] Obey `--rate-limit`
* [EmbedSubtitle] Continue even if some files are missing
* [extractor] Better error message for DRM
* [extractor] Common function `_match_valid_url`
* [extractor] Show video id in error messages if possible
* [FormatSort] Remove priority of `lang`
* [options] Add `_set_from_options_callback`
* [SubtitleConvertor] Fix bug during subtitle conversion
* [utils] Add `parse_qs`
* [webvtt] Fix timestamp overflow adjustment by [fstirlitz](https://github.com/fstirlitz)
* Bugfix for `--replace-in-metadata`
* Don't try to merge with final extension
* Fix `--force-overwrites` when using `-k`
* Fix `--no-prefer-free-formats` by [CeruleanSky](https://github.com/CeruleanSky)
* Fix `-F` for extractors that directly return url
* Fix `-J` when there are failed videos
* Fix `extra_info` being reused across runs
* Fix `playlist_index` not obeying `playlist_start` and add tests
* Fix resuming of single formats when using `--no-part`
* Revert erroneous use of the `Content-Length` header by [fstirlitz](https://github.com/fstirlitz)
* Use `os.replace` where applicable by; paulwrubel
* [build] Add homebrew taps `yt-dlp/taps/yt-dlp` by [nao20010128nao](https://github.com/nao20010128nao)
* [build] Fix bug in making `yt-dlp.tar.gz`
* [docs] Fix some typos by [pukkandan](https://github.com/pukkandan), [zootedb0t](https://github.com/zootedb0t)
* [cleanup] Replace improper use of tab in trovo by [glenn-slayden](https://github.com/glenn-slayden)


### 2021.08.10

* Add option `--replace-in-metadata`
* Add option `--no-simulate` to not simulate even when `--print` or `--list...` are used - Deprecates `--print-json`
* Allow entire infodict to be printed using `%()s` - makes `--dump-json` redundant
* Allow multiple `--exec` and `--exec-before-download`
* Add regex to `--match-filter`
* Add all format filtering operators also to `--match-filter` by [max-te](https://github.com/max-te)
* Add compat-option `no-keep-subs`
* [adobepass] Add MSO Cablevision by [Jessecar96](https://github.com/Jessecar96)
* [BandCamp] Add BandcampMusicIE by [Ashish0804](https://github.com/Ashish0804)
* [blackboardcollaborate] Add new extractor by [mzbaulhaque](https://github.com/mzbaulhaque)
* [eroprofile] Add album downloader by [jhwgh1968](https://github.com/jhwgh1968)
* [mirrativ] Add extractors by [nao20010128nao](https://github.com/nao20010128nao)
* [openrec] Add extractors by [nao20010128nao](https://github.com/nao20010128nao)
* [nbcolympics:stream] Fix extractor by [nchilada](https://github.com/nchilada), [pukkandan](https://github.com/pukkandan)
* [nbcolympics] Update extractor for 2020 olympics by [wesnm](https://github.com/wesnm)
* [paramountplus] Separate extractor and fix some titles by [shirt](https://github.com/shirt-dev), [pukkandan](https://github.com/pukkandan)
* [RCTIPlus] Support events and TV by [MinePlayersPE](https://github.com/MinePlayersPE)
* [Newgrounds] Improve extractor and fix playlist by [u-spec-png](https://github.com/u-spec-png)
* [aenetworks] Update `_THEPLATFORM_KEY` and `_THEPLATFORM_SECRET` by [wesnm](https://github.com/wesnm)
* [crunchyroll] Fix thumbnail by [funniray](https://github.com/funniray)
* [HotStar] Use API for metadata and extract subtitles by [Ashish0804](https://github.com/Ashish0804)
* [instagram] Fix comments extraction by [u-spec-png](https://github.com/u-spec-png)
* [peertube] Fix videos without description by [u-spec-png](https://github.com/u-spec-png)
* [twitch:clips] Extract `display_id` by [dirkf](https://github.com/dirkf)
* [viki] Print error message from API request
* [Vine] Remove invalid formats by [u-spec-png](https://github.com/u-spec-png)
* [VrtNU] Fix XSRF token by [pgaig](https://github.com/pgaig)
* [vrv] Fix thumbnail extraction by [funniray](https://github.com/funniray)
* [youtube] Add extractor-arg `include-live-dash` to show live dash formats
* [youtube] Improve signature function detection by [PSlava](https://github.com/PSlava)
* [youtube] Raise appropriate error when API pages can't be downloaded
* Ensure `_write_ytdl_file` closes file handle on error
* Fix `--compat-options filename` by [stdedos](https://github.com/stdedos)
* Fix issues with infodict sanitization
* Fix resuming when using `--no-part`
* Fix wrong extension for intermediate files
* Handle `BrokenPipeError` by [kikuyan](https://github.com/kikuyan)
* Show libraries present in verbose head
* [extractor] Detect `sttp` as subtitles in MPD by [fstirlitz](https://github.com/fstirlitz)
* [extractor] Reset non-repeating warnings per video
* [ffmpeg] Fix streaming `mp4` to `stdout`
* [ffpmeg] Allow `--ffmpeg-location` to be a file with different name
* [utils] Fix `InAdvancePagedList.__getitem__`
* [utils] Fix `traverse_obj` depth when `is_user_input`
* [webvtt] Merge daisy-chained duplicate cues by [fstirlitz](https://github.com/fstirlitz)
* [build] Use custom build of `pyinstaller` by [shirt](https://github.com/shirt-dev)
* [tests:download] Add batch testing for extractors (`test_YourExtractor_all`)
* [docs] Document which fields `--add-metadata` adds to the file
* [docs] Fix some mistakes and improve doc
* [cleanup] Misc code cleanup


### 2021.08.02

* Add logo, banner and donate links
* [outtmpl] Expand and escape environment variables
* [outtmpl] Add format types `j` (json), `l` (comma delimited list), `q` (quoted for terminal)
* [downloader] Allow streaming some unmerged formats to stdout using ffmpeg
* [youtube] **Age-gate bypass**
    * Add `agegate` clients by [pukkandan](https://github.com/pukkandan), [MinePlayersPE](https://github.com/MinePlayersPE)
    * Add `thirdParty` to agegate clients to bypass more videos
    * Simplify client definitions, expose `embedded` clients
    * Improve age-gate detection by [coletdjnz](https://github.com/coletdjnz)
    * Fix default global API key by [coletdjnz](https://github.com/coletdjnz)
    * Add `creator` clients for age-gate bypass using unverified accounts by [zerodytrash](https://github.com/zerodytrash), [coletdjnz](https://github.com/coletdjnz), [pukkandan](https://github.com/pukkandan)
* [adobepass] Add MSO Sling TV by [wesnm](https://github.com/wesnm)
* [CBS] Add ParamountPlusSeriesIE by [Ashish0804](https://github.com/Ashish0804)
* [dplay] Add `ScienceChannelIE` by [Sipherdrakon](https://github.com/Sipherdrakon)
* [UtreonIE] Add extractor by [Ashish0804](https://github.com/Ashish0804)
* [youtube] Add `mweb` client by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Add `player_client=all`
* [youtube] Force `hl=en` for comments by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix format sorting when using alternate clients
* [youtube] Misc cleanup by [pukkandan](https://github.com/pukkandan), [coletdjnz](https://github.com/coletdjnz)
* [youtube] Extract SAPISID only once
* [CBS] Add fallback by [llacb47](https://github.com/llacb47), [pukkandan](https://github.com/pukkandan)
* [Hotstar] Support cookies by [Ashish0804](https://github.com/Ashish0804)
* [HotStarSeriesIE] Fix regex by [Ashish0804](https://github.com/Ashish0804)
* [bilibili] Improve `_VALID_URL`
* [mediaset] Fix extraction by [nixxo](https://github.com/nixxo)
* [Mxplayer] Add h265 formats by [Ashish0804](https://github.com/Ashish0804)
* [RCTIPlus] Remove PhantomJS dependency by [MinePlayersPE](https://github.com/MinePlayersPE)
* [tenplay] Add MA15+ age limit by [pento](https://github.com/pento)
* [vidio] Fix login error detection by [MinePlayersPE](https://github.com/MinePlayersPE)
* [vimeo] Better extraction of original file by [Ashish0804](https://github.com/Ashish0804)
* [generic] Support KVS player (replaces ThisVidIE) by [rigstot](https://github.com/rigstot)
* Add compat-option `no-clean-infojson`
* Remove `asr` appearing twice in `-F`
* Set `home:` as the default key for `-P`
* [utils] Fix slicing of reversed `LazyList`
* [FormatSort] Fix bug for audio with unknown codec
* [test:download] Support testing with `ignore_no_formats_error`
* [cleanup] Refactor some code


### 2021.07.24

* [youtube:tab] Extract video duration early
* [downloader] Pass `info_dict` to `progress_hook`s
* [youtube] Fix age-gated videos for API clients when cookies are supplied by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Disable `get_video_info` age-gate workaround - This endpoint seems to be completely dead
* [youtube] Try all clients even if age-gated
* [youtube] Fix subtitles only being extracted from the first client
* [youtube] Simplify `_get_text`
* [cookies] bugfix for microsoft edge on macOS
* [cookies] Handle `sqlite` `ImportError` gracefully by [mbway](https://github.com/mbway)
* [cookies] Handle errors when importing `keyring`

### 2021.07.21

* **Add option `--cookies-from-browser`** to load cookies from a browser by [mbway](https://github.com/mbway)
    * Usage: `--cookies-from-browser BROWSER[:PROFILE_NAME_OR_PATH]`
    * Also added `--no-cookies-from-browser`
    * To decrypt chromium cookies, `keyring` is needed for UNIX and `pycryptodome` for Windows
* Add option `--exec-before-download`
* Add field `live_status`
* [FFmpegMetadata] Add language of each stream and some refactoring
* [douyin] Add extractor by [pukkandan](https://github.com/pukkandan), [pyx](https://github.com/pyx)
* [pornflip] Add extractor by [mzbaulhaque](https://github.com/mzbaulhaque)
* **[youtube] Extract data from multiple clients** by [pukkandan](https://github.com/pukkandan), [coletdjnz](https://github.com/coletdjnz)
    * `player_client` now accepts multiple clients
    * Default `player_client` = `android,web`
        * This uses twice as many requests, but avoids throttling for most videos while also not losing any formats
    * Music clients can be specifically requested and is enabled by default if `music.youtube.com`
    * Added `player_client=ios` (Known issue: formats from ios are not sorted correctly)
    * Add age-gate bypass for android and ios clients
* [youtube] Extract more thumbnails
    * The thumbnail URLs are hard-coded and their actual existence is tested lazily
    * Added option `--no-check-formats` to not test them
* [youtube] Misc fixes
    * Improve extraction of livestream metadata by [pukkandan](https://github.com/pukkandan), [krichbanana](https://github.com/krichbanana)
    * Hide live dash formats since they can't be downloaded anyway
    * Fix authentication when using multiple accounts by [coletdjnz](https://github.com/coletdjnz)
    * Fix controversial videos when requested via API by [coletdjnz](https://github.com/coletdjnz)
    * Fix session index extraction and headers for non-web player clients by [coletdjnz](https://github.com/coletdjnz)
    * Make `--extractor-retries` work for more errors
    * Fix sorting of 3gp format
    * Sanity check `chapters` (and refactor related code)
    * Make `parse_time_text` and `_extract_chapters` non-fatal
    * Misc cleanup and bug fixes by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Fix channels tab
* [youtube:tab] Extract playlist availability by [coletdjnz](https://github.com/coletdjnz)
* **[youtube:comments] Move comment extraction to new API** by [coletdjnz](https://github.com/coletdjnz)
    * Adds extractor-args `comment_sort` (`top`/`new`), `max_comments`, `max_comment_depth`
* [youtube:comments] Fix `is_favorited`, improve `like_count` parsing by [coletdjnz](https://github.com/coletdjnz)
* [BravoTV] Improve metadata extraction by [kevinoconnor7](https://github.com/kevinoconnor7)
* [crunchyroll:playlist] Force http
* [yahoo:gyao:player] Relax `_VALID_URL` by [nao20010128nao](https://github.com/nao20010128nao)
* [nebula] Authentication via tokens from cookie jar by [hheimbuerger](https://github.com/hheimbuerger), [TpmKranz](https://github.com/TpmKranz)
* [RTP] Fix extraction and add subtitles by [fstirlitz](https://github.com/fstirlitz)
* [viki] Rewrite extractors and add extractor-arg `video_types` to `vikichannel` by [zackmark29](https://github.com/zackmark29), [pukkandan](https://github.com/pukkandan)
* [vlive] Extract thumbnail directly in addition to the one from Naver
* [generic] Extract previously missed subtitles by [fstirlitz](https://github.com/fstirlitz)
* [generic] Extract everything in the SMIL manifest and detect discarded subtitles by [fstirlitz](https://github.com/fstirlitz)
* [embedthumbnail] Fix `_get_thumbnail_resolution`
* [metadatafromfield] Do not detect numbers as field names
* Fix selectors `all`, `mergeall` and add tests
* Errors in playlist extraction should obey `--ignore-errors`
* Fix bug where `original_url` was not propagated when `_type`=`url`
* Revert "Merge webm formats into mkv if thumbnails are to be embedded (#173)"
    * This was wrongly checking for `write_thumbnail`
* Improve `extractor_args` parsing
* Rename `NOTE` in `-F` to `MORE INFO` since it's often confused to be the same as `format_note`
* Add `only_once` param for `write_debug` and `report_warning`
* [extractor] Allow extracting multiple groups in `_search_regex` by [fstirlitz](https://github.com/fstirlitz)
* [utils] Improve `traverse_obj`
* [utils] Add `variadic`
* [utils] Improve `js_to_json` comment regex by [fstirlitz](https://github.com/fstirlitz)
* [webtt] Fix timestamps
* [compat] Remove unnecessary code
* [docs] fix default of multistreams


### 2021.07.07

* Merge youtube-dl: Upto [commit/a803582](https://github.com/ytdl-org/youtube-dl/commit/a8035827177d6b59aca03bd717acb6a9bdd75ada)
* Add `--extractor-args` to pass some extractor-specific arguments. See [readme](https://github.com/yt-dlp/yt-dlp#extractor-arguments)
    * Add extractor option `skip` for `youtube`, e.g. `--extractor-args youtube:skip=hls,dash`
    * Deprecates `--youtube-skip-dash-manifest`, `--youtube-skip-hls-manifest`, `--youtube-include-dash-manifest`, `--youtube-include-hls-manifest`
* Allow `--list...` options to work with `--print`, `--quiet` and other `--list...` options
* [youtube] Use `player` API for additional video extraction requests by [coletdjnz](https://github.com/coletdjnz)
    * **Fixes youtube premium music** (format 141) extraction
    * Adds extractor option `player_client` = `web`/`android`
        * **`--extractor-args youtube:player_client=android` works around the throttling** for the time-being
    * Adds extractor option `player_skip=config`
    * Adds age-gate fallback using embedded client
* [youtube] Choose correct Live chat API for upcoming streams by [krichbanana](https://github.com/krichbanana)
* [youtube] Fix subtitle names for age-gated videos
* [youtube:comments] Fix error handling and add `itct` to params by [coletdjnz](https://github.com/coletdjnz)
* [youtube_live_chat] Fix download with cookies by [siikamiika](https://github.com/siikamiika)
* [youtube_live_chat] use `clickTrackingParams` by [siikamiika](https://github.com/siikamiika)
* [Funimation] Rewrite extractor
    * Add `FunimationShowIE` by [Mevious](https://github.com/Mevious)
    * **Treat the different versions of an episode as different formats of a single video**
        * This changes the video `id` and will break break existing archives
        * Compat option `seperate-video-versions` to fall back to old behavior including using the old video ids
    * Support direct `/player/` URL
    * Extractor options `language` and `version` to pre-select them during extraction
        * These options may be removed in the future if we can extract all formats without additional network requests
        * Do not rely on these for format selection and use `-f` filters instead
* [AdobePass] Add Spectrum MSO by [kevinoconnor7](https://github.com/kevinoconnor7), [ohmybahgosh](https://github.com/ohmybahgosh)
* [facebook] Extract description and fix title
* [fancode] Fix extraction, support live and allow login with refresh token by [zenerdi0de](https://github.com/zenerdi0de)
* [plutotv] Improve `_VALID_URL`
* [RCTIPlus] Add extractor by [MinePlayersPE](https://github.com/MinePlayersPE)
* [Soundcloud] Allow login using oauth token by [blackjack4494](https://github.com/blackjack4494)
* [TBS] Support livestreams by [llacb47](https://github.com/llacb47)
* [videa] Fix extraction by [nyuszika7h](https://github.com/nyuszika7h)
* [yahoo] Fix extraction by [llacb47](https://github.com/llacb47), [pukkandan](https://github.com/pukkandan)
* Process videos when using `--ignore-no-formats-error` by [krichbanana](https://github.com/krichbanana)
* Fix `--throttled-rate` when using `--load-info-json`
* Fix `--flat-playlist` when entry has no `ie_key`
* Fix `check_formats` catching `ExtractorError` instead of `DownloadError`
* Fix deprecated option `--list-formats-old`
* [downloader/ffmpeg] Fix `--ppa` when using simultaneous download
* [extractor] Prevent unnecessary download of hls manifests and refactor `hls_split_discontinuity`
* [fragment] Handle status of download and errors in threads correctly; and minor refactoring
* [thumbnailsconvertor] Treat `jpeg` as `jpg`
* [utils] Fix issues with `LazyList` reversal
* [extractor] Allow extractors to set their own login hint
* [cleanup] Simplify format selector code with `LazyList` and `yield from`
* [cleanup] Clean `extractor.common._merge_subtitles` signature
* [cleanup] Fix some typos


### 2021.06.23

* Merge youtube-dl: Upto [commit/379f52a](https://github.com/ytdl-org/youtube-dl/commit/379f52a4954013767219d25099cce9e0f9401961)
* **Add option `--throttled-rate`** below which video data is re-extracted
* [fragment] **Merge during download for `-N`**, and refactor `hls`/`dash`
* [websockets] Add `WebSocketFragmentFD` by [nao20010128nao](https://github.com/nao20010128nao), [pukkandan](https://github.com/pukkandan)
* Allow `images` formats in addition to video/audio
* [downloader/mhtml] Add new downloader for slideshows/storyboards by [fstirlitz](https://github.com/fstirlitz)
* [youtube] Temporary **fix for age-gate**
* [youtube] Support ongoing live chat by [siikamiika](https://github.com/siikamiika)
* [youtube] Improve SAPISID cookie handling by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Login is not needed for `:ytrec`
* [youtube] Non-fatal alert reporting for unavailable videos page by [coletdjnz](https://github.com/coletdjnz)
* [twitcasting] Websocket support by [nao20010128nao](https://github.com/nao20010128nao)
* [mediasite] Extract slides by [fstirlitz](https://github.com/fstirlitz)
* [funimation] Extract subtitles
* [pornhub] Extract `cast`
* [hotstar] Use server time for authentication instead of local time
* [EmbedThumbnail] Fix for already downloaded thumbnail
* [EmbedThumbnail] Add compat-option `embed-thumbnail-atomicparsley`
* Expand `--check-formats` to thumbnails
* Fix id sanitization in filenames
* Skip fixup of existing files and add `--fixup force` to force it
* Better error handling of syntax errors in `-f`
* Use `NamedTemporaryFile` for `--check-formats`
* [aria2c] Lower `--min-split-size` for HTTP downloads
* [options] Rename `--add-metadata` to `--embed-metadata`
* [utils] Improve `LazyList` and add tests
* [build] Build Windows x86 version with py3.7 and remove redundant tests by [pukkandan](https://github.com/pukkandan), [shirt](https://github.com/shirt-dev)
* [docs] Clarify that `--embed-metadata` embeds chapter markers
* [cleanup] Refactor fixup


### 2021.06.09

* Fix bug where `%(field)d` in filename template throws error
* [outtmpl] Improve offset parsing
* [test] More rigorous tests for `prepare_filename`

### 2021.06.08

* Remove support for obsolete Python versions: Only 3.6+ is now supported
* Merge youtube-dl: Upto [commit/c2350ca](https://github.com/ytdl-org/youtube-dl/commit/c2350cac243ba1ec1586fe85b0d62d1b700047a2)
* [hls] Fix decryption for multithreaded downloader
* [extractor] Fix pre-checking archive for some extractors
* [extractor] Fix FourCC fallback when parsing ISM by [fstirlitz](https://github.com/fstirlitz)
* [twitcasting] Add TwitCastingUserIE, TwitCastingLiveIE by [pukkandan](https://github.com/pukkandan), [nao20010128nao](https://github.com/nao20010128nao)
* [vidio] Add VidioPremierIE and VidioLiveIE by [MinePlayersPE](Https://github.com/MinePlayersPE)
* [viki] Fix extraction from [ytdl-org/youtube-dl@59e583f](https://github.com/ytdl-org/youtube-dl/commit/59e583f7e8530ca92776c866897d895c072e2a82)
* [youtube] Support shorts URL
* [zoom] Extract transcripts as subtitles
* Add field `original_url` with the user-inputted URL
* Fix and refactor `prepare_outtmpl`
* Make more fields available for `--print` when used with `--flat-playlist`
* [utils] Generalize `traverse_dict` to `traverse_obj`
* [downloader/ffmpeg] Hide FFmpeg banner unless in verbose mode by [fstirlitz](https://github.com/fstirlitz)
* [build] Release `yt-dlp.tar.gz`
* [build,update] Add GNU-style SHA512 and prepare updater for similar SHA256 by [nihil-admirari](https://github.com/nihil-admirari)
* [pyinst] Show Python version in exe metadata by [nihil-admirari](https://github.com/nihil-admirari)
* [docs] Improve documentation of dependencies
* [cleanup] Mark unused files
* [cleanup] Point all shebang to `python3` by [fstirlitz](https://github.com/fstirlitz)
* [cleanup] Remove duplicate file `trovolive.py`


### 2021.06.01

* Merge youtube-dl: Upto [commit/d495292](https://github.com/ytdl-org/youtube-dl/commit/d495292852b6c2f1bd58bc2141ff2b0265c952cf)
* Pre-check archive and filters during playlist extraction
* Handle Basic Auth `user:pass` in URLs by [hhirtz](https://github.com/hhirtz) and [pukkandan](https://github.com/pukkandan)
* [archiveorg] Add YoutubeWebArchiveIE by [coletdjnz](https://github.com/coletdjnz) and [alex-gedeon](https://github.com/alex-gedeon)
* [fancode] Add extractor by [rhsmachine](https://github.com/rhsmachine)
* [patreon] Support vimeo embeds by [rhsmachine](https://github.com/rhsmachine)
* [Saitosan] Add new extractor by [llacb47](https://github.com/llacb47)
* [ShemarooMe] Add extractor by [Ashish0804](https://github.com/Ashish0804) and [pukkandan](https://github.com/pukkandan)
* [telemundo] Add extractor by [king-millez](https://github.com/king-millez)
* [SonyLIV] Add SonyLIVSeriesIE and subtitle support by [Ashish0804](https://github.com/Ashish0804)
* [Hotstar] Add HotStarSeriesIE by [Ashish0804](https://github.com/Ashish0804)
* [Voot] Add VootSeriesIE by [Ashish0804](https://github.com/Ashish0804)
* [vidio] Support login and premium videos by [MinePlayersPE](https://github.com/MinePlayersPE)
* [fragment] When using `-N`, do not keep the fragment content in memory
* [ffmpeg] Download and merge in a single step if possible
* [ThumbnailsConvertor] Support conversion to `png` and make it the default by [louie-github](https://github.com/louie-github)
* [VideoConvertor] Generalize with remuxer and allow conditional recoding
* [EmbedThumbnail] Embed in `mp4`/`m4a` using mutagen by [tripulse](https://github.com/tripulse) and [pukkandan](https://github.com/pukkandan)
* [EmbedThumbnail] Embed if any thumbnail was downloaded, not just the best
* [EmbedThumbnail] Correctly escape filename
* [update] replace self without launching a subprocess in windows
* [update] Block further update for unsupported systems
* Refactor `__process_playlist` by creating `LazyList`
* Write messages to `stderr` when both `quiet` and `verbose`
* Sanitize and sort playlist thumbnails
* Remove `None` values from `info.json`
* [extractor] Always prefer native hls downloader by default
* [extractor] Skip subtitles without URI in m3u8 manifests by [hheimbuerger](https://github.com/hheimbuerger)
* [extractor] Functions to parse `socket.io` response as `json` by [pukkandan](https://github.com/pukkandan) and [llacb47](https://github.com/llacb47)
* [extractor] Allow `note=False` when extracting manifests
* [utils] Escape URLs in `sanitized_Request`, not `sanitize_url`
* [hls] Disable external downloader for `webtt`
* [youtube] `/live` URLs should raise error if channel is not live
* [youtube] Bug fixes
* [zee5] Fix m3u8 formats' extension
* [ard] Allow URLs without `-` before id by [olifre](https://github.com/olifre)
* [cleanup] `YoutubeDL._match_entry`
* [cleanup] Refactor updater
* [cleanup] Refactor ffmpeg convertors
* [cleanup] setup.py


### 2021.05.20

* **Youtube improvements**:
    * Support youtube music `MP`, `VL` and `browse` pages
    * Extract more formats for youtube music by [craftingmod](https://github.com/craftingmod), [coletdjnz](https://github.com/coletdjnz) and [pukkandan](https://github.com/pukkandan)
    * Extract multiple subtitles in same language by [pukkandan](https://github.com/pukkandan) and [tpikonen](https://github.com/tpikonen)
    * Redirect channels that doesn't have a `videos` tab to their `UU` playlists
    * Support in-channel search
    * Sort audio-only formats correctly
    * Always extract `maxresdefault` thumbnail
    * Extract audio language
    * Add subtitle language names by [nixxo](https://github.com/nixxo) and [tpikonen](https://github.com/tpikonen)
    * Show alerts only from the final webpage
    * Add `html5=1` param to `get_video_info` page requests by [coletdjnz](https://github.com/coletdjnz)
    * Better message when login required
* **Add option `--print`**: to print any field/template
    * Makes redundant: `--get-description`, `--get-duration`, `--get-filename`, `--get-format`, `--get-id`, `--get-thumbnail`, `--get-title`, `--get-url`
* Field `additional_urls` to download additional videos from metadata using [`--parse-metadata`](https://github.com/yt-dlp/yt-dlp#modifying-metadata)
* Merge youtube-dl: Upto [commit/dfbbe29](https://github.com/ytdl-org/youtube-dl/commit/dfbbe2902fc67f0f93ee47a8077c148055c67a9b)
* Write thumbnail of playlist and add `pl_thumbnail` outtmpl key
* [embedthumbnail] Add `flac` support and refactor `mutagen` code by [pukkandan](https://github.com/pukkandan) and [tripulse](https://github.com/tripulse)
* [audius:artist] Add extractor by [king-millez](https://github.com/king-millez)
* [parlview] Add extractor by [king-millez](https://github.com/king-millez)
* [tenplay] Fix extractor by [king-millez](https://github.com/king-millez)
* [rmcdecouverte] Generalize `_VALID_URL`
* Add compat-option `no-attach-infojson`
* Add field `name` for subtitles
* Ensure `post_extract` and `pre_process` only run once
* Fix `--check-formats` when there is network error
* Standardize `write_debug` and `get_param`
* [options] Alias `--write-comments`, `--no-write-comments`
* [options] Refactor callbacks
* [test:download] Only extract enough videos for `playlist_mincount`
* [extractor] bugfix for when `compat_opts` is not given
* [build] Fix x86 build by [shirt](https://github.com/shirt-dev)
* [cleanup] code formatting, youtube tests and readme

### 2021.05.11
* **Deprecate support for python versions < 3.6**
* **Subtitle extraction from manifests** by [fstirlitz](https://github.com/fstirlitz). See [be6202f](https://github.com/yt-dlp/yt-dlp/commit/be6202f12b97858b9d716e608394b51065d0419f) for details
* **Improve output template:**
    * Allow slicing lists/strings using `field.start:end:step`
    * A field can also be used as offset like `field1+num+field2`
    * A default value can be given using `field|default`
    * Prevent invalid fields from causing errors
* **Merge youtube-dl**: Upto [commit/a726009](https://github.com/ytdl-org/youtube-dl/commit/a7260099873acc6dc7d76cafad2f6b139087afd0)
* **Remove options** `-l`, `-t`, `-A` completely and disable `--auto-number`, `--title`, `--literal`, `--id`
* [Plugins] Prioritize plugins over standard extractors and prevent plugins from overwriting the standard extractor classes
* [downloader] Fix `quiet` and `to_stderr`
* [fragment] Ensure the file is closed on error
* [fragment] Make sure first segment is not skipped
* [aria2c] Fix whitespace being stripped off
* [embedthumbnail] Fix bug where jpeg thumbnails were converted again
* [FormatSort] Fix for when some formats have quality and others don't
* [utils] Add `network_exceptions`
* [utils] Escape URL while sanitizing
* [ukcolumn] Add Extractor
* [whowatch] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [CBS] Improve `_VALID_URL` to support movies
* [crackle] Improve extraction
* [curiositystream] Fix collections
* [francetvinfo] Improve video id extraction
* [generic] Respect the encoding in manifest
* [limelight] Obey `allow_unplayable_formats`
* [mediasite] Generalize URL pattern by [fstirlitz](https://github.com/fstirlitz)
* [mxplayer] Add MxplayerShowIE by [Ashish0804](https://github.com/Ashish0804)
* [nebula] Move to nebula.app by [Lamieur](https://github.com/Lamieur)
* [niconico] Fix HLS formats by [CXwudi](https://github.com/CXwudi), [tsukumijima](https://github.com/tsukumijima), [nao20010128nao](https://github.com/nao20010128nao) and [pukkandan](https://github.com/pukkandan)
* [niconico] Fix title and thumbnail extraction by [CXwudi](https://github.com/CXwudi)
* [plutotv] Extract subtitles from manifests
* [plutotv] Fix format extraction for some urls
* [rmcdecouverte] Improve `_VALID_URL`
* [sonyliv] Fix `title` and `series` extraction by [Ashish0804](https://github.com/Ashish0804)
* [tubi] Raise "no video formats" error when video url is empty
* [youtube:tab] Detect playlists inside community posts
* [youtube] Add `oembed` to reserved names
* [zee5] Fix extraction for some URLs by [Hadi0609](https://github.com/Hadi0609)
* [zee5] Fix py2 compatibility
* Fix `playlist_index` and add `playlist_autonumber`. See [#302](https://github.com/yt-dlp/yt-dlp/issues/302) for details
* Add experimental option `--check-formats` to test the URLs before format selection
* Option `--compat-options` to revert [some of yt-dlp's changes](https://github.com/yt-dlp/yt-dlp#differences-in-default-behavior)
    * Deprecates `--list-formats-as-table`, `--list-formats-old`
* Fix number of digits in `%(playlist_index)s`
* Fix case sensitivity of format selector
* Revert "[core] be able to hand over id and title using url_result"
* Do not strip out whitespaces in `-o` and `-P`
* Fix `preload_download_archive` writing verbose message to `stdout`
* Move option warnings to `YoutubeDL`so that they obey `--no-warnings` and can output colors
* Py2 compatibility for `FileNotFoundError`


### 2021.04.22
* **Improve output template:**
    * Objects can be traversed like `%(field.key1.key2)s`
    * An offset can be added to numeric fields as `%(field+N)s`
    * Deprecates `--autonumber-start`
* **Improve `--sub-langs`:**
    * Treat `--sub-langs` entries as regex
    * `all` can be used to refer to all the subtitles
    * language codes can be prefixed with `-` to exclude it
    * Deprecates `--all-subs`
* Add option `--ignore-no-formats-error` to ignore the "no video format" and similar errors
* Add option `--skip-playlist-after-errors` to skip the rest of a playlist after a given number of errors are encountered
* Merge youtube-dl: Upto [commit/7e8b3f9](https://github.com/ytdl-org/youtube-dl/commit/7e8b3f9439ebefb3a3a4e5da9c0bd2b595976438)
* [downloader] Fix bug in downloader selection
* [BilibiliChannel] Fix pagination by [nao20010128nao](https://github.com/nao20010128nao) and [pukkandan](https://github.com/pukkandan)
* [rai] Add support for http formats by [nixxo](https://github.com/nixxo)
* [TubiTv] Add TubiTvShowIE by [Ashish0804](https://github.com/Ashish0804)
* [twitcasting] Fix extractor
* [viu:ott] Fix extractor and support series by [lkho](https://github.com/lkho) and [pukkandan](https://github.com/pukkandan)
* [youtube:tab] Show unavailable videos in playlists by [coletdjnz](https://github.com/coletdjnz)
* [youtube:tab] Reload with unavailable videos for all playlists
* [youtube] Ignore invalid stretch ratio
* [youtube] Improve channel syncid extraction to support ytcfg by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Standardize API calls for tabs, mixes and search by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Bugfix in `_extract_ytcfg`
* [mildom:user:vod] Download only necessary amount of pages
* [mildom] Remove proxy completely by [fstirlitz](https://github.com/fstirlitz)
* [go] Fix `_VALID_URL`
* [MetadataFromField] Improve regex and add tests
* [Exec] Ensure backward compatibility when the command contains `%`
* [extractor] Fix inconsistent use of `report_warning`
* Ensure `mergeall` selects best format when multistreams are disabled
* Improve the yt-dlp.sh script by [fstirlitz](https://github.com/fstirlitz)
* [lazy_extractor] Do not load plugins
* [ci] Disable fail-fast
* [docs] Clarify which deprecated options still work
* [docs] Fix typos


### 2021.04.11
* Add option `--convert-thumbnails` (only jpg currently supported)
* Format selector `mergeall` to download and merge all formats
* Pass any field to `--exec` using similar syntax to output template
* Choose downloader for each protocol using `--downloader PROTO:NAME`
    * Alias `--downloader` for `--external-downloader`
    * Added `native` as an option for the downloader
* Merge youtube-dl: Upto [commit/4fb25ff](https://github.com/ytdl-org/youtube-dl/commit/4fb25ff5a3be5206bb72e5c4046715b1529fb2c7) (except vimeo)
* [DiscoveryPlusIndia] Add DiscoveryPlusIndiaShowIE by [Ashish0804](https://github.com/Ashish0804)
* [NFHSNetwork] Add extractor by [llacb47](https://github.com/llacb47)
* [nebula] Add extractor (watchnebula.com) by [hheimbuerger](https://github.com/hheimbuerger)
* [nitter] Fix extraction of reply tweets and update instance list by [B0pol](https://github.com/B0pol)
* [nitter] Fix thumbnails by [B0pol](https://github.com/B0pol)
* [youtube] Fix thumbnail URL
* [youtube] Parse API parameters from initial webpage by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Extract comments' approximate timestamp by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix alert extraction
* [bilibili] Fix uploader
* [utils] Add `datetime_from_str` and `datetime_add_months` by [coletdjnz](https://github.com/coletdjnz)
* Run some `postprocessors` before actual download
* Improve argument parsing for `-P`, `-o`, `-S`
* Fix some `m3u8` not obeying `--allow-unplayable-formats`
* Fix default of `dynamic_mpd`
* Deprecate `--all-formats`, `--include-ads`, `--hls-prefer-native`, `--hls-prefer-ffmpeg`
* [docs] Improvements

### 2021.04.03
* Merge youtube-dl: Upto [commit/654b4f4](https://github.com/ytdl-org/youtube-dl/commit/654b4f4ff2718f38b3182c1188c5d569c14cc70a)
* Ability to set a specific field in the file's metadata using `--parse-metadata`
* Ability to select n'th best format like `-f bv*.2`
* [DiscoveryPlus] Add discoveryplus.in
* [la7] Add podcasts and podcast playlists by [nixxo](https://github.com/nixxo)
* [mildom] Update extractor with current proxy by [nao20010128nao](https://github.com/nao20010128nao)
* [ard:mediathek] Fix video id extraction
* [generic] Detect Invidious' link element
* [youtube] Show premium state in `availability` by [coletdjnz](https://github.com/coletdjnz)
* [viewsource] Add extractor to handle `view-source:`
* [sponskrub] Run before embedding thumbnail
* [docs] Improve `--parse-metadata` documentation


### 2021.03.24.1
* Revert [commit/8562218](https://github.com/ytdl-org/youtube-dl/commit/8562218350a79d4709da8593bb0c538aa0824acf)

### 2021.03.24
* Merge youtube-dl: Upto 2021.03.25 ([commit/8562218](https://github.com/ytdl-org/youtube-dl/commit/8562218350a79d4709da8593bb0c538aa0824acf))
* Parse metadata from multiple fields using `--parse-metadata`
* Ability to load playlist infojson using `--load-info-json`
* Write current epoch to infojson when using `--no-clean-infojson`
* [youtube_live_chat] fix bug when trying to set cookies
* [niconico] Fix for when logged in by [CXwudi](https://github.com/CXwudi) and [xtkoba](https://github.com/xtkoba)
* [linuxacadamy] Fix login


### 2021.03.21
* Merge youtube-dl: Upto [commit/7e79ba7](https://github.com/ytdl-org/youtube-dl/commit/7e79ba7dd6e6649dd2ce3a74004b2044f2182881)
* Option `--no-clean-infojson` to keep private keys in the infojson
* [aria2c] Support retry/abort unavailable fragments by [damianoamatruda](https://github.com/damianoamatruda)
* [aria2c] Better default arguments
* [movefiles] Fix bugs and make more robust
* [formatSort] Fix `quality` being ignored
* [splitchapters] Fix for older ffmpeg
* [sponskrub] Pass proxy to sponskrub
* Make sure `post_hook` gets the final filename
* Recursively remove any private keys from infojson
* Embed video URL metadata inside `mp4` by [damianoamatruda](https://github.com/damianoamatruda) and [pukkandan](https://github.com/pukkandan)
* Merge `webm` formats into `mkv` if thumbnails are to be embedded by [damianoamatruda](https://github.com/damianoamatruda)
* Use headers and cookies when downloading subtitles by [damianoamatruda](https://github.com/damianoamatruda)
* Parse resolution in info dictionary by [damianoamatruda](https://github.com/damianoamatruda)
* More consistent warning messages by [damianoamatruda](https://github.com/damianoamatruda) and [pukkandan](https://github.com/pukkandan)
* [docs] Add deprecated options and aliases in readme
* [docs] Fix some minor mistakes

* [niconico] Partial fix adapted from [animelover1984/youtube-dl@b5eff52](https://github.com/animelover1984/youtube-dl/commit/b5eff52dd9ed5565672ea1694b38c9296db3fade) (login and smile formats still don't work)
* [niconico] Add user extractor by [animelover1984](https://github.com/animelover1984)
* [bilibili] Add anthology support by [animelover1984](https://github.com/animelover1984)
* [amcnetworks] Fix extractor by [2ShedsJackson](https://github.com/2ShedsJackson)
* [stitcher] Merge from youtube-dl by [nixxo](https://github.com/nixxo)
* [rcs] Improved extraction by [nixxo](https://github.com/nixxo)
* [linuxacadamy] Improve regex
* [youtube] Show if video is `private`, `unlisted` etc in info (`availability`) by [coletdjnz](https://github.com/coletdjnz) and [pukkandan](https://github.com/pukkandan)
* [youtube] bugfix for channel playlist extraction
* [nbc] Improve metadata extraction by [2ShedsJackson](https://github.com/2ShedsJackson)


### 2021.03.15
* **Split video by chapters**: using option `--split-chapters`
    * The output file of the split files can be set with `-o`/`-P` using the prefix `chapter:`
    * Additional keys `section_title`, `section_number`, `section_start`, `section_end` are available in the output template
* **Parallel fragment downloads** by [shirt](https://github.com/shirt-dev)
    * Use option `--concurrent-fragments` (`-N`) to set the number of threads (default 1)
* Merge youtube-dl: Upto [commit/3be0980](https://github.com/ytdl-org/youtube-dl/commit/3be098010f667b14075e3dfad1e74e5e2becc8ea)
* [zee5] Add Show Extractor by [Ashish0804](https://github.com/Ashish0804) and [pukkandan](https://github.com/pukkandan)
* [rai] fix drm check [nixxo](https://github.com/nixxo)
* [wimtv] Add extractor by [nixxo](https://github.com/nixxo)
* [mtv] Add mtv.it and extract series metadata by [nixxo](https://github.com/nixxo)
* [pluto.tv] Add extractor by [kevinoconnor7](https://github.com/kevinoconnor7)
* [youtube] Rewrite comment extraction by [coletdjnz](https://github.com/coletdjnz)
* [embedthumbnail] Set mtime correctly
* Refactor some postprocessor/downloader code by [pukkandan](https://github.com/pukkandan) and [shirt](https://github.com/shirt-dev)


### 2021.03.07
* [youtube] Fix history, mixes, community pages and trending by [pukkandan](https://github.com/pukkandan) and [coletdjnz](https://github.com/coletdjnz)
* [youtube] Fix private feeds/playlists on multi-channel accounts by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Extract alerts from continuation by [coletdjnz](https://github.com/coletdjnz)
* [cbs] Add support for ParamountPlus by [shirt](https://github.com/shirt-dev)
* [mxplayer] Rewrite extractor with show support by [pukkandan](https://github.com/pukkandan) and [Ashish0804](https://github.com/Ashish0804)
* [gedi] Improvements from youtube-dl by [nixxo](https://github.com/nixxo)
* [vimeo] Fix videos with password by [teesid](https://github.com/teesid)
* [lbry] Support `lbry://` url by [nixxo](https://github.com/nixxo)
* [bilibili] Change `Accept` header by [pukkandan](https://github.com/pukkandan) and [animelover1984](https://github.com/animelover1984)
* [trovo] Pass origin header
* [rai] Check for DRM by [nixxo](https://github.com/nixxo)
* [downloader] Fix bug for `ffmpeg`/`httpie`
* [update] Fix updater removing the executable bit on some UNIX distros
* [update] Fix current build hash for UNIX
* [docs] Include wget/curl/aria2c install instructions for Unix by [Ashish0804](https://github.com/Ashish0804)
* Fix some videos downloading with `m3u8` extension
* Remove "fixup is ignored" warning when fixup wasn't passed by user


### 2021.03.03.2
* [build] Fix bug

### 2021.03.03
* [youtube] Use new browse API for continuation page extraction by [coletdjnz](https://github.com/coletdjnz) and [pukkandan](https://github.com/pukkandan)
* Fix HLS playlist downloading by [shirt](https://github.com/shirt-dev)
* Merge youtube-dl: Upto [2021.03.03](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.03.03)
* [mtv] Fix extractor
* [nick] Fix extractor by [DennyDai](https://github.com/DennyDai)
* [mxplayer] Add new extractor by [codeasashu](https://github.com/codeasashu)
* [youtube] Throw error when `--extractor-retries` are exhausted
* Reduce default of `--extractor-retries` to 3
* Fix packaging bugs by [hseg](https://github.com/hseg)


### 2021.03.01
* Allow specifying path in `--external-downloader`
* Add option `--sleep-requests` to sleep b/w requests
* Add option `--extractor-retries` to retry on known extractor errors
* Extract comments only when needed
* `--get-comments` doesn't imply `--write-info-json` if `-J`, `-j` or `--print-json` are used
* Fix `get_executable_path` by [shirt](https://github.com/shirt-dev)
* [youtube] Retry on more known errors than just HTTP-5xx
* [youtube] Fix inconsistent `webpage_url`
* [tennistv] Fix format sorting
* [bilibiliaudio] Recognize the file as audio-only
* [hrfensehen] Fix wrong import
* [viki] Fix viki play pass authentication by [RobinD42](https://github.com/RobinD42)
* [readthedocs] Improvements by [shirt](https://github.com/shirt-dev)
* [hls] Fix bug with m3u8 format extraction
* [hls] Enable `--hls-use-mpegts` by default when downloading live-streams
* [embedthumbnail] Fix bug with deleting original thumbnail
* [build] Fix completion paths, zsh pip completion install by [hseg](https://github.com/hseg)
* [ci] Disable download tests unless specifically invoked
* Cleanup some code and fix typos


### 2021.02.24
* Moved project to an organization [yt-dlp](https://github.com/yt-dlp)
* **Completely changed project name to yt-dlp** by [Pccode66](https://github.com/Pccode66) and [pukkandan](https://github.com/pukkandan)
    * Also, `youtube-dlc` config files are no longer loaded
* Merge youtube-dl: Upto [commit/4460329](https://github.com/ytdl-org/youtube-dl/commit/44603290e5002153f3ebad6230cc73aef42cc2cd) (except tmz, gedi)
* [Readthedocs](https://yt-dlp.readthedocs.io) support by [shirt](https://github.com/shirt-dev)
* [youtube] Show if video was a live stream in info (`was_live`)
* [Zee5] Add new extractor by [Ashish0804](https://github.com/Ashish0804) and [pukkandan](https://github.com/pukkandan)
* [jwplatform] Add support for `hyland.com`
* [tennistv] Fix extractor
* [hls] Support media initialization by [shirt](https://github.com/shirt-dev)
* [hls] Added options `--hls-split-discontinuity` to better support media discontinuity by [shirt](https://github.com/shirt-dev)
* [ffmpeg] Allow passing custom arguments before -i using `--ppa "ffmpeg_i1:ARGS"` syntax
* Fix `--windows-filenames` removing `/` from UNIX paths
* [hls] Show warning if pycryptodome is not found
* [docs] Improvements
    * Fix documentation of `Extractor Options`
    * Document `all` in format selection
    * Document `playable_in_embed` in output templates


### 2021.02.19
* Merge youtube-dl: Upto [commit/cf2dbec](https://github.com/ytdl-org/youtube-dl/commit/cf2dbec6301177a1fddf72862de05fa912d9869d) (except kakao)
* [viki] Fix extractor
* [niconico] Extract `channel` and `channel_id` by [kurumigi](https://github.com/kurumigi)
* [youtube] Multiple page support for hashtag URLs
* [youtube] Add more invidious instances
* [youtube] Fix comment extraction when comment text is empty
* Option `--windows-filenames` to force use of windows compatible filenames
* [ExtractAudio] Bugfix
* Don't raise `parser.error` when exiting for update
* [MoveFiles] Fix for when merger can't run
* Changed `--trim-file-name` to `--trim-filenames` to be similar to related options
* Format Sort improvements:
    * Prefer `vp9.2` more than other `vp9` codecs
    * Remove forced priority of `quality`
    * Remove unnecessary `field_preference` and misuse of `preference` from extractors
* Build improvements:
    * Fix hash output by [shirt](https://github.com/shirt-dev)
    * Lock python package versions for x86 and use `wheels` by [shirt](https://github.com/shirt-dev)
    * Exclude `vcruntime140.dll` from UPX by [jbruchon](https://github.com/jbruchon)
    * Set version number based on UTC time, not local time
    * Publish on PyPi only if token is set
* [docs] Better document `--prefer-free-formats` and add `--no-prefer-free-format`


### 2021.02.15
* Merge youtube-dl: Upto [2021.02.10](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.02.10) (except archive.org)
* [niconico] Improved extraction and support encrypted/SMILE movies by [kurumigi](https://github.com/kurumigi), [tsukumijima](https://github.com/tsukumijima), [bbepis](https://github.com/bbepis), [pukkandan](https://github.com/pukkandan)
* Fix HLS AES-128 with multiple keys in external downloaders by [shirt](https://github.com/shirt-dev)
* [youtube_live_chat] Fix by using POST API by [siikamiika](https://github.com/siikamiika)
* [rumble] Add support for video page
* Option `--allow-unplayable-formats` to allow downloading unplayable video formats
* [ExtractAudio] Don't re-encode when file is already in a common audio format
* [youtube] Fix search continuations
* [youtube] Fix for new accounts
* Improve build/updater: by [pukkandan](https://github.com/pukkandan) and [shirt](https://github.com/shirt-dev)
    * Fix SHA256 calculation in build and implement hash checking for updater
    * Exit immediately in windows once the update process starts
    * Fix updater for `x86.exe`
    * Updater looks for both `yt-dlp` and `youtube-dlc` in releases for future-proofing
    * Change optional dependency to `pycryptodome`
* Fix issue with unicode filenames in aria2c by [shirt](https://github.com/shirt-dev)
* Fix `allow_playlist_files` not being correctly passed through
* Fix for empty HTTP head requests by [shirt](https://github.com/shirt-dev)
* Fix `get_executable_path` in UNIX
* [sponskrub] Print ffmpeg output and errors to terminal
* `__real_download` should be false when ffmpeg unavailable and no download
* Show `exe`/`zip`/`source` and 32/64bit in verbose message


### 2021.02.09
* **aria2c support for DASH/HLS**: by [shirt](https://github.com/shirt-dev)
* **Implement Updater** (`-U`) by [shirt](https://github.com/shirt-dev)
* [youtube] Fix comment extraction
* [youtube_live_chat] Improve extraction
* [youtube] Fix for channel URLs sometimes not downloading all pages
* [aria2c] Changed default arguments to `--console-log-level=warn --summary-interval=0 --file-allocation=none -x16 -j16 -s16`
* Add fallback for thumbnails
* [embedthumbnail] Keep original thumbnail after conversion if write_thumbnail given
* [embedsubtitle] Keep original subtitle after conversion if write_subtitles given
* [pyinst.py] Move back to root dir
* [youtube] Simplified renderer parsing and bugfixes
* [movefiles] Fix compatibility with python2
* [remuxvideo] Fix validation of conditional remux
* [sponskrub] Don't raise error when the video does not exist
* [docs] Crypto is an optional dependency


### 2021.02.04
* Merge youtube-dl: Upto [2021.02.04.1](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.02.04.1)
* **Date/time formatting in output template:**
    * You can use [`strftime`](https://docs.python.org/3/library/datetime.html#strftime-and-strptime-format-codes) to format date/time fields. Example: `%(upload_date>%Y-%m-%d)s`
* **Multiple output templates:**
    * Separate output templates can be given for the different metadata files by using `-o TYPE:TEMPLATE`
    * The allowed types are: `subtitle|thumbnail|description|annotation|infojson|pl_description|pl_infojson`
* [youtube] More metadata extraction for channel/playlist URLs (channel, uploader, thumbnail, tags)
* New option `--no-write-playlist-metafiles` to prevent writing playlist metadata files
* [audius] Fix extractor
* [youtube_live_chat] Fix `parse_yt_initial_data` and add `fragment_retries`
* [postprocessor] Raise errors correctly
* [metadatafromtitle] Fix bug when extracting data from numeric fields
* Fix issue with overwriting files
* Fix "Default format spec" appearing in quiet mode
* [FormatSort] Allow user to prefer av01 over vp9 (The default is still vp9)
* [FormatSort] fix bug where `quality` had more priority than `hasvid`
* [pyinst] Automatically detect python architecture and working directory
* Strip out internal fields such as `_filename` from infojson


### 2021.01.29
* **Features from [animelover1984/youtube-dl](https://github.com/animelover1984/youtube-dl)**: by [animelover1984](https://github.com/animelover1984) and [bbepis](https://github.com/bbepis)
    * Add `--get-comments`
    * [youtube] Extract comments
    * [billibilli] Added BiliBiliSearchIE, BilibiliChannelIE
    * [billibilli] Extract comments
    * [billibilli] Better video extraction
    * Write playlist data to infojson
    * [FFmpegMetadata] Embed infojson inside the video
    * [EmbedThumbnail] Try embedding in mp4 using ffprobe and `-disposition`
    * [EmbedThumbnail] Treat mka like mkv and mov like mp4
    * [EmbedThumbnail] Embed in ogg/opus
    * [VideoRemuxer] Conditionally remux video
    * [VideoRemuxer] Add `-movflags +faststart` when remuxing to mp4
    * [ffmpeg] Print entire stderr in verbose when there is error
    * [EmbedSubtitle] Warn when embedding ass in mp4
    * [anvato] Use NFLTokenGenerator if possible
* **Parse additional metadata**: New option `--parse-metadata` to extract additional metadata from existing fields
    * The extracted fields can be used in `--output`
    * Deprecated `--metadata-from-title`
* [Audius] Add extractor
* [youtube] Extract playlist description and write it to `.description` file
* Detect existing files even when using `recode`/`remux` (`extract-audio` is partially fixed)
* Fix wrong user config from v2021.01.24
* [youtube] Report error message from youtube as error instead of warning
* [FormatSort] Fix some fields not sorting from v2021.01.24
* [postprocessor] Deprecate `avconv`/`avprobe`.  All current functionality is left untouched. But don't expect any new features to work with avconv
* [postprocessor] fix `write_debug` to not throw error when there is no `_downloader`
* [movefiles] Don't give "cant find" warning when move is unnecessary
* Refactor `update-version`, `pyinst.py` and related files
* [ffmpeg] Document more formats that are supported for remux/recode


### 2021.01.24
* Merge youtube-dl: Upto [2021.01.24](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.01.16)
* Plugin support ([documentation](https://github.com/yt-dlp/yt-dlp#plugins))
* **Multiple paths**: New option `-P`/`--paths` to give different paths for different types of files
    * The syntax is `-P "type:path" -P "type:path"`
    * Valid types are: home, temp, description, annotation, subtitle, infojson, thumbnail
    * Additionally, configuration file is taken from home directory or current directory
* Allow passing different arguments to different external downloaders
* [mildom] Add extractor by [nao20010128nao](https://github.com/nao20010128nao)
* Warn when using old style `--external-downloader-args` and `--post-processor-args`
* Fix `--no-overwrite` when using `--write-link`
* [sponskrub] Output `unrecognized argument` error message correctly
* [cbs] Make failure to extract title non-fatal
* Fix typecasting when pre-checking archive
* Fix issue with setting title on UNIX
* Deprecate redundant aliases in `formatSort`. The aliases remain functional for backward compatibility, but will be left undocumented
* [tests] Fix test_post_hooks
* [tests] Split core and download tests


### 2021.01.20
* [TrovoLive] Add extractor (only VODs)
* [pokemon] Add `/#/player` URLs
* Improved parsing of multiple postprocessor-args, add `--ppa` as alias
* [EmbedThumbnail] Simplify embedding in mkv
* [sponskrub] Encode filenames correctly, better debug output and error message
* [readme] Cleanup options


### 2021.01.16
* Merge youtube-dl: Upto [2021.01.16](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.01.16)
* **Configuration files:**
    * Portable configuration file: `./yt-dlp.conf`
    * Allow the configuration files to be named `yt-dlp` instead of `youtube-dlc`. See [this](https://github.com/yt-dlp/yt-dlp#configuration) for details
* Add PyPI release


### 2021.01.14
* Added option `--break-on-reject`
* [roosterteeth.com] Fix for bonus episodes by [Zocker1999NET](https://github.com/Zocker1999NET)
* [tiktok] Fix for when share_info is empty
* [EmbedThumbnail] Fix bug due to incorrect function name
* [docs] Changed sponskrub links to point to [yt-dlp/SponSkrub](https://github.com/yt-dlp/SponSkrub) since I am now providing both linux and windows releases
* [docs] Change all links to correctly point to new fork URL
* [docs] Fixes typos


### 2021.01.12
* [roosterteeth.com] Add subtitle support by [samiksome](https://github.com/samiksome)
* Added `--force-overwrites`, `--no-force-overwrites` by [alxnull](https://github.com/alxnull)
* Changed fork name to `yt-dlp`
* Fix typos by [FelixFrog](https://github.com/FelixFrog)
* [ci] Option to skip
* [changelog] Added unreleased changes in blackjack4494/yt-dlc


### 2021.01.10
* [archive.org] Fix extractor and add support for audio and playlists by [wporr](https://github.com/wporr)
* [Animelab] Added by [mariuszskon](https://github.com/mariuszskon)
* [youtube:search] Fix view_count by [ohnonot](https://github.com/ohnonot)
* [youtube] Show if video is embeddable in info (`playable_in_embed`)
* Update version badge automatically in README
* Enable `test_youtube_search_matching`
* Create `to_screen` and similar functions in postprocessor/common


### 2021.01.09
* [youtube] Fix bug in automatic caption extraction
* Add `post_hooks` to YoutubeDL by [alexmerkel](https://github.com/alexmerkel)
* Batch file enumeration improvements by [glenn-slayden](https://github.com/glenn-slayden)
* Stop immediately when reaching `--max-downloads` by [glenn-slayden](https://github.com/glenn-slayden)
* Fix incorrect ANSI sequence for restoring console-window title by [glenn-slayden](https://github.com/glenn-slayden)
* Kill child processes when yt-dlc is killed by [Unrud](https://github.com/Unrud)


### 2021.01.08
* Merge youtube-dl: Upto [2021.01.08](https://github.com/ytdl-org/youtube-dl/releases/tag/2021.01.08) except stitcher ([1](https://github.com/ytdl-org/youtube-dl/commit/bb38a1215718cdf36d73ff0a7830a64cd9fa37cc), [2](https://github.com/ytdl-org/youtube-dl/commit/a563c97c5cddf55f8989ed7ea8314ef78e30107f))
* Moved changelog to separate file


### 2021.01.07-1
* [Akamai] fix by [nixxo](https://github.com/nixxo)
* [Tiktok] merge youtube-dl tiktok extractor by [GreyAlien502](https://github.com/GreyAlien502)
* [vlive] add support for playlists by [kyuyeunk](https://github.com/kyuyeunk)
* [youtube_live_chat] make sure playerOffsetMs is positive by [siikamiika](https://github.com/siikamiika)
* Ignore extra data streams in ffmpeg by [jbruchon](https://github.com/jbruchon)
* Allow passing different arguments to different postprocessors using `--postprocessor-args`
* Deprecated `--sponskrub-args`. The same can now be done using `--postprocessor-args "sponskrub:<args>"`
* [CI] Split tests into core-test and full-test


### 2021.01.07
* Removed priority of `av01` codec in `-S` since most devices don't support it yet
* Added `duration_string` to be used in `--output`
* Created First Release


### 2021.01.05-1
* **Changed defaults:**
    * Enabled `--ignore`
    * Disabled `--video-multistreams` and `--audio-multistreams`
    * Changed default format selection to `bv*+ba/b` when `--audio-multistreams` is disabled
    * Changed default format sort order to `res,fps,codec,size,br,asr,proto,ext,has_audio,source,format_id`
    * Changed `webm` to be more preferable than `flv` in format sorting
    * Changed default output template to `%(title)s [%(id)s].%(ext)s`
    * Enabled `--list-formats-as-table`


### 2021.01.05
* **Format Sort:** Added `--format-sort` (`-S`), `--format-sort-force` (`--S-force`) - See [Sorting Formats](README.md#sorting-formats) for details
* **Format Selection:** See [Format Selection](README.md#format-selection) for details
    * New format selectors: `best*`, `worst*`, `bestvideo*`, `bestaudio*`, `worstvideo*`, `worstaudio*`
    * Changed video format sorting to show video only files and video+audio files together
    * Added `--video-multistreams`, `--no-video-multistreams`, `--audio-multistreams`, `--no-audio-multistreams`
    * Added `b`,`w`,`v`,`a` as alias for `best`, `worst`, `video` and `audio` respectively
* Shortcut Options: Added `--write-link`, `--write-url-link`, `--write-webloc-link`, `--write-desktop-link` by [h-h-h-h](https://github.com/h-h-h-h) - See [Internet Shortcut Options](README.md#internet-shortcut-options) for details
* **Sponskrub integration:** Added `--sponskrub`, `--sponskrub-cut`, `--sponskrub-force`, `--sponskrub-location`, `--sponskrub-args` - See [SponSkrub Options](README.md#sponskrub-sponsorblock-options) for details
* Added `--force-download-archive` (`--force-write-archive`) by [h-h-h-h](https://github.com/h-h-h-h)
* Added `--list-formats-as-table`,  `--list-formats-old`
* **Negative Options:** Makes it possible to negate most boolean options by adding a `no-` to the switch. Usefull when you want to reverse an option that is defined in a config file
    * Added `--no-ignore-dynamic-mpd`, `--no-allow-dynamic-mpd`, `--allow-dynamic-mpd`, `--youtube-include-hls-manifest`, `--no-youtube-include-hls-manifest`, `--no-youtube-skip-hls-manifest`, `--no-download`, `--no-download-archive`, `--resize-buffer`, `--part`, `--mtime`, `--no-keep-fragments`, `--no-cookies`, `--no-write-annotations`, `--no-write-info-json`, `--no-write-description`, `--no-write-thumbnail`, `--youtube-include-dash-manifest`, `--post-overwrites`, `--no-keep-video`, `--no-embed-subs`, `--no-embed-thumbnail`, `--no-add-metadata`, `--no-include-ads`, `--no-write-sub`, `--no-write-auto-sub`, `--no-playlist-reverse`, `--no-restrict-filenames`, `--youtube-include-dash-manifest`, `--no-format-sort-force`, `--flat-videos`, `--no-list-formats-as-table`, `--no-sponskrub`, `--no-sponskrub-cut`, `--no-sponskrub-force`
    * Renamed: `--write-subs`, `--no-write-subs`, `--no-write-auto-subs`, `--write-auto-subs`. Note that these can still be used without the ending "s"
* Relaxed validation for format filters so that any arbitrary field can be used
* Fix for embedding thumbnail in mp3 by [pauldubois98](https://github.com/pauldubois98) ([ytdl-org/youtube-dl#21569](https://github.com/ytdl-org/youtube-dl/pull/21569))
* Make Twitch Video ID output from Playlist and VOD extractor same. This is only a temporary fix
* Merge youtube-dl: Upto [2021.01.03](https://github.com/ytdl-org/youtube-dl/commit/8e953dcbb10a1a42f4e12e4e132657cb0100a1f8) - See [blackjack4494/yt-dlc#280](https://github.com/blackjack4494/yt-dlc/pull/280) for details
    * Extractors [tiktok](https://github.com/ytdl-org/youtube-dl/commit/fb626c05867deab04425bad0c0b16b55473841a2) and [hotstar](https://github.com/ytdl-org/youtube-dl/commit/bb38a1215718cdf36d73ff0a7830a64cd9fa37cc) have not been merged
* Cleaned up the fork for public use


**Note**: All uncredited changes above this point are authored by [pukkandan](https://github.com/pukkandan)

### Unreleased changes in [blackjack4494/yt-dlc](https://github.com/blackjack4494/yt-dlc)
* Updated to youtube-dl release 2020.11.26 by [pukkandan](https://github.com/pukkandan)
* Youtube improvements by [pukkandan](https://github.com/pukkandan)
    * Implemented all Youtube Feeds (ytfav, ytwatchlater, ytsubs, ythistory, ytrec) and SearchURL
    * Fix some improper Youtube URLs
    * Redirect channel home to /video
    * Print youtube's warning message
    * Handle Multiple pages for feeds better
* [youtube] Fix ytsearch not returning results sometimes due to promoted content by [coletdjnz](https://github.com/coletdjnz)
* [youtube] Temporary fix for automatic captions - disable json3 by [blackjack4494](https://github.com/blackjack4494)
* Add --break-on-existing by [gergesh](https://github.com/gergesh)
* Pre-check video IDs in the archive before downloading by [pukkandan](https://github.com/pukkandan)
* [bitwave.tv] New extractor by [lorpus](https://github.com/lorpus)
* [Gedi] Add extractor by [nixxo](https://github.com/nixxo)
* [Rcs] Add new extractor by [nixxo](https://github.com/nixxo)
* [skyit] New skyitalia extractor by [nixxo](https://github.com/nixxo)
* [france.tv] Fix thumbnail URL by [renalid](https://github.com/renalid)
* [ina] support mobile links by [B0pol](https://github.com/B0pol)
* [instagram] Fix thumbnail extractor by [nao20010128nao](https://github.com/nao20010128nao)
* [SouthparkDe] Support for English URLs by [xypwn](https://github.com/xypwn)
* [spreaker] fix SpreakerShowIE test URL by [pukkandan](https://github.com/pukkandan)
* [Vlive] Fix playlist handling when downloading a channel by [kyuyeunk](https://github.com/kyuyeunk)
* [tmz] Fix extractor by [diegorodriguezv](https://github.com/diegorodriguezv)
* [ITV] BTCC URL update by [WolfganP](https://github.com/WolfganP)
* [generic] Detect embedded bitchute videos by [pukkandan](https://github.com/pukkandan)
* [generic] Extract embedded youtube and twitter videos by [diegorodriguezv](https://github.com/diegorodriguezv)
* [ffmpeg] Ensure all streams are copied by [pukkandan](https://github.com/pukkandan)
* [embedthumbnail] Fix for os.rename error by [pukkandan](https://github.com/pukkandan)
* make_win.bat: don't use UPX to pack vcruntime140.dll by [jbruchon](https://github.com/jbruchon)


### Changelog of [blackjack4494/yt-dlc](https://github.com/blackjack4494/yt-dlc) till release 2020.11.11-3

**Note**: This was constructed from the merge commit messages and may not be entirely accurate

* [bandcamp] fix failing test. remove subclass hack by [insaneracist](https://github.com/insaneracist)
* [bandcamp] restore album downloads by [insaneracist](https://github.com/insaneracist)
* [francetv] fix extractor by [Surkal](https://github.com/Surkal)
* [gdcvault] fix extractor by [blackjack4494](https://github.com/blackjack4494)
* [hotstar] Move to API v1 by [theincognito-inc](https://github.com/theincognito-inc)
* [hrfernsehen] add extractor by [blocktrron](https://github.com/blocktrron)
* [kakao] new apis by [blackjack4494](https://github.com/blackjack4494)
* [la7] fix missing protocol by [nixxo](https://github.com/nixxo)
* [mailru] removed escaped braces, use urljoin, added tests by [nixxo](https://github.com/nixxo)
* [MTV/Nick] universal mgid extractor + fix nick.de feed by [blackjack4494](https://github.com/blackjack4494)
* [mtv] Fix a missing match_id by [nixxo](https://github.com/nixxo)
* [Mtv] updated extractor logic & more by [blackjack4494](https://github.com/blackjack4494)
* [ndr] support Daserste ndr by [blackjack4494](https://github.com/blackjack4494)
* [Netzkino] Only use video id to find metadata by [TobiX](https://github.com/TobiX)
* [newgrounds] fix: video download by [insaneracist](https://github.com/insaneracist)
* [nitter] Add new extractor by [B0pol](https://github.com/B0pol)
* [soundcloud] Resolve audio/x-wav by [tfvlrue](https://github.com/tfvlrue)
* [soundcloud] sets pattern and tests by [blackjack4494](https://github.com/blackjack4494)
* [SouthparkDE/MTV] another mgid extraction (mtv_base) feed url updated by [blackjack4494](https://github.com/blackjack4494)
* [StoryFire] Add new extractor by [sgstair](https://github.com/sgstair)
* [twitch] by [geauxlo](https://github.com/geauxlo)
* [videa] Adapt to updates by [adrianheine](https://github.com/adrianheine)
* [Viki] subtitles, formats by [blackjack4494](https://github.com/blackjack4494)
* [vlive] fix extractor for revamped website by [exwm](https://github.com/exwm)
* [xtube] fix extractor by [insaneracist](https://github.com/insaneracist)
* [youtube] Convert subs when download is skipped by [blackjack4494](https://github.com/blackjack4494)
* [youtube] Fix age gate detection by [random-nick](https://github.com/random-nick)
* [youtube] fix yt-only playback when age restricted/gated - requires cookies by [blackjack4494](https://github.com/blackjack4494)
* [youtube] fix: extract artist metadata from ytInitialData by [insaneracist](https://github.com/insaneracist)
* [youtube] fix: extract mix playlist ids from ytInitialData by [insaneracist](https://github.com/insaneracist)
* [youtube] fix: mix playlist title by [insaneracist](https://github.com/insaneracist)
* [youtube] fix: Youtube Music playlists by [insaneracist](https://github.com/insaneracist)
* [Youtube] Fixed problem with new youtube player by [peet1993](https://github.com/peet1993)
* [zoom] Fix url parsing for url's containing /share/ and dots by [Romern](https://github.com/Romern)
* [zoom] new extractor by [insaneracist](https://github.com/insaneracist)
* abc by [adrianheine](https://github.com/adrianheine)
* Added Comcast_SSO fix by [merval](https://github.com/merval)
* Added DRM logic to brightcove by [merval](https://github.com/merval)
* Added regex for ABC.com site. by [kucksdorfs](https://github.com/kucksdorfs)
* alura by [hugohaa](https://github.com/hugohaa)
* Arbitrary merges by [fstirlitz](https://github.com/fstirlitz)
* ard.py_add_playlist_support by [martin54](https://github.com/martin54)
* Bugfix/youtube/chapters fix extractor by [gschizas](https://github.com/gschizas)
* bugfix_youtube_like_extraction by [RedpointsBots](https://github.com/RedpointsBots)
* Create build workflow by [blackjack4494](https://github.com/blackjack4494)
* deezer by [LucBerge](https://github.com/LucBerge)
* Detect embedded bitchute videos by [pukkandan](https://github.com/pukkandan)
* Don't install tests by [l29ah](https://github.com/l29ah)
* Don't try to embed/convert json subtitles generated by [youtube](https://github.com/youtube) livechat by [pukkandan](https://github.com/pukkandan)
* Doodstream by [sxvghd](https://github.com/sxvghd)
* duboku by [lkho](https://github.com/lkho)
* elonet by [tpikonen](https://github.com/tpikonen)
* ext/remuxe-video by [Zocker1999NET](https://github.com/Zocker1999NET)
* fall-back to the old way to fetch subtitles, if needed by [RobinD42](https://github.com/RobinD42)
* feature_subscriber_count by [RedpointsBots](https://github.com/RedpointsBots)
* Fix external downloader when there is no http_header by [pukkandan](https://github.com/pukkandan)
* Fix issue triggered by [tubeup](https://github.com/tubeup) by [nsapa](https://github.com/nsapa)
* Fix YoutubePlaylistsIE by [ZenulAbidin](https://github.com/ZenulAbidin)
* fix-mitele' by [DjMoren](https://github.com/DjMoren)
* fix/google-drive-cookie-issue by [legraphista](https://github.com/legraphista)
* fix_tiktok by [mervel-mervel](https://github.com/mervel-mervel)
* Fixed problem with JS player URL by [peet1993](https://github.com/peet1993)
* fixYTSearch by [xarantolus](https://github.com/xarantolus)
* FliegendeWurst-3sat-zdf-merger-bugfix-feature
* gilou-bandcamp_update
* implement ThisVid extractor by [rigstot](https://github.com/rigstot)
* JensTimmerman-patch-1 by [JensTimmerman](https://github.com/JensTimmerman)
* Keep download archive in memory for better performance by [jbruchon](https://github.com/jbruchon)
* la7-fix by [iamleot](https://github.com/iamleot)
* magenta by [adrianheine](https://github.com/adrianheine)
* Merge 26564 from [adrianheine](https://github.com/adrianheine)
* Merge code from [ddland](https://github.com/ddland)
* Merge code from [nixxo](https://github.com/nixxo)
* Merge code from [ssaqua](https://github.com/ssaqua)
* Merge code from [zubearc](https://github.com/zubearc)
* mkvthumbnail by [MrDoritos](https://github.com/MrDoritos)
* myvideo_ge by [fonkap](https://github.com/fonkap)
* naver by [SeonjaeHyeon](https://github.com/SeonjaeHyeon)
* ondemandkorea by [julien-hadleyjack](https://github.com/julien-hadleyjack)
* rai-update by [iamleot](https://github.com/iamleot)
* RFC: youtube: Polymer UI and JSON endpoints for playlists by [wlritchi](https://github.com/wlritchi)
* rutv by [adrianheine](https://github.com/adrianheine)
* Sc extractor web auth by [blackjack4494](https://github.com/blackjack4494)
* Switch from binary search tree to Python sets by [jbruchon](https://github.com/jbruchon)
* tiktok by [skyme5](https://github.com/skyme5)
* tvnow by [TinyToweringTree](https://github.com/TinyToweringTree)
* twitch-fix by [lel-amri](https://github.com/lel-amri)
* Twitter shortener by [blackjack4494](https://github.com/blackjack4494)
* Update README.md by [JensTimmerman](https://github.com/JensTimmerman)
* Update to reflect website changes. by [amigatomte](https://github.com/amigatomte)
* use webarchive to fix a dead link in README by [B0pol](https://github.com/B0pol)
* Viki the second by [blackjack4494](https://github.com/blackjack4494)
* wdr-subtitles by [mrtnmtth](https://github.com/mrtnmtth)
* Webpfix by [alexmerkel](https://github.com/alexmerkel)
* Youtube live chat by [siikamiika](https://github.com/siikamiika)
