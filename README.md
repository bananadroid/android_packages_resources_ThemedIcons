# ThemedIcons

This repo contains the resources required to add Themed icons in your Launcher. The idea of this repo is having the essential resources and support for the greatest amount of apps available. 

### Adding it to your launcher

For implementing this icon pack, you'll need to add the following commit for Launcher3:
[Launcher3 Add support for themed icons](https://github.com/bananadroid/android_packages_apps_Launcher3/commit/78deaf9ae22d02dddb39aec3870248a9f4cfe37d)
After that, you need to add the following entry to your manifest, and modify the destination if you're not using Launcher3. 
```
  <project path="packages/resources/ThemedIcons" name="bananadroid/android_packages_resources_ThemedIcons" remote="github" revision="13">
    <linkfile src="res" dest="packages/apps/Launcher3/res-icons" />
  </project>
```
Once you've done that, you're ready to go.
### Feedback, issues and submitting icons

If you want to report an issue, or you want some of the icons removed from the project, please let us know by opening an issue. We'll willing to work to solve any issues. 
If you want to submit your icons, send us a pull request. We suggest that the icons are done in a vector drawable format for better scaling and lighter app sizes.

### Credits for the resources
- The Google team
- TheScarastic
- Project-404
- Project Streak
- CipherOS
- SimpleIcons.org
- TeamFiles
