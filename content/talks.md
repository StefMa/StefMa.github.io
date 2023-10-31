---
title: Talks
sidebar: false
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: false # or false to display the footer
---

{{% title4 "From hundred (86) to zero (7). How we publish 67 Android apps in under 7 minutes." %}}

Given at Mobile DevOps Summit 2023

Imagine being able to publish 67 Android white-labeled-apps in under 7 minutes. It may seem like an impossible feat, but our team has turned this into a reality.

Since 2017, we have committed ourselves to a rigorous publishing schedule, releasing our apps every two weeks without fail. This relentless dedication has taught us valuable lessons about the importance of investing in our release pipeline and continuously improving it.

In this talk, we will share the secrets behind our remarkable achievement and delve into the strategies and tools that have enabled us to streamline the publishing process.

3 key takeaways from this session: 
1. Continuously investing into your release pipeline is critical for your success
2. Sometimes it is not obvious which changes require more attention
3. ...

(Slides available at [Speaker Deck](https://speakerdeck.com/stefma/from-hundred-86-to-zero-7-how-we-publish-67-android-apps-in-under-7-minutes))

</br>

{{% title4 "A guide through publishing white label apps in a healthy way" %}}

Given at Mobile DevOps Summit 2022

Publishing and releasing one Android app is easy.

But what if you have to publish 5 apps, or 10, or even 50?

You have to start thinking about the build time on your continuous delivery server to build all of those apps. You have to think about how to roll them out in a comfortable way. You have to think about your architecture and a lot more...

We are at ioki creating white label apps and have, as of today, 38 apps public in the Play Store.

In this talk, I will guide you through the challenges we had to publish more and more apps over the years in a healthy way. I will show you what we did - release process-wise as well as code architecture-wise - to scale further to stay in this healthy environment we have today.

Takeaways from this session:
1. A reliable continues delivery server is important
2. Architecture is important when you publish multiple apps
3. What does it mean to growth in a healthy way

(Slides available at [Speaker Deck](https://speakerdeck.com/stefma/a-guide-through-publishing-white-label-apps-in-a-healthy-way))

{{< youtube id="IpbgBtDRC1k" >}}

</br>

{{% title4 "How to write a Gradle Plugin (in Kotlin)" %}}

Given at Droidcon Italy 2018

Every Android Developer is familiar with Gradle, right?</br>
We know how to apply a plugin, how to setup the Android extension and how to declare our dependencies.

But from where does the Android extension come from?</br>
Which settings are possible here?</br>
How can a task use these information to run a specific action?

I'll explain all the Gradle magic by showing how to write a Gradle plugin.</br>
The plugin will be pretty simple and straightforward but shows you what Gradle does behind the scenes.

Naturally we will write the plugin in Kotlin.</br>
We will also cover a little bit about Gradle's Kotlin DSL.

Basically you will leave my talk knowing the basics of the Gradle plugin development:
* How can I declare my own task?
* How can I declare my own extension?
* How can I test my plugin?

(Slides available at [Speaker Deck](https://speakerdeck.com/stefma/how-to-write-gradle-plugins-in-kotlin))

{{< youtube id="NK4-n6uQA0g" >}}