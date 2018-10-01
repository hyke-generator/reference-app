# Hike reference app

### Guide
In order to make changes [react-native-template-hike](https://github.com/lklacar/react-native-template-hike), follow this guide:

- Add your changes here
- Make sure your feature works
- Ensure your changes don't include anything they should not and make sure your commit does NOT include the patch file
- Commit your changes here
- Make sure your commit is merged to master
- Generate patch file from your last commit
```bash
    git format-patch -1 HEAD
```
- Apply your patch in [react-native-template-hike](https://github.com/lklacar/react-native-template-hike)
```bash
    git apply --stat file.patch
    git apply --check file.patch
    git am < file.patch
```
- Make sure your patch did not do anything stupid
- Make sure you don't commit your patch
- Commit & push to [react-native-template-hike](https://github.com/lklacar/react-native-template-hike)