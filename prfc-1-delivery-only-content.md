**Summary**

This [PRFC](https://github.com/exmosis/prfc-0-prfcs/blob/master/prfc-0.md) sets out a simple spec for digital (+ potentially physical) content that does not encourage casual browsing by having a home page, or any kind of archive. *Delivery-only content* focuses on subscription-based models, primarily (but not exclusively) through email, RSS, and physical post.

**Meta**

Authors: @[6loss](https://twitter.com/6loss)<br>
Version: Draft v0.1.0<br>
URL: TBA<br>

**Background**

As the internet reaches truly ubiquitous proportions, there is a growing collective awareness that information is not just in the background continnually, but also our foreground. We spend our lives tailoring the information we publish, and collecting/filtering the information that everyone else publishes. We have become curators foremost, and inherently also marketeers, intent on 'selling' our updates and information in return for attention and status. In a blind sea of never-ending media, we find ourselves shouting ever louder, leaving constant signposts for people to follow, and hoping that the breadcrumbs we leave will be picked up by *something*, but whether it is people or bots or algorithms, we no longer know.

Among this sea of content, a tiny voice nags us that it is not enough, and will *never* be enough. Content changes to quickly. Merely dumping information into a particular space and waiting for it to be discovered is like publishing to a graveyard. The echo chamber is a boundary to itself.

**Aims**

Delivery-only content aims to redefine our interaction with content, and move away from the fire-and-hope mentality of the "publish to everyone" model, and towards a richer, "publish to those interested" approach.

It seeks to re-introduce a sense of *mystery* and arcane, almost esoteric access to information. It seeks to thrive off parallel network lines of interest - to exploit the rich interpersonal links we form through shared objectives, rather than random browsing. It aims to be *exclusive* rather than *inclusive*, to be "closed" rather than open, in order to revel in the deeper relationships that exist along such lines.

It aims to act fully within the realms of "permissioned" content - that is, content that receivers have indicated they are interested in *in advance*, for reasons other than the content itself. There is an inherent element of risk-taking here, of course. This risk is all part of the adventure.

Alongside all of this, there is a counterpart attitude that the content delivered should include only content that is interesting. Subsidiary and side-effect payloads, such as advertising, metadata, and site navigation all distract and detract from the content itself. Delivery-only content focuses on this core aspect of "only what is neededto be known", in order to enrich the receiver's experience of consuming information.

**Spec**

Delivery-only content should adhere fairly closely to the following objectives and methods. Naturally, truly "targeted" and otherwise closed content can be difficult - eg. it is difficult to fully hide RSS feeds. However, as long as general principles adhering to the Aims above are followed, everything should be fine.

Two main over-arching principles emerge from the Aims above:

1. Content should aim to *only go to people that have requested it*.
2. Content should be as *minimal as needed*.

The three initial primary delivery models that can be addressed and adopted easily are:

1. E-mail subscription. Clearly the internet has a long history of this, in terms of mailing lists. Modern common methods include mailing list software such as [mailman](http://www.list.org/) and [ezmlm](https://cr.yp.to/ezmlm.html), or services such as [Mailchimp](http://mailchimp.com/) and [TinyLetter](https://tinyletter.com/)
2. RSS/Atom subscription. 
3. Snail mail. Yes, real post.

Clearly these are all fairly common these days, although may be under threat by other commercial interests attempting to replace with more private, tracked options.

**More importantly**, the delivery-only model must **avoid** the casual browsing of previous content, eg through archive pages. Archives should either be not kept in the first place (beyond what is needed for any delivery model above), or should be hidden without access.

Ideally, where content has multiple delivery models, the same core content should be made available via both, simultaneously, so that receivers can choose the medium most appropriate for them. This may not always be possible though. Clarity on what is available is always useful.

**Questions**

* What other delivery options might exist?

**Resources**



