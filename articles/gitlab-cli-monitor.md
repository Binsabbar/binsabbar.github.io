<!--- #intro --->
_24/09/2020_

## CLI Tool for monitoring Gitlab Pipelines


![Image](https://raw.githubusercontent.com/Binsabbar/gitlab-cli-build-monitor/master/screenshot.png)

During covid-19 and lockdown, I wanted to utilise my time with something interesting. During my day, I needed to track multiple projects build status for over 50 projects. It was hard and time consuming. Sometimes I forget to check, the other time I lose track and focus on my main task. 
<!--- #intro --->

So I wanted something simple that I can glimpse at.I was using Gitlab, and did not provide a Dashboard that dispalyed all pipeline status. So I created a simple cli tool that will monitor and check projects that I am interested in. It is the simplest and fastest thing I could make in such a limited time, while getting value out of it. Also, some people enjoy cli based tools more.

The tools is not very sophisticated, but yet simple enough to use and get value out of it.

The configuration is simple, all you need is a single `YAML` file that looks like that:
```
baseUrl: https://gitlab.com
accessToken: some-token-goes-here
projects: # list of either ID number or full path to project
- groupA/projectA
- userA/projectB
- groupA/projectB
- groupA/projectV
updateIntervals: 50 # in seconds
```

The above will monitor the lists of projects and displays the status of each of them.

The project is still new and it thas its own limitations such as: filtering branches or showing project that failed in the last X minutes. Feel free to contribute to it.

You can find the repo [here](https://github.com/Binsabbar/gitlab-cli-build-monitor) with more details.
