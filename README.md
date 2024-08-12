# ReachInBox-Frontend Assignment Task

## Deployment

**View my deployment on \_\_\_ => [Live Demo](https://bhanu-reachinbox-assignment-6v24upktn.vercel.app/).**

## Overview

This repository contains the code for Reachinbox frontend App using React with Typescript for an assignment given by Reachinbox.

## Technologies Used ( Frontend )

- Typescript
- React
- Tailwind css

## Demo Video :- 
https://www.loom.com/share/d8838ff6b327485b9de229dd19921b75?sid=16090086-3e0c-4cd4-8c42-0b3ef1fa16c4


# How to Run <br/>

   <h2>Installation</h2>
   
   Clone the repository:   ``` git clone  https://github.com/Bhanuprasadgantela14/ReachInbox-Assignment-Bhanu.git``` <br/>
   Navigate to the project directory:   ``` cd reachinbox ``` <br/>
   Install the dependencies:   ``` npm install ``` <br/>
   Start the development server:   ``` npm run start ``` <br/>
   Open your browser and visit:   ``` http://localhost:3000 ``` <br/>

## Features

- Authentication
- Get Emails
- Post (send) Email
- Delete Email

   <h2>Endpoints</h2>
   <h3>All Emails</h3>
   <pre><code>GET {{baseurl}}/onebox/list </code></pre>

   <h3>All Emails from Onebox</h3>
   <pre><code>GET {{baseurl}}/onebox/messages/:thread_id </code></pre>

   <h3>Add Onebox Mail</h3>
   <pre><code>POST {{baseurl}}/onebox/reply/:thread_id </code></pre>

   <h3>Delete Email</h3>
   <pre><code>DELETE {{baseurl}}/onebox/messages/:thread_id </code></pre>

## Usage

- Upon opening the application, the user is presented with the login page once the user clicks on login using google it navigated to one box home page.
- The user can go to mail section where every thing is Implemented and when they type keyboard shortcuts in onebox - “D” should delete. “R” should open Reply box
- Implemented custom text editor (which Add Custom button in editor like “SAVE” and “Variables”)
- Implemented Reply - Clicking on send It will send Reply
- Implemented both - light and dark mode

  # Credits <br/>

  This project was developed by `Bhanu Prasad` as a part of `ReachInbox Assignment`.

   <p>Feel free to explore and integrate these endpoints into your application.</p>
