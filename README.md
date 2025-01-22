# ionModalBug
Minimal project to reproduce a bug with Ion Modal dismissing on iOS

Guess I'll test this, but probably 
1. `git clone https://github.com/chrisjdev/ionModalBug`
1. `npm i`
1. `ionic cap build ios`
1. Run it in Xcode
   
To Reproduce the issue:
1. Tap Open to open the modal
2. Tap You name to focus the text box and bring up the on-screen keyboard
3. Press Confirm to dismiss the modal
   Observe the modal slides down, pauses a moment towards the bottom, and then disappears.
