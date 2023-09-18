# Cricket-desktop-score-notifier

# Problem Statement:
Cricket enthusiasts often find it challenging to stay updated with real-time cricket scores and updates while working on their desktop computers. To address this issue, we aim to develop a Desktop Cricket Score Alert Application that provides users with timely and convenient access to live cricket scores and match updates without disrupting their workflow.

# do before using the code
install requests library
install toastnotifier

# how this works
The code will first utilize web scrapping techniques to fetch live matches,live score and special events from a well known cricket website.
This is done by the various function namely get current_matches() ,fetch_score(), special_events() using beautifulsoup library of python then for which the request to api for details is done by requests library.
The notification to desktop is given by the toastnotifier library of python.
