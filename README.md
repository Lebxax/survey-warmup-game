# Survey warm-up game: concept prototype

An independent product concept for Informly (not an existing Informly feature): a short, optional, topic-related mini-game that introduces a survey.

## What it demonstrates
A clickable prototype of the full flow: welcome, mini-game, transition, a 5-question banking survey, and a completion screen. It runs in the browser with no backend. Answers stay in the open tab and are not sent anywhere.

## The problem it addresses
People often skip surveys because they feel repetitive, time-consuming or uninteresting. The concept explores whether a brief, skippable, interactive introduction could make starting a survey feel friendlier.

## Main user journey
1. **Welcome:** "Play a quick game" or "Skip and start survey".
2. **Game:** best of three rounds against a friendly robot, picking one of three cards each round (about 15 seconds). No financial knowledge needed.
3. **Transition:** a short message that depends on whether the player won or lost. The survey is identical either way.
4. **Survey:** 5 questions (multiple choice, rating scales, one optional open question) with progress shown. Each answer opens one lock on the robot's vault.
5. **Completion:** a thank-you screen, with a restart button.

## Design principles
The game is always optional, short, adaptable to other survey topics, and never required to reach the survey.

## What needs testing with real participants
No claim is made that this improves completion rates or engagement. That requires experimental evidence, for example:
- Completion and drop-off compared with a standard introduction (A/B test).
- How many participants skip the game, and whether it feels like an extra barrier.
- Whether the game, the "forfeit" wording or the vault progress changes the answers people give, or feels pushy.
- Whether losing feels playful rather than punishing, and which win/lose odds feel fair.
- Added time, accessibility, and fit across different topics and audiences.
