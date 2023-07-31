# bluejay
This was my DCIM minor capstone project, a website guide all about cyber harassment and how to survive it, including helpful resources and the stories of some notable victims. As a joke, I replicated the design of the Kiwi Farms forum, a site infamous for being labeled by media outlets as "the Web’s biggest community of stalkers".


<h2>Final Report</h2>
<h3>Introduction</h3>
<h4>Goals</h4>

<p>The goals of my project were to make a website that functions as a comprehensive guide for people who are curious about or afraid of cyber harassment. The website was to have information about the different kinds of cyber harassment including cyberstalking, cyberbullying, revenge porn, and so on, as well as the effects of these types of harassment on the lives of individuals, with specific stories to illustrate. The website was to look good on desktop as well as mobile with a catchy name and a design that makes the website easy to use and navigate. I can safely say that the final product does accomplish these goals.</p>

<h4>Purpose</h4>
<p>The purpose of the website is to serve as a guide for people to learn more about cyber harassment and its victims and perpetrators. Its purpose is also to teach people how to avoid becoming a victim of cyber harassment and how to fight cyber harassment if they have already been targeted. The website also contains references to all the sources found through research, information on immediate help, links to helpful digital tools, and other useful resources.</p>

<h3>Deliverables</h3>
<p>The deliverable of the project is a link to a website. This website is a bundle of files and folders that is stored and hosted as a static website on the <em>Github Pages</em> service for free. The name of the repository is “bluejay” because the name of my project is <em>Blue Jay</em>. The link to it is <a href="https://irisoflys.com/bluejay" target="_blank">https://irisoflys.com/bluejay</a>.</p>
<h3>Design</h3>
<p>The design of the website is meant to mirror the design of the forum website <em>Kiwi Farms</em>, which is known in mainstream media as “the web’s biggest community of stalkers” (Pless, 2016). The point of this was to playfully mock that website as like a parody. Using their design but being an anti-cyberstalking resource gives the content some artistic merit. The name of my project is also a callout to <em>Kiwi Farms</em>. The name of my project is <em>Blue Jay</em>, which simultaneously tells victims to Blue Jay to get away from toxic people and also tells harassers to Blue Jay and quit harassing others.</p> 

<p>There are a few changes to the design because the purpose of my website is totally different from the purpose of the <em>Kiwi Farms</em> website. <em>Kiwi Farms</em> is a forum website so they have different options for threads, while <em>Blue Jay</em> is a database-type educational website. The menu is simplified to the six pages on the website: the homepage, a page about the different types of cyber harassment and attacks, a page that answers questions about how to prevent it, a page that answers questions about how to fight it, a page with stories about notable victims of cyber harassment, and, finally, a page with credits and additional resources for users. There are also no sidebar widgets because they are not needed. The things that stayed the same include the color scheme, the homepage, the fonts, and other layout elements like the footer widgets and credits section. I took creative liberties with the list of profiles on the victims page, the items on the resources page (the bullets are a reference to the “greentext” typing on <em>4Chan</em>), and the format on the other pages. Here is the link to the <em>Kiwi Farms</em> website for comparison: <a href="https://kiwifarms.net" target="_blank">https://kiwifarms.net</a>.</p>
<h3>Development</h3>
<p>I knew from the beginning that I would make my project a website that I would build from scratch using HTML, CSS, and JavaScript. This is because I wanted to create another website project for my web development and design career portfolio. I chose my medium because I had recently rediscovered the educational database website <a href="http://SchoolShooters.Info" target="_blank">SchoolShooters.Info</a> by psychologist and school shooter mental health expert Peter Langman, Ph.D., who studies the effects of the 1999 Columbine High School massacre years after. I was moved to cover a similarly impactful topic which applies to the material in the DCIM minor: cyber harassment in online communities. I was heavily interested in researching these cases and communities like <em>Kiwi Farms</em> already, so I chose that as my starting point.</p>
<p>Because only static websites can be hosted on <em>Github Pages</em>, I would not be able to create an actual database. I took advantage of these limitations to come up with a creative solution that I felt could save space, be faster, and be used for future projects. I would use the wonderful <em>Jekyll</em> static site generator to create a modular website with widgets that I could plug and unplug from my website super easily and not have to waste space reusing code. I would use the built-in “posts” feature of <em>Jekyll</em> to store the data of each victim in the YAML header of each entry. This way I would just need to focus on adding new information on files that I just drop into the designated folder, and my code would put it on the page itself. The information included the online alias of the victim, a short summary with embedded links if needed, the date the harassment began, the URL path of the victim’s photo, and a link in the title of the entry that led to either a video or article by or for the victim that gives his or her own account of the abuse.</p>
<p>I used my research about the definitions, preventing, and fighting of cyber harassment in the form of questions and answers. I reckoned that the people coming to my website would have a lot of questions, so I thought this would be the best way to organize this information and make it digestible for readers. My answers include hyperlinks that users can click on to be taken to articles for further context. I also include images and videos on these pages to keep the reader’s attention and provide more information. These images and videos have captions under them to explain what they are.</p>
<p>I used the developer tools of my preferred browser <em>Firefox Quantum: Developer Edition</em> to plan out my styling and layouts before I committed to them. I ran my website while I worked on it using my local server through the <em>Jekyll</em> software and my computer’s command line. Then I could easily drag and drop my folders and files into my online <em>Github</em> repository for the project to update changes to the live version of the website.</p>
<h3>Research</h3>
<h4>About Cyber Harassment</h4>
<p>In my research, I discovered that there were many different types of cyber harassment that I wanted to write about on my website. Cyber harassment itself is the willfully harmful intent to directly or indirectly harm or undermine the character of a person, group, or business through digital mediums including texts, videos, photos, and forums (Nuccitelli). The different types are cyberbullying, cyberstalking, and sexual harassment including revenge porn. Different tactics that are used by cyber harassers are threats, doxxing, DDoS attacks, swatting, and defamation. The most widely known websites with members who are known to engage in these behaviors include <em>Kiwi Farms</em>, <em>4Chan</em>, <em>8Chan</em>, <em>Encyclopedia Dramatica</em>, and <em>Lolcow.farm</em>, although I understand that not every member of these websites is a cyber harasser and that cyber harassment can happen on any platform where there is human interaction including mainstream social media like <em>Facebook</em>, <em>Twitter</em>, <em>YouTube</em>, and so on. However, the lax rules and increased anonymity of the first group of websites I mention facilitate cyber harassment, so it is best to exercise extra caution if you choose to interact with their members.</p> 
<h4>Preventing Cyber Harassment</h4>
<p>One of the important things to avoid online is getting doxxed. Doxxing is when an attacker discovers the real identity of an Internet user and releases it on the Internet without the user's consent in hopes that others will attack the user. To avoid getting doxxed, you must be very careful with what you post online, making sure not to reveal your full name, address, contact information, birth date, employer, and so on publicly or privately to people you do not know or trust. Any clue could be picked up by cyberstalkers to piece together your entire identity, and cyberstalkers sometimes pose as friends to get closer to you. Your IP address is also important to hide because it can be used to pinpoint the exact location of your device and – by extension – you (Dascalescu, 2018).</p>
<h4>Fighting Cyber Harassment</h4>
<p>When it comes to cyberstalking or revenge porn tactics, it is important to take action quickly to save your reputation. According to <em>Forbes</em> contributor Dorie Clark, unless you live in Europe and make use of their "right to be forgotten" laws, you cannot remove search results from <em>Google</em> if they contain bad things about you such as the kind of gossip thrown around by cyberstalkers. However, what helps push these negative results down is using social media more actively in positive ways for your brand. The more websites you have an active profile on, the more spots these profiles will take at the top of search results (Clark, 2015). Additionally, I knew that you could contact websites with available contact information to have the content removed immediately, and once this information was removed, the search results with outdated caches could be removed using <em>Google</em>’s outdated content removal tool. If no contact information is available and the content you want to have removed is serious enough, you can file a report to the FBI and use <em>Google</em>’s web search troubleshooter to have the result removed from results.</p>
<h4>Stories</h4>
<p>There are many different stories that I wanted to share on this website. My favorite part of doing this project was actually learning about how cyber harassment has damaged people and their lives. I thought this would be an important element to include on my website to spread awareness of the seriousness of this problem in our society.</p>
<p>One of the stories I included in the about page cyber harassment page was the revenge porn case of the <em>You Got Posted</em> website. This was a revenge porn website created by Kevin Bollaert where angry exes and strangers could submit nude or pornographic images and videos of mostly women without their consent. On the website there was also an ad to another website by Bollaert where victims had to pay a fee of hundreds of dollars in order to get their material removed (Steinbaugh, 2015). Thankfully the ones responsible for creating these websites were charged and arrested, but this is just one example of the limits people will go to exploit others online for notoriety or even monetary gain.</p>
<p>Another story I included on this page was a horrific example of a swatting prank gone very wrong. Swatting is a dangerous prank common in the online gaming and livestreaming communities in which the perpetrator will call a SWAT team on their victim using nothing but their address and a made-up emergency where peoples’ lives are in immediate danger such as an active shooter situation. In late 2017, a <em>Call of Duty</em> player got angry over the loss of a petty bet and decided to swat somebody he was playing with. This person gave him the address of a family in Kansas that had absolutely nothing to do with the game, and the innocent father of the father was sniped and killed by a SWAT team member (Henderson, 2017).</p>
<p>On the preventing cyber harassment page in the sexual harassment section, I touch upon the tragic story of Amanda Todd, a Canadian teenager who took her life after enduring years of online and real-life harassment. Her cyber harassment began when she was tricked by a stranger on the livestreaming website <em>YouNow</em> to expose her chest. After taking a screenshot and extorting more naked pictures out of her, he sent the illegal material to her family, friends, and classmates on <em>Facebook</em> (CBC News, 2013). Todd’s infamous video talking about the subsequent cyberbullying by classmates and online stalking from her abuser has been viewed 13 million times around the world. To think her trauma may been prevented had she never gone on that website as a minor is an important point I wanted to make with her inclusion on this page.</p>
<p>On the victims page, some of the people I managed to include before the deadline are Julie Terryberry, Chloe Sagal, and Jessi Slaughter. Terryberry was a 19-year-old woman whose suicide was the first to be attributed to cyberstalking from members on <em>Kiwi Farms</em> ([FREE LGBTQPIA], 2016). Chloe Sagal was a transgender indie video game developer who endured cyber harassment from <em>Kiwi Farms</em> members for even longer than Terryberry. This, coupled with her worsening mental health problems, led her to commit suicide by self-immolation (Katzowitz, 2018). Finally, Jessi Slaughter was only in elementary school when she was turned into a “meme” by <em>4Chan</em> members for her inappropriate behavior online. Few people know that her life became a nightmare when nude photos of her were spread to her schools by some of these members, and she still is being cyberstalked to this day (Notopoulos, 2016).</p>
<h3>Conclusion</h3>
<p>Cyber harassment is a scary thing that can happen to anyone and be hard to escape because of the freedom of the Internet and its pervasiveness in our modern world. However, this project has helped me realize that as long as one is living and calm and knows what to do, cyber harassers can not win. In the broader scope of DCIM, I would say that the only potential solution is to educate both would-be victims and perpetrators and address their mental health. Cracking down on websites like <em>Kiwi Farms</em> which have a subculture of cyberstalking would do no good because more like it would spring up. Therefore, I think helping people understand that cyber harassment is not okay and that nobody is safe from it is what could turn some lives around.</p>
<h3>References</h3>

<ul>
	<li>
		Amanda Todd suicide: RCMP repeatedly told of blackmailer's attempts. (2013, November 15). <em>CBC News</em>. Retrieved from https://www.cbc.ca/news/canada/amanda-todd-suicide-rcmp-repeatedly-told-of-blackmailer-s-attempts-1.2427097
	</li>
	<li>
		Clark, D. (2015, January 15). How to protect your online reputation. <em>Forbes</em>. Retrieved from https://www.forbes.com/sites/dorieclark/2015/01/15/how-to-protect-your-online-reputation
	</li>
	<li>
		Dascalescu, A. (2018, January 3). Doxxing can ruin your life. Here’s how (you can avoid it). <em>Heimdal Security</em>. Retrieved from https://heimdalsecurity.com/blog/doxxing/
	</li> 
	<li>
		[FREE LGBTQPIA]. (2016, September 13). Kiwi Farms, the web’s biggest community of stalkers. Retrieved from http://freelgbtqpia.tumblr.com/post/150351805056/kiwi-farms-the-webs-biggest-community-of
	</li>
	<li>
		Henderson, C. (2017, December 30). Los Angeles man arrested after 'swatting' call led to innocent man's death in Kansas. <em>AZCentral</em>. Retrieved from https://www.azcentral.com/story/news/nation/2017/12/30/z-tyler-barriss-los-angeles-man-arrested-connection-swatting-call-led-deadly-police-shooting-kansas/992265001/
	</li>
	<li>
		Katzowitz, J. (2018, June 25). Transgender game developer who’d been bullied online dies by suicide. <em>The Daily Dot</em>. Retrieved from https://www.dailydot.com/irl/chloe-sagal-suicide-cyberbullying-harassment/
	</li>
	<li>
		Notopoulos, K. (2016, March 28). How the internet failed Jessi Slaughter. <em>Buzzfeed News</em>. Retrieved from https://www.buzzfeednews.com/article/katienotopoulos/how-the-internet-failed-jessi-slaughter
	</li>
	<li>
		Nuccitelli, M. (n.d.). Cyber harassment: Internet defamation and internet trolls. <em>iPredator</em>. Retrieved from https://www.ipredator.co/cyber-harassment/
	</li>
	<li>
		Pless, M. (2016, July 19). Kiwi Farms, the web’s biggest community of stalkers. <em>New York Magazine</em>. Retrieved from http://nymag.com/intelligencer/2016/07/kiwi-farms-the-webs-biggest-community-of-stalkers.html
	</li>
	<li>
		Steinbaugh, A. (2015, April 3). Kevin Bollaert sentenced to 18 years over revenge porn site "You Got Posted". Retrieved from http://adamsteinbaugh.com/2015/04/03/kevin-bollaert-sentenced-to-years-over-revenge-porn-site-you-got-posted/
	</li>
</ul>

