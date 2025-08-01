## 🧩 ReVanced Patches

ReVanced Extended Patches.

## Documentation

Check the [wiki](https://github.com/anddea/revanced-patches/wiki) for resources on patching, customization, and debugging.

## 📋 List of patches in this repository

### [📦 `com.google.android.youtube`](https://play.google.com/store/apps/details?id=com.google.android.youtube)
<details>

| 💊 Patch | ⚙️ Patch-Options | 📜 Description | 🏹 Target Version |
|:--------:|:---------------:|:--------------:|:-----------------:|
| `Alternative thumbnails` | - | Adds options to replace video thumbnails using the DeArrow API or image captures from the video. | 19.43.41 ~ 19.47.53 |
| `Ambient mode control` | - | Adds options to disable Ambient mode and to bypass Ambient mode restrictions. | 19.43.41 ~ 19.47.53 |
| `Bypass URL redirects` | - | Adds an option to bypass URL redirects and open the original URL directly. | 19.43.41 ~ 19.47.53 |
| `Bypass image region restrictions` | - | Adds an option to use a different host for static images, so that images blocked in some countries can be received. | 19.43.41 ~ 19.47.53 |
| `Change form factor` | - | Adds an option to change the UI appearance to a phone, tablet, or automotive device. | 19.43.41 ~ 19.47.53 |
| `Change live ring click action` | - | Adds an option to open the channel instead of the live stream when clicking on the live ring. | 19.43.41 ~ 19.47.53 |
| `Change player flyout menu toggles` | - | Adds an option to use text toggles instead of switch toggles within the additional settings menu. | 19.43.41 ~ 19.47.53 |
| `Change share sheet` | - | Adds an option to change the in-app share sheet to the system share sheet. | 19.43.41 ~ 19.47.53 |
| `Change start page` | - | Adds an option to set which page the app opens in instead of the homepage. | 19.43.41 ~ 19.47.53 |
| `Custom Shorts action buttons` | `iconType`: cairo, outline, outlinecircle, round, youtubeoutline, youtube<br><br>**Visual Preview:**<br><div style="background-color: #2d2d2d; padding: 10px; border-radius: 5px; display: inline-block;"><img src="https://github.com/user-attachments/assets/63c2b333-7fb2-4f44-9f17-803c6988c1b2" width="25"> <img src="https://github.com/user-attachments/assets/27cc3e65-970a-4695-ac7c-12c691244674" width="25"> <img src="https://github.com/user-attachments/assets/9ff66d34-e60b-4e7d-831d-3064328e5859" width="25"> <img src="https://github.com/user-attachments/assets/d48774d5-7e69-4890-9c27-76895a473dd9" width="25"> <img src="https://github.com/user-attachments/assets/360c4d59-936e-4e3f-ad70-ff50565a1d62" width="25"> <img src="https://github.com/user-attachments/assets/cd18fc99-8700-49af-90a6-0e2603198123" width="25"></div> | Changes, at compile time, the icon of the action buttons of the Shorts player. | 19.43.41 ~ 19.47.53 |
| `Custom branding icon for YouTube` | `appIcon`:<br><div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 8px; align-items: center;"><div><img src="https://github.com/user-attachments/assets/594faabe-4588-44f7-ae18-3783ec955992" width="20"> afn_blue</div><div><img src="https://github.com/user-attachments/assets/5544c32d-9c19-4112-bc2c-e5d55227494f" width="20"> afn_red</div><div><img src="https://github.com/user-attachments/assets/0867b9ad-30e0-4140-9833-f119dbe48a25" width="20"> mmt</div><div><img src="https://github.com/user-attachments/assets/64ac275d-be3d-4849-b6a2-033c45984865" width="20"> mmt_blue</div><div><img src="https://github.com/user-attachments/assets/0064ca0e-478c-47ad-b898-66ff5544bc7b" width="20"> mmt_green</div><div><img src="https://github.com/user-attachments/assets/c2d921a9-888a-4b41-9601-3258ae0010b3" width="20"> mmt_orange</div><div><img src="https://github.com/user-attachments/assets/d99c59fe-987c-43db-8dd9-186fa68726fb" width="20"> mmt_pink</div><div><img src="https://github.com/user-attachments/assets/ea83a754-976b-43d4-a67b-8a49aaa44de9" width="20"> mmt_turquoise</div><div><img src="https://github.com/user-attachments/assets/08492413-2b58-4bf0-b786-4c849ff5f90e" width="20"> mmt_yellow</div><div><img src="https://github.com/user-attachments/assets/145a81f5-3af2-4337-b12e-c6ae6186522e" width="20"> revancify_blue</div><div><img src="https://github.com/user-attachments/assets/9868cb0d-b18e-4a3c-af40-92b207cd69c6" width="20"> revancify_red</div><div><img src="https://github.com/user-attachments/assets/469c7ff8-1bc2-4dec-b2d2-b85dc5955f8f" width="20"> squid_game</div><div><img src="https://github.com/user-attachments/assets/3922516a-1d5f-4c6a-ad73-ad7acd4dadbc" width="20"> vanced_black</div><div><img src="https://github.com/user-attachments/assets/c9159af3-f382-4ba9-9a51-f5b5d10e7a33" width="20"> vanced_light</div><div><img src="https://github.com/user-attachments/assets/3705bd5b-d922-419b-b9d8-d9da596ee628" width="20"> xisr_special</div><div><img src="https://github.com/user-attachments/assets/a55e1441-bcb1-4ad5-9a31-a597398ad5ad" width="20"> xisr_yellow</div><div><img src="https://github.com/user-attachments/assets/594faabe-4588-44f7-ae18-3783ec955992" width="20"> youtube</div><div><img src="https://github.com/user-attachments/assets/4dc710b0-3122-4519-aaaf-e88f254e4219" width="20"> youtube_black</div></div><br>`changeSplashIcon`: true, false<br>`restoreOldSplashAnimation`: true, false | Changes the YouTube app icon to the icon specified in patch options. **Enhanced with custom splash animations and multiple color variants.** | 19.43.41 ~ 19.47.53 |
| `Custom branding name for YouTube` | `appName`: ReVanced Extended, RVX, YouTube RVX, YouTube | Changes the YouTube app name to the name specified in patch options. | 19.43.41 ~ 19.47.53 |
| `Custom double tap length` | `doubleTapLengthArrays`: 3, 5, 10, 15, 20, 30, 60, 120, 180 | Adds Double-tap to seek values that are specified in patch options. | 19.43.41 ~ 19.47.53 |
| `Custom header for YouTube` | `customHeader`: custom_branding_icon | Applies a custom header in the top left corner within the app. | 19.43.41 ~ 19.47.53 |
| `Description components` | - | Adds options to hide and disable description components. | 19.43.41 ~ 19.47.53 |
| `Disable QUIC protocol` | - | Adds an option to disable CronetEngine's QUIC protocol. | 19.43.41 ~ 19.47.53 |
| `Disable forced auto audio tracks` | - | Adds an option to disable audio tracks from being automatically enabled. | 19.43.41 ~ 19.47.53 |
| `Disable forced auto captions` | - | Adds an option to disable captions from being automatically enabled. | 19.43.41 ~ 19.47.53 |
| `Disable haptic feedback` | - | Adds options to disable haptic feedback when swiping in the video player. | 19.43.41 ~ 19.47.53 |
| `Disable layout updates` | - | Adds an option to disable layout updates by server. | 19.43.41 ~ 19.47.53 |
| `Disable resuming Miniplayer on startup` | - | Adds an option to disable the Miniplayer 'Continue watching' from resuming on app startup. | 19.43.41 ~ 19.47.53 |
| `Disable resuming Shorts on startup` | - | Adds an option to disable the Shorts player from resuming on app startup when Shorts were last being watched. | 19.43.41 ~ 19.47.53 |
| `Disable splash animation` | - | Adds an option to disable the splash animation on app startup. | 19.43.41 ~ 19.47.53 |
| `Enable OPUS codec` | - | Adds an option to enable the OPUS audio codec if the player response includes it. | 19.43.41 ~ 19.47.53 |
| `Enable debug logging` | - | Adds an option to enable debug logging. | 19.43.41 ~ 19.47.53 |
| `Enable gradient loading screen` | - | Adds an option to enable the gradient loading screen. | 19.43.41 ~ 19.47.53 |
| `Force player buttons background` | `BackgroundColor`: <span style="background-color: #4d4d4d; color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#4d4d4d</span> ?ytOverlayBackgroundMediumLight, <span style="background-color: rgba(0,0,0,0); color: black; padding: 2px 6px; border-radius: 3px; font-size: 11px; border: 1px solid #ccc;">transparent</span> @android:color/transparent, <span style="background-color: rgba(0,0,0,0.1); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#1a000000</span>, <span style="background-color: rgba(0,0,0,0.2); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#33000000</span>, <span style="background-color: rgba(0,0,0,0.3); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#4d000000</span>, <span style="background-color: rgba(0,0,0,0.4); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#66000000</span>, <span style="background-color: rgba(0,0,0,0.5); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#80000000</span>, <span style="background-color: rgba(0,0,0,0.6); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#99000000</span>, <span style="background-color: rgba(0,0,0,0.7); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#b3000000</span>, <span style="background-color: rgba(0,0,0,0.8); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#cc000000</span>, <span style="background-color: rgba(0,0,0,0.9); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#e6000000</span>, <span style="background-color: rgba(0,0,0,1); color: white; padding: 2px 6px; border-radius: 3px; font-size: 11px;">#ff000000</span> | Changes the dark background surrounding the video player controls at compile time. **Unique feature: Option to change color and opacity with enhanced control.** | 19.43.41 ~ 19.47.53 |
| `Fullscreen components` | - | Adds options to hide or change components related to fullscreen. | 19.43.41 ~ 19.47.53 |
| `GmsCore support` | `gmsCoreVendorGroupId`: app.revanced<br>`checkGmsCore`: true, false<br>`packageNameYouTube`: bill.youtube, anddea.youtube<br>`packageNameYouTubeMusic`: bill.youtube.music, anddea.youtube.music<br>`patchAllManifest`: true, false | Allows patched Google apps to run without root and under a different package name by using GmsCore instead of Google Play Services. **Enhanced with "Don't show again" option for GMSCore battery optimization dialog.** | 19.43.41 ~ 19.47.53 |
| `Hide Shorts dimming` | - | Removes, at compile time, the dimming effect at the top and bottom of Shorts videos. | 19.43.41 ~ 19.47.53 |
| `Hide accessibility controls dialog` | - | Removes, at compile time, accessibility controls dialog 'Turn on accessibility controls for the video player?'. | 19.43.41 ~ 19.47.53 |
| `Hide action buttons` | - | Adds options to hide action buttons under videos. | 19.43.41 ~ 19.47.53 |
| `Hide ads` | - | Adds options to hide ads. | 19.43.41 ~ 19.47.53 |
| `Hide comments components` | - | Adds options to hide components related to comments. | 19.43.41 ~ 19.47.53 |
| `Hide feed components` | - | Adds options to hide components related to feeds. | 19.43.41 ~ 19.47.53 |
| `Hide feed flyout menu` | **Custom Filter Options:**<br><div style="display: grid; grid-template-columns: 1fr 2fr; gap: 8px; align-items: center; font-size: 12px;"><div><code>status_dot</code></div><div><img src="https://github.com/anddea/revanced-patches/assets/70171475/c65c107f-5a89-4abe-8b5f-7f9f1e23727c" style="max-height: 40px; width: auto;"></div><div><code>channel_action_button</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264081895-bae83d84-3d2f-4943-bdbb-e7af40fb5551.png" style="max-height: 60px; width: auto;"></div><div><code>channel_description_preview</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264082769-e206b437-f427-4c83-905e-923a896d89b6.png" style="max-height: 80px; width: auto;"></div><div><code>channel_header_links</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264079727-e240b8a2-645e-4987-a497-53731e36361b.png" style="max-height: 60px; width: auto;"></div><div><code>compact_channel_bar</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263509768-a34165a4-de81-4dd9-9b49-e5d1c1ea4720.jpg" style="max-height: 70px; width: auto;"></div><div><code>compact_channel_bar_header</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263509937-e2a35082-6e66-4bc3-8ab8-3d6561c0283d.jpg" style="max-height: 60px; width: auto;"></div><div><code>grid_channel_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263473867-e8c85554-c7c7-4040-907e-b776cb1dee0e.png" style="max-height: 80px; width: auto;"></div><div><code>subscribe_button</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263595829-b574b799-327d-4e43-b8af-7e816b832d90.jpg" style="max-height: 50px; width: auto;"></div><div><code>carousel_header</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263311832-3383c92b-fe41-4d00-bd3b-b8de5c728354.png" style="max-height: 40px; width: auto;"></div><div><code>expandable_product_grid</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244918938-2b8b5fb3-7462-4737-b658-0843f17bf5c2.png" style="max-height: 80px; width: auto;"></div><div><code>hero_carousel</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263474010-45f67dcc-581d-4b16-bcf4-09248ee23edd.png" style="max-height: 70px; width: auto;"></div><div><code>horizontal_gaming_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263474088-3c9e3d30-a7ec-4199-ba62-bbebc661cd10.png" style="max-height: 80px; width: auto;"></div><div><code>horizontal_tile_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263474243-d1242379-2bdd-4d24-a852-7603db413211.png" style="max-height: 80px; width: auto;"></div><div><code>library_recent_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263314942-7a5b4d69-1d05-49db-9094-9ae914a5a125.png" style="max-height: 70px; width: auto;"></div><div><code>more_drawer</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263474330-6fc1fd61-b3bb-4e61-b308-da3037dc457a.png" style="max-height: 50px; width: auto;"></div><div><code>shelf_header</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263310675-6a1f5e80-60cf-4cf1-9bb1-36709bc65e14.jpg" style="max-height: 60px; width: auto;"></div><div><code>shorts_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263312492-80145f6c-b569-45a0-9988-69ae0fda787e.png" style="max-height: 80px; width: auto;"></div><div><code>snappy_horizontal_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263474162-4769dbda-7193-4e8e-a6cf-fa5c6d8fed9d.png" style="max-height: 70px; width: auto;"></div><div><code>grid_video_wrapper</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264083099-ab65248f-d36b-4d6c-b124-38bbbfd40c47.png" style="max-height: 80px; width: auto;"></div><div><code>horizontal_video_shelf</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263311273-b6d3affa-e668-4289-a34d-ffc06835b30a.png" style="max-height: 70px; width: auto;"></div><div><code>player_overlay_video_heading</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263313396-143aa728-ce07-4cb7-8f57-a3ad8d758609.png" style="max-height: 50px; width: auto;"></div><div><code>quick_actions</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263313060-93b06e5e-d427-4d1f-ac67-c6cdc6b83895.png" style="max-height: 60px; width: auto;"></div><div><code>related_video</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263319461-e8b87f37-99bc-49fc-b660-45ec19309ac0.png" style="max-height: 80px; width: auto;"></div><div><code>video_action_toggle_button</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263313868-ecd65726-5112-41b3-86a9-e0a08e14c62c.png" style="max-height: 50px; width: auto;"></div><div><code>video_card_content</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263478662-99324dde-3304-40ab-ab5d-ec76e9de55b9.png" style="max-height: 70px; width: auto;"></div><div><code>video_subtitle</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/263509564-c6efe8d4-372a-4421-afb4-f4bec1fe9b21.jpg" style="max-height: 60px; width: auto;"></div><div><code>post_base</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264084713-3005a3f1-dd8a-461b-8361-d69aff6e366d.png" style="max-height: 80px; width: auto;"></div><div><code>post_attachment_container</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264089393-6b9aa5dc-0956-457e-abc5-2b3976d27063.png" style="max-height: 70px; width: auto;"></div><div><code>post_comment_button</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264095712-b7290f3b-3aff-43ee-b0fc-8561d8847ea8.png" style="max-height: 80px; width: auto;"></div><div><code>post_content</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264087123-ff92ad05-1830-407c-9a34-5d5db9766e0d.png" style="max-height: 70px; width: auto;"></div><div><code>expandable_list_inner</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244920930-1040a30a-dc90-49d6-82e2-a00520ccd55b.png" style="max-height: 60px; width: auto;"></div><div><code>image_attachment</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264088110-101888c3-5bae-405c-a7b9-e07ac688e7e0.png" style="max-height: 80px; width: auto;"></div><div><code>inline_expander</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244917808-990a2819-eb5e-47eb-b4c5-158ef7ed2692.png" style="max-height: 60px; width: auto;"></div><div><code>multi_image_attachment</code></div><div><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/82371061/264091369-24c12d50-3adb-4047-9b49-f4e29baaaab7.png" style="max-height: 80px; width: auto;"></div><div><code>offer_box</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244917906-35cf37cb-8526-4bbf-8b77-edd6a283f1fe.png" style="max-height: 70px; width: auto;"></div><div><code>product_offers</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244918320-f0e77a26-a1fd-48fa-981f-13438562d26e.png" style="max-height: 60px; width: auto;"></div><div><code>shopping_flagging</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244919879-0ff8fa73-7e62-41f9-be25-cac9f7401f21.png" style="max-height: 50px; width: auto;"></div><div><code>styled_product_carousel</code></div><div><img src="https://user-images.githubusercontent.com/117499019/244918005-2aa3cbe3-b4f2-4cc3-a75c-ce5750c8061d.png" style="max-height: 70px; width: auto;"></div></div> | Adds the ability to hide feed flyout menu components using a custom filter. **Enhanced with comprehensive visual filter gallery - all 35+ filters displayed with screenshots for easy identification.** | 19.43.41 ~ 19.47.53 |
| `Hide layout components` | - | Adds options to hide general layout components. | 19.43.41 ~ 19.47.53 |
| `Hide player buttons` | - | Adds options to hide buttons in the video player. | 19.43.41 ~ 19.47.53 |
| `Hide player flyout menu` | - | Adds options to hide player flyout menu components. | 19.43.41 ~ 19.47.53 |
| `Hide shortcuts` | `explore`: true, false<br>`subscriptions`: true, false<br>`search`: true, false<br>`shorts`: true, false | Remove, at compile time, the app shortcuts that appears when the app icon is long pressed. | 19.43.41 ~ 19.47.53 |
| `Hook YouTube Music actions` | - | Adds support for opening music in RVX Music using the in-app YouTube Music button. | 19.43.41 ~ 19.47.53 |
| `Hook download actions` | - | Adds support to download videos with an external downloader app using the in-app download button. | 19.43.41 ~ 19.47.53 |
| `MaterialYou` | - | Applies the MaterialYou theme for Android 12+ devices. | 19.43.41 ~ 19.47.53 |
| `Miniplayer` | - | Adds options to change the in-app minimized player, and if patching target 19.16+ adds options to use modern miniplayers. | 19.43.41 ~ 19.47.53 |
| `Navigation bar components` | - | Adds options to hide or change components related to the navigation bar. | 19.43.41 ~ 19.47.53 |
| `Open links externally` | - | Adds an option to always open links in your browser instead of the in-app browser. | 19.43.41 ~ 19.47.53 |
| `Overlay buttons` | `iconType`: bold, rounded, thin<br>`bottomMargin`: 2.5dip, 0.1dip, 5.0dip<br>`widerButtonsSpace`: true, false<br>`changeTopButtons`: true, false<br><br>**Visual Preview:**<br><div style="background-color: #2d2d2d; padding: 10px; border-radius: 5px; display: inline-block;"><br>**Bold:** <img src="https://github.com/user-attachments/assets/36f2c3e2-a75d-4ad1-9095-685abc9c7c66" width="20"> <img src="https://github.com/user-attachments/assets/71bc0b1a-45da-48e1-a8cb-4c45420efba7" width="20"> <img src="https://github.com/user-attachments/assets/9b0b75e6-8fcf-4943-ad37-d32695271dd6" width="20"><br>**Rounded:** <img src="https://github.com/user-attachments/assets/4bc5c48c-6e82-4a64-8996-edbc4ca5ac56" width="20"> <img src="https://github.com/user-attachments/assets/fdbbcaee-feaa-477d-8240-24ce763aac0e" width="20"> <img src="https://github.com/user-attachments/assets/3588a468-3a25-4cac-a901-8ba5e0f4f3c9" width="20"><br>**Thin:** <img src="https://github.com/user-attachments/assets/177c1236-f9b2-436e-919c-e9062df5b218" width="20"> <img src="https://github.com/user-attachments/assets/5099a654-2dd6-4956-8175-c930d35ba534" width="20"> <img src="https://github.com/user-attachments/assets/5967e63d-2b94-4cde-bb73-81f631be59f8" width="20"><br></div> | Adds options to display useful overlay buttons in the video player. **Enhanced with accessibility content descriptions, second downloader on long tap, and Gemini/Yandex integration for video summarization and transcription.** | 19.43.41 ~ 19.47.53 |
| `Player components` | - | Adds options to hide or change components related to the video player. | 19.43.41 ~ 19.47.53 |
| `Remove background playback restrictions` | - | Removes restrictions on background playback, including for music and kids videos. | 19.43.41 ~ 19.47.53 |
| `Remove viewer discretion dialog` | - | Adds an option to remove the dialog that appears when opening a video that has been age-restricted by accepting it automatically. This does not bypass the age restriction. | 19.43.41 ~ 19.47.53 |
| `Return YouTube Dislike` | - | Adds an option to show the dislike count of videos using the Return YouTube Dislike API. | 19.43.41 ~ 19.47.53 |
| `Return YouTube Username` | - | Adds an option to replace YouTube handles with usernames in comments using YouTube Data API v3. **Enhanced with ability to export API key (Caution: Do not share with others).** | 19.43.41 ~ 19.47.53 |
| `Sanitize sharing links` | - | Adds an option to sanitize sharing links by removing tracking query parameters. | 19.43.41 ~ 19.47.53 |
| `Seekbar components` | - | Adds options to hide or change components related to the seekbar. **Unique features: Color indicator and color picker, gradient seekbar bounds customization.** | 19.43.41 ~ 19.47.53 |
| `Settings for YouTube` | `insertPosition`: @string/parent_tools_key, @string/general_key, @string/account_switcher_key, @string/data_saving_settings_key, @string/auto_play_key, @string/video_quality_settings_key, @string/offline_key, @string/pair_with_tv_key, @string/history_key, @string/your_data_key, @string/privacy_key, @string/premium_early_access_browse_page_key, @string/subscription_product_setting_key, @string/billing_and_payment_key, @string/notification_key, @string/connected_accounts_browse_page_key, @string/live_chat_key, @string/captions_key, @string/accessibility_settings_key, @string/about_key<br>`rvxSettingsLabel`: ReVanced Extended, RVX<br>`settingsSummaries`: true, false | Applies mandatory patches to implement ReVanced Extended settings into the application. **Enhanced with clickable categories in search results, full path display, improved search indexing, search highlighting, and search history.** | 19.43.41 ~ 19.47.53 |
| `Shorts components` | - | Adds options to hide or change components related to YouTube Shorts. **Enhanced with Gemini video summarization and hide disabled comment button functionality.** | 19.43.41 ~ 19.47.53 |
| `Snack bar components` | `cornerRadius`: 8.0dip<br>`applyCornerRadiusToPlaylistBottomBar`: true, false<br>`darkThemeBackgroundColor`: @color/yt_black3, @android:color/black, #FF181825, #FF290025, #FF001029, #FF002905, #FF282900, #FF291800, #FF290000<br>`lightThemeBackgroundColor`: @color/yt_white3, @android:color/white, #FFE6E9EF, #FFFCCFF3, #FFD1E0FF, #FFCCFFCC, #FFFDFFCC, #FFFFE6CC, #FFFFD6D6<br>`strokeColor`: (empty), ?attr/ytThemedBlue, ?attr/ytChipBackground | Adds options to hide or change components related to the snack bar. | 19.43.41 ~ 19.47.53 |
| `SponsorBlock` | `outlineIcon`: true, false<br>`NewSegmentAlignment`: right, left | Adds options to enable and configure SponsorBlock, which can skip undesired video segments, such as sponsored content. **Enhanced with draggable new segment window and configurable window alignment.** | 19.43.41 ~ 19.47.53 |
| `Spoof app version` | - | Adds options to spoof the YouTube client version. This can be used to restore old UI elements and features. | 19.43.41 ~ 19.47.53 |
| `Spoof streaming data` | `useIOSClient`: true, false | Adds options to spoof the streaming data to allow playback. | 19.43.41 ~ 19.47.53 |
| `Spoof watch history` | - | Adds an option to change the domain of the watch history or check its status. | 19.43.41 ~ 19.47.53 |
| `Swipe controls` | - | Adds options for controlling volume and brightness with swiping, and whether to enter fullscreen when swiping down below the player. **Enhanced with horizontal swipe for playback speed control (bottom half) and video seeking (top half).** | 19.43.41 ~ 19.47.53 |
| `Theme` | `darkThemeBackgroundColor`: @android:color/black, #FF212121, #FF181825, #FF290025, #FF001029, #FF002905, #FF282900, #FF291800, #FF290000<br>`lightThemeBackgroundColor`: @android:color/white, #FFE6E9EF, #FFFCCFF3, #FFD1E0FF, #FFCCFFCC, #FFFDFFCC, #FFFFE6CC, #FFFFD6D6, #FFD4FFF8, #FFD1FFCC, #FFFFE9AA | Changes the app's themes to the values specified in patch options. **Enhanced with unique Pale Blue, Green, and Yellow color variants.** | 19.43.41 ~ 19.47.53 |
| `Toolbar components` | - | Adds options to hide or change components located on the toolbar, such as the search bar, header, and toolbar buttons. | 19.43.41 ~ 19.47.53 |
| `Translations for YouTube` | `customTranslations`: (custom file)<br>`selectedTranslations`: ar, bg-rBG, de-rDE, el-rGR, es-rES, fr-rFR, hu-rHU, id-rID, in, it-rIT, ja-rJP, ko-rKR, pl-rPL, pt-rBR, ru-rRU, tr-rTR, uk-rUA, vi-rVN, zh-rCN, zh-rTW<br>`selectedStringResources`: af, am, ar, ar-rXB, as, az, b+es+419, b+sr+Latn, be, bg, bn, bs, ca, cs, da, de, el, en-rAU, en-rCA, en-rGB, en-rIN, en-rXA, en-rXC, es, es-rUS, et, eu, fa, fi, fr, fr-rCA, gl, gu, hi, hr, hu, hy, id, in, is, it, iw, ja, ka, kk, km, kn, ko, ky, lo, lt, lv, mk, ml, mn, mr, ms, my, nb, ne, nl, no, or, pa, pl, pt, pt-rBR, pt-rPT, ro, ru, si, sk, sl, sq, sr, sv, sw, ta, te, th, tl, tr, uk, ur, uz, vi, zh, zh-rCN, zh-rHK, zh-rTW, zu | Add translations or remove string resources. | 19.43.41 ~ 19.47.53 |
| `Video playback` | - | Adds options to customize settings related to video playback, such as default video quality and playback speed. | 19.43.41 ~ 19.47.53 |
| `Visual preferences icons for YouTube` | `settingsMenuIcon`: custom_branding_icon, extension, gear, yt_alt, revanced, revanced_colored, rvx_letters, rvx_letters_bold<br>`applyToAll`: true, false | Adds icons to specific preferences in the settings. | 19.43.41 ~ 19.47.53 |
</details>

### [📦 `com.google.android.apps.youtube.music`](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music)
<details>

| 💊 Patch | ⚙️ Patch-Options | 📜 Description | 🏹 Target Version |
|:--------:|:---------------:|:--------------:|:-----------------:|
| `Bitrate default value` | - | Sets the audio quality to 'Always High' when you first install the app. | 6.20.51 ~ 8.12.53 |
| `Bypass image region restrictions` | - | Adds an option to use a different host for static images, so that images blocked in some countries can be received. | 6.20.51 ~ 8.12.53 |
| `Certificate spoof` | - | Enables YouTube Music to work with Android Auto by spoofing the YouTube Music certificate. | 6.20.51 ~ 8.12.53 |
| `Change share sheet` | - | Adds an option to change the in-app share sheet to the system share sheet. | 6.20.51 ~ 8.12.53 |
| `Change start page` | - | Adds an option to set which page the app opens in instead of the homepage. | 6.20.51 ~ 8.12.53 |
| `Custom branding icon for YouTube Music` | `appIcon`: afn_blue, afn_red, mmt, mmt_blue, mmt_green, mmt_orange, mmt_pink, mmt_turquoise, mmt_yellow, revancify_blue, revancify_red, vanced_black, vanced_light, xisr_yellow, youtube_music<br>`changeSplashIcon`: true, false<br>`restoreOldSplashIcon`: true, false<br><br>**Visual Preview:**<br><img src="https://github.com/user-attachments/assets/9ec7d708-a3f7-4eca-b0b6-e6eb1588b780" width="25"> <img src="https://github.com/user-attachments/assets/d1044240-d7aa-4c0b-a789-8a7e68630028" width="25"> <img src="https://github.com/user-attachments/assets/7d71e1f4-614c-47e7-be96-ccef5cb8d3a2" width="25"> <img src="https://github.com/user-attachments/assets/095f7ca7-8cef-428b-9ac5-dc3c12ea7288" width="25"> <img src="https://github.com/user-attachments/assets/3d09a5b1-526f-4be9-81c6-5beb28449164" width="25"> <img src="https://github.com/user-attachments/assets/a6045d15-18a4-4475-82e4-aa5300abf0ca" width="25"> <img src="https://github.com/user-attachments/assets/fabf9d34-6437-492f-826c-e0e63f38a018" width="25"> <img src="https://github.com/user-attachments/assets/c041318f-2e93-45b5-82e8-cd77a9f7165f" width="25"> <img src="https://github.com/user-attachments/assets/5b75fec0-50b3-478c-86c9-a08dbb67bfb4" width="25"> <img src="https://github.com/user-attachments/assets/78d74ed7-2a60-4643-86b5-dc9082e961f0" width="25"> <img src="https://github.com/user-attachments/assets/5fd2aa0a-146d-44f1-b04e-516d15f3ad47" width="25"> <img src="https://github.com/user-attachments/assets/3851723f-b1fb-44b1-b324-cdfef9e155ee" width="25"> <img src="https://github.com/user-attachments/assets/aedd4072-fc7f-472a-9570-26687ce6a2a6" width="25"> <img src="https://github.com/user-attachments/assets/676374fc-8114-4e49-bb15-3b5c69a916c0" width="25"><br>*Enhanced with improved metadata cleaning and updated designs* | Changes the YouTube Music app icon to the icon specified in patch options. **Enhanced with custom splash animations and multiple color variants.** | 6.20.51 ~ 8.12.53 |
| `Custom branding name for YouTube Music` | `appNameNotification`: ReVanced Extended Music, RVX Music, YouTube Music, YT Music<br>`appNameLauncher`: ReVanced Extended Music, RVX Music, YouTube Music, YT Music | Changes the YouTube Music app name to the name specified in patch options. | 6.20.51 ~ 8.12.53 |
| `Custom header for YouTube Music` | `customHeader`: custom_branding_icon | Applies a custom header in the top left corner within the app. | 6.20.51 ~ 8.12.53 |
| `Dark theme` | `darkThemeBackgroundColor`: @android:color/black, #FF181825, #FF290025, #FF001029, #FF002905, #FF282900, #FF291800, #FF290000<br>`materialYou`: true, false | Changes the app's dark theme to the values specified in patch options. | 6.20.51 ~ 8.12.53 |
| `Disable Cairo splash animation` | - | Adds an option to disable Cairo splash animation. | 7.06.54 ~ 8.12.53 |
| `Disable DRC audio` | - | Adds an option to disable DRC (Dynamic Range Compression) audio. | 6.20.51 ~ 8.12.53 |
| `Disable QUIC protocol` | - | Adds an option to disable CronetEngine's QUIC protocol. | 6.20.51 ~ 8.12.53 |
| `Disable dislike redirection` | - | Adds an option to disable redirection to the next track when clicking the Dislike button. | 6.20.51 ~ 8.12.53 |
| `Disable forced auto captions` | - | Adds an option to disable captions from being automatically enabled. | 6.20.51 ~ 8.12.53 |
| `Disable music video in album` | - | Adds option to redirect music videos from albums for non-premium users. | 6.20.51 ~ 8.12.53 |
| `Enable OPUS codec` | - | Adds an option to enable the OPUS audio codec if the player response includes it. | 6.20.51 ~ 8.12.53 |
| `Enable debug logging` | - | Adds an option to enable debug logging. | 6.20.51 ~ 8.12.53 |
| `Enable landscape mode` | - | Adds an option to enable landscape mode when rotating the screen on phones. | 6.20.51 ~ 8.12.53 |
| `Flyout menu components` | - | Adds options to hide or change flyout menu components. | 6.20.51 ~ 8.12.53 |
| `GmsCore support` | `gmsCoreVendorGroupId`: app.revanced<br>`checkGmsCore`: true, false<br>`packageNameYouTube`: bill.youtube, anddea.youtube<br>`packageNameYouTubeMusic`: bill.youtube.music, anddea.youtube.music<br>`patchAllManifest`: true, false | Allows patched Google apps to run without root and under a different package name by using GmsCore instead of Google Play Services. **Enhanced with "Don't show again" option for GMSCore battery optimization dialog.** | 6.20.51 ~ 8.12.53 |
| `Hide account components` | - | Adds options to hide components related to the account menu. | 6.20.51 ~ 8.12.53 |
| `Hide action bar components` | - | Adds options to hide action bar components and replace the offline download button with an external download button. | 6.20.51 ~ 8.12.53 |
| `Hide ads` | - | Adds options to hide ads. | 6.20.51 ~ 8.12.53 |
| `Hide layout components` | - | Adds options to hide general layout components. | 6.20.51 ~ 8.12.53 |
| `Hide overlay filter` | - | Removes, at compile time, the dark overlay that appears when player flyout menus are open. | 6.20.51 ~ 8.12.53 |
| `Hide player overlay filter` | - | Removes, at compile time, the dark overlay that appears when single-tapping in the player. | 6.20.51 ~ 8.12.53 |
| `Navigation bar components` | - | Adds options to hide or change components related to the navigation bar. | 6.20.51 ~ 8.12.53 |
| `Player components` | - | Adds options to hide or change components related to the player. | 6.20.51 ~ 8.12.53 |
| `Remove background playback restrictions` | - | Removes restrictions on background playback, including for kids videos. | 6.20.51 ~ 8.12.53 |
| `Remove viewer discretion dialog` | - | Adds an option to remove the dialog that appears when opening a video that has been age-restricted by accepting it automatically. This does not bypass the age restriction. | 6.20.51 ~ 8.12.53 |
| `Restore old style library shelf` | - | Adds an option to return the Library tab to the old style. | 6.20.51 ~ 8.12.53 |
| `Return YouTube Dislike` | - | Adds an option to show the dislike count of songs using the Return YouTube Dislike API. | 6.20.51 ~ 8.12.53 |
| `Return YouTube Username` | - | Adds an option to replace YouTube handles with usernames in comments using YouTube Data API v3. **Enhanced with ability to export API key (Caution: Do not share with others).** | 6.20.51 ~ 8.12.53 |
| `Sanitize sharing links` | - | Adds an option to sanitize sharing links by removing tracking query parameters. | 6.20.51 ~ 8.12.53 |
| `Settings for YouTube Music` | `rvxSettingsLabel`: ReVanced Extended, RVX<br>`settingsSummaries`: true, false | Applies mandatory patches to implement ReVanced Extended settings into the application. **Enhanced with ability to remove summaries/descriptions of RVX settings and improved preferences indexing.** | 6.20.51 ~ 8.12.53 |
| `SponsorBlock` | - | Adds options to enable and configure SponsorBlock, which can skip undesired video segments, such as non-music sections. | 6.20.51 ~ 8.12.53 |
| `Spoof app version` | - | Adds options to spoof the YouTube Music client version. This can be used to restore old UI elements and features. | 6.51.53 ~ 8.10.52 |
| `Spoof player parameter` | - | Adds options to spoof player parameter to allow playback. | 6.20.51 ~ 8.12.53 |
| `Translations for YouTube Music` | `customTranslations`: (custom)<br>`selectedTranslations`: bg-rBG, bn, cs-rCZ, el-rGR, es-rES, fr-rFR, hu-rHU, id-rID, in, it-rIT, ja-rJP, ko-rKR, nl-rNL, pl-rPL, pt-rBR, ro-rRO, ru-rRU, tr-rTR, uk-rUA, vi-rVN, zh-rCN, zh-rTW<br>`selectedStringResources`: (multiple language codes available) | Add translations or remove string resources. | 6.20.51 ~ 8.12.53 |
| `Video playback` | - | Adds options to customize settings related to video playback, such as default video quality and playback speed. | 6.20.51 ~ 8.12.53 |
| `Visual preferences icons for YouTube Music` | `settingsMenuIcon`: custom_branding_icon, extension, gear, yt_alt, revanced, revanced_colored, rvx_letters, rvx_letters_bold<br>`applyToAll`: true, false | Adds icons to specific preferences in the settings. | 6.20.51 ~ 8.12.53 |
| `Watch history` | - | Adds an option to change the domain of the watch history or check its status. | 6.20.51 ~ 8.12.53 |
</details>

### [📦 `com.reddit.frontpage`](https://play.google.com/store/apps/details?id=com.reddit.frontpage)
<details>

| 💊 Patch | ⚙️ Patch-Options | 📜 Description | 🏹 Target Version |
|:--------:|:---------------:|:--------------:|:-----------------:|
| `Change package name` | `packageNameReddit` | Changes the package name for Reddit to the name specified in patch options. | 2024.17.0 ~ 2025.12.1 |
| `Custom branding name for Reddit` | `appName` | Changes the Reddit app name to the name specified in patch options. | 2024.17.0 ~ 2025.12.1 |
| `Disable screenshot popup` | - | Adds an option to disable the popup that appears when taking a screenshot. | 2024.17.0 ~ 2025.12.1 |
| `Hide Recently Visited shelf` | - | Adds an option to hide the Recently Visited shelf in the sidebar. | 2024.17.0 ~ 2025.12.1 |
| `Hide ads` | - | Adds options to hide ads. | 2024.17.0 ~ 2025.12.1 |
| `Hide navigation buttons` | - | Adds options to hide buttons in the navigation bar. | 2024.17.0 ~ 2025.12.1 |
| `Hide recommended communities shelf` | - | Adds an option to hide the recommended communities shelves in subreddits. | 2024.17.0 ~ 2025.12.1 |
| `Open links directly` | - | Adds an option to skip over redirection URLs in external links. | 2024.17.0 ~ 2025.12.1 |
| `Open links externally` | - | Adds an option to always open links in your browser instead of in the in-app-browser. | 2024.17.0 ~ 2025.12.1 |
| `Premium icon` | - | Unlocks premium app icons. | 2024.17.0 ~ 2025.12.1 |
| `Remove subreddit dialog` | - | Adds options to remove the NSFW community warning and notifications suggestion dialogs by dismissing them automatically. | 2024.17.0 ~ 2025.12.1 |
| `Sanitize sharing links` | - | Adds an option to sanitize sharing links by removing tracking query parameters. | 2024.17.0 ~ 2025.12.1 |
| `Settings for Reddit` | `rvxSettingsLabel` | Applies mandatory patches to implement ReVanced Extended settings into the application. | 2024.17.0 ~ 2025.12.1 |
</details>

### [📦 `com.spotify.music`](https://play.google.com/store/apps/details?id=com.spotify.music)
<details>

| 💊 Patch | ⚙️ Patch-Options | 📜 Description | 🏹 Target Version |
|:--------:|:---------------:|:--------------:|:-----------------:|
| `Change lyrics provider` | Changes the lyrics provider to a custom one. | ALL |
| `Custom branding name for Spotify` | Changes the Spotify app name to the name specified in patch options. | ALL |
| `Custom theme` | Applies a custom theme (defaults to amoled black) | ALL |
| `Fix Facebook login` | Fix logging in with Facebook when the app is patched by always opening the login in a web browser window. | ALL |
| `Fix third party launchers widgets` | Fixes Spotify widgets not working in third party launchers, like Nova Launcher. | ALL |
| `Hide Create button` | Hides the "Create" button in the navigation bar. | ALL |
| `Lyrics search` | Displays a "Search Lyrics" panel in the Main Activity that searches for lyrics on Google, and song meanings on Songtell. The activity is set to SpotifyMainActivity, so the "Search Lyrics" panel won't be shown in NowPlayingActivity (Player view) or possibly other activities. | ALL |
| `Sanitize sharing links` | Removes the tracking query parameters from links before they are shared. | ALL |
| `Spoof package info` | Spoofs the package info of the app to fix various functions of the app. | ALL |
| `Unlock Premium` | Unlocks Spotify Premium features. Server-sided features like downloading songs are still locked. | ALL |
</details>



## 📝 JSON Format

This section explains the JSON format for the [patches.json](patches.json) file.

Example:

```json
[
  {
    "name": "Alternative thumbnails",
    "description": "Adds options to replace video thumbnails using the DeArrow API or image captures from the video.",
    "use":true,
    "compatiblePackages": {
      "com.google.android.youtube": [
        "19.43.41",
        "19.44.39",
        "19.47.53"
      ]
    },
    "options": []
  },
  {
    "name": "Bitrate default value",
    "description": "Sets the audio quality to 'Always High' when you first install the app.",
    "use":true,
    "compatiblePackages": {
      "com.google.android.apps.youtube.music": [
        "6.20.51",
        "6.51.53",
        "7.16.53",
        "7.25.53",
        "8.05.51",
        "8.12.53"
      ]
    },
    "options": []
  },
  {
    "name": "Hide ads",
    "description": "Adds options to hide ads.",
    "use":true,
    "compatiblePackages": {
      "com.reddit.frontpage": [
        "2024.17.0",
        "2025.05.1",
        "2025.12.1"
      ]
    },
    "options": []
  }
]
```