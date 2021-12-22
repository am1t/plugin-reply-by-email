# ✍️ Reply by email for Micro.blog

Hey, fellow microblogger! 👋

This is super duper alpha and lacks decent documentation, for now. But it's actually a working plug-in that you can install manually and test.

To get updates on this project, [follow @sod on Micro.blog](https://micro.blog/sod).

## Get started with the alpha

These instructions will be a lot easier to follow shortly. Bear with me.

### Install the plug-in

1. Sign in to https://micro.blog in your favorite browser.

2. [Follow this link](https://micro.blog/account/themes/new?plugin=1) or manually go to *Design* → *Edit Custom Themes* and press *New Plug-in*.

3. Enter a fitting *Title* (like Reply by mail).

4. Enter `https://github.com/svendahlstrand/plugin-reply-by-email` inside *Clone URL*.

5. Choose which *Site* you want to install the plug-in on.

6. Press *Add Plug-in*

7. Congratulations, the plug-in is installed. On to configuration.

### Configure the plug-in

1. Go to *Plug-ins* and press ⚙️ Settings (for the Reply by email plug-in).

2. Fill your address in *Reply by email*.

3. Make other changes as you see fit.

4. Press *Update Settings* and go to the next step.

### Include the Reply by email link in your custom theme

For this step, you need to set up a custom theme. Maybe you already have one? If not, [follow Manton's instructions here](https://help.micro.blog/t/custom-themes/59).

1. [Follow this link](https://micro.blog/account/themes) or go to *Design* → *Edit Custom Themes*.

2. Click on your custom theme. (It's probably named Marfa Custom or something like that.)

3. Click on the template `layouts/post/single.html`

4. Add this partial call where you see fit: `{{ partial "reply-by-email.html" . }}`. A good place is after the content (look for `{{ .Content }}` in the template).

5. Press *Update Template* and pat yourself on the back.

### Make sure the Reply by email link shows up

1. Find a post on your blog and make sure you see the *Reply by email* link.

2. Click it, make sure it works like expected.

### Having troubles?

If you know how the developer console work in your browser, *Enable debug console* under the plug-in settings. It may help you while troubleshooting.

Feel free to [reach out to @sod on Micro.blog](https://micro.blog/sod) for additional help.
