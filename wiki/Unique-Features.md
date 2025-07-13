[RVX](https://github.com/inotia00/revanced-patches/) includes additional features beyond the original [ReVanced](https://github.com/revanced/revanced-patches), and this project further enhances RVX with even more features. Previously, this project introduced some features that have since been adopted and moved to the projects mentioned above. Keep in mind that enabling more features can reduce the performance of the patched app.

### Unique features:

> [!NOTE]
> #### YouTube
> - Force player buttons background: Option to change the color and opacity
> - Overlay buttons: Content descriptions for improved accessibility (for users with visual impairments)
> - Overlay buttons: Second downloader on long tap
> - Overlay buttons: Summarize and transcribe videos with Gemini, transcribe videos with Yandex (faster and more reliable than Gemini)
> - Overlay buttons: Whitelist lists are importable and exportable
> - Seekbar components: A color indicator and a color picker 
> - Seekbar components: Set gradient seekbar bounds
> - Settings: Clickable categories in search results
> - Settings: Categories show full path
> - Settings: More preferences are indexed
> - Settings: Search results highlighting
> - Settings: Search history
> - Shorts custom actions: Summarize videos with Gemini
> - Shorts components: Hide disabled comment button
> - SponsorBlock: Draggable new segment window
> - SponsorBlock: New segment window alignment
> - Swipe controls: Horizontal swipe for playback speed control (bottom half of the screen) and video seeking (top half)
> - Theme: Pale Blue, Green, Yellow colors
> - Visual preferences icons: Updated icons and added some new icons

> [!IMPORTANT]
> #### YT & YTM
> - Icons
>   - MMT Blue
>   - MMT Green
>   - MMT Orange
>   - MMT Pink
>   - MMT Turquoise
>   - MMT Yellow
>   - Squid Game
>   - Vanced Light
>   - Vanced Dark
>   - Xisr Special
>   - Xisr Yellow
>   - YouTube Black
> 
> - "Don't show again" option for GMSCore battery optimization dialog
> - Settings: Ability to remove summaries / descriptions of RVX settings
> - Settings: Allow to export API key for `Return YouTube Username` (Caution: Do not share with others)
>
> In comparison with RVX, some icons have been updated, improved, and cleaned of unnecessary metadata. Additionally, some settings and default options for some patches have been modified.

> [!TIP]
> #### Spotify
> - Patches from ReVanced
> - Custom branding name
> - Lyrics search
> - ~Remove Create tab from bottom navigation bar~ [Replaced with ReVanced implementation (Hide Create button) for consistency and future maintainability]
> - Sanitize sharing links (manual selection of parameters to remove from URL)

<details><summary>Diff</summary>

.*,

FOLDERS
build,
resources,
spotify,
xml_tools,

FILES
*.iml,
*.json,
*.md,
*.properties,
AboutGeminiPreference.java,
AndroidManifest.xml,
BaseGestureController.kt,
BaseSettings.java,
build.gradle.kts,
BytecodeUtils.kt,
CairoFragmentPatch.kt,
CategoryType.kt,
ClassicSwipeController.kt,
ClickablePreferenceCategory.java,
ColorPreference.java,
CustomActionsPatch.java,
CustomBrandingIconPatch.kt,
CustomBrandingNamePatch.kt,
CustomColorPickerView.java,
ExternalDownload.java,
ExternalDownloaderVideoLongPressPreference.java,
FeedVideoViewsFilter.java,
Fingerprints.kt,
FlyoutMenuComponentsPatch.kt,
GeminiManager.java,
GeminiSummarize.java,
GeminiUtils.java,
GmsCoreSupport.java,
GmsCoreSupportPatch.kt,
gradle-wrapper.jar,
gradlew,
LayoutComponentsPatch.kt,
libs.versions.toml,
NewSegmentLayout.java,
OverlayButtonsPatch.kt,
patches.api,
PatchList.kt,
PlaybackSpeedPatch.java,
PlayerButtonBackgroundPatch.kt,
PlayerControlsPatch.java,
PressToSwipeController.kt,
proguard-rules.pro,
ResourceUtils.kt,
ReturnYouTubeUsernamePatch.kt,
ReVancedPreferenceFragment.java,
SeekbarColorPatch.java,
SeekbarComponentsPatch.kt,
SegmentCategoryListPreference.java,
SegmentPlaybackController.java,
settings.gradle.kts,
Settings.java,
SettingsPatch.kt,
ShortsButtonFilter.java,
SpeedDialog.java,
SponsorBlockPatch.kt,
SubtitleOverlay.java,
SwipeControlsConfigurationProvider.kt,
SwipeControlsOverlay.kt,
SwipeControlsOverlayLayout.kt,
SwipeControlsPatch.java,
SwipeControlsPatch.kt,
SwipeZonesController.kt,
ThemePatch.kt,
ThemeUtils.java,
Utils.java,
VideoInformation.java,
VideoQualitySettingsActivity.java,
VideoUtils.java,
VisualPreferencesIconsPatch.kt,
VolumeAndBrightnessScroller.kt,
Whitelist.java,
Whitelists.java,
YandexVotUtils.java.

</details>