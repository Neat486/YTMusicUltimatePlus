# YTMusicUltimatePlus
The best tweak for the YouTube Music on iOS.

## How to build a YTMusicUltimatePlus IPA using Github Actions

If this is your first time here, start from step 1. If you built a YTMU+ IPA before, skip steps 1 and 2. Instead, click on the "Sync fork" button to get the latest version of the tweak and continue through step 3.

1. Fork this repository using the fork button on the top right.
2. On your forked repository, go to Repository Settings > Actions, enable Read and Write permissions.
3. Go to the Actions tab on your forked repo, click on "Build YTMusicUltimatePlus IPA" located on the left side. Click "Run workflow" button located on the right side.
4. Find a decrypted YTMusic .ipa file (I cannot provide you this due to legal reasons.) and upload it to a file provider(filebin.net or catbox.moe is recommended). Paste the url to the necessary field and click "Run workflow".
5. Wait for the build to finish. You can download the tweaked IPA from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the url. i.e github.com/user/YTMusicUltimatePlus/releases)

## IPA building troubleshooting (I can't build the IPA/Github Actions fails/I can't find the releases section etc.)

99.9% of the time, the culprit is the IPA URL you provided. You HAVE TO provide a decryped IPA. It cannot be any other extension, it has to be a **.ipa** file. Find a decrypted YTMusic IPA (I can't help you with that.), upload it to filebin.net or catbox.moe, give the direct link to the GitHub Actions. If you find a working ipa and upload it properly, everything will start working perfectly, pinky promise.

If the github action works and you cannot find where you can download the result, you need to add /releases to the url of your forked repository. It'll probably look like this: https://github.com/YOURUSERNAME/YTMusicUltimatePlus/releases, don't forget to replace the YOURUSERNAME part with your username. It may seem invisible but if the github action is successful, IPA will be there.
