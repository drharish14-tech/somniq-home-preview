# LIVE: https://drharish14-tech.github.io/somniq-home-preview/android-fixboard/

# Somniq Android fix board — deploy

## Live URL
https://drharish14-tech.github.io/somniq-home-preview/android-fixboard/

Hosted via GitHub Pages on public repo `drharish14-tech/somniq-home-preview`
(path `/android-fixboard/`).

## Local source
`/workspace/android/parity/fixboard/` (index.html + images/)

## Status (5 Nov 2026 IST)
- Build C Home (c-robo-26 / scrolled) = WRONG TARGET (empty AWAITING / NO DATA), not Fixed.
- Target = signature Home Build 67 (`images/target-home-build67.jpg` from `morning-mobile-top.png`).
- Home code port in progress; **no new APK until Harish says yes**.

## Update flow
```
cp -a /workspace/android/parity/fixboard/. /workspace/somniq-home-preview/android-fixboard/
cd /workspace/somniq-home-preview && git add android-fixboard && git commit -m "Update fixboard" && git push
```
