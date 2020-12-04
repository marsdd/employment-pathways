# Employment Pathway Builder

Welcome to the [MaRS Data Catalyst](https://www.marsdd.com/service/data-catalyst/) employment pathway builder github repository. This pathway tool was built using D3.js. In this repo, you will find the HTML, CSS and JavaScript code used to build this tool. We use labour market information and tree structures to model and represent job adjacency and measures of job demand. 

## Getting Started

Visualisation [HERE](https://marsdd.github.io/employment-pathways/index.html). Select an occupation from the drop down menu to begin building your employment pathway. This will cause a node to appear on the page. By clicking through the nodes, you can explore various neighbouring jobs in terms of their underlying skills. 

### Background & Methodology

MaRS launched [planext](myplanext.com) in July 2019, a career navigation tool to help job seekers navigate the future of work. Since the release of our minimum viable product, we have engaged in beta-testing to understand the experience of job-seekers with planext, identify their pain points and overall compatibility of their needs with what is delivered in planext. The most common feedback received to planext was that users struggled to find their jobs. Choosing a set of job titles to fully represent the workforce is not easy nor is identifying how to move between jobs. The first iteration of planext relies on O\*NET, a US occupation information database describing nearly 1000 jobs. 
 
With the results delivered via this prototype, our focus was on integrating job posting data into our employment pathways model. As job-seekers regularly interact with job posting data, we believe this data will enable users to more easily locate their jobs in planext, as well as provide a more granular set of occupations upon which we can model job distances and build pathways. In our initial effort to provide greater visibility into the availability and change in demand for jobs, accompanying each occupation are measures of job demand. We derive these measures using Vicinity Jobs data, which provides unique insights on the availability and demand for jobs across Canada over time and at various geographic levels. We hope these pathways can be paired with further workplace analyses to enable users to navigate disruptions to work. 
 
This tool is meant to serve as a prototype to test the results from our initial modeling of job adjacency using job posting data. We will be publishing a post about the approach taken to arrive at these results on marsdd.com. Once live, we will link it here. 

### Limitations and Future Research

While these pathway results incorporate a larger set of occupations from which a user can begin their career path, this expanded set of occupations now allows and often recommends occupations with very small barriers to transition. To remedy this, we recommend applying a minimum distance threshold to filter out occupations where a transition is too close to be sensible. Additionally, this model recommends some 'downwards' moves where the recommended occupation does not require any upskilling or retraining. By implementing logic that accounts for experience, training and salary information, we can aim to avoid significant downward movement. 

## License

This work was developed in collaboration with the Ontario Tourism Education Corporation and the Future Skills Center for Project Integrate. We thank our partner and data provider Vicinity Jobs Inc. for engaging with us throughout the project. 

This visualization is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


