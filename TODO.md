- [X] Use a top-layer root window instead of 'dragging container'
- [ ] Change API to use pasteboard instead of modelObject
- [ ] Send drag metadata such as thumbnail, icon, name over auxilliary pasteboard
- [ ] If drop target doesn't accept drop, don't send the drop to it when dragging ends!
- [ ] Make gesture recognizer survive view disappearing from its superview.
	  We need to be able to navigate away from the drag source during dnd.
- [ ] Make everybody know when a remote app can accept a drag, so we can do
	  cancellation/acceptance correctly at the end of a drag.