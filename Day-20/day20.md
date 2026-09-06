# Day 20 — Face Puzzle Game

## Objective

Today's task was to use Claude to generate a complete HTML Face Puzzle Game application and test its core functionality in the browser.

## Application

The generated application allows the user to:

- Capture a photo using the webcam
- Choose puzzle difficulty
- Scramble the captured image into puzzle pieces
- Reconstruct the image through puzzle interactions
- Track time and moves
- Record completed-puzzle results on a leaderboard

Available difficulty levels:

- 3×3 — Easy, 9 pieces
- 4×4 — Medium, 16 pieces
- 5×5 — Hard, 25 pieces

## Testing

I tested the application using a captured photo and selected the **3×3** difficulty.

The puzzle was successfully completed.

### Final Result

| Metric | Result |
|---|---|
| Difficulty | 3×3 |
| Time | 00:54.9 |
| Moves | 18 |
| Correct | 9/9 |
| Result | Solved |
| Leaderboard | Result recorded |

## Features Verified

- ✅ Webcam/photo capture
- ✅ Difficulty selection
- ✅ Puzzle generation from the captured photo
- ✅ Puzzle interaction
- ✅ Timer
- ✅ Move counter
- ✅ Correct-piece tracking
- ✅ Puzzle completion
- ✅ Leaderboard result

The application also displayed a privacy note stating that the photo does not leave the device and that the processing runs locally in the browser.

## Key Learnings

1. Claude can generate a complete browser-based interactive application from a structured prompt.
2. A simple HTML application can combine webcam access with an interactive game experience.
3. Testing the generated application in a real browser is important because generation alone does not guarantee that every feature works.
4. The puzzle successfully tracked multiple game metrics and displayed the final result.
5. The generated interface included multiple difficulty levels and a leaderboard, making the application more engaging than a basic puzzle implementation.

## Evidence

Screenshots were captured for:

- The Face Puzzle application/start screen showing the captured photo and difficulty options.
- The completed puzzle showing the final time, moves, correct count, difficulty, and leaderboard result.

## Conclusion

Day 20 demonstrated how Claude can turn a natural-language application requirement into a functional interactive HTML game.

The generated Face Puzzle application was successfully opened in the browser, tested with a webcam-captured photo, and completed at 3×3 difficulty.

### Day 20 Status: Completed ✅
