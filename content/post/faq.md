+++
authors = [
    "Collabora",
]
title = "FAQ"
date = "2020-09-30"
description = "Frequently Asked Questions"
tags = [
    "contribute",
    "report",
		"test",
]
images = [
    "faq.jpg",
]
+++

Perhaps your question is one that we have been asked before; have a read, and let us know if not.

<!--more-->

## What is Collabora Online anyway ?

Collabora Online is a feature rich online collaboration office suite
with great support for all major document, spreadsheet and
presentation file formats. It is based on LibreOffice and used in
combination with software for managing, sharing, files.

It can be installed on a server that you host yourself, or by a
company of your choice. It is excellent for users and organizations
looking for an office solution in the cloud that protects their
privacy and allows them to keep full control of their sensitive data.

### Who created Collabora Online ?

Collabora Online is mainly created by Collabora. Collabora's 20+
committers provided 95%+ of the commits in the last year. Checkout
our [2020 infographic]("https://www.collaboraoffice.com/community-news/updated-libreoffice-growth-infographic-2020/")
or the [git repository](FIXME)

We built on top of a huge volume of work from both LibreOffice [credits](https://www.libreoffice.org/about-us/credits/),
however the Online functionality was created primarily by Collabora (as [announced in 2015](https://people.gnome.org/~michael/blog/2015-03-25-libreoffice-icewarp.html)) – or for a [detailed story](https://people.gnome.org/~michael/blog/2015-12-15-code.html).

The first integration for ownCloud (and later for Nextcloud) was built
on top of Documents plugin (based on work of Frank Karlitschek and
Victor Dubiniuk) that was renamed to RichDocuments, with a docker
image from Lukas Reschke. Currently we have many more integrations
written by either by Collabora or by Collabora Partners.

### Who contributed to the Mobile work ?

Our mobile app is built on top of our Online / web work. For the story
of those behind that [see here](https://www.collaboraoffice.com/collabora-office-for-android-ios-credits/)
in particular thanks to Adfinis for their investment!

Of note, was the [TDF tender](https://blog.documentfoundation.org/blog/2014/09/04/tender-for-base-framework-for-an-android-version-of-libreoffice-with-basic-editing-capabilities-201409-01/) to build a base framework for editing. This built
on the work Smoose/SUSE/Collabora re-using the Mozilla Java/Fennec renderer for an
Android viewer. You can read the reports
[1](https://www.collaboraoffice.com/wp-content/uploads/2020/09/TDF0002-report-M1.pdf),
[2](https://www.collaboraoffice.com/wp-content/uploads/2020/09/TDF0002-report-M2.pdf)
that list the commits, all of which were to the LibreOffice core; at that time
Online barely existed. It is safe to say that a negligable amount of TDF
donor funded code is present in Online.

### What about translators work ?

Great point! many translators have made a wonderful contribution. While Online
represents only one hundredth of the strings that LibreOffice has, it re-uses
many translations from the core too. We try to extract translators names to
[credit their hard work]({{< relref "translate.md#Credits" >}}), which is much
appreciated.

## Why is Collabora Online its own project ?

Back in 2015 Collabora started the online development on TDF's
infrastructure as a source-only project: a place to collaborate around
development, with own-branded products versions derived from that.

Gradually pressure built to change this, and there were very long discussions
around some [serious problems](https://lwn.net/Articles/825602/) with the
new board, staff, wider community in 2020. During these discussions it became
clear that we could provide the stability and confidence needed to invest
longer term in improving the software most simply by moving Collabora
Online to its own project.

We believe that doing this also removes the need for a number of
unpleasant compromises and inter-company conflict that put strain
on TDF. It also follows the well known pattern of many other successful
FOSS companies: RedHat/Fedora, openSUSE, Samba+, ownCloud, Nextcloud,
RocketChat, Mattermost, BigBlueButton, and others beyond number.

### Is this the first separate project round this code ?

It seems not; this turns out to be reasonably common. Checkout
[OSSIIs](https://github.com/OSSII/oxool-community) [version](https://www.ossii.com.tw/product/online).
Or [Zimbra Docs](https://www.zimbra.com/email-server-software/zimbra-docs/)
(with no contributions back), and there are other examples.
Clearly having a team of engineers with wide experience, who contribute
to the code behind the version you choose is important.

### Do we need investment ?

Volunteers have always contributed to FOSS projects, LibreOffice is no
exception, and we would love you to get involved and help out improving
the code with us. Professional developers bring the ability to contribute
huge amounts of feature/function work, mentoring, and the depth of focus
necessary to tackle the hardest issues: improving interoperability,
performance, memory consumption, latency - as well as building new UX
infrastructure and adding product polish - we're far from done.

Donations have also been a helpful revenue stream for TDF, however the
size of our investment need is sufficiently large that TDF's
donation cash-flow cannot meet it.

If you'd like a detailed explanation of some of the problems see: [vendor neutral
marketing](https://people.gnome.org/~michael/data/vendor-neutral-marketing.html)
complete with pictures.

### Does investment mean Venture Capital ?

In a nutshell no. Collabora is a FOSS company focused on a mission of
making FOSS rock, we have no plans to dilute our mission that way.
Against that we cannot spend money we do not earn, there
is no money fairy (TINMF), so Return on Investment (RoI) is important
to us as we invest. No-one should put their life savings in a bank
with a highly uncertain reputation for re-paying.


### Did you try to work things out with TDF ?

Indeed, from [2013](https://people.gnome.org/~michael/data/2013-09-25-economics.pdf)
it has been clear that we need to work to build the ecoystem around
LibreOffice. Many papers have been written since, presented, long
blogs, lengthy conversations through many conferences, board meetings.
Large, rambling discussions in the community have done nothing to
build confidence.

Against that there have been some positives, a visionary plan
from Italo for example; but against much resistance.

### Why is branding & visibility important ?

In large part for marketing. By investing in OSS - you can get your
brand widely known, that's really important when someone wants support
or services, or a custom version of the product.

	"No one expects it to be easy to make money in free
	software. While making money with free software is a
	challenge, the challenge is not necessarily greater than with
	proprietary software. In fact you make money in free software
	exactly the same way you do it in proprietary software: by
	building a great product, marketing it with skill and
	imagination, looking after your customers, and thereby
	building a brand that stands for quality and customer
	service." - Bob Young (founder of RedHat)

FOSS companies have very few assets: our code is all public, but we
can build brands that reflect the time & excellence we put into our
software, and use these to create a distinction that commands a price.

Unfortunately, investing in a brand you do not own, and leading people
to an environment where end-users / casual purchasers are extremely
unlikely to discover that the work was done by you - makes things
very difficult.

### Which brand to choose ?

Customers have been confused in the past by branding, seeing
LibreOffice/TDF as the authentic source for Online. The use and
licensing of that brand has also been a cause for concern.

We all know well the annoyance or injustice of using a misleading
brand, or one that doesn't acknowledge those doing the work. The
LibreOffice users who call it OpenOffice by mistake, and of course
for years the GNU/Linux campaign to try to get fair representation
of the GNU project's work.

In more recent times we have several examples
[1](https://github.com/owncloud/richdocuments/issues/277),
[2](https://github.com/nextcloud/richdocuments/issues/639),
[3](https://github.com/learnweb/moodle-mod_collabora/issues/16)
of attempts to change the branding on code written by others.


## A Free / Open Source project

We are committed to becoming a best-of-breed Free / Open Source
project. We start from a great place with the LibreOffice
heritage of license and general ethos, and we plan to build on
that, to make CODE a fun project to develop on. Clearly we
respect and recognize the contribution of all the developers of
LibreOffice and will honor that in equivalent access.

### Can I re-compile and re-distribute CODE ?

Yes, you'll need to follow the
[build instructions]({{< relref "build-code.md" >}}), as well
as the FIXME: LICENSE and for now if you're modifying it significantly
you'll want to use your own brand name to make it clear that you are
standing behind that, and to avoid creating confusion around its origin.
That is easy to do using various configure options.

If you contribute significantly back to CODE we would love to work
with you to credit, help and promote your contribution, we look
forward to working with you. We will work to more explicitly open
up our (small) pieces of proprietary theming / branding / CSS over
time.

### How do I get a say in the project ?

We love to work with sharp people, to write FOSS, and to listen to
them. We will try to attract and energise a community of do-ers, and
include them into our decision making over time.

We will try to keep commercial rivalry out in the marketplace
where it belongs, and keep the project focused on developing new
feature / function.

We also have a Partner Council that includes those partners and
customers who through their sales &amp; evangelism efforts have
contributed significantly to development, and we expect to expand this
over time.

### Is there the forum for questions and discussions ?

You are welcome on the [Collabora Online forum](https://forum.collaboraonline.com/)!


{{< css.inline >}}
<style>
.canon { background: white; width: 100%; height: auto;}
</style>
{{< /css.inline >}}