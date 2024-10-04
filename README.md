##  MultiBlogs - Multi Authors Blog Project in Django/Python
#### Navigation : [Technology](#technology-used---)--[Setup Local](#how-to-setup-in-windowsmaclinux)--[Project Features](#project-features---)--[Issues](#issues--questions)

  

### Technology Used : -
1. Python Web Framework Django as Backend
2. HTML, CSS & Framework BootsTrap  
3. JS

### Tempaletes Used : -
1. For Frontend, Mundana BootsTrap Blog Templates. 
2. For Frontend User Admin Panel, SB Admin 2 .

#### Download both templates from below : -
1. Frontend Templates [ Mundana Bootstrap Blog ](https://www.wowthemes.net/mundana-free-html-bootstrap-template/).
2. Frontend User Admin Panel [ SB Admin 2 ](https://startbootstrap.com/theme/sb-admin-2).

### How to SETup in Windows/MAC/Linux
1. Clone this Project <code>git clone https://github.com/yeazin/Multi-Authors-advanced-Django-Blog.git </code>
2. Go to Project Directory <code>cd Multi-Authors-advanced-Django-Blog </code>
3. Create a Virtual Environment :-
    * for Windows <code>python -m venv env </code>
    * for Linux/Mac <code>python3 -m venv env </code>
4. Activate Virtual Environment <code>source env/bin/activate </code>
5. Install Requirment Packages <code>pip install -r requirments.txt</code>
6. Migrate Database :-
    * For Windows <code>py manage.py migrate</code>
    * For Linux/Mac <code>python3 manage.py migrate</code>
7. Create SuperUser :-
    * For Windows <code>py manage.py createsuperuser</code>
    * For Linux/Mac <code>python3 manage.py createsuperuser</code>
8. Finally Run the Projects :-
    * For Windows <code>py manage.py runserver</code>
    * For Linux/Mac <code>python3 manage.py runserver</code>

### Project Features : -

1. Dedicated Users Frontend Admin Panel.
2. Frontend __Login/ Register__ System.
3. User`s Sides (Frontend) -
    * Users can register.
    * Users can login/logout.
    * Users can add Posts.
    * Users can Show / Hide Posts.
    * Users can edit posts.
    * Users can Delete Posts.
4. Admin`s Sides (Frontend) -
    * Admins can add posts.
    * Admins can add Categories.
    * Admin can edit posts.
    * Admin can edit categories.
    * Admin can delete Posts.
    * Admin can delete categories.
    * Admin can add users and delete users.
    * Admin can make posts Features.
    * Admin can Approve or Pending posts.
5. Blog Posts Features - 
    * Blog`s Menu shows categories with most posts under them. Highest to Lowest.
    * Posts are showing by Featured,by Recently added,by Categories, by most views count.
    * Only the Active/Approved ,not the pending post, will show.
    * Each Post has Visit Count.
    * Post can be featured or popular by most views counts and comments.
    * Each post has comment features.
6. Has __Subscription System__ to collect Emails for further email marketing.
7. Releted posts by users.
8. Search Facility.
9. Dedicated Single Category page by ( featured, popular, recently added).
10. Social Media Sharing System & Much More.









