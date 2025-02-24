---
title: Using MobileSheets for sheet music on Android tablets
date: 2025-02-24
lang: en
lang-ref: mobile-sheets # Also create a directory for this in _data/comments. Throws error otherwise. Add empty file there to propagate on Github as well, then remove again.
tags: android tablet bladmuziek technologie klassiekemuziek howto review 
# Run tag_generator.py for every new blog post!
published: true
tootId: 114060735046433954
---

<figure class="fr-ns w-20-ns br3 ma1 ba b--light-gray">
  	<img src="https://lh3.googleusercontent.com/NzG7u3_0xrBfYdx-_ddIZn9x8VFv5oBtOuMsgpWIZJ8vqB8pWUIUeIMcl-9saY8-N0o=s180" alt="MobileSheets" class="br3 br--top">
  	<figcaption class="tc caption f7">MobileSheets</figcaption>
</figure>

<div class="flex items-center justify-center pa4 bg-lightest-blue navy">
  <svg class="w3-ns w4" data-icon="info" viewBox="0 0 32 32" style="fill:currentcolor">
    <title>info icon</title>
    <path d="M16 0 A16 16 0 0 1 16 32 A16 16 0 0 1 16 0 M19 15 L13 15 L13 26 L19 26 z M16 6 A3 3 0 0 0 16 12 A3 3 0 0 0 16 6"></path>
  </svg>
  <span class="lh-title ml3">This is a translation of a blog post from 2019 on my website. Most of the information should hold up today, but some of the content might be outdated.</span>
</div>

In the past year, I've tried out various Android apps for sheet music. (Apple's iOS may have more choices, but [I'm not a fan of Apple](https://stallman.org/apple.html).) My favourite among them was [MobileSheets](https://play.google.com/store/apps/details?id=com.zubersoft.mobilesheetspro), which also has a free trial version available [here](https://play.google.com/store/apps/details?id=com.zubersoft.mobilesheetsfree). There's a [manual](https://www.zubersoft.com/mobilesheets/manual.html), but it can be a bit overwhelming. In this blog post, I'll show you which options are most relevant for classical music.

The three main features that make MobileSheets my favourite app:

1. [Automatic cropping of page margins](#margessnijden) of sheet music
2. [Reference points](#linkpoints) for quickly handling repeats or *da capos*
3. [Concert mode](#concertstand) that temporarily disables all menus

<div class="flex items-center justify-center pa4 bg-lightest-blue navy">
  <svg class="w3-ns w4" data-icon="info" viewBox="0 0 32 32" style="fill:currentcolor">
    <title>info icon</title>
    <path d="M16 0 A16 16 0 0 1 16 32 A16 16 0 0 1 16 0 M19 15 L13 15 L13 26 L19 26 z M16 6 A3 3 0 0 0 16 12 A3 3 0 0 0 16 6"></path>
  </svg>
  <span class="lh-title ml3">Note: MobileSheets is intended for the more serious musician who is willing to put in some practice with the app. If you're just looking for simple display of your sheet music without too much fuss, check out <a href="#andereApps">my list of other apps</a> at the bottom of this blog post.</span>
</div>

## Music Library

When you open the app, you'll first need to grant permission for the app to access your files. Press yes here.

<figure class="fr-ns w-50-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/welkomstvraag.jpg">
<img src="/images/blog/2019/welkomstvraag.jpg" alt="Welcome question" class="br3 br--top"></a>
A very technical question in Dutch about having Mobilesheets manage where imported files are stored.
</figure>
The app then asks a complicated question (see image). The easiest thing to do is press "yes." This takes up more disk space, but ultimately makes it easier to keep track of any annotations you make.

You'll then see the music library: an overview of all the sheet music you've imported. Right now, everything will be empty.

<figure class="br3 ma1 ba b--light-gray caption tc f7 mw5">
<a href="/images/blog/2019/openingsscherm.png">
    <img src="/images/blog/2019/openingsscherm.png" alt="Opening screen" class="br3 br--top"></a>
    An empty library welcomes you.
</figure>

<section class="mw5 mw7-ns center bg-lightest-blue pa3 ph5-ns navy pa5-l pa5-m">
  <h1 class="mt0">Tip</h1>
  <p class="lh-copy measure-wide">
    You can import multiple sheet music files at once with MobileSheets, but it's better to use a file explorer to import the files you want to open one by one, as you need them. This allows you to ensure that all information is filled in correctly and that the margin cropping is successful.
    </p>
</section>
<figure class="fr-ns w-40-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/instellingenknop.jpg">
    <img src="/images/blog/2019/instellingenknop.jpg" alt="Settings button" class="br3 br--top"></a>
    The hiding place of the settings button. (Text in Dutch, but should be in the same place in English.)
</figure>

### Tabs <a name="tabbladen"></a>

The library is initially filled with tabs that are unnecessary for classical musicians. This is easy to adjust and makes for a library that's much easier to navigate. For classical music, you really only need a tab with composers and possibly a tab with music titles. A tab with recently opened files is a handy third tab. (And honestly my most used tab by far.)

To do this, press the three dots stacked on top of each other in the top right corner, and go to "Library settings". Here you'll find a large number of settings. Read through them carefully so you know the options are there. Also, try out some things; for example, I can recommend the dark theme, and for classical composers, characters don't need to be "normalized."

<figure class="fr-ns w-30-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/titelopmaak.jpg">
    <img src="/images/blog/2019/titelopmaak.jpg" alt="Title formatting" class="br3 br--top"></a>
    This way, the composer's name is always at the front of the library.
</figure>

Specific settings that are useful for classical music can be found under the "Piece Title Formatting" button. I would recommend setting this as in the image to the right.

Then press "Tab Selection and Order". Here, I can recommend the tabs as in the image below. The rest of the tabs might be more interesting for pop musicians, but not very relevant for most classical music.

**Update 2025: These days I also use the "Setlists" tab.**

<figure class="br3 ma1 ba b--light-gray caption tc f7 mw5">
<a href="/images/blog/2019/tabvolgorde.jpg">
    <img src="/images/blog/2019/tabvolgorde.jpg" alt="Tab order" class="br3 br--top"></a>
    These three tabs are sufficient for most classical musicians.
</figure>

## Other Settings

Don't be intimidated by all the buttons: the MobileSheets settings are well worth a small time investment to be able to set everything to your liking. An overview of the most relevant options per tab of the settings:

- **Storage:** Here you can set up Dropbox and Google Drive, among other things.
- **Display settings:** The default settings here are good, but I turned off the page-turning animation here to be able to see the next page faster in the heat of the battle.
- **Import settings:** Here I enabled aggressive cropping. The less margin, the better on a small screen. What do you need whitespace for on a tablet?
  <figure class="fr-ns w-40-ns br3 ma1 ba b--light-gray caption tc f7">
  <a href="/images/blog/2019/aanraakacties.jpg">
      <img src="/images/blog/2019/aanraakacties.jpg" alt="Touch actions" class="br3 br--top"></a>
      This way, most touch areas simply turn the page.
  </figure>
- **Touch and pedal settings:** <a name="aanraakacties"></a> Here are options for Bluetooth pedals. I haven't used this myself yet. It's useful to look at the "Touch Actions." The screen can be roughly divided into a grid (see [later in this blog post](#aanraakgebieden)). With these options, you can set what each of the cells of the grid do when you press them. I recommend the settings in the image.
- **Text file settings:** Especially relevant for people who play (guitar) tabs, whose "sheet music" is often in text files.
- **MIDI settings:** I haven't used this yet and it's probably more relevant for pop musicians.
- **Backup and restore:** Can come in handy if you're going to buy a new tablet at some point.
- **Other settings:** Read through these to see what's possible. I recommend disabling the Audio Player in "Performance Mode" so you're less likely to suddenly play audio during a concert.

<figure class="fr-ns w-30-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/importeren.jpg">
  	<img src="/images/blog/2019/importeren.jpg" alt="Muziek_importeren" class="br3 br--top"></a>
  	Press "Import to MobileSheets".
</figure>

## Viewing Sheet Music

Once the settings are optimized for classical music, it's time to import your first piece of sheet music. As an example, I downloaded a [piano reduction of the St. Matthew Passion](<https://imslp.org/wiki/Matth%C3%A4uspassion%2C_BWV_244_(Bach%2C_Johann_Sebastian)#tabScore3>) from [IMSLP](https://imslp.org).

When you import the file, you'll come to a screen where you can edit the file before it's added to your library. In this blog post, I'll cover the "Fields" and "Files" tabs; in a future post, I'll show you how to link an MP3 file to your sheet music to help with studying.

<div class="pa5-ns"></div>

<figure class="fr-ns w-50-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/bestanden.jpg">
    <img src="/images/blog/2019/bestanden.jpg" alt="Files tab" class="br3"></a>
</figure>

### "Files" Tab

At the top of the screen, you'll see the files that belong to this piece of music. Usually, there's only one file here, as now. If the piece of music consists of multiple separate images or PDF files, you can add them with the buttons on the right. This should be fairly self-explanatory. If not, see the [manual](https://www.zubersoft.com/mobilesheets/MobileSheetsPro.pdf).

<a name="margessnijden"></a>In the bottom left of the screen is the option to rotate all pages or only the page currently displayed. In the bottom right is the most powerful feature of the app: **automatic cropping of page margins**, which allows the sheet music to be displayed as large as possible on your tablet screen. You can do this per page by pressing the <img src="/images/blog/2019/crop.svg" alt="Crop icon" class="h1"> icon, or you can press "automatic crop," and the app will do it for you.

If the automatic cropping was inadvertently too enthusiastic, causing notes to fall off the page, you can always return to this screen to make manual adjustments.

### "Fields" Tab

<figure class="fr-ns w-50-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/veldenIngevuld.jpg">
    <img src="/images/blog/2019/veldenIngevuld.jpg" alt="Fields filled" class="br3"></a>
</figure>

On this page, you can fill in the so-called meta-information of the piece of music. By default, many fields are enabled that you can fill in, but I have disabled all fields except "Composers." Do this by pressing "Set fields" at the top of the screen and unchecking all boxes except the one for "composers." Or not, of course, if you find certain fields useful! (In that case, you'll probably want to restore the corresponding tab in the [library](#tabbladen).)

Now press OK at the top, and your library will have its first piece of music.

<figure class="w-30-ns br3 ma1 ba b--light-gray caption tc f7 center">
<a href="/images/blog/2019/tabvolgorde.jpg">
    <img src="/images/blog/2019/tabvolgorde.jpg" alt="Tab order" class="br3 br--top"></a>
    It can of course happen that you want to sort your music by genre if you have a very large library. Or you can create a "Custom group" for instrumentation.
</figure>

## Displaying Sheet Music and Making Annotations

Open a piece of sheet music by pressing it in the library.

<figure class="fr-ns w-40-ns br3 ma1 ba b--light-gray caption tc f7">
<a href="/images/blog/2019/paginaAanraakgebieden.jpg">
    <img src="/images/blog/2019/paginaAanraakgebieden.jpg" alt="Touch areas" class="br3 br--top"></a>
     The sheet music screen is divided into an invisible grid of touch areas with three rows and three columns.
</figure>

<a name="aanraakgebieden"></a>
The screen is divided into nine invisible "touch areas." You set these in the ["touch actions"](#aanraakacties) in the settings. If you follow my settings there, you'll get the following effects:

1. Previous page
2. Previous page
3. Previous page
4. Show overlay screen
5. Show overlay screen
6. Make annotations
7. Next page
8. Next page
9. "Quick action box"

Once you understand these touch areas, it make navigation much easier. The **overlay screen**, the **annotation screen**, and the **"Quick action box"** are the three navigation screens you want to master to work quickly during rehearsals and concerts.

### Overlay Screen

The overlay screen is accessed by pressing box 4 or 5, and disappears again when you press 4 or 5 again.

A brief description of the most important buttons:

<section class="cf w-100 pa2-ns">
  <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
    <div class="aspect-ratio aspect-ratio--1x1">
    <a href="/images/blog/2019/knopjesLinksboven.jpg" class="ph2 ph0-ns pb3 link db">
      <img style="background-image:url(/images/blog/2019/knopjesLinksboven.jpg);"
      class="db bg-center cover aspect-ratio--object" /></a>
    </div>
      <h3 class="f6 f5 fw4 mt2 black-60">From left to right:
          <ul>
  <li>Return to library</li>
  <li>Write notes about the piece. You can display these on the screen every time you open the file</li>
  <li>Open the annotation screen</li>
  <li>Reopen the screen where you can adjust margin cropping and meta-information</li>
</ul></h3>

  </article>
  <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
    <div class="aspect-ratio aspect-ratio--1x1">
    <a href="/images/blog/2019/menuLinksonder.jpg" class="ph2 ph0-ns pb3 link db">
      <img style="background-image:url(/images/blog/2019/menuLinksonder.jpg);"
      class="db bg-center cover aspect-ratio--object" /></a>
    </div>
      <h3 class="f6 f5 fw4 mt2 black-60">These options are largely self-explanatory. A "Snippet" allows you to clip a part of the sheet music into a PDF file with only those pages.<br> There is also an auto-scroll function in the app that automatically slides the music to the next page at a set tempo.</h3>
  </article>
    <article class="fl w-100 w-50-m  w-third-ns pa2-ns pb7-l">
    <div class="aspect-ratio aspect-ratio--1x1">
    <a href="/images/blog/2019/weergavemenu.jpg" class="ph2 ph0-ns pb3 link db">
      <img style="background-image:url(/images/blog/2019/weergavemenu.jpg);"
      class="db bg-center cover aspect-ratio--object" /></a>
    </div>
      <h3 class="f6 f5 fw4 mt2 black-60">Allows you to quickly crop the margins of the current page, display a clock on the sheet music, and more.</h3>
  </article>
    <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
    <div class="aspect-ratio aspect-ratio--1x1">
    <a href="/images/blog/2019/schuifknopje.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/schuifknopje.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">Perhaps useful for very large scores: this allows you to set whether you can move the image on the page by rubbing your finger over it. If the entire page is already displayed, this button does nothing.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/scherminstelling.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/scherminstelling.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60"><img src="/images/blog/2019/displayMode.png" alt="Crop icon" class="h1">-button. Settings for the display of the sheet music on the screen. The default settings are fine for most sheet music. <br>
                  <b>Tip:</b> Set the screen setting to "Vertical scrolling." If you've cropped your margins tight enough, you can usually see a bit of the next page on your screen, which can be quite handy.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns pb7-l pb0-m">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/paginazoommodus.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/paginazoommodus.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60"><img src="/images/blog/2019/pageScaling.png" alt="Crop icon" class="h1">-button. If you have a small tablet, it may be useful to choose "Fit to width" here, which can help with readability.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/afspeellijst.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/afspeellijst.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">This allows you to create a "setlist" of a concert if you want to be able to quickly switch between pieces in the correct order.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns pb0-m">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="//images/blog/2019/bladwijzers.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/bladwijzers.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">Go to the page for which you want to create a bookmark and press + to create a bookmark. If your PDF file already had bookmarks, they will be displayed here automatically.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/linkpoint.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/linkpoint.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60"><a name="linkpoints"></a>A handy advanced feature: if your piece of music has a repeat (da capo, dal segno...), you can use this to create a so-called "Link." Press +, then on the spot where "da capo" or something similar is...</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns pb0-l pb0-m">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/linkpointEnd.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/linkpointEnd.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">...and then on the spot where you want to go back to. Colored circles (the Links) appear on the page, allowing you to immediately go to the repeat spot.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/linkpointGrootte.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/linkpointGrootte.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">Hold a reference point in the list to adjust the size of the circles in the sheet music.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns pb0-m">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/smartButtons.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/smartButtons.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">Similar to reference points are the *smart buttons*. However, these do something with MIDI, which classical musicians usually don't have much to do with.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/geluidsspeler.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/geluidsspeler.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">This allows you to play a sound file that is linked to the sheet music. I will discuss this further in a later blog post.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/metronoom.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/metronoom.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">There is a metronome built into the app. Handy. A small piano would also be handy for us singers, but unfortunately, that's not there.</h3>
          </article>
            <article class="fl w-100 w-50-m  w-third-ns pa2-ns">
            <div class="aspect-ratio aspect-ratio--1x1">
            <a href="/images/blog/2019/settings.jpg" class="ph2 ph0-ns pb3 link db">
              <img style="background-image:url(/images/blog/2019/settings.jpg);"
              class="db bg-center cover aspect-ratio--object" /></a>
            </div>
              <h3 class="f6 f5 fw4 mt2 black-60">Finally, this allows you to quickly go to the app's settings.</h3>
          </article>
        </section>

### "Quick Action Box"

<figure class="fr-ns w-30-ns br3 ma1 ba b--light-gray caption tc f7">
  <a href="/images/blog/2019/snelleActiebox.jpg">
      <img src="/images/blog/2019/snelleActiebox.jpg" alt="Quick action box" class="br3 br--top"></a>
      This was translated into Dutch quite clunkily, which is why I usually leave my apps in English.
  </figure>

Catchy name, isn't it? Here are a number of buttons that are also in the overlay screen, which the app's developer thought would be used the most.

<a name="concertstand"></a>The middle button is not found in the overlay screen: this is for **concert mode**. This is a kind of safety mode: all [touch areas](#aanraakgebieden) of the screen are disabled except for the "Quick action box" in the bottom right, so you don't accidentally open some menu during a concert when you want to turn the page. Touching the screen now always ensures that you go to the next or previous page. The concert mode button can also be found in the library.

### Annotations

<figure class="fr-ns w-30-ns br3 ma1 ba b--light-gray caption tc f7">
  <a href="/images/blog/2019/aantekeningen.jpg">
      <img src="/images/blog/2019/aantekeningen.jpg" alt="Annotations" class="br3 br--top"></a>
      Having fun scribbling.
  </figure>

<div class="flex items-center justify-center pa4 bg-lightest-blue navy">
  <svg class="w3-ns w4" data-icon="info" viewBox="0 0 32 32" style="fill:currentcolor">
    <title>info icon</title>
    <path d="M16 0 A16 16 0 0 1 16 32 A16 16 0 0 1 16 0 M19 15 L13 15 L13 26 L19 26 z M16 6 A3 3 0 0 0 16 12 A3 3 0 0 0 16 6"></path>
  </svg>
  <span class="lh-title ml3">Update 2025: This looks a bit different today. But most of the actual options are still the same, if in a different place.</span>
</div>


The annotation mode is quite self-explanatory. The "undo" button is in the top left, so go ahead and experiment. A few tips:

- The pen and highlighter settings I use are a good start, but see what works best for you.
- "Smooth mode" tries to make your annotations less angular but usually results in less precision. Not usually recommended.
- Everything is already set correctly in the menu at the top left. Two remarks:
  - Stylus mode is intended for an ["active" stylus](/posts/Android-tablets-klassieke-musicus#stylus). This does not work with a normal "passive" stylus.
  - Auto-save when changing pages is recommended. If you quickly scroll through the file while annotating with the buttons at the top right, you can easily accidentally press the cancel button next to it.
- With the arrows in this box, you can precisely move the annotation you just made: <img src="/images/blog/2019/zweefknop.jpg" alt="Crop icon" class="h3">
- Also see the tip in my other blog post: [zoom in](/posts/Android-tablets-klassieke-musicus#tipZoomen) before you start writing.
- By tapping your screen with two fingers at the same time, you can quickly switch between pen/highlighter and "move mode." Very handy if you're zoomed in and want to make an annotation on another part of the screen.

<div class="center">
  <div class="cf ph2-ns">
    <div class="fl w-100 w-50-ns pa2">
      <figure class="br3 ba b--light-gray caption tc f7">
    <a href="/images/blog/2019/peninstellingen.jpg">
      <img src="/images/blog/2019/peninstellingen.jpg" alt="Pen settings" class="br3 br--top"></a>
      My pen settings.
  </figure>
    </div>
    <div class="fl w-100 w-50-ns pa2">
      <figure class="br3 ba b--light-gray caption tc f7">
    <a href="/images/blog/2019/markeerinstellingen.jpg">
      <img src="/images/blog/2019/markeerinstellingen.jpg" alt="Highlighter settings" class="br3 br--top"></a>
      My highlighter settings.
  </figure>
  </div>
  </div>
</div>

## Other Apps <a name="andereApps"></a>

In addition to MobileSheets, there are also a number of other apps for sheet music. Below is a brief list with some observations.

<main class="mw6 center">
  <article>
    <a class="link dt w-100 bb b--black-10 pb2 mt2 dim blue" href="https://play.google.com/store/apps/details?id=com.sheet.music">
      <div class="dtc w3">
        <img src="https://lh3.googleusercontent.com/S2KmttgTsUiiBQ63Ck6c8MkAJX8ZZLi6GMDZ_dsZPVJACoweQSvTMMyaiEtMUbHutW4=s180"/>
      </div>
      <div class="dtc v-top pl2">
        <h1 class="f6 f5-ns fw6 lh-title black mv0">My Sheet Music</h1>
        <h2 class="f6 fw4 mt2 mb0 black-60">App intended for viewing sheet music on your smartphone, not on a tablet. If possible, you should avoid this entire scenario, but in emergencies, this app can provide a solution. <b>Seems to be discontinued in 2025.</b></h2>
        <dl class="mt2 f6">
          <dt class="clip">Price</dt>
          <dd class="ml0">€2.99</dd>
        </dl>
      </div>
    </a>
  </article>
  <article>
    <a class="link dt w-100 bb b--black-10 pb2 mt2 dim blue" href="https://play.google.com/store/apps/details?id=com.gramercy.orpheus">
      <div class="dtc w3">
        <img src="https://lh3.googleusercontent.com/KcP3zOJQuxlO53DU3Bg9niDb3ziJi95mfz1fA4J4BBLmZGE1Yapy0G6EMKu_tZ39C4Y=s180" class="db w-100"/>
      </div>
      <div class="dtc v-top pl2">
        <h1 class="f6 f5-ns fw6 lh-title black mv0">Orpheus Sheet Music PRO</h1>
        <h2 class="f6 fw4 mt2 mb0 black-60">Also has a free version. Simpler than MobileSheets and with a less active developer. In its simplicity, it also lacks many features that MobileSheets does have. Although this app is cheaper, it adds little to a simple PDF viewer for that money. <b>Not updated for more than a year in 2025</b></h2>
        <dl class="mt2 f6">
          <dt class="clip">Price</dt>
          <dd class="ml0">€7.49</dd>
        </dl>
      </div>
    </a>
  </article>
  <article>
    <a class="link dt w-100 bb b--black-10 pb2 mt2 dim blue" href="https://play.google.com/store/apps/details?id=com.ryanlothian.sheetmusic">
      <div class="dtc w3">
        <img src="https://lh3.googleusercontent.com/CiF7eYJeXYctpfIyuAqAaLvISHFZQUMgs-MP0Udq3FE1dHjQ4duwNcmS8Phoo00R8iTq=s180" class="db w-100"/>
      </div>
      <div class="dtc v-top pl2"><h1 class="f6 f5-ns fw6 lh-title black mv0">Sheet Music</h1>
        <h2 class="f6 fw4 mt2 mb0 black-60">Very simple app with no support for annotations. Free, so worth considering in that regard, but you're better off using a free PDF viewer that does support annotations.</h2>
        <dl class="mt2 f6">
          <dt class="clip">Price</dt>
          <dd class="ml0">Free</dd>
        </dl>
      </div>
    </a>
  </article>
  <article>
    <a class="link dt w-100 bb b--black-10 pb2 mt2 dim blue" href="https://play.google.com/store/apps/details?id=com.adobe.reader">
      <div class="dtc w3">
        <img src="https://lh3.googleusercontent.com/oUukRV8x9WR5J68u9pAxzbDoesBqT3lvdsEip-c0RnsNnO9f-qcqmddWzl6AFuYDMbA=s180" class="db w-100"/>
      </div>
      <div class="dtc v-top pl2">
        <h1 class="f6 f5-ns fw6 lh-title black mv0">Adobe Acrobat Reader</h1>
        <h2 class="f6 fw4 mt2 mb0 black-60">Not specifically intended for sheet music, but if you don't want to pay for your apps, this might be your best choice. Supports annotations, tapping to go to the next page, and other handy tricks.</h2>
        <dl class="mt2 f6">
          <dt class="clip">Price</dt>
          <dd class="ml0">Free</dd>
        </dl>
      </div>
    </a>
  </article>
</main>

In addition, you have a number of apps that belong to a specific sheet music website, such as [MuseScore](https://play.google.com/store/apps/details?id=com.musescore.playerlite), [Virtual Sheet Music](https://play.google.com/store/apps/details?id=com.virtualsheetmusic.vsheetmusic), and [IMSLP Browser](https://play.google.com/store/apps/details?id=com.imslp.app). These are less well-maintained and also only support sheet music from their own source. There are also all kinds of apps that allow you to photograph sheet music to have it played by the app. These types of apps are more gimmicks and not particularly suitable for displaying sheet music.

Do you use another app for sheet music that you are satisfied with, or have I forgotten any handy features of MobileSheets? Let me know in the comments!