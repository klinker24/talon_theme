# Talon Example Theme

This theme is just an example of what you can do with the theme engine for Talon, the whole process is fairly straightforward.

<p>Steps to creating a custom Talon theme:</p>
<ol>
<li>Rename the package name in the AndroidManifest.xml file to whatever you want, it just needs to be different from what I have and what others have done, you can't install the same package multiple times on a device (common practice is something like com.lastname.android.talon_theme_name)</li>
<li>Edit each of the meta-data attributes defined in the AndroidManifest.xml to whatever you want for your theme, any combination of any of them should work fine</li>
<li>Change the icon.png file to whatever you want in each of the drawable folders (mdpi, hdpi, xhdpi and xxhdpi). It will show up when selecting the themes in Talon</li>
<li>Add nine-patch resources for the different background types (selected and unselected) and any other icons that you wish to change</li>
<li>Edit the layout xml filse to match how you want them to look. You can basically do whatever you want here as long as you don't remove any of the components I have. I have made some comments on some that you should be aware of</li>
<li>Edit the text colors defined in the colors resource file</li>
<li>Add the EditText background of your choosing. If one isn't found in your theme, it will default to holo orange. I would suggest looking here to get them: http://android-holo-colors.com/</li>
<li>Compile the app and install it on your phone</li>
<li>Set the theme in the Theme Settings section of Talon</li>
<li>Fix any problems with the theme and make it look perfect</li>
<li>Put it up on the Google+ community for everyone to enjoy! https://plus.google.com/u/0/communities/112468199526946242218/stream/c2f77fd2-23f2-4cb5-923e-6bb748fbcb69</li>
</ol>

<p>For information on creating 9-patch files: http://radleymarx.com/blog/simple-guide-to-9-patch/</p>

<p>Pretty much anything can be done with these themes. For now, these are the only elements that are possible to change and it may stay that way. There really isn't much left other than the drawer, but that is never going to be themeable.</p>

<p>You will NOT be able to configure the app's accent color with this theme engine. It will stay orange. That isn't something that I can read from a package and place into the app on the fly. So, please, <b>DO NOT</b> ask me about this. The answer will be no and I am not afraid to tell you that, even if you don't like my answer. You have been warned!</p>

---

Don't hesitate to contact me if you have any questions!

Email: luke@klinkerapps.com

---

## License

    Copyright 2014 Luke Klinker

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
