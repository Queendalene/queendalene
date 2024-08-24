# I-deployed
# This is my first deployment
# first deployment ID
at1zp755cqvyx2gs2h3aqyc0vwdhlzeux23yvcdh4ul7nu6e235uvxs3uqj07

# Details
using the leo run main 3u32 2u32 command i was able to create my main.aleo file in the playground where i got my code that i pasted on my demo.leo.app/deploy to successfully deploy this program
![Screenshot 2024-08-22 205737](https://github.com/user-attachments/assets/d8fba6f0-dac4-44df-a724-b374b5acd521)
# Second
# Second deploy transaction id
at1x8a4sszvkhvr8nfppjamyxpjredkun6sgakf4vav05qtdugywvqqzmyxkn

# Details
using my playground i ran this command leo run main 3u32 2u32 to build a main.aleo file inside the simple token then i copied the code in the main.aleo and used it to deployon my demo.leo.app/deploy
![Screenshot 2024-08-23 172708](https://github.com/user-attachments/assets/6bb0ceb9-7406-46d5-a62e-23f61d7ddb01)
# Third
# Third deployment Transaction ID
at1uthz0dc6f4wageaclrc5n22z8hwv7akcanhgc2tpmd2a4kzugupq0gwc53

# Details
using the leo run main 3u32 2u32 command i was able to create my main.aleo file in the playground where i got my code that i pasted on my demo.leo.app/deploy to successfully deploy this program
![Screenshot 2024-08-24 171140](https://github.com/user-attachments/assets/7bf328f3-88b7-402e-a997-adbd0ed4d8e9)

# Source Code
program simple_token_cd16a6o.aleo;

record Token:
    owner as address.private;
    amount as u64.private;

function mint:
    input r0 as address.private;
    input r1 as u64.private;
    cast r0 r1 into r2 as Token.record;
    output r2 as Token.record;

function transfer:
    input r0 as Token.record;
    input r1 as address.private;
    input r2 as u64.private;
    sub r0.amount r2 into r3;
    cast r0.owner r3 into r4 as Token.record;
    cast r1 r2 into r5 as Token.record;
    output r4 as Token.record;
    output r5 as Token.record;

}    
I was able to build my main.aleo from the simple token file,then i copied the code, changed the private key to my own private key in the environment and then entered the terminal in the playground and i ran this code format > leo run

combine_hash_owner_receiver <type_your_address>

<type_friend_address> deployed successfully in my demo.leo.app/display
    





<!--
**Queendalene/queendalene** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
