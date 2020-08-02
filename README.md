# rednoise-stick

While it seems clear that temperatures are increasing, and that mankind's carbon emissions
probably has something to do with this, some of the science seems dodgy to me. One of those
dodgy things is the "hocky stick" graphs showing stable temperatures followed by an abrupt
rise in the last 70 years. I suspect it's not that *data* that produces the hocky stick
shape, but the *methodology*. This project proves that this is possible -- not that it 
actually happened, only that it was possible.


## Some methodology

We have a fairly good record of recent temperatures, especially since we've been putting
statellites in space that can measure the temperature of roughly the entire planet. Going
back further in time, we need to *reconstruct* temperatures based on *proxies* for those
temperatures. This means observing old things that might vary by temperature.

One proxy is tree rings. In cold years, trees grow slower, and the rings are closer
together. In warm years, trees grow faster, and the rings are wider. Not all trees are
useful here, but those in marginal areas, like the tops of mountains, or the artic circle,
can show big swings based primarily on temperature.

This can go back a long time, even beyond the age of the trees. We can look at old cabins
built hundreds of years ago from chopped down wood and integrate those rings into our
models.

Tree rings are the most famous proxies, but there are a long list of other potential
candidates, such as sediments in lakes, pollen, ice cores from glaciers, and so on.
Any natural or biological process is a candidate. Even human activities are candidates,
when climate change causes civilizations to change.

Whether a proxy accurately reflects temperature is a theory. We may think it's valid
when in fact it's not.

One way of testing a proxy is whether it matches the known temperature record over the
last 50 to 70 years. In the last decades, we have a more accurate knowledge of surface
temperatures from thermometers. Better yet, we have a fairly good record going back
approximately 40 years from satellite measurements that measure the entire planet's
surface temperature.

Once we have a set of proven good proxies, we can then cast them back in time to reconstruct
historic temperatures.

This sounds like a good way of reconstructing historic temperatures, but it's not. It's
a fallacy. This methodlogy, as I've described it, always produces a hocky stick.

The purpose of this project is to demonstrate why it's a fallacy using code you can
run within your browser.

This fallacy is known by climate scientists, so this isn't some new criticism here. They
claim to have worked around the problem. They may be right. The purpose of this project
isn't to debate whether their actual methodology is sound, but only to show that its
possible for unsound methodology to consistently produce hocky stick graphs, even if
that's not what the actual data would produce.


## The demonstration

This project contains an HTML file [rednoise.html](../../blob/master/rednoise.html) containing JavaScript that draws the picture.

The algorithm is this.

  1. We first start with a *known record* of increasing temperatures going back 70 years.
  2. We then generate *random walk* records going back 1000 years. Each record is completely random.
  3. We then select for *valid records*, defined as those that closely match the known records.
  4. We then average all the valid records together to produce a graph.

This produces a result that looks something like the following:

![redstick](/redstick.png)

Each time you refresh the page, it'll generate a new random graph. Each time you do this, you'll
produce a hocky stick.

This is not the methodology climate scientists use. The point is simply to show that results
can be due to methodology. The essential similarity is that the validity of a lot of climate
proxies is measured by how well they match the known climate record of recent times.

![hockeystick](/hockeystick.jpg)

