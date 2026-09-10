## Suma's Notes

- Looked at how Flutter's declarative UI works - the widget tree gets rebuilt automatically whenever setState() is called, instead of manually updating the UI like in plain JavaScript/HTML
- Compared stateless widgets (like our Text and Card widgets, which never change on their own) versus stateful widgets (like the tab controller, which needs to remember which tab is active)
- Thought about what would happen if dispose() was skipped - the app would hold onto resources it no longer needs, which could slow things down over time
