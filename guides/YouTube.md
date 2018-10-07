# The Rust YouTube Channel Maintenance Guide

## Help Wanted

We need your help! Even just doing one or two playlists would be awesome. If you are working on something, comment below so we know you are doing it. Check the comments before starting on anything.

**Follow the guides below to learn how to do these tasks.**

- [ ] Add videos to [Web Development](https://www.youtube.com/playlist?list=PL85XCvVPmGQhB5ym7ylsVXTpbo1DIHt9c)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [ ] Add videos to [Embedded/Low Level Programming](https://www.youtube.com/playlist?list=PL85XCvVPmGQg8xuBO6Lrr4dfcooP7Er-B)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [ ] Add videos to [Code Design/Architecture](https://www.youtube.com/playlist?list=PL85XCvVPmGQiEn7es4pHisSjFqbt2sYC0)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [ ] Add videos to [Concurrency and Parallelism](https://www.youtube.com/playlist?list=PL85XCvVPmGQgxwe46ip2gqaMi8iqcEXJ_)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [ ] Add videos to [Testing](https://www.youtube.com/playlist?list=PL85XCvVPmGQjlqnfIgYhzJQ-WpJU06uuZ)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [x] Add videos to [Macros](https://www.youtube.com/playlist?list=PL85XCvVPmGQixaIh-t5arXD0jlpXxSqHC)
    * Follow the guides below to learn how to do this
    * Use any existing videos as well as the title of the video to determine which videos belong
    * Make sure the playlist is public once you've gone through and added videos at least once
- [ ] Put descriptive titles on the meetup videos so people know what the video is actually about
    * Keep the original title, but prefix it with a descriptive title so it both describes what it's about and that it's from a meetup

I'll add any additional playlists that get created but aren't populated to this list. Just let me know in the comments below.

**In addition to these tasks, you can also help by:**

* Suggesting new category playlists for the videos
    * Aim for categories that are distinct from the ones that are already playlists
    * Look for topics that Rust programmers are interested in that videos already exist for on the channel
    * Examples: "Web Development", "Embedded/Low Level Programming", "Concurrency and Parallelism"
      All of these are distinct categories and all of them have videos we can add from the Rust channel
* Suggesting videos that should be added to the existing category playlists (including the ones that aren't listed in the tasks above)
    * The category playlists aren't perfect and are probably still missing quite a few videos
    * You can help us by finding videos we missed and either adding them or commenting to let us know that they should be added to a particular playlist
* Finding duplicates or miscategorized videos
    * Mistakes happen, help us by pointing out where we accidentally added a video more than once or where we added a video to a playlist where it really shouldn't belong
    * For miscategorization: As long as the main topic of the video fits in a playlist, it's okay. We're really looking for mistakes like "you put [Florian's Inline Assembly talk](https://www.youtube.com/watch?v=7Mzl2HA3TuU) in the Web Development playlist". Florian's talk doesn't directly deal with web development, so it probably shouldn't be in that playlist.
    * This isn't a perfect science. Use your judgement.

All playlists: https://www.youtube.com/channel/UCaYhcUwRBNscFNUKTjgPFiA/playlists

## How to help organize videos into playlists

The following is a guide for anyone wanting to help out. If anyone knows of better ways or wants to help improve this process, please don't hesitate to leave a comment.

### Prerequisites

* If you are not a member already, get yourself added to the YouTube channel so you can help out
* Have a modern browser on a desktop computer (do not do this from your phone/tablet app)

### Creating a new category playlist

This may seem like a lot of steps, but once you do it once you'll see that it's actually just a few actions written in a lot of detail.

1. Make sure you have selected the Rust YouTube account
    a. Click on your picture in the top right corner of the YouTube website
    b. You will either see an option to "Switch account" or see a list of accounts if you are already in Creator Studio
    c. Switch to the Rust account
2. Go to: https://www.youtube.com/view_all_playlists (Creator Studio > Video Manager > Playlists)
3. Click "New playlist" at the top of the list of playlists
4. Enter the playlist title -- try to write a clear title that accurately describes the category of videos that it will contain
5. Set the playlist to **Private** before creating it by clicking on the dropdown list with the word "Public" and selecting "Private" from the options that appear
    * Set the playlist to public after you've had a chance to go through and add videos to it at least once (see next section)
6. Once you click "Create", you should be taken to a page that shows your playlist
7. Click the big "Edit" button next to the channel name
8. Click "Add description"
9. **Optional:** If you think it would be helpful, add a sentence or two clarifying the kinds of videos that should be added to this playlist. This is only necessary if the playlist name is not self explanatory. Example:
    > Videos of Rust being used in companies/in production. Advice for other people/organizations looking to do so as well.
10. Add the following to the bottom of the playlist description separated from the rest by an empty line:
    > Do you know of a video that should be on this playlist that we missed? Please open an issue on https://github.com/rust-community/team and let us know!
11. To save the description, click somewhere outside of its field
12. Click on "Playlist settings"
13. Under "ORDERING", select "Date published (newest)"
    * This makes it so that even if we add older videos that we find later to the playlist, everything will stay in a reasonable, sorted order
14. Click "Save". Something should show up on the playlist page to indicate the sorting
    > This playlist is automatically sorted by date published.
15. You are now ready to add videos to this playlist. See the next section for how to do that!

### Adding videos to an existing playlist

These instructions specifically cover adding videos that are uploaded to the Rust channel. Videos from other sources that are relevant can be added as well.

1. See the previous section for instructions about selecting the Rust YouTube account
2. Make sure you are on the Edit page for the playlist you want to add videos to
    a. You will know you've reached the right page when you see "Add videos" in the top right corner just above the list of videos
    b. If you don't see that, you may just have to click "Edit"
    c. If there is no edit button, follow these instructions:
    d. Go to: https://www.youtube.com/view_all_playlists (Creator Studio > Video Manager > Playlists)
    e. Click on the playlist you want to add videos to
    f. Click "Edit"
3. Click "Add videos" -- button should be in the top right corner of the list of videos
    ![screenshot from 2017-09-01 11-52-15](https://user-images.githubusercontent.com/530939/29981718-0aee2206-8f0c-11e7-9491-e556b1b0b17f.png)
4. If you have a specific URL or video that you want to add, use the other tabs in the popup to add that video
5. Otherwise, if you are helping with the bulk categorization of the existing videos, click on the "Your YouTube videos" tab
6. Go through the list of videos, read each title, and if it belongs in the playlist, click on it
7. Click "Add videos" once you finish going through all of the videos
8. Scroll through the playlist and look for duplicates. Thanks to the sorting applied when creating the playlist, any duplicates should be right beside each other in the playlist
9. If the playlist is still private, make it public by clicking on "Playlist settings", selecting "Public" from the options under "Playlist Privacy" and then clicking "Save"
