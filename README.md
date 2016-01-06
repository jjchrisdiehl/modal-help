# modal-help
I wish to use a modal window that will load the portfolio post's content instead of generating a separate single.php page.

As you can see in my project files I have set up a custom theme via the TeamTreeHouse Bootstrap to Wordpress course. In this course we took a normal Bootstrap html/css/js example page and modified it so it works as a Wordpress theme. 

My theme 'Portfolio' has a custom post called 'portfolio' that loads a posts gallery found under Example Page > Portfolio Grid w Custom Posts. 

On this page the featured image of each post loads a picture, in this case a group of badge icons, that can be clicked on to view the post content (single-portfolio.php). When a user clicks the post it loads a new page with the content.

Here-in lies the problem. I would prefer to use the Bootstrap modal window (found here http://getbootstrap.com/javascript/#modals) to load the post content (single-portfolio.php) inside a modal window ON the Portfolio Grid page. Basically I do not want the user to leave that page as they browse the content.

I have tried placing the modal code in single-portfolio.php and page-portfolio.php with no luck. I believe the answer is to wrap the 'post loop' with the modal code and pull in each post's content while looping in the posts. 

Any help would be greatly appreciated!
