---
title: "Namecheap Domain to GitHub"
date: 2020-06-17T04:15:40+06:00
hero: /images/posts/Website/namecheap-cover.jpg
menu:
  sidebar:
    name: Custom-Domain-GitHub
    identifier: Namecheap Domain to GitHub
    parent: website-domain
    weight: 200
---

GitHub provides you the chance to host your website via ``username.github.io`` domain. But if you have a custom domain then you can also configure that with GitHub. Today, I'm about to show you how you can add your **Namecheap** domain to GitHub. If you have not any Namecheap domain then you certainly can have for free like I got. Just apply to [GitHub student dev](https://education.github.com/pack) pack and grab one. Okay, first thing first. First you have to create an account in Namecheap. I am assuming that you already hosted your site in GitHub. Now, open your home page in Namecheap. You'll have a page like below. 
</br>

![img1](/images/posts/Website/img1.png)

</br>
Next, click ``manage`` to go to the next page. There, after scrolling a bit, you'll get a section like below. Select ``Namecheap BasicDNS`` from there.
</br>

![img2](/images/posts/Website/img2.png)

</br>
In that page, at the top click to ``Advanced DNS`` tab. You will have some records field to add there. Click the ``Add New Record`` button and Add 5 records like the image below:
</br>

![img3](/images/posts/Website/img3.png)

</br>
Select ``CNAME record`` in the first column of row 1 and select ``A Record`` for the rest. In column 3 of the first row(CNAME record), Instead of ``HabibRh26.github.io``(which is my repo name where I hosted my site), use your's and select ``Automatic`` for column 4 entry. Next, you have to add 4 entries where you have to choose ``@`` for column 2 entry, distinct IP address(for GitHub) for column 3 entry, and ``Automatic`` for the last column. Use the IP addresses same as to me or you can search in Google. Now, you are almost done. Just go to the GitHub Repo where you hosted your site. Select the ``settings`` tab at the top right keep scrolling until you find the box ``Custom domain``. Just add your domain that you got from Namecheap. Don't forget to put ``www`` before the domain. So, It'd be like this for example- www.username.me. Click ``Save`` and ``Enforce HTTPS``. Congratulations! You're done. Go to your domain URL and Enjoy!. Warning! It may take 24 hrs for GitHub to reflect the changes you've made. So, be patient. Be amazed at your personal site. :grin:




