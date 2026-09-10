## Tejaswini's Notes
- Reviewed how the app's UI is built as a tree of nested widgets (Scaffold to AppBar/TabBar/TabBarView to individual tab content)
- Looked at why the tab-switching logic needs a StatefulWidget instead of a stateless one, since it has to track which tab is currently active
- Studied the role of TabController and why it needs to be created in initState() and cleaned up in dispose()