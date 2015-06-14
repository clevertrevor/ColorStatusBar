# ColorStatusBar
Support class for pre-Lollipop versions of Android that changes the color of the status bar 

Usage:

1. Place the code from Background.xml into the top of your View.
2. Call this line of code from your main Activity `ColorStatusBar.setStatusBarColor(this, findViewById(R.id.statusBarBackground), getResources().getColor(android.R.color.white));`


Credits:
User "itzhar" from StackOverflow.com for the majority of the code from his answer http://stackoverflow.com/a/26215844/2337925
