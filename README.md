# CourseResources
Continuously updated course profiles and catalogs of SHSID's curriculums for curriculum services. 
- Written in a custom JSON DSL with full-line comment support.

### [`Courses.gpa`](./Courses.gpa)
- The current course profile used by [GPA Calculator](https://github.com/willuhd/GPA-Calculator-3) (iOS and web), **last updated Apr 1, 2026**
- Download the iOS app [here](https://apps.apple.com/us/app/gpa-calculator-by-michel/id1540111715), or use the [web version](https://gpa.indexademics.com)!
- Reworked to the latest curriculum, including new features like rule checking and configurable score maps

### [`Courses.catalog`](./Courses.catalog)
- The catalog file used for SHSID's [interactive course planner](https://github.com/Ziqian-Huang0607/SHSID_CC_Advisor) (use it [here](https://cc.indexademics.com)!)
- Prerelease! For the latest experimental changes visit my fork [here](https://github.com/WillUHD/SHSID_CC_Advisor)

### How this works
- The client (iOS/serverless web) will download the continuously updated configuration file from here to use in its own UI.
- This way the app's physical code doesn't have to be updated. Only the course profiles have to, and the resources will automatically be updated by the app. This mainly streamlines development for course tools as the course catalog may change much more frequently than these tools (if at all).
- I'm the primary maintainer of these course configurations and this repository serves as the hosting point for all of them. They may contain contributions made by many people, credits given as-is in the files themselves (in a credits section or commented). For future SHSID course profile projects that need hosting, adding to this repository is recommended over making another one. 

### View the resources
- For production (eg. iOS/web GPA Calculators), the EdgeOne mirrors are used. This makes the content accessible worldwide, including mainland China.
- `Courses.gpa` as raw [here](https://raw.githubusercontent.com/WillUHD/CourseResources/refs/heads/main/Courses.gpa), gh-proxy mirror [here](https://edgeone.gh-proxy.org/https://raw.githubusercontent.com/WillUHD/CourseResources/refs/heads/main/Courses.gpa)
- `Courses.catalog` as raw [here](https://raw.githubusercontent.com/WillUHD/CourseResources/refs/heads/main/Courses.catalog), gh-proxy mirror [here](https://edgeone.gh-proxy.org/https://raw.githubusercontent.com/WillUHD/CourseResources/refs/heads/main/Courses.catalog)
