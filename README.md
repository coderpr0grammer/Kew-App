# 🎉 Kew - The Cooler way to Queue 🎉

## 🌟 Inspiration
Looking back at our experiences attending social events, we have realized how people are not able to make the most of their fun. Instead of dancing the night away 💃🕺, they are lined up at the DJ’s booth trying to request a song 🎶. Our goal is to create a seamless way for people to request songs in a way that not only allows them to enjoy their night but also is not overwhelming for the DJ who is trying to satisfy everyone's needs.



## 🎵 What it does
When a user goes on KEW, they are prompted to enter a pin for the party 🎉. With this, they are able to request songs from the DJ. The DJ sees all of the song requests ordered by popularity so that they are able to create a mixtape 📼. If, however, someone really wants their song request to be played, they can pay a $5 fee 💵 to have priority.

## 🛠️ How we built it
We used React and Vite for the front end development and Firebase for our backend infrastructure. We also used the Spotify API and Paybilt API. Spotify holds the largest marketshare meaning most users have Spotify, which was one of the main reasons we used its API. To add, Spotify has a vast library of music 🎧 that can provide users with a better experience. On the other hand, we used the Paybilt API to make it easier for users to pay without having to go through the time and effort of inputting their card information at a party.

<!--## 🚧 Challenges we ran into-->
<!--**Spotify and Paybilt API Integration:**  -->
<!--One of the most significant challenges was familiarizing ourselves with the documentation of the Spotify and Paybilt APIs. It was essential to understand the required parameters, response format, and possible errors to ensure smooth integration.-->
<!---->
<!--Spotify uses OAuth 2.0, requiring users to grant permissions for specific scopes. While Paybilt has its own set of keys and authentication headers. Managing these and ensuring secure storage was a major task.-->
<!---->
<!--Not to mention, the token we would use to make an API call would expire so we would have to check the token was experienced. If so, we would have to prompt the user to sign in again.-->
<!---->
<!--**Time Constraint:** We felt very limited by the time we had. Our project lasted the entirety of the hackathon and it was challenging to finish all of our components in time. We tried to combat this by extensively planning as much as we could and breaking steps up into attainable goals.-->
<!---->
<!--## 🏆 Accomplishments that we're proud of-->
<!--**Using different API's:** One of our proudest accomplishments is our team's ability to step out of our comfort zone and dive headfirst into unfamiliar APIs. This not only expanded our technical knowledge but also enhanced the versatility of our application.-->
<!---->
<!--**Learning curve:** The speed at which our team learned, adapted, and integrated these new APIs into our application is an accomplishment in itself. We held regular brainstorming sessions, shared resources, and collaborated effectively to understand and leverage the APIs' full potential.-->
<!---->
<!--## 📚 What we learned-->
<!--**Teamwork:** Most of the team is not used to creating such a robust project at a team level because usually we have pursued such projects individually. It was difficult at first as we tended to go into our own bubble and work independently. However, we quickly realized that the lack of communication was putting us in a position where we were not on the same page. We learned that in order to create this project together, we would need to constantly ask questions from one another and update each other. We were able to learn more about each other and find ways to combine our skill sets to create our project.-->

## 🚀 What's next for Kew App
Our next step for KEW would be to incorporate song suggestions that are based on the requests that partygoers made. Once the user requests a few songs, KEW will be able to generate similar songs for the user to consider. This feature will also be present on the DJ’s side as he will also have a list of recommendations that consider the genres and songs that have been requested.

Ever had a long, exhausting day and just ready to let loose? Pumped for semi-formal or prom but the DJ just **DOESN'T DELIVER**? 🎧 Music is crucial for setting the mood and nobody wants to be stuck with classical tunes when there are so many bangers out there. Can't blame the DJ though, how are they supposed to know your taste? That’s where **Kew** steps in! No more waiting in line to request a song—do it via **Kew**. Want your song played sooner? Pay a *small fee* for priority queuing. Enjoy your night, your way, and discover what others are vibing to with insights into the upcoming playlist. 🎵

Instead of wasting time and energy walking to the DJ booth, simply **queue up** your song requests on **Kew**. Your song gets sent straight to the DJ’s screen—from your phone to the dance floor. Stay in the know with upcoming tracks and discover new tunes you'll love. The platform even prioritizes highly requested songs to keep the majority grooving. 🕺💃 Eager to hear your song sooner? **GREAT NEWS**: with **Paybilt**, you can pay between **$3-$5** to bump your song to the top. Not only does this tip the DJ, it also encourages them to mix things up. And if you're with that special someone when the mood for a slow dance hits, pay a small fee for an unforgettable experience. 🌌

## 🛠️ The Process

For this project, we embraced **React.js** for front-end development. With **Vite**, we built a snappy and optimized web application. We also integrated the **Spotify API** for a vast range of music recommendations. 🎤

## 💸 Payment Processing with Paybilt

We're thrilled to have **Paybilt API** onboard, making e-transfers a breeze. **Paybilt** not only simplifies transactions but also aligns perfectly with our audience—students who prefer a hassle-free payment method without the need to enter card details for small payments. A big shoutout to **Paybilt** for making our project more user-friendly! 🥳

## 📚 Stack

- **React**
- **Vite**
- **Paybilt API**
- **Spotify API**
- **Google OAuth**
