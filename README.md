# CSE412 Final Project Template (Idyll)

## Team Members

Hailin Guan, Surabhi Biyani, Rita Kuo, Runjing Li, Gordon An

### Contribution Statements

(Add individual contribution statements here.)

We currently have all the cleaned data uploaded in the "data" folder and static images above. We
will start developing our webpage after some feedbacks.

## Project Proposal Abstract

In this project, we plan to explore the use of clean-energy transportation (including electric vehicles, biking, and walking) and the impact on air quality across the United States, with a focus on Washington. We will look at trends in transportation and air quality individually at first, and then study the correlation between the two topics on a city or county basis. We will construct a narrative-based visualization at which the reader can explore and interact with the data. By doing so, we want to convey our message to readers in a clear way and let them experience the interactivity and draw their own conclusions. With that in mind, we will use interactive techniques such as point selection, brushing and linking, etc. We might compare visualizations side-by-side.

## Getting Started

This template is a starting place for your project. Update the header information to include the relevant details for your project, and then feel free to mix and match the visualization and layout techniques introduced here for your own narrative.

Think about how the narrative structure draws readers into the story you are telling and how the visualizations interact with the text (and with each other). The narrative should help ensure that the page as a whole is greater than just the sum of it's parts. When designing your page, decide on particular layouts that enhance the reader's experience and understanding of the topic.

### Required Software

You must have Node.js installed. You can get it directly from https://nodejs.org/en/.

### Installation

- Clone and open your project repo on your own computer.
- Make sure you have `idyll` installed (`npm i -g idyll`).
- Run `npm install` to install project-specific dependencies.

npm is the node package manager. If you're curious how this works and what the project dependencies are, open up `package.json` to see where these are listed.

You can install custom dependencies by running `npm install <package-name> --save`. Note that any collaborators will also need to download the package locally by running `npm install` after pulling the changes.

### Developing a post locally

Run `idyll` from the command line. Your post will appear at [http://localhost:3000/](http://localhost:3000/). When the server is running, any local change that you make will be deteched and your webpage will auto-update with the new changes. Your local changes will not be visible to your team members until you push the changes to your repository. These changes will not be reflected in the final website unless you run the build script and push the updated docs folder (see below).

### Building a post for production

Run `idyll build`. The output will appear in the top-level `build` folder. To change the output location, change the `output` option in `package.json`.

### Deploying

Make sure your post has been built, then commit the `docs` folder to your project repository. It will be available at [cse412-21sp.github.io/your-repo-name/](). For example, you can view the sample embedded Tableau, vega-lite, and d3 charts at [https://cse412-21sp.github.io/Final-Project-Template](https://cse412-21sp.github.io/Final-Project-Template).

#### Acknowledgements

This template was adapted from the initial Scrollytelling template for Idyll. The code and visualization examples were adapted from the [final project template](https://github.com/cse412-21w/project-demo) created for a previous offering of CSE 412.
