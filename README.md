[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)



# ProsumerSense

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)


## Project summary

### The issue we are hoping to solve

Current housing practices lack environmental optimization, resulting in unsustainable resource consumption and energy inefficiency. Traditional housing practices result in substantial ecological impact, resource wastage, and energy inefficiency. ProsumerSense addresses the urgent sustainability challenges of housing, aiming to optimize environmental parameters, energy consumption and grid optimization. It leverages AI, IoT, and advanced technologies to revolutionize the sector, making it more ecologically responsible and economically viable. 
[IEEE: "A Framework for Sustainable Housing Practices," DOI: 10.1109/IEEEMagazine.2019.8898192]

### How our technology solution can help

ProsumerSense: Watson AI-driven tech optimizes housing's environment, energy, and grid.

### Our idea

ProsumerSense: Revolutionizing Sustainable Housing through Watson AI-Enabled BIM and Digital Twin Technology

**Real-World Problem:**
The global housing sector is facing a critical challenge in terms of sustainability and environmental impact. Traditional housing practices have led to excessive resource consumption, energy inefficiency, and ecological strain. The construction of over 10 million houses by 2020, with an estimated revenue exceeding $12.6 trillion, underscores the urgency of addressing these issues. Current housing models not only fall short in terms of environmental responsibility but also impact social and economic facets of sustainability.

**Technological Solution:**
ProsumerSense presents an innovative solution that harnesses the power of AI, Building Information Modeling (BIM), and Digital Twin technology to optimize housing's environmental parameters, energy consumption, and grid efficiency. The cornerstone of the ProsumerSense approach lies in its integration of social-physical behavioral sensing, enabling an adaptive and responsive housing ecosystem.

At the heart of ProsumerSense is an AI-enabled BIM and Digital Twin system that creates a virtual representation of a physical house. This model incorporates real-time data from a variety of sources, including IoT-enabled sensors that capture environmental conditions and social-physical behaviors. By fusing these data streams, ProsumerSense generates insights into how a house interacts with its environment and occupants.

**Improvement Over Existing Solutions:**
Compared to conventional housing practices and existing solutions, ProsumerSense offers several key improvements:

1. **Holistic Optimization:** ProsumerSense's holistic approach addresses environmental, social, and economic dimensions of housing sustainability. It optimizes energy consumption based on real-time environmental conditions and inhabitants' behavior, leading to enhanced resource efficiency.

2. **Adaptive Intelligence:** The AI-enabled BIM and Digital Twin technology provide an intelligent, adaptive platform. This allows for real-time adjustments and optimization of a house's parameters, such as temperature, lighting, and ventilation, to create a comfortable and energy-efficient living environment.

3. **Grid Efficiency Integration:** In addition to optimizing individual houses, ProsumerSense considers grid efficiency. By coordinating energy consumption patterns within a neighborhood or community, the system contributes to more balanced grid utilization and reduced strain on energy resources.

4. **Transparency and Accountability:** ProsumerSense enhances transparency and accountability in housing practices. AI Factsheets track and document every step of the machine learning model lifecycle, promoting model governance and regulatory compliance.

5. **Customizable Solutions:** The versatility of ProsumerSense allows for customizable solutions that adapt to different housing types, climates, and resident behaviors. It enables data-driven decision-making and tailoring of solutions to unique requirements.

To delve deeper into the ProsumerSense solution, you can access our comprehensive documentation in the provided source code repository. This repository houses detailed technical specifications, architectural diagrams, code samples, and usage guides, enabling developers, architects, and stakeholders to explore and implement the solution effectively.

In conclusion, ProsumerSense represents a paradigm shift in sustainable housing. By leveraging Watson AI, BIM, and IBM Match 360 with watson Digital Twin technology, and integrating social-physical behavioral sensing, ProsumerSense offers an advanced, adaptable, and comprehensive solution to optimize housing's environmental parameters, energy consumption, and grid efficiency. This breakthrough not only addresses the pressing challenges of today's housing sector but also paves the way for a more sustainable and resilient future.

More detail is available in our [ProsumerSense](https://docs.google.com/document/d/1V7PhQyX1kaqYwXmxbH0YATcUxemS5L2AGMT7DJpKZLo/edit?usp=sharing.)

## Technology implementation

### IBM AI service(s) used

_INSTRUCTIONS: Included here is a list of commonly used IBM AI services. Remove any services you did not use, or add others from the linked catalog not already listed here. Leave only those included in your solution code. Provide details on where and how you used each IBM AI service to help judges review your implementation. Remove these instructions._

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology used in your solution and describe how each component was used. If you can provide links to/details on exactly where these were used in your code, that would help the judges review your submission.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2023 submission.

!![image](https://github.com/ProsumerSense/ProsumerSense/assets/139712652/e2758587-f406-4712-a540-cd96ebffec5c)


## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

_INSTRUCTIONS: You can remove the below section from your specific project README._

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

- **Aaron Masuba** - _Project Lead_ - [Aaron Masuba](https://github.com/Aaron-MSB)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Thanks to our Mentor ***Ms. Jennifer Judge*** for the tremendous insights and guidance.
