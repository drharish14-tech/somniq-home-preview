# LIVE: https://drharish14-tech.github.io/somniq-home-preview/android-fixboard/

# Somniq Android fix board — deploy

## Live URL
https://drharish14-tech.github.io/somniq-home-preview/android-fixboard/

Hosted via existing GitHub Pages on public repo `drharish14-tech/somniq-home-preview`
(path `/android-fixboard/`). Site size ~960KB.

## Local source
`/workspace/android/parity/fixboard/` (index.html + images/)

## Firebase Hosting (optional alternative)
Project: `somniq-bb1fd` (Spark). Needs interactive `firebase login` or a CI token.
From this folder:
```
npx firebase-tools@latest init hosting   # public: ., single-page: N
npx firebase-tools@latest deploy --only hosting --project somniq-bb1fd
```
Blocker without browser login: no `FIREBASE_TOKEN` / `login:ci` on this box.

## Update flow
Replace files under `/workspace/android/parity/fixboard/`, then:
```
cp -a /workspace/android/parity/fixboard/. /tmp/somniq-home-preview/android-fixboard/
cd /tmp/somniq-home-preview && git add android-fixboard && git commit -m "Update fixboard" && git push
```
