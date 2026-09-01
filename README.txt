LIVE STATS + CLEAN PROJECT PREVIEWS

Important changes:
- Codeforces solved count is now calculated live from unique accepted problems.
- Codeforces rating, max rating and rank load live from the official Codeforces API.
- LeetCode solved/easy/medium/hard/ranking load live through same-origin Vercel proxy routes.
- Multiple LeetCode sources are tried automatically for resilience.
- Fallback snapshot is CF 290 solved and LeetCode 227 total / 177 easy / 49 medium / 1 hard.
- Overall Problems Solved automatically becomes LeetCode + Codeforces.
- Tic Tac Toe and Rock Paper Scissors thumbnails were rebuilt without duplicate inner titles/cards.
- Existing CV, social links, mobile menu and /game integration are preserved.

After upload, test on the deployed Vercel URL (not by double-clicking index.html),
because the /live/* proxy routes only exist on Vercel.
