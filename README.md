# RSA [Release Status Analyser]
==============

### Jenkins xfpanel plugin Reloaded
-----------


A one click solution for ALL [ QA engineer, DevOps, CTO ] based on [jenkins/xfpanel](https://github.com/jenkinsci/xfpanel-plugin)
A comprehensive dashboard for feedback of all tests triggered for a build with lot more benefits, 
originally built for serving test feedback needs @ [goibibo.com](http://www.goibibo.com/)


![Alt text](/docs/QuickView-dashBoard.png "QuickView")

### Features
- Nice layout of test jobs feedback [ Any one can understand and infer the release status in a glance ]
- Release info which broke the test [ DevOps Engineer love it]
- Quick links to visit detail report of each build [ Full fledged customised report which shows details about all tests, their data & reason for failure]
- Quick link to visit screenshots of the failed tests [ Dev Engineer love it ]
- Quick link to visit console for debugging the cause [ Test Engineer need it]
And yes off-course, it helps a lot to check test status on all your mobile app versions in one shot, so no more surprises after production !


### Get Started
To add this plugin to your internal jenkins
1. Use plugin
     - [Download](https://raw.githubusercontent.com/p00j4/xfpanel-plugin/master/docs/xfpanel.hpi') directly and upload/deploy plugin file in your jenkins server
     - Or build your own from source [Fork RSA]("https://github.com/goibibo/xfpanel-plugin") 

2. Add 2 keys in build parameters of your test jobs
    - env
    - tagtotest

![Alt text](/docs/jobdef.png)	


### Contributing
Fork the project, make a change, and send a pull request!


### Credits & Inspiration
- Thanks to [Vikalp](https://github.com/vikalp) for the motivation.
- Thanks to [Vishal](https://github.com/vishal24tuniki) & [Raj](https://github.com/rajdgreat007) for consistent support & patience.
- Thanks to [Tilman and all contributors](https://github.com/jenkinsci/xfpanel-plugin) for starting it up :-)





