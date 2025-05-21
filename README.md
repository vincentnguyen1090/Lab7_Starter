Vincent Nguyen, Phiroze Duggal

2. Manually run them locally before pushing code
I think runnning an automated tests manually locally before pushing the code in my Recipe project development pipeline would be the best case. This ensures any bugs and issues are caught before they reach the remote repo and impact other contributors. By doing so, it maintain code quality and not having major breaking changes. Setting up continuous integration will ensure the quality is still there.

3. What is the difference between navigation and snapshot mode?
Snapshot mode analyzes the page in its current state. It's good for finding any accessbility issues like it will return a statement stating the page needs a lang attribute to change the default language for certain readers. It will describe elements that does a good job for accessibility like touch targets has sufficient size and spacing. Navigation mode analyzes a page right after it loads and provides an overall performace metric. On my performace run, I got an 86 on it. It will return aspects that hinder the page's performances such as speed index which means it will tell you the page runs slow. It will give you examples on how to properly size image to save space on the page, etc.

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
We could improve the performace metric on the page by reducing image size which saves more space. WE could also save the image in better compression than PNG or JPEG which saves more space. We could preconnect to required origins which could save time because we want to establish early connections to important dependencies. We can improve our accessbility metric by providing a lang attribute in the html element. This means the text will transform to the reader's default language and not to English if they can't read it. Our webpage should also provide a viewport tag that optimizes the webpage for mobile screensizes and also prevents a 300 ms delay to user input.





