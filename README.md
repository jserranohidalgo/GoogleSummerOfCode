In this document, you can find a list of ideas that are proposed by the Scala Organisation for [Google Summer of Code 2024](https://summerofcode.withgoogle.com/).

# Application

If you are interested in becoming a contributor on any idea, please reach out to your potential mentor using their email address specified with the project. You can also reach Scala Center at [scala.center(at)epfl.ch](mailto:scala.center@epfl.ch).

If you would like to be a mentor and propose your own idea, please submit a PR editing this file (e.g. see [2023's projects](Past%20years%20ideas/2023.md)), adding your project to the list, following the format of other projects below.

# Rules

You can read the full rules of the program at the following links: [Rules](https://summerofcode.withgoogle.com/rules), [Terms and Conditions](https://summerofcode.withgoogle.com/terms/contributor), [Help](https://summerofcode.withgoogle.com/help).

And here are the requirements for the potential contributor's proposal: [Writing a proposal](https://google.github.io/gsocguides/student/writing-a-proposal).

However, here are some rules that we'd like to emphacise since they are not visible enough at the above links:

- The program is geared towards beginners first and foremost. It is intended to **be a learning experience** for people at the very beginning of their careers. It is also intended to **give an opportunity** to people who would otherwise not have one. It is NOT a freelance job. Therefore, when making an acceptance decision on a potential contributor, we will prioritize disadvantaged backgrounds and contributors at the very beginning of their careers.
- **IMPORTANT - EPFL Students**: Please note that, according to GSoC rules, there are restrictions on accepting students from an organization's host university. For Scala Center, the host university is EPFL. We can only accept up to 1 student from EPFL, so please take it into account if you're studying at EPFL and consider applying.

# Project Ideas

## Doodle Canvas

|Title                   |Doodle Canvas|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle/|
|Brief Description       |Doodle is a library for 2D graphics. It has good support for producing structured images, but sometimes you just want to blast pixels onto a screen. This project aims to add support for that.|
|Expected Outcome        |A Doodle algebra or algebras that support writing pixels, and probably lines, circles, and other shapes, directly onto the screen.|
|Prerequisites           |Basic Scala knowledge|
|Ideal Prerequisites     |Some understanding on tagless final style.|
|Expected Difficulty     |Easy – straightforward task, path for execution visible right now, very little uncertainty|
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
|Co-mentor               | |



## Doodle Bitmap Convolutions

|Title                   |Doodle Bitmap Convolutions|
|------------------------|-|
|Link to Project         |https://github.com/creativescala/doodle/issues/94|
|Brief Description       |Add support for bitmap convolutions to Doodle. The link has more, including a Github project laying out the steps.|
|Expected Outcome        |Working code and documentation.|
|Prerequisites           |Some Scala knowledge.|
|Ideal Prerequisites     |Basic knowledge of bitmap convolutions, some understanding of tagless final.|
|Expected Difficulty     |Easy – straightforward task, path for execution visible right now, very little uncertainty|
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noelwelsh), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com))|
|Co-mentor               | |

## Generate Scala Documentation website with Scaladoc

|Title                   |Generate Scala Documentation website with Scaladoc|
|------------------------|--------------------------------------------------|
|Link to Project         |https://github.com/scala/docs.scala-lang/|
|Brief Description       |Scaladoc for Scala 3 has a modern UI and is developed to render static websites. We would like to use it to replace Jekyll in rendering the documentation website.|
|Expected Outcome        |We would like a MVP of the website, generated via Scaladoc. We'd need to add support for some Jekyll features such as `include`, and our custom tabs liquid extension.|
|Prerequisites           |some Scala knowledge|
|Ideal Prerequisites     |familiarity with Jekyll, fundamentals of CSS and JS|
|Expected Difficulty     |Medium - We mostly expect pure engineering to bring in the needed Jeykll features, which can be tested on the present documentation sources. As a stretch goal the participant may want to work on styling the pages, create a plug-in system for Scaladoc, or work on incremental documentation builds.|
|Expected Time Commitment|Large project – 350 hours|
|Mentor                  |Jamie Thompson (GitHub: [@bishabosha](https://github.com/bishabosha), Email: [jamie.thompson@bath.edu](mailto:jamie.thompson@bath.edu)) |
|Co-mentor               | |

## Dotty-cps-async:  support for extensible effect stacks.

|Title                   |Support for extensible effect stacks in dotty-cps-async|
|------------------------|-|
|Link to Project         |https://github.com/rssh/dotty-cps-async|
|Brief Description       |Add support for effect stacks into dotty-cps-async.|
|Expected Outcome        |Project module with working code and documentation for users and effect stack providers.|
|Prerequisites           |Some Scala knowledge|
|Ideal Prerequisites     |Basic knowledge of functional programming and understanding of effect stacks|
|Expected Difficulty     |Medium – path for execution visible right now, but possible high variations of efforts depend of unknown technical details|
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Ruslan Shevchenko (GitHub: [@rssh](https://github.com/rssh), Email: [ruslan@shevchenko.kiev.ua](mailto:ruslan@shevchenko.kiev.ua))|
|Co-mentor               | |

## Scala CLI: scripting protocol

|Title                   |Scripting protocol for Scala CLI|
|------------------------|--------------------------------|
|Link to Project         |https://github.com/VirtusLab/scala-cli|
|Brief Description       |Extend Scala CLI with a scripting protocol that can be used to e.g. create source generators. (building on Bloop's built-in support) |
|Expected Outcome        |You can build a Scala CLI project that will run a source generator (e.g. Protobuf or Smithy). Configuration of script is handled via directives or CLI args, script itself is a self contained scala cli project executed with main method.|
|Prerequisites           |Some familiarity with Scala, understanding of serialization|
|Ideal Prerequisites     |Familiarity with Bloop and Scala-CLI, passion for developer tooling|
|Expected Difficulty     |Medium - protocol needs to expose metadata that is compatible with Scala CLI, and to be extensible in the future (core components are already done, such as Bloop integration) |
|Expected Time Commitment|Medium project – 175 hours|
|Mentor                  |Jamie Thompson (GitHub: [@bishabosha](https://github.com/bishabosha), Email: [jamie.thompson@bath.edu](mailto:jamie.thompson@bath.edu)) |
|Co-mentor               | |

## Scaladex: new artifact page

|Title                   |New artifact page in Scaladex|
|------------------------|--------------------------------|
|Link to Project         |https://github.com/scalacenter/scaladex|
|Brief Description       |Add a new page in Scaladex to browse through the list of all artifacts of a project. See full description in [scalacenter/scaladex#1337](https://github.com/scalacenter/scaladex/issues/1337)|
|Expected Outcome        |We can deploy the new version of Scaladex where it is possible to browse through the artifacts of a project by their names.|
|Prerequisites           |Some familiarity with Scala and SQL. Basic knowledge about HTML and CSS.|
|Ideal Prerequisites     |Familiarity with Scala's `Future`, akka-http, doobie|
|Expected Difficulty     |Medium - most of the implementation can be adapted from the existing code |
|Expected Time Commitment|Medium project – 175 hours|
|spoken Language         |French and English|
|Mentor                  |Adrien Piquerez (GitHub: [@adpi2](https://github.com/adpi2), Email: [adrien.piquerez@epfl.ch](mailto:adrien.piquerez@epfl.ch)) |
|Co-mentor               | |


## Scalafix: `ExplicitResultTypes` for Scala 3

|Title                   |Add Scala 3 support to [`ExplicitResultTypes`](https://scalacenter.github.io/scalafix/docs/rules/ExplicitResultTypes.html)|
|------------------------|--------------------------------|
|Link to Project         |https://github.com/scalacenter/scalafix/issues/1583|
|Brief Description       |At the moment, `ExplicitResultTypes` can only run against source files compiled with Scala 2, as its implementation relies on the Scala 2 presentation compiler. A [2022 GSoC added Scala 3 cross-compilation for all Scalafix modules](https://contributors.scala-lang.org/t/scalafix-cross-compiled-for-scala-3-gsoc-2022/6001), so we can now add and publish an implementation supporting source files compiled with Scala 3, leveraging [the stable Scala 3 presentation compiler API](https://contributors.scala-lang.org/t/stable-presentation-compiler-api/6139), [available in Scala 3.3.3 and later](https://github.com/lampepfl/dotty/tree/main/presentation-compiler/src/main/dotty/tools/pc).|
|Expected Outcome        |`ExplicitResultTypes` can run against source files compiled with Scala 3 (validated by an extensive Scala 3 corpus / test suite & smoke-runs on a couple of major Scala 3 projects). As a side effect, ability for rule authors to write Scalafix rules in Scala 3. As a bonus, potential ability to run, against source files compiled with Scala 3, `ExplicitResultTypes` along with community rules written in Scala 2 and published with TASTy.|
|Prerequisites           |Some knowledge of Scala internals|
|Ideal Prerequisites     |Experience with [SemanticDB](https://scalameta.org/docs/semanticdb/specification.html) and the [Scala 2 or 3 presentation compiler](https://www.chris-kipp.io/blog/an-intro-to-the-scala-presentation-compiler)|
|Expected Difficulty     |Medium - the stable presentation compiler API was added as an effort to upstream the mtags module from the Metals project, which provides a similar feature, so we do not foresee any contribution to the compiler, only integration work|
|Expected Time Commitment|Medium project – 175 hours|
|Spoken Language         |French or English|
|Mentor                  |Brice Jaglin (GitHub: [@bjaglin](https://github.com/bjaglin), Email: [bjaglin@gmail.com](mailto:bjaglin@gmail.com)) |
|Co-mentor               | |


## Sounds of Scala Sampler

|Title                   |Sounds of Scala Sampler|
|------------------------|-|
|Link to Project         |[Sounds of Scala](https://github.com/pauliamgiant/sounds-of-scala/)|
|Brief Description       |Build a basic sampler, extending the current codebase as necessary to support this functionality.|
|Expected Outcome        |The minimum functionality to be able to load samples (e.g from [FreeSound](https://freesound.org/) or other source) and play them back. There are unlimited possibilities for extensions. The most basic features are pitch shifting, looping, and effects such as envelopes, reverb, and distortion.|
|Prerequisites           |Some basic knowledge of digital music and Scala.|
|Ideal Prerequisites     |Some knowledge of Web Audio would also be helpful.|
|Expected Difficulty     |Medium. The basic project is quite simple but extensions have increasing complexity.|
|Expected Time Commitment|Medium project – 175 hours|
|Spoken Language         |English|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noel), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
|Co-mentor               |Paul Matthews (Github: [@pauliamgiant](https://github.com/pauliamgiant/))|


## Sounds of Scala Composable Sound Synthesis

|Title                   |Sounds of Scala Audio Graph|
|------------------------|-|
|Link to Project         |[Sounds of Scala](https://github.com/pauliamgiant/sounds-of-scala/)|
|Brief Description       |Build an audio graph library in Scala, that compiles to Web Audio.|
|Expected Outcome        |Users can specify an audio graph (consisting of sound sources, transformations, and sink) and run it in the browser using Web Audio. Extensions would allow interactivity, such as controlling sounds from keyboard and mouse events, and changing the graph while it is running.|
|Prerequisites           |Some basic knowledge of digital music and Scala.|
|Ideal Prerequisites     |Some knowledge of Web Audio would also be helpful.|
|Expected Difficulty     |Medium. The basic project is quite simple but extensions have increasing complexity.|
|Expected Time Commitment|Medium project – 175 hours|
|Spoken Language         |English|
|Mentor                  |Noel Welsh (GitHub: [@noelwelsh](https://github.com/noel), Email: [noel@noelwelsh.com](mailto:noel@noelwelsh.com)) |
|Co-mentor               |Paul Matthews (Github: [@pauliamgiant](https://github.com/pauliamgiant/))|

## Typelevel Ecosystem

For project ideas relating to the Typelevel ecosystem in the categories of AI/ML, serverless, data streaming, observability, and systems programming, please visit https://typelevel.org/gsoc/ideas/.
