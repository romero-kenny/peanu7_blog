---
title: "Programming Studio"
date: 2025-09-05
---
[Programming Studio: How Games Can Better Prepare Software
Engineers]{align="center"}

+-----------------------------------------------------------------------+
| ::: {align="center"}                                                  |
| Kenneth Romero\                                                       |
| *Department of Computer Science*                                      |
|                                                                       |
| \                                                                     |
| *University of North Georgia*                                         |
|                                                                       |
| \                                                                     |
| Dahlonega, Georgia 30597                                              |
|                                                                       |
| \                                                                     |
| <kfrome3062@ung.edu>                                                  |
| :::                                                                   |
+-----------------------------------------------------------------------+

::: {.columns-flow count="2"}
:::

   *Abstract*--- The complexity of modern software poses a significant
challenge for aspiring software engineers, as traditional computer
science curricula often fall short in preparing students to effectively
navigate large systems. This gap arises from the reliance on
conventional teaching methods rather than engaging activity or
project-based approaches that could better stimulate students"
computational thinking. Games, serve as a medium that naturally
cultivates computational thinking, as players grapple with the
intricacies of game mechanics while playing. Drawing inspiration from
game design principles, instructors can create playful learning
environments that promote deeper understanding of course content and
foster the development of computational thinking skills. This paper
proposes a course design that leverages game design to establish such a
playful environment specifically tailored for enhancing computational
thinking, thereby equipping students with the necessary skills for
future coursework and tackling more complex software projects.

  *Index terms*---active learning, project-based learning,
activity-based learning, computational thinking, game design, play
environment

> I think that it's extraordinarily important that we in computer
> science keep fun in computing\[...\] Don't feel as if the key to
> successful computing is only in your hands. What's in your hands, I
> think and hope, is intelligence: the ability to see the machine as
> more than when you were first led up to it, that you can make it more.
>
> --- Alan J. Perlis

Current computer science curricula often fail to equip students with the
skills needed to address the complexity of today's software. An emphasis
on memorization hinders the development of computational thinking that
is essential for success. This approach forces students to repeatedly
relearn material, as they lack opportunities to apply their knowledge.
Consequently, they are ill-prepared for advanced courses that require
programming experience and the practical use of foundational
concepts[@follow_c].

The primary obstacle is embedding computational thinking within the
curriculum. "Computational thinking involves solving problems, designing
systems, and understanding human behavior, by drawing on the concepts
fundamental to computer science."[@comp_thinking] Programming, in turn,
is the application of computational thinking. While curricula centered
on programming have been devised, they often prioritize correctness and
tend to feature relatively small-scale projects, thus failing to fully
embrace computational thinking. To truly cultivate computational
thinking, there must be a shift towards larger-scale projects,
necessitating an educational environment conducive to project and
activity based learning [@guide_teach_cs].

Environments that promote exploration and confidence-building are
needed[@leisure_play]. Classical teaching methods create environments
that obscure the potential of programming and limit exploration. This
stifles students" sense of agency and discourages them from exploring.
Minimizing the tools needed for programming empowers students by showing
them they possess the necessary resources to solve
problems[@guide_teach_cs]. Empowering students to actively evaluate
their understanding, iterate on their skills, and gain confidence in
their abilities[@code_to_learn].

This paper outlines methods for selecting tools and designing courses,
illustrating the creation of a curriculum that fosters computational
thinking through a playful environment.

Video games are often misconstrued when it comes to their potential in
education. The concept of gamification has exacerbated this
misunderstanding by framing games solely as tools for enhancing
engagement in the classroom. However, in reality, games serve as
exemplary environments for nurturing computational thinking skills
[@jblow_vg_edu].

Game developers intricately design complex systems that players must
comprehend to progress. Through the implementation of levels and
mechanics, they construct a series of incremental challenges that
players must navigate. This approach allows players to intuitively grasp
the game's mechanics and continually test and refine their understanding
of its systems. Moreover, certain games, such as *Kerbal Space Program*
for rocket science[@kerbal], *Minecraft* for digital logic [@minecraft],
or *Seven Billion Humans* for algorithms
([\[seven_bil_humans\]](#seven_bil_humans){.ref}), offer immersive
experiences that familiarize players with fundamental concepts rather
than directly teaching them[@zachtronics]. This immersion facilitates
the development of a profound understanding of these concepts at their
core.

<figure>
<p><img src="./figures/seven_bil_humans.png" /></p>
<figcaption><p>A solution to a problem in Seven Billion Human using the
least amount of code</p></figcaption>
</figure>

[]{#seven_bil_humans}

Drawing inspiration from the structure of games, educators can design
learning environments that promote deeper comprehension of essential
concepts. By integrating game-like elements, such as incremental
challenges and immersive experiences, alongside traditional teaching
methods, educators can foster intuitive and active learning while
addressing any misconceptions students may have[@guide_teach_cs].
Through careful selection of tools and the incorporation of playful
projects and problems, play environments can emulate the engaging nature
of games, enticing students to enjoy learning for its intrinsic value
rather than extrinsic rewards [@Moraz_n_2020]
[@game_development_teaching] [@active_discrete_structs].

Through the creation of playful learning environments, computational
thinking can flourish. Establishing a playful environment requires
careful selection of tools and assignments that empower students,
fostering their agency and confidence. This approach encourages
exploration, experimentation, and iteration of knowledge and skills. The
choice of appropriate tools is dictated by the curriculum's objectives.
Just as game developers must adhere to the constraints of their genre
while innovating with mechanics and levels, instructors must similarly
curate and deploy tools and assignments that reinforce the core concepts
of the curriculum. This approach not only cultivates a deeper
understanding of the subject-matter but also nurtures an appreciation
for it by giving rise to an intrinsic want to learn
[@code_to_learn; @jblow_vg_edu].

Tools serve as vehicles for students to actively engage with the
fundamental concepts of the curriculum. Simplifying the complexity of
these tools enables students to direct their focus towards understanding
the curriculum itself, rather than grappling with the intricacies of the
tools[@jblow_vg_edu; @zachtronics]. When tools are easier to grasp,
students are more inclined to believe in their ability to master them,
fostering a sense of agency and confidence. This empowerment fosters
student autonomy in practicing with the tools, thereby providing greater
opportunities for students to develop a personal connection with the
content and deepen their understanding of the concept or computer
science as a whole.

As students develop a personal connection with the material, they become
motivated to explore the concepts more deeply, leading to a heightened
appreciation for them[@code_to_learn]. This intimate familiarity with
the concepts allows for the integration and interweaving of ideas,
fostering a holistic understanding of how the discipline operates as a
cohesive system. Over time, this empowers students to construct a
cohesive framework of concepts in computer science, enabling them to
consistently broaden their perspective on the possibilities within the
field[@guide_teach_cs].

Recognizing the diversity among students" abilities is key to nurturing
computational thinking[@guide_teach_cs]. Assignments should encourage
exploration and iteration, fostering a systemic perspective on concepts.
By building upon prior knowledge and skills iteratively, students gain
confidence and agency in applying these concepts practically. This
approach encourages experimentation, deepening comprehension and
fostering intuitive understanding[@jblow_vg_edu]. Activity and
project-based assignments exemplify this approach, providing practical
engagement within simulated environments. Open-ended tasks allow
students to demonstrate creativity and understanding, instilling an
intrinsic want to learn. This iterative process promotes growth in
confidence and skills, facilitating direct application and fostering a
social dimension as students share discoveries, ideas, or designs with
peers.

The social dimension of play cultivates community, empowering students
and fostering a culture within the environment. Just as games have clans
and sports have clubs, programming has its hacker
communities[@game_jams; @kris_hackathons]. Belonging to such communities
provides extrinsic motivation, as students find value in being part of a
larger group. Community membership also instills a sense of
responsibility and sets expectations, motivating students to explore and
improve their skills[@blow_depth_jam].

Games developers craft an environment that instill an intrinsic want
from the player to continually better their skills and understanding of
the game. Instructors can do the same with play environments by
utilizing activity and project-based assignments and careful choice of
tools. This intrinsic want cultivates a social aspect as students want
to share their ideas and skills to others.

Play environments offer significant benefits to instructors akin to how
game developers iterate on their games for improvement. Instructors can
dynamically adjust courses based on student skills, participating
alongside them to set benchmarks or assist those facing challenges. This
flexibility allows instructors to creatively engage students, enhancing
their learning experience and deepening understanding. Moreover,
instructors can learn from students, much like game developers gather
feedback from players, leading to continuous improvement in course
delivery and effectiveness[@guide_teach_cs; @john_programming].

An activity and project based approach provides instructors with
valuable free time [@leisure_play; @sep_plato], which can be utilized to
enhance the course in various ways. This time can be spent completing
assignments alongside students, potentially turning it into a
competition or an opportunity for instructors to demonstrate their
expertise and build credibility[@guide_teach_cs]. Additionally,
instructors can use this time to experiment with new technologies or
tools to determine their suitability for the curriculum. This
exploration can inspire instructors to gain fresh perspectives on
teaching certain topics and better engage students. Moreover,
instructors can directly assist students who are struggling with
activities or projects by providing guidance, diagrams, or
demonstrations.

Engaging in activities where students take on the role of the instructor
enables a dynamic exchange of
knowledge[@guide_teach_cs; @john_programming]. This allows instructors
to assess students" understanding of the course material and gain
insights into their perspectives on the concepts being taught.
Understanding the effectiveness of teaching methods is essential for
refining course delivery. Moreover, this approach empowers instructors
to learn new teaching methods from students, enhancing the instructor's
ability to convey curriculum concepts effectively and fostering stronger
connections with students. By facilitating this student-as-instructor
dynamic, instructors can better tailor the course to meet students"
learning needs, ensuring a deeper understanding of the material.

Just as game developers engage players to assess game enjoyment and may
also play themselves to enhance skills and build community, instructors
can adopt similar approaches utilizing activity and project-based
assignments. This enables instructors to tailor the curriculum to
students" skills and understanding, fostering deeper comprehension of
advanced coursework while nurturing a supportive learning community
where students can collaborate and develop their understanding alongside
peers and instructors.

This course draws inspiration from several sources: Daniel Zingaro's
*Algorithmic Thinking*[@algo_think], John Ousterhout's *CS 190: Software
Design Studio*[@john_cs190], Jae Woo Lee's course[@follow_c],
hackathons[@kris_hackathons], and game jams[@game_jams]. The assignments
follow an activity and project-based approach.

The course is divided into three sections. The first section, inspired
by Zingaro's work [@algo_think], focuses on competitive programming
problems to assess students" programming proficiency or teach a new
language. The second section, inspired by hackathons[@kris_hackathons],
aims to build students" confidence and provide practice with libraries.
The final section draws inspiration from Ousterhout's
course[@john_cs190] and game jams[@game_jams], particularly Jonathan
Blow's and Chris Hecker's *Depth Jam*[@blow_depth_jam], incorporating
thematic project assignments for iterative work and peer feedback. The
third section encourages exploration of ideas and creativity.

In truth, any language or library can be chosen as long as it aligns
with the course curriculum or the institution's preferred language.
However, one may wish to adapt this course to teach introductory
programming or transition to a different language [@follow_c]. This
course focuses on utilizing play to foster computational thinking, thus
requiring a simple, comprehensive language. *Python*, *Go*, and *C* are
excellent choices due to their rich ecosystems, ubiquity, and simple,
familar syntax, providing an "easy to learn, hard to master" experience
that allows students to accomplish more with less and concentrate on
implementation design.

*Odin*[@odin] is a *C* alternative inspired by *Pascal*, *Go* and
*Python* [@kris_odin], featuring a simple build system, easy
interoperability with *C*, and a rich standard and vendor library. The
base installation of *Odin* provides a battery-included experience for
new students, with a simple syntax for quick learning. This enables a
joyful programming experience with the power of *C*.

*Raylib*[@raylib] is simple library for putting graphics on the screen.
It was originally created for art students to understand the basics of
game programming [@tj_raylib]. Written in *C99*, portable to different
platforms and languages, *Raylib* is a great library to know for
student's or instructor's own future tools, projects or hobbies. The
simplicity enables students to focus on creating their ideas, whereas
the portability allow students to explicitly take their skills to other
languages or platforms.

This section utilizes programming problems from *Advent of Code*
[@advent], focusing on problem-solving rather than algorithms. These
problems are an excellent resource for developing computational thinking
and familiarity with a new programming language. Additionally, they
offer accompanying questions that force students to iterate on their
designs to meet requirements. The class structure comprises three
sections: independent work time, collaborative thinking, and lecture.
During independent work time, students practice computational thinking,
research skills, and proficiency with the programming language.
Collaborative thinking allows students to review each other's code and
explain their reasoning, fostering self-review. Lecture time is reserved
for the instructor to present preferred solutions, emphasizing language
features, recommended libraries, or efficient problem-solving
approaches. Independent work should consume $\frac{3}{5}$ of class time,
with collaborative thinking encouraged for $\frac{1}{5}$. However,
lecture time may overlap with collaborative thinking to emphasize why
the problem was selected. The duration of this course section is
dependent on students" language proficiency, maximum 2 weeks.

<figure id="advent_code">
<div class="rect">
<pre><code>package aoc
import &quot;core:strings&quot;
...
bad_words :: []string{&quot;ab&quot;, &quot;cd&quot;, &quot;pq&quot;, &quot;xy&quot;}

part_1 :: proc(file: ^string) -&gt; (total: int) {
  
  line_loop:
  for line in strings.split_lines_iterator(file){
    for word in bad_words {
      if strings.contains(line, word) {
        continue line_loop
      }
    }
...
</code></pre>
</div>
<figcaption><p>A snippet of <em>Odin</em> code solving <em>Advent of
Code</em> problem: Day 5 of 2015<a href="#fn1" class="footnote-ref"
id="fnref1" role="doc-noteref"><sup>1</sup></a></p></figcaption>
</figure>
<section id="footnotes" class="footnotes footnotes-end-of-document"
role="doc-endnotes">
<hr />
<ol>
<li id="fn1"><p><a
href="https://adventofcode.com/2015/day/5">https://adventofcode.com/2015/day/5</a><a
href="#fnref1" class="footnote-back" role="doc-backlink">↩︎</a></p></li>
</ol>
</section>

Students will learn *Raylib* by creating a simple game, such as
*Conway's Game of Life*. This approach enables them to experiment with
rendering to the screen, capturing user input, and implementing UI
elements. By focusing on continually adding new features to the game
rather than figuring out how to make it, students have the freedom to
explore *Raylib* and personalize their project. This fosters a personal
connection to the game and enhances their understanding of *Raylib*'s
capabilities.

Classes serve as dedicated workspaces for students to collaborate on
their project. They are encouraged to attend to share ideas, showcase
their progress or simply work on their game. While the project has
requirements, they are intentionally vague to foster student creativity.
For example, in the case of the *Game of Life* project, requirements
might include controlling the size of cells and the window, implementing
save states for player creations, adding a UI, and providing game speed
control. Depending on students" programming proficiency, the instructor
may adjust requirements to optimize difficulty to promote learning.
Additionally, programming time allows the instructor to have free time
to pursue their own hobby projects, catch up on work, or work on the
same project alongside students.

<figure id="odin_raylib">
<div class="rect">
<pre><code>package game_of_life
import rl &quot;vendor/raylib&quot;
...
game_draw :: proc(size: int) {
  rl.BeginDrawing()
  defer rl.EndDrawing()
  rl.ClearBackground(rl.YELLOW)
  for &amp;row, y in game_space {
    if y &gt;= size {
      break
    }
    for &amp;space, x in row {
      if x &gt;= size {
        break
      } else if space {
        rl.DrawRectangle(
          i32(x * cell.width),
          i32(y * cell.height),
          i32(cell.width),
          i32(cell.height),
          rl.PINK,
        )
      }
    }
  }
}
...
main :: proc() {
  size := SMALL
  cellsize := game_creator(size)
  game_init(cellsize, cellsize, size)
  
  rl.InitWindow(i32(size * cell.width), i32(size * cell.height), &quot;Game of Life&quot;)
  defer rl.CloseWindow()
  rl.SetTargetFPS(30)
  
  for !rl.WindowShouldClose() {
    game_draw(size)
    game_play(size)
  }
}
</code></pre>
</div>
<figcaption><p>Another snippet of <em>Odin</em> code, but utilizing
<em>Raylib</em> to create an early implementation of <em>Conway’s Game
of Life</em></p></figcaption>
</figure>

This section consists of two parts: the first and second iterations.
During the first iteration, students have two weeks to implement the
Game of Life. Afterwards, students read their peer's code and provide
feedback. With this feedback, students undergo their second iteration,
which will serve as the final product graded by both the instructor and
their peers.

This section of the course adopts the structure of Ousterhout's course,
with a focus on fostering students" creativity in programming rather
than software design. Drawing inspiration from game jams, students are
provided with a theme, mechanic, genre, or application to incorporate
into their project. This approach gives them a main goal while allowing
for exploration, experimentation, and iteration. It serves as an
opportunity for students to enhance their proficiency with the language,
deepen their knowledge of the library, develop computational thinking
skills, and build confidence in their abilities.

Students have four weeks to develop their initial concept, aiming to
produce a finished level that utilizes the core program feature for the
first code review. Subsequently, the following four weeks are dedicated
to iterating on their program based on feedback, similar to the previous
project. However, students are now paired up, allowing them to tackle
more complex projects or achieve a higher level of polish. Each project
should ideally consist of around 1000 - 1500 lines of code per
student[@john_programming], although this is not a strict requirement as
the number may vary depending on how efficiently students express their
ideas.

This section largely mirrors the previous one, providing students with
dedicated time to work and explore while giving instructors flexibility
for personal pursuits. The main distinction lies in affording students
more time to develop a more complex system compared to the previous
project.

The primary drawback of the course is the substantial amount of reading
required by the instructor, which limits its
scalability[@john_programming]. While the first section can be automated
relatively easily, the heart of the course lies in the projects.
Therefore, small class sizes are necessary to conduct the course
effectively, as the instructor aims to avoid overwhelming themselves
with the task of reviewing large volumes of code.

By incorporating game design principles into course development,
educators can craft a playful learning environment by carefully choosing
tools and assignments. This approach benefits both instructors and
students. Students not only deepen their understanding of the curriculum
but also have increased opportunities to apply fundamental computer
science concepts and skills. Activity-based learning establishes the
groundwork by fostering computational thinking through problem-solving
and intentional tool practice, while project-based learning increases
difficulty and complexity, and integrates concepts into a cohesive
system. This allows students to work with larger codebases, collaborate,
review code, and manipulate systems, better preparing them for future
endeavors in a playful learning environment. Allowing students"
ingenuity and mastery to be rewarded through personal goals and desires.

Instructors also reap advantages by having free time to enhance the
course. They can observe students, actively participate in
activities/projects, or experiment with new tools and environments. This
dynamic mirrors the relationship between game developers and players:
developers strive to impart their ideas to players, while players seek
enjoyment and engagement with the tools, environments, and problems
(games) made by developers.
