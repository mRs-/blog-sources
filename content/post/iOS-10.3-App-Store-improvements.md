+++
author = "Marius Landwehr"
date = "2017-01-25T09:07:22+01:00"
title = "iOS 10.3 App Store improvements"
tags = ["AppStore", "Xcode", "iOS"]
draft = false
+++

Wow it's really happening, no more custom rating dialogue that are a harm to the user. No more jumping in the App Store. And hopefully no more **password** typing for a review.

This could be a huge thing even for small apps, it can speed up getting ratings for your app and maybe it's easier to get as a small company more ratings then ever.

## ceveats
Maybe the UI from Apple is clunky and not easy to get for the customer. We all now that the App Store right now is a horrible in user experience.

## implement
The implementation for the requests is pretty easy. If you look into `SKStoreReviewController` there is only one method to call and tahts `requestReview()`.

All we need to do is to call this little bit of code.
```
SKStoreReviewController.requestReview()
```

# App Store Answers
And there is more. We have finally the option to react on review. No more finger pointing from the user on you without a proper reaction. Thanks Android for providing this for us.