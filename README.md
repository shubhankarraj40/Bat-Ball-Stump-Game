# Bat-Ball-Stump Game

## Introduction:
The Bat-Ball-Stump game is a simple interactive game where the user plays against the computer. The user selects one of three moves: <strong>Bat</strong>, <strong>Ball</strong>, or <strong>Stump</strong>, and the computer randomly chooses one of these as well. The game then determines the winner based on a set of rules.

## Rules:
<ul>
  <li><strong>User wins</strong> if:
    <ul>
      <li><strong>Bat</strong> beats <strong>Ball</strong></li>
      <li><strong>Ball</strong> beats <strong>Stump</strong></li>
      <li><strong>Stump</strong> beats <strong>Bat</strong></li>
    </ul>
  </li>
  <li><strong>Tie</strong> occurs if both the user and computer choose the same move.</li>
  <li><strong>Computer wins</strong> in all other cases where the user's move is defeated by the computer's choice.</li>
</ul>

## Game Flow:
<ol>
  <li>The user makes a choice between <strong>Bat</strong>, <strong>Ball</strong>, or <strong>Stump</strong>.</li>
  <li>The computer randomly generates its move.</li>
  <li>The winner is determined based on the rules above.</li>
  <li>The score is updated, showing the total wins, ties, and losses for the user.</li>
</ol>

## Logic:
<ul>
  <li><strong>Win</strong>: The game compares the user’s and computer's choices, awarding a win to the user if their move beats the computer's.</li>
  <li><strong>Tie</strong>: If both the user and computer choose the same move, the game is a draw.</li>
  <li><strong>Loss</strong>: If the computer’s move beats the user’s, the computer wins.</li>
</ul>

<p>The current score (wins, ties, and losses) is stored in the browser's local storage, so the score is retained between game sessions.</p>

<p>Enjoy playing and improving your score!</p>


![Screenshot (322)](https://github.com/user-attachments/assets/42145dd4-5bc8-4eff-bb53-fe1d310e1b1a)
