# Tutorial Structure

With all types of tutorials, there are a number of elements that should be considered:

- The title

- The introduction

- Prerequisites

- Steps and Commands

- Conclusion

- Optional: Troubleshooting

### The Title

The title of the tutorial should be as specific and descriptive as possible. It should cover the overall goal of the tutorial and the tools being used. Think of the title as the shortest possible summary of your article.

### The Introduction

Each tutorial needs an introduction. This section should describe both what the tutorial will be about, the goals of the tutorial, and the benefit to the reader of completing the tutorial. The benefit to the reader should be covered explicitly — why would reading tutorial help them?

### Prerequisites

The prerequisites section is incredibly important as this will define the approximate knowledge level of the tutorial reader. When you are writing the tutorial, consider all of the components that go into the tutorial and what you will and will not cover in the piece. When in doubt, you should always opt on the side of including more, but there are many times when such an approach may not be useful. There are two types of tutorial prerequisites.

- Tool prerequisites: These are the tools, configurations, products, that individuals need to have installed or set up prior to going through the tutorial. If the tutorial doesn’t cover how to install or get set up with a specific tools that it uses, it should be highlighted in the prerequisites section. If Prisma has a tutorial that educates people on how to accomplish that task, you should link to it, otherwise do your best to link to the related documentation on the tool’s homepage. If neither of these are available, try to find the associated documentation on established tutorial websites such as DigitalOcean or FreeCodeCamp. You should try to avoid linking to individual blogs or

gists, as those can change or disappear over time.

- Knowledge prerequisites: Knowledge prerequisites define the concepts that readers need to know and understand to successfully go through the tutorial. These concepts are usually things not explicitly related to the tutorial, but may be something that the tutorial builds on.

For example, if apollo client is being used in the piece, it may not be the core of the article, but understanding how to use it may be important to completing the tutorial.

When writing up these prerequisites, you do not necessarily need to link out to specific documentation, but if there are articles you think that you think the reader would find helpful as background material, feel free to link to those as well.

### Steps and Commands (for exemplar and procedural tutorials)

The steps in Prisma tutorials in exemplars (as relevant) and procedural articles all have two functions: to educate the reader and to give them a concrete step to undertake. Each tutorial step should have background information as to why the reader should be making the suggested changes and also include the code itself that is relevant to them. In order to make articles easily re-readable or skimmable by those who already understand the concepts, the commands themselves should have a “step” element right next to the code. You can see an example of what this looks like below and find the formatting details in the MDX section of this document.

![step formatting](https://prisma-tutorial-images.ams3.cdn.digitaloceanspaces.com/step.png)

### Conclusion

All of the articles should have a conclusion which summarizes what the reader learned in the tutorial and also links out to additional resources. The conclusion is most effective when it also leaves the reader with suggestions of the next steps that they could take or ideas on how they could build on what they just did or learned.

### Optional: Troubleshooting

Even in the most straightforward tutorials, individuals can run into issues. Adding further information via the collapsable MDX feature can help readers understand where they may have run into an issue. This helps not just the individuals reading the article, but others who may just be googling for the error.
