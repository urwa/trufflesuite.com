<div class="post-trufflecon-box mb-5">
  **[TruffleCon 2019](https://www.trufflesuite.com/trufflecon2019)** is happening August 2-4 on Microsoft’s campus in Redmond, WA. This year’s event will include 60+ speakers from the blockchain ecosystem, along with hands-on workshops geared toward novice users and expert builders alike. The Truffle team is ramping up for TruffleCon 2019 by writing a daily blog post about everything that’s on our minds. We hope you enjoy and we’ll see you in Redmond!

  <div class="text-center">
    <a class="btn btn-truffle mt-3" href="/trufflecon2019">Get your Ticket for TruffleCon 2019 Today</a>
  </div>
</div>

Have you ever thought about contributing to Truffle? All of us at Truffle really enjoy producing free and open source software, and it is especially fun when many of you in the community contribute. User contributions make life easier for us, make our work more enjoyable by showing that you’re engaged, and often give us a chance to learn from those that offer code to the project. We’d absolutely love any and all developers to contribute to our project. The following are a few ways that you can get involved. 

## Read the contributor guidelines. 

The first step anyone should take before contributing to Truffle is to hop on over to our Github page and [read our contributing guidelines](https://github.com/trufflesuite/truffle/blob/develop/CONTRIBUTING.md). Our contributing guidelines will give you a baseline understanding of how Truffle is built, which tools to use during development, and other useful information to get you started. Make sure to read those guidelines before continuing on in this post. 

## Follow the command flow. 

You’ll see that the contributing guidelines focus on the command flow. This is because at its core, Truffle is a command line tool that processes and runs specific commands on behalf of a user. If you can figure out where a command starts, you can follow its execution to get a better understanding of what Truffle is doing. We recommend choosing your favorite command and following its path through the code. We’d also recommend performing your own local experiments by changing the behavior of a specific command and seeing how it behaves. Don’t forget to read the contributing guidelines above, as it tells you where to get started for each command.

## Change callbacks to Promises. 

Given the lifetime of the project -- over four years! -- Truffle has its share of legacy code. Before Promises became widespread in the Node world, callbacks were used to control the flow of asynchronous code within Truffle. The code was written in a style where a callback function was passed from one method to the next, intended to be executed after everything else had finished running or when an error occurred. Nowadays, many people find this style of code to be abstruse, and hard to understand, and now favor Promises over callbacks. We do too. One of our major tasks over the coming year is to rework our code to favor a Promise-based coding style instead of a callback-based one. We are always interested in receiving PRs that clean up our callbacks and make the code easier to understand for everyone (we love you async/await).


## Start small, and chat with us for larger tasks. 

It can be very overwhelming to begin contributing to Truffle with a big feature. Instead, we recommend going after a smaller, more bite-sized change that will not only make you feel more successful, but can also help you get a better understanding of the underlying code. If you find something trivial, like a documentation error, go ahead and fork the repository, make your changes, and submit a pull request. For something bigger, we like to have a discussion first as our tools support many different use cases and platforms. If you have a great idea for a change that will require significant effort, we recommend filing a GitHub issue with a proposal or contacting us using the channels below. We can layout specs, bounce ideas around, and agree on what’s needed before you dive in. 

## Tackle an issue.

Many of our users submit issues for things that need to be fixed. Sometimes these issues are small bugs that have been able to hide in the cracks. Other times they can be large changes or feature requests that require significant effort to fix. Regardless of your appetite, our [issues list](https://github.com/trufflesuite/truffle/issues) is often a great place to start for people to contribute. Due to the nature of software, you’re bound to find an issue that’s right for you. And even if you don’t think you can fix an issue, confirming that issues exist and giving us extra information can be extremely helpful. Often the biggest factor keeping a sneaky bug alive is information, so validating an issue exists and providing more data can help us squash that bug even faster.

## Contact us.

As always, we’d love to hear your feedback and concerns, as well as answer any questions you have when contributing to Truffle. Feel free to reach out to us on our [Spectrum](https://spectrum.chat/trufflesuite) page, or file an issue on [Github](https://github.com/trufflesuite/truffle/issues). We'd love to hear from you. Happy Truffling!

<div class="post-trufflecon-box mt-5 text-center">
  Get your ticket for TruffleCon 2019 Today

  <div class="mt-3">
    <a class="btn btn-truffle" href="/trufflecon2019">Get your Ticket for TruffleCon 2019 Today</a>
  </div>
</div>