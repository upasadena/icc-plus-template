# ICC Plus 2 - GitHub Template
A template to easily host Interactive CYOAs on GitHub.

> [!WARNING]  
> May break very easily, considering to download the latest Viewer it just
> downloads the latest zip that doesn't have 'local' in the name. Therefore,
> if wahaha303 stops uploading viewers there or uses a different format, it
> could break upon update, so you will have to host it manually.

Features:

* Automatically fetches the latest viewed from the ICCPlus2's GitHub page
* Automatic GitHub workflow to republish your site on any change

View the text instructions [below](#instructions) or
[watch the video tutorial](https://www.youtube.com/watch?v=LCvOVB8wZQE).

## Instructions

### Sign up

1. First, [create an account](https://github.com/signup) on GitHub

### Create the repository

1. Press the bright green **Use this template** button at the top of this repo
2. Press **Create a new repository**
3. Give your repository a name, this will be the folder that will be used to
   access your CYOA
4. Press **Create repository**

> [!IMPORTANT]
> Don't worry if it errors here, it's doing so because you haven't enabled
> Pages, but we'll do that in the step below. After you do that and upload
> your `project.json` if it still errors THEN, *then* you should be worried.

### Enable GitHub Pages

1. Go into **Settings** → **Pages** and where it says **Build and deployment**
   look for the **Source** dropdown menu. Select **GitHub Actions**

### Uploading your files

1. Press the **Add file** dropdown → **Upload files**
2. Upload your `project.json` (and `images/` if appropriate)

---

That should be all! After a short time (usually ~12s) it should now
automatically begin hosting at `https://YOURUSERNAME.github.io/REPONAME`.

Feel free to remove this file and `LICENSE` to clean up the code even more.

### Video tutorial
Press the thumbnail below to open the video. You may need to open in a new tab
so as to not replace this window.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=LCvOVB8wZQE" target="_blank">
 <img src="http://img.youtube.com/vi/LCvOVB8wZQE/maxresdefault.jpg" alt="Watch the video" width="720" height="405" border="10" />
</a>

## More stuff

### Add the URL to the repository for ease of access
1. Press the settings gear to the right of the **About** section title and
   below the **Star** button.
2. Tick **Use your GitHub Pages website**

Your URL should now display!

### Manually republish without pushing
If you want to republish without adding or modifying files, simply go into the
**Actions** tab → select **Deploy static content to Pages** on the left side →
**Run workflow** → and **Run workflow** again.

### Other styles
To do the CSS stuff mentioned in the Features above, edit your `index.html` and
find the `<style>` section. There will be comments that describe each style.

### Manually do this
If you want to manually do this, check out the **GitHub** section of the ICCT:
[https://icctutorial.pages.dev/publishing/github/][icct-gh]

[icct-gh]: https://icctutorial.pages.dev/publishing/github/

## Acknowledgements

* Thanks to `wahaha303` for the awesome ICCPlus!
* Thanks to `u/ridler7` for bringing a bug to my attention

<!-- BUFFER -->
