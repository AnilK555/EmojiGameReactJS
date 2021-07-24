### Refer to image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Design Files

- [Extra Small (Size < 576px), Small (Size >= 576px) - output](https://assets.ccbp.in/frontend/content/react-js/emoji-game-sm-output-v2.png)
- [Extra Small (Size < 576px), Small (Size >= 576px) - won game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-won-game-sm-output-v2.png)
- [Extra Small (Size < 576px), Small (Size >= 576px) - lose game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-lose-game-sm-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - output](https://assets.ccbp.in/frontend/content/react-js/emoji-game-lg-output-v2.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - won game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-won-game-lg-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - lose game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-lose-game-lg-output.png)

#### Add Functionality

The app has the following functionalities

- The _Score_ and _Total Score_ for the current game is **0** initially.
- When an **Emoji** is clicked

  - If the clicked emoji is not the same as any of the previously clicked emojis
    then the _Score_ will be increased by **1**.
  - If all the emojis are clicked exactly once

    - The _Game status_ along with _Best score_ and _Play Again_ button will
      be displayed as shown in the **design file (won game)**.
    - The _Best score_ will be equal to the _Top Score_

  - If the clicked emoji is the same as any of the previously clicked emojis

    - The _Game status_ along with _Current score_ and _Play Again_ button
      will be displayed as shown in the **design file (lose game)**.

    - If the score achieved in the current game is higher than the previous
      scores then the _Top Score_ will be updated accordingly.

- When the _Play Again_ button is clicked, then we will be able to play the
  game again.

- The _Play Again_ button will reset the game and _Score_ value but not the
  _Top Score_ value.


> ### _Things to Keep in Mind_
>
> - All components you implement should go in the `src/components` directory.
> - Don't change the component folder names as those are the files being
>   imported into the tests.
> - **Do not remove the pre-filled code**
> - Want to quickly review some of the concepts you’ve been learning? Take a
>   look at the Cheat Sheets.
