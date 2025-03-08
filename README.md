# fivethirtyeight-podcast-archive

Fans of the old fivethirtyeight politics podcast may notice that the podcast feed only goes back to 2023, as it only contains the most recent 200 episodes.

I have constructed a RSS feed that contains nearly all the episodes (4 are missing, see nerd stuff below) which is available at: <Github Raw RSS> . Copy and paste that URL into your favorite podcatcher, and enjoy. I recommend downloading the whole feed if it is even of slight interest in case ABC/Disney stop hosting the files.

You will need to use a podcatcher that allows you to enter a custom RSS feed URL.  Spotify in particular will not support this. I've had luck with this method with the following (but more should work):

* iOS, MacOS: Overcast
* Android: Antennapod, PocketCasts
* Windows: FluentCast, AudioBookShelf
* Linux, NAS servers: AudioBookShelf

If you have trouble figuring out what to do with that link, reply to this post and I'll try to help. Generally googling "<Your Podcast Player> + add url manually" will get you some proper instructions though. If you are viewing this in the far future and the links are dead, rest assured the files are safe and backed up even if we can't share them anymore.

___


For more technical discussion, this is a follow up to my earlier post on the subject. That post was admittedly very technical, as I was rushing to get something up in case ABC/Disney pulled the files. Thankfully that didn't happen.

The core issue here is that 538's podcast feed only has 200 entries, which only goes back to 2023. I used the internet archive to find as many old RSS feeds as possible, and merged their entries together. However, some of the links to .mp3 files within were to old links hosted by ESPN - those went dead when 538 was moved under ABC (or so I suspect). Thankfully they reuploaded the old episodes to the new megaphone host, so I swapped out the old dead links for the new megaphone links.

The IA didn't have any RSS feeds for the earliest 14 episodes or so. For those I constructed entries that reflected the metadata as best I could, and then added them to the feed at the start.

Unfortunately, it seems whoever was migrating the old podcasts to from ESPN to megaphone made a handful of mistakes. A few podcasts erroneously linked to the wrong episode (creating a false duplicate) or were never updated. In some instances I found an archived copy at the Internet Archive or an extant .mp3 link on podchaser, but I could not locate the following episodes:

1. "A Primary Night For Both Parties To Be Happy About" published on Jun. 6, 2018, with the filename "fivethirtyeightpolitics_2018-06-06-143238.64k.mp3"

2. "Trump Meets Kim" published on Jun. 11, 2018, with the filename "fivethirtyeightpolitics_2018-06-11-171921.64k.mp3"

3. "Who Are Democrats Nominating?" published on Aug. 13, 2018, with the filename "fivethirtyeightpolitics_2018-08-13-150634.64k.mp3"

If anybody has an old copy of any of those episodes in a personal archive, or knows who I could reach out to at ABC/Disney who could reupload them (other than the listed email address in the RSS feed), I would be very grateful for your reply.
