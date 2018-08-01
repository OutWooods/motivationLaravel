# What??!

This is the backend of the nuxt project chain I've created. To read more details see here [INSERT LINK]

### So whats this one?
This is the backend, this readme may be out of date. But still should provide a basic explanation. Look at the link above for more detail

This is a motivation, or target tracking site. Essentially, when you meet a target you get to fill in a pixl in a screen. 
Gradualy over time these build up and up as a measure of your success. So you get a satisfying image as you achieve. 
Hopefully also the pixels move and form a mini-universe, with sounds to make it even cooler. 

I felt this was a nice balance as its little enough that you don't just do it 'to get points' (as I find this works 
for a short period of time, but ineffective to build long term motivation to do habits) but also gives you a sense of pride 
over time. It also motivates me to log my goals, which I am not great at, and I know massively increases my ability to meet targets anyway. 

This was heavily influenced by the project (insert link here). As they produced a pretty awesome looking website. I also wanted to learn about gravity.js and javascript sound libraries. 

--- Edit --- 
I also decided structually to try out having an API backend using laravel. The main challenge here is authentication and I've decided to set up a separate MVP over there. You can see that. 

My reasoning for all these design principals, is primarily to further understand the tech that is used at work, but also I really like Vue and want to get to know it better. I also wanted the challenge of planning architecture. Going for an API backend was alsoa way ot opening up the opportunity to make a mobile app for this project too. If I really want it to be a useful productivity tool for me, than this would work well. 

Furthermore Laravel is great, and with the Resources options to send JSON data. It seemed a good choice, both for authentication (with passport) and for ease of use. Admitedly its a bit massive for just an API backend for a small project, but thats not a massive drawback and it leaves options open for how I want to take this project further. 

### Steps to MVP 
Currently everything else is BLOCKED until the backend is working 

(BACKEND WORK)
- [ ] Setup a laravel project
- [ ] Setup MySQL DB with targets (targets have a colour and name)
- [ ] Be able to make requests from Nuxt to Laravel (v. basic)
- [ ] Route for getting all targets
 
-- From this point on, F and B mark what is front and backend work --
- [ ] F Can get targets from DB
- [ ] FB Can add new targets to DB
- [ ] FB Can delete targets 


- [ ] You can't use the same colour more than once 
- [ ] You can only meet a target once a day 
- [ ] You can only add one new target a day 


- [ ] Diagram structure
- [ ] Reflection - are there alternate designs that could have been done? 
- [ ] Write up two articles on how I got there

#### Learning 
How to build an API backend with Laravel 

#### Tech
Laravel
Passport
MySQL

#### How to run

