# Forum search: removable scope token — media

Recordings and screenshots for the pull request "Forum search: removable scope token, with shake to undo"
(branch `contest/forum-search-unscope-publish`). This branch holds only media; the code is in the PR.
Everything was captured on the iPhone 17 Pro simulator (iOS 26.5) from builds of that branch, in a test
account with fixture chats.

## Videos

| File | What it shows |
|------|---------------|
| `videos/feature-1-demo-vertical.mp4` | 25.6 s edited demo, 9:16 (1080x1920) for watching on a phone: the query `strava` finds nothing inside the "Running Club" forum, one tap on the token shows public channels, bots and the Posts tab, a shake and Undo bring the forum scope back. |
| `videos/feature-1-demo.mp4` | The same cut in 16:9 (1920x1080) for a desktop screen. |
| `videos/feature-1-forum-search-unscope.mp4` | 16 s raw take, light theme: scoped search, tap on the token, global results, shake, Undo. |
| `videos/feature-1-forum-search-unscope-dark.mp4` | 13 s raw take, dark theme, same scenario. |
| `videos/feature-1-before.mp4` | 15 s, the same forum search with the flag off: upstream behaviour, the token cannot be removed. |

## Screenshots

| File | What it shows |
|------|---------------|
| `screenshots/feature-1-token-v2-light.png`, `-dark.png` | Scoped forum search with the badge token, light and dark theme. |
| `screenshots/feature-1-token-v2-light-crop.png`, `-dark-crop.png` | The token enlarged: avatar, badge, cutout ring and cross. |
| `screenshots/feature-1-before-unscope.png` | Scoped search, query `Design`, before the tap. |
| `screenshots/feature-1-after-unscope.png` | After the tap: Global Search section, Posts tab, the query kept. |
| `screenshots/feature-1-undo-alert-light.png`, `-dark.png` | The shake alert "Undo Search in All Chats". |
| `screenshots/feature-1-undo-alert-vs-system.png` | Our alert next to the system "Undo Typing" alert it mirrors. |
| `screenshots/feature-1-after-undo-v2.png` | After Undo: forum scope, token and query restored. |
| `screenshots/feature-1-forum-search-v1.png`, `feature-1-token-v1.png` | Iteration 1 for reference: the earlier capsule token that was replaced by the badge. |
