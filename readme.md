# [Symfony Live - London 2014](http://london2014.live.symfony.com/) talks

- All talks are in **english**.
- Comment and rate talks on [joind.in](http://joind.in/event/view/2120)

## Keynote: Understanding Craftsmanship

[Slides](http://www.slideshare.net/marcello.duarte/understanding-craftsmanship)  
~~Video~~  

By [Marcello Duarte](https://connect.sensiolabs.com/profile/md)  
![github](icon/github.png) [@MarcelloDuarte](https://github.com/MarcelloDuarte)  
![twitter](icon/twitter.png) [@_md](https://twitter.com/_md)  

---

## The Dependency Trap

<dl>
  <dt>Description</dt>
  <dd>A framework, by definition, provides a basic set of tools to use for application development to avoid writing repeatable code. It often encourages us to take shortcuts to enable rapid development. In theory, we only need to implement the part which is specific to our domain. In practice, we often end up with highly coupled code, mixed layers and a dependency graph deceptively close to spaghetti. This talk is going back to basics to remind you what software coupling is and when to consider it good or bad. The presentation will also demonstrate a few techniques on how to write applications that embrace change in a Symfony environment.</dd>
</dl>

[Slides](https://speakerdeck.com/jakzal/the-dependency-trap)  
[Video](http://youtu.be/eJ8qlLS1kUs)

By [Jakub Zalas](https://connect.sensiolabs.com/profile/jakubzalas)  
![github](icon/github.png) [@jakzal](https://github.com/jakzal)  
![twitter](icon/twitter.png) [@jakub_zalas](https://twitter.com/jakub_zalas)  

---

## Optimising Your Front End Workflow

<dl>
  <dt>Description</dt>
  <dd>We take great care in our back end coding workflow, optimising, automating and abstracting as much as is possible. So why don't we do that with our front end code? In this session, we'll take a look at some tools to help us take our front end workflow to the next level, and hopefully optimise our load times in the process! We'll be looking at using Twig templates and optimising them for the different areas of your application, integrating Bower and Gulp for managing assets and processing our front end code to avoid repetitive tasks - looking at how that impacts the typical Symfony workflow.</dd>
</dl>

[Slides](http://slideshare.net/mdavis1982/optimising-your-front-end-workflow-with-symfony-twig-bower-and-gulp)  
[Video](http://youtu.be/qs8b-zBZVxE)

By [Matthew Davis](https://connect.sensiolabs.com/profile/mdavis1982)  
![github](icon/github.png) [@mdavis1982](https://github.com/mdavis1982)  
![twitter](icon/twitter.png) [@mdavis1982](https://twitter.com/mdavis1982)  

---

## The Naked Bundle

<dl>
  <dt>Description</dt>
  <dd> The Bundle system is one of the greatest and most powerful features of Symfony2. Bundles contain all the files related to a single feature of your application: controllers, entities, event listeners, form types, Twig templates, etc. But how much of that actually needs to be inside a bundle? In this talk we\u2019ll take a bundle, containing all those different types of classes, configuration files and templates, and strip it down to the bare necessities. And I promise that after moving many files out of the bundle, everything still works. While looking for ways to move things out of the bundle, I will discuss some of the more advanced features of bundle design, like prepending configuration, compiler passes and Doctrine mapping drivers. We will end with a very lean bundle, surrounded by a few highly reusable, maximally decoupled libraries.</dd>
</dl>

[Slides](http://slideshare.net/matthiasnoback/the-naked-bundle-symfony-live-london-2014)  
[Video](http://youtu.be/nX3sBQhqfPs)

By [Matthias Noback](https://connect.sensiolabs.com/profile/mnoback)  
![github](icon/github.png) [@matthiasnoback](https://github.com/matthiasnoback)  
![twitter](icon/twitter.png) [@matthiasnoback](https://twitter.com/matthiasnoback)  

---

## How Kris Builds Symfony Apps

<dl>
  <dt>Description</dt>
  <dd>You've seen Kris' open source libraries, but how does he tackle coding out an application? Walk through green fields with a Symfony expert as he takes his latest "next big thing" idea from the first line of code to a functional prototype. Learn design patterns and principles to guide your way in organising your own code and take home some practical examples to kickstart your next project.</dd>
</dl>

[Slides](http://www.slideshare.net/kriswallsmith/how-kriswritessymfonyappslondon)  
[Video](http://youtu.be/W8MOIOyPbmM)

By [Kris Wallsmith](https://connect.sensiolabs.com/profile/kriswallsmith)  
![github](icon/github.png) [@kriswallsmith](https://github.com/kriswallsmith)  
![twitter](icon/twitter.png) [@kriswallsmith](https://twitter.com/kriswallsmith)  

---

## One Commit, One Release. Continuously Delivering a Symfony Project

<dl>
  <dt>Description</dt>
  <dd>For the last few months we've been implementing a Continuous Delivery pipeline for the redesign of Time Out. In this talk I will demonstrate a real life example of what our pipeline looks like, the different tools we've used to get it done (phing, github, jenkins, ansible, AWS S3, ...), and peculiarities for PHP and Symfony2 projects. Most importantly, I'll be looking at things we've struggled with along the way and the lessons we've learnt. </dd>
</dl>

[Slides](http://slideshare.net/loalf/one-commit-one-release-continuously-delivering-a-symfony-project-39566087)  
[Video](http://youtu.be/sPcmIDV_r4g)

By [Javier López](https://connect.sensiolabs.com/profile/loalf)  
![github](icon/github.png) [@loalf](https://github.com/loalf)  
![twitter](icon/twitter.png) [@loalf](https://twitter.com/loalf)  

---

## Sylius - eCommerce for Symfony2 Developers

<dl>
  <dt>Description</dt>
  <dd>Introduction to Symfony powered eCommerce framework for PHP. What is Sylius and how can it help all Symfony developers with their next online selling platform? How Sylius leverages Symfony2 flexibility to provide next-generation, online-selling platform and why Symfony is the best choice for modern eCommerce.</dd>
</dl>

[Slides](https://speakerdeck.com/pjedrzejewski/sylius-e-commerce-for-symfony-developers)  
[Video](http://youtu.be/HX27erOkqW4)

By [Paweł Jędrzejewski](https://connect.sensiolabs.com/profile/pjedrzejewski)  
![github](icon/github.png) [@pjedrzejewski](https://github.com/pjedrzejewski)  
![twitter](icon/twitter.png) [@pjedrzejewski](https://twitter.com/pjedrzejewski)  

---

## Mocks Aren't Stubs, Fakes, Dummies or Spies

<dl>
  <dt>Description</dt>
  <dd>If you're familiar with testing your PHP code, there's a good chance you've been using mock objects: But are they really mocks? The term mock object is commonly used in the PHP community to describe both Mocks and Stubs, but they do behave differently, and more importantly, they should be used differently. Test double is used as the general name for objects, procedures or systems used to replace real components, purely for testing purposes. As the title of the talk implies, mock objects aren't the only kind of test doubles out there. This talk will cover the basic differences between the test doubles you might use and when or what you might utilise them for, including practical examples using several of the most popular PHP test double libraries. We'll then go into a little bit more detail on how the way you approach the design of your software can lead to the use of the different types and the trade-offs between those approaches.</dd>
</dl>

[Slides](https://speakerdeck.com/davedevelopment/mocks-arent-stubs-fakes-dummies-or-spies-symfonylive-london-2014)  
[Video](http://youtu.be/6_r3AzRg1HM)

By [Dave Marshall](https://connect.sensiolabs.com/profile/davedevelopment)  
![github](icon/github.png) [@davedevelopment](https://github.com/davedevelopment)  
![twitter](icon/twitter.png) [@davedevelopment](https://twitter.com/davedevelopment)  

---

## Converting a Website to a New Religion: Symfony

<dl>
  <dt>Description</dt>
  <dd>When you have a huge website and you decide to make the move to Symfony, it can be a very daunting prospect of having to rewrite your entire website on top of the Symfony framework. We\u2019ll go through how this can be done as smoothly as possible with a large enterprise size website, piece by piece, deploying your site every step of the way, following along with the example of phpBB, an organisation going through this process, to discover the right and wrong way to go about it and the many tools you can use on enterprise-scale Symfony applications to help along the way.</dd>
</dl>

[Slides](https://speakerdeck.com/michaelcullum/converting-a-website-to-a-new-religion-symfony)  
[Video](http://youtu.be/xF64DNmai_U)

By [Michael Cullum](https://connect.sensiolabs.com/profile/unknownbliss)  
![github](icon/github.png) [@unknownbliss](https://github.com/unknownbliss)  
![twitter](icon/twitter.png) [@unknownblissmc](https://twitter.com/unknownblissmc)  

---

## Decoupling with Design Patterns and Symfony2 DIC

<dl>
  <dt>Description</dt>
  <dd>How do you create applications with an incredible level of extendability without losing readability in the process? What if there's a way to separate concerns not only on the code, but on the service definition level? This talk will explore structural and behavioural patterns and ways to enrich them through tricks of powerful dependency injection containers such as Symfony2 DIC component.</dd>
</dl>

[Slides](http://slideshare.net/everzet/decoupling-with-design-patterns-and-symfony2-dic)  
[Video](http://youtu.be/UIDlOV40xCY)

By [Konstantin Kudryashov](https://connect.sensiolabs.com/profile/everzet)  
![github](icon/github.png) [@everzet](https://github.com/everzet)  
![twitter](icon/twitter.png) [@everzet](https://twitter.com/everzet)  

---

## Decorating Applications with Stack

<dl>
  <dt>Description</dt>
  <dd>Stack is a convention for composing HttpKernelInterface middlewares. By following Stack's conventions you can add behavior and functionality to any application based on Symfony's HttpKernelInterface. This means Stack middlewares can be applied to Silex, Laravel 4, and Drupal 8 applications in addition to any other HttpKernelInterface based application. Learn the conventions, see community middlewares, and find out how to get started with Stack.</dd>
</dl>

[Slides](https://speakerdeck.com/simensen/decorating-applications-with-stack-symfony-live-london-2014)  
[Video](http://youtu.be/fusN0yhEB7c)

By [Beau Simensen](https://connect.sensiolabs.com/profile/simensen)  
![github](icon/github.png) [@simensen](https://github.com/simensen)  
![twitter](icon/twitter.png) [@beausimensen](https://twitter.com/beausimensen)  

---

## Closing Keynote: Doing Everything with Nothing: Ephemeralization in the Cloud

[Slides](https://speakerdeck.com/dzuelke/doing-everything-with-nothing-ephemeralization-in-the-cloud)  
[Video](http://youtu.be/AZ2kydtUilc)

By [David Zuelke](https://connect.sensiolabs.com/profile/dzuelke)  
![github](icon/github.png) [@dzuelke](https://github.com/dzuelke)  
![twitter](icon/twitter.png) [@dzuelke](https://twitter.com/dzuelke)  

---
---
---

# Lightning Talks

## PHP & Heroku

~~Slides~~  
[Video](http://youtu.be/JZ0ztHmul-8)

By [David Zuelke](https://connect.sensiolabs.com/profile/dzuelke)  
![github](icon/github.png) [@dzuelke](https://github.com/dzuelke)  
![twitter](icon/twitter.png) [@dzuelke](https://twitter.com/dzuelke)  
