Greetings!
My name is Roman. I am from St. Petersburg, at the moment moved to Bishkek, Kyrgyzstan.
I am a junior frontend developer, have mastered HTML, CSS, JS, Git. I am studying React and Node.js.
 
What courses have i completed?
First of all I finished "Learning How to Learn" on Coursera, the entire electronic book "Modern Javascript" by Ilya Kantor, finished the HTML Academy workshop, and also the Reat course by
Bogdan Stashuk on Udemy. Rigth now I'm currently attending the RS School course.
 
Why did I decide to study programming?
(this story has far distant beginning) everything started in 1997 when I saw internet for the first time in my life (The Web). It impressed me.
At school we were studying QBasic in computer science class. One day I asked the teacher why we were learning this boring and ugly QBasic. After all, there are so much cool things like websites in HTML, 3D Studio or Corel Draw. The teacher told me, that's not real programming, QBasic is real programming. QBasic killed all my love of programming!
To tell the truth, it wasn't just QBasic's fault, I was a kid, and kids are easily addicted, and there was a whole bunch of games, like DOOM, Diablo on floppy disks.
You know, kids just are  kids. (smile)
 
Why did I decide to go back to learning programming so many years later?
In the past (from 2013 to 2022), I was running an entrepreneurial business. On the business side, I saw a need to optimize work processes,
and how information techology could contribute to it.
I had an E-commerce project, and I wanted to figure out how it worked under the hood. How modern websites are developed, which programming language is used for that?
I was curious, what is JSON, JS, API? Then I figured out about Java Script, about a frontend and a backend. One language allows you to cover the entire development cycle.
At first it was curiosity. Then i fall in love...
 
About the pet project...
I would like to talk about a little pet project and why it's important to me.
As I mentioned before I moved from St. Petersburg to Bishkek. My friends from Russia are big fans of video games.
They asked me to help them pay for their favorite games through Kyrgyzstan. i said, no problem, I'll help.
I started buying the game purchases with a local card, and they transfered money to my Russian card.
And at some point, I got tired of counting conversion percentages and currency exchange rates.
I decided to write a converter, which would send requests to the yahoo finance api, get the latest exchange rate, and calculate the transfer amount including all commissions.
The first implementation was not quite correct.
Every digit in the input field triggered a request to api. For example, if you entered a number of four digits, it was at least four requests plus one if the page had been reloaded.
It doesn't sound right. And there was a free limit of five hundred requests per month. It needed to be fixed.
I decided to make a "smart query", with the date and the exchange rate in the local storage. If the local storage is empty the query puts today's date and exchange rates inside.
Before the next query we check the date. If the date matches with today's date, we use the local storage.
Otherwise, the new date and the new exchange rates will be updated.
So, we reduced the number of requests to the server to one per day.
 
Why this project is important for me?
Because it is first time when my code solves a real problem. It saves time not only for me, but also for my friends. And that's cool! That's awesome!
 
I appreciate you listening to this monologue, I know my accent is terrible. But I'm working on it.
Oh, by the way, I mark study hours every day, including English. I've already accumulated over a thousand and a five hundred hours of study. That says more about my diligence than it does about my intelligence )
Good Luck!

