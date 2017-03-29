Patch for the old facebook (accounts) package.

If you have a meteor app running an old version of meteor (prior to meteor 1.4.3?), you probably needs this patch in order for the facebook auth system to work properly.

How to use this package:
1. go to your project's root folder and create a 'packages' folder if you don't have one already.
2. copy the facebook folder provided in this repo inside your 'packages' folder.
3. run your app locally and verify that the facebook accounts system is working properly.

SOURCE: https://github.com/meteor/meteor/commit/873f13d743053fc080b5562dec786784bc52a610
