---
menu: "foot"
title: "Our Addon Fostering Process"
type: "about"
weight: 1
---

We choose to take on the maintenance of an addon, because we find it particularly useful or we see it popular in the community, and there are no comparable alternatives, but the creator has stopped maintaining it. When the addon has gone un-updated for more than six months to a year, or across one or more major addon-breaking changes from the game publisher, then we look to take on its maintenance.

This is a non-issue for addons with explicit open source licenses, but where it gets hairy is with addons where the creator did not include an explicit license or uses the distribution channel's default of "All Rights Reserved." When this happens we put in a good-faith effort to contact the creator to obtain explicit permission via any and all contact channels available.

But sometimes, the creator is completely unreachable. Repeated attempts to contact them go unanswered (or no contact information is available), and the addon remains unmaintained. In those cases, we consider the addon "abandonware" and decide whether to take on the project.

How we make this decision depends on a number of factors, including:

- How valued by the community the addon is
- Whether there's already a comparable alternative, or one close enough and with an open license that we could modify
- The feasibility of creating a new addon with feature parity and a sufficiently different codebase
- The amount of effort required to make a new, comparable addon
- The anticipated response of the original creator, should they return

We consider this process "addon fostering," because when we choose to take on the maintenance of an abandoned project, we're doing so only because the original creator is unreachable and the project would otherwise die. We recognize that these projects are not "ours" and we claim no ownership over them. We are only stewards until such time as the original creator returns or the addon becomes no longer necessary.

### What Is Abandonware?

[Abandonware](https://en.wikipedia.org/wiki/Abandonware) is software that is no longer supported by the creator and the creator no longer enforces their copyright over it. The creator may or may not be known and, if known, may not be reachable. Generally, the latest official version of the software has been rendered obsolete and unusable by changes in things like hardware, operating system support, or (in our case) changes to the host software that break functionality.

## Hey! I'm The Creator Of One Of The Projects You List!

Great! We _want_ to hear from you! Seriously. We have no interest in depriving you of your project and would love to make explicit whatever relationship you chooose. Please <a href="mailto:dreamwalker@shaunagordon.com">drop us an email</a> so we can chat!

### What can you expect from a discussion with us?

To make the conversation go more smoothly, here are our plans for the different scenarios that we foresee.

#### You're Okay With This And Want Us To Continue

Awesome, and thank you! We would love to make that persmission explicit, so that we can distribute the addon more broadly. If you could send us an email that says that -- or update your original repository to include a license, if applicable -- we would greatly appreciate it.

#### You're Okay With It In Your Absence, But Want To Take It Back Over

That's great, too! We've kept the code under source control since we started working on it and maintained continuity from the source control you originally used if available, so that you can see the changes we've made over the life of the project.

If you have an existing Github repository from which we forked the project, we will create a pull request back to your repository and yours will again be the new source of truth for the project. We will also do a knowledge transfer of any workflow changes we've made and explain their purpose. Our repository will become a "contributing fork" -- the purpose will be to send pull requests to your respository and all other pipelines will be shut off.

If you don't have an existing Github repository or are choosing not to host your source on Github, but are using git for your source control, we can arrange a way to set up a shared remote repository instance for the purpose of incorporating our work into your repository.

If you aren't using git for source control at all, we can send you a complete copy of the source code that you can then merge into your workflow however you see fit, or you can download it from the Github repository.

In all cases, we will change our references to the project to point to your project page as the source of truth and make it clear that we are no longer the primary maintainer of the project.

In the cases where our copy of the project is not a Github fork, we will remove the content of the repository and replace it with a note that points users to your project pages accordingly.

*Note:* When we fork a Github repository, we continue to monitor it for the owner's return. If the owner returns and starts responding in the project, we create a pull request with our changes, without waiting for explicit action on the creator's part.

#### You're Okay With What We've Done, But Wish Us To Not Continue And Won't Be Maintaining It Yourself

We're sorry to hear that, but we respect your rights to the project.

We will mark the project as discontinued and update it with a note that you've asked us to stop maintaining it. The repository and previous releases will remain, but no future ones will be created and all release pipelines will be shut off. We will also shut off or lock down Github issues and other methods of contribution as much as we are able to do so.

#### You're Not Okay With What We've Done, And Want Us To Cease And Desist

We're sorry to hear that, but we respect your rights to the project. We will create an archive of the source (including the `.git` folder) and send it to you as a formal gesture of compliance. We will then initiate the following deprecation-removal process:

We will remove all content of the repository and replace it with a message that states that you've explicitly denied permission and that we're complying with that ruling. We will also remove release references from our website and make an update in our blog explaining that we are complying with your request for removal. After approximately six weeks, we will remove the repository entirely and remove any of our remaining links to the repository. The announcement post will remain as record and reference. Our local copies will be deleted and backups will be removed over time per backup rotation/expiration processes.

#### Something Else

Regardless of how you want to proceed, we are willing to work with you. Just <a href="mailto:dreamwalker@shaunagordon.com">send us an email</a> with your thoughts and we can discuss further. At the end of the day, the rights to your project are yours and our priority is working with you.