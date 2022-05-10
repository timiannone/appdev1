
# Tim's F5HW README.md

@timiannone What do you think about these updates?

![MacDown Screenshot](https://github.com/timiannone/timiannone.github.io/blob/master/404-trooper-map.jpg?raw=true)


**WELCOME, LINK TO GITHUB MARKDOWN HELP [github link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).**


## Getting started

[Deployment Instructions](#deployment-instructions) •
[Code Block](#code-block) •
[Links1](#Links1) •
[Links2](#links2)


# Deployment Instructions


AZ-104 has been released. We will continue to monitor this repository in the short term, but please consider moving over to the new labs as soon as possible.

## Emoji Ref
[emoji reference](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
@timiannone :+1: This PR looks great - it's ready to merge! :shipit:


# Large Header

> **THIS IS QUOTED TEXT, LEFTSIDE LINE.**

> **Microsoft is prioritizing cloud resources for Covid-19 support. You can read more here - [Update #2 on Microsoft cloud services continuity](https://azure.microsoft.com/en-us/blog/update-2-on-microsoft-cloud-services-continuity/). There is also an active discussion on the MCT Courseware Forum.**

> **There is a [Lab Recordings and Demos](https://github.com/MicrosoftLearning/Lab-Demo-Recordings) repo with links to videos of labs used in Microsoft Official Curriculum. The intent is to provide Microsoft Certified Trainers an easy way to access a non-audio version recording of hands-on labs used in the portfolio.**



## Medium Header


### Small Header - with bullets

- **Bullet 1 - Bold text** - hidden link [MicrosoftLearning/Docker-Build](https://github.com/MicrosoftLearning/Docker-Build) repository
- **Bullet 2** - text
- **Bullet 3** - plain link <https://microsoftlearning.github.io/AZ-103-MicrosoftAzureAdministrator/>


### Small Header - with lists

* Lists must be preceded by a blank line (or block element)
* Unordered lists start each item with a `*`
- `-` works too
	* Indent a level to make a nested list
		1. Ordered lists are supported.
		2. Start each item (number-period-space) like `1. `
		42. It doesn't matter what number you use, I will render them sequentially
		1. So you might want to start each line with `1.` and let me sort it out


### Small Header - with table
You can align cell contents with syntax like this:

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |



### Code Block:
```

kind: Route
apiVersion: route.openshift.io/v1
metadata:
  name: tim-service-f5hw
  namespace: tim-ns3
  labels:
    app: tim-app-f5hw
  annotations:
    openshift.io/host.generated: 'true'
spec:
  host: tim-service-f5hw-tim-ns3.apps.ocp22.devlab.nt
  to:
    kind: Service
    name: tim-service-f5hw
    weight: 100
  port:
    targetPort: http
  wildcardPolicy: None


```

### Links1

- **Bullet 1** - plain link <https://microsoftlearning.github.io/AZ-103-MicrosoftAzureAdministrator/>

### Links2

- **Bullet 1** - plain link <https://microsoftlearning.github.io/AZ-103-MicrosoftAzureAdministrator/>


