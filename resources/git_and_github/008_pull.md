# Pull
Alright, now if you have already got your own forked repository of 2024-Academy, next step is to clone it to your local machine, you know how to do it right ? if you forgot then refer back to section 2.

Alright, now if you have already got your own forked repository of 2025-Academy, next step is to clone it to your local machine, you know how to do it right ? if you forgot then refer back to section 2.

Cool, now question remains, how if there are other people that make changes to Daskom-Lab/2025-Academy and then you want to also have those changes in your version which is your_username/2025-Academy ?

You pull it!

Yes pulling here means you get latest changes/version of a repository from the cloud (remote git server such as github).

These are the steps that you can use to do this:

1. add the Daskom-Lab/2024-Academy repository as one of remote source by using this command
    ```
1. add the Daskom-Lab/2025-Academy repository as one of remote source by using this command
    ```
    git remote add original https://github.com/Daskom-Lab/2025-Academy.git
    ```
    You can change `original` to other name such as `uwu` for example :v (just be creative)

2. now then you can pull from that remote source that you have just added before, like this
    ```
    git pull original/main
    ```
    (if you are wondering what is main here, dont worry, we will discuss it in the next section)

Congratulations now you have the newest changes from Daskom-Lab/2025-Academy, but in this case most likely there will be no new changes in Daskom-Lab/2025-Academy since possibly you were just forking from it seconds ago, but keep in mind, this technique will be useful in the later times.
