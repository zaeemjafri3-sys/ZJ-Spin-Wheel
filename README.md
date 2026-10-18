# ZJ Spin Wheel

A customizable **spin-the-wheel app for Android**, built with Flutter and Dart. Companies and individuals can brand it with their own logo, define their own rewards, and run a spin campaign with exact win limits, all on-device with no internet needed.

<p align="center">
  <img src="demo/demo.gif" width="260" alt="App demo">
  <br>
  <sub><a href="demo/demo.mp4">Watch the demo video</a></sub>
</p>

## Features

- **Custom branding**: add your logo from the gallery or camera, as a full image or an automatic subject cutout (PNG).
- **Campaign setup**: set the total number of spins and 3 to 10 rewards.
- **Per-reward control**: name, image, maximum number of wins, and an optional custom win message for every reward.
- **Exact win limits**: a reward can never be won more than its configured maximum.
- **Non-winning option**: choose "Better Luck Next Time" or "Try Again" (default image, your own image, or text only) for when spins outnumber available wins.
- **Wheel review**: preview the wheel, drag to reorder sections, and pick colours from a multi-shade palette.
- **Spin button colour and background**: default, solid colour, or picture, applied to the dashboard, password and spin screens.
- **Dark and light mode**.
- **Password protection**: the name and password are locked after setup, a password is required to spin, and resetting the app requires the password.
- **Local storage**: all data is saved in a local JSON file.

## How it works

1. **Identity setup**: enter the person or organisation name, a password, and an optional logo. These cannot be changed later.
2. **Campaign setup**: choose total spins, number of rewards, and the non-winning option, then fill in each reward.
3. **Wheel review**: arrange sections, colours, spin button colour and background, then confirm. Settings are locked after confirmation.
4. **Dashboard**: shows the logo, the spins remaining, and the SPIN button.
5. **Spin**: enter the password, spin the wheel, and see the result. The spins remaining count goes down after each spin.

## Screenshots

### 1. Identity setup
| <img src="screenshots/01_setup.png" width="160"><br><sub>Identity setup</sub> | <img src="screenshots/02_logo_picker.png" width="160"><br><sub>Logo source</sub> | <img src="screenshots/03_logo_mode.png" width="160"><br><sub>Full image or cutout</sub> | <img src="screenshots/04_logo_selected.png" width="160"><br><sub>Logo selected</sub> |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/05_cutout_preview.png" width="160"><br><sub>Cutout preview</sub> | <img src="screenshots/06_setup_filled_dark.png" width="160"><br><sub>Setup (dark)</sub> | <img src="screenshots/07_setup_filled_light.png" width="160"><br><sub>Setup (light)</sub> |

### 2. Campaign setup
| <img src="screenshots/08_campaign_setup.png" width="160"><br><sub>Campaign setup</sub> | <img src="screenshots/09_non_winning_option.png" width="160"><br><sub>Non-winning option</sub> | <img src="screenshots/10_choose_image_dialog.png" width="160"><br><sub>Choose loss image</sub> | <img src="screenshots/11_reward_cards.png" width="160"><br><sub>Reward cards</sub> |
| :---: | :---: | :---: | :---: |

### 3. Wheel review
| <img src="screenshots/12_wheel_review.png" width="160"><br><sub>Wheel review</sub> | <img src="screenshots/13_wheel_review_settings.png" width="160"><br><sub>Review settings</sub> | <img src="screenshots/14_custom_colors.png" width="160"><br><sub>Custom colours</sub> | <img src="screenshots/15_spin_button_color.png" width="160"><br><sub>Spin button colour</sub> |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/16_shade_picker.png" width="160"><br><sub>Shade picker</sub> | <img src="screenshots/17_background_picture.png" width="160"><br><sub>Background picture</sub> | <img src="screenshots/18_confirm_lock.png" width="160"><br><sub>Confirm and lock</sub> |

### 4. Dashboard and spin
| <img src="screenshots/19_dashboard.png" width="160"><br><sub>Dashboard</sub> | <img src="screenshots/21_spin_password.png" width="160"><br><sub>Spin password</sub> | <img src="screenshots/22_wheel_ready.png" width="160"><br><sub>Wheel ready</sub> | <img src="screenshots/23_wheel_spinning.png" width="160"><br><sub>Spinning</sub> |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/24_result_win.png" width="160"><br><sub>Win result</sub> | <img src="screenshots/25_dashboard_updated.png" width="160"><br><sub>Spins updated</sub> | <img src="screenshots/20_reset_app.png" width="160"><br><sub>Reset app</sub> |

## Tech stack

- Flutter / Dart (Android)
- Local JSON storage
- On-device ML Kit subject segmentation for logo and reward cutouts

## Download and install

1. Download **`app-release.apk`** from this repository (or from the [Releases](../../releases) page).
2. Copy it to your Android phone, or download it directly on the phone.
3. Open the file and tap **Install**. If Android asks, allow installs from this source (Settings > Install unknown apps).
4. Open **ZJ Spin Wheel** and follow the setup screens.

**Requirements:** an Android phone. The app works fully offline.

> Only the compiled release APK is published here. The source code is not included in this repository.
